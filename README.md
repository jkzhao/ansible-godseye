# ansible-godseye
ansible-playbook deploy distributed log system. godseye is the name of the system.

This distributed log system contains zookeeper, kafka, elasticsearch, nginx, redis, mysql, flume-ng, hadoop, habse and hive. The opological diagram is opological.png.

This project only contains configuration, there are no installation packages in the directory 'files', because some of them are too big.
When you use this project, you need pay attention to the file vars/main.yml and the hosts defined in /etc/ansible/hosts, you need modify this two file according to actual environment.

You also can see my blog which introducing detail. The article address is 'http://jkzhao.github.io/2017/07/27/Ansible%E5%AE%9E%E6%88%98%EF%BC%9A%E9%83%A8%E7%BD%B2%E5%88%86%E5%B8%83%E5%BC%8F%E6%97%A5%E5%BF%97%E7%B3%BB%E7%BB%9F/#more'.
