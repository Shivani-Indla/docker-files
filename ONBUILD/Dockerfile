FROM almalinux:9
RUN yum install nginx -y
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"] 