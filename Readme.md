1. install ansible
2. passwordless authentication
        * .ssh folder exist and contains key pairs
        * use the .pem and chmod 600 <file>.pem
        * ssh-copy-id -f "-o IdentityFile <file>.pem" ubuntu@<public_key_target>
3. create inventory and add target server public ips
4. create roles and playbook