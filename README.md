httpd
=========

Installs Apache on RHEL OS and open port 80 in the firewall

Requirements
------------

None

Role Variables
--------------

Defaults:

package:
   - httpd

Add list to variable to install futher packages

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - jesperberth.httpd

License
-------

BSD

Author Information
------------------

Jesper Berth