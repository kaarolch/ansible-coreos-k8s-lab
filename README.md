# ansible-coreos-k8s-lab
Small ansible playbook that allow me setup more persistent environment with libvirt.

This is one of the first version of this playbook.

# How to run
## Setup stack
Before you run please review all group_vars.
```
ansible-playbook main.yml -K -vvv --extra-vars
```

To stop or start machines just use extra vars steps equal start or stop.
## Destroy stack

```
ansible-playbook main.yml -K -vvv --extra-vars "step=destroy"
```

# ToDo:
- test playbook
- refractory some variables dep.
