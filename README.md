# geth
## This repo is made for geth auto installing with monitoring based on Prometheus
### Use cases

Install all in one(Oneclick)
```
ansible-playbook -CD playbooks/etherium/_aio.yaml
```


Bootstrap new node
```
ansible-playbook -CD playbooks/bootstrap.yaml
```


Install monitoring only
```
ansible-playbook -CD playbooks/etherium/install-monitoring.yaml
```

Install geth only
```
ansible-playbook -CD playbooks/etherium/install-geth.yaml
```
