FROM node:14  
# react için kullanılan image
# Create app directory app için bir directory
WORKDIR /app

# bizim client içinde bulunan json filelarimiz
COPY package*.json ./
# pakey yöneticisi yarn. 
RUN yarn install

# copy all files into the image
COPY . .

EXPOSE 3000
# uygulamayı run etme
CMD ["yarn", "run", "start"]