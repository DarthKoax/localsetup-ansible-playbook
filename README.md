
# Setup
```
ansible-galaxy install geerlingguy.dotfiles
ansible-galaxy install gantsign.golang
```

`ansible-galaxy install -r requirements.yml`


## Run me
```
ansible-playbook -i inventory.ini main.yaml --ask-become
```
