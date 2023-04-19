# 赵晨阳的简历

- Topic: docker python drf kubernetes 容器 运维开发 自动化 AI

## 关于我

- 赵晨阳
- 2016-09 ～ Now
- 工作年限: 6年
- 期望职位:SRE运维工程师 kubenetes工程师 python开发工程师
- 期望城市: 上海 杭州
- Email: zhaochenyang_zcy1@163.com
- 目前状态: 离职
- 学历：大专 自学本科（自学中）

## 技能清单

- 开发语言: Shell,Python
- 版本管理: Git（github、gitee）
- 数据库: MySQL,,Redis,Etcd
- 方法论: Devops
- Container Tech: Containerd, Docker
- Ops: LNMP, Linux, MySQL, Shell，Docker, Kubernetes，Ansible，Zookeeper，Hdfs，Kvm，Django Rest framework，Ingress，Prometheus,Etcd,Coredns
- OS:  CoreOS, Ubuntu 

## 项目经历

以下为实施的项目，时间按倒序排列

### Momenta

#### MOPS k8s 多集群管理平台

- 基于360开源的[wayne](https://github.com/Qihoo360/wayne)项目定制开发
  - ingress相关功能
  - 对接阿里云实现域名自动解析
  - 现有集群导入功能

#### Jenkins CI平台

- jenkins+kubernetes 提供jenkins构建集群
- 使用共享存储解决jenkins agent编译缓存

#### goslurm 深度学习调度平台

- CLI兼容[slurm](https://www.schedmd.com/) 降低了传统HPC生态用户迁移成本
- 基于k8s调度任务,使用自定义scheduler
- 兼容 `caffe2` `tensorflow` `pytorch` 常见框架 使用对应k8s的operator
- 云上环境与云下环境混合部署，多集群调度
- 云上环境自动扩缩容 aws 使用ASG
- 集群自动部署（terraform+rke）
- 支持以太网以及RDMA网络异构网络环境调度


### 上海游族

#### UPaaS 私有PaaS平台

类似于简化版的网易蜂巢，包含代码托管构建，镜像市场，弹性计算，云盘 等功能

- 负责系统后端架构设计，技术选型。后端系统开发
- 子系统：
    - CI/CD 系统: 使用 `gogs` git服务 和 `drone` 自动构建系统 进行代码过托管和自动构建
    - 私有docker registry: 使用 `Vmware Harbor` 高可用集群建设私有镜像托管系统
    - CEPH 块存储以及对象存储系统: 为PaaS平台提供块存储实现云盘功能，对git系统提供共享存储，为registry 提供对象存储
    - Kubernetes: 提供弹性计算和服务调度功能。
    - `archon`实现kubernetes集群的管理。使用一个共享的管理集群来管理每个租户的业务集群。


#### CMDB

- 负责系统设计，需求整理，把控进度
- 计划设计开发一个CMDB系统来管理中间件，操作系统，硬件，网络设备，IDC 所有运维相关实体的配置信息，但是由于经验不足，而且没有具体需求导致项目陷入描述每个具体配置对象的配置模式，而忽略了CMDB的本质最终导致无法推进

### 17173北京分公司

#### 监控系统

- 负责基于`zabbix`设计一个监控系统监控173所有服务器以及中间件，数据库的状态，以及报警
- 基于`zabbix`定制了报警行为，报警模式。以`python`开发了一套`zabbix`的报警脚本库。使用`MySQL-TokuDB` 作为存储。由于当时zabbix当时不能处理大量数据，对监控系统依据业务进行拆分，然后封装一个统一接口对外提供服务

## 工作经历


- 北京宇信科技
    - 时间: 2022.8-2023.3
    - 职位: kubenetes运维工程师
    - 职责: 负责kubenetes集群的运维工作。
    - 离职原因: 出了点小事故，回家养伤了一段时间。
- 上海微创北京分公司
    - 时间: 2019.6-2022.7
    - 职位: AI交付运维工程师
    - 职责: 负责AI私有化产品的交付，技术支持与运维工作。
    - 离职原因: 部门调整，人员变动，我们组被其他调动到其他团队。
    - 总结: 在这里认识了一群很棒的人，接触实践了最新的技术。
- 北京亚太东方有限公司
    - 时间: 2018.5-2019.5
    - 职位: 网络工程师
    - 职责: 负责IDC机房的运维，windows server，sqlserver 的安装与运维
    - 离职原因: 由于经常上夜班，自己没有精神。
    - 总结: 在这里我对应IT行业有了进一步的了解。
- 北煤机电
    - 时间: 2017.4~2018.4
    - 职位: 单片机技术员
    - 职责: 单片机电路图修改，单片机程序调试，单片机硬件维修
    - 离职原因: 年轻想四处看看
    - 总结: 跟自己学习的专业相关，对嵌入式开发有了进一步的了解，开拓眼界。
- 北京宽带通
    - 时间: 2016.10~2017.3
    - 职位: 网络部技术(实习)
    - 职责: 负责宽带区域网络，机房的维护
    - 总结: 一切的起点，给了我进入IT行业的机会。
