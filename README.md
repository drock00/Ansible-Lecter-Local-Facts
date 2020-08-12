# Ansible-Lecter-Local-Facts

### Create some simple facts about samba and use them on the managed nodes

This is simply a demo on how to create your own local facts and copy them over to manage nodes. Create a facts directory on the managed nodes and copy over some hidden gems. 

# Example Run 1
```sh
$ ansible-playbook localfactsplay.yml 
```

# Validate using adhoc

```sh
$ ansible-playbook ansible22.example.com -m setup -a "filter=ansible_local"
```

### Tech and Running the file

Bash shell, boom. You should probably be setting up a lab of virtual hosts. 