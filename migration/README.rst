Migration from ML2/OVS to ML2/OVN
=================================

Prerequisites:

1. ML2/OVS must be using the OVS firewall driver.

To use:

1. Create an ansible inventory with the expected set of groups and variables
   as indicated by the hosts-sample file.

2. Run the playbook::

   $ ansible-playbook migrate-to-ovn.yml -f 10 -i hosts
