# In this Description Box ALL the Brief of this Project is given

# **PREREQUSITE OF THIS REPO**

## 1. Ansible
## 2. Python boto Module   **pip3 install boto**

## 3. Put the file # Dynamic_Inventory.py in some folder so that you have to give the path in inventory file
## 4. Configure the Inventory file
#      **  [defaults]
#      **  inventory=/location/of/Dynaimc_Inventory.py/file
#      **  Host_Key_checking=false
#      **  remote_user= ec2-user
#      **  private_key_file=/location/of/your/aws/private/key.pem
      
#      **  [privilege_escalation]
#      **  become=true
#      **  become_method=sudo
#      **  become_user=root

