Getting started
===============

.. contents::
   :local:


Example inventory
-----------------

To enable the borg_server service on a host, it needs to be included in the
``[debops_service_borg_server]`` Ansible inventory group:

.. code-block:: none

   [debops_service_borg_server]
   hostname


Example playbook
----------------

If you are using this role without DebOps, here's an example Ansible playbook
that uses the ``debops.borg_server`` role:

.. literalinclude:: playbooks/borg_server.yml
   :language: yaml
