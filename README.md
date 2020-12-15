# ansible_pull
```
sudo apt update -y
sudo apt install -y git
sudo apt install -y ansible
sudo ansible-pull https://github.com/inmanturbo/rancher-vm.git
sudo -U ansible-pull https://github.com/inmanturbo/rancher-vm.git
sudo  ansible-pull -U https://github.com/inmanturbo/rancher-vm.git
curl https://releases.rancher.com/install-docker/19.03.sh | sh
sudo usermod  -aG docker inman
docker run -d --restart=unless-stopped   -p 80:80 -p 443:443   -v /opt/rancher:/var/lib/rancher   --privileged   rancher/rancher:latest
cat $HISTFILE
exit
```
