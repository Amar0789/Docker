FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/index.html
ONBUILD COPY index.html /usr/share/nginx/index.html
CMD ["sleep", "100"]