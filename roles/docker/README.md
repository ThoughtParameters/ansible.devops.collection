# Ansible Role: docker

This role installs and configures Docker on supported systems.

## Requirements

- Ansible 2.10+

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
docker_packages:
  - docker-ce
  - docker-ce-cli
  - containerd.io
  - docker-buildx-plugin
  - docker-compose-plugin
```

## Dependencies

None.

## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
    - role: thoughtparameters.devops.docker
```

## License

MIT

## Author Information

This role was created in 2024 by Jules.
