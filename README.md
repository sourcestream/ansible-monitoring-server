monitoring-server
=========

This role exposes:

uchiwa: 0.0.0.0:{{monitoring_dashboard_port}}
rabbitmq: 0.0.0.0:{{monitoring_port}}
sensu-api: 0.0.0.0:4567 -- is not configurable as per upstream

Requirements
------------

Role Variables
--------------

Dependencies
------------

DavidWittman.redis
Mayeu.RabbitMQ
Mayeu.sensu
monitoring-client

Example Playbook
----------------


License
-------

MIT

Author Information
------------------
