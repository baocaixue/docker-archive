FROM centos
MAINTAINER Isaac Bao "bao.isaac@gmail.com"
RUN dnf install -y nginx
RUN /bin/cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime && echo 'Asia/Shanghai' >/etc/timezone
ENV PORT_ 80
EXPOSE $PORT_
ENTRYPOINT ["nginx"]
CMD ["-g","daemon off;"]
