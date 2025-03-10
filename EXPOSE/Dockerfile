FROM almalinux:9
RUN dnf install nginx -y
# no functionlity for EXPOSE, it is just for information purpose
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]