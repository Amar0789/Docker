FROM almalinux:9
RUN dnf install nginx -y
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]