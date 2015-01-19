# ansible-firewall
Ansible role for shorewall provisioning

site.yml:
---
- name: Install openvpn
  hosts: localhost

  roles:
    - openvpn
