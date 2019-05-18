
Add the following line to /etc/apt/sources.list:
```
deb http://ppa.launchpad.net/ansible/ansible/ubuntu trusty main
```

Then run these commands:
```
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367
sudo apt update
sudo apt install ansible
```

```bash
#comment out google cros package,  for wall...
vim /etc/apt/sources.list.d/cros.list

# change source list to aliyun mirror, https://opsx.alibaba.com/mirror
vim /etc/apt/sources.list

# install ansible
# archlinux
sudo pacman -S ansible

# debian
sudo apt-get install ansible

# init debian via ansible
sudo ansible-pull -U https://github.com/wiloon/ansible.git
```
