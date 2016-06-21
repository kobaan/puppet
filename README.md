# puppet
Kobaan's puppet collection


Puppet fix für Could not evaluate: invalid byte sequence in US-ASCII

Fehler wenn puppet agent ohne Locale nach dem Booten startet: Puppet-Bug PUP-1055

Das hilft: /etc/default/puppet export LC_ALL=en_US.UTF-8
