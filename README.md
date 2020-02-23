# ansible-nginx-load-balancer

Ansible role to install/configure an NGINX load balancer for:

## Usages

- HTTP Load Balancing
- HTTPS Load Balancing
  - SSL Termination
  - Self Signed Certs
- TCP Load Balancing
- UDP Load Balancing
- HA (Highly Available) Setup

## Build Status

### GitHub Actions

![Molecule Test](https://github.com/mrlesmithjr/ansible-nginx-load-balancer/workflows/Molecule%20Test/badge.svg)

### Travis CI

[![Build Status](https://travis-ci.org/mrlesmithjr/ansible-nginx-load-balancer.svg?branch=master)](https://travis-ci.org/mrlesmithjr/ansible-nginx-load-balancer)

## Requirements

For any required Ansible roles, review:
[requirements.yml](requirements.yml)

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

The following Ansible roles **should** be used along with this `ansible-nginx-load-balancer` role.

- [ansible-etc-hosts](https://github.com/mrlesmithjr/ansible-etc-hosts)
  - Provides the ability to update `/etc/hosts` with all hosts which are part of the solution
- [ansible-keepalived](https://github.com/mrlesmithjr/ansible-keepalived)
  - Provides the ability to provide the `VIP` for `HA` of multiple `ansible-nginx-load-balancer` nodes.

You can install the above roles using `ansible-galaxy` and the included [requirements](requirements.yml)

```bash
ansible-galaxy install -r requirements.yml
```

## Example Playbook

[playbook.yml](playbook.yml)

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
- [http://everythingshouldbevirtual.com](http://everythingshouldbevirtual.com)

> NOTE: Repo has been created/updated using [https://github.com/mrlesmithjr/cookiecutter-ansible-role](https://github.com/mrlesmithjr/cookiecutter-ansible-role) as a template.
