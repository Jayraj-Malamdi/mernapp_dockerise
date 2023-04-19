FROM node:14-alpine

WORKDIR /trainee_backend

# RUN cp ./package.json .

COPY package.json ./

RUN npm install

COPY . .    

#ENV DB_USERNAME=jayraj
#ENV DB_PASSWORD=jayraj123
ENV PORT_NUMBER=8000

#EXPOSE 8000
EXPOSE ${PORT_NUMBER}

CMD ["npm" , "start"]