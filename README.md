📣 ROSI Tunneling 📣

☘ SUPPORT OS ☘  
  
➽ Debian 10, 11  (recommended)   
➽ Ubuntu 20

⚡️ INSTALASI ⚡️     

❏ STEP 1 :    
```
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && apt install curl jq wget screen build-essential -y && reboot
```

❏ STEP 2 :    
➽ Pastikan anda sudah login sebagai root :    
```
wget https://raw.githubusercontent.com/rosi606/RosiTunnelAIO/main/installer &&  bash installer && apt install tmux -y && tmux new-session -d -s rosivpn bash install && tmux attach -t rosivpn
```

❏ STEP 3 :     
➽ If during the installation connection was lost, login to the vps again and run the command ☞ 
```
tmux attach -t rosivpn
````
