# DONT use this config. It is verrrry personal and thus poorly documented.
# You will not like my preferences. Use the parent-projet instead

```bash
sudo pacman -Sy ansible
mkdir -p ~/dev
cd ~/dev
git clone --recurse-submodules https://github.com/CommanderStorm/ansible-arch-setup.git
```
```bash
cd ~/dev/ansible-arch-setup/roles
ansible-playbook -K main.yml
```
