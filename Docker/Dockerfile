FROM nginx
RUN rm -rf /usr/share/nginx/html/*
RUN echo "<h1> This is first Dockerfile </h1>" > /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["/usr/sbin/nginx", "-g", "daemon off;"] 
