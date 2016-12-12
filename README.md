Leanote
=========

This role installs and configures the Leanote application.

Requirements
------------

At this time, there seem to be no special requirements.


Role Variables
--------------

```
leanote_install_dir # The directory in which to install
leanote_start_script # The start-script path
leanote_port # The port on which Leanote will listen
```

Dependencies
------------

No dependencies, yet.

Example Playbook
----------------

```
    - hosts: server
      roles:
         rjongejan.leanote
```

License
-------

MIT

Author Information
------------------

Ruben Jongejan
