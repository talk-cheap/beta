?> Gitlab 是 CICD 的核心系统，提供了源代码版本控制和持续交付相关的所有功能。

Gitlab 本身提供了良好的文档供我们参考，在和其他系统集成时，我们可以参考这些文档。

- https://docs.gitlab.com/ee/integration/

在本项目中我们将 Gitlab 集成了以下系统：

1. Slack：用于通知 CICD 信息
2. Jira： 用于同步需求交付状态
3. Email: 用于邮件通知 CICD 信息
