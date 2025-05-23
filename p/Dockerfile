FROM almalinux
RUN dnf install nginx -y 
CMD ["nginx" , "-g" , "daemon off;"]
ENV user = "Amar" \
    envi = "dev"
EXPOSE 80
COPY sample.txt   /home/ec2-user/sample.txt
ADD https://github.com/daws-81s/dockerfiles/blob/main/RUN/Dockerfile  /home/ec2-user/sample1.txt
WORKDIR /home/ec2-user/
RUN useradd Amar
