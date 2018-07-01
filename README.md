# LDAP Mail Schema

This is a collection of LDAP schemas that could be used in a virtual mail environment consisting of Postfix, Dovecot and Roundcube.

## Postfix and Dovecot
[postfix-book.schema](https://github.com/variablenix/ldap-mail-schema/blob/master/postfix-book.schema) was originally available from _http://www.postfix-buch.com/download/postfix-book.schema.gz_ but is no longer around. Two new attributes have since been added to further enhance the schema to avoid the need of loading multiple different mail specific schemas. These attributes include:

```
mailSieveRuleSource
mailForwardingAddress
```

Both Postfix and Dovecot benefit from using [postfix-book.schema](https://github.com/variablenix/ldap-mail-schema/blob/master/postfix-book.schema) as their primary schema source.
