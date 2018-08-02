# ansible_install_nginx

## Installing  nginx

`ansible-playbook -i inventory/node playbooks/nginx.yml --tags nginx -K`

## Creation of SSL Certificates

`ansible-playbook -i inventory/node playbooks/nginx.yml --tags ssl -K`

## Configuring HTTPS

`ansible-playbook -i inventory/node playbooks/nginx.yml --tags https -K`
