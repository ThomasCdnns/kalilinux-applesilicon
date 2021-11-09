# kalilinux-applesilicon
Docker container for Apple Silicon Mac

docker run -it --name Kali-M1 --mount type=bind,source=/Users/thomas/Documents/Pentest,target=/home/shared/pentest --mount type=bind,source=/Users/thomas/Downloads,target=/home/shared/downloads --cap-add=NET_ADMIN --cap-add=SYS_ADMIN --device /dev/net/tun  --sysctl net.ipv6.conf.all.disable_ipv6=0 ghcr.io/thomascdnns/kalilinux-applesilicon:version1.0 /bin/bash
