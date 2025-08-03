# GreasyFork 镜像站 / GreasyFork Mirror
## https://greasyfork.org.cn/zh-hans
脚本工具服务已移交运营，进入长期服务状态，不再发布重大更新。

[![状态](https://img.shields.io/badge/状态-运营中-brightgreen)](https://greasyfork.org.cn/zh-hans)  
[![Status](https://img.shields.io/badge/Status-Operational-brightgreen)](https://greasyfork.org.cn/zh-hans)  
[![文档](https://img.shields.io/badge/文档-Documentation-blue)](https://doc.greasyfork.org.cn/)  
![流量](https://img.shields.io/badge/流量重置-每日08:00_SGT-blue)

为网络不畅环境提供的备用镜像 / Alternative access for poor network conditions

**此镜像主网址**: [https://greasyfork.org.cn/zh-hans](https://greasyfork.org.cn/zh-hans)  
**文档中心**: [https://doc.greasyfork.org.cn/](https://doc.greasyfork.org.cn/)  

---

## ⚠️ 重要通知 / Important Notice
| 状态提示 | Status Alerts |
|----------|--------------|
| • 每日访问量过大时可能会出现 **HTTP 429 (1027/1102错误)** | • Daily traffic may cause **HTTP 429 (Error 1027/1102)** |
| • 流量限制（1027）每日新加坡时间08:00自动重置 | • Limits (1027) reset daily at **08:00 SGT (UTC+8)** |
| • 高峰期请错峰访问 | • Off-peak hours recommended during high traffic |

---

## 中文版

### 核心特点
- 🔄 **智能更新**：仅替换官方站相关链接，非全量更新
- 🛡️ **内容安全**：违禁词系统+违法内容搜索屏蔽
- ⏳ **缓存机制**：关键内容保留48小时
- 🔄 **每日重置**：1027错误每日08:00自动解除

### 功能状态
| 功能 | 状态 | 说明 |
|------|------|------|
| 脚本下载 | ✔️ 正常 | 自动替换依赖链接 |
| 用户登录 | ✔️ 正常 |  |
| 讨论区 | ⚠️ 部分 | 部分功能受限 |
| 验证码 | ❌ 不可用 | 所有人机验证功能 |

### 技术说明
1. **流量控制**：
   - 每日请求限额
   - 超额返回1027错误
   - 次日08:00自动恢复
2. **安全机制**：
   - 强制HTTPS
   - 内容过滤系统
   - 敏感词实时屏蔽

---

## English Version

### Key Features
- 🔄 **Smart Updates**: Official link replacements only
- 🛡️ **Content Safety**: Prohibited word filtering + illegal content blocking
- ⏳ **Caching**: Key content kept for 48h
- 🔄 **Daily Reset**: 1027 errors auto-clear at 08:00 SGT

### Status
| Feature | Status | Notes |
|---------|--------|-------|
| Scripts | ✔️ Works | Auto-link conversion |
| Login | ✔️ Works |  |
| Forum | ⚠️ Partial | Some limits |
| CAPTCHA | ❌ Unavailable | All verification |

### Technical Notes
1. **Traffic Control**:
   - Daily request quota
   - Returns 1027 when exceeded
   - Auto-reset at 08:00 SGT
2. **Security**:
   - Enforced HTTPS
   - Content filtering
   - Real-time word blocking

---

## 使用建议 / Recommendations
```diff
+ 推荐方案：
- 开发者：测试链接替换效果
- 普通用户：遇到1027错误可次日08:00后重试
- 高峰期：建议早晚非高峰时段访问

+ Recommended:
- Devs: Verify link conversions
- Users: Retry after 08:00 SGT if 1027 occurs
- Peak hours: Try early/late hours
```
