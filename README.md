# mongodb-mms-server

[![Build Status](https://travis-ci.org/Temelio/ansible-role-mongodb-mms-server.svg?branch=master)](https://travis-ci.org/Temelio/ansible-role-mongodb-mms-server)

Install mongodb-mms-server package.

## Requirements

This role requires Ansible 2.0 or higher,
and platform requirements are listed in the metadata file.

## Testing

This role has some testing methods.

To use locally testing methods, you need to install Docker and/or Vagrant and Python requirements:

* Create and activate a virtualenv
* Install requirements

```
pip install -r requirements_dev.txt
```

### Automatically with Travis

Tests runs automatically on Travis on push, release, pr, ... using docker testing containers

### Locally with Docker

You can use Docker to run tests on ephemeral containers.

```
make test-docker
```

### Locally with Vagrant

You can use Vagrant to run tests on virtual machines.

```
make test-vagrant
```

## Role Variables

### Default role variables

``` yaml
```

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
         - { role: Temelio.mongodb-mms-server }

## License

MIT

## Author Information

Alexandre Chaussier (for Temelio company)
- http://temelio.com
- alexandre.chaussier [at] temelio.com

