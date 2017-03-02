ansible-rabbitmq-packages
=========================

[![Build Status](https://travis-ci.org/jmatt/ansible-rabbitmq-packages.svg?branch=master)](https://travis-ci.org/jmatt/ansible-rabbitmq-packages)

Install and simple configuration of [RabbitMQ](https://www.rabbitmq.com/) for LSST SQuaRE infrastructure.


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jmatt.rabbitmq-packages }

License
-------

The MIT License. See the [LICENSE file](https://github.com/jmatt/ansible-rabbitmq-packages/blob/master/LICENSE).
