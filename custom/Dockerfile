FROM litespeedtech/openlitespeed:latest
RUN apt-get update && apt-get install lsphp74-pspell -y

# Install Less for WP-CLI
RUN apt-get update && apt-get -y install less vim
 
# Install WP-CLI
RUN curl -s -o /usr/local/bin/wp \
    https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar \
    && chmod +x /usr/local/bin/wp