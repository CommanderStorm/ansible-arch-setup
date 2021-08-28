# DONT use this config. It is verrrry personal and thus poorly documented.
# You will not like my preferences. Use the parent-projet instead


## single
```bash
git clone --recurse-submodules git@github.com:CommanderStorm/ansible-arch-setup.git && cd ansible-arch-setup/roles && sudo pacman -Sy ansible && ansible-playbook -K main.yml
```
## split
```bash
git clone --recurse-submodules git@github.com:CommanderStorm/ansible-arch-setup.git
```
```bash
cd ansible-arch-setup/roles
```
```bash
sudo pacman -Sy ansible
```
```bash
ansible-playbook -K main.yml
```
