FROM insideo/rabbitmq
MAINTAINER ccondit@randomcoder.com

RUN \
	opkg update && \
	opkg install bash ncurses-base && \
	opkg clean

COPY docker-entrypoint-init.d /docker-entrypoint-init.d
