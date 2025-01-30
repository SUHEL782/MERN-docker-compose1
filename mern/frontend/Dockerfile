
FROM node:18.9.1

# Set the working directory
WORKDIR /app


COPY package.json .


RUN npm install


EXPOSE 5173


COPY . .


CMD ["npm", "run", "dev"]
