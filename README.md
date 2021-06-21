# Ansible

![CI Status](https://github.com/kennykristiansen/infrastructure/workflows/CI/badge.svg)

## Requirements

- Python 3
- Locally configured SSH config (ideally deployed through [dotfiles](https://github.com/realorangeone/dotfiles))
- `ansible` installed on the system

## Installation

git clone https://github.com/KennyKristiansen/Ansible.git
cd Ansible

## Deploying
- cd Ansible
- ansible-playbook main.yml -i hosts -K --connection=local
