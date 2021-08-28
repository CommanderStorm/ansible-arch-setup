# DONT use this config. It  is verrry personal and you will not like my preferences. Use the parent-projet instead


## single
```bash
git clone --recurse-submodules git@github.com:CommanderStorm/ansible-arch-setup.git && sudo pacman -Sy ansible && ansible-playbook -K main.yml
```
## split
```bash
git clone --recurse-submodules git@github.com:CommanderStorm/ansible-arch-setup.git
```
```bash
sudo pacman -Sy ansible
```
```bash
ansible-playbook -K main.yml
```
