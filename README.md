# kafkaQuickstart
A quickstart Kafka script for all your sanity needs when working with Kafka.

==Assumptions==
1. Ubuntu Linux platform
2. Apache Kafka and all dependences (i.e. zookeeper) is properly installed and operational.

==Installation==
1. Download the script. Open it.
2. Copy&Paste the top folder of your Kakfa_Path under KAFKA_HOME.

==Usage==
Under terminal, CD to where you have the script stored. 

There are four functions: start, stop, restart, and status

=I. Start=
sudo bash kafkaQuickstart.sh start

=II. Stop=
sudo bash kafkaQuickstart.sh stop

=III. Restart=
sudo bash kafkaQuickstart.sh restart

=IV. Status==
sudo bash kafkaQuickstart.sh status
