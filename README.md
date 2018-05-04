# Ansible - Cloudformation alternative
These two roles will deploy hosts from the `awsnd-deployer\tasks\hosts` with the command `ansible-playbook -i inventory-ec2 test-deploy.yml` and will remove those hosts with the `ansible-playbook -v -i inventory-ec2 test-purge.yml`.

Follow standard boto setup for Ansible AWS modules.

See full readme at https://github.com/AlmostGosu/awsnd.git
