# prometeus-ansible
usage:

ansible-playbook ./provision.yml -i ./inventory.yml --private-key=key -b\
-e "grafana_creds.url=interal_gafana_address:3000 prom_server=external_ssh_addr_for_ansible"
