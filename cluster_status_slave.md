``` bash
root@debian-rmq2:/home/andaks# rabbitmqctl cluster_status
Cluster status of node rabbit@debian-rmq2 ...
Basics

Cluster name: rabbit@debian-rmq2.local

Disk Nodes

rabbit@debian-andaks
rabbit@debian-rmq2

Running Nodes

rabbit@debian-andaks
rabbit@debian-rmq2

Versions

rabbit@debian-andaks: RabbitMQ 3.10.8 on Erlang 25.2.3
rabbit@debian-rmq2: RabbitMQ 3.10.8 on Erlang 25.2.3

Maintenance status

Node: rabbit@debian-andaks, status: not under maintenance
Node: rabbit@debian-rmq2, status: not under maintenance

Alarms

(none)

Network Partitions

(none)

Listeners

Node: rabbit@debian-andaks, interface: [::], port: 15672, protocol: http, purpose: HTTP API
Node: rabbit@debian-andaks, interface: [::], port: 25672, protocol: clustering, purpose: inter-node and CLI tool communication
Node: rabbit@debian-andaks, interface: [::], port: 5672, protocol: amqp, purpose: AMQP 0-9-1 and AMQP 1.0
Node: rabbit@debian-rmq2, interface: [::], port: 25672, protocol: clustering, purpose: inter-node and CLI tool communication
Node: rabbit@debian-rmq2, interface: [::], port: 15672, protocol: http, purpose: HTTP API
Node: rabbit@debian-rmq2, interface: [::], port: 5672, protocol: amqp, purpose: AMQP 0-9-1 and AMQP 1.0

Feature flags

Flag: classic_mirrored_queue_version, state: enabled
Flag: drop_unroutable_metric, state: enabled
Flag: empty_basic_get_metric, state: enabled
Flag: implicit_default_bindings, state: enabled
Flag: maintenance_mode_status, state: enabled
Flag: quorum_queue, state: enabled
Flag: stream_queue, state: enabled
Flag: user_limits, state: enabled
Flag: virtual_host_metadata, state: enabled
root@debian-rmq2:/home/andaks#
```
