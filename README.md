# git-clone-all
### Create a ssh-key
Create a ssh key and then set in in github:

```bash
ssh-keygen -t ed25519 -C "r.finland88@gmail.com"
```
Installedpackages:
```bash
apt install python3-pip
pip3 install github-archive
```
To achieve all repose run:
```bash
github-archive --users rfatolahzade --clone
```
You should read help of github-archive if you want to clone special repos
To clone private repos un int manually (update needs)
```bash
git clone git@github.com:rfatolahzade/akube-pdf.git
git clone git@github.com:rfatolahzade/auseful-Doc.git
git clone git@github.com:rfatolahzade/omy-adventure.git
git clone git@github.com:rfatolahzade/anAWS-Training.git
git clone git@github.com:rfatolahzade/anAnsible-Kubespray.git
```
