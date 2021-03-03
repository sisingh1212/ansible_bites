# ansible_bites
- **prompt ansible** - prompts for a value on command line and passes it to the value defined in vars_prompt  
- **ansible_valut_with_askpass** - prompts for vault password and copies secret in a file 
    - ansible-playbook -i localhost vault_wthaskpass.yml  -e @file_wth_secret_password.yml --ask-vault-pass
