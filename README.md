# zeevo.docker

Deploy Docker.

## Role Variables

```yml
# Allow users to use docker
docker_users:
  - admin
```

## Example Playbook

Use `zeevo.docker` in a Playbook.

```yml
- name: docker
  hosts: all
  become: true
  roles:
    - zeevo.docker
```

## License

MIT

## Author Information

This role was created by and is maintained by [Zeevo](https://zeevo.io).
