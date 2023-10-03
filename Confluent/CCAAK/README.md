# Confluent Certification for Apache Kafka

## Domains
| Domain                                                         | % of Exam |
| -------------------------------------------------------------- | --------- |
| Kafka Fundamentals                                             | 15%       |
| Managing, configuring and optimizing a cluster for performance | 30%       |
| Kafka Security                                                 | 15%       |
| Designing, troubleshooting and integrating systems             | 40%       |
| Total                                                          | 100%      |

## Set Up the Simulation Environment

1. Downloading and Installing VirtualBox

2. Install Ubuntu 20.04 on VirtualBox

3. Install Confluent Platform using ZIP and TAR Archives
```
# 1. Download TAR Archives
curl -O http://packages.confluent.io/archive/7.1/confluent-community-7.1.2.tar.gz

# 2. Extract (Unzip) Tar Gz File
tar -xvf confluent-community-7.1.2.tar.gz

# 3. Install JDK 11
sudo apt install openjdk-11-jdk

# 4. Starting ZooKeeper server
/home/vagrant/confluent-7.1.2/bin/zookeeper-server-start /home/vagrant/confluent-7.1.2/etc/kafka/zookeeper.properties

# 5. Starting Kafka server
/home/vagrant/confluent-7.1.2/bin/kafka-server-start /home/vagrant/confluent-7.1.2/etc/kafka/server.properties
```

## Configuration

### Static Configuration

### Dynamic Configuration

### Service Configuration

### Client Configuration