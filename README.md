Role Name
=========

Install Debian Apt-Packages

Requirements
------------

- none

Role Variables
--------------

- #### BASE_PACKAGES__DEB_CACHE_VALID_TIME
  Default 3600
- #### BASE_PACKAGES__DEB
  List of apt-packages to be installed


Dependencies
------------

- none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: yes
      roles:
      - role: ansible-role-deb_packages
        BASE_PACKAGES__DEB:
        - sudo
        - htop

License
-------

GPLv3

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
