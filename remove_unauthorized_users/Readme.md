### Removing the unauthorized users from the server

## Description

The playbook will check and create the allowed users passed by variable in {allowed_list} if not present
Then it will remove all the users other than users in allowed list 

## How to use?

1. Clone this repo
2. Fill the nodes detail in inventory file in YAML format
3. Update the list of allowed users list under the group_vars 