# Best Practices

## File Directory Layout

https://docs.ansible.com/ansible/2.8/user_guide/playbooks_best_practices.html#directory-layout

## Properly Name Tasks

tasks:

- name: Create directory for nginx
  file:
  path: /path/to/ngix/dir
  state: directory
