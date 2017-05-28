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

# Infra topology

[![topology](/topology.png)](/topology.png)

# Hands on guide

[![asciicast](https://asciinema.org/a/1y58sz24xssfbgtchfvh4z9uc.png)](https://asciinema.org/a/1y58sz24xssfbgtchfvh4z9uc)

[1]: https://github.com/dminca/fictional-umbrella
[2]: http://docs.ansible.com/ansible/intro_installation.html
