# 研发运营一体化（DevOps）能力成熟度模型 第9部分：系统和工具

研发运营一体化（DevOps）能力成熟度模型 第9部分：系统和工具（DevOps 产品标准）属于研发运营一体化（DevOps）能力成熟度模型系列标准的一部分，旨在通过行业的力量，规范化DevOps产品的功能特性，帮助企业建设、选型和购买DevOps产品工具。

本标准由DevOps标准工作组下DevOps产品工作小组负责编写和维护。

### 工具箱列表

说明：如果该工具

#### 1. [项目与开发管理](project_and_development_management.md)


| 项目管理              | 需求管理                    | 计划与任务管理        | 文档与知识管理              | 团队协同            | 统计度量              | 项目集管理             |
| --------------------- | --------------------------- | --------------------- | --------------------------- | ------------------- | --------------------- | ---------------------- |
| JIRA <br/> (国外/商业)           | JIRA+Confluence             | JIRA                  | Confluence                  | Slack               | Hygieia<br/> (国外/开源)                | Portfolio<br/>for Jira |
| Redmine               | 百度：iCafe                 | 华为云DevCloud：项目管理 | 华为云DevCloud：Wiki和文档管理 | 华为云DevCloud：HiChat | MirrorGate            | 华为云DevCloud：项目管理  |
| 华为云DevCloud：项目管理 | 华为云DevCloud：项目管理       | 阿里云效:项目协作     | ONES Project                | Mattermost          | 华为云DevCloud：项目管理 | 阿里云效:项目协作      |
| 阿里云效:项目协作     | 阿里云效:项目协作           | ONES Project          |                             |                     | CloudBees DevOptics   | Oracel Primavera       |
| ONES Project          | ONES Project                | MS Project            |                             |                     | JIRA EasyBI           |                        |
|                       | Rational RequisitePro/DOORS |                       |                             |                     |                       |                        |
CODING：项目管理 | CODING：项目管理 | CODING：项目管理 | CODING：Wiki 与文档管理 | - | CODING：项目管理 | CODING：项目管理
|                       | 平安神兵:协作平台(Alm) | 平安神兵:协作平台(Alm) |                             |                        | 平安神兵:数据平台(DC)| 平安神兵:协作平台(Alm) |



#### 2. [应用设计与开发](application_design_and_development.md)

| 应用框架 | 云IDE         |
| -------- | ------------- |
| Dubbo    | AWS Cloud9 |
| TARS<br/> (国产/开源)     | Eclipse Che |
| EDAS    |Codenvy |
| 灵雀云（Alauda EE PaaS）     | 华为云DevCloud：CloudIDE<br/>（国产/商业） |
| 华为云 ServiceStage    |   Coding:WebIDE      |
| EMAS     | OrionHub |
| 谐云（观云台）     |  |
| - | CODING：Cloud Studio

#### 3. [持续交付](continuous_delivery.md)

| 源代码管理  | 构建管理 | 持续集成 | 流水线 | 制品管理 | 发布管理 | 环境管理 | 数据管理 | 应用配置管理 |
| ----------- | -------- | -------- | ------ | -------- | -------- | -------- | -------- | :----------: |
| Github      |          |          |        |          |          |          |          |  携程Apollo  |
| Gitlab:代码 |          |          |        |          |          |          |          |              |
| 腾讯工蜂 |          |          |        |          |          |          |          |              |
| 平安神兵:Code | 平安神兵:VT | 平安神兵:VT | 平安神兵:VT | 平安神兵:VT | 平安神兵:VT | 平安神兵:VT |          | 平安神兵:CC |
| 华为云DevCloud：代码托管 | 华为云DevCloud：编译构建 | 华为云DevCloud：编译构建 | 华为云DevCloud：流水线 | 华为云DevCloud：发布 | 华为云DevCloud：发布 | 华为云DevCloud：部署 |          |              |
| 云效: code  | 云效: 持续交付| 云效:持续交付|云效:持续交付|云效:私库服务|云效:持续交付 | | |
| CODING：代码托管 | CODING：持续集成  | CODING：持续集成 | CODING：持续集成 | - | - | - | - | - |


#### 4. [测试管理](test_management.md)

| 用例与测试计划管理 | 缺陷管理 | 测试数据管理 |
| ------------------ | -------- | ------------ |
|                    | JIRA     |              |
| 华为云DevCloud：云测 | 华为云DevCloud：项目管理 | 华为云DevCloud：云测 |
| 平安神兵:协作平台(Alm) | 平安神兵:协作平台(Alm) |              |
| CODING：测试管理 | CODING：缺陷管理 | - |

#### 5. [自动化测试](test_automation.md)

| 代码质量管理 | 单元测试 | 接口/服务测试 | UI测试 | 移动应用测试 | 性能测试 |
| ------------ | -------- | ------------- | ------ | ------------ | -------- |
| SonarQube    |          |               |        |              |          |
| CODING：持续集成 | - | - | - | - | - |
| 华为云DevCloud：代码检查 |          | 华为云DevCloud：云测 |        | 华为云DevCloud：移动应用测试 |          |
|              |          |  平安神兵:api |        |              | 平安神兵:Power |

#### 6. 技术运营（待定）

#### 7. [安全开发](security_development.md) \ [安全交付](security_delivery.md) \ 安全运营

| 安全开发 | 安全交付 | 安全运营 |
| -------- | -------- | -------- |
|          |          |          |
|          |          |          |
|          |          |          |





