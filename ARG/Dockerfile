#ARG is the only one exception for FROM to have first line in Dockerfile
ARG version
# if user forgot to provide version from terminal provide default version 
FROM almalinux:${version:-8}
#FROM almalinux:${version}
# ARG variable should be before FROM, It will not work after FROM
#RUN echo "version passed by user is: ${version}"
#you can also use 
ARG COURSE
ARG TRAINER
RUN echo "Course is:${COURSE}, trainer is:${TRAINER}"