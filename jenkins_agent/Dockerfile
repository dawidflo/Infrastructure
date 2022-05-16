FROM jenkins/ssh-agent:4.2.1-jdk11

RUN apt update && \
    apt install -y curl git mc python3 python3-pip

RUN groupadd docker && \
    usermod -aG docker jenkins && \
    curl -fsSL https://get.docker.com | sh