## Ansible playbook for Kali linux

A playbook to configure a fresh install of Kali linux

### Run

Run in `mate-terminal`, allowing `qterminal` settings to persist

```
sudo apt install -y ansible
ansible-galaxy install -r requirements.yml
ansible-playbook kali.yml -K
```

### Post run

- Firefox sync
- Tmux plugins install
- Vim plugins install