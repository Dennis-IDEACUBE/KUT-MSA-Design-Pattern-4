# KUT-MSA-Design-Pattern-4

### VirtualBox 

VBoxManage natnetwork add --netname natnet1 --network "192.168.15.0/24" --enable --dhcp off --port-forward-4 "ssh:tcp:[]:22:[192.168.15.101]:22"
