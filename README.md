# How to

1. First edit the "host" file to populate the IP address of the nodes
2. Run master setup
```
ansible-playbook setup_master_nodes.yml
```

3. Once the master setup finished
```
ansible-playbood setup_worker_nodes.yml
```