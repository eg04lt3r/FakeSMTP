FROM java:8

ADD fakeSMTP-2.1.jar /opt

EXPOSE 25
VOLUME ["/var/mail"]

CMD java -jar /opt/fakeSMTP-2.1.jar -s -b -o /var/mail
