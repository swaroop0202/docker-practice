FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
LABEL name="swaroop"\
      course="devops"
CMD ["nginx","-g","daemon off;"]
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/swaroop0202/expenses-documention/refs/heads/main/frontend.MD /tmp/frontend