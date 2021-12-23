# detect-log4j-jars
Ansible playbook to detect vulnerable log4j jar files


## Usage

```ansible-playbook detect-log4j-jars.yml -i inventory.yml --extra-vars "servers=<host groups>"```

Where host groups can be defined in your inventory.yml file as below:

```
[prod]
server1.example.com
server2.example.com

[dev]
dev1.example.com
dev2.example.com
```
