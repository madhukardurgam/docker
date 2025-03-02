FROM almalinux:9
RUN dnf install nginx -y
LABEL project="expense"\
      environment="dev"
      trainer="dmk"
CMD ["nginx","-g","daemon off;"]