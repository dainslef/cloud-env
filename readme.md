# dainslef-cloud-environment-config
Debian package for setting up my VPS enviroment in a short time.

Build package:

```html
<!-- Generate deb package in current directory. -->
$ dpkg-deb --build $REPO_ROOT/dainslef-cloud-environment-config
<!-- Generate deb package in custom path. -->
$ dpkg-deb --build $REPO_ROOT/dainslef-cloud-environment-config xxx_path/dainslef-cloud-environment-config.deb
```

Usage:

```html
<!-- Use Ansible to run the playbook. -->
$ ansible-playbook playbook.yaml
```
