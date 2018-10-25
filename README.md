NGB-deploy
=========

Assuming you are in a python3 virtual environment (either plain `python -mvenv venv` or via `conda`):

    `pip install ansible boto3 botocore`
    `ansible-playbook site.yml --extra-vars='{ ansible_python_interpreter: "/usr/bin/python3" }' -i ec2-13-211-159-178.ap-southeast-2.compute.amazonaws.com,`

License
-------

GPL-v3