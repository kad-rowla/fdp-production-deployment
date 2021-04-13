FROM fairdata/fairdatapoint:1.8.0

COPY ./fdp/application.yml /fdp/application.yml

ENTRYPOINT java -jar app.jar --spring.profiles.active=production --spring.config.location=classpath:/application.yml,classpath:/application-production.yml,file:/fdp/application.yml
