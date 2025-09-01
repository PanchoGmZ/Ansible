README breve: InnovaSys Ansible
1) Editar inventory/hosts.ini con IP y usuario si es necesario.
2) Editar group_vars/innovasys.yml para cambiar nombre_empresa y samba_password
3) ansible-playbook -i inventory/hosts.ini site.yml
