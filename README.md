# beta

![](https://img.shields.io/badge/project-beta-orange) ![](https://img.shields.io/badge/build-passing-brightgreen) ![](https://img.shields.io/badge/vulnerabilities-0-brightgreen) ![](https://img.shields.io/badge/version-0.0.1-blue) ![](https://img.shields.io/badge/license-MIT-blue)

> DevOps is not a goal, but a never-ending process of **continuous improvement**. 
>
> — Jez Humble

一个 DevOps 流水线演示项目，用于展示企业级软件交付自动化场景，提供端到端交付设计思路。本项目源于工作经验提炼和抽象，也借鉴了互联网提供的资源，欢迎大家提供反馈和指导意见。

更好的阅读体验请点击：https://talk-cheap.github.io/beta/

## 项目亮点

1. **完整的交付链：**从需求收集、需求管理、代码开发、CICD、测试、发布、运维监控都提供了相应的设计思路和实践。
2. **主流的工具栈：**本项目中所演示的工具均为业界主流工具栈，我们在这个过程中也在学习和提高。
3. **代码既是文档：**DevOps的落地离不开文档，项目维护也离不开文档。代码即文档的理念应该得到推行。

## 项目规划

本项目大约历时4个月，利用大家工作之余的时间断断续续完成。就完成度来说，坦白讲并没有那么优秀，不过项目的规划图还是可以供其他同学参考。

![roadmap](docs/images/image-20220220152907206.png)

前期的头脑风暴和知识总结我们主要使用思维导图来完成，实际工作中xmind也是我们使用非常频繁的工具之一，强烈推荐。

## 设计理念

本项目主要围绕着[DevOps的CAMS 理念模型](https://www.linkedin.com/learning/devops-foundations/devops-core-values-cams-2)实现：

- **Culture 文化：**文化包括理念讲解和宣传，包括此文档，我们都在向所有DevOps从业者传递有价值的信息，DevOps不仅仅是流程和工作的改进，更是从开发和运维的意识转变，以全局优化的角度去优化软件交付流和改善研发体验。

- **Automation 自动化：**自动化是DevOps中重要的组成部分，我们应该尽可能地将交付过程中的工作自动化掉，在本项目中我们提供了自动化基础设施，自动化配置，自动化编译部署，自动化测试和监控等方面的实践。

- **Measurement 度量：**合理地管理和改进我们的系统的关键之一就是我们有测量它们的能力。除此之外我们还需要让开发团队感知DevOps工作的价值。不过指标的设计和选择需要十分谨慎，一旦对团队构成压迫将可能带来不良后果。

- **Sharing 分享：**在DevOps推进中，开放和透明性是合作的核心。知识共享是持续反馈和改进过程中一个重要的点，有了更多更好的分享，DevOps才能做的更好，企业才能不断发展壮大。

## 项目架构

![overview](docs/images/image-20220220173741876.png)

项目架构依据设计理念分为3个层次，分别是：

1. 最上层的自动化交付层，通过自动化构建完整的交付流水线。
2. 中间层的数据采集和度量服务，提供改进的思路和方向。
3. 基础层的最佳实践沉淀，作为业务团队的培训和改进的指导。

## 核心组件

## 演示场景

## 经验教训

## 参考资料

## 版权声明

本项目基于MIT开源，你可以在个人或者商业场景使用和修改本项目源代码。当然，如果你愿意保留来源作者和项目信息我们将不胜感激。

本项目成员名单如下：

| 成员         | 简介                                                 | 开源/博客         |
| ------------ | ---------------------------------------------------- | ----------------- |
| Toby Qin     | 资深 DevOps 工程师，喜欢和人沟通，擅长学习和分享技术 | tobyqin@github    |
| Shimin Wang  | 全栈工程师，喜欢捣鼓工具和新鲜的东西                 | sirius0301@github |
| Thyme Chen   | 测试开发工程师，擅长Python和数据分析                 | nowu@github       |
| Xiaokang Han | 运维工程师，擅长Kubernetes和Linux服务器运维和构建    |                   |

最后，感谢你的阅读。

