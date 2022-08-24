# Ansible

![GitHub branch checks state](https://img.shields.io/github/checks-status/kennykristiansen/Ansible/master)

## Requirements

- Python 3
- `ansible` installed on the system

## Installation

    git clone https://github.com/KennyKristiansen/Ansible.git && cd Ansible

## Deploying

    ansible-playbook main.yml -i hosts -K --connection=local
