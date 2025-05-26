# Ansible LAMP Stack

This project automates the setup of a LAMP stack (Linux, Apache, MySQL, PHP) using Ansible.

## Features

- Installs and configures Apache
- Installs MySQL and sets the root password
- Installs PHP and connects it with Apache
- Works on Ubuntu/Debian systems

## Requirements
- Ansible installed on control node
- SSH access to target node

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/pranali2482/Ansible-LAMP-Stack.git
   cd Ansible-LAMP-Stack
   ansible-playbook -i inventory lamp.yml


