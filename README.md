# ansiblepull

run as root:
```bash
apt install ansible -y
ansible-galaxy collection install ansible.posix
ansible-pull --accept-host-key --url https://github.com/memoryalpha/ansiblepull.git create.user.yml 
```
