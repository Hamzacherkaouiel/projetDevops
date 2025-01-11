FROM node:10

WORKDIR /app/vehicle

# Copier uniquement les fichiers package.json et package-lock.json
COPY package*.json ./

# Installer les dépendances
RUN npm install

# Copier tous les autres fichiers
COPY . .

# Commande de démarrage
CMD ["npm", "start"]
