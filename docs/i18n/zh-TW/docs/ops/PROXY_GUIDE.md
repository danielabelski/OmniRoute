# 🌐 OmniRoute Proxy Guide (中文 (繁體))

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md)

---

> **繞過地理封鎖，保護您的身份，並透過任何代理—路由AI流量，配置複雜度為零。**

OmniRoute包含一個功能齊全的代理管理系統，可讓您透過HTTP、 HTTPS或SOCKS5代理程式路由上游AI提供者流量。無論您是在封鎖區域、需要IP旋轉還是想要隱形指紋—本指南都涵蓋了所有內容。

---

## 目錄

- [為什麼要使用代理？](#why-use-proxies)
- [架構概述](#architecture-overview)
- [四級代理系統](#4-level-proxy-system)
- [代理註冊中心 (CRUD)](#proxy-registry-crud)
- [1proxy 免費市場](#1proxy-free-proxy-marketplace)
- [代理輪換](#proxy-rotation)
- [反偵測與隱身](#anti-detection--stealth)
- [上游代理模式](#upstream-proxy-modes)
- [儀表板UI](#dashboard-ui)
- [API參考](#api-reference)
- [環境變數](#environment-variables)
- [故障排除](#troubleshooting)

---

## 為什麼要使用代理？

許多AI提供者按地理區域限制存取。開發商位於**俄羅斯、中國、伊朗、古巴、土耳其**，而其他國家會遇到以下錯誤：

```
unsupported_country_region_territory
```

即使在封鎖區域之外，代理商也可用於：

| 使用案例     | 描述                                                |
| ------------ | --------------------------------------------------- |
| **地理繞行** | 從被封鎖的國家訪問OpenAI, Anthropic, Codex, Copilot |
| **IP輪換**   | 將請求分佈到多個IPs以避免速率限制                   |
| **隱私**     | 對上游提供者隱藏您真實的IP                          |
| **遵守**     | 透過特定管轄區路由流量                              |
| **測試**     | 模擬不同地區的請求                                  |

---

## 架構概述

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

### 關鍵零件

| 成分             | 文件                                         | 角色                                            |
| ---------------- | -------------------------------------------- | ----------------------------------------------- |
| **代理登記處**   | `src/lib/db/proxies.ts`                      | CRUD用於代理條目+範圍分配                       |
| **代理調度程序** | `open-sse/utils/proxyDispatcher.ts`          | 建立帶有快取的`undici` ProxyAgent/SOCKS調度程序 |
| **代理獲取**     | `open-sse/utils/proxyFetch.ts`               | 使用代理調度程序注入封裝`fetch()`               |
| **設定路線**     | `src/app/api/settings/proxy/route.ts`        | 舊代理配置API (GET/PUT/DELETE)                  |
| **管理路線**     | `src/app/api/v1/management/proxies/route.ts` | 註冊表CRUD API (GET/POST/PATCH/DELETE)          |
| **1代理DB**      | `src/lib/db/oneproxy.ts`                     | 免費代理市場持久性                              |

---

## 新帳戶的預設代理狀態

在**設定→代理→全域配置**， 使用**預設為新連線啟用代理**選擇新新增的提供者帳戶的初始代理狀態。

新設定控制新新增的提供者帳戶的初始代理狀態。它不會更改現有帳戶或替換全域代理交換器。它的初始值保留了先前的行為。將其關閉一次以建立預設情況下停用代理程式的未來帳戶。

此首選項透過現有設定API儲存為`defaultNewConnectionProxyEnabled` 。從未儲存時預設為`true` 。儲存`false`對後續新帳戶生效，無需重新啟動。 `POST /api/providers`接受可選的嚴格布林值`proxyEnabled`；明確`true`或`false`優先於建立預設值。省略重複帳戶或OAuth重新連線會保留該帳戶的儲存狀態。之後仍可以啟用或停用個人帳號。

選擇性提供者傳輸使用新帳戶的目標安裝預設設置，並在替換現有帳戶時保留目標策略。代理切換不是便攜式傳輸欄位。完整備份還原和歷史JSON/SQL遷移保留其現有的復原語義，包括已儲存的帳戶值和舊模式預設值；完整設定還原也可以還原此首選項。

此首選項不會分配代理或確定代理是否健康或正在使用。實際路由仍然取決於全域代理交換器和適用的代理程式配置。沒有持久帳戶的綜合提供者、帳戶建立前的OAuth流量、 environment/system代理程式和外部後端網路均超出其範圍。

## 四級代理系統

OmniRoute支援代理配置**四個獨立的範圍**，依優先順序解決：

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### 解析度如何運作

當OmniRoute向上游提供者發送請求時，它會呼叫`resolveProxyForConnectionFromRegistry()`按順序檢查每個層級：

1. **帳戶等級**—是否有分配給此特定連接ID代理？
2. **提供者級**—是否有分配給該提供者的代理人（例如`openai`）？
3. **全球層面**—是否配置了全域代理？
4. **無代理**—直接連接到提供者。

第一場比賽獲勝。這意味著您可以將全域代理設定為後備，但針對特定提供者或連線覆寫它。

### 什麼被代理

| 流量類型        | 代理？ | 筆記                                       |
| --------------- | ------ | ------------------------------------------ |
| 聊天完成狀況    | ✅     | 所有`/v1/chat/completions`請求             |
| 嵌入            | ✅     | `/v1/embeddings`                           |
| 影像生成        | ✅     | `/v1/images/generations`                   |
| 音訊（TTS/STT） | ✅     | `/v1/audio/*`                              |
| OAuth幣兌換     | ✅     | 解決`unsupported_country_region_territory` |
| 連接測試        | ✅     | “測試連線”按鈕使用代理                     |
| 令牌刷新        | ✅     | 後台OAuth續訂                              |
| 模型同步        | ✅     | 模型清單和發現                             |

---

## 代理註冊中心 (CRUD)

代理註冊表是一個SQLite表 (`proxy_registry`)，用於儲存所有代理。每個代理商都有：

| 場地       | 類型 | 描述                               |
| ---------- | ---- | ---------------------------------- |
| `id`       | UUID | 唯一識別符                         |
| `name`     | 細繩 | 人類可讀的標籤                     |
| `type`     | 細繩 | 協定： `http`、 `https`、 `socks5` |
| `host`     | 細繩 | 代理主機名稱或IP                   |
| `port`     | 整數 | 連接埠號                           |
| `username` | 細繩 | 身份驗證使用者名稱（靜態加密）     |
| `password` | 細繩 | 身份驗證密碼（靜態加密）           |
| `region`   | 細繩 | 地理區域標籤                       |
| `notes`    | 細繩 | 自由文本註釋                       |
| `status`   | 細繩 | `active`或`inactive`               |
| `source`   | 細繩 | `manual`或`oneproxy`               |

### 創建代理

**透過儀表板：**

1. 前往**設定→代理**
2. 點選**新增代理**
3. 填寫類型、主機、連接埠和可選的身份驗證憑證
4. 節省

**透過API：**

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

> **筆記：**除非您明確發送非空替換，否則憑證將被保留。為`username`/`password`發送空字串將保留儲存的值。

### 刪除代理

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

### 將代理程式分配給範圍

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

### 解決有效代理

檢查給定連線將使用哪個代理：

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

傳回已解析的代理程式及其等級（`account`、 `provider`或`global`）和來源。

### 批量分配

一次將一個代理程式指派給多個提供者或連線：

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

代理包含在**Backup/Restore**系統。當您匯出OmniRoute配置時：

1. 前往**儀表板→設定→備份**
2. 點選**出口**包括—代理註冊表和分配
3. 若要恢復，請按一下**進口**並上傳備份文件

代理註冊表也支持**透過主機+連接埠更新插入**—如果您匯入已存在的代理程式（相同的主機和連接埠），它將更新而不是建立副本。

### 舊版遷移

如果您在舊版本（預先註冊）中配置了代理， OmniRoute會自動遷移它們：

```
Legacy key_value store → proxy_registry + proxy_assignments
```

升級後首次啟動時會發生一次這種情況。使用`migrateLegacyProxyConfigToRegistry({ force: true })`重新運行。

---

## 1proxy 免費代理市場

> 🆕**貢獻者： [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) （問題[#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) ）

OmniRoute與**[1個代理](https://1proxy-api.aitradepulse.com)**社區平台提供訪問**數百個免費且經過驗證的代理**來自世界各地。這對於沒有自己的代理基礎設施的用戶來說是完美的。

### 它是如何運作的

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **同步**— OmniRoute從 1proxy API取得經過驗證的代理
2. **店鋪**—代理與`source = 'oneproxy'`保存在同一個`proxy_registry`表中
3. **篩選**—按協議、國家/地區、品質分數過濾
4. **旋轉**—使用品質、隨機或順序策略選擇最佳代理
5. **自動降解**—失敗的代理人的品質分數會降低；低於閾值→標記為非活動狀態

### 同步代理

**透過儀表板：**

1. 前往**設定→ 1proxy**選項卡
2. 點選**“立即同步”**
3. 查看統計數據：代理總數、活躍數量、平均品質、按國家/地區細分

**透過API：**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### 過濾代理

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

### 代理品質得分

每個 1proxy 代理程式都帶有元資料：

| 場地            | 描述                                 |
| --------------- | ------------------------------------ |
| `qualityScore`  | 1proxy 驗證的 0-100 評級             |
| `latencyMs`     | 測量的網路延遲                       |
| `anonymity`     | `transparent`、 `anonymous`或`elite` |
| `googleAccess`  | proxy是否可以存取Google服務          |
| `countryCode`   | 兩個字母的ISO國家/地區代碼           |
| `lastValidated` | 上次驗證的時間戳                     |

品質分數動態調整：

- **失敗的請求**降低10分
- **≤分數降至 10** →代理標記為`inactive`
- 不活動的代理被排除在輪換之外

### 輪換策略

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

### 斷路器

1proxy 同步有一個內建斷路器：

- 後**連續 5 次同步失敗**，進一步的同步嘗試被阻止
- 重置： `resetOneproxyCircuitBreaker()`或重新啟動伺服器
- 同步狀態可在`GET /api/settings/oneproxy?action=status`上取得

### 清除1proxy代理

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## 反偵測與隱身

OmniRoute不僅透過代理—路由流量，它還使流量看起來合法：

### TLS指紋欺騙

使用`wreq-js`產生類似瀏覽器的TLS指紋，繞過標記非瀏覽器TLS握手的機器人偵測系統。

### CLI指紋比對

這**CLI指紋切換**(`Settings → Security`) 重新排序HTTP標頭和JSON正文欄位以符合本機CLI二進位檔案的確切簽章（Claude Code、 Codex等）。這有效**在上面**代理：

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

你兩者都得到**IP掩碼**和**要求真實性**同時地。

### 代理IP保存

儀表板中的顏色編碼徽章顯示哪個代理級別處於活動狀態：

| 徽章 | 等級   | 意義                              |
| ---- | ------ | --------------------------------- |
| 🟢   | 全球的 | 所有流量都經過此代理              |
| 🟡   | 提供者 | 僅代理該提供者的流量              |
| 🔵   | 聯繫   | 這個特定的key/account使用這個代理 |

徽章也顯示已解析的代理程式IP以供驗證。

---

## 上游代理模式

對於使用CLIProxyAPI模式的提供者， OmniRoute支援三種上游代理模式：

| 模式          | 描述                              |
| ------------- | --------------------------------- |
| `native`      | OmniRoute直接處理代理路由（預設） |
| `cliproxyapi` | 委託給外部CLIProxyAPI實例         |
| `fallback`    | 先嘗試原生，然後回退到CLIProxyAPI |

配置每個提供者：

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## 儀表板UI

### 設定→代理選項卡

- **全球代理**配置（為所有流量設定一次）
- **每個提供者的代理**覆蓋
- **每個連接代理**作業
- **連接測試**透過配置的代理
- **顏色編碼徽章**顯示活動代理級別

### 設定→ 1proxy 選項卡

- **立即同步**取得免費代理的按鈕
- **統計卡**：總計、活動、平均品質、上次同步
- **過濾器**：協議、國家代碼、最低質量
- **代理表**包含主機、協議、國家/地區、品質得分、延遲、匿名、 Google訪問
- **同步狀態**具有success/failure追蹤和連續故障計數的面板
- **全部清除**刪除所有 1proxy 條目

---

## API參考

### 代理設定API

| 方法     | 端點                                           | 描述               |
| -------- | ---------------------------------------------- | ------------------ |
| `GET`    | `/api/settings/proxy`                          | 取得完整的代理配置 |
| `GET`    | `/api/settings/proxy?level=global`             | 獲取全球代理       |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | 取得提供者代理     |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | 解決有效代理       |
| `PUT`    | `/api/settings/proxy`                          | 更新代理程式配置   |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | 刪除層級的代理     |

### 代理註冊中心API

| 方法     | 端點                                              | 描述           |
| -------- | ------------------------------------------------- | -------------- |
| `GET`    | `/api/v1/management/proxies`                      | 列出所有代理   |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | 透過ID獲取代理 |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | 獲取代理分配   |
| `POST`   | `/api/v1/management/proxies`                      | 創建代理       |
| `PATCH`  | `/api/v1/management/proxies`                      | 更新代理       |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | 刪除代理       |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | 強制刪除       |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | 批量分配       |
| `GET`    | `/api/v1/management/proxies/assignments`          | 列出作業       |
| `GET`    | `/api/v1/management/proxies/health`               | 代理健康統計   |

### 隧道API

若要將您的OmniRoute執行個體公開到公共網際網路 (Cloudflare/ngrok/Tailscale)，而不是透過代理程式路由出站，請參閱[TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) 。隧道REST API位於`/api/tunnels/{cloudflared,ngrok,tailscale}/*`之下，並且與上面記錄的出站代理鏈正交。

### 1代理API

| 方法     | 端點                                   | 描述              |
| -------- | -------------------------------------- | ----------------- |
| `GET`    | `/api/settings/oneproxy`               | 列表1proxy代理    |
| `GET`    | `/api/settings/oneproxy?action=stats`  | 取得統計+同步狀態 |
| `GET`    | `/api/settings/oneproxy?action=status` | 僅獲取同步狀態    |
| `POST`   | `/api/settings/oneproxy`               | 觸發同步          |
| `POST`   | `/api/settings/oneproxy/rotate`        | 輪換到下一個代理  |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | 刪除一個          |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | 全部清除          |

### 上游代理API

| 方法     | 端點                              | 描述             |
| -------- | --------------------------------- | ---------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | 獲取上游代理配置 |
| `PUT`    | `/api/upstream-proxy/:providerId` | 設定上游代理模式 |
| `DELETE` | `/api/upstream-proxy/:providerId` | 刪除上游代理配置 |

---

## 環境變數

| 多變的                | 預設   | 描述                                               |
| --------------------- | ------ | -------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true` | 啟用SOCKS5代理支援（ `.env.example`中預設`true` ） |

---

## 故障排除

### “SOCKS5代理程式已停用”

在`.env`檔案中設定`ENABLE_SOCKS5_PROXY=true`並重新啟動。

### 透過代理出現「套接字掛起」錯誤

對於會丟棄空閒連線的廉價代理來說，這是正常現象。 OmniRoute已經透過以下方式處理了這個問題：

- 停用代理連線上的保持活動狀態 (`keepAliveTimeout: 1`)
- 禁用管道（`pipelining: 0`）
- 快取調度程序以避免重複握手

如果問題仍然存在，請嘗試其他代理程式或使用 1proxy 輪換功能。

### OAuth期間“unsupported_country_region_territory”

確保代理已配置**前**啟動OAuth流程。 OmniRoute透過設定的代理路由OAuth令牌交換。首先設定全域或提供者級代理，然後進行連線。

### 代理未被使用

檢查解析順序：

1. 透過`GET /api/settings/proxy?resolve=your-connection-id`驗證
2. 檢查代理`status`是否為`active` （不是`inactive`）
3. 確保代理分配範圍與您的連線相符

### 1代理同步失敗

檢查同步狀態：

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

如果`consecutiveFailures >= 5`，則斷路器已跳脫。重啟伺服器進行重置，或等待手動重置。

---

## 資料庫結構定義

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

## 代理健康檢查 (v3.8.16 +)

OmniRoute的**代理快速失敗**機制（`src/lib/proxyHealth.ts`）透過快速TCP連線檢查在< 2s 中偵測死代理，然後**快取結果**以避免每個請求的開銷。

### 它是如何運作的

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

如果沒有這個，死代理將在失敗之前阻止對完整`PROXY_TIMEOUT_MS`的每個請求（預設 30 秒）。

### 可調整的環境變數

| 多變的                       | 預設    | 目的                          |
| ---------------------------- | ------- | ----------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | 每次運行狀況檢查的TCP連線逾時 |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | 健康結果快取多長時間          |

**推薦值：**

| 設想            | 快速失敗超時 | 快取TTL   | 推理                                                 |
| --------------- | ------------ | --------- | ---------------------------------------------------- |
| 高吞吐量API網關 | 1500毫秒     | 60000毫秒 | 積極的快速失敗、更長的快取以減少檢查                 |
| 地理分散式節點  | 3000毫秒     | 15000毫秒 | 較慢的網路需要更多時間；更短的快取可實現快速故障轉移 |
| 開發/測試       | 1000毫秒     | 10000毫秒 | 本地代理的快速迭代                                   |
| 隱身/反探測     | 2500毫秒     | 45000毫秒 | 避免可能觸發速率限制的快速探測                       |

### 檢查代理健康狀況

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

當快取條目超過`HEALTH_CACHE_TTL_MS`且下一個請求將觸發新檢查時， `stale`標誌為`true` 。

### 每個代理類型預設值

健康檢查使用基於URL方案的合理預設值：

| 方案                       | 預設連接埠 |
| -------------------------- | ---------- |
| `http://`                  | 8080       |
| `https://`                 | 443        |
| `socks5://` / `socks5h://` | 1080       |

URL (`http://host:9999`) 中的自訂連接埠始終優先於方案預設值。

---

## 代理分析和可觀察性

OmniRoute追蹤每個代理程式的使用情況，以幫助營運商診斷路由模式、延遲峰值和重複出現的故障。

### 追蹤的內容

對於透過設定的代理程式的每個請求， OmniRoute記錄：

| 公制         | 描述                                 |
| ------------ | ------------------------------------ |
| `proxy_url`  | 完整代理URL （驗證憑證被封鎖）       |
| `provider`   | 上游提供者ID （openai、anthropic等） |
| `latency_ms` | 包括代理握手的總往返時間             |
| `connect_ms` | 僅TCP連線時間                        |
| `status`     | 來自上游的HTTP狀態碼                 |
| `error`      | 請求失敗時的錯誤類                   |
| `timestamp`  | ISO 8601 UTC                         |

### 存取數據

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

真正的端點是`/api/usage/proxy-logs` （參見`src/app/api/usage/proxy-logs/route.ts`）。此端點支援：

- `GET /api/usage/proxy-logs` —檢索代理日誌
- `DELETE /api/usage/proxy-logs` —清除所有代理程式日誌

如果需要，可以透過SQL直接從`proxy_logs`表查詢聚合統計資料。儀表板UI可以提供聚合視圖。

### 常見模式

**偵測抖動代理**（在success/failure之間交替）：

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

**查找慢速代理**（p95 延遲> 2 秒）：

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

## 輪換策略決策樹

當多個代理被分配到一個作用域時， OmniRoute使用**輪換策略**為每個請求選擇使用哪一個。此策略是在範圍層級（全域、每個提供者、每個帳戶、每個組合）配置的。

### 可用策略

| 策略               | 何時使用                 | 權衡                                   |
| ------------------ | ------------------------ | -------------------------------------- |
| `quality` （預設） | 使用混合品質代理進行生產 | 青睞高評價代理；可能會讓低評價的人挨餓 |
| `random`           | 負載分配、隱私           | 分佈均勻；忽略質量訊號                 |
| `sequential`       | 調試、確定性測試         | 按順序循環代理；容易推理               |

### 決策樹

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

## 自動排除您自己的代理程式的故障

1proxy 市場池已經自行自動降級失敗的代理（請參閱[代理品質分數](#proxy-quality-scores)）。對於代理**你**新增至登錄機碼後，背景執行狀況排程器（`src/lib/proxyHealth/scheduler.ts`）提供相同的「自動從鏈中排除失效成員」行為，而不刪除任何內容：

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

它如何融入多代理鏈：

1. 調度程式每個`PROXY_HEALTH_INTERVAL_MS`都會偵測每個已註冊的代理程式（預設 10 分鐘；最少 1 分鐘）。
2. `PROXY_AUTO_REMOVE_AFTER`連續後**確鑿**失敗（真正的連線失敗—逾時或偵測目標自己的 5xx 永遠不會計數，請參閱[代理運行狀況檢查](#proxy-health-checking-v3816)），代理程式的`status`設定為`dead`。
3. `dead`是pool/rotation解析所使用的活動狀態過濾器排除的狀態之一，因此作用域的輪換（循環/隨機/黏性/延遲—請參閱[輪換策略決策樹](#rotation-strategy-decision-tree)）立即停止將該代理移交給新請求。池中的其他代理不會受到影響，整個池永遠不會默默地回退到直接連接—看到[4 級代理系統](#4-level-proxy-system)故障關閉防護。
4. 調度程序以相同的時間間隔不斷探測`dead`代理。下一個成功的探測會將`status`翻轉回`active` ，並重新進入旋轉—無需手動重新添加。

這是故意的**選擇加入且非破壞性**：預設情況下，調度程序僅計算和記錄失敗（請參閱`decision.ts`中的策略 C），並且`PROXY_AUTO_DISABLE`永遠不會刪除行—這就是單獨的、更積極的`PROXY_AUTO_REMOVE`標誌的用途。如果兩者都設定為`true`， `PROXY_AUTO_REMOVE`獲勝（即將刪除的代理程式對於中間的軟禁用沒有用處）。有關完整變數列表，請參閱[環境配置](../reference/ENVIRONMENT.md)參考。

---

> 📖**相關文件：**
>
> - [使用者指南](../guides/USER_GUIDE.md)—常規設定和配置 - [API參考](../reference/API_REFERENCE.md)—完整的API文件 -[環境配置](../reference/ENVIRONMENT.md)—所有環境變量
