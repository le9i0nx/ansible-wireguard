

```YAML
---

- name: wireguard install
  hosts:
    - service_wireguard_server
    - service_wireguard_client
  become: True

  roles:

    - role: le9i0nx.wireguard
      tags: [ 'role::wireguard' ]

```
