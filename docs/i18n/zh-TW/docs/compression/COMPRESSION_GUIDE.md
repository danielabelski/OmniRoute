# 🗜️ Prompt Compression Guide — OmniRoute (中文 (繁體))

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_GUIDE.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_GUIDE.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_GUIDE.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_GUIDE.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_GUIDE.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_GUIDE.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_GUIDE.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_GUIDE.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_GUIDE.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_GUIDE.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_GUIDE.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_GUIDE.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_GUIDE.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_GUIDE.md)

---

> 自動為符合條件的上下文節省 15-95%。如需快速概覽，請參閱 [README 壓縮章節](../README.md#%EF%B8%8F-prompt-compression--save-15-95-eligible-tokens-automatically)。

## 概覽

OmniRoute 實作了一套模組化提示詞壓縮管線，會在請求送達上游提供者之前**主動**執行。這表示系統會以透明方式節省權杖，無須變更您的工作流程。

```
用戶端請求
  → 壓縮策略選擇器
    → 有組合覆寫？→ 使用組合設定
    → 達到自動觸發門檻？→ 使用自動模式
    → 有預設模式？→ 使用全域設定
    → 關閉？→ 略過壓縮
  → 所選壓縮模式
    → 關閉：不壓縮
    → 輕量：安全地清理空白與格式（約 15%）
    → 標準：移除穴居人式贅詞（約 30%）
    → 積極：對歷史記錄進行老化處理與摘要（約 50%）
    → 超高：啟發式修剪與程式碼區塊精簡（約 75%）
    → RTK：辨識命令的終端機／工具輸出篩選（上游範圍 60-90%）
    → 堆疊：依序執行的多引擎管線，通常先執行 RTK，再執行 Caveman（符合條件的範圍為 78-95%）
  → 壓縮後的請求 → 提供者
```

---

## 壓縮模式

### 關閉

不套用壓縮。所有訊息會原封不動地傳遞。

### Lite 模式（約節省 15%，延遲 <1ms）

最安全的模式 — 格式清理。其工具結果截斷功能具有破壞性，因此預設路徑
（沒有 `allow-lossy`、`engine:lite` 或具名組合選擇加入）會以 lite 模式執行，並將
`compressToolResults: false` 設為 false：較早的工具結果會不變地傳送給提供者。

| 技術                     | 說明                                                                       |
| ------------------------ | -------------------------------------------------------------------------- |
| `collapseWhitespace`     | 合併連續的空白行與結尾空格                                                 |
| `dedupSystemPrompt`      | 移除重複的系統訊息                                                         |
| `compressToolResults`    | 將較早的工具結果截斷至 lite 上限（具有破壞性：僅在請求明確選擇加入時使用） |
| `removeRedundantContent` | 移除重複的指示                                                             |
| `replaceImageUrls`       | 縮短 base64 圖片資料 URI                                                   |

**最適合：** 始終啟用的使用情境、安全關鍵工作流程。

### Standard 模式（約節省 30%）

受 [Caveman](https://github.com/JuliusBrussee/caveman) 啟發 — 移除填充詞與冗長措辭，同時保留原意：

- 移除填充詞（「please」、「I think」、「basically」、「actually」）
- 縮減冗長片語（「in order to」→「to」、「as a result of」→「because」）
- 移除禮貌式保留語氣（「Would you mind...」、「If you could possibly...」）
- 30 多條針對程式設計提示調校的正規表示式規則

**最適合：** 日常程式設計工作流程、重視成本的團隊。

### Aggressive 模式（約節省 50%）

適用於長時間工作階段的智慧歷史記錄管理：

- **訊息老化** — 較舊的訊息會逐步壓縮
- **工具結果壓縮** — 較長的工具輸出會被截斷或省略（首尾行、符合行篩選、JSON 索引鍵壓縮）
- **結構完整性防護** — 確保 `tool_use` + `tool_result` 配對保持一致
- **內容視窗感知** — 遵守各模型的 token 限制

**最適合：** 長時間的偵錯工作階段、大型程式碼庫。

### Ultra 模式（約節省 75%）

針對 token 關鍵情境的最大程度壓縮：

- **啟發式修剪** — 依分數修剪文字中的 token
- **結構保留** — 圍欄程式碼區塊、行內程式碼、URL 與識別碼會被標記並逐字重新接合，絕不修剪
- **選用 SLM 層級** — 設定後，小型本機模型可精修修剪結果
- 與 Aggressive 模式獨立：不執行訊息老化、工具結果壓縮或備援摘要器（只有 SLM 層級失敗時，才可能將備援處理路由至 aggressive）

**最適合：** 反覆達到內容限制時。

### RTK 模式（上游範圍 60-90%）

RTK 模式針對程式設計代理工作階段中出現的冗長工具輸出進行最佳化：

- 偵測 `git status`、`git diff`、`git log`、測試執行器、TypeScript/Vite/Webpack 建置、ESLint/Biome/Prettier、npm audit/安裝、Docker 記錄、基礎架構輸出與一般 shell 輸出等命令／輸出類別
- 套用來自 `open-sse/services/compression/engines/rtk/filters/` 的 JSON 篩選器套件
- 從專案或全域 `filters.toml` 檔案匯入 RTK TOML schema v1 篩選器，並進行行內測試驗證與專案檔案的信任閘控
- 隨附 56 個內建篩選器，並提供行內驗證範例
- 移除 ANSI 控制序列、進度列、重複行與不可執行的雜訊
- 保留失敗、錯誤、警告、變更的檔案、摘要與長輸出的尾端
- 支援信任閘控的專案篩選器、全域篩選器，以及選用的已遮蔽原始輸出復原

**最適合：** 包含 shell、建置、測試、git、grep 與檔案輸出記錄的代理工作階段。

### Stacked 模式（符合資格範圍 78-95%）

Stacked 模式會以決定性的順序執行多個壓縮引擎。預設管線為：

```txt
RTK -> Caveman
```

此順序會先壓縮終端機／工具輸出，接著對剩餘的自然語言提示套用 Caveman 語意縮減。
Stacked 管線可全域設定，或透過指派給路由組合的壓縮組合進行設定。

**最適合：** 包含大型工具記錄以及人類指示或助理摘要的混合內容。

## 上游節省量計算

OmniRoute 記錄了來自兩個來源的壓縮節省量：上游專案的基準測試，以及
OmniRoute 自身的引擎組合。

| 來源    | 此處使用的上游 README 數據                                                                         |
| ------- | -------------------------------------------------------------------------------------------------- |
| Caveman | 輸出 token 減少 `~75%`、基準測試平均輸出節省 `65%`、範圍為 `22-87%`，以及輸入壓縮工具可節省 `~46%` |
| RTK     | 命令輸出節省 `60-90%`；範例工作階段從 `~118,000 -> ~23,900` 個 token，亦即節省 `79.7%`（`~80%`）   |

對於重疊的工具／上下文承載資料，預設的 OmniRoute 組合會依序串接引擎：

```txt
RTK -> Caveman
```

組合節省量採乘法計算，而非加法：

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

當 RTK 與 Caveman 都能縮減相同的輸入／上下文承載資料時，才適用 `78-95%` 這個數字。
Caveman 回應輸出模式是獨立的：啟用後，請使用 Caveman 自身的輸出節省量（平均 `65%`、
主打數字 `~75%`、範圍 `22-87%`）。總計費節省量取決於提示詞與輸出的比例。

### 「符合條件」的實際含義

15-95% 這個主打範圍確實存在，但它僅適用於**重複或冗長**的內容——例如重複的
錯誤行、不斷刷出相同警告的建置日誌，或過大的 `grep`／檔案讀取輸出。這
**不**代表每個請求都能節省這麼多。

實證驗證（`tests/unit/compression/stacked-compression-tool-result-savings.test.ts`）：對包含 300 行相同
錯誤訊息的 Anthropic 格式 `tool_result` 區塊執行 `stacked`（RTK + Caveman）流程後，達到
**95.93% token 節省量／96.26% 字元節省量**——完全落在宣傳的範圍內。
但當相同流程處理一般、非重複的工具輸出（乾淨的 `grep` 相符項目清單、
簡短的檔案讀取內容、一般對話文字）時，則會正確地產生**接近零的節省量**，因為
其中沒有可移除的重複內容，而且 `validateCompression()`（`validation.ts`）會拒絕送出
任何會遺失或改動程式碼區塊、URL、標題、版本或全大寫常數識別碼的改寫。

這是符合預期且安全的行為，並非錯誤：即使已完全啟用壓縮，主要讀取／搜尋乾淨檔案的
程式設計工作階段，其總節省量仍會較為有限；而遇到失敗迴圈或輸出冗長之 linter 的
工作階段，則會在該類流量上達到完整的 78-95% 範圍。不要將單一工作階段偏低的
整體節省百分比視為壓縮設定錯誤的證據——請先確認底層工具輸出實際上是否具有重複內容。

---

## Token 節省量視覺化

```
不使用壓縮：       傳送 47K 個 token 至 LLM
使用 Lite：        傳送 40K 個 token        （節省 15%——安全且永遠啟用）
使用 Standard：    傳送 33K 個 token        （節省 30%——caveman-speak 規則）
使用 Aggressive：  傳送 24K 個 token        （節省 50%——老化處理 + 摘要）
使用 Ultra：       傳送 12K 個 token        （節省 75%——啟發式剪枝）
使用 RTK：         傳送 19K-5K 個 token     （命令／工具輸出節省 60-90%）
使用 Stacked：     傳送 10K-2.5K 個 token   （符合條件的 RTK+Caveman 範圍為 78-95%）
```

---

## 設定

### 儀表板

前往 `Dashboard → Context & Cache`：

- **Caveman** — 模式選取、語言套件、預覽與全域預設值
- **RTK** — 命令篩選預覽、RTK 安全性設定與篩選器目錄
- **Compression Combos** — 指派給路由組合的具名引擎管線
- **Auto-Trigger Threshold** — 當 token 數量超過閾值時自動啟用壓縮

### 每個組合的覆寫

在 `Dashboard → Context & Cache → Compression Combos` 中，將壓縮組合指派給路由
組合：

```txt
Combo: "free-tier-fallback"
  Compression Combo: "coding-agent-stack"
  Pipeline: RTK -> Caveman
  Targets:
    1. if/kimi-k2.7-code
    2. if/qwen3.8-max-preview
```

這讓您可以在免費／程式設計提供者上使用堆疊式壓縮，同時在付費訂閱上維持精簡模式。

這個「每個組合的覆寫」指派，與**路由組合壓縮模式**覆寫（Default/Off/Lite/Standard/Aggressive/Ultra/Codex Responses — 欄位的結構描述也接受
`rtk`、`stacked` 和 `omniglyph`）是不同的控制項；後者不會選取具名的壓縮組合管線，而只會設定
`compressionMode` 欄位，由 `resolveCompressionPlan` 參照。此設定可以在組合卡片上設定（`Dashboard → Combos`），或自 #6760 起，在
`Dashboard → Context & Cache → Compression Combos` 的「Assign to routing」清單中，針對每個路由組合設定，就在上方所述的管線指派核取方塊旁邊。兩個介面都會透過相同的
`PUT /api/combos/{id}` 端點保存設定。

### 每個請求的覆寫

傳送 `x-omniroute-compression` 請求標頭，以覆寫單一請求的壓縮計畫。此設定具有最高優先順序 — 它優先於路由組合覆寫、使用中的設定檔、自動觸發與面板 Default。未知值會被忽略（請求永遠不會因此遭拒），而全域主開關仍會控管所有功能：當全域壓縮功能關閉時，標頭無法將其開啟。可用值：

| Value         | Effect                                                                      |
| ------------- | --------------------------------------------------------------------------- |
| `off`         | 此請求不進行壓縮。                                                          |
| `default`     | 由面板衍生的 Default 設定檔（忽略使用中的設定檔）。有損引擎維持關閉。       |
| `safe`        | 與省略標頭相同。                                                            |
| `allow-lossy` | 保留此請求的運算子計畫，包括摘要、相關性篩選器與樣式重寫。                  |
| `engine:<id>` | 啟用時使用單一引擎，例如 `engine:rtk`。這是該引擎的每個請求選擇性啟用方式。 |
| `<combo>`     | 具名組合，優先依名稱（不分大小寫）比對，接著依 id 比對。                    |

若沒有使用 `allow-lossy`、`engine:<id>` 或具名組合，則不會套用有損引擎。當有損的 Default、自動觸發或路由覆寫遭降級時，OmniRoute 會依照已設定的順序，保留已設定堆疊管線中可辨識的無損步驟。只有在沒有任何已設定的無損步驟存留時，才會退回至
`session-dedup → lite`。

設定面板的**Effective pipeline**預覽會顯示一般的靜態計畫。當可執行自動觸發時，同一個預覽也會顯示其條件式有效管線，讓面板與不含標頭的執行階段解析保持一致。

套用的計畫會在 `X-OmniRoute-Compression: <mode>; source=<source>` 回應標頭中回傳，其中 `<source>` 為 `request-header`、`routing-override`、`active-profile`、`auto-trigger`、`default` 或 `off` 之一。

### API

```bash
# 取得壓縮設定
curl http://localhost:20128/api/settings/compression

# 更新壓縮設定
curl -X PUT http://localhost:20128/api/settings/compression \
  -H "Content-Type: application/json" \
  -d '{"defaultMode":"stacked","autoTriggerMode":"stacked","autoTriggerTokens":32000}'

# 預覽特定的 RTK/堆疊式 payload
curl -X POST http://localhost:20128/api/compression/preview \
  -H "Content-Type: application/json" \
  -d '{"mode":"rtk","messages":[{"role":"tool","content":"npm test output here"}]}'

# 列出 RTK 篩選器套件
curl http://localhost:20128/api/context/rtk/filters

# 直接測試 RTK，也可選擇提供命令中繼資料
curl -X POST http://localhost:20128/api/context/rtk/test \
  -H "Content-Type: application/json" \
  -d '{"command":"npm test","text":"FAIL tests/example.test.ts\nError: boom"}'
```

---

## 受保護的內容

壓縮引擎**一律保留：**

- ✅ 程式碼區塊（圍欄式與行內）
- ✅ URL 與檔案路徑
- ✅ JSON 結構與結構化資料
- ✅ 識別碼與受保護的技術權杖
- ✅ 數學運算式
- ✅ 工具／函式呼叫定義
- ✅ 系統提示（在 lite 模式下）

在持久化任何內容之前，RTK 原始輸出復原功能會遮蔽常見的 API 金鑰、bearer 權杖、Slack 權杖、AWS 存取金鑰、
密碼、權杖與密鑰。

---

## 壓縮統計

每個壓縮請求都包含伺服器日誌中的統計資料：

```json
{
  "originalTokens": 47200,
  "compressedTokens": 40120,
  "savingsPercent": 15.0,
  "techniquesUsed": ["collapseWhitespace", "dedupSystemPrompt"],
  "mode": "lite",
  "engine": "caveman",
  "compressionComboId": "coding-agent-stack",
  "durationMs": 0.8,
  "rtkRawOutputPointers": []
}
```

---

## 階段路線圖

| 階段     | 模式                                                                                                                         | 狀態      |
| -------- | ---------------------------------------------------------------------------------------------------------------------------- | --------- |
| Phase 1  | Off, Lite                                                                                                                    | ✅ 已發布 |
| Phase 2  | Standard, Aggressive, Ultra                                                                                                  | ✅ 已發布 |
| Phase 3  | RTK, Stacked, Compression Combos                                                                                             | ✅ 已發布 |
| Phase 4  | Output Styles, SLM-tier Ultra, 評估框架                                                                                      | ✅ 已發布 |
| Phase 4C | 自適應上下文預算（「旋鈕」）— 運算引擎 + API（`PUT /api/settings/compression` 上的 `contextBudget`）+ 儀表板模式／政策控制項 | ✅ 已發布 |

---

## 致謝

Standard 模式的壓縮規則靈感來自 **[JuliusBrussee](https://github.com/JuliusBrussee)** 所開發的 **[Caveman](https://github.com/JuliusBrussee/caveman)**（⭐ 51K+）——這個爆紅專案的理念是「能用較少權杖完成，為何要用很多權杖」。Caveman 報告指出，輸出權杖減少約 `~75%`、基準測試的平均輸出節省量為 `65%`、輸出節省範圍為 `22-87%`，而輸入壓縮工具則可節省約 `~46%`。

RTK 模式的靈感來自 **[RTK AI](https://github.com/rtk-ai)** 所開發的 **[RTK - Rust Token Killer](https://github.com/rtk-ai/rtk)**——這是一個高效能的命令輸出壓縮專案，用於終端機、建置、測試、git 與工具輸出篩選。RTK 報告指出可節省 `60-90%`，其 README 範例工作階段顯示節省了約 `~80%`。

---

## 先進的壓縮系統

除了上述 7 種模式（原始碼也接受`codex-responses`和`omniglyph`模式，本指南未涵蓋）之外，以下部分介紹了在這些模式內部或與這些模式一起工作的功能：工具結果壓縮和漸進老化是積極引擎的步驟`ultra`和 2（積極模式和堆疊管道的`aggressive`步驟），堆疊壓縮管道是`standard`模式的運行方式，快取`aggressive`輸出模式和輸出樣式是選擇加入的系統提示指令，預設關閉，它們塑造模型的輸出而不是壓縮請求。

### 快取感知壓縮

一些提供者（例如帶有提示快取的Anthropic ）支持**提示快取**，這讓他們可以快取部分提示，以降低成本和延遲。啟用快取後，主動壓縮實際上可以**傷害**效能，因為它更改了快取的令牌，使快取失效。

`cachingAware.ts`模組透過以下方式解決了這個問題**檢測快取上下文**和**調整壓縮策略**因此。

#### 它是如何運作的

1. **檢測快取上下文**—掃描請求正文中的`cache_control`標記
2. **識別快取提供者**—檢查目標提供者是否支援快取
3. **調整策略**—將快取提供者`aggressive`/`ultra`降級為`standard`
4. **跳過系統提示**—系統提示通常會被快取，所以不要壓縮它們

策略助理也傳回一個`deterministicOnly`標誌，但計畫建構器僅使用策略—下游今天不會讀取該標誌。

#### 程式碼範例

```ts
import {
  detectCachingContext,
  getCacheAwareStrategy,
} from "@omniroute/open-sse/services/compression/cachingAware";

const body = {
  model: "anthropic/claude-sonnet-4.5",
  messages: [{ role: "user", content: "Hello" }],
  cache_control: { type: "ephemeral" }, // ← Cache marker
};

const ctx = detectCachingContext(body, { provider: "anthropic" });
// → { hasCacheControl: true, provider: "anthropic", targetFormat: null, isCachingProvider: true }

const strategy = getCacheAwareStrategy("aggressive", ctx);
// → { strategy: "standard", skipSystemPrompt: true, deterministicOnly: true }
```

#### 何時使用

快取感知壓縮是**始終開啟**—無需配置。只要壓縮開啟且目標提供者支援提示快取（Anthropic、 OpenAI等），它就會啟動；不需要明確的`cache_control`標記—快取提供者單獨觸發降級，而單獨的標記永遠不會觸發降級（標記偵測提供快取遙測，而不是策略決策）。

OpenRouter僅算是`anthropic/*`模型的快取提供者： Claude程式碼請求保留其`cache_control`斷點（最多 4 個），並且防護措施保護前綴，而其他所有OpenRouter系列（`openai/`、 `google/`、 `qwen/`等）保持剝離且不受防護。

### 漸進式老化

長時間的對話會累積許多訊息輪次，但較舊的輪次變得不那麼相關。 `progressiveAging.ts`模組**根據轉彎距離降低訊息質量**（從對話結束開始測量的距離）。使用附帶的預設值（`verbatim: 2, light: 2, moderate: 3`）：

- **最後 2 回合（距離≤ 2）** : 逐字保留
- **距離3** ：穴居人壓縮（填充物去除）
- **距離 4 +** ：助理訊息匯總；用戶訊息減少到第一行，上限為 120 個字元；其他角色不變。無論距離如何，系統提示、已過期的訊息和最新的用戶訊息始終逐字保留。沒有任何內容被徹底刪除，並且`light`帶無法透過附帶的預設值（`light`等於`verbatim`）存取。

#### 程式碼範例

```ts
import { applyAging } from "@omniroute/open-sse/services/compression/progressiveAging";

const messages = [
  { role: "system", content: "You are a helpful assistant" },
  { role: "user", content: "What is 2+2?" },
  { role: "assistant", content: "4" },
  // ... 50 more turns ...
];

const { messages: aged, saved } = applyAging(messages, {
  verbatim: 3, // last 3 turns: verbatim
  light: 8, // distance <= 8: lite compression
  moderate: 20, // distance <= 20: caveman compression
  fullSummary: 5, // required by the type, not read by the banding code
  // distance > 20: summarized (assistant) / first line kept (user)
});

// saved = number of tokens saved
```

#### 何時使用

漸進式老化是**始終開啟**對於`aggressive`模式—它是`compressAggressive()`的步驟 2。超級模式不運行它。它對於以下方面特別有效：

- 長時間運行的編碼會話
- 多日對話
- 具有許多工具呼叫的代理工作流程

### 穴居人輸出模式

穴居人輸出模式增加**系統提示說明**要求模型本身提供簡潔的輸出— `lite`級別要求保持完整句子的簡潔答案， `full`要求它“像聰明的穴居人一樣回答簡潔”， `ultra`要求電報輸出；說明只是詢問，他們不能保證。請求透過`applyOutputStyles()` (`open-sse/services/compression/outputStyles/apply.ts`) 接收它們： `open-sse/handlers/chatCore.ts`首先使用 back-compat shim ( `open-sse/services/compression/outputStyles/backCompat.ts`中的`resolveOutputStyleSelection()` ) 解析選擇，當`outputStyles`為空時，它將啟用的`cavemanOutputMode`映射到`cavemanOutputMode.intensity`處的`terse-prose`輸出樣式（請參閱下面`cavemanOutputMode.enabled` `autoClarity` `intensity` compat ）； `outputStyles` `outputMode.ts`保存指令文字（`CAVEMAN_INSTRUCTION_BY_LANGUAGE`）、內容旁路和注入使用的放置助手；它自己的`applyCavemanOutputMode()`注入器沒有生產呼叫者。

#### 它是如何運作的

此模式不壓縮輸入。它將指令區塊新增至系統提示字元（請參閱下方的注入如何運作），並且為請求選擇的任何輸入壓縮模式仍然會在現在攜帶該區塊的主體上執行。在每個層級結束的共享邊界子句之前，英語`full`等級如下：

> 「像聰明的穴居人一樣簡潔地回答。刪除文章（a/an/the）、填充物（just/really/basically/actually/simply）、寒暄、對沖。片段OK。簡短的同義詞（大而不廣泛，修復而不實施）。保持所有技術實質、代碼、錯誤、 URLs、標識符準確。」

這尤其適用於：

- 程式碼產生（terser 輸出=更少的標記）
- 快速問答（無需詳細解釋）
- 批次（最大化吞吐量）

#### 何時使用

Caveman輸出模式是**選擇加入**。開啟壓縮（`enabled: true`，壓縮設定頁面上的主開關），使用`cavemanOutputMode.enabled`將其開啟； `intensity`選擇`lite`、 `full`或`ultra`：

```json
{
  "enabled": true,
  "cavemanOutputMode": {
    "enabled": true,
    "intensity": "full"
  }
}
```

壓縮組合**輸出方式**切換（`outputMode`， `outputModeIntensity`中的等級）為組合適用的請求設定相同的開關，並且`omniroute_set_compression_engine` MCP工具透過其布林`outputMode`參數寫入它。非空`outputStyles`選擇優先於此開關。在儀表板中，啟用**簡潔的散文**輸出樣式註入相同的區塊（請參閱下面的輸出樣式）。

### 輸出樣式（目錄）

上面的Caveman輸出模式是**遺留單一樣式路徑**。階段 4 將其概括為可組合輸出樣式的目錄： `OUTPUT_STYLE_CATALOG` in `open-sse/services/compression/outputStyles/catalog.ts`。每種風格都是系統提示指令，要求模型本身提供更便宜的輸出；樣式可以一起啟用並按目錄順序注入。

| 風格                         | `id`            | 它的作用                                                                                                                                                                   | 教學語言                                      |
| ---------------------------- | --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| 簡潔的散文                   | `terse-prose`   | 刪除filler/articles/hedging；保持技術實質準確。與傳統穴居人輸出模式相同的文字（引用，未重新輸入）。                                                                        | en、pt-BR、es、de、fr、it、ru、zh、ja、id、vi |
| 更少的程式碼                 | `less-code`     | YAGNI階梯：最小的工作變化，沒有未請求的抽象。                                                                                                                              | en、pt-BR、es、de、fr、it、ru、zh、ja、id、vi |
| 馬尾辮（懶惰的高級開發人員） | `ponytail`      | 「最好的程式碼是從未寫過的程式碼」：重用>重寫、根本原因>症狀、最短工作差異。                                                                                               | en、pt-BR、es、de、fr、it、ru、zh、ja、id、vi |
| 我有ADHD （行動第一）        | `i-have-adhd`   | 先行動（command/path/snippet在散文之前），編號有界步驟， ONE具體下一步，無preamble/recap/closers.改編自[ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) (MIT)。 | en、pt-BR、es、de、fr、it、ru、zh、ja、id、vi |
| UI防滑過濾器                 | `antislop-ui`   | 每一種視覺技術都必須通過目的測試（層次結構、同一性、可讀性）；沒有預設的gradients/glass/glow、上限調色盤、沒有模板佈局。兩種防傾斜樣式都添加了無死點控制/無製造聲明邊界。  | en、pt-BR、es、de、fr、it、ru、zh、ja、id、vi |
| 防傾斜複製和人工過濾         | `antislop-copy` | 具體的文案（無破折號、通用CTAs、流行語、聊天機器人終結者、發明的事實）加上人員規則： WCAG AA對比、可見焦點、鍵盤範圍、 empty/loading/error狀態、移動回流。                 | en、pt-BR、es、de、fr、it、ru、zh、ja、id、vi |
| 簡潔的CJK （文言）           | `terse-cjk`     | `full`/`ultra`用文言回答； `lite`只要求簡短的回答，不帶虛詞、寒暄或修飾。                                                                                                  | zh（區域設定門控，見下文）                    |

每種樣式都提供三個強度等級— `lite`、 `full`、 `ultra` — ，每個等級都以共享邊界子句（`SHARED_BOUNDARIES` in `outputMode.ts`）結尾，這使程式碼區塊、檔案路徑、命令、錯誤和URLs保持精確。 `terse-prose`和`terse-cjk`等級文字將標識符新增至該清單。

`terse-cjk`在兩個地方被區域設定連接到`zh` 。只有當儀表板UI語言為中文（`zh-CN`或`zh-TW`）時，「壓縮設定」頁面才會列出其行，並且僅當請求解析的語言（請參閱下面的語言選擇）為`zh`時， `applyOutputStyles()`才會注入它。隱藏該行不會清除已儲存的`terse-cjk`選擇：設定API接受任何樣式 ID，並且在頁面上儲存其他樣式會保留它。在請求時， `applyOutputStyles()`語言檢查是唯一的區域設定門。

#### 注射的工作原理

`applyOutputStyles()` (`open-sse/services/compression/outputStyles/apply.ts`) 根據目錄解析選擇（未知 id 和區域設定不匹配的樣式將被刪除，絕不會出現錯誤；解析為無樣式的選擇不會使正文保持不變，作為`no_styles`跳過），按目錄順序連接所選指令，附加邊界子句**一次**（加上安全子句`SAFETY_BOUNDARIES`或其翻譯，當選擇`less-code`或`ponytail` ），並使用單一冪等性標記（`[OmniRoute Output Styles]`）啟動區塊，因此重新應用是無操作的。當解析的語言（請參閱下面的語言選擇）有翻譯時，將注入在地化指令而不是英文。

在具有非空`messages`數組的正文上，冪等性檢查在內容旁路之前運行：當`[OmniRoute Output Styles]`標記已位於頂級`system`字段（字串或內容塊數組）中或包含字串內容的系統消息中時，正文將保持不變，如`already_applied`並且不運行關鍵字檢查。否則，內容旁路（ `open-sse/services/compression/outputMode.ts`中的`shouldBypassCavemanOutputMode()` ）會檢查最後三個訊息的文本，無論它們的作用是什麼，並在該文本與其安全性、 `delete`可逆操作或澄清關鍵字或順序敏感序列匹配時跳過整個回合的樣式： `first`、 `then`、 `after that`、 `before` `drop` `rollback`或`migrate` `backup`後跟`deploy`的`release`個字元內。旁路運轉時**自動清晰度繞過**切換（`cavemanOutputMode.autoClarity`，預設開啟）開啟；關閉該開關會跳過關鍵字檢查。

當旁路允許轉彎時， `placeSystemInstruction()` （同一檔案）永遠不會建立新的`messages[0]`，將該區塊放置在它找到的第一個區塊中：

1. 帶有字串內容的前導系統訊息：該區塊附加在其文字之後。
2. 頂級`system`欄位：此區塊附加在字串文字之後，或作為新文字區塊新增至內容區塊陣列。
3. 第一條帶有字串內容的後續系統訊息：該區塊附加在其文字之後。
4. 以上皆非：該區塊在`messages`末尾進入新的系統訊息。

在沒有`messages`數組（或空數組）的主體上，不會運行任何內容旁路，並且不會參考頂級`system`字段。該區塊將附加在字串`instructions`欄位的文字之後，除非該欄位已包含`[OmniRoute Output Styles]`標記，在這種情況下，正文將保持不變，如`already_applied`。當主體沒有字串`instructions`欄位但包含`input` （字串或陣列）時，該區塊將變為`instructions`，取代該欄位保存的任何非字串值。既沒有字串`instructions`欄位也沒有字串或陣列`input`的主體保持不變並作為`no_messages`跳過。

#### 如何啟用

在儀表板中：**壓縮上下文→壓縮設定**(`/dashboard/context/settings`)，輸出樣式部分：每個樣式一行，帶有on/off切換器和等級選擇器。樣式在壓縮本身開啟時注入（頁面的主切換， `enabled`）。這**自動清晰度繞過**切換開關位於**穴居人**頁 (`/dashboard/context/caveman`)，在其**輸出方式**卡片。以程式設計方式，壓縮配置將選擇保留為：

```json
{
  "outputStyles": [
    { "id": "i-have-adhd", "level": "full" },
    { "id": "less-code", "level": "lite" }
  ]
}
```

向後相容：當`outputStyles`為空時，舊的`cavemanOutputMode.enabled`設定映射到`cavemanOutputMode.intensity`處的`terse-prose` 。然後該區塊以`[OmniRoute Output Styles]`標記開始，舊的`applyCavemanOutputMode()`注入器在其中寫入`[OmniRoute Caveman Output Mode]`。在標記下方，文字與 en、pt-BR、es、de、fr、it、ru、id 和 vi 中的遺留注入相匹配；在 ja 和 zh 中，它在邊界子句之前帶有一個額外的空格。 `terse-prose`翻譯為 pt-BR、es、de、fr、it、ru、zh、ja、id 和 vi，因此解析語言為`hu`的請求將獲取舊注入器使用匈牙利語文本的英語文本。

輸出樣式語言選擇（`resolveOutputStyleLanguage()` in `outputStyles/apply.ts`）：啟用`languageConfig.enabled`時， `autoDetect`對請求的`messages`陣列中包含文字（字串內容或其內容部分的`text` ）的最新使用者訊息進行取樣，並在其上執行 Caveman 引擎的偵測器 (`detectCompressionLanguage()`)。對於包含漢字且不含假名的文本，檢測器返回`zh` ；否則，它將返回`it`、 `pt-BR`、 `es`、 `de`、 `fr`、 `ru`、 `ja`、 `hu`和`id`中具有最多提示匹配的一個，而`en`當沒有匹配的— ， `vi` `defaultLanguage`不會被檢測到，儘管樣式附帶`vi`文字。回應API主體保持在`input`中，它沒有被取樣，所以它得到`defaultLanguage`，然後是英文。當`messages`中沒有使用者訊息包含文字或`autoDetect`關閉時，先套用`defaultLanguage` ，然後套用英文。 `languageConfig.enabled`關閉時，語言為英語—除非壓縮組合應用於請求（分配給請求的路由組合的組合，或預設壓縮組合chatCore回退到內建堆疊管道）：應用組合將為該請求打開`languageConfig.enabled`並從組合的語言包設定`defaultLanguage` （如果它是組合的包之一，則保存的值，預設組合的第一個預設值，否則仍然適用的預設`autoDetect`的`en`組合。 Caveman 輸入引擎為每個文字部分選擇不同的規則包語言— ，並且在自動偵測關閉的情況下，在`enabledPacks`上進行門控。

樣式×語言矩陣由`tests/unit/compression/output-styles-i18n-matrix.test.ts`固定：每個目錄樣式都需要測試的`BASELINE_LANGUAGES`中的一個條目；非語言環境門控的樣式必須提供 pt-BR 翻譯（語言環境門控`terse-cjk`不受此規則約束），除非它列在`KNOWN_ENGLISH_ONLY`中，它可能只包含根本沒有翻譯的樣式—列出的具有任何測試的`BASELINE_LANGUAGES`通過測試；若要新增樣式，請參閱[EXTENDING_COMPRESSION.md](./EXTENDING_COMPRESSION.md#adding-an-output-style) 。

### 工具結果壓縮

`open-sse/services/compression/toolResultCompressor.ts`中的`compressToolResult()`壓縮工具結果文本**5個策略**。它按此順序嘗試它們，並且檢查與內容相符的第一個啟用的策略決定結果：

1. **`fileContent`**: content of 3 or more lines in which at least one line, ignoring leading indentation, starts with `import `, `export `, `function `, `class `, `const `, `let `, `var ` or `return ` (the keyword plus a space), or with `if`, `for` or `while` followed by `(` or ` (`, keeps its first 20 and last 5 lines, with the elided middle marked.
2. **`grepSearch`** ：至少有一行`<path>:<digits>:`形式的內容，其中第一個冒號之前的文字沒有空格，僅保留這些行，最多 30 行，後跟任何進一步匹配的計數和匹配文件的列表；其他所有行都會被刪除。這樣的一行足以觸發該策略，因此以`12:30:45`等時間戳記開頭的日誌行也算在內。
3. **`shellOutput`** ：包含ANSI CSI序列（`ESC[`然後數字或分號然後字母，如顏色代碼）或`$`後跟文本中任何位置的空格的輸出將丟失這些序列（保留其他轉義符，例如`ESC[?25l`或OSC窗口標題序列）並保留最後 50 行，連續重複的行折疊。因為此檢查在`json`和`errorMessage`之前運行，所以當`shellOutput`打開時，包含此類`$`的JSON或錯誤輸出永遠不會到達它們。
4. **`json`** ：以`{`或`[`開頭（可選空格之後）並解析的超過 2,000 個字元的JSON負載被總結為：超過 7 個項目的數組保留其前 5 個和最後 2 個項目及其總數，對象保留其前 20 個鍵，每個嵌套對像或數組值替換為`_remaining_<N>_keys`鍵標（對於計數組，Nq 對數字） `{…N keys}`數字值被整個複製，因此 20 個或更少的鍵且沒有嵌套值的物件只會重新縮排—一個縮小的物件會獲得字元並保持不變。
5. **`errorMessage`** ：在任何位置和任何字母大小寫下包含`error:`、 `error ` （後面跟著一個空格的單詞，如`no error found`）、 `[error]`、 `exception:`、 `exception `、 `[exception]`或`traceback`的輸出保留其第一行、接下來的 10 行和最後 3 行，並用zqj的輸出保留其第一行、接下來的 10 行和最後 3 行，並用`… [N frames elided] …`標記代替它們之間的行。只有當第一行後面有超過 13 行時，標記才會出現，因此 14 行或更少的錯誤輸出不會縮短（在 12 或 13 行時，最後 3 行重複行已經保留）。

一個策略匹配後，即使是沒有保存任何內容的策略，後面的策略也不會被嘗試。當匹配策略未保存估計標記（長度÷ 4，向上舍入） — ，例如 25 行或更少的類似代碼的文件，或包含 7 個或更少—超過 2,000 個字元的JSON數組，激進引擎將保留原始`compressToolResult()`結果：當`compressAggressive()`為`saved`或`compressAnthropicToolResultBlock()`工具結果步驟並不是最終結論：引擎的後備摘要器仍然可以縮短長度超過 8,192 個字元的`tool`或`function`訊息（`maxTokensPerMessage`， 2,048，乘以 4）。

#### 何時使用

工具結果壓縮是積極引擎（`compressAggressive()` in `open-sse/services/compression/aggressive.ts`）的第一步，因此它在積極模式和堆疊管道的`aggressive`步驟中運作。它壓縮 OpenAI 形狀的`tool`和`function`訊息以及Anthropic `tool_result`區塊內的文字。每個策略在`aggressive.toolStrategies`下都有自己的開關，預設全部開啟。在儀表板中，開關位於 Caveman 頁面的**先進的**壓縮開啟時的視圖，預設模式為「積極」。

### 堆疊式管道

堆疊模式運行**多個引擎按順序排列**—通常先RTK （工具輸出節省 60-90%），然後 Caveman 處理剩餘文字（~節省 46% 輸入）。組成的，就是**78-95% 合格範圍**（請參閱上面的上游儲蓄數學）： `1 - (1 - 0.60..0.90) × (1 - 0.46)`平均≈ 89%。

#### 它是如何運作的

```
Input (1000 tokens)
  → RTK (command-aware filter) → 200 tokens
    → Caveman (filler removal) → 108 tokens
  → Output (108 tokens, ~89% savings)
```

#### 何時使用

使用堆疊模式用於：

- 工具密集型工作流程（代理編碼、研究）
- 成本敏感的批次
- 當您需要最大限度地節省代幣時

堆疊管道是透過全域`stackedPipeline`壓縮設定或透過指派給路由組合的命名壓縮組合（請參閱上面的每個組合覆蓋） —進行配置，而不是透過自動組合`modePack` （此欄位僅重新權重自動組合模型選擇，且`stacked`不是有效的套件名稱）。

---

## 壓縮組合覆寫

您可以針對**每個組合**覆寫全域壓縮模式，以針對不同使用情境微調行為：

```json
{
  "id": "coding-combo",
  "strategy": "priority",
  "config": {
    "weights": { "taskFit": 0.5 },
    "modePack": "quality-first"
  },
  "compressionOverride": "aggressive"
}
```

這適用於：

- **程式設計組合**：長時間工作階段使用 `aggressive` 模式
- **快速問答組合**：使用 `lite` 模式以快速回應
- **大量使用工具的組合**：使用 `stacked` 模式以最大化節省效果
- **正式環境組合**：對快取提供者停用覆寫——持續啟用的快取感知調整會自動將 `aggressive`/`ultra` 降級為 `standard`（沒有可選取的 `cache-aware` 模式）

---

## 另請參閱

- [環境設定](../reference/ENVIRONMENT.md) — 壓縮環境變數
- [架構指南](../architecture/ARCHITECTURE.md) — 壓縮管線內部機制
- [使用者指南](../guides/USER_GUIDE.md) — 開始使用壓縮
- [RTK 壓縮](./RTK_COMPRESSION.md) — RTK 篩選器、信任模型、驗證閘門、原始輸出復原
- [壓縮引擎](./COMPRESSION_ENGINES.md) — Caveman、RTK、stacked、API、MCP、儀表板
- [壓縮規則格式](./COMPRESSION_RULES_FORMAT.md) — JSON 規則套件格式
- [壓縮語言套件](./COMPRESSION_LANGUAGE_PACKS.md) — 特定語言的 Caveman 規則
