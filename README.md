# Install Command 
```
apt update && apt install -y git && git clone https://github.com/nahmo/tunnel && chmod +x tunnel/tunnel && mv tunnel/tunnel /usr/local/bin/ && rm -rf tunnel && clear && echo "Tunnel installed successfully! Run it with 'tunnel'"
```


Then run
for ssh
```
tunnel make 22
```

if want u can install rdp in kvm

# RDP CODES 🚀 

```sudo apt update && sudo apt upgrade -y

sudo apt install xfce4 xfce4-goodies xrdp -y

echo "startxfce4" > ~/.xsession
sudo chown $(whoami):$(whoami) ~/.xsession


sudo systemctl enable xrdp
sudo systemctl restart xrdp

tunnel make 3389
```
