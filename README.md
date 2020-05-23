# ansible-hc2
Repository of ansible playbooks and roles for managing my Odroid HC2 GlusterFS 
and K8s cluster.


## Getting started
**NOTE:** Ansible can't be installed on Windows. 
It is possible to manage Windows machines via ansible though.
 
### Setup a clean working environment (optional)
#### Create Python virtual environment
```bash
cd path/to/project
python -m venv .venv
```

#### Activate Python virtual environment
```bash
source .venv/bin/activate
```

### Install dependencies
#### Python dependencies
```bash
python -m pip install -r requirements.txt
```

#### Ansible Galaxy dependencies
```bash
ansible-galaxy install -r requirements.yml
```

---
