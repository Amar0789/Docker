FROM almalinux
RUN yum install nginx -y
CMD ["nginx","-g","daemon off ;"]
LABEL author="amar"
EXPOSE 80
ENV author="new"
COPY Dockerfile /home/ec2-user/