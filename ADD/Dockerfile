FROM almalinux:9
RUN dnf install nginx -y
#removing old files
RUN rm -f /usr/share/nginx/html/index.html
#copying the local file dest folder (source to dest)
ADD https://github.com/madhukardurgam/docker/blob/main/CMD/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]