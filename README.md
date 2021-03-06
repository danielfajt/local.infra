# Following services are included:

### **MongoDB**
- name: mongodb
- exposed port: 27017

### **ArangoDB**
- name: arangodb
- exposed port: 8529

### **PostgresSQL**
- name: postgres
- exposed port: 5432

### **pgAdmin4**
- name: pgadmin
- exposed port: 8000

### **RabbitMQ**
- name: rabbitmq
- exposed ports: 5672, 15672

### **Elasticsearch**
- name: elasticsearch
- exposed ports: 9200, 9300

### **Elasticsearch (no auth)**
- name: elasticsearch-noauth
- exposed ports: 9200, 9300

### **Fluentbit**
- name: fluentbit
- exposed ports: 24224
- config file: ./fluentd-bit/etc/fluent-bit.conf

### **Fluentd**
- name: fluentd
- exposed ports: 24224
- config file: ./fluentd/etc/fluentd.conf


<br><br>

# Network
You have to manually create a docker network first:
```
$docker network create mydevnetwork
```
