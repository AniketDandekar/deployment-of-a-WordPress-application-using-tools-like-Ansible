# Deployment-of-a-WordPress-application-using-tools-like-Ansible

# Steps:
* Set the ip-address of Managed Node in the inventory
* Docker needs to be available in managed node or you can install by adding extra lineof code in playbook
* Run mysql playbook first and after successfull mysql container launch, next run wordpress playbook.
