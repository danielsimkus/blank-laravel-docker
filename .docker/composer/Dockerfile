FROM cash4chores_cli
COPY --from=composer /usr/bin/composer /usr/bin/composer

WORKDIR /var/www
USER www
CMD ["/usr/bin/composer", "install"]