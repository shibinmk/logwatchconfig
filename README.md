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

Here is how a sample playbook looks like:

    - hosts: servers
      roles:
         - { role: shibinmk.logwatchconfig }

License
-------

GNU

Author Information
------------------

Shibin
shibinarayan@gmail.com
