# 赵晨阳的简历

- Topic: docker python drf kubernetes 容器 运维开发 自动化 AI

## 关于我

- 赵晨阳
- 2016-09 ～ Now
- 工作年限: 6年
- 期望职位:SRE运维工程师 kubenetes工程师 python开发工程师
- 期望城市: 杭州 南京
- Email: zhaochenyang_zcy1@163.com
- 目前状态: 离职
- 学历：大专 自学本科（自学中）
- 证书：CKA
- ![image](https://user-images.githubusercontent.com/86656798/232954190-0fd9ed1b-f789-468d-ae97-b3558be6050f.png)

## 技能清单

- 开发语言: Shell,Python
- 版本管理: Git（github、gitee）
- 数据库: MySQL,,Redis,Etcd
- 方法论: Devops
- Container Tech: Containerd, Docker
- Ops: LNMP, Linux, MySQL, Shell，Docker, Kubernetes，Ansible，Zookeeper，Hdfs，Kvm，Django Rest framework，Ingress，Prometheus,Etcd,Coredns
- OS:  CoreOS, Ubuntu 

## 项目经历


#### K8s 集群中增加prometheus监控ingress指标

- 基于开源的prometheus监控nginx-ingress
  - 测试环境搭建nginx-ingress，prometheus
  - 调试ingress监控指标
  - ingress的监控指标对接到prometheus的监控模板
  - 完成测试，进行验证
  - 编写对应的变更控制表
  - 根据审批后的变更控制表在生成环境部署调试


#### zookeeper 集群zxid溢出处理方案

- CLI兼容[slurm](https://www.schedmd.com/) 降低了传统HPC生态用户迁移成本
- 基于k8s调度任务,使用自定义scheduler
- 兼容 `caffe2` `tensorflow` `pytorch` 常见框架 使用对应k8s的operator
- 云上环境与云下环境混合部署，多集群调度
- 云上环境自动扩缩容 aws 使用ASG
- 集群自动部署（terraform+rke）
- 支持以太网以及RDMA网络异构网络环境调度


#### k8s 集群node节点扩容

类似于简化版的网易蜂巢，包含代码托管构建，镜像市场，弹性计算，云盘 等功能

- 负责系统后端架构设计，技术选型。后端系统开发
- 子系统：
    - CI/CD 系统: 使用 `gogs` git服务 和 `drone` 自动构建系统 进行代码过托管和自动构建
    - 私有docker registry: 使用 `Vmware Harbor` 高可用集群建设私有镜像托管系统
    - CEPH 块存储以及对象存储系统: 为PaaS平台提供块存储实现云盘功能，对git系统提供共享存储，为registry 提供对象存储
    - Kubernetes: 提供弹性计算和服务调度功能。
    - `archon`实现kubernetes集群的管理。使用一个共享的管理集群来管理每个租户的业务集群。


#### k8s AI私有化交付

类似于简化版的网易蜂巢，包含代码托管构建，镜像市场，弹性计算，云盘 等功能

- 负责系统后端架构设计，技术选型。后端系统开发
- 子系统：
    - CI/CD 系统: 使用 `gogs` git服务 和 `drone` 自动构建系统 进行代码过托管和自动构建
    - 私有docker registry: 使用 `Vmware Harbor` 高可用集群建设私有镜像托管系统
    - CEPH 块存储以及对象存储系统: 为PaaS平台提供块存储实现云盘功能，对git系统提供共享存储，为registry 提供对象存储
    - Kubernetes: 提供弹性计算和服务调度功能。
    - `archon`实现kubernetes集群的管理。使用一个共享的管理集群来管理每个租户的业务集群。


#### python web游戏

- 负责基于`zabbix`设计一个监控系统监控173所有服务器以及中间件，数据库的状态，以及报警
- 基于`zabbix`定制了报警行为，报警模式。以`python`开发了一套`zabbix`的报警脚本库。使用`MySQL-TokuDB` 作为存储。由于当时zabbix当时不能处理大量数据，对监控系统依据业务进行拆分，然后封装一个统一接口对外提供服务
-项目地址：

#### python 微信电商小程序

- 负责基于`zabbix`设计一个监控系统监控173所有服务器以及中间件，数据库的状态，以及报警
- 基于`zabbix`定制了报警行为，报警模式。以`python`开发了一套`zabbix`的报警脚本库。使用`MySQL-TokuDB` 作为存储。由于当时zabbix当时不能处理大量数据，对监控系统依据业务进行拆分，然后封装一个统一接口对外提供服务
-项目地址：

#### 自动化脚本
- 实际运行pod的pod_name,image,replicas，limits，requests,node_selector,host_network与

## 工作经历
时间按倒序排列

- 北京宇信科技
    - 时间: 2022.8-2023.3
    - 职位: kubenetes运维工程师
    - 职责: 负责kubenetes集群，etcd集群，zookeeper集群，hdfs集群的运维，编写相应的自动化脚本。
    - 离职原因: 出了点小事故，回家养伤了一段时间。
- 上海微创北京分公司
    - 时间: 2019.6-2022.7
    - 职位: AI交付运维工程师
    - 职责: 负责AI私有化产品的交付，技术支持与运维工作。
    - 离职原因: 部门调整，人员变动，我们组被其他调动到其他团队。
    - 总结: 在这里认识了一群很棒的人，接触实践了最新的技术（AI，kubenetes）。
- 北京亚太东方有限公司
    - 时间: 2018.5-2019.5
    - 职位: 网络工程师
    - 职责: 负责IDC机房的运维，windows server，sqlserver，centos的安装与运维。
    - 离职原因: 由于经常上夜班，自己没有精神。
    - 总结: 在这里接触到了IDC机房，windows系列的服务器与数据库，还有linux系统。
- 北煤机电
    - 时间: 2017.4~2018.4
    - 职位: 单片机技术员
    - 职责: 单片机电路图修改，单片机程序调试，单片机硬件维修。
    - 离职原因: 年轻想四处看看。
    - 总结: 跟自己学习的专业相关，对嵌入式开发有了进一步的了解，开拓眼界。
- 北京宽带通
    - 时间: 2016.10~2017.3
    - 职位: 网络部技术(实习)
    - 职责: 负责宽带区域网络，机房的维护
    - 总结: 一切的起点，给了我进入IT行业的机会。
