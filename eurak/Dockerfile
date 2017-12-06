FROM java:8
VOLUME /tmp
ADD eurekaserver-0.0.1-SNAPSHOT.jar /eurakapp.jar
RUN bash -c 'touch /eurakapp.jar'
EXPOSE 8761
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/eurakapp.jar"]