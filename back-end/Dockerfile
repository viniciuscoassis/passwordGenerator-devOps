FROM node 

WORKDIR /src/usr

COPY . .

EXPOSE 5000

RUN npm i
RUN npm run build
RUN npx prisma generate

CMD [ "npm", "start" ]