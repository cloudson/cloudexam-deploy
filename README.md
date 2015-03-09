cloudexam-deploy
=======

scripts and templates to deploy microservices of cloudexam application

## Requirements

* Ansible (apt-get install ansible)
* Boto (pip install boto)


## Steps 

1) copy vars/ec2.yml.template to vars/ec2.yml
2) complete the informations in vars/ec2.yml
3) run `sudo ansible-playbook create-instances.yml --private-key=/path/chairkey.pem`
