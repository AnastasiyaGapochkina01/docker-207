```
ansible-vault encrypt files/container.env
ansible-playbook -i inventory -u anestesia bookstore-playbook.yml --ask-vault-pass
ansible-vault edit roles/setup-bookstore/files/container.env
```