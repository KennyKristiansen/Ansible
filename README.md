# Ansible

![GitHub branch checks state](https://img.shields.io/github/checks-status/kennykristiansen/Ansible/master)

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
