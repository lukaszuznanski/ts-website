FROM phpdockerio/php56-fpm:latest

# Install selected extensions and other stuff
RUN apt-get update \
    && apt-get -y --no-install-recommends install  php5-memcached php5-mongo php5-mysql php5-pgsql php5-redis php5-sqlite php5-adodb php5-sasl php5-enchant php5-exactimage php5-gd php5-gearman php5-geos php5-gmp php5-geoip php5-gnupg php5-vtkgdcm php5-gdcm php5-pecl-http php5-igbinary php5-imap php5-interbase php5-intl php5-imagick php5-remctl php5-lasso php5-ldap php5-libvirt-php php5-mapscript php5-memcache php5-msgpack php5-oauth php5-odbc php5-radius php5-phpdbg php5-pinba php5-propro php5-pspell php5-raphf php5-rrd php5-recode php5-librdf php5-ssh2 php5-snmp php5-solr php5-stomp php5-svn php5-sybase php5-tidy php5-tokyo-tyrant php5-twig php5-xmlrpc php5-xsl php5-zmq \
    && apt-get clean; rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*


WORKDIR "/var/www/imperiumgracza"
