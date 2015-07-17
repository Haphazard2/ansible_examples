# ansible_examples
* user_accounts.yml # This is a playbook to create accounts on servers.  It was originally a part of a role, but I placed it here by itself as a coding example.  A vars file accompanies this playbook, which includes all of the account info for the users.  I used the "with_subelements" function in order to allow for multiple public keys.  
