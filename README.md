# Provisioning server with Docker and ELK
> Provisioning the server with Docker and launch monitoring stack

Project created for [fictional-umbrella][1]

# Prerequisites
- Install [Ansible][2]
- `ansible-galaxy install -r requirements.yml`
- Add server hostname/IP address in `./inventory` file

# Run the playbook

```sh
# prompt for sudo & SSH pass
ansible-playbook playbook.yml -kK
```

[1]: https://github.com/dminca/fictional-umbrella
[2]: http://docs.ansible.com/ansible/intro_installation.html
