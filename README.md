
# Timestamp

sudo apt install moreutils -y


bash -c "ping -w 60 192.168.200.2 | ts '[%Y-%m-%d %H:%M:%.S]' > ~/ping.txt;exec bash"


replace <ping> with command of your choice
