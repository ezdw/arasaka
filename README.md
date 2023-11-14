![wp7743712-1440x2560-mobile-wallpapers](https://github.com/ezdw/arasaka/assets/72717235/4bcb6f14-50b8-46dc-9dee-d13a037f8320)


### INSTALL SCRIPT

<pre><code>apt install -y && apt update -y && apt upgrade -y</code></pre>
<pre><code>apt install -y && apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && wget -q https://raw.githubusercontent.com/ezdw/arasaka/main/premi.sh && chmod +x premi.sh && ./premi.sh
</code></pre>

wajib install
<pre><code>
echo; echo 'Installing DOS-Deflate 0.6'; echo
echo; echo -n 'Downloading source files...'
wget -q -O /usr/local/ddos/ddos.conf https://gitlab.com/akunzpn25/gknlojinulhlmjlgjyg/-/raw/master/DDOS%20MASTER/ddos.conf >/dev/null 2>&1
echo -n '.'
wget -q -O /usr/local/ddos/LICENSE https://gitlab.com/akunzpn25/gknlojinulhlmjlgjyg/-/raw/master/DDOS%20MASTER/LICENSE >/dev/null 2>&1
echo -n '.'
wget -q -O /usr/local/ddos/ignore.ip.list https://gitlab.com/akunzpn25/gknlojinulhlmjlgjyg/-/raw/master/DDOS%20MASTER/ignore.ip.list >/dev/null 2>&1
echo -n '.'
wget -q -O /usr/local/ddos/ddos.sh https://gitlab.com/akunzpn25/gknlojinulhlmjlgjyg/-/raw/master/DDOS%20MASTER/ddos.sh >/dev/null 2>&1
chmod 0755 /usr/local/ddos/ddos.sh
cp -s /usr/local/ddos/ddos.sh /usr/local/sbin/ddos
echo '...done'
echo; echo -n 'Creating cron to run script every minute.....(Default setting)'
/usr/local/ddos/ddos.sh --cron > /dev/null 2>&1
</code></pre>

Fail2Ban

<pre><code>apt -y install fail2ban > /dev/null 2>&1</code></pre>

<pre><code>sudo systemctl enable --now fail2ban</code></pre>

<pre><code>/etc/init.d/fail2ban restart</code></pre>

<pre><code>/etc/init.d/fail2ban status</code></pre>


### OS

- UBUNTU 20.04.05
- DEBIAN 10

### FITUR TAMBAHAN

- Tambah Swap 1GiB
- Pemasangan yang dinamis
- Tuning profile pada server
- Penambahan fail2ban
- Penambahan ddos dflate
- Auto block sebagian ads indo by default
- Auto clear log per 3 menit
- Auto deler expired
- User Details Akun

### PORT INFO

```
- TROJAN WS 443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- VLESS WS 443
- VLESS GRPC 443
- VLESS NONTLS 80
- VMESS WS 443
- VMESS GRPC 443
- VMESS NONTLS 80
- SSH WS / TLS 443
- SSH NON TLS 8880
- OVPN SSL/TCP 1194
- SLOWDNS 5300
```

### SETTING CLOUDFLARE

```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```
