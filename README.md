## Ansible playbook to setup a WebDAV server

### How to use it

- Clone the repository
- Create a variable file (Example: `group_vars/all.yml`)

**Available variables**
```
email: email@service.com
webdav_domain: webdav.yourdomain.com
webdav_root: /srv/webdav
webdav_users:
  - username: webdav_user1
    password: 'strongpassword'

  - username: webdav_user2
    password: 'differentstrongpassword'

fail2ban_bantime: 30d
```