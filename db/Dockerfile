FROM mysql:5.6

LABEL maintainer="Theo Tzaferis<t.tzfrs@gmail.com>"

RUN sed -i -e '$a# Accept connections from any IP address' /etc/mysql/mysql.conf.d/mysqld.cnf
RUN sed -i -e '$abind-address	            = 0.0.0.0' /etc/mysql/mysql.conf.d/mysqld.cnf
