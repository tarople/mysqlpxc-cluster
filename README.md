# docker-compose haproxy、mysqlpxc集群

### 包含容器

* pxc1和pxc2
* haproxy

### 下载

~~~bash

git clone https://github.com/tarople/mysqlpxc-cluster.git

~~~

### 说明

#### 1、mysql

  > 如需要做多个pxc结点，可复制pxc1,并修改docker-compose.yml的相关配置

### 启动容器

> 1、进入子目录
> 2、启动顺序为[pxc1](https://github.com/tarople/mysqlpxc-cluster/tree/master/pxc1) -> [pxc2](https://github.com/tarople/mysqlpxc-cluster/tree/master/pxc2) -> [haproxy](https://github.com/tarople/mysqlpxc-cluster/tree/master/haproxy)