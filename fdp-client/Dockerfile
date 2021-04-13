FROM fairdata/fairdatapoint-client:1.8.0

COPY ./fdp-client/_variables.scss /src/scss/custom/_variables.scss
COPY ./fdp-client/assets/kadaster-logo.png /usr/share/nginx/html/assets/kadaster-logo.png
COPY ./fdp-client/application.yml /fdp/application.yml

CMD ["/start.sh"]
