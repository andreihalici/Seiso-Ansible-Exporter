Ansible Seiso Exporter
===============================

POC on how to use Ansible with the URI module to add Seiso data using the REST API with support for services, service groups, service types, rotation statuses and status types.

How to run
===============================
# Please make sure you set seiso_url in seiso_vars.yml before running the playbook
ansible-playbook seiso-onboarding.yml
