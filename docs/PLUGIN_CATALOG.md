This is the master catalog of plugins for snap. The plugins in this list may be written by multiple sources. Please examine the license and documentation of each plugin for more information.

## Maintained plugins

### Intel®

| Name  | Type  | Description | Link |
| :---- | :---- | :---------- | :--- |
| CEPH | Collector | Collects from CEPH cluster | [snap-plugin-collector-ceph](https://github.com/intelsdi-x/snap-plugin-collector-ceph)
| Docker | Collector | Collects from Docker engine | [snap-plugin-collector-docker](https://github.com/intelsdi-x/snap-plugin-collector-docker)
| Ethtool | Collector | Collect from ethtool stats & registry dump |[snap-plugin-collector-ethtool](https://github.com/intelsdi-x/snap-plugin-collector-ethtool)
| Facter | Collector | Collects from Facter | [snap-plugin-collector-facter](https://github.com/intelsdi-x/snap-plugin-collector-facter)
| IOstat | Collector | Collect from IOstat | [snap-plugin-collector-iostat](https://github.com/intelsdi-x/snap-plugin-collector-iostat)
| Libvirt | Collector | Collects from libvirt | [snap-plugin-collector-libvirt](https://github.com/intelsdi-x/snap-plugin-collector-libvirt)
| NodeManager | Collector | Collects from Intel Node Manager | [snap-plugin-collector-node-manager](https://github.com/intelsdi-x/snap-plugin-collector-node-manager)
| PCM | Collector | Collects from PCM.x | [snap-plugin-collector-pcm](https://github.com/intelsdi-x/snap-plugin-collector-pcm)|
| Perfevents | Collector | Collects perfevents from Linux | [snap-plugin-collector-perfevents](https://github.com/intelsdi-x/snap-plugin-collector-perfevents)|
| PSUtil | Collector | Collects from psutil | [snap-plugin-collector-psutil](https://github.com/intelsdi-x/snap-plugin-collector-psutil) |
| SMART | Collector | Collects SMART metrics from Intel SSDs | [snap-plugin-collector-smart](https://github.com/intelsdi-x/snap-plugin-collector-smart) |
| OSv | Collector | Collect from OSv | [snap-plugin-collector-osv](https://github.com/intelsdi-x/snap-plugin-collector-osv) |
 |
| Movingaverage | Processor | Processes data and outputs movingaverage | [snap-plugin-processor-movingaverage](https://github.com/intelsdi-x/snap-plugin-processor-movingaverage) |
 |
| HANA | Publisher | Writes to SAP HANA Database | [snap-plugin-publisher-hana](https://github.com/intelsdi-x/snap-plugin-publisher-hana) |
| InfluxDB | Publisher | Writes to Influx Database | [snap-plugin-publisher-influxdb](https://github.com/intelsdi-x/snap-plugin-publisher-influxdb) |
| Kafka | Publisher | Writes to Kafka messaging system | [snap-plugin-publisher-kafka](https://github.com/intelsdi-x/snap-plugin-publisher-kafka) |
| MySQL | Publisher | Writes to MySQL Database | [snap-plugin-publisher-mysql](https://github.com/intelsdi-x/snap-plugin-publisher-mysql) |
| OpenTSDB | Publisher | Writes to Opentsdb Database | [snap-plugin-publisher-opentsdb](https://github.com/intelsdi-x/snap-plugin-publisher-opentsdb) |
| PostgreSQL | Publisher | Writes to PostgreSQL Database | [snap-plugin-publisher-postgresql](https://github.com/intelsdi-x/snap-plugin-publisher-postgresql) |
| RabbitMQ | Publisher | Writes to RabbitMQ | [snap-plugin-publisher-rabbitmq](https://github.com/intelsdi-x/snap-plugin-publisher-rabbitmq) |
| Riemann | Publisher | Writes to Riemann monitoring system | [snap-plugin-publisher-riemann](https://github.com/intelsdi-x/snap-plugin-publisher-riemann) |

### Third-party

TBD

## Committed plugins
These plugins are in planned/active development. This list is useful if you want to reach out and contribute to the development.

| Name  | Type  | Description | Link | Authors |
| :---- | :---- | :---------- | :--- | :------ |
| Nova | Collector | Collect from Nova/Libvirt | -| [@sandlbn](https://github.com/sandlbn) |
| Open vSwitch | Collector | Collect Open vSwitch performance data | -| [@sandlbn](https://github.com/sandlbn) |
| NFS Client | Collector | Collect NFS client counters and RPC data | [snap-plugin-collector-nfsclient](https://github.com/intelsdi-x/snap-plugin-collector-nfsclient) | [@thomastaylor312](https://github.com/thomastaylor312) |
| Disk | Collector | Collects disk related metrics from Linux procfs | [snap-plugin-collector-disk](https://github.com/intelsdi-x/snap-plugin-collector-disk) | [@IzabellaRaulin](https://github.com/IzabellaRaulin) |
| Swap | Collector | Collects swap related metrics from Linux procfs | [snap-plugin-collector-swap](https://github.com/intelsdi-x/snap-plugin-collector-swap) | [@andrzej-k](https://github.com/andrzej-k) |
| Meminfo | Collector | Collects memory related metrics from Linux procfs | [snap-plugin-collector-meminfo](https://github.com/intelsdi-x/snap-plugin-collector-meminfo) | [@marcin-krolik](https://github.com/marcin-krolik) |
| Load | Collector | Collects plaform load metrics from Linux procfs | [snap-plugin-collector-load](https://github.com/intelsdi-x/snap-plugin-collector-load) | [@marcin-krolik](https://github.com/marcin-krolik) |
| Interface | Collector | Collects network interfaces metrics from Linux procfs | [snap-plugin-collector-interface](https://github.com/intelsdi-x/snap-plugin-collector-interface) | [@marcin-krolik](https://github.com/marcin-krolik) |
| Df | Collector | Collects disk space metrics from ```df``` Linux tool | [snap-plugin-collector-df](https://github.com/intelsdi-x/snap-plugin-collector-df) | [@PatrykMatyjasek](https://github.com/PatrykMatyjasek) |
| HAProxy | Collector | Collects metrics from HAProxy | [snap-plugin-collector-haproxy](https://github.com/intelsdi-x/snap-plugin-collector-haproxy) | [@marcin-krolik](https://github.com/marcin-krolik) |
| Etcd | Collector | Collects metrics from Etcd's `/metrics` endpoint. | [snap-plugin-collector-etcd](https://github.com/intelsdi-x/snap-plugin-collector-etcd) | [@danielscottt](https://github.com/danielscottt) |
| Processes | Collector | Collects processes metrics from Linux procfs | [snap-plugin-collector-processes](https://github.com/intelsdi-x/snap-plugin-collector-processes) | [@marcin-krolik](https://github.com/marcin-krolik) |
| Users | Collector | Collects users related metrics from Linux utmp | [snap-plugin-collector-users](https://github.com/intelsdi-x/snap-plugin-collector-users) | [@IzabellaRaulin](https://github.com/IzabellaRaulin) |
| MySQL | Collector | Collects metrics from MySQL DB | [snap-plugin-collector-mysql](https://github.com/intelsdi-x/snap-plugin-collector-mysql) | [@lmroz](https://github.com/lmroz) |
| CPU | Collector | Collects CPU metrics from Linux procfs | [snap-plugin-collector-cpu](https://github.com/intelsdi-x/snap-plugin-collector-cpu) | [@katarzyna-z](https://github.com/katarzyna-z) |
| DBI | Collector | Collects metrics from SQL DBs using go's "sql" package | [snap-plugin-collector-dbi](https://github.com/intelsdi-x/snap-plugin-collector-dbi) | [@IzabellaRaulin](https://github.com/IzabellaRaulin) |
| Apache | Collector | Collects metrics from the Apache Webserver for mod_status| [snap-plugin-collector-apache](https://github.com/intelsdi-x/snap-plugin-collector-apache) | [@tiffanyfj](https://github.com/tiffanyfj) |
 |
| Elasticsearch | Collector | Collects metrics from Elasticsearch cluster | [snap-plugin-collector-elasticsearch](https://github.com/intelsdi-x/snap-plugin-collector-elasticsearch) | [@candysmurf](https://github.com/candysmurf) |
| HEKA | Publisher | Publishes snap metrics into heka via TCP | [snap-plugin-publisher-heka](https://github.com/intelsdi-x/snap-plugin-publisher-heka) | [@candysmurf](https://github.com/candysmurf) |
|Graphite | Publisher | Publishes snap metrics to graphite | [snap-plugin-publisher-graphite](https://github.com/intelsdi-x/snap-plugin-publisher-graphite) | [@ircody](https://github.com/ircody) |

## Wish List
This is a wish list of plugins for snap. If you see one here and want to start on it please let us know.
#### Collector

- CollectD native
- Prometheus
- snap App Endpoint (needs event spec)
- Intel NIC
- Kubernetes Minion
- Mesos Slave
- Mesos Master
- JVM (via JMX)

#### Processor

- Caffe
- Oslo

#### Publisher

- 0MQ
- ActiveMQ
- SQLite
- Ceilometer (possibly just OSLO proc + RMQ)

