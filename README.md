## Ansible contains a number of modules for controlling Amazon Web Services (AWS).
#### Requirements:
All of the modules require and are tested against recent versions of boto. You’ll need this Python module installed on your control machine. Boto can be installed from your OS distribution or python’s “pip install boto”.
#### Authentication:
Authentication with the AWS-related modules is handled by either specifying your access and secret key as ENV variables or module arguments.

Connecting to AWS cloud using AWS_ACCESS_KEY and AWS_SECRET_ACCESS_KEY:
```
$ export AWS_ACCESS_KEY_ID=‘YOUR_AWS_API_KEY'
$ export AWS_SECRET_ACCESS_KEY=‘YOUR_AWS_API_SECRET_KEY’
```
Download and export AWS python “ec.py” script and configuration file  “ec.ini” environment variable to access aws instances:
```
$ export ANSIBLE_HOSTS=/etc/ansible/ec2.py 
$ export EC2_INI_PATH=/etc/ansible/ec2.ini
```
