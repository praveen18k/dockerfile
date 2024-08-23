#ARG is the only one exception for FROM to have first line in Dockerfile
ARG version
FROM almalinux:${version}
# ARG variable should be before FROM, It will not work after FROM
RUN echo "version passed by user is: ${version}"