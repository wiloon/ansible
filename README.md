
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
