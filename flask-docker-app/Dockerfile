FROM public.ecr.aws/ubuntu/apache2:latest
# install apache2

#RUN apt-get update && apt-get install -y apache2

# port number the container should expose
EXPOSE 80

# run apache2
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

