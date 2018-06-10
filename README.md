# CCC-ACI-BIG-IP
Cisco CloudCenter orchestrate ACI and BIG-IP with Ansible automation

Sample playbooks that allow you complete L2 stitching between Cisco ACI and F5 BIG-IP.

We also provide playbook to clean up the configurations.

ACI tasks (using aci_rest Ansible module)
- create contract
- assign consumer and provider EPG to the contract
- create an unmanaged BIG-IP VE L4-L7 device
- create service graph template
- create device selection policy
- attach graph to contract

BIG-IP tasks
- create VLAN
- create self IP
- create default route
