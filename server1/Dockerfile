FROM tomcat:9.0
COPY /mnt/game-of-life/gameoflife-web/target/gameoflife.war /usr/local/tomcat/webapps
EXPOSE 8080
ENTRYPOINT [ "catalina.sh", "run" ]

