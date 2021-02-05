# In this Description Box ALL the Brief of this Project is given

# **PREREQUSITE OF THIS REPO**

# 1. Ansible
# 2. Python boto Module   **pip3 install boto**
# 3. AWS SECRET KEY  **export AWS_ACCESS_KEY_ID='ACCESS KEY'**
# 4. AWS SECRET ACCESS KEY  **export AWS_SECRET_ACCESS_KEY='AWS ACCESS KEY'**


## 5. Put the file # Dynamic_Inventory.py in some folder so that you have to give the path in inventory file
## 6. Configure the Ansible Config file
#      **  [defaults]
#      **  inventory=/location/of/Dynaimc_Inventory.py/file
#      **  Host_Key_checking=false
#      **  remote_user= ec2-user
#      **  private_key_file=/location/of/your/aws/private/key.pem
      
#      **  [privilege_escalation]
#      **  become=true
#      **  become_method=sudo
#      **  become_user=root

# 7. Run the "Configure_EC2.yml" file to launch 1 master and 2 worker node
# 8. Before Run the any program run this command
##    ** chmod 400 private_key_of_aws.pem

# 9. Run the file "Configure_Master.yml" to configure the master node
# 10. Run the file "Configure_Worker.yml" to configure worker node
