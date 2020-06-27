FROM ubuntu:latest
RUN apt-get update && apt-get install -y ansible \
    vim
COPY ansible.cfg /etc/ansible/ansible.cfg
COPY hosts /etc/ansible/hosts
WORKDIR /etc/ansible
CMD ["bash"]