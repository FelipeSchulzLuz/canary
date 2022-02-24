FROM opentibiabr/canary:latest

WORKDIR /otbr

COPY ../config.lua /otbr/

CMD ["chmod", "+x", "/tmp/web/download-myaac.sh"]

RUN ./tmp/web/download-myaac.sh

