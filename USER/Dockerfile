FROM almalinux:9
RUN dnf install nginx -y
#root access required to create user
RUN useradd roboshop
USER roboshop
CMD ["sleep", "100"]