# ldap-mail-schema

This is a collection of LDAP schemas that could be used in a virtual mail environment consisting of Postfix, Dovecot, SASL and Roundcube.

## Postfix and Dovecot
[postfix-book.schema](https://github.com/variablenix/ldap-mail-schema/blob/master/postfix-book.schema) was originally available from _http://www.postfix-buch.com/download/postfix-book.schema.gz_ but is no longer around. Two new attributes have since been added to further enhance the schema without the need of loading multiple email specific schemas. These attributes include:

* mailSieveRuleSource
* mailForwardingAddress

Both postfix and dovecot benefit from using [postfix-book.schmea](https://github.com/variablenix/ldap-mail-schema/blob/master/postfix-book.schema) as their primary schema source.
