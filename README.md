# aws-scripts-ansible
ansible playbook scripts to create aws instances

Install python latest version

install pyhton-pip latest version

install boto { pip install boto }

install ansible latest version

Remember one thing is that Ansible uses the boto configuration file (typically ~/.boto) if no credentials are provided.
you can provide credentials in .boto file

AWS_ACCESS_KEY_ID = 
AWS_SECRET_ACCESS_KEY =

Now in your ansible working directory you can write playbook. lightsail.yml
Always check syntax before using playbook
ansible-playbook --syntax-check lightsail.yml

