FROM amazonlinux:2023

RUN yum -y update

RUN yum -y install nginx

ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]

# コンテナのディレクトリ
WORKDIR /var/www/vhosts/