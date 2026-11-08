# 🌐 OmniRoute Proxy Guide (Malti)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Bypass blokki ġeografiċi, ipproteġi l-identità tiegħek, u rotta AI traffiku minn kwalunkwe proxy — b'kumplessità ta 'konfigurazzjoni żero.**

OmniRoute jinkludi sistema ta' ġestjoni ta' prokura sħiħa li tħallik rotta upstream traffiku tal-fornitur AI permezz ta' prokuri HTTP, HTTPS, jew SOCKS5. Kemm jekk int f'reġjun imblukkat, għandek bżonn rotazzjoni IP, jew tridx tiġbed il-marki tas-swaba 'stealth — din il-gwida tkopri kollox.

---

## Werrej

- [Għaliex Uża Prokuri?](#why-use-proxies)
- [Ħarsa ġenerali lejn l-Arkitettura](#architecture-overview)
- [Sistema ta' Prokura ta' 4 Livelli](#4-level-proxy-system)
- [Reġistru tal-Prokura (CRUD)](#proxy-registry-crud)
- [1Prokura Suq Ħieles](#1proxy-free-proxy-marketplace)
- [Rotazzjoni tal-Prokura](#proxy-rotation)
- [Kontra l-Kxif u Stealth](#anti-detection--stealth)
- [Modi ta' Prokura Upstream](#upstream-proxy-modes)
- [Dashboard UI](#dashboard-ui)
- [API Referenza](#api-reference)
- [Varjabbli Ambjentali](#environment-variables)
- [Issolvi l-problemi](#troubleshooting)

---

## Għaliex Uża Prokuri?

Ħafna fornituri AI jirrestrinġu l-aċċess skont ir-reġjun ġeografiku. Iżviluppaturi fi** Ir-Russja, iċ-Ċina, l-Iran, Kuba, it-Turkija** , u pajjiżi oħra jiltaqgħu ma' żbalji bħal:

```
unsupported_country_region_territory
```

Anke barra minn reġjuni mblukkati, il-prokuri huma utli għal:

| Każ ta' Użu           | Deskrizzjoni                                                       |
| --------------------- | ------------------------------------------------------------------ |
| **Bypass ġeografiku** | Aċċess OpenAI, Anthropic, Codex, Copilot minn pajjiżi imblukkati   |
| **IP rotazzjoni**     | Qassam it-talbiet fuq IPs multipli biex tevita li tillimita r-rata |
| **Privatezza**        | Aħbi IP reali tiegħek minn fornituri upstream                      |
| **Konformità**        | It-traffiku tar-rotta minn ġurisdizzjonijiet speċifiċi             |
| **Ittestjar**         | Issimula talbiet minn reġjuni differenti                           |

---

## Ħarsa ġenerali lejn l-Arkitettura

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

### Komponenti Ewlenin

| Komponent                  | Fajl                                         | Rwol                                                     |
| -------------------------- | -------------------------------------------- | -------------------------------------------------------- |
| **Reġistru tal-Prokura**   | `src/lib/db/proxies.ts`                      | CRUD għal daħliet prokura + ambitu assenjazzjonijiet     |
| **Dispatcher tal-Prokura** | `open-sse/utils/proxyDispatcher.ts`          | Joħloq dispatchers `undici` ProxyAgent/SOCKS bil-caching |
| **Proxy Fetch**            | `open-sse/utils/proxyFetch.ts`               | Wraps `fetch()` b'injezzjoni ta' proxy dispatcher        |
| **Settings Rotta**         | `src/app/api/settings/proxy/route.ts`        | Legacy proxy konfig API (GET/PUT/DELETE)                 |
| **Rotta ta' Ġestjoni**     | `src/app/api/v1/management/proxies/route.ts` | Reġistru CRUD API (GET/POST/PATCH/DELETE)                |
| **1proxy DB**              | `src/lib/db/oneproxy.ts`                     | Persistenza tas-suq prokura b'xejn                       |

---

## Stat prokura default għal kontijiet ġodda

Fil** Settings → Proxy → Konfigurazzjoni globali** , uża** Ippermetti proxy awtomatikament għal konnessjonijiet ġodda** biex tagħżel l-istat inizjali tal-prokura tal-kontijiet tal-fornitur li għadhom kif ġew miżjuda.

L-issettjar il-ġdid jikkontrolla l-istat inizjali tal-prokura tal-kontijiet tal-fornitur li għadhom kif ġew miżjuda. Ma tbiddilx il-kontijiet eżistenti jew tissostitwixxi l-iswiċċ tal-prokura globali. Il-valur inizjali tiegħu jippreserva l-imġieba preċedenti. Itfiha darba biex toħloq kontijiet futuri bi proxy diżattivat awtomatikament.

Il-preferenza tinħażen bħala `defaultNewConnectionProxyEnabled` permezz tas-Settings API eżistenti. Huwa default għal `true` meta qatt ma jiġi salvat. L-iffrankar `false` jidħol fis-seħħ għal kontijiet ġodda sussegwenti mingħajr bidu mill-ġdid. `POST /api/providers` jaċċetta `proxyEnabled` boolean strett fakultattiv; `true` jew `false` espliċitu jieħu preċedenza fuq id-default tal-ħolqien. Omissjoni fuq kont duplikat jew OAuth reconnect jippreserva l-istat maħżun ta' dak il-kont. Il-kontijiet individwali xorta jistgħu jiġu attivati jew diżattivati wara.

It-trasferimenti tal-fornituri selettivi jużaw il-mod awtomatiku tal-installazzjoni tad-destinazzjoni għal kontijiet ġodda u jippreservaw il-politika tad-destinazzjoni meta jissostitwixxu l-kontijiet eżistenti. Proxy toggles mhumiex oqsma ta 'trasferiment portabbli. Ir-restawr sħiħ tal-backup u l-migrazzjoni storika JSON/SQL jżommu s-semantika tar-restawr eżistenti tagħhom, inklużi l-valuri tal-kont issejvjati u l-inadempjenzi tal-iskema tal-legat; restawr tas-settings sħiħ jista 'wkoll jirrestawra din il-preferenza.

Din il-preferenza ma tassenjax prokura jew tistabbilixxi li wieħed huwa b'saħħtu jew qed jintuża. Ir-rotot attwali għadu jiddependi fuq is-swiċċ tal-prokura globali u l-konfigurazzjoni tal-prokura applikabbli. Fornituri sintetiċi mingħajr kont persistenti, traffiku OAuth qabel il-ħolqien tal-kont, prokuri environment/system, u netwerking ta 'backends esterni huma barra l-ambitu tiegħu.

## Sistema ta' Prokura ta' 4 Livelli

OmniRoute jappoġġja konfigurazzjoni tal-prokura fuq** erba’ ambiti indipendenti** , solvuti f'ordni ta' prijorità:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Kif Taħdem ir-Riżoluzzjoni

Meta OmniRoute jibgħat talba lil fornitur upstream, isejjaħ `resolveProxyForConnectionFromRegistry()` li jiċċekkja kull livell fl-ordni:

1. **Livell tal-kont** — Hemm prokura assenjata għal din il-konnessjoni speċifika ID?
2. **Livell tal-fornitur** — Hemm prokura assenjata lil dan il-fornitur (eż., `openai`)?
3. **Livell globali** — Hemm proxy globali kkonfigurat?
4. **Ebda prokura** — Konnessjoni diretta mal-fornitur.

L-ewwel partita tirbaħ. Dan ifisser li tista' tissettja prokura globali bħala riżerva iżda tegħlebha għal fornituri jew konnessjonijiet speċifiċi.

### What Gets Prokurat

| Tip ta' Traffiku             | Prokurat? | Noti                                           |
| ---------------------------- | --------- | ---------------------------------------------- |
| Tlestija taċ-chat            | ✅        | It-talbiet kollha `/v1/chat/completions`       |
| Inkorporazzjonijiet          | ✅        | `/v1/embeddings`                               |
| Ġenerazzjoni tal-immaġni     | ✅        | `/v1/images/generations`                       |
| Awdjo (TTS/STT)              | ✅        | `/v1/audio/*`                                  |
| OAuth token exchange         | ✅        | Issolvi `unsupported_country_region_territory` |
| Testijiet ta' konnessjoni    | ✅        | Il-buttuna "Test Konnessjoni" tuża prokura     |
| Aġġornar tat-token           | ✅        | Sfond OAuth tiġdid                             |
| Sinkronizzazzjoni tal-mudell | ✅        | Elenkar tal-mudelli u skoperta                 |

---

## Reġistru tal-Prokura (CRUD)

Ir-reġistru tal-prokura hija tabella SQLite (`proxy_registry`) li taħżen il-prokuri kollha tiegħek. Kull prokura għandha:

| Qasam      | Tip     | Deskrizzjoni                                               |
| ---------- | ------- | ---------------------------------------------------------- |
| `id`       | UUID    | Identifikatur uniku                                        |
| `name`     | Spag    | Tikketta li tinqara mill-bniedem                           |
| `type`     | Spag    | Protokoll: `http`, `https`, `socks5`                       |
| `host`     | Spag    | Proxy hostname jew IP                                      |
| `port`     | Integer | Numru tal-port                                             |
| `username` | Spag    | Awth username (kriptat waqt il-mistrieħ)                   |
| `password` | Spag    | Password ta' awtorizzazzjoni (kodifikata waqt il-mistrieħ) |
| `region`   | Spag    | Tikketta tar-reġjun ġeografiku                             |
| `notes`    | Spag    | Noti b'test liberu                                         |
| `status`   | Spag    | `active` jew `inactive`                                    |
| `source`   | Spag    | `manual` jew `oneproxy`                                    |

### Ħolqien ta 'Prokura

**Permezz tad-Dashboard:**

1. Mur fuq** Settings → Proxy**
2. Ikklikkja** Żid Prokura**
3. Imla t-tip, l-ospitant, il-port, u l-kredenzjali tal-awtentikazzjoni fakultattivi
4. Ħlief

**Via API:**

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

### Aġġornament ta' Prokura

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Nota:** Il-kredenzjali huma ppreservati sakemm ma tibgħatx b'mod espliċitu sostituti mhux vojta. Li tibgħat strings vojta għal `username`/`password` se żżomm il-valuri maħżuna.

### Tħassir ta' Prokura

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Elenkar ta' Prokuri

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Assenjazzjoni ta' Prokuri għal Ambiti

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

### Riżoluzzjoni ta' Prokura Effettiva

Iċċekkja liema proxy se jintuża għal konnessjoni partikolari:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Jirritorna l-prokura riżolta bil-livell tagħha (`account`, `provider`, jew `global`) u s-sors.

### Assenjazzjoni bl-ingrossa

Assenja prokura waħda lil fornituri jew konnessjonijiet multipli f'daqqa:

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

Prokuri huma inklużi fil-**Backup/Restore** sistema. Meta tesporta l-konfigurazzjoni OmniRoute tiegħek:

1. Mur fuq** Dashboard → Settings → Backup**
2. Ikklikkja** Esportazzjoni** — proxy reġistru u assenjazzjonijiet huma inklużi
3. Biex tirrestawra, ikklikkja** Importazzjoni** u ttella' l-fajl tal-backup

Ir-reġistru tal-prokura jappoġġja wkoll** upsert by host + port** — jekk timporta proxy li diġà jeżisti (l-istess host u port), jaġġorna minflok ma joħloq duplikat.

### Migrazzjoni Legat

Jekk kkonfigurajt prokuri f'verżjoni eqdem (pre-reġistru), OmniRoute jemigrahom awtomatikament:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Dan jiġri darba fl-ewwel bidu wara l-aġġornament. Uża `migrateLegacyProxyConfigToRegistry({ force: true })` biex terġa' tmexxi.

---

## 1Prokura Prokura Ħieles Suq

> 🆕** Kontribut minn [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Ħruġ [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute tintegra mal-** [1prokura](https://1proxy-api.aitradepulse.com)** pjattaforma komunitarja biex tipprovdi aċċess għal** mijiet ta’ prokuraturi b’xejn u validati** minn madwar id-dinja. Dan huwa perfett għall-utenti li m'għandhomx l-infrastruttura tal-prokura tagħhom stess.

### Kif Taħdem

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sinkronizzazzjoni** — OmniRoute iġib prokuri validati mill-1proxy API
2. **Aħżen** — Proxies huma ssejvjati fl-istess tabella `proxy_registry` ma `source = 'oneproxy'`
3. **Iffiltra** — Iffiltra skond il-protokoll, il-pajjiż, il-punteġġ tal-kwalità
4. **Dawwar** — Agħżel l-aħjar prokura billi tuża strateġiji ta' kwalità, każwali jew sekwenzjali
5. **Auto-degrada** — Prokuraturi falluti jnaqqsu l-punteġġ tal-kwalità tagħhom; taħt il-limitu → immarkat inattiv

### Is-sinkronizzazzjoni tal-Prokuri

**Permezz tad-Dashboard:**

1. Mur fuq** Settings → 1proxy** tab
2. Ikklikkja** "Ssinkronizza Issa"**
3. Ara l-istatistiċi: prokuri totali, għadd attiv, kwalità medja, tqassim skont il-pajjiż

**Via API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Iffiltrar ta' Prokuri

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

### Punteġġi ta' Kwalità Prokura

Kull proxy 1 proxy jiġi b'metadejta:

| Qasam           | Deskrizzjoni                                    |
| --------------- | ----------------------------------------------- |
| `qualityScore`  | 0-100 klassifikazzjoni mill-validazzjoni 1proxy |
| `latencyMs`     | Latenza tan-netwerk imkejla                     |
| `anonymity`     | `transparent`, `anonymous`, jew `elite`         |
| `googleAccess`  | Jekk il-prokura jistax jaċċessa servizzi Google |
| `countryCode`   | Kodiċi tal-pajjiż ISO b'żewġ ittri              |
| `lastValidated` | Timestamp tal-aħħar validazzjoni                |

Il-punteġġi tal-kwalità huma aġġustati dinamikament:

- **Talbiet falluti** tnaqqas il-punteġġ b'10 punti
- **Score jinżel għal ≤ 10** → proxy huwa mmarkat `inactive`
- Prokuri inattivi huma esklużi mir-rotazzjoni

### Strateġiji ta' Rotazzjoni

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

Is-sinkronizzazzjoni 1proxy għandha circuit breaker inkorporat:

- Wara** 5 fallimenti konsekuttivi tas-sinkronizzazzjoni** , aktar tentattivi ta' sinkronizzazzjoni huma mblukkati
- Irrisettja bi: `resetOneproxyCircuitBreaker()` jew ibda mill-ġdid is-server
- L-istatus tas-sinkronizzazzjoni huwa disponibbli fuq `GET /api/settings/oneproxy?action=status`

### Ikklerjar ta' Prokuraturi 1

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Kontra l-Kxif u Stealth

OmniRoute ma jindirizzax biss it-traffiku minn proxy — iżda jagħmel it-traffiku jidher leġittimu:

### TLS Spoofing tal-marki tas-swaba

Juża `wreq-js` biex jiġġenera marki tas-swaba TLS bħal browser, billi jinjora s-sistemi ta' skoperta tal-bot li jimmarkaw handshakes TLS mhux tal-browser.

### CLI Fingerprint Matching

Il-**CLI Fingerprint Toggle** (`Settings → Security`) terġa' tordna HTTP headers u JSON body fields biex jaqblu mal-firma eżatta ta' binarji CLI indiġeni (Claude Code, Codex, eċċ.). Dan jaħdem** fuq nett** il-prokura:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Ikollok it-tnejn**IP masking** u** titlob l-awtentiċità** fl-istess ħin.

### Prokura IP Preservazzjoni

Badges kodifikati bil-kulur fid-daxxbord juru liema livell ta' prokura huwa attiv:

| Badge | Livell      | Tifsira                                       |
| ----- | ----------- | --------------------------------------------- |
| 🟢    | Globali     | It-traffiku kollu jgħaddi minn dan il-prokura |
| 🟡    | Fornitur    | Huwa biss it-traffiku ta' dan il-fornitur     |
| 🔵    | Konnessjoni | Din key/account speċifika tuża din il-prokura |

Il-badge turi wkoll il-prokura IP solvuta għall-verifika.

---

## Modi ta' Prokura Upstream

Għal fornituri li jużaw il-mudell CLIProxyAPI, OmniRoute jappoġġja tliet modi ta’ proxy upstream:

| Modalità      | Deskrizzjoni                                                    |
| ------------- | --------------------------------------------------------------- |
| `native`      | OmniRoute jimmaniġġja r-rotot tal-prokura direttament (default) |
| `cliproxyapi` | Delegati f'istanza CLIProxyAPI esterna                          |
| `fallback`    | Jipprova nattiv l-ewwel, jaqa lura CLIProxyAPI                  |

Ikkonfigura għal kull fornitur:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Dashboard UI

### Settings → Proxy Tab

- **Prokura globali** konfigurazzjoni (issettjat darba għat-traffiku kollu)
- **Prokura għal kull fornitur** jegħleb
- **Prokura għal kull konnessjoni** inkarigi
- **Test tal-konnessjoni** permezz ta' prokura konfigurata
- **Badges kodifikati bil-kulur** li juri livell ta' prokura attiv

### Settings → 1proxy Tab

- **Sinkronizza Issa** buttuna biex iġġib prokuri b'xejn
- **Karti tal-istatistiċi** : Totali, Attiva, Kwalità Medja, L-Aħħar Sinkronizzazzjoni
- **Filtri** : Protokoll, Kodiċi tal-Pajjiż, Kwalità Min
- **Tabella prokura** b'host, protokoll, pajjiż, punteġġ ta' kwalità, latency, anonimità, aċċess Google
- **L-istatus tas-sinkronizzazzjoni** panel ma success/failure tracking u għadd konsekuttiv ta 'falliment
- **Ċara Kollha** biex tneħħi l-iskrizzjonijiet kollha tal-1proxy

---

## API Referenza

### Proxy Settings API

| Metodu   | Endpoint                                       | Deskrizzjoni                               |
| -------- | ---------------------------------------------- | ------------------------------------------ |
| `GET`    | `/api/settings/proxy`                          | Ikseb il-konfigurazzjoni sħiħa tal-prokura |
| `GET`    | `/api/settings/proxy?level=global`             | Ikseb prokura globali                      |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Ikseb prokura tal-fornitur                 |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Issolvi prokura effettiva                  |
| `PUT`    | `/api/settings/proxy`                          | Aġġorna l-konfigurazzjoni tal-prokura      |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Neħħi prokura fil-livell                   |

### Reġistru tal-Prokura API

| Metodu   | Endpoint                                          | Deskrizzjoni                    |
| -------- | ------------------------------------------------- | ------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Elenka l-prokuri kollha         |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Ikseb proxy minn ID             |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Ikseb inkarigi ta' prokura      |
| `POST`   | `/api/v1/management/proxies`                      | Oħloq prokura                   |
| `PATCH`  | `/api/v1/management/proxies`                      | Aġġorna l-prokura               |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Ħassar prokura                  |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Forza tħassar                   |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Assenja bl-ingrossa             |
| `GET`    | `/api/v1/management/proxies/assignments`          | Elenka l-inkarigi               |
| `GET`    | `/api/v1/management/proxies/health`               | Statstiċi tas-saħħa tal-prokura |

### Mini API

Biex tesponi l-istanza ta' OmniRoute tiegħek għall-internet pubbliku (Cloudflare/ngrok/Tailscale) minflok ta' rotta 'l barra permezz ta' prokura, ara [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Il-mina REST API tgħix taħt `/api/tunnels/{cloudflared,ngrok,tailscale}/*` u hija ortogonali għall-katina ta' prokura 'l barra dokumentata hawn fuq.

### 1proxy API

| Metodu   | Endpoint                               | Deskrizzjoni                               |
| -------- | -------------------------------------- | ------------------------------------------ |
| `GET`    | `/api/settings/oneproxy`               | Elenka 1 prokuri prokura                   |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Ikseb stats + sync status                  |
| `GET`    | `/api/settings/oneproxy?action=status` | Ikseb l-istatus tas-sinkronizzazzjoni biss |
| `POST`   | `/api/settings/oneproxy`               | Trigger sync                               |
| `POST`   | `/api/settings/oneproxy/rotate`        | Dawwar għall-prokura li jmiss              |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Ħassar wieħed                              |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Ċara kollox                                |

### Upstream Proxy API

| Metodu   | Endpoint                          | Deskrizzjoni                                  |
| -------- | --------------------------------- | --------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Ikseb il-konfigurazzjoni tal-prokura upstream |
| `PUT`    | `/api/upstream-proxy/:providerId` | Issettja l-modalità prokura upstream          |
| `DELETE` | `/api/upstream-proxy/:providerId` | Neħħi l-konfigurazzjoni tal-prokura upstream  |

---

## Varjabbli Ambjentali

| Varjabbli             | Default | Deskrizzjoni                                                         |
| --------------------- | ------- | -------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`  | Ippermetti l-appoġġ ta' proxy SOCKS5 (default `true` `.env.example`) |

---

## Issolvi l-problemi

### "SOCKS5 proxy huwa diżattivat "

Issettja `ENABLE_SOCKS5_PROXY=true` fil-fajl `.env` tiegħek u ibda mill-ġdid.

### "socket hang up" żbalji permezz ta' prokura

Dan huwa normali bi prokuri irħas li jwaqqgħu konnessjonijiet idle. OmniRoute diġà jieħu ħsieb dan billi:

- Id-diżattivazzjoni ta' keep-alive fuq konnessjonijiet ta' prokura (`keepAliveTimeout: 1`)
- Id-diżattivazzjoni tal-pipelining (`pipelining: 0`)
- Caching dispatchers biex jiġu evitati handshakes ripetuti

Jekk tippersisti, ipprova prokura differenti jew uża l-karatteristika ta 'rotazzjoni 1proxy.

### "unsupported_country_region_territory" matul OAuth

Kun żgur li l-prokura hija kkonfigurata** qabel** jibda l-fluss OAuth. OmniRoute imur skambju ta' tokens OAuth permezz tal-prokura konfigurata. Issettja prokura globali jew fil-livell tal-fornitur l-ewwel, imbagħad qabbad.

### Prokura mhux qed jintuża

Iċċekkja l-ordni tar-riżoluzzjoni:

1. Ivverifika bi `GET /api/settings/proxy?resolve=your-connection-id`
2. Iċċekkja jekk il-prokura `status` hijiex `active` (mhux `inactive`)
3. Kun żgur li l-ambitu tal-assenjazzjoni tal-prokura jaqbel mal-konnessjoni tiegħek

### 1-sinkronizzazzjoni tal-proxy tfalli

Iċċekkja l-istatus tas-sinkronizzazzjoni:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Jekk `consecutiveFailures >= 5`, is-circuit breaker ikun qabad. Ibda mill-ġdid is-server biex jerġa' jiġi ssettjat, jew stenna għal reset manwali.

---

## Skema tad-Database

### `proxy_registry` Tabella

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

### `proxy_assignments` Tabella

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

## Iċċekkjar tas-Saħħa tal-Prokura (v3.8.16 +)

OmniRoute's** prokura fast-fail** mekkaniżmu (`src/lib/proxyHealth.ts`) jiskopri prokuri mejta < 2s permezz ta 'kontroll ta' konnessjoni TCP malajr, imbagħad** caches ir-riżultat** biex tevita overhead għal kull talba.

### Kif Taħdem

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

Mingħajr dan, prokura mejjet jimblokka kull talba għall- `PROXY_TIMEOUT_MS` sħiħa (default 30s) qabel ma tfalli.

### Varjabbli Ambjentali Sintonizzabbli

| Varjabbli                    | Default | Għan                                                     |
| ---------------------------- | ------- | -------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | TCP timeout tal-konnessjoni għal kull kontroll tas-saħħa |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | Kemm idum riżultat tas-saħħa huwa cache                  |

**Valuri rakkomandati:**

| Xenarju                             | Timeout fast-fail | Cache TTL | Raġunar                                                                     |
| ----------------------------------- | ----------------- | --------- | --------------------------------------------------------------------------- |
| Gateway API ta’ prestazzjoni għolja | 1500ms            | 60000ms   | Fassil aggressiv veloċi, cache itwal biex jitnaqqsu l-kontrolli             |
| Nodi mqassma ġeo                    | 3000ms            | 15000ms   | Netwerks aktar bil-mod jeħtieġu aktar ħin; cache iqsar għal failover veloċi |
| Dev / ittestjar                     | 1000ms            | 10000ms   | Iterazzjoni malajr fuq prokuri lokali                                       |
| Stealth / kontra l-iskoperta        | 2500ms            | 45000ms   | Evita probing rapidu li jista 'jwassal għal limiti tar-rata                 |

### Spezzjonar tas-Saħħa tal-Prokura

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Il-bandiera `stale` hija `true` meta d-dħul tal-cache qabeż `HEALTH_CACHE_TTL_MS` u t-talba li jmiss se tagħti bidu għal kontroll ġdid.

### Defaults tat-Tip Per-Proxy

Il-kontroll tas-saħħa juża nuqqasijiet sensibbli bbażati fuq l-iskema URL :

| Skema                      | Port default |
| -------------------------- | ------------ |
| `http://`                  | 8080         |
| `https://`                 | 443          |
| `socks5://` / `socks5h://` | 1080         |

Portijiet tad-dwana URL (`http://host:9999`) dejjem jieħdu preċedenza fuq l-iskema default.

---

## Analitika tal-Prokura u Osservabbiltà

OmniRoute jsegwi l-użu għal kull proxy biex jgħin lill-operaturi jiddijanjostikaw il-mudelli tar-rotot, spikes latency, u fallimenti rikorrenti.

### X'inhu Tracked

Għal kull talba permezz ta' prokura kkonfigurata, OmniRoute jirreġistra:

| Metriku      | Deskrizzjoni                                                      |
| ------------ | ----------------------------------------------------------------- |
| `proxy_url`  | Prokura sħiħa URL (bil-kredenzjali ta' awtorizzazzjoni mgħottija) |
| `provider`   | Upstream provider ID (openai, antropiku, eċċ.)                    |
| `latency_ms` | Ħin totali ta' vjaġġ bir-ritorn inkluż handshake ta' prokura      |
| `connect_ms` | TCP connect time biss                                             |
| `status`     | kodiċi tal-istatus HTTP minn upstream                             |
| `error`      | Klassi ta' żball jekk it-talba falliet                            |
| `timestamp`  | ISO 8601 UTC                                                      |

### Aċċess għad-Data

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

L-endpoint reali huwa `/api/usage/proxy-logs` (ara `src/app/api/usage/proxy-logs/route.ts`). Dan l-endpoint jappoġġja:

- `GET /api/usage/proxy-logs` — jirkupra proxy logs
- `DELETE /api/usage/proxy-logs` — ikklerja l-logs proxy kollha

Stats aggregati jistgħu jiġu mistoqsija direttament mit-tabella `proxy_logs` permezz SQL jekk meħtieġ. Id-dashboard UI jista' joffri fehmiet aggregati.

### Mudelli Komuni

**Issib prokura flapping** (jalterna bejn success/failure):

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

**Sib prokuri bil-mod** (p95 latency > 2s):

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

## Siġra tad-Deċiżjoni ta' Strateġija ta' Rotazzjoni

Meta diversi prokuri jiġu assenjati għal skop, OmniRoute juża a** strateġija ta' rotazzjoni** biex tagħżel liema waħda tuża għal kull talba. L-istrateġija hija kkonfigurata fil-livell tal-ambitu (globali, għal kull fornitur, għal kull kont, għal kull combo).

### Strateġiji Disponibbli

| Strateġija          | Meta tuża                                  | Kompromess                                                                       |
| ------------------- | ------------------------------------------ | -------------------------------------------------------------------------------- |
| `quality` (default) | Produzzjoni bi prokuri ta' kwalità mħallta | Jippreferi prokuri b'rata għolja; jistgħu joqogħdu bil-ġuħ lil dawk b’rata baxxa |
| `random`            | Distribuzzjoni tat-tagħbija, privatezza    | Anke distribuzzjoni; jinjora sinjali ta 'kwalità                                 |
| `sequential`        | Debugging, ittestjar deterministiku        | Iċċekkja permezz ta' prokuri fl-ordni; faċli biex tirraġuna dwar                 |

### Siġra tad-Deċiżjoni

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

## Esklużjoni ta' Falliment Awtomatiku għall-Prokuri Tiegħek stess

Il-pool tas-suq 1proxy diġà jiddegrada awtomatikament il-prokuri falluti waħdu (ara [Punteġġi tal-Kwalità tal-Prokura](#proxy-quality-scores) ). Għal prokuri** int** miżjud mar-reġistru, l-iskedar tas-saħħa fl-isfond (`src/lib/proxyHealth/scheduler.ts`) jipprovdi l-istess imġieba "eskludi membru mejjet mill-katina awtomatikament", mingħajr ma tħassar xejn:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Kif tidħol f'katina multi-prokura:

1. L-iskeder jistħarreġ kull proxy reġistrat kull `PROXY_HEALTH_INTERVAL_MS` (default 10 min; minimu 1 min).
2. Wara `PROXY_AUTO_REMOVE_AFTER` konsekuttiva** konklussiv** fallimenti (falliment ta' konnessjoni reali — a timeout jew il-5xx tal-mira tas-sonda stess qatt ma jgħodd, ara [Proxy Health Checking](#proxy-health-checking-v3816) ), `status` tal-prokura huwa ssettjat għal `dead`.
3. `dead` huwa wieħed mill-istatus li l-filtru tal-istatus ħaj użat mir-riżoluzzjoni pool/rotation jeskludi, għalhekk rotazzjoni ta 'ambitu (round-robin / każwali / twaħħal / latency — ara [Siġra tad-Deċiżjoni tal-Istrateġija ta' Rotazzjoni](#rotation-strategy-decision-tree) ) immedjatament tieqaf tagħti dik il-prokura għal talbiet ġodda. L-ebda prokuri oħra fil-pool ma huma affettwati, u l-pool kollu qatt ma jaqa’ lura fis-skiet għal konnessjoni diretta — ara s [-Sistema ta’ Prokura ta’ 4 Livelli](#4-level-proxy-system) fail-closed guard.
4. L-iskeder ikompli jfittex `dead` proxies fuq l-istess intervall. Is-sonda ta' suċċess li jmiss taqleb `status` lura għal `active` u terġa' tidħol fir-rotazzjoni — l-ebda żieda manwali meħtieġa.

Dan huwa apposta** opt-in u mhux distruttiv** : b'mod awtomatiku l-iskeduler jgħodd u jirreġistra biss il-fallimenti (ara l-politika C `decision.ts`), u `PROXY_AUTO_DISABLE` qatt ma jħassar ringiela — li hija għaliha l-bandiera `PROXY_AUTO_REMOVE` separata u aktar aggressiva. Jekk it-tnejn huma ssettjati għal `true`, `PROXY_AUTO_REMOVE` jirbaħ (prokura li waslet biex titħassar m'għandha l-ebda użu għal soft-disable bejniethom). Ara r-referenza [tal-Konfigurazzjoni tal-Ambjent](../reference/ENVIRONMENT.md) għal-lista sħiħa tal-varjabbli.

---

> 📖** Dokumentazzjoni relatata:**
>
> - [Gwida għall-Utent](../guides/USER_GUIDE.md) — Setup u konfigurazzjoni ġenerali - [API Reference](../reference/API_REFERENCE.md) — Dokumentazzjoni sħiħa API - [Environment Config](../reference/ENVIRONMENT.md) — Il-varjabbli ambjentali kollha
