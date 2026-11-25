Claude 中转接口 · 个人接入指南
面向个人开发者、Claude Code / Cursor / Cline 用户的第三方 Claude API 接入说明。

本服务是第三方转发服务,与 Anthropic / AWS 无任何关系,请知悉后再使用。

这是什么
一个 Claude 接口转发服务。你通过下方地址和 key 调用 Claude 系列模型,可用于 Claude Code、Cursor、Cline 及支持自定义接口地址的工具。

支持模型
系列	模型 ID	用途建议
Opus	claude-opus-x-x	复杂推理、长文档
Sonnet	claude-sonnet-x-x	日常编码、对话
Haiku	claude-haiku-x-x	快速、低成本任务
暂不支持:fable
实际可用模型以后台列表为准,可能随上游调整而变动。
快速开始
Claude Code
bash


export ANTHROPIC_BASE_URL=https://你的域名
export ANTHROPIC_API_KEY=你的key
claude
Windows PowerShell:

powershell


$env:ANTHROPIC_BASE_URL = "https://你的域名"
$env:ANTHROPIC_API_KEY  = "你的key"
Cursor / Cline / 其他 OpenAI 兼容工具


接口地址填 
https://你的域名/v1
,key 填我们给你的 key 即可。

计费
按实际用量计费,以美元额度为计量单位。
支持小额充值,方式:____(微信 / 支付宝 / 卡密)。
用量可在后台查询。
风险须知(使用前请阅读)
本服务依赖上游供应,可能出现限流、模型下架、服务中断或停止运营。
因上游原因中断,按未消耗额度退款,其余不承担。
请勿用于违法违规、侵权、诈骗、批量注册等用途,违者封号且不退款。
请勿提交密码、密钥、个人敏感信息等内容。


联系
反馈 / 售后:qq号：923200792


免责声明
本项目仅供学习与个人使用。使用者需自行确认所用接口的合法性及是否符合上游服务条款。
