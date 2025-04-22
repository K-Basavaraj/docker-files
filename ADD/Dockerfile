FROM almalinux/9-base
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/K-Basavaraj/terraform-aws-secuirty-group/refs/heads/main/readme.md /usr/share/nginx/html/index.html
RUN chomd +x /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]