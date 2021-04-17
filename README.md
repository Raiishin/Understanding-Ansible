

# Best Practices

## Examples

https://github.com/ansible/ansible-examples

## File Directory Layout

https://docs.ansible.com/ansible/2.8/user_guide/playbooks_best_practices.html#directory-layout

## Properly Name Tasks
```{YAML} 
tasks:
  - name: Create directory for nginx
    file:
      path: /path/to/ngix/dir
      state: directory

  - name: Install latest version of nginx
    yum:
      name: nginx
      state: latest

  - name: Start nginx
    service:
      name: nginx
      state: started
```
