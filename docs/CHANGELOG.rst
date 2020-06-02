
Changelog
=========

`0.19.0 <https://github.com/saltstack-formulas/tomcat-formula/compare/v0.18.0...v0.19.0>`_ (2020-05-28)
-----------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** add new platforms [skip ci] (\ `91e57b5 <https://github.com/saltstack-formulas/tomcat-formula/commit/91e57b5672e2a9f93fe9cf8f216ce513ba89b613>`_\ )
* **kitchen+travis:** adjust matrix to add ``3000.2`` & remove ``2018.3`` [skip ci] (\ `fea7a6c <https://github.com/saltstack-formulas/tomcat-formula/commit/fea7a6c07f4ca7e7273b9c0d406941f5d53bcb09>`_\ )
* **kitchen+travis:** adjust matrix to add ``3000.3`` [skip ci] (\ `b378533 <https://github.com/saltstack-formulas/tomcat-formula/commit/b378533a10cc11e339c81e40d7ef39a13f137870>`_\ )
* **kitchen+travis:** remove ``master-py2-arch-base-latest`` [skip ci] (\ `7ee2926 <https://github.com/saltstack-formulas/tomcat-formula/commit/7ee2926402e291243edf301b8733f24d80a22518>`_\ )
* **kitchen+travis:** use new platforms (\ `2fd6f92 <https://github.com/saltstack-formulas/tomcat-formula/commit/2fd6f92a7976b42b61a21687b67a425b0ca5f54e>`_\ )
* **travis:** add notifications => zulip [skip ci] (\ `65a5733 <https://github.com/saltstack-formulas/tomcat-formula/commit/65a5733198495632fc08da803fce832b4adc81ca>`_\ )
* **workflows/commitlint:** add to repo [skip ci] (\ `2451442 <https://github.com/saltstack-formulas/tomcat-formula/commit/2451442b07659439ade466a0f2626482f24514f8>`_\ )

Features
^^^^^^^^


* support new platforms (\ ``ubuntu-20.04`` & ``fedora-32``\ ) (\ `fce35a5 <https://github.com/saltstack-formulas/tomcat-formula/commit/fce35a522d8effc99f0d1e03e0ed63518c114530>`_\ )

