# 🌐 OmniRoute Proxy Guide (Filipino)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **I-bypass ang mga heograpikong bloke, protektahan ang iyong pagkakakilanlan, at iruta ang trapiko AI sa anumang proxy — na walang kumplikadong configuration.**

Kasama sa OmniRoute ang isang buong tampok na sistema ng pamamahala ng proxy na nagbibigay-daan sa iyong iruta ang upstream na trapiko ng provider ng AI sa pamamagitan ng HTTP, HTTPS, o SOCKS5 na mga proxy. Kung ikaw ay nasa isang naka-block na rehiyon, kailangan ng IP rotation, o gusto ng stealth fingerprinting — sinasaklaw ng gabay na ito ang lahat.

---

## Talaan ng mga Nilalaman

- [Bakit Gumamit ng mga Proxies?](#why-use-proxies)
- [Pangkalahatang-ideya ng Arkitektura](#architecture-overview)
- [4-Antas na Proxy System](#4-level-proxy-system)
- [Proxy Registry (CRUD)](#proxy-registry-crud)
- [1proxy na Libreng Marketplace](#1proxy-free-proxy-marketplace)
- [Pag-ikot ng Proxy](#proxy-rotation)
- [Anti-Detection at Stealth](#anti-detection--stealth)
- [Upstream Proxy Mode](#upstream-proxy-modes)
- [Dashboard UI](#dashboard-ui)
- [API Sanggunian](#api-reference)
- [Mga variable ng kapaligiran](#environment-variables)
- [Pag-troubleshoot](#troubleshooting)

---

## Bakit Gumamit ng mga Proxies?

Pinaghihigpitan ng maraming provider AI ang pag-access ayon sa heyograpikong rehiyon. Mga developer sa** Russia, China, Iran, Cuba, Turkey** , at iba pang mga bansa ay nakakaranas ng mga error tulad ng:

```
unsupported_country_region_territory
```

Kahit sa labas ng mga naka-block na rehiyon, ang mga proxy ay kapaki-pakinabang para sa:

| Use Case                 | Paglalarawan                                                                        |
| ------------------------ | ----------------------------------------------------------------------------------- |
| **Geographic na bypass** | I-access OpenAI, Anthropic, Codex, Copilot mula sa mga naka-block na bansa          |
| **pag-ikot ng IP**       | Ipamahagi ang mga kahilingan sa maraming IPs upang maiwasan ang paglilimita sa rate |
| **Pagkapribado**         | Itago ang iyong tunay IP mula sa mga upstream provider                              |
| **Pagsunod**             | I-ruta ang trapiko sa pamamagitan ng mga partikular na hurisdiksyon                 |
| **Pagsubok**             | Gayahin ang mga kahilingan mula sa iba't ibang rehiyon                              |

---

## Pangkalahatang-ideya ng Arkitektura

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

### Mga Pangunahing Bahagi

| Component               | file                                         | Tungkulin                                                         |
| ----------------------- | -------------------------------------------- | ----------------------------------------------------------------- |
| **Proxy Registry**      | `src/lib/db/proxies.ts`                      | CRUD para sa mga proxy na entry mga takdang-aralin sa saklaw ng + |
| **Proxy Dispatcher**    | `open-sse/utils/proxyDispatcher.ts`          | Lumilikha ng `undici` ProxyAgent/SOCKS dispatcher na may caching  |
| **Proxy Fetch**         | `open-sse/utils/proxyFetch.ts`               | Binabalot `fetch()` gamit ang proxy dispatcher injection          |
| **Mga Setting ng Ruta** | `src/app/api/settings/proxy/route.ts`        | Legacy proxy config API (GET/PUT/DELETE)                          |
| **Ruta ng Pamamahala**  | `src/app/api/v1/management/proxies/route.ts` | Registry CRUD API (GET/POST/PATCH/DELETE)                         |
| **1proxy DB**           | `src/lib/db/oneproxy.ts`                     | Libreng proxy marketplace na pagtitiyaga                          |

---

## Default na estado ng proxy para sa mga bagong account

Sa** Mga setting → Proxy → Global configuration** , gamitin** Paganahin ang proxy bilang default para sa mga bagong koneksyon** upang piliin ang paunang proxy na estado ng mga bagong idinagdag na provider account.

Kinokontrol ng bagong setting ang paunang estado ng proxy ng mga bagong idinagdag na provider account. Hindi nito binabago ang mga kasalukuyang account o pinapalitan ang pandaigdigang proxy switch. Pinapanatili ng paunang halaga nito ang dating gawi. I-off ito nang isang beses para gumawa ng mga account sa hinaharap na may naka-disable na proxy bilang default.

Ang kagustuhan ay nakaimbak bilang `defaultNewConnectionProxyEnabled` sa pamamagitan ng umiiral na Mga Setting API. Nagde-default ito sa `true` kapag hindi na-save. Magkakabisa ang pag-save `false` para sa mga kasunod na bagong account nang hindi nagre-restart. tumatanggap `POST /api/providers` ng opsyonal na mahigpit na boolean `proxyEnabled`; inuuna ang tahasang `true` o `false` kaysa sa default ng paggawa. Ang pagtanggal sa isang duplicate na account o OAuth reconnect ay nagpapanatili sa nakaimbak na estado ng account na iyon. Maaari pa ring i-enable o i-disable ang mga indibidwal na account pagkatapos.

Ginagamit ng mga piling paglilipat ng provider ang default ng pag-install ng patutunguhan para sa mga bagong account at pinapanatili ang patakaran sa patutunguhan kapag pinapalitan ang mga kasalukuyang account. Ang mga proxy toggle ay hindi mga portable transfer field. Ang buong backup na pagpapanumbalik at makasaysayang JSON/SQL migration ay nagpapanatili ng kanilang mga umiiral na semantika ng pagpapanumbalik, kabilang ang mga naka-save na halaga ng account at mga default na legacy na schema; ang isang kumpletong pag-restore ng mga setting ay maaari ding ibalik ang kagustuhang ito.

Ang kagustuhang ito ay hindi nagtatalaga ng proxy o nagtatatag na ang isa ay malusog o ginagamit. Ang aktwal na pagruruta ay nakadepende pa rin sa pandaigdigang proxy switch at naaangkop na proxy configuration. Ang mga sintetikong provider na walang paulit-ulit na account, trapiko OAuth bago ang paggawa ng account, mga proxy environment/system, at networking ng mga panlabas na backend ay wala sa saklaw nito.

## 4-Antas na Proxy System

Sinusuportahan OmniRoute ang proxy configuration sa** apat na malayang saklaw** , nalutas sa priority order:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Paano Gumagana ang Resolusyon

Kapag nagpadala OmniRoute ng kahilingan sa isang upstream provider, tatawagan nito `resolveProxyForConnectionFromRegistry()` na sumusuri sa bawat antas sa pagkakasunud-sunod:

1. **Antas ng account** — Mayroon bang proxy na nakatalaga sa partikular na koneksyong ito ID?
2. **Antas ng provider** — Mayroon bang proxy na nakatalaga sa provider na ito (hal., `openai`)?
3. **Global-level** — Mayroon bang pandaigdigang proxy na na-configure?
4. **Walang proxy** — Direktang koneksyon sa provider.

Panalo ang unang laban. Nangangahulugan ito na maaari kang magtakda ng isang pandaigdigang proxy bilang isang fallback ngunit i-override ito para sa mga partikular na provider o koneksyon.

### Ano ang Nai-proxy

| Uri ng Trapiko            | Proxied? | Mga Tala                                                  |
| ------------------------- | -------- | --------------------------------------------------------- |
| Mga pagkumpleto ng chat   | ✅       | Lahat ng hiling `/v1/chat/completions`                    |
| Mga pag-embed             | ✅       | `/v1/embeddings`                                          |
| Pagbuo ng imahe           | ✅       | `/v1/images/generations`                                  |
| Audio (TTS/STT)           | ✅       | `/v1/audio/*`                                             |
| OAuth token exchange      | ✅       | Lutasin `unsupported_country_region_territory`            |
| Mga pagsubok sa koneksyon | ✅       | Gumagamit ng proxy ang button na "Subukan ang Koneksyon." |
| Pag-refresh ng token      | ✅       | Background OAuth renewal                                  |
| Pag-sync ng modelo        | ✅       | Listahan ng modelo at pagtuklas                           |

---

## Proxy Registry (CRUD)

Ang proxy registry ay isang SQLite table (`proxy_registry`) na nag-iimbak ng lahat ng iyong mga proxy. Ang bawat proxy ay may:

| Patlang    | Uri     | Paglalarawan                            |
| ---------- | ------- | --------------------------------------- |
| `id`       | UUID    | Natatanging identifier                  |
| `name`     | String  | Label na nababasa ng tao                |
| `type`     | String  | Protocol: `http`, `https`, `socks5`     |
| `host`     | String  | Proxy hostname o IP                     |
| `port`     | Integer | Numero ng port                          |
| `username` | String  | Awth username (naka-encrypt sa pahinga) |
| `password` | String  | Awth password (naka-encrypt sa pahinga) |
| `region`   | String  | Label ng heyograpikong rehiyon          |
| `notes`    | String  | Libreng-text na mga tala                |
| `status`   | String  | `active` o `inactive`                   |
| `source`   | String  | `manual` o `oneproxy`                   |

### Paglikha ng isang Proxy

**Sa pamamagitan ng Dashboard:**

1. Pumunta sa** Mga Setting → Proxy**
2. I-click** Magdagdag ng Proxy**
3. Punan ang uri, host, port, at mga opsyonal na kredensyal sa pagpapatotoo
4. I-save

**Sa pamamagitan API:**

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

### Pag-update ng isang Proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Tandaan:** Pinapanatili ang mga kredensyal maliban kung tahasan kang magpapadala ng mga walang laman na kapalit. Ang pagpapadala ng mga walang laman na string para sa `username`/`password` ay magpapanatili sa mga nakaimbak na halaga.

### Pagtanggal ng Proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Listahan ng mga Proxies

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Pagtatalaga ng mga Proxies sa Saklaw

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

### Paglutas ng Epektibong Proxy

Suriin kung aling proxy ang gagamitin para sa isang naibigay na koneksyon:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Ibinabalik ang naresolbang proxy kasama ang antas nito (`account`, `provider`, o `global`) at pinagmulan.

### Maramihang Pagtatalaga

Magtalaga ng isang proxy sa maraming provider o koneksyon nang sabay-sabay:

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

Ang mga proxy ay kasama sa**Backup/Restore** sistema. Kapag na-export mo ang iyong configuration OmniRoute :

1. Pumunta sa** Dashboard → Mga Setting → Backup**
2. I-click** I-export** — proxy registry at mga takdang-aralin ay kasama
3. Para i-restore, i-click** Mag-import** at i-upload ang backup file

Sinusuportahan din ng proxy registry** upsert ng host + port** — kung nag-import ka ng proxy na mayroon na (parehong host at port), mag-a-update ito sa halip na gumawa ng duplicate.

### Legacy Migration

Kung nag-configure ka ng mga proxy sa mas lumang bersyon (pre-registry), awtomatikong inililipat ng OmniRoute ang mga ito:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Nangyayari ito nang isang beses sa unang pagsisimula pagkatapos ng pag-upgrade. Gamitin `migrateLegacyProxyConfigToRegistry({ force: true })` upang muling tumakbo.

---

## 1proxy Libreng Proxy Marketplace

> 🆕** Iniambag ni [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Isyu [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integrates sa** [1proxy](https://1proxy-api.aitradepulse.com)** platform ng komunidad upang magbigay ng access sa** daan-daang libre, napatunayang proxy** mula sa buong mundo. Ito ay perpekto para sa mga user na walang sariling proxy infrastructure.

### Paano Ito Gumagana

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **I-sync** Kinukuha ng — OmniRoute ang mga validated na proxy mula sa 1proxy API
2. **Tindahan** — Proxies ay naka-save sa parehong `proxy_registry` table na may `source = 'oneproxy'`
3. **Salain** — I-filter ayon sa protocol, bansa, marka ng kalidad
4. **Iikot** — Piliin ang pinakamahusay na proxy gamit ang kalidad, random, o sunud-sunod na mga diskarte
5. **Auto-degrade** — Binabawasan ng mga nabigong proxy ang kanilang marka ng kalidad; sa ibaba ng threshold → ay minarkahan na hindi aktibo

### Sini-sync ang mga Proxies

**Sa pamamagitan ng Dashboard:**

1. Pumunta sa** Mga setting → 1proxy** tab
2. I-click** "I-sync Ngayon"**
3. Tingnan ang mga istatistika: kabuuang mga proxy, aktibong bilang, average na kalidad, breakdown ayon sa bansa

**Sa pamamagitan API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Pag-filter ng mga Proxies

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

### Mga Marka ng Kalidad ng Proxy

Ang bawat 1proxy proxy ay may metadata:

| Patlang         | Paglalarawan                                     |
| --------------- | ------------------------------------------------ |
| `qualityScore`  | 0-100 rating mula sa 1proxy validation           |
| `latencyMs`     | Sinusukat ang latency ng network                 |
| `anonymity`     | `transparent`, `anonymous`, o `elite`            |
| `googleAccess`  | Kung maa-access ng proxy ang mga serbisyo Google |
| `countryCode`   | Dalawang titik ISO country code                  |
| `lastValidated` | Timestamp ng huling pagpapatunay                 |

Ang mga marka ng kalidad ay dynamic na inaayos:

- **Mga nabigong kahilingan** bawasan ang iskor ng 10 puntos
- **Bumaba ang marka sa ≤ 10** → proxy ay may markang `inactive`
- Ang mga hindi aktibong proxy ay hindi kasama sa pag-ikot

### Mga Istratehiya sa Pag-ikot

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

### Circuit Breaker

Ang 1proxy sync ay may built-in na circuit breaker:

- Pagkatapos** 5 magkakasunod na pagkabigo sa pag-sync** , ang mga karagdagang pagtatangka sa pag-sync ay hinarangan
- I-reset gamit ang: `resetOneproxyCircuitBreaker()` o i-restart ang server
- Available ang status ng pag-sync sa `GET /api/settings/oneproxy?action=status`

### Pag-clear ng 1proxy Proxies

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-Detection at Stealth

OmniRoute ay hindi lamang nagruruta ng trapiko sa pamamagitan ng isang proxy — ginagawa nitong lehitimo ang trapiko:

### TLS Fingerprint Spoofing

Gumagamit `wreq-js` upang makabuo ng mga TLS na fingerprint na tulad ng browser, na nilalampasan ang mga system ng pag-detect ng bot na nag-flag ng mga non-browser TLS handshake.

### CLI Pagtutugma ng Fingerprint

Ang**CLI Fingerprint Toggle** (`Settings → Security`) muling inaayos ang mga HTTP header at JSON body field upang tumugma sa eksaktong lagda ng mga native CLI binary (Claude Code, Codex, atbp.). Gumagana ito** sa ibabaw ng** ang proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Makukuha mo pareho**IP masking** at** humiling ng pagiging tunay** sabay-sabay.

### Proxy IP Pagpapanatili

Ipinapakita ng mga color-coded na badge sa dashboard kung aling antas ng proxy ang aktibo:

| Badge | Antas     | Ibig sabihin                                                   |
| ----- | --------- | -------------------------------------------------------------- |
| 🟢    | Global    | Ang lahat ng trapiko ay dumadaan sa proxy na ito               |
| 🟡    | Provider  | Ang trapiko lang ng provider na ito ang na-proxy               |
| 🔵    | Koneksyon | Ginagamit ng partikular na key/account na ito ang proxy na ito |

Ipinapakita rin ng badge ang nalutas na proxy IP para sa pag-verify.

---

## Upstream Proxy Mode

Para sa mga provider na gumagamit ng CLIProxyAPI pattern, sinusuportahan ng OmniRoute ang tatlong upstream proxy mode:

| Mode          | Paglalarawan                                                        |
| ------------- | ------------------------------------------------------------------- |
| `native`      | Direktang pinangangasiwaan ng OmniRoute ang proxy routing (default) |
| `cliproxyapi` | Nagde-delegate sa isang external CLIProxyAPI instance               |
| `fallback`    | Sinubukan muna ang native, bumabalik sa CLIProxyAPI                 |

I-configure ang bawat provider:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Dashboard UI

### Mga Setting → Proxy Tab

- **Global proxy** configuration (itakda nang isang beses para sa lahat ng trapiko)
- **Proxy ng bawat provider** overrides
- **Proxy sa bawat koneksyon** mga takdang-aralin
- **Pagsubok sa koneksyon** sa pamamagitan ng naka-configure na proxy
- **Mga badge na may kulay** nagpapakita ng aktibong antas ng proxy

### Mga Setting → 1proxy Tab

- **I-sync Ngayon** button para kumuha ng mga libreng proxy
- **Mga kard ng istatistika** : Kabuuan, Aktibo, Avg na Kalidad, Huling Pag-sync
- **Mga filter** : Protocol, Code ng Bansa, Min na Kalidad
- **Proxy table** may host, protocol, bansa, marka ng kalidad, latency, anonymity, Google access
- **Katayuan ng pag-sync** panel na may pagsubaybay success/failure at magkakasunod na bilang ng pagkabigo
- **I-clear ang Lahat** para tanggalin lahat ng 1proxy na entry

---

## API Sanggunian

### API Setting ng Proxy

| Pamamaraan | Endpoint                                       | Paglalarawan                    |
| ---------- | ---------------------------------------------- | ------------------------------- |
| `GET`      | `/api/settings/proxy`                          | Kunin ang buong proxy config    |
| `GET`      | `/api/settings/proxy?level=global`             | Kumuha ng pandaigdigang proxy   |
| `GET`      | `/api/settings/proxy?level=provider&id=openai` | Kumuha ng proxy ng provider     |
| `GET`      | `/api/settings/proxy?resolve=connectionId`     | Resolbahin ang epektibong proxy |
| `PUT`      | `/api/settings/proxy`                          | I-update ang proxy config       |
| `DELETE`   | `/api/settings/proxy?level=provider&id=openai` | Alisin ang proxy sa antas       |

### Ang Proxy Registry API

| Pamamaraan | Endpoint                                          | Paglalarawan                          |
| ---------- | ------------------------------------------------- | ------------------------------------- |
| `GET`      | `/api/v1/management/proxies`                      | Ilista ang lahat ng mga proxy         |
| `GET`      | `/api/v1/management/proxies?id=uuid`              | Kumuha ng proxy sa pamamagitan ng ID  |
| `GET`      | `/api/v1/management/proxies?id=uuid&where_used=1` | Kumuha ng mga proxy assignment        |
| `POST`     | `/api/v1/management/proxies`                      | Gumawa ng proxy                       |
| `PATCH`    | `/api/v1/management/proxies`                      | I-update ang proxy                    |
| `DELETE`   | `/api/v1/management/proxies?id=uuid`              | Tanggalin ang proxy                   |
| `DELETE`   | `/api/v1/management/proxies?id=uuid&force=1`      | Sapilitang tanggalin                  |
| `POST`     | `/api/v1/management/proxies/bulk-assign`          | Bultuhang italaga                     |
| `GET`      | `/api/v1/management/proxies/assignments`          | Maglista ng mga takdang-aralin        |
| `GET`      | `/api/v1/management/proxies/health`               | Mga istatistika ng kalusugan ng proxy |

### Tunnels API

Para sa paglalantad ng iyong OmniRoute instance sa pampublikong internet (Cloudflare/ngrok/Tailscale) sa halip na iruta ang palabas sa pamamagitan ng proxy, tingnan [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Ang tunnel REST API ay nakatira sa ilalim ng `/api/tunnels/{cloudflared,ngrok,tailscale}/*` at orthogonal sa outbound proxy chain na nakadokumento sa itaas.

### 1proxy API

| Pamamaraan | Endpoint                               | Paglalarawan                          |
| ---------- | -------------------------------------- | ------------------------------------- |
| `GET`      | `/api/settings/oneproxy`               | Maglista ng 1proxy na mga proxy       |
| `GET`      | `/api/settings/oneproxy?action=stats`  | Kunin ang stats + sync status         |
| `GET`      | `/api/settings/oneproxy?action=status` | Kunin ang katayuan ng pag-sync lamang |
| `POST`     | `/api/settings/oneproxy`               | I-trigger ang pag-sync                |
| `POST`     | `/api/settings/oneproxy/rotate`        | I-rotate sa susunod na proxy          |
| `DELETE`   | `/api/settings/oneproxy?id=uuid`       | Tanggalin ang isa                     |
| `DELETE`   | `/api/settings/oneproxy?clearAll=1`    | I-clear lahat                         |

### Upstream Proxy API

| Pamamaraan | Endpoint                          | Paglalarawan                     |
| ---------- | --------------------------------- | -------------------------------- |
| `GET`      | `/api/upstream-proxy/:providerId` | Kumuha ng upstream proxy config  |
| `PUT`      | `/api/upstream-proxy/:providerId` | Itakda ang upstream proxy mode   |
| `DELETE`   | `/api/upstream-proxy/:providerId` | Alisin ang upstream proxy config |

---

## Mga variable ng kapaligiran

| Variable              | Default | Paglalarawan                                                          |
| --------------------- | ------- | --------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`  | Paganahin ang suporta SOCKS5 proxy (default `true` sa `.env.example`) |

---

## Pag-troubleshoot

### " naka-disable SOCKS5 proxy"

Itakda ang `ENABLE_SOCKS5_PROXY=true` sa iyong `.env` file at i-restart.

### Mga error sa "socket hang up" sa pamamagitan ng proxy

Normal ito sa mga murang proxy na nag-aalis ng mga idle na koneksyon. Hinahawakan na ito OmniRoute sa pamamagitan ng:

- Hindi pagpapagana ng keep-alive sa mga proxy na koneksyon (`keepAliveTimeout: 1`)
- Hindi pagpapagana ng pipelining (`pipelining: 0`)
- I-cache ang mga dispatcher upang maiwasan ang paulit-ulit na pakikipagkamay

Kung magpapatuloy ito, sumubok ng ibang proxy o gamitin ang feature na 1proxy rotation.

### "unsupported_country_region_territory" sa panahon OAuth

Tiyaking naka-configure ang proxy** dati** simulan ang daloy ng OAuth. ruta OmniRoute OAuth token exchange sa pamamagitan ng naka-configure na proxy. Magtakda muna ng pandaigdigang o provider-level na proxy, pagkatapos ay kumonekta.

### Hindi ginagamit ang proxy

Suriin ang pagkakasunud-sunod ng resolusyon:

1. I-verify gamit ang `GET /api/settings/proxy?resolve=your-connection-id`
2. Suriin kung ang proxy `status` ay `active` (hindi `inactive`)
3. Tiyaking tumutugma ang saklaw ng pagtatalaga ng proxy sa iyong koneksyon

### Nabigo ang 1proxy sync

Suriin ang katayuan ng pag-sync:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Kung `consecutiveFailures >= 5`, ang circuit breaker ay nabadtrip. I-restart ang server upang i-reset, o maghintay para sa manu-manong pag-reset.

---

## Schema ng Database

### `proxy_registry` Talahanayan

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

### `proxy_assignments` Talahanayan

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

## Proxy Health Checking (v3.8.16 +)

OmniRoute** mabilis na nabigo ang proxy** mekanismo (`src/lib/proxyHealth.ts`) nakakakita ng mga patay na proxy sa < 2s sa pamamagitan ng isang mabilis TCP connection check, pagkatapos** ini-cache ang resulta** upang maiwasan ang overhead sa bawat kahilingan.

### Paano Ito Gumagana

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

Kung wala ito, haharangin ng isang patay na proxy ang bawat kahilingan para sa buong `PROXY_TIMEOUT_MS` (default na 30s) bago mabigo.

### Natutunaw na Mga Variable sa Kapaligiran

| Variable                     | Default | Layunin                                                  |
| ---------------------------- | ------- | -------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | timeout ng koneksyon TCP sa bawat pagsusuri sa kalusugan |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | Gaano katagal naka-cache ang isang resulta sa kalusugan  |

**Mga inirerekomendang halaga:**

| Sitwasyon                   | Mabilis na nabigo ang timeout | I-cache TTL | Pangangatwiran                                                                                                     |
| --------------------------- | ----------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------ |
| High-throughput API gateway | 1500ms                        | 60000ms     | Aggressive fail-fast, mas mahabang cache para bawasan ang mga pagsusuri                                            |
| Mga geo-distributed na node | 3000ms                        | 15000ms     | Ang mas mabagal na network ay nangangailangan ng mas maraming oras; mas maikling cache para sa mabilis na failover |
| Dev / pagsubok              | 1000ms                        | 10000ms     | Mabilis na pag-ulit sa mga lokal na proxy                                                                          |
| Stealth / anti-detection    | 2500ms                        | 45000ms     | Iwasan ang mabilis na pagsusuri na maaaring mag-trigger ng mga limitasyon sa rate                                  |

### Pag-inspeksyon sa Kalusugan ng Proxy

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Ang `stale` flag ay `true` kapag ang cache entry ay lumampas `HEALTH_CACHE_TTL_MS` at ang susunod na kahilingan ay magti-trigger ng bagong check.

### Mga Default na Uri ng Bawat Proxy

Gumagamit ang pagsusuri sa kalusugan ng mga makabuluhang default batay sa URL scheme:

| Scheme                     | Default na port |
| -------------------------- | --------------- |
| `http://`                  | 8080            |
| `https://`                 | 443             |
| `socks5://` / `socks5h://` | 1080            |

Palaging inuuna ang mga custom na port sa URL (`http://host:9999`) kaysa sa default na scheme.

---

## Proxy Analytics at Observability

Sinusubaybayan OmniRoute ang bawat-proxy na paggamit upang matulungan ang mga operator na mag-diagnose ng mga pattern ng pagruruta, latency spike, at paulit-ulit na pagkabigo.

### Ano ang Sinusubaybayan

Para sa bawat kahilingan sa pamamagitan ng naka-configure na proxy, itinatala ng OmniRoute ang:

| Sukatan      | Paglalarawan                                                |
| ------------ | ----------------------------------------------------------- |
| `proxy_url`  | Buong proxy URL (na may nakamask na mga kredensyal ng auth) |
| `provider`   | Upstream provider ID (openai, anthropic, atbp.)             |
| `latency_ms` | Kabuuang round-trip na oras kasama ang proxy handshake      |
| `connect_ms` | TCP connect time lang                                       |
| `status`     | HTTP status code mula sa upstream                           |
| `error`      | Error class kung nabigo ang kahilingan                      |
| `timestamp`  | ISO 8601 UTC                                                |

### Pag-access sa Data

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Ang tunay na endpoint ay `/api/usage/proxy-logs` (tingnan `src/app/api/usage/proxy-logs/route.ts`). Sinusuportahan ng endpoint na ito ang:

- `GET /api/usage/proxy-logs` — kunin ang mga proxy log
- `DELETE /api/usage/proxy-logs` — i-clear ang lahat ng proxy logs

Maaaring direktang i-query ang pinagsama-samang istatistika mula sa `proxy_logs` table sa pamamagitan ng SQL kung kinakailangan. Ang dashboard UI ay maaaring mag-alok ng mga pinagsama-samang view.

### Mga Karaniwang Pattern

**Mag-detect ng flapping proxy** (papalitan ng success/failure):

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

**Maghanap ng mga mabagal na proxy** (p95 latency > 2s):

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

## Puno ng Desisyon ng Diskarte sa Pag-ikot

Kapag maraming proxy ang itinalaga sa isang saklaw, OmniRoute ay gumagamit ng a** diskarte sa pag-ikot** upang pumili kung alin ang gagamitin para sa bawat kahilingan. Naka-configure ang diskarte sa antas ng saklaw (global, per-provider, per-account, per-combo).

### Mga Magagamit na Istratehiya

| Diskarte            | Kailan gagamitin                                     | Trade-off                                                                                     |
| ------------------- | ---------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `quality` (default) | Produksyon na may magkakahalong kalidad na mga proxy | Pinapaboran ang mga proxy na may mataas na rating; maaaring magutom ang mga mababa ang rating |
| `random`            | Pamamahagi ng load, privacy                          | Kahit na pamamahagi; binabalewala ang mga signal ng kalidad                                   |
| `sequential`        | Pag-debug, deterministikong pagsubok                 | Umikot sa pamamagitan ng mga proxy sa pagkakasunud-sunod; madaling mangatwiran                |

### Puno ng Desisyon

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

## Awtomatikong Pagbubukod ng Pagkabigo para sa Iyong Sariling Mga Proxies

Ang 1proxy marketplace pool ay nag-auto-degrade na sa mga nabigong proxy sa sarili nitong (tingnan [ang Proxy Quality Scores](#proxy-quality-scores) ). Para sa mga proxy** ikaw** idinagdag sa registry, ang background health scheduler (`src/lib/proxyHealth/scheduler.ts`) ay nagbibigay ng parehong gawi na "awtomatikong ibukod ang isang patay na miyembro mula sa chain," nang hindi tinatanggal ang anuman:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Paano ito umaangkop sa isang multi-proxy na chain:

1. Sinusuri ng scheduler ang bawat nakarehistrong proxy bawat `PROXY_HEALTH_INTERVAL_MS` (default na 10 min; minimum na 1 min).
2. Pagkatapos `PROXY_AUTO_REMOVE_AFTER` magkasunod** conclusive** mga pagkabigo (isang tunay na pagkabigo ng koneksyon — isang timeout o ang sariling target ng probe na 5xx ay hindi kailanman binibilang, tingnan [ang Proxy Health Checking](#proxy-health-checking-v3816) ), ang `status` ng proxy ay nakatakda sa `dead`.
3. `dead` ay isa sa mga status na ibinubukod ng alive-status filter na ginagamit ng pool/rotation resolution, kaya ang pag-ikot ng saklaw (round-robin / random / sticky / latency — tingnan ang [Rotation Strategy Decision Tree](#rotation-strategy-decision-tree) ) ay agad na huminto sa pagbibigay ng proxy na iyon sa mga bagong kahilingan. Walang ibang proxy sa pool ang apektado, at ang buong pool ay hindi kailanman tahimik na bumabalik sa direktang koneksyon — makita ang [4-Level Proxy System](#4-level-proxy-system) na fail-closed guard.
4. Patuloy na sinusuri ng scheduler ang mga `dead` proxy sa parehong pagitan. Ang susunod na matagumpay na probe ay nag-flip ng `status` pabalik sa `active` at ito ay muling pumasok sa rotation — na hindi kinakailangan ng manu-manong muling pagdaragdag.

Ito ay sadyang** mag-opt-in at hindi mapanira** : bilang default ang scheduler ay nagbibilang lamang at nagla-log ng mga pagkabigo (tingnan ang patakaran C sa `decision.ts`), at hindi kailanman tinatanggal `PROXY_AUTO_DISABLE` ang isang row — na para sa hiwalay, mas agresibong `PROXY_AUTO_REMOVE` flag. Kung parehong nakatakda sa `true`, mananalo ang `PROXY_AUTO_REMOVE` (ang isang proxy na malapit nang tanggalin ay walang silbi para sa isang soft-disable sa pagitan). Tingnan ang sanggunian ng [Environment Config](../reference/ENVIRONMENT.md) para sa buong listahan ng variable.

---

> 📖** Kaugnay na dokumentasyon:**
>
> - [User Guide](../guides/USER_GUIDE.md) — Pangkalahatang setup at configuration - [API Reference](../reference/API_REFERENCE.md) — Buong API documentation - [Environment Config](../reference/ENVIRONMENT.md) — Lahat ng environment variable
