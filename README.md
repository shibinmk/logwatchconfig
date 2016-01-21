Role Name
=========

Logwatch will record all activities from your linux machine. 

MailTo: The email address to which daily reports are sent

MailFrom: mail origin

Range: range for reports.

Detail: Reports detail

Service: Logwatch covers all services under the machine. You can choose it either ALL or some specific ones. 

Requirements
------------

There is no specific pre-requisites for logwatch 

Dependencies
------------

No dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.logwatchconfig }

License
-------

GNU

Author Information
Shibin  (shibinarayan@gmail.com)
