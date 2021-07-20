FROM        ubuntu
RUN         apt update -y
RUN         apt install nginx -y
CMD         ["nginx", "-g", "daemon off;"]
LABEL       Owner="ZelarSoft" \
            Maintainer="DevOps Team"\
            ProjectName="Docker"
EXPOSE      80/tcp
ENV         URL=google.com
ENV         PROJECT=Demo