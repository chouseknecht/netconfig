Role Name
=========

Demonstrats the power of the new Ansible network modules by executing a simple port shutdown command on any interface of a given network device.


Role Variables
--------------
port_shutdown_debug
   Turn on detailed debug info. Use for troubleshooting. Debug info will be written to the log file. See port_shutdown_logfile.

port_shutdown_logfile
   Control the path of the logfile. 

port_shutdown_remove_log_on_start
   Defaults to True. Will remove the log file before execution. Otherwise, each run appends to the log file.

port_shutdown_authorize
   Put the device in privileged mode prior to executing the shutdown command.

port_shutdown_username
   Username for authenticating with the device.

port_shutdown_password 
   Password for authentication.

port_shutdown_use_ssl
   Defaults to True. Will use https when connecting to the device's API.



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Chris Houseknecht @chouseknecht
Principal Engineer
Ansible / Red Hat
