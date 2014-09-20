===================
OAuthd Ansible Role
===================

Requirements
============

Centos (6.5+)

Role Variables
==============

See `defaults/main.yml` for the defaults values.

- `oauthd_host_url`: url for the service
- `oauthd_base`: base url
- `oauthd_base_api`: base url for the api
- `oauthd_staticsalt`: random string as salt
- `oauthd_publicsalt`: random string as public salt
- `oauthd_enable_ssl`: whether ssl is supported

If ssl is supported, the following variables indicate keys and certs:

- `oauthd_ssl_key`: path to the key
- `oauthd_certificate`: path to the certificate
- `oauthd_ca`: path to the ca