`0.18.0 <https://github.com/saltstack-formulas/tomcat-formula/compare/v0.17.2...v0.18.0>`_ (2020-04-27)
-----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **cluster:** set accumlator name (\ `51f2968 <https://github.com/saltstack-formulas/tomcat-formula/commit/51f2968ed0014079d392b52fc613e181bce3501f>`_\ )
* **fedora:** use ``ver: 9`` (Jasper Listener deprecated in tomcat >= 8) (\ `ba9cbf1 <https://github.com/saltstack-formulas/tomcat-formula/commit/ba9cbf12f79702b18eb0b5c95b62f219281f44fc>`_\ )
* **native:** use EPEL repo for ``amazonlinux-2`` (\ `242f063 <https://github.com/saltstack-formulas/tomcat-formula/commit/242f06378e4e9772be9f3ebffbe26ed3ca45bdb3>`_\ )
* **server.xml:** replace tabs with spaces (\ `58d65f9 <https://github.com/saltstack-formulas/tomcat-formula/commit/58d65f91e46aa2174985f4728da69e5efcd9c4ce>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis+inspec:** merge test suites into single ``default`` suite (\ `429c56e <https://github.com/saltstack-formulas/tomcat-formula/commit/429c56e9b940e03f0b24ecb93540961fd450737b>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** switch mixed-up state descriptions (\ `d43958f <https://github.com/saltstack-formulas/tomcat-formula/commit/d43958fe613312d74b5f78c973081a31c8a923f1>`_\ )

Features
^^^^^^^^


* **osfingermap:** add settings for ``debian-8`` (\ `7c86d80 <https://github.com/saltstack-formulas/tomcat-formula/commit/7c86d801ef492dc210ad8dc396502d9b60e0129b>`_\ )

Tests
^^^^^


* update and fix all tests (inc. provide files for comparison) (\ `50262c3 <https://github.com/saltstack-formulas/tomcat-formula/commit/50262c3c012b0ebdb86810edd04793c31d2a0a79>`_\ )

`0.17.2 <https://github.com/saltstack-formulas/tomcat-formula/compare/v0.17.1...v0.17.2>`_ (2020-04-27)
-----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **config.sls:** ensure catalina_tmpdir created with correct permissions (\ `4b5387f <https://github.com/saltstack-formulas/tomcat-formula/commit/4b5387f412766558962ea92d1f9fd9a852562c2a>`_\ )
* **debian:** define catalina_* variables for Debian based OSes (\ `7062834 <https://github.com/saltstack-formulas/tomcat-formula/commit/706283490bb52eda7b191f458efd0ef7cbadd55b>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile.lock:** add to repo with updated ``Gemfile`` [skip ci] (\ `479c014 <https://github.com/saltstack-formulas/tomcat-formula/commit/479c0147bedb57cca8d670e92387fa806fe5dbfc>`_\ )

Tests
^^^^^


* **yaml_dump:** update tests for changed catalina_* variables (\ `20cbcb8 <https://github.com/saltstack-formulas/tomcat-formula/commit/20cbcb82c6d81ef07bef6d24936b420d096fafea>`_\ )

`0.17.1 <https://github.com/saltstack-formulas/tomcat-formula/compare/v0.17.0...v0.17.1>`_ (2020-04-21)
-----------------------------------------------------------------------------------------------------------

Code Refactoring
^^^^^^^^^^^^^^^^


* standardise structure from the ``template-formula`` (\ `db49764 <https://github.com/saltstack-formulas/tomcat-formula/commit/db49764ef1af145e9469f5dcd888a2b2779b04f3>`_\ )
* **map.jinja:** use ``template-formula`` structure & add ``debian-10`` (\ `d1bb84f <https://github.com/saltstack-formulas/tomcat-formula/commit/d1bb84fdf0c788044ff6b72d45c7dc033346aac6>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **travis+inspec:** test ``debian-10`` as well (\ `9b2bab5 <https://github.com/saltstack-formulas/tomcat-formula/commit/9b2bab530575f90ce9070bd4e64ecc026ac73d1c>`_\ )

`0.17.0 <https://github.com/saltstack-formulas/tomcat-formula/compare/v0.16.0...v0.17.0>`_ (2020-04-20)
-----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **rubocop:** fix (or exclude) all violations (\ `ead2d21 <https://github.com/saltstack-formulas/tomcat-formula/commit/ead2d21b12ce97a58f0108ca8027667c1027bd4e>`_\ )
* **salt-lint:** fix all violations (\ `579ea68 <https://github.com/saltstack-formulas/tomcat-formula/commit/579ea689936c50b5b11b3e621ef044d69bb5c5b0>`_\ )
* **yamllint:** fix (or ignore) all errrors (\ `d50126a <https://github.com/saltstack-formulas/tomcat-formula/commit/d50126a333511f77ae6645357cdf0a5611a2ecaa>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** apply standard structure (\ `a1365ef <https://github.com/saltstack-formulas/tomcat-formula/commit/a1365ef0ebea176e9892fb06730493ddd09b6e33>`_\ )

Features
^^^^^^^^


* **semantic-release:** implement for this formula (\ `7e4ced7 <https://github.com/saltstack-formulas/tomcat-formula/commit/7e4ced79821cb78d0dc1bc996c2d7c193e19281f>`_\ )

Tests
^^^^^


* add tests for packages and services (\ `d1b4f3a <https://github.com/saltstack-formulas/tomcat-formula/commit/d1b4f3ae67b3be3a2fb5302f1c8c0dd549ed8c97>`_\ )
* **yaml_dump:** add to ``tomcat_install`` suite (\ `c948f8b <https://github.com/saltstack-formulas/tomcat-formula/commit/c948f8b1eb7017c8c3d08e9d4023f573309908c6>`_\ )
