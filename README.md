Building a private filtering server

Operating system required: Centos 7 x86 (or) Centos 7 x64

You need to install Putty to run the commands

cd /tmp/ && yum install git -y && git clone https://github.com/AlefbeMedia/Personal-vpn.git && cd Personal-vpn/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh

Codes to add a user to the server:

useradd [username] - passwd [username]
