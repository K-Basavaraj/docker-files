FROM almalinux/9-base
RUN dnf install nginx -y 
#expose means it not open the port just it tell the user that which port will open when the image runs.
EXPOSE 80   
CMD ["nginx", "-g", "daemon off;"]