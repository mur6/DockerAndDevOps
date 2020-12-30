FROM ubuntu
RUN apt-get update
RUN apt-get install -y build-essential
RUN apt-get install -y python3
RUN apt-get install -y python3-pip
RUN apt-get install -y sudo
RUN pip3 install conan
RUN useradd developer
RUN gpasswd -a developer sudo
USER developer