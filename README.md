# infrastructure
##aim
Just a repo to put my staff to create a data science machine.

This repo will most probably contains only an ansible playbook.

For those not familiar with ansible look [here] (http://docs.ansible.com/ansible/playbooks.html).
I assumed the starting OS would be ubuntu 16.04.

## steps:
###install ansible
```
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```
###run a playbook
`sudo ansible-playbook -i "localhost, " -c local [script.yml]`

script.yml is the file containing the playbook.

## assumptions
> this machine will be able to develop code on java, python and R.





