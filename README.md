check_squid
===========

The check_squid monitoring plugin uses the squidclient binary to monitor a Squid proxy.

Requriements
------------

**General**

- Perl 5
- Perl Modules:
    - Nagios::Plugin

**RHEL/CentOS**

- perl
- perl-Nagios-Plugin

Installation
------------

Just copy the file `check_squid` to your Icinga or Nagios plugin directory.

Config
------

**Icinga2**

The CheckCommand definition is included in the [Icinga Template Library (ITL)](https://icinga.com/docs/icinga2/latest/doc/10-icinga-template-library) for more information about the CheckCommand and the available parameters have a look at the [SQUID section in the Icinga2 documentation](https://icinga.com/docs/icinga2/latest/doc/10-icinga-template-library/#squid).

Source
------

- [Latest source at git.dinotools.org](https://git.dinotools.org/monitoring/check_squid)
- [Mirror at github.com](https://github.com/DinoTools/monitoring-check_squid)

History
-------

Cyril Feraudet is the orignal author if this plugin. He has published his work on GitHub [feraudet/check_squid](https://github.com/feraudet/check_squid). In April 2019 the last commit has been pushed to this repository on 20 November 2012.

License
-------

GPLv2+

See the LICENSE.md for additonal information.
