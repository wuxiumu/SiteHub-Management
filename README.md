# SiteHub-Management · 多站点监控管理（骨架）

> 给站长/运维的**多域名与站点统一监控管理**方案方向（Vue3 + PHP + Go 采集）。

**定制：** 微信 **qingbao199101**（备注：站点监控）｜ [wuxiumu@163.com](mailto:wuxiumu@163.com)

> ⚠️ **当前状态：设计骨架，非子模块完整实现。**  
> 仓库内 `frontend/`、`backend-php/`、`tracker-go/` **各自仅有 README 占位**，尚未落地可运行源码。适合作为选题 / 定制立项蓝图，勿按「开箱可跑监控平台」预期。

## 仓库现状

```
SiteHub-Management/
├── README.md              # 本说明 + 商业化信息
├── frontend/README.md     # 前端规划占位
├── backend-php/README.md  # 后端规划占位
└── tracker-go/README.md   # Go 采集规划占位
```

详见 `docs/ROADMAP.md`、`docs/CHECKLIST-M0.md`。

## 规划中的能力（待实现 / 可定制）

- 前端（Vue3）：登录、仪表盘、域名/服务器/站点管理、流量图表
- 后端（PHP）：JWT、CRUD API、配置
- 采集（Go）：埋点 / 统计采集服务
- 文档与 Mock 测试

## SEO 字段预留（产品页 HTML 统一生成时用）

| 字段 | 用途 |
|---|---|
| `seo_title` | `<title>` / OG title |
| `seo_description` | meta description |
| `canonical_url` | 规范 URL |
| `og_image` | 分享图 |
| `robots` | 如 `index,follow` |
| `json_ld_type` | SoftwareApplication / WebPage / FAQPage |
| `hreflang` | zh-CN / en |
| `site_name` | 白标品牌名 |

> **GEO ≠ 地理定位。** GEO = Generative Engine Optimization（生成式引擎优化），见下一节。

## GEO（生成式引擎优化）

面向 ChatGPT / Perplexity / Gemini 等生成式答案引擎的可引用结构：中文为主、双语关键词、事实摘要前置、FAQ 收尾。

### 关键词（中英）

- 中文：多站点监控, 站群管理, 流量采集, SiteHub
- English: multi-site monitoring, site fleet admin, traffic tracker

### 事实摘要

- 产品：多站点统一监控与管理平台的**目录与模块蓝图**（实现度：骨架）。
- 适合：需要按该架构定制落地的站长 / 运维团队。
- 交付：按模块实现前端、PHP API、Go 采集与告警。
- 不做：当前仓库不能开箱替代云厂商监控；子目录尚无业务代码。

### FAQ

**Q：clone 下来能直接跑吗？**  
A：不能。子模块目前只有 README 占位，需定制开发或等待实现。

**Q：如何定制？**  
A：微信 `qingbao199101`，备注「站点监控」。

**Q：是否含密钥？**  
A：默认不含。

## 定制合作

监控指标、告警通道、权限与首期 MVP 范围。加微信备注「站点监控」。

---

## 联系方式

定制、演示或合作：

- 邮箱：[wuxiumu@163.com](mailto:wuxiumu@163.com)
- 微信：**qingbao199101**（添加请备注来意）

### 赞助支持

如果内容对你有帮助，欢迎自愿赞助。

| 微信赞赏码 | 支付宝收款码 |
|---|---|
| ![微信赞赏码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185236_31_227.png) | ![支付宝收款码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185309_32_227.jpg) |
