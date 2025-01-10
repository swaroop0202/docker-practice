FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
LABEL name="swaroop"\
      course="devops"
CMD ["nginx","-g","daemon off;"]
ADD https://raw.githubusercontent.com/swaroop0202/expenses-documention/refs/heads/main/frontend.MD /tmp/file
ADD  sample-1.zip /tmp/file