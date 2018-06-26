# Ansible Role: nginx

Forked role from Geerlingguy Ansible Role nginx (https://galaxy.ansible.com/geerlingguy/nginx/). It's only compatible with Debian.

This role installs nginx latest version from the nginx.org package repo and allow to handle with WordPress and addons like WP-Rocket. Cloudflare CDN configuration is also supported.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - ansible-role-debian-nginx
```

## License

MIT / BSD

