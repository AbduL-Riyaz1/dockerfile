ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    tranier="Riyaz" \
    duration="120HRS"
#here username is key, Riyaz is default value
ARG username=Riyaz
RUN echo "Hello user : ${username}.image version: ${version}"  > /tmp/devops.txt
CMD ["sleep", "100"]