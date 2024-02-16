FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ENV TRAINING="DEVOPS" \
      TRAINER="SIVAKUMAR" \
      DURATION="1220 HRS"

CMD ["nginx", "-g", "daemon off;"] 