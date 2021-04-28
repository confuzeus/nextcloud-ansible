Nextcloud automated installation
=========

This playbook will prepare an Ubuntu 20.04 host for Nextcloud.

It uses default PHP, Apache, and SQLite.

Role Variables
--------------

A sample variables file named `main.sample.yml` is in the vars directory. Rename this file to
`main.yml` and change the values to your liking starting the play.

Tutorial
----------------

1. Rename `inventory.sample.yml` to `inventory.yml` and change the hosts lists (by default `host_name`) to match your own.
2. Setup your variables in `main.yml`.
3. Run the play using the included `start` shell script.
4. The play doesn't setup an ssl certificate. You have to do that manually.
5. Proceed to <your-domain.com>/nextcloud to start the installation process.

License
-------

BSD

Author Information
------------------

Michael Karamuth
