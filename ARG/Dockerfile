FROM almalinux:9
ENV course="Devops with AWS" \
    tranier="Riyaz" \
    duration="120HRS"
#here user1 is key, someuser is default value
ARG ${username:-some_user}
RUN echo "Hello user : ${username}" 
CMD ["sleep", "100"]