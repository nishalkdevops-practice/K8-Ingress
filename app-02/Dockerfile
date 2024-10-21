# systemctl start status and all comes under this CMD command 
FROM almalinux:8 
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html 
RUN echo "<h1>Hello from App-02</h1>" > /usr/share/nginx/html/index.html
CMD [ "nginx","-g", "daemon off;" ]