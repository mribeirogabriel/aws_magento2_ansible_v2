# magento2_container_ansible 🖥️
![Magento2](https://wishtech.com.br/wp-content/uploads/elementor/thumbs/magento2-logo-nmsuizg4uu9z0hjd4gcv0m3uybqei3lnne838sddoo.png "Magento2")
- EC2 Instance = Ubuntu 18.04
- Docker CE
- RDS - MySQL
- Magento 2 Container

**Description:**
- This playbook provides AWS infrastructure (Keys, Network, Database, Ec2, Docker ) and deploy the Magento 2 aplication.


**Requirements:**
- ansible
- git (to clone repo)
- Dynamic Inventory (ec2.py)

**Usage:**
ansible-playbook -i ec2.py playbook.yml

-- Use ansible-vault to encrypt password vars 
