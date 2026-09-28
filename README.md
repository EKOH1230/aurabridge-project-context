# AuraBridge 开发资料包

> 面向 AuraBridge 内部展示网站、后续 B2B 营销与自动化讨论的开发交接资料。最近更新：2026-09-28。

## 当前已确认方向

- 先做供 Joe 内部审阅的英文 B2B 网站原型；不对公众开放，不需要域名。
- 首页先平均面向所有 B2B 合作伙伴，不设优先客群。
- 视觉以蓝、白、黑为主，红色少量点缀；临时使用本轮指定的 AuraBridge Logo 图片。
- 产品组合未定，原型暂时不展示具体产品。集团关系介绍作为默认隐藏的可开关模块。
- 后续营销规划纳入 TikTok、Instagram、Facebook、Google、抖音等渠道。
- 自动化先讨论 AuraBridge 自身的邮件问候/跟进、内容审核辅助和财务资料整理。Bright Bridge 集团整体自动化另行讨论。

## 从这里开始

1. 先读本文件和 [AGENTS.md](AGENTS.md)。
2. 将 [docs/00_Codex接续提示.md](docs/00_Codex接续提示.md) 复制到 Codex，或按需修改。
3. 看 [docs/01_项目定位与品牌.md](docs/01_项目定位与品牌.md) 了解品牌基础。
4. 看 [docs/02_网站需求草案.md](docs/02_网站需求草案.md) 开始英文 B2B 原型；不要自行填充未定产品。
5. 看 [docs/05_决策记录与待确认事项.md](docs/05_决策记录与待确认事项.md) 核对用户已确认的范围和后续问题。
6. 需要了解商业假设和旧路线图时，查看 [docs/03_商业探索与产品假设.md](docs/03_商业探索与产品假设.md)、[docs/04_路线图与事项.md](docs/04_路线图与事项.md) 及 `references/`；[docs/08_技术选择与自助边界.md](docs/08_技术选择与自助边界.md) 说明当前原型适合自行完成的范围。

## 文件布局

- `AGENTS.md`：Codex 项目规则。
- `docs/`：项目定位、网站需求、商业假设、路线图、决策记录、研究提示和技术自助建议。
- `references/`：品牌 Word、路线图、Logo 图片及申请资料、聊天摘录。
- `references/README.md`：来源、用途与局限。

## 资料边界

本资料包依据 AuraBridge ChatGPT 项目中的三条聊天、已找到的品牌 Word、路线图 Excel、Logo 素材及商标 PDF 整理。它不是完整的 ChatGPT 导出。旧市场推测、法规说法和效果结论没有在本次重新验证；公开使用前需核实。

本包只整理 AuraBridge 项目。Bright Bridge 集团其他公司的自动化事项不在当前工作范围内。资料用于 Joe 内部审阅；文件措辞避免使用家庭称谓。

## 与 Codex 协作

将整个文件夹放入网站代码库，使 Codex 可同时读取本 README、`AGENTS.md`、`docs/` 和 `references/`。有新决定时更新相关 Markdown 和决策记录，保留原始附件。当前资料包含商业背景；若上传 GitHub，应使用私有仓库并确认访问权限。
