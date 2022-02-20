# xmrig-ubuntu-install
XMRIG Monero Ubuntu Script Auto-INSTALL


# SCRIPT AUTO-INST UBUNTU 18/20/21

git clone https://github.com/xmrig/xmrig.git 
chmod a+x script.sh
./script.sh

curl -s https://packagecloud.io/install/repositories/immortal/immortal/script.deb.sh | sudo bash apt install immortal sudo apt install libssl-dev sudo apt-get install git build-essential cmake automake libtool autoconf git clone https://github.com/xmrig/xmrig.git mkdir xmrig/build && cd xmrig/scripts ./build_deps.sh && cd ../build cmake .. -DXMRIG_DEPS=scripts/deps make -j$(nproc) cd /root/xmrig/build immortal /bin/sh -c "nohup ./xmrig -o fr.minexmr.com:443 -u 46tfyDCzhgZH5xUWEnUJ7ngwfPa6apAppVD7tLqP1mkzDgRJnKP3nqMMKiCZq9aBUZGHsha5q95gkZLFEDaQo64rQ9jVn1X -k --tls --rig-id {YOUR-ADDRESS_XMR}"
