FROM almalinux/9-base
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/K-Basavaraj/terraform-aws-secuirty-group/refs/heads/main/readme.md /usr/share/nginx/html/index.html
RUN /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]