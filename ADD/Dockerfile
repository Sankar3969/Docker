FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
COPY https://gist.github.com/lillylangtree/b55828fa05ed3470d352/index.html /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]