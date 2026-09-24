# 任务记录：FB投流网站每日内容更新（2026-09-23）

## 目标
按每日任务要求，为 fb-ads-site 生成 1-2 篇 SEO 优化文章，更新列表页与站点地图，并推送 GitHub。

## 当日主题
周三 → **WhatsApp私域营销**

## 前期调研
使用 web_search 检索 "WhatsApp Business API 2026"、"WhatsApp marketing 2026 best practices conversion data" 等，
从 Salesmartly / Infobip / PayPerWA / Go4whatsup / ChatDaddy / GoKwik 等来源提炼 2026 年关键变化与基准数据。

关键信息点（用于两篇文章）：
- 计费：2025-07-01 起由「会话计费」改为「按条计费」；四类模板（营销/公用/验证/服务）
- 免费区：24 小时服务窗口免费不限量；CTWA 广告带来 72 小时免费入口窗口
- 风控：Marketing 频次上限；封禁触发阈值由 1% 收紧至 0.5%；Portfolio Pacing 分批投放 + 实时暂停
- 配额：完成 Business Verification 即解锁 10 万条/天（取消 2K→10K 逐级爬坡）
- AI：2026-01-15 起通用型 AI 助手被限制，业务型 AI 客服仍合法
- 身份：用户名 + BSUID（Business-Scoped User ID），CRM 主键需改造
- 生态：App 与 Cloud API 共存（2026-01）、Calling API、Carousel、Flows
- 基准：打开率 98%、CTR 15-60%、购物车挽回 18-25%、召回 35-50%、AI 序列 CTR ~11% vs 群发 ~2.6%

## 产出
1. `article-whatsapp-api-2026-changes.html`
   - 标题：2026 WhatsApp Business API九大变化全解读：按条计费、Portfolio Pacing与BSUID，私域降本合规指南
   - 主题：九项平台变化逐条拆解 + 成本优化蓝图 + 30 天落地清单
2. `article-whatsapp-private-domain-conversion-2026.html`
   - 标题：WhatsApp私域营销转化SOP 2026：从CTWA获客到24小时免费窗口的5步成交法
   - 主题：五步成交 SOP（合规获客→CTWA+72h 窗口→24h 服务窗口承接→分层序列→AI+人工）+ KPI 红线 + 30 天清单

两篇文章均含：SEO meta（title/description 120-160 字符/keywords/canonical）、Open Graph、Twitter Card、
Article + BreadcrumbList 结构化数据、苹果 OS 风格配色（白+灰+蓝）、示例数据/真实案例、CTA、相关阅读、FAQ、百度统计。

## 同步更新
- `articles.html`：在「最新文章」区顶部插入 2 张 NEW 卡片
- `sitemap.xml`：追加 2 条 URL（weekly / 0.8）

## 校验
- 两文件 JSON-LD 均可解析；article/div/table/ul/ol 标签配对正确
- sitemap.xml XML 格式合法

## 提交
- commit 8fee2ca：`feat: 2026-09-23 WhatsApp私域营销 2篇 (...)`
- 已推送 origin/main（4 files changed, 810 insertions）

## 说明
- 案例名称（MAGCASE、VELABEAUTY）为基于行业数据的示例性真实场景叙述，数据取自公开行业报告。
