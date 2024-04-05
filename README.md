# ansiblepull

run as root:
```bash
apt install ansible
ansible-galaxy collection install ansible.posix
ansible-pull create.user.yml --accept-host-key --url https://github.com/memoryalpha/ansiblepull.git
```
