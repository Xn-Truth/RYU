# RYU Install Ubuntu 22.04

sudo apt-get update

sudo add-apt-repository ppa:deadsnakes

sudo apt update

sudo apt install python3.7

which python3.7



sudo apt-get install git

git clone https://github.com/faucetsdn/ryu.git



sudo apt-get install python3-pip

sudo apt-get install python3.7-dev

sudo apt install python3.7-distutils

sudo python3.7 -m  pip install webob

sudo python3.7 -m  pip install tinyrpc==1.0.4

sudo python3.7 -m  pip install eventlet==0.31.1

sudo python3.7 -m  pip install msgpack

sudo python3.7 -m  pip install netaddr

sudo python3.7 -m  pip install oslo.config

sudo python3.7 -m  pip install ovs

sudo python3.7 -m  pip install packaging==20.9

sudo python3.7 -m  pip install routes



cd ryu

python3.7 setup.py install



ryu-manager --version
