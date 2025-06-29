FROM node:20-slim
RUN mkdir /app 
WORKDIR /app
ADD https://expense-builds.s3.us-east-1.amazonaws.com/expense-backend-v2.zip .
RUN npm install
ENV DB_HOST="mysql-exp"
CMD ["node", "index.js"]