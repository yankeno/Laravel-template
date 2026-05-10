FROM mysql:9.7

ENV TZ=Asia/Tokyo 

COPY ./my.cnf /etc/mysql/conf.d/zz-custom.cnf
RUN chmod 644 /etc/mysql/conf.d/zz-custom.cnf
