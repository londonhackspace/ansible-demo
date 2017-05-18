# Mini ansible playbook to setup your homedir

## How to use

- Copy to your home dir on adminstuff (the playbook relies on the list of hosts in /etc/ansible/hosts)
- edit it, at least change jasper everywhere to yourusername!
- check that it's only trying to do the dot files you want.
- run with:

~~~~
ansible-playbook -k ./me.yml
~~~~

Type your password at the prompt, and it should churn away and set everything up for you.
