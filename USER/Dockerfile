FROM almalinux:9
RUN adduser expence
USER expence
CMD ["sleep", "100"]
#when we use this user artifact if we connect to the docker container it will login as normal user insted of login as root user inside the container. sudo su - is alos not works here when we user user attribute.