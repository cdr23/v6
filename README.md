# BRINGAS TUNNEL
<code><pre>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/Bringas-tunnel/v6/main/setup/setupku.sh && chmod +x setupku.sh && sed -i -e 's/\r$//' setupku.sh && screen -S setupku ./setupku.sh</code></pre>
