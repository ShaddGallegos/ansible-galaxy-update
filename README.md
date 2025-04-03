# ansible-galaxy-update 
ansible-galaxy-wrapper - Installs collections while skipping failures
Crazy requirements.yml included in repo to show report after install

- installed 
- failed to install
- warnings

The script wont fail if you run into an issue installing collections it will report on failures so you can open a suppport ticket if needed easier output on the eyes 

ansible-galaxy-update collection install -r requirements.yml 
