# Image de base
FROM nginx:1.13.3-alpine
RUN rm -rf /usr/share/nginx/html/*
# Copie des fichiers Angular se trouvant dans le dossier dist vers un répertoire spécifique de l'image
COPY  /dist usr/share/nginx/html


