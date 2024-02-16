FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-76s/user-deploy/main/terraform/bootstrap.sh /tmp/session1.txt
ENV TRAINING="DEVOPS" \
      TRAINER="SIVAKUMAR" \
      DURATION="1220 HRS"

CMD ["nginx", "-g", "daemon off;"] 