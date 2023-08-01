Ansible playbooks for Cisco Devices.

This is a collection of Ansible playbooks for various Cisco devices. 

Note the naming convention for the device model:

ansible_pb_cisco_asa = Cisco ASAv
ansible_pb_cisco_csr = Cisco CSR1000v
ansible_pb_cisco_sw = Cisco IOSvL2

How to use ansible-playbook with extra variables:
ansible-playbook ansible_pb_cisco_csr_show_version.yml --extra-vars "nodes=cisco_sandbox_csr password=<_password_>" 
