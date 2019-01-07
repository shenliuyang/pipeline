FROM docker.bj1580.top/exposed_base:102
WORKDIR /root
ENV  logbackFile = "logback.xml"
ADD  libs/lib-dynamic /root/lib-dynamic
ADD  libs/app.jar /root/app.jar
ENTRYPOINT java -Dlogback.configurationFile=${logbackFile}  -jar app.jar