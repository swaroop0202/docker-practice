FROM almalinux:9
RUN dnf install nginx -y
LABEL name="swaroop"\
      course="devops"
#CMD ["ping","-c5","google.com"]
ENTRYPOINT [ "ping","-c5","google.com" ]