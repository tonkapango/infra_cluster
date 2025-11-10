# infra_cluster

### kvm install
0. install kvm/qemu/*
```
sudo apt install qemu-kvm libvirt-daemon-system libvirt-clients bridge-utils virt-manager virtinst ovmf swtpm qemu-utils guestfs-tools libosinfo-bin tuned
```
1. setup
```
sudo systemctl enable libvirtd
sudo systemctl start libvirtd
```
or
```
sudo systemctl enable libvirt-daemon
sudo systemctl start libvirt-daemon
```
```
sudo usermod -aG libvirt $USER
```

 ### create VMs
 

 
