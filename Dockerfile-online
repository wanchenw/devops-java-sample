FROM java:8

WORKDIR /home/xpeng/local

COPY target/*.jar /home/xpeng/local

ENTRYPOINT [ "sh", "-c", "java $APP_OPTS $JMX_OPTS $JAVA_OPTS $GCLOG_OPTS -jar *.jar" ]
