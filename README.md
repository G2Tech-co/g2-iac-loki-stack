# G2 Loki stack IaC (Infrastructure as code)

[loki doc](https://grafana.com/docs/loki/latest/)

## Roles
- [x] Essentials
- [x] Swap
- [x] Docker
- [x] Traefik
- [x] loki
- [x] Reboot

## Setup
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run
Add ssh config host name to `hosts`
```
ansible-playbook setup.yml
```

## Defaults
```
Swap: 2G
Traefik: auth
```
