Role Name
=========

A brief description of the role goes here.

Requirements
------------

Make sure all nodes are accessible via passwordless ssh

Role Variables
--------------

Please make sure you have the GUID environment variable set:

 export GUID=`hostname | awk -F"." '{print $2}'`


Example Playbook
----------------

ansible-playbook -i hosts main.yml

License
-------

OpenSource

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
# sleek-ansible
