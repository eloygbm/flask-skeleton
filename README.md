
[![ License ](https://img.shields.io/badge/license-Apache v2-blue.svg)](LICENSE)

# flask-skeleton

Ansible playbook to generate a Flask project skeleton

## Prerequisites

Ansible

and the python developer's tools:

* Python
* Pip
* Virtualenv 
* Git


## Use

`ansible-playbook flask-skeleton.yml` 

it will prompt about your project name.

## Basic structure

```
.
├── db
│   └── .gitignore
├── logs
│   └── .gitignore
├── MyProject
│   ├── scripts
│   │   └── schema.sql
│   ├── templates
│   ├── db.py
│   ├── __init__.py
│   └── main.py
├── .gitignore
├── run.py
└── settings.py

5 directories, 6 files
```
