title: docker&devops
speaker: gomaster
url: https://github.com/ksky521/nodeppt
transition: fadein
files: /js/demo.js,/css/demo.css

[slide]

# Docker&Devops 持续集成与交付

# 手把手实践

## 分享者：gomaster.me

[slide]

# 回顾微服务架构 {:&.flexbox.vleft}

## 持续集成与交付

![](/img/ms.png)

[slide]

# 硬币游戏

---

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 角色: 项目经理-> `产品->开发->测试->运维`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 分工: Manager(项目经理) &nbsp;&nbsp;`Worker(其他四类角色)`

---

工具: 硬币，计时器

[slide]

## 持续集成与交付手把手实践

---

vagrant 虚拟环境和项目文件，文件比较大 5G 多

```sh
⋊> ~/g/workshop_day1 tree -L 1                                                        02:02:28
.
├── Vagrantfile
├── ci
├── hello
├── leanms_d1.box
├── live
└── prepare.sh

3 directories, 3 files
```

采用 vagrant 为了实验平台宿主机环境统一

[slide]

## 一些现状

[slide]

## 一些榜样

[百度效率云](https://xiaolvyun.baidu.com/)
[阿里云 CRP 持续交付平台](https://crp.aliyun.com/#page6)
[腾讯云 TGit](https://cloud.tencent.com/solution/devops?from=qcloudHpHeaderDevops)
[coding](coding.net)

[slide]

## 当前现状的反思

- 审批的意义有多大
  - 等待时间
  - 审批人是否理解
- 开发者的自己的狗粮自己吃

## 自下而上? 自上而下?

[slide]

## 敏捷宣言

[slide]

# Thanks

---

**Docker Devops!**
