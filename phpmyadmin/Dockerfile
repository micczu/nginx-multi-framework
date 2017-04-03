FROM phpmyadmin/phpmyadmin:latest

# For ENV with TZ for time zone to work; if not needed you could use default image
RUN apk add --no-cache tzdata
#&& apk --no-cache upgrade

EXPOSE 80 443

ENTRYPOINT [ "/run.sh" ]
CMD ["phpmyadmin"]
