mashape.node
=========
[![License][license]][license-url]

[license-url]: http://choosealicense.com/licenses/isc/
[license]: https://img.shields.io/npm/l/simon-promise.svg?style=flat-square

Installs node from https://github.com/nodesource/distributions/tree/master/deb

Role Variables
--------------

node_version: 4.x, 5.x, 6.x etc

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mashape.node, node_version: 4.x }

License
-------

ISC
