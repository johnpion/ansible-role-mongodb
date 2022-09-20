# Ansible role 'mongodb'

## system
OS: Debian 10

## example vars
```
mongodb_default_roles: []
mongodb_version:       6.0
mongodb_admin_roles:
  - db: admin
    role: userAdminAnyDatabase
  - db: admin
    role: readWriteAnyDatabase
```
