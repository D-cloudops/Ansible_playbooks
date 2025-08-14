### Removing the unauthorized users from the server

#prequisite 
SSh keys at directory .ssh_key/

## Description

The playbook will check and create the allowed users passed by variable in {allowed_list} if not present
Then it will remove all the users other than users in allowed list 