ansible_role_local_yum_repo
===========================

A role that sets up the services and installs the required software to run a local yum/dnf/rpm repository.
The fake package `files/fake_rpm-1.0.0-0.x86_64.rpm` is provided for testing.

Requirements
------------


Role Variables
--------------

Repository is served by apache. We assume that the repo is in the default location for apache (`/var/www/html`), so no further setup is done. The sub-folder can still be defined:

```
local_yum_repo_folder: /var/www/html/yum_repo
```


Dependencies
------------

Example Playbook
----------------


License
-------

BSD

Author Information
------------------

Written by Simppa Äkäslompolo from Aalto Scientific Computing https://scicomp.aalto.fi/
