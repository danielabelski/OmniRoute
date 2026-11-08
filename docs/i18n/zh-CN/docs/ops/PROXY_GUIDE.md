# 🌐 OmniRoute Proxy Guide (中文 (简体))

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **绕过地理封锁，保护您的身份，并通过任何代理—路由AI流量，配置复杂性为零。**

OmniRoute包含一个功能齐全的代理管理系统，可让您通过HTTP、 HTTPS或SOCKS5代理路由上游AI提供者流量。无论您是在封锁区域、需要IP旋转还是想要隐形指纹—本指南都涵盖了所有内容。

---

## 目录

- [为什么使用代理？](#why-use-proxies)
- [架构概述](#architecture-overview)
- [四级代理系统](#4-level-proxy-system)
- [代理注册中心 (CRUD)](#proxy-registry-crud)
- [1proxy 免费市场](#1proxy-free-proxy-marketplace)
- [代理轮换](#proxy-rotation)
- [反探测与隐身](#anti-detection--stealth)
- [上游代理模式](#upstream-proxy-modes)
- [仪表板UI](#dashboard-ui)
- [API参考](#api-reference)
- [环境变量](#environment-variables)
- [故障排除](#troubleshooting)

---

## 为什么使用代理？

许多AI提供者按地理区域限制访问。开发商位于**俄罗斯、中国、伊朗、古巴、土耳其**，而其他国家/地区会遇到如下错误：

```
unsupported_country_region_territory
```

即使在封锁区域之外，代理也可用于：

| 使用案例     | 描述                                                |
| ------------ | --------------------------------------------------- |
| **地理绕行** | 从被封锁的国家访问OpenAI, Anthropic, Codex, Copilot |
| **IP轮换**   | 将请求分布到多个IPs以避免速率限制                   |
| **隐私**     | 对上游提供者隐藏您真实的IP                          |
| **遵守**     | 通过特定管辖区路由流量                              |
| **测试**     | 模拟不同地区的请求                                  |

---

## 架构概述

```
┌───────────────────────────────────────────────────────────────┐
│                       OmniRoute Server                        │
│                                                               │
│  ┌─────────────┐    ┌──────────────┐    ┌──────────────────┐  │
│  │ Proxy       │    │ Proxy        │    │ Proxy            │  │
│  │ Registry    │───▶│ Dispatcher   │───▶│ Fetch (undici)   │  │
│  │ (SQLite)    │    │ (cached)     │    │                  │  │
│  └─────────────┘    └──────────────┘    └────────┬─────────┘  │
│         ▲                                        │            │
│         │                                        ▼            │
│  ┌──────┴──────┐                        ┌──────────────────┐  │
│  │ 1proxy Sync │                        │ Upstream         │  │
│  │ (free pool) │                        │ Provider API     │  │
│  └─────────────┘                        └──────────────────┘  │
└───────────────────────────────────────────────────────────────┘
```

### 关键部件

| 成分             | 文件                                         | 角色                                            |
| ---------------- | -------------------------------------------- | ----------------------------------------------- |
| **代理登记处**   | `src/lib/db/proxies.ts`                      | CRUD用于代理条目+范围分配                       |
| **代理调度程序** | `open-sse/utils/proxyDispatcher.ts`          | 创建带有缓存的`undici` ProxyAgent/SOCKS调度程序 |
| **代理获取**     | `open-sse/utils/proxyFetch.ts`               | 使用代理调度程序注入封装`fetch()`               |
| **设置路线**     | `src/app/api/settings/proxy/route.ts`        | 旧代理配置API (GET/PUT/DELETE)                  |
| **管理路线**     | `src/app/api/v1/management/proxies/route.ts` | 注册表CRUD API (GET/POST/PATCH/DELETE)          |
| **1代理DB**      | `src/lib/db/oneproxy.ts`                     | 免费代理市场持久性                              |

---

## 新帐户的默认代理状态

在**设置→代理→全局配置**， 使用**默认为新连接启用代理**选择新添加的提供者帐户的初始代理状态。

新设置控制新添加的提供者帐户的初始代理状态。它不会更改现有帐户或替换全局代理交换机。它的初始值保留了之前的行为。将其关闭一次以创建默认情况下禁用代理的未来帐户。

该首选项通过现有设置API存储为`defaultNewConnectionProxyEnabled` 。从未保存时默认为`true` 。保存`false`对后续新账户生效，无需重启。 `POST /api/providers`接受可选的严格布尔值`proxyEnabled`；显式`true`或`false`优先于创建默认值。省略重复帐户或OAuth重新连接会保留该帐户的存储状态。之后仍可以启用或禁用个人帐户。

选择性提供者传输使用新帐户的目标安装默认设置，并在替换现有帐户时保留目标策略。代理切换不是便携式传输字段。完整备份恢复和历史JSON/SQL迁移保留其现有的恢复语义，包括保存的帐户值和旧模式默认值；完整设置恢复也可以恢复此首选项。

此首选项不会分配代理或确定代理是否健康或正在使用。实际路由仍然取决于全局代理交换机和适用的代理配置。没有持久帐户的综合提供者、帐户创建前的OAuth流量、 environment/system代理和外部后端网络均超出其范围。

## 四级代理系统

OmniRoute支持代理配置**四个独立的范围**，按优先顺序解决：

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### 分辨率如何运作

当OmniRoute向上游提供者发送请求时，它会调用`resolveProxyForConnectionFromRegistry()`按顺序检查每个级别：

1. **账户级别**—是否有分配给此特定连接ID代理？
2. **提供者级**—是否有分配给该提供者的代理（例如`openai`）？
3. **全球层面**—是否配置了全局代理？
4. **无代理**—直接连接到提供者。

第一场比赛获胜。这意味着您可以将全局代理设置为后备，但针对特定提供者或连接覆盖它。

### 什么被代理

| 流量类型        | 代理？ | 笔记                                       |
| --------------- | ------ | ------------------------------------------ |
| 聊天完成情况    | ✅     | 所有`/v1/chat/completions`请求             |
| 嵌入            | ✅     | `/v1/embeddings`                           |
| 图像生成        | ✅     | `/v1/images/generations`                   |
| 音频（TTS/STT） | ✅     | `/v1/audio/*`                              |
| OAuth币兑换     | ✅     | 解决`unsupported_country_region_territory` |
| 连接测试        | ✅     | “测试连接”按钮使用代理                     |
| 令牌刷新        | ✅     | 后台OAuth续订                              |
| 模型同步        | ✅     | 模型列表和发现                             |

---

## 代理注册中心 (CRUD)

代理注册表是一个SQLite表 (`proxy_registry`)，用于存储所有代理。每个代理都有：

| 场地       | 类型 | 描述                               |
| ---------- | ---- | ---------------------------------- |
| `id`       | UUID | 唯一标识符                         |
| `name`     | 细绳 | 人类可读的标签                     |
| `type`     | 细绳 | 协议： `http`、 `https`、 `socks5` |
| `host`     | 细绳 | 代理主机名或IP                     |
| `port`     | 整数 | 端口号                             |
| `username` | 细绳 | 身份验证用户名（静态加密）         |
| `password` | 细绳 | 身份验证密码（静态加密）           |
| `region`   | 细绳 | 地理区域标签                       |
| `notes`    | 细绳 | 自由文本注释                       |
| `status`   | 细绳 | `active`或`inactive`               |
| `source`   | 细绳 | `manual`或`oneproxy`               |

### 创建代理

**通过仪表板：**

1. 前往**设置→代理**
2. 点击**添加代理**
3. 填写类型、主机、端口和可选的身份验证凭据
4. 节省

**通过API：**

```bash
curl -X POST http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "name": "US Proxy",
    "type": "http",
    "host": "proxy.example.com",
    "port": 8080,
    "username": "user",
    "password": "pass",
    "region": "US"
  }'
```

### 更新代理

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **笔记：**除非您明确发送非空替换，否则凭证将被保留。为`username`/`password`发送空字符串将保留存储的值。

### 删除代理

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### 列表代理

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### 将代理分配给范围

```bash
# Assign to global scope
curl -X PUT http://localhost:20128/api/settings/proxy \
  -H "Content-Type: application/json" \
  -d '{"level": "global", "proxy": {"type":"http","host":"proxy.example.com","port":8080}}'

# Assign to a specific provider
curl -X PUT http://localhost:20128/api/settings/proxy \
  -H "Content-Type: application/json" \
  -d '{"level": "provider", "id": "openai", "proxy": {"type":"socks5","host":"socks.example.com","port":1080}}'

# Assign to a specific connection/key
curl -X PUT http://localhost:20128/api/settings/proxy \
  -H "Content-Type: application/json" \
  -d '{"level": "key", "id": "connection-uuid", "proxy": {"type":"http","host":"key-proxy.com","port":3128}}'
```

### 解决有效代理

检查给定连接将使用哪个代理：

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

返回已解析的代理及其级别（`account`、 `provider`或`global`）和源。

### 批量分配

一次将一个代理分配给多个提供者或连接：

```bash
curl -X POST http://localhost:20128/api/v1/management/proxies/bulk-assign \
  -H "Content-Type: application/json" \
  -d '{
    "scope": "provider",
    "scopeIds": ["openai", "anthropic", "codex"],
    "proxyId": "proxy-uuid"
  }'
```

### Import/Export

代理包含在**Backup/Restore**系统。当您导出OmniRoute配置时：

1. 前往**仪表板→设置→备份**
2. 点击**出口**包括—代理注册表和分配
3. 要恢复，请单击**进口**并上传备份文件

代理注册表还支持**通过主机+端口更新插入**—如果您导入已存在的代理（相同的主机和端口），它将更新而不是创建副本。

### 旧版迁移

如果您在旧版本（预注册）中配置了代理， OmniRoute会自动迁移它们：

```
Legacy key_value store → proxy_registry + proxy_assignments
```

升级后首次启动时会发生一次这种情况。使用`migrateLegacyProxyConfigToRegistry({ force: true })`重新运行。

---

## 1proxy 免费代理市场

> 🆕**贡献者： [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) （问题[#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) ）

OmniRoute与**[1个代理](https://1proxy-api.aitradepulse.com)**社区平台提供访问**数百个免费且经过验证的代理**来自世界各地。这对于没有自己的代理基础设施的用户来说是完美的。

### 它是如何运作的

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **同步**— OmniRoute从 1proxy API获取经过验证的代理
2. **店铺**—代理与`source = 'oneproxy'`保存在同一个`proxy_registry`表中
3. **筛选**—按协议、国家/地区、质量得分过滤
4. **旋转**—使用质量、随机或顺序策略选择最佳代理
5. **自动降解**—失败的代理的质量分数会降低；低于阈值→标记为非活动状态

### 同步代理

**通过仪表板：**

1. 前往**设置→ 1proxy**选项卡
2. 点击**“立即同步”**
3. 查看统计数据：代理总数、活跃数量、平均质量、按国家/地区细分

**通过API：**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### 过滤代理

```bash
# Filter by protocol
curl "http://localhost:20128/api/settings/oneproxy?protocol=socks5"

# Filter by country
curl "http://localhost:20128/api/settings/oneproxy?countryCode=US"

# Filter by minimum quality score
curl "http://localhost:20128/api/settings/oneproxy?minQuality=80"

# Combine filters
curl "http://localhost:20128/api/settings/oneproxy?protocol=http&countryCode=DE&minQuality=70"
```

### 代理质量得分

每个 1proxy 代理都带有元数据：

| 场地            | 描述                                 |
| --------------- | ------------------------------------ |
| `qualityScore`  | 1proxy 验证的 0-100 评级             |
| `latencyMs`     | 测量的网络延迟                       |
| `anonymity`     | `transparent`、 `anonymous`或`elite` |
| `googleAccess`  | proxy是否可以访问Google服务          |
| `countryCode`   | 两个字母的ISO国家/地区代码           |
| `lastValidated` | 上次验证的时间戳                     |

质量分数动态调整：

- **失败的请求**降低10分
- **≤分数降至 10** →代理标记为`inactive`
- 不活动的代理被排除在轮换之外

### 轮换策略

```bash
# Rotate by quality (best proxy first) — default
curl -X POST http://localhost:20128/api/settings/oneproxy/rotate \
  -H "Content-Type: application/json" \
  -d '{"strategy": "quality"}'

# Random rotation
curl -X POST http://localhost:20128/api/settings/oneproxy/rotate \
  -d '{"strategy": "random"}'

# Sequential (least recently validated first)
curl -X POST http://localhost:20128/api/settings/oneproxy/rotate \
  -d '{"strategy": "sequential"}'
```

### 断路器

1proxy 同步有一个内置断路器：

- 后**连续 5 次同步失败**，进一步的同步尝试被阻止
- 重置： `resetOneproxyCircuitBreaker()`或重新启动服务器
- 同步状态可在`GET /api/settings/oneproxy?action=status`上获取

### 清除1proxy代理

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## 反探测与隐身

OmniRoute不仅仅通过代理—路由流量，它还使流量看起来合法：

### TLS指纹欺骗

使用`wreq-js`生成类似浏览器的TLS指纹，绕过标记非浏览器TLS握手的机器人检测系统。

### CLI指纹比对

这**CLI指纹切换**(`Settings → Security`) 重新排序HTTP标头和JSON正文字段以匹配本机CLI二进制文件的确切签名（Claude Code、 Codex等）。这有效**在上面**代理：

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

你两者都得到**IP掩码**和**要求真实性**同时地。

### 代理IP保存

仪表板中的颜色编码徽章显示哪个代理级别处于活动状态：

| 徽章 | 等级   | 意义                              |
| ---- | ------ | --------------------------------- |
| 🟢   | 全球的 | 所有流量都经过此代理              |
| 🟡   | 提供者 | 仅代理该提供者的流量              |
| 🔵   | 联系   | 这个特定的key/account使用这个代理 |

徽章还显示已解析的代理IP以供验证。

---

## 上游代理模式

对于使用CLIProxyAPI模式的提供者， OmniRoute支持三种上游代理模式：

| 模式          | 描述                                |
| ------------- | ----------------------------------- |
| `native`      | OmniRoute直接处理代理路由（默认）   |
| `cliproxyapi` | 委托给外部CLIProxyAPI实例           |
| `fallback`    | 首先尝试原生，然后回退到CLIProxyAPI |

配置每个提供者：

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## 仪表板UI

### 设置→代理选项卡

- **全球代理**配置（为所有流量设置一次）
- **每个提供者的代理**覆盖
- **每个连接代理**作业
- **连接测试**通过配置的代理
- **颜色编码徽章**显示活动代理级别

### 设置→ 1proxy 选项卡

- **立即同步**获取免费代理的按钮
- **统计卡**：总计、活动、平均质量、上次同步
- **过滤器**：协议、国家代码、最低质量
- **代理表**包含主机、协议、国家/地区、质量得分、延迟、匿名、 Google访问
- **同步状态**具有success/failure跟踪和连续故障计数的面板
- **全部清除**删除所有 1proxy 条目

---

## API参考

### 代理设置API

| 方法     | 端点                                           | 描述               |
| -------- | ---------------------------------------------- | ------------------ |
| `GET`    | `/api/settings/proxy`                          | 获取完整的代理配置 |
| `GET`    | `/api/settings/proxy?level=global`             | 获取全球代理       |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | 获取提供者代理     |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | 解决有效代理       |
| `PUT`    | `/api/settings/proxy`                          | 更新代理配置       |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | 删除级别的代理     |

### 代理注册中心API

| 方法     | 端点                                              | 描述           |
| -------- | ------------------------------------------------- | -------------- |
| `GET`    | `/api/v1/management/proxies`                      | 列出所有代理   |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | 通过ID获取代理 |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | 获取代理分配   |
| `POST`   | `/api/v1/management/proxies`                      | 创建代理       |
| `PATCH`  | `/api/v1/management/proxies`                      | 更新代理       |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | 删除代理       |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | 强制删除       |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | 批量分配       |
| `GET`    | `/api/v1/management/proxies/assignments`          | 列出作业       |
| `GET`    | `/api/v1/management/proxies/health`               | 代理健康统计   |

### 隧道API

要将您的OmniRoute实例公开到公共互联网 (Cloudflare/ngrok/Tailscale)，而不是通过代理路由出站，请参阅[TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) 。隧道REST API位于`/api/tunnels/{cloudflared,ngrok,tailscale}/*`之下，并且与上面记录的出站代理链正交。

### 1代理API

| 方法     | 端点                                   | 描述              |
| -------- | -------------------------------------- | ----------------- |
| `GET`    | `/api/settings/oneproxy`               | 列表1proxy代理    |
| `GET`    | `/api/settings/oneproxy?action=stats`  | 获取统计+同步状态 |
| `GET`    | `/api/settings/oneproxy?action=status` | 仅获取同步状态    |
| `POST`   | `/api/settings/oneproxy`               | 触发同步          |
| `POST`   | `/api/settings/oneproxy/rotate`        | 轮换到下一个代理  |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | 删除一个          |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | 全部清除          |

### 上游代理API

| 方法     | 端点                              | 描述             |
| -------- | --------------------------------- | ---------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | 获取上游代理配置 |
| `PUT`    | `/api/upstream-proxy/:providerId` | 设置上游代理模式 |
| `DELETE` | `/api/upstream-proxy/:providerId` | 删除上游代理配置 |

---

## 环境变量

| 多变的                | 默认   | 描述                                               |
| --------------------- | ------ | -------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true` | 启用SOCKS5代理支持（ `.env.example`中默认`true` ） |

---

## 故障排除

### “SOCKS5代理已禁用”

在`.env`文件中设置`ENABLE_SOCKS5_PROXY=true`并重新启动。

### 通过代理出现“套接字挂起”错误

对于会丢弃空闲连接的廉价代理来说，这是正常现象。 OmniRoute已经通过以下方式处理了这个问题：

- 禁用代理连接上的保持活动状态 (`keepAliveTimeout: 1`)
- 禁用管道（`pipelining: 0`）
- 缓存调度程序以避免重复握手

如果问题仍然存在，请尝试其他代理或使用 1proxy 轮换功能。

### OAuth期间“unsupported_country_region_territory”

确保代理已配置**前**启动OAuth流程。 OmniRoute通过配置的代理路由OAuth令牌交换。首先设置全局或提供者级代理，然后进行连接。

### 代理未被使用

检查解析顺序：

1. 通过`GET /api/settings/proxy?resolve=your-connection-id`验证
2. 检查代理`status`是否为`active` （不是`inactive`）
3. 确保代理分配范围与您的连接匹配

### 1代理同步失败

检查同步状态：

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

如果`consecutiveFailures >= 5`，则断路器已跳闸。重启服务器进行重置，或者等待手动重置。

---

## 数据库架构

### `proxy_registry`表

```sql
CREATE TABLE proxy_registry (
  id TEXT PRIMARY KEY,
  name TEXT NOT NULL,
  type TEXT NOT NULL DEFAULT 'http',
  host TEXT NOT NULL,
  port INTEGER NOT NULL,
  username TEXT DEFAULT '',
  password TEXT DEFAULT '',
  region TEXT,
  notes TEXT,
  status TEXT DEFAULT 'active',
  source TEXT NOT NULL DEFAULT 'manual',    -- 'manual' or 'oneproxy'
  quality_score INTEGER,                     -- 0-100 (1proxy only)
  latency_ms INTEGER,                        -- milliseconds (1proxy only)
  anonymity TEXT,                            -- transparent/anonymous/elite
  google_access INTEGER DEFAULT 0,           -- can access Google? (1proxy)
  last_validated TEXT,                       -- ISO timestamp (1proxy)
  country_code TEXT,                         -- ISO 2-letter code (1proxy)
  created_at TEXT NOT NULL,
  updated_at TEXT NOT NULL
);
```

### `proxy_assignments`表

```sql
CREATE TABLE proxy_assignments (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  proxy_id TEXT NOT NULL REFERENCES proxy_registry(id),
  scope TEXT NOT NULL,        -- 'global', 'provider', 'account', 'combo'
  scope_id TEXT,              -- provider ID, connection ID, or combo ID
  created_at TEXT NOT NULL,
  updated_at TEXT NOT NULL,
  UNIQUE(scope, scope_id)
);
```

---

## 代理健康检查 (v3.8.16 +)

OmniRoute的**代理快速失败**机制（`src/lib/proxyHealth.ts`）通过快速TCP连接检查在< 2s 中检测死代理，然后**缓存结果**以避免每个请求的开销。

### 它是如何运作的

```
Request ──▶ ProxyHealthCache.get(url)
             │
             ├─ Cache hit + fresh?  ──▶ return cached status
             │
             └─ Cache miss / stale?  ──▶ TCP connect to host:port
                                          (timeout: FAST_FAIL_TIMEOUT_MS)
                                          ──▶ cache for HEALTH_CACHE_TTL_MS
                                          ──▶ return result
```

如果没有这个，死代理将在失败之前阻止对完整`PROXY_TIMEOUT_MS`的每个请求（默认 30 秒）。

### 可调整的环境变量

| 多变的                       | 默认    | 目的                          |
| ---------------------------- | ------- | ----------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | 每次运行状况检查的TCP连接超时 |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | 健康结果缓存多长时间          |

**推荐值：**

| 设想            | 快速失败超时 | 缓存TTL   | 推理                                                 |
| --------------- | ------------ | --------- | ---------------------------------------------------- |
| 高吞吐量API网关 | 1500毫秒     | 60000毫秒 | 积极的快速失败、更长的缓存以减少检查                 |
| 地理分布式节点  | 3000毫秒     | 15000毫秒 | 较慢的网络需要更多时间；更短的缓存可实现快速故障转移 |
| 开发/测试       | 1000毫秒     | 10000毫秒 | 本地代理的快速迭代                                   |
| 隐身/反探测     | 2500毫秒     | 45000毫秒 | 避免可能触发速率限制的快速探测                       |

### 检查代理健康状况

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

当缓存条目超过`HEALTH_CACHE_TTL_MS`且下一个请求将触发新检查时， `stale`标志为`true` 。

### 每个代理类型默认值

健康检查使用基于URL方案的合理默认值：

| 方案                       | 默认端口 |
| -------------------------- | -------- |
| `http://`                  | 8080     |
| `https://`                 | 443      |
| `socks5://` / `socks5h://` | 1080     |

URL (`http://host:9999`) 中的自定义端口始终优先于方案默认值。

---

## 代理分析和可观察性

OmniRoute跟踪每个代理的使用情况，以帮助运营商诊断路由模式、延迟峰值和重复出现的故障。

### 追踪的内容

对于通过配置的代理的每个请求， OmniRoute记录：

| 公制         | 描述                                 |
| ------------ | ------------------------------------ |
| `proxy_url`  | 完整代理URL （身份验证凭据被屏蔽）   |
| `provider`   | 上游提供者ID （openai、anthropic等） |
| `latency_ms` | 包括代理握手的总往返时间             |
| `connect_ms` | 仅TCP连接时间                        |
| `status`     | 来自上游的HTTP状态代码               |
| `error`      | 请求失败时的错误类                   |
| `timestamp`  | ISO 8601 UTC                         |

### 访问数据

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

真正的端点是`/api/usage/proxy-logs` （参见`src/app/api/usage/proxy-logs/route.ts`）。该端点支持：

- `GET /api/usage/proxy-logs` —检索代理日志
- `DELETE /api/usage/proxy-logs` —清除所有代理日志

如果需要，可以通过SQL直接从`proxy_logs`表查询聚合统计信息。仪表板UI可以提供聚合视图。

### 常见模式

**检测抖动代理**（在success/failure之间交替）：

```sql
SELECT proxy_url,
       COUNT(*) AS total,
       SUM(CASE WHEN status >= 500 THEN 1 ELSE 0 END) AS errors,
       ROUND(100.0 * SUM(CASE WHEN status >= 500 THEN 1 ELSE 0 END) / COUNT(*), 1) AS error_pct
FROM proxy_logs
WHERE timestamp > datetime('now', '-1 hour')
GROUP BY proxy_url
HAVING error_pct > 5
ORDER BY error_pct DESC;
```

**查找慢速代理**（p95 延迟> 2 秒）：

```sql
WITH ranked AS (
  SELECT proxy_url, latency_ms,
         PERCENT_RANK() OVER (PARTITION BY proxy_url ORDER BY latency_ms) AS pct
  FROM proxy_logs
  WHERE timestamp > datetime('now', '-24 hour')
)
SELECT proxy_url, latency_ms
FROM ranked
WHERE pct >= 0.95
ORDER BY latency_ms DESC;
```

---

## 轮换策略决策树

当多个代理被分配到一个作用域时， OmniRoute使用**轮换策略**为每个请求选择使用哪一个。该策略是在范围级别（全局、每个提供者、每个帐户、每个组合）配置的。

### 可用策略

| 战略               | 何时使用                 | 权衡                                   |
| ------------------ | ------------------------ | -------------------------------------- |
| `quality` （默认） | 使用混合质量代理进行生产 | 青睐高评价代理；可能会让低评级的人挨饿 |
| `random`           | 负载分配、隐私           | 分布均匀；忽略质量信号                 |
| `sequential`       | 调试、确定性测试         | 按顺序循环代理；容易推理               |

### 决策树

```
                    Do you have quality scores for your proxies?
                    │
        ┌───────────┴───────────┐
        │                       │
       YES                     NO
        │                       │
   Are all proxies             │
   roughly equal                  │
   in quality?                   │
        │                       │
   ┌────┴────┐                  │
   │         │                  │
  YES       NO                Use
   │         │              `random`
   │         │              (even spread
   │         │              builds quality
   │         │              data over time)
   │         │
   │    Use `quality`
   │    (best for
   │    mixed quality)
   │
Use `random`
(spread load
evenly)
```

## 自动排除您自己的代理的故障

1proxy 市场池已经自行自动降级失败的代理（请参阅[代理质量分数](#proxy-quality-scores)）。对于代理**你**添加到注册表后，后台运行状况调度程序（`src/lib/proxyHealth/scheduler.ts`）提供相同的“自动从链中排除失效成员”行为，而不删除任何内容：

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

它如何融入多代理链：

1. 调度程序每个`PROXY_HEALTH_INTERVAL_MS`都会探测每个已注册的代理（默认 10 分钟；最少 1 分钟）。
2. `PROXY_AUTO_REMOVE_AFTER`连续后**确凿**失败（真正的连接失败—超时或探测目标自己的 5xx 永远不会计数，请参阅[代理运行状况检查](#proxy-health-checking-v3816)），代理的`status`设置为`dead`。
3. `dead`是pool/rotation解析使用的活动状态过滤器排除的状态之一，因此作用域的轮换（循环/随机/粘性/延迟—请参阅[轮换策略决策树](#rotation-strategy-decision-tree)）立即停止将该代理移交给新请求。池中的其他代理不会受到影响，并且整个池永远不会默默地回退到直接连接—看到[4 级代理系统](#4-level-proxy-system)故障关闭防护。
4. 调度程序以相同的时间间隔不断探测`dead`代理。下一个成功的探测会将`status`翻转回`active` ，并重新进入旋转—无需手动重新添加。

这是故意的**选择加入且非破坏性**：默认情况下，调度程序仅计算和记录失败（请参阅`decision.ts`中的策略 C），并且`PROXY_AUTO_DISABLE`永远不会删除行—这就是单独的、更积极的`PROXY_AUTO_REMOVE`标志的用途。如果两者都设置为`true`， `PROXY_AUTO_REMOVE`获胜（即将删除的代理对于中间的软禁用没有用处）。有关完整变量列表，请参阅[环境配置](../reference/ENVIRONMENT.md)参考。

---

> 📖**相关文档：**
>
> - [用户指南](../guides/USER_GUIDE.md)—常规设置和配置 - [API参考](../reference/API_REFERENCE.md)—完整的API文档 -[环境配置](../reference/ENVIRONMENT.md)—所有环境变量
