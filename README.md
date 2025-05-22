# My .dotfiles

## Do not ask for password

type `sudo visudo` and put the command bellow.
```
your_user ALL=(ALL) NOPASSWD: ALL
```
it will be fixed here: https://github.com/eerison/.dotfiles/issues/1
## Usage
### You can install by specific package:
```
ansible-playbook -i hosts playbook.yaml -t lazyvim -t php
```
### You can install all:
```
ansible-playbook -i hosts playbook.yaml
```
