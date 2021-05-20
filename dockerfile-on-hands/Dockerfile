#A partir de l'image de node
FROM node

#Dossier dans lequel le build de l'app sera avec Docker
WORKDIR /home/darel/Bureau

#COPIES LES FILES PACKAGES.JSON A LA RACINE DU WORKDIR
COPY package*.json ./

#INSTALLE LES DEPENDANCIES
RUN npm install

#COPIE TOUS LES FILES A LA RACINE 
COPY . .

EXPOSE 4000

CMD ["npm","start"]
















