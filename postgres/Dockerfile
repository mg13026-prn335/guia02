FROM postgresql:9.6.3-alpine

COPY docker-entrypoint.sh /
COPY posts_v2.sql /docker-entrypoint-initdb.d/

ENTRYPOINT ["/docker-entrypoint.sh"]

EXPOSE 5432
CMD ["postgres"]


