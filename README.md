# Memagent

 Memagent 通过代理 Memcached 来实现集群通信。


## 介绍

该应用模板会使用 [Helm](https://helm.sh) 包管理工具在 [Kubernetes](http://kubernetes.io) 上启动一个 Memagent.

MASTER_IP 为memagent命令行参数“-s" 和 memcached节点主节点ip

BACKUP_IP 为memagent命令行参数“-b" 和 memcached节点备用节点ip


