FROM postgres:16-alpine
COPY scripts/ /docker-entrypoint-initdb.d
LABEL maintainer="sudhams reddy duba<sudhams@visualpath.in>"
ENV POSTGRES_DB=userdb
ENV POSTGRES_USER=testuser2
ENV POSTGRES_PASSWORD=test123



