Usage
=====

**unifi-backup** is a simple tool to fetch configuration backups from
the UniFi Network Application.

Arguments
----------------

``-h``, ``--help``
   show the help message and exit.

``-c FILE``, ``--c FILE``
   the configuration file (default: ``~/.config/unifi-backup/config.yml``)

Configuration file
==================

The ``unifi-backup`` needs a configuration file
(default ``~/.config/unifi-backup/config.yml``). As the file contains secrets,
take care to set reasonable permissions. The file is in
the `YAML <https://yaml.org/>`_ format.

Configuration file
------------------

.. code-block:: yaml

    unifi:
