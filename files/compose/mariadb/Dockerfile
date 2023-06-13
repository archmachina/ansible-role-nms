FROM mariadb:10.5

COPY init_file.cnf /etc/mysql/mariadb.conf.d/80-init_file.cnf
RUN chmod 0644 /etc/mysql/mariadb.conf.d/80-init_file.cnf
RUN touch /etc/mysql/init_file
