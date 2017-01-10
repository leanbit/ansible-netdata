leanbit.netdata
=========

Install and update netdata.

Requirements
------------

* Systemd (optional)

Role Variables
--------------

    netdata_install_dir: /opt
    netdata_systemd: True
    netdata_deps:
      - zlib1g-dev
      - uuid-dev
      - libmnl-dev
      - gcc
      - make
      - git
      - autoconf
      - autoconf-archive
      - autogen
      - automake
      - pkg-config
    netdata_version: v1.4.0

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - leanbit.netdata

License
-------

MIT

Author Information
------------------

Leanbit srl
