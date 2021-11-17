# ansible-hero

## setup:

- Install AWS CLI, Python > 2.6 and Ansible
$ aws configure

- Change path of file users.csv

- Install aws module:
$ ansible-galaxy collection install community.aws
https://docs.ansible.com/ansible/latest/collections/community/aws/iam_module.html
https://docs.ansible.com/ansible/latest/scenario_guides/guide_aws.html

- Verify module installed: 
$ ansible-galaxy collection list

Collection    Version
------------- -------
amazon.aws    2.0.0
community.aws 2.0.0

## run tests:

$ ansible-playbook main-playbook


