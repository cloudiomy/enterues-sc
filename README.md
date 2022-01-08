# Installation Enterues-SC-V1.0.2

```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils -y && wget -P /root -N --no-check-certificate https://raw.githubusercontent.com/enterues-cloud/enterues-sc/main/setup.sh && chmod +x setup.sh && "/root/setup.sh"
```

Only support Debian 10 Buster & Ubuntu 20.04 LTS
