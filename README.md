# Ansible for Ubuntu+Docker Setup

🚀 How to Use
Save this as setup_ubuntu_docker.yml.

Adjust any variables as needed (e.g., allowed ports or Docker Compose version).

Run with:

ansible-playbook -i inventory setup_ubuntu_docker.yml
(replace inventory with your Ansible hosts inventory file)

🔒 Key Features

✅ Updates system and installs security tools (fail2ban, ufw, unattended-upgrades)

✅ Configures firewall with SSH, HTTP, and HTTPS rules

✅ Installs Docker and Docker Compose (standalone and plugin)

✅ Ensures the user is in the Docker group

✅ Reboots automatically if needed after updates
