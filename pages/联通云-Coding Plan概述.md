Coding Plan概述

更新时间：
2026-05-18 10:20:16


> 公告：
>
> 当前联通云AISP Coding Plan 需求火爆，部分资源出现阶段性紧张情况。
>
> 针对这一情况，近期平台已紧急扩充智算资源。针对免费体验期内的用户，为提升体验效果，平台已上线模型动态调度策略，当您使用的模型触发限流时，系统将自动路由至当前负载更轻的模型，保障服务不间断。感谢您的理解与支持。

联通云AI服务平台 Coding Plan 整合了DeepSeek V4、GLM-5.1、GLM-5、MiniMax M2.5，Qwen3.5等顶级模型，同时兼容主流AI编程工具，折算成本远低于常规 API 调用。

* * *

**快速开始**

访问 [Coding Plan 页面](https://console.cucloud.cn/console/cuig/subscribePlan) 即可订阅并获取Coding Plan专属API Key，详细使用方法请参考 [快速开始](https://support.cucloud.cn/document/127/591/2357.html?id=2357&arcid=7014)。

* * *

****套餐详情****

|     |     |     |
| --- | --- | --- |
|  | Coding Plan-Lite | Coding Plan-Pro |
| 适用场景 | 基础开发任务需求，开发者的首选起点 | 大量开发任务需求，团队提效的进阶之选 |
| 价格 | 40元/月 | 200元/月 |
| 额度 | - 每 5 小时1,200 次请求<br>  <br>- 每周9,000 次请求<br>  <br>- 每月18,000 次请求 | - 每 5 小时6,000 次请求<br>  <br>- 每周45,000 次请求<br>  <br>- 每月90,000 次请求 |

**套餐升级：** 若额度不够，可在Coding Plan控制台进行套餐升级操作，升级后立即生效。 **注意**：升级套餐并不是延长套餐有效期，请留意到期时间，如有需要可进行续费。

**额度消耗**：单次提问将按实际“模型调用次数”扣除额度。简单 Agent 任务约消耗 5-10 次，复杂 Agent 任务约 10-30+ 次，实际消耗受任务难度、上下文及工具使用影响，可在 [Coding Plan 页面](https://console.cucloud.cn/console/cuig/subscribePlan) 可以查看用量。

**套餐支持云区域与模型**

|     |     |     |
| --- | --- | --- |
| 云区域 | 支持模型 | BaseURL（不同AI工具配置略有差异，详见 [接入AI工具](https://support.cucloud.cn/document/127/591/2357.html?id=2357&folderid=3237)） |
| 贵阳基地二区 | DeepSeek-V4-Flash<br>glm-5.1、glm-5<br>MiniMax-M2.5<br>Qwen3.5-397B-A17B、Qwen3-235B-A22B<br>kimi-k2.5<br>**注：**<br>**当前服务资源有限，DeepSeek-V4-Flash 仅供尝鲜体验，上下文窗口目前仅支持 200K。**<br>高峰期易触发接口限流或响应慢，建议切换模型使用 | 兼容OpenAI协议： https://aigw-gzgy2.cucloud.cn:8443/v1 <br>兼容Anthropic协议：https://aigw-gzgy2.cucloud.cn:8443 |
| 武汉四区 | DeepSeek-V4-Flash<br>glm-5<br>MiniMax-M2.5<br>Qwen3-235B-A22B<br>kimi-k2.5<br>**注：**<br>**当前服务资源有限，DeepSeek-V4-Flash 仅供尝鲜体验，上下文窗口目前仅支持 200K。** | 同上（贵阳基地二区） |
| 广州一区 | MiniMax-M2.5 | 同上（贵阳基地二区） |
| 济南五区 | MiniMax-M2.5 | 兼容OpenAI协议： https://aigw-jnzs5.cucloud.cn:8443/v1<br>兼容Anthropic协议：https://aigw-jnzs5.cucloud.cn:8443 |

注1：在后续接入AI工具时配置的模型名称请与此处保持一致；

注2：如遇到模型调用限流，可能是因为当前访问流量太大，可尝试切换其他模型使用。

**套餐有效期**

套餐自购买成功当日开始计算，以 1 个月套餐有效期为例：

|     |     |     |
| --- | --- | --- |
| 云区域 | 购买时长 | 到期时间（UTC+8） |
| 2026-01-31 09:00:00 | 1 个月 | 2026-02-28 23:59:59 |
| 2026-02-01 09:00:00 | 1 个月 | 2026-03-01 23:59:59 |
| 2026-02-28 09:00:00 | 1 个月 | 2026-03-28 23:59:59 |

* * *

**订阅前须知**

**Coding Plan 服务不支持退款**。因此在订阅前请知悉以下重要内容：

**订阅账号限制**：一个联通云账号主体（不区分主子账号）仅支持订阅一个套餐（不区分Lite和Pro）。

**严禁 API 调用**：仅限在编程工具（如 Claude Code、OpenClaw 等）中使用，禁止以 API 调用的形式用于自动化脚本、自定义应用程序后端或任何非交互式批量调用场景。将套餐 API Key 用于允许范围之外的调用将被视为违规或滥用，可能会导致订阅被暂停或 API Key 被封禁。