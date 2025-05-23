FROM almalinux
RUN dnf install nginx -y 
CMD ["nginx" , "-g" , "daemon off;"]
ENV user = "Amar" \
    envi = "dev"
EXPOSE 80
COPY sample.txt /home/ec2-user/sample.txt 