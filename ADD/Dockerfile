FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Sankar3969/Docker/main/COPY/index.html /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]