FROM almalinux:9
ENV name="shiva" email="abc@gmail.com" mob=96322
LABEL auther="siva" duration=100
EXPOSE 80/TCP
CMD ["nginx", "-g", "daemon off"]
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/