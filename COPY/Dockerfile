FROM almalinux 
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY hostit-html /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]