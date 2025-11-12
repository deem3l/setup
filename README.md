# setup
A project to setup the lab

## Install

Installation procedure for standard linux with bash :

First install ansible : 

```
pipx install ansible
echo '--- Custom ansible pipx path ---'
echo 'export PATH=$PATH:~/.local/share/pipx/venvs/ansible/bin' >> ~/.bashrc
echo 'export PATH=$PATH:~/.local/bin' >> ~/.bashrc
source ~/.bashrc
```

Then clone the projet :

```
git clone https://github.com/deem3l/setup deem3l_setup
cd deem3l_setup
```

## Configure

Configure your own ansible.cfg :

```
mv ansible.cfg.tmpl ansible.cfg
vim ansible.cfg # Fill with your own conf/access
```
