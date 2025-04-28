## Ansible Playbook Commands

### Run the playbook using the below command:
```bash
$ ansible-playbook playbook.yml

### Run the playbook in verbose mode:
$ ansible-playbook playbook.yml -vvv

## Get playbook helpful commands:
$ ansible-playbook --help

## To check the syntax of a playbook:
$ ansible-playbook playbook.yml --syntax-check

## To execute the playbook in dry run mode:
$ ansible-playbook playbook.yml --check

## To display which hosts would be affected by the playbook before running:
$ ansible-playbook playbook.yml --list-hosts

## Execute one step at a time (manual confirmation required):
$ ansible-playbook playbook.yml --step
