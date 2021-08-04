FROM        ubuntu
RUN         apt update -y
RUN         apt install nginx -y
CMD         ["nginx", "-g", "daemon off;"]
ADD         index.html /var/www/html/index.html
#to add a file
#RUN         rm -rf /var/www/html/*
#ADD         html /var/www/html
# to add a directory in that location
#COPY        html /var/www/html