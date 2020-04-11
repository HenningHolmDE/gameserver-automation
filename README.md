# Automated game server setup

## Prerequisites
- Install `hcloud` Python package: `python -m pip install hcloud`
- Install `ansible` Python package: `python -m pip install ansible`

## Commands to run

### Start server
```
ansible-playbook start_factorio.yml --vault-password-file YOUR_VAULT_FILE
```

### Stop server
```
ansible-playbook stop_factorio.yml --vault-password-file YOUR_VAULT_FILE
```
