workspace
=========

A setup guide and ansible playbook to setup my preferred dev environment.


## setup

```bash
sudo apt-get install git python-pip cowsay
sudo pip install ansible

mkdir ~/Tools
cd ~/Tools
git clone git@github.com:anithri/workspace
sudo ansible-galaxy install rvm_io.rvm1-ruby
sudo ansible-galaxy install devbox.chrome

cd workspace
ansible-playbook -i dev site.yml
```


