
# Deploy nexus using Ansible


## Requirement

-  A remote server (ec2) running an Ubuntu operating system
   
- install Ansible on your local machine
- Add inventory file contain ip of ec2
-  configured SSH connection to the remote server


## Playbook Overview
The Ansible playbook consists of two roles:
- Prerequisites
This role installs the necessary packages and dependencies for running Nexus, including Java.
- Nexus
This role deploys and configures Nexus on your remote server ec2 on aws.



## How to Run the Playbook

#### Open a terminal on the local machine

#### Navigate to the directory containing the playbook.
##### Run the playbook using the following command:

```http
  ansible-playbook -i inventory deploy-nexus.yml

```



