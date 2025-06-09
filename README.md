## Ansible Playbook Commands

### Run the playbook Using below command
```
$ ansible-playbook playbook.yml
```
### Run the playbook.yml in verbose
```
$ ansible-playbook playbook.yml -vvv
```
### Get Playbook helpful commands
```
$ ansible-playbook --help
```
### To Check syntax of playbook
```
$ ansible-playbook playbook.yml --syntax-check
```
### To Execute playbook in dry run mode
```
$ ansible-playbook playbook.yml --check
```
### To Display which hosts would be effected by a playbook before run
```
$ ansible-playbook playbook.yml --list-hosts
```
### Execute one step at a time (Manual Confirmation Required)
```
$ ansible-playbook playbook.yml --step
```
