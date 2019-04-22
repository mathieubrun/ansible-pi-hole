# ansible playbooks for setting up pi-hole with unbound

## prerequisites

- a Raspberry Pi with internet connectivity and static IP address

## usage

ansible-playbook -i PI_IP_ADDRESS, pi-hole.yaml

## additional setup

- define admin password on pi-hole using command `pihole -a -p`
- adjust privacy settings
- configure internet box to use pi-hole as an upstream DNS
