FROM node

WORKDIR /app

COPY . .

RUN npm install 

RUN npm run build

EXPOSE 4000

CMD ["npm", "run", "start:dev"] 