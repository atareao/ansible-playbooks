# Ansible Playbooks

This is a collection of playbooks to make my life easier, and avoid repeat taks one time and again

repeat taks one time and again


## Some somples

### Make a ping to all hosts in inventory

```
ansible all -i inventory.yml -m ping
```

### Update all hosts in inventory

```
ansible-playbook -i inventory.yml update
```

### Install docker in all webs

Add docker repository and add `ubuntu` user to docker group

```
ansible -i inventory.yml install_docker.yml
```




