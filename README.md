Ansible role: OpenSSH server
=========

Configures OpenSSH server.

Requirements
------------

None.

Role Variables
--------------

    ssh_Port: 22
    ssh_PermitRootLogin: "no"
    ssh_PubkeyAuthentication: "yes"
    ssh_PermitEmptyPasswords: "no"
    ssh_PasswordAuthentication: "no"

Dependencies
------------

None.

Example Playbook
----------------

After configured, restart sshd manually.

    - hosts: servers
      roles:
         - { role: shomatan.openssh-server }

License
-------

MIT

Author Information
------------------

Shoma Nishitateno