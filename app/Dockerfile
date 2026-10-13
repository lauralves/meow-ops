FROM nginx:1.31.6-alpine-slim

RUN apk upgrade --no-cache pcre2

COPY index.html /usr/share/nginx/html/index.html
COPY assets /usr/share/nginx/html/assets

EXPOSE 80
