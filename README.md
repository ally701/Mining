apt update

apt upgrade

To Install Ubuntu


pkg install wget openssl-tool proot -y && hash -r && wget https://raw.githubusercontent.com/EXA... && bash ubuntu.sh

 Start Ubuntu

./start-ubuntu.sh

2. While In Ubuntu

Install SSH with command: 

wget https://raw.githubusercontent.com/EXA... && bash ssh-apt.sh

 Install Desktop Environment

wget https://raw.githubusercontent.com/EXA... && bash de-apt-xfce4.sh

apt-get update

apt-get upgrade

To Install xmrig

 apt-get install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev libhwloc-dev 

git clone https://github.com/xmrig/xmrig.git 

cd xmrig 

mkdir build 

cd build 

cmake .. 

make

Start mining :

./xmrig -a cryptonight -o stratum+tcp://xmr.pool.minergate.com:45700 -u emailaddress@gmail.com -p x

After -u , you should type your wallet address .
I made a wallet address on minergate , so I used that email and the minergate's pool for monero mining.

If Termux crashed then you'll need to switch to light mode 

1.cd ../
2.cp src/config.json  build/
3.cd build 
4. apt install nano 
5.nano config.json
follow video to make the changes and save the file
6. ./xmrig and enter to start the mining process
