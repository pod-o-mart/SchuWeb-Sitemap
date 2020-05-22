sitemap-dev-php74-up:
	sudo UID=${UID} GID=${UID} docker-compose -f sitemap-dev-php7.4/docker-compose.yml up -d
sitemap-dev-php74-stop:
	sudo docker-compose -f sitemap-dev-php7.4/docker-compose.yml stop
sitemap-dev-php74-install:
	sudo ln -sf /src/administrator/components/com_schuweb_sitemap ${CURDIR}/sitemap-dev-php7.4/public/administrator/components/
	sudo ln -sf /src/components/com_schuweb_sitemap ${CURDIR}/sitemap-dev-php7.4/public/components/
	sudo ln -sf /src/plugins/schuweb_sitemap ${CURDIR}/sitemap-dev-php7.4/public/plugins/