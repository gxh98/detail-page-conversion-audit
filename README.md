# Detail Page Conversion Audit Skill

这是一个用于诊断商品详情页、落地页、营销页转化问题的 Codex Skill。

它基于一套“详情页转化率课程”的方法论沉淀，目标不是做审美点评，而是帮助你判断：一个页面为什么没有把流量转成订单、线索、咨询或预约，并给出可执行的迭代方案。

## 能做什么

- 找出商品详情页/落地页影响转化的问题
- 判断首屏、卖点、页面结构、文案、图片、按钮、视频、排版的问题
- 区分页面问题和流量/渠道匹配问题
- 输出优先级、影响程度、修改成本和判断置信度
- 给出改版建议、文案替换方向和 A/B 测试方案

## 适用场景

- “帮我看看这个商品详情页哪里影响转化”
- “这个落地页为什么咨询率低”
- “帮我优化首屏和按钮文案”
- “给这个详情页出一份诊断报告”
- “把这张长图详情页按转化逻辑重排一下”

## 安装方式

把本目录放到 Codex skills 目录下：

```bash
~/.codex/skills/detail-page-conversion-audit
```

目录中必须保留 `SKILL.md` 和 `references/`。

## 使用方式

在 Codex 中给出页面截图、URL、PDF、长图或 HTML，并说明你希望做快速体检、深度诊断还是直接改版。

示例：

```text
请用 detail-page-conversion-audit 技能诊断这个商品详情页，找出影响转化的问题，并给出优先级、改法和 A/B 测试建议。
```

如果你能补充这些信息，诊断会更准：

- 商品类目和价格
- 目标用户
- 流量来源或投放渠道
- 当前转化目标
- 当前数据，比如点击率、下滑率、加购率、支付转化率
- 竞品页面

## 目录结构

```text
detail-page-conversion-audit/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── audit-checklist.md
    ├── course-rules.md
    ├── iteration-playbook.md
    └── report-template.md
```

## 文件说明

- `SKILL.md`：技能入口，包含触发条件、工作流和输出规则
- `references/course-rules.md`：课程方法论提炼
- `references/audit-checklist.md`：详情页诊断检查清单
- `references/report-template.md`：正式报告模板
- `references/iteration-playbook.md`：常见问题、改法和 A/B 测试方案
- `agents/openai.yaml`：Codex 技能展示元数据

## 隐私说明

这个仓库默认建议保持 private。技能内容来自课程材料的方法论提炼，不建议直接公开分发课程派生内容。
