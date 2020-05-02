# ansible-hc2

## Getting started
**NOTE:** Ansible can't be installed on Windows. It is possible to manage Windows via though.
 
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
