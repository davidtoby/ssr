# ssr
ssr server one click to install



run 3 command as below：

1.
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh

(or wget --no-check-certificate -O shadowsocks-all.sh https://github.com/davidtoby/ssr/blob/master/shadowsocks-all.sh) Thanks teddysun!

2.
chmod +x shadowsocks-all.sh

3.
sudo ./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
