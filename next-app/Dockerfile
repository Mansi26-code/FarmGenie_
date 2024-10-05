<<<<<<< HEAD
FROM node:16
=======
FROM node:18
>>>>>>> 31321a7f6224e7d61b76d54baedbfcfbb28db89b

WORKDIR /next-app

COPY package*.json ./
<<<<<<< HEAD

RUN npm install

RUN npx prisma generate

=======
COPY prisma ./prisma


ENV DATABASE_URL="postgresql://swataswayamdash:Dcnhf1IajsW5@ep-gentle-math-a5z04t41.us-east-2.aws.neon.tech/farmgenie?sslmode=require"


RUN npm install
RUN npx prisma generate


>>>>>>> 31321a7f6224e7d61b76d54baedbfcfbb28db89b
COPY . .

RUN npm run build

<<<<<<< HEAD
=======
EXPOSE 3001

>>>>>>> 31321a7f6224e7d61b76d54baedbfcfbb28db89b
CMD ["npm", "run", "start"]