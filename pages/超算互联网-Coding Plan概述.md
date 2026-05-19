# Coding Plan [​](https://www.scnet.cn/ac/openapi/doc/2.0/moduleapi/codingplan/subscriptionnotice.html\#coding-plan)

## 套餐详情 [​](https://www.scnet.cn/ac/openapi/doc/2.0/moduleapi/codingplan/subscriptionnotice.html\#%E5%A5%97%E9%A4%90%E8%AF%A6%E6%83%85)

| 套餐项 | Lite 基础套餐 | Pro 高级套餐 |
| --- | --- | --- |
| 价格 | ¥20/月 | ¥100/月 |
| 定位 | 适合个人开发者和轻量编程需求 | 适合高频编程和复杂项目开发 |
| 模型支持 | MiniMax、Qwen 等最新版本模型 | 与 Lite 相同 |
| 用量限制 | 每 5 小时最多约 1,200 次请求<br>每周最多约 9,000 次请求<br>每月最多约 18,000 次请求 | 每 5 小时最多约 6,000 次请求<br>每周最多约 45,000 次请求<br>每月最多约 90,000 次请求 |
| 可接入工具 | OpenClaw、OpenCode、Claude Code、Cursor、CodeX、Cline、RooCode | 与 Lite 相同 |
| 免费实例 | OpenClaw 2核4G 实例免费使用 | OpenClaw 2核4G 实例免费使用 |

**额度消耗说明**

请求次数为模型调用的预估数值。通常一次用户提问会触发多次模型调用，每次调用均消耗 1 次用量额度。

- 简单任务：单次提问约消耗 **5~15** 次模型调用
- 复杂任务：单次提问约消耗 **15~30** 次或更多模型调用

用量消耗可在控制台 → 模型服务 → Coding Plan 中查看

**支持的模型**

Coding Plan 精选适用于 AI 开发场景的主流模型，并根据平台适配与稳定性验证结果持续更新。

当前已开放的模型如下：

| 模型名称（Model） | 说明 |
| --- | --- |
| `MiniMax-M2.5` | 适用于通用开发问答、代码理解、代码修改与日常交互式编程任务 |
| `Qwen3-235B-A22B` | 适用于代码生成、工程理解、复杂指令处理与多轮开发协作场景 |

> **说明**
>
> - 请在工具中严格按照上述模型名称填写 `Model` 或 `Model ID`，注意大小写、连接符与字符完整性。
> - Lite 套餐和 Pro 套餐使用相同的模型资源和推理服务，两者在模型响应速度上没有差异，区别仅在于调用次数额度不同。
> - 更多模型正在适配验证中，请关注本页面更新或控制台内的可用模型列表。
> - Anthropic暂时只有MiniMax-M2.5模型支持，更多模型支持敬请期待。