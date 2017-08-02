Role Name
=========

This role installs and configures the Cloudflare plugin for certbot

Requirements
------------

N/A

Role Variables
--------------

Variables with their default:

Plugin variables:
  - dns_cloudflare_ini_location: /etc/letsencrypt/
  - dns_cloudflare_ini_permissions_owner: root
  - dns_cloudflare_ini_permissions_group: root
  - dns_cloudflare_ini_permissions_mode: 0600

Cloudflare account variables (must be set):
  - dns_cloudflare_email: ""
  - dns_cloudflare_api_key: ""

Dependencies
------------

Stouts.python

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sambaum.certbot-cloudflare }

License
-------

BSD

Author Information
------------------

None
