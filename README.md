Using Ansible Vault

Given that I would need to pass in my lexaloffe account credentials in order to download the latest pico-8 zip, I decided to use ansible vault to encrypt my credentials. 

To encrypt your credentials, use the `ansible-vault create` command. 