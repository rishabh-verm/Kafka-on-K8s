# Kafka-on-K8s (Namespace I am in is "Kafka", you can create you own custom namespace in K8s)

Steps to follow-

Step 1: Deploying Zookeeper

Command - kubectl create -f zookeeperdeploy.yaml

Step 2: Exposing Zookeeper Service

Command - kubectl create -f servicezookeeper.yaml

Step 3: Deploying Kafka Service

Command -  kubectl create -f kafkaservice.yaml

Step 4: Deploying Kafka Broker

Command - kubectl create -f kafkabroker.yaml
