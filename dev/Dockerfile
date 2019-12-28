FROM wordpress

WORKDIR /root

RUN curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar

RUN chmod +x wp-cli.phar

RUN mv wp-cli.phar /usr/local/bin/wp

WORKDIR /var/www/html

# RUN wp core install --allow-root --url=rollbar-php-wordpress.local --title="Rollbar PHP Wordpress Dev Env" --admin_user=admin --admin_password=admin --admin_email=admin@rollbar-php-wordpress.local

# RUN wp plugin activate rollbar --allow-root