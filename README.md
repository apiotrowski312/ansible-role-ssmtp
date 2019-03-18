ssmtp
=========

[![Build Status](https://travis-ci.com/apiotrowski312/ssmtp.svg?branch=master)](https://travis-ci.com/apiotrowski312/ssmtp)

Simple role to install and config ssmtp package.


Role Variables
--------------

Vars used for configuring ssmtp with default values:

```
mail_AuthUser: none
mail_AuthPass: none
mail_hostname: root
mail_root: postmaster
mail_mailhub: mail
mail_FromLineOverride: no
mail_UseSTARTTLS: no
mail_UseTLS: no
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
        - role: apiotrowski312.ssmtp
          mail_AuthUser: apiotrowski312
          mail_AuthPass: TemporaryPassword
          mail_hostname: notify@test.com

License
-------

MIT
