FROM almalinux:9
RUN yum install nginx -y && yum clean all
RUN rm -rf /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
ENV name="shiva" email="abc@gmail.com" mob=96322
LABEL auther="siva" duration=100
EXPOSE 80
COPY index.html /usr/share/nginx/html/index.html