cm-exittask
===========

normal mode:
$ ansible-playbook site.yml -i hosts

set maintenance mode:
$ ansible-playbook site.yml -i hosts --extra-vars "maintenance_mode=On"