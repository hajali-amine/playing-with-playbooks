# Playing with Playbooks

The goal of this repository is to test out deploying an Nginx server using the _Configuration Management_ tool __Ansible__.

## Process

1. Install Nginx in the virtual machine.
1. Copy the HTML page that will be rendered.
1. Create a new server configuration that will render the HTML page.
1. Enable it using Symbolic link.
1. Restart Nginx.

## Requirements

A virtual machine. Please change _./hosts_ like this;

``` text
ws1 ansible_host=<IP_ADDRESS> ansible_user=<USERNAME> ansible_ssh_private_key_file=<PATH_TO_SSH_PRIVATE_KEY>
```
