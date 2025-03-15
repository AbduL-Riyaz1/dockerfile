FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# ONBUILD execits if any user uses your image as their ase os
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]