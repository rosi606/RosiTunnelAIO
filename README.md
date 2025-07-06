📣 ROSI Tunneling 📣

☘ SUPPORT OS ☘  
  
➽ Debian 10, 11  (recommended)   
➽ Ubuntu 20

⚡️ INSTALASI ⚡️     

❏ STEP 1 :    
```apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && apt install curl jq wget screen build-essential -y && reboot```

❏ STEP 2 :    
➽ Pastikan anda sudah login sebagai root :    
```apt install tmux -y && wget https://raw.githubusercontent.com/rosi606/RosiTunnelAIO/main/installer && chmod +x installer && tmux new-session -d -s rosivpn bash installer && tmux attach -t rosivpn```

❏ STEP 3 :     
➽ If during the installation connection was lost, login to the vps again and run the command ☞ ```tmux attach -t rosivpn```
