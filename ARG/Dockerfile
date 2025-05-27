ARG version
FROM almalinux:${version:-8}
#here :-8 is default value if we not pass the aurg
RUN cat /etc/*release
CMD ["sleep", "100"]

#pass the aurg from command line $docker build -t arg:v1.0 --build-arg version=9
