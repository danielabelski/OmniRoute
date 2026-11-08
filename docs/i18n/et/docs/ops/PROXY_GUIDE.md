# 🌐 OmniRoute Proxy Guide (Eesti)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Mööduge geograafilistest plokkidest, kaitske oma identiteeti ja suunake AI liiklus läbi mis tahes puhverserveri — mille konfiguratsiooni pole keeruline.**

OmniRoute sisaldab täisfunktsionaalsusega puhverserveri haldussüsteemi, mis võimaldab teil suunata ülesvoolu AI pakkuja liiklust HTTP, HTTPS või SOCKS5 puhverserverite kaudu. Olenemata sellest, kas asute blokeeritud piirkonnas, vajate IP pööramist või soovite salajase — see juhend hõlmab kõike.

---

## Sisukord

- [Miks kasutada puhverservereid?](#why-use-proxies)
- [Arhitektuuri ülevaade](#architecture-overview)
- [4-tasemeline puhverserveri süsteem](#4-level-proxy-system)
- [Puhverserveri register (CRUD)](#proxy-registry-crud)
- [1 puhverserveri tasuta turg](#1proxy-free-proxy-marketplace)
- [Puhverserveri pööramine](#proxy-rotation)
- [Tuvastamisvastane ja varjamine](#anti-detection--stealth)
- [Ülesvoolu puhverserveri režiimid](#upstream-proxy-modes)
- [Armatuurlaud UI](#dashboard-ui)
- [API viide](#api-reference)
- [Keskkonnamuutujad](#environment-variables)
- [Veaotsing](#troubleshooting)

---

## Miks kasutada puhverservereid?

Paljud AI pakkujad piiravad juurdepääsu geograafilise piirkonna järgi. Arendajad sisse** Venemaa, Hiina, Iraan, Kuuba, Türgi** ja teistes riikides ilmnevad sellised vead nagu:

```
unsupported_country_region_territory
```

Isegi väljaspool blokeeritud piirkondi on puhverserverid kasulikud:

| Kasuta ümbrist              | Kirjeldus                                                          |
| --------------------------- | ------------------------------------------------------------------ |
| **Geograafiline ümbersõit** | Juurdepääs OpenAI, Anthropic, Codex, Copilot blokeeritud riikidest |
| **IP pöörlemine**           | Jaotage päringud mitme IPs vahel, et vältida kiiruse piiramist     |
| **Privaatsus**              | Peida oma tegelik IP ülesvoolu pakkujate eest                      |
| **Vastavus**                | Suunake liiklus läbi kindlate jurisdiktsioonide                    |
| **Testimine**               | Simuleerige taotlusi erinevatest piirkondadest                     |

---

## Arhitektuuri ülevaade

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

### Põhikomponendid

| Komponent                  | Fail                                         | Roll                                                                |
| -------------------------- | -------------------------------------------- | ------------------------------------------------------------------- |
| **Puhverserveri register** | `src/lib/db/proxies.ts`                      | CRUD puhverserveri kirjete jaoks + ulatuse määramiseks              |
| **Puhverserver dispetšer** | `open-sse/utils/proxyDispatcher.ts`          | Loob vahemällu salvestamisega `undici` ProxyAgent/SOCKS dispetšerid |
| **Puhverserveri toomine**  | `open-sse/utils/proxyFetch.ts`               | Mähib `fetch()` puhverserveri dispetšeri süstiga                    |
| **Seaded Marsruut**        | `src/app/api/settings/proxy/route.ts`        | Pärandpuhverserveri konfiguratsioon API (GET/PUT/DELETE)            |
| **Juhtimistee**            | `src/app/api/v1/management/proxies/route.ts` | Registry CRUD API (GET/POST/PATCH/DELETE)                           |
| **1 puhverserver DB**      | `src/lib/db/oneproxy.ts`                     | Tasuta puhverserveri turu püsivus                                   |

---

## Uute kontode puhverserveri vaikeolek

sisse** Seaded → Puhverserver → Globaalne konfiguratsioon** , kasutage** Luba uute ühenduste jaoks vaikimisi puhverserver** äsja lisatud pakkujakontode esialgse puhverserveri oleku valimiseks.

Uus säte juhib äsja lisatud pakkujakontode esialgset puhverserveri olekut. See ei muuda olemasolevaid kontosid ega asenda globaalset puhverserveri lülitit. Selle algväärtus säilitab varasema käitumise. Lülitage see üks kord välja, et luua tulevasi kontosid, kus puhverserver on vaikimisi keelatud.

Eelistus salvestatakse `defaultNewConnectionProxyEnabled` -na olemasolevate sätete API kaudu. Kui seda pole kunagi salvestatud, on see vaikimisi `true`. `false` salvestamine jõustub järgmiste uute kontode puhul ilma taaskäivitamiseta. `POST /api/providers` aktsepteerib valikulist ranget tõeväärtust `proxyEnabled`; selgesõnaline `true` või `false` on loomise vaikeväärtuse suhtes ülimuslik. Duplikaatkonto väljajätmine või OAuth uuesti ühendamine säilitab selle konto salvestatud oleku. Individuaalseid kontosid saab ka hiljem lubada või keelata.

Pakkuja valikulised ülekanded kasutavad uute kontode jaoks sihtinstalli vaikeseadet ja säilitavad olemasolevate kontode asendamisel sihtkoha poliitika. Puhverserveri lülitid ei ole kaasaskantavad edastusväljad. Täielik varukoopia taastamine ja ajalooline JSON/SQL migratsioon säilitavad olemasoleva taastamise semantika, sealhulgas salvestatud kontoväärtused ja pärandskeemi vaikeseaded; seadete täielik taastamine võib ka selle eelistuse taastada.

See eelistus ei määra puhverserverit ega kinnita, et see on terve või kasutusel. Tegelik marsruutimine sõltub endiselt globaalsest puhverserveri lülitist ja kohaldatavast puhverserveri konfiguratsioonist. Ilma püsiva kontota sünteetilised pakkujad, OAuth -liiklus enne konto loomist, environment/system puhverserverid ja väliste taustaprogrammide võrgud jäävad selle kohaldamisalast välja.

## 4-tasemeline puhverserveri süsteem

OmniRoute toetab puhverserveri konfigureerimist aadressil** neli sõltumatut ulatust** , lahendatud prioriteetsuse järjekorras:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Kuidas resolutsioon töötab

Kui OmniRoute saadab päringu ülesvoolu pakkujale, helistab ta `resolveProxyForConnectionFromRegistry()`, mis kontrollib iga taset järjekorras:

1. **Konto tasemel** — Kas sellele konkreetsele ühendusele ID on määratud puhverserver?
2. **Pakkuja tasemel** — Kas sellele pakkujale on määratud puhverserver (nt `openai`)?
3. **Globaalne tase** — Kas globaalne puhverserver on konfigureeritud?
4. **Puhverserver puudub** — Otseühendus teenusepakkujaga.

Esimene matš võidab. See tähendab, et saate määrata globaalse puhverserveri tagavaraks, kuid alistada selle konkreetsete pakkujate või ühenduste jaoks.

### Mis saab puhverserveri

| Liikluse tüüp         | Vahendatud? | Märkmed                                         |
| --------------------- | ----------- | ----------------------------------------------- |
| Vestluse lõpetamised  | ✅          | Kõik `/v1/chat/completions` taotlused           |
| Manused               | ✅          | `/v1/embeddings`                                |
| Pildi genereerimine   | ✅          | `/v1/images/generations`                        |
| Heli (TTS/STT)        | ✅          | `/v1/audio/*`                                   |
| OAuth märgivahetus    | ✅          | Lahendab `unsupported_country_region_territory` |
| Ühendustestid         | ✅          | Nupp "Testi ühendust" kasutab puhverserverit    |
| Žetooni värskendamine | ✅          | Tausta OAuth uuendamine                         |
| Mudeli sünkroonimine  | ✅          | Mudelite loetlemine ja avastamine               |

---

## Puhverserveri register (CRUD)

Puhverserveri register on SQLite tabel (`proxy_registry`), mis salvestab kõik teie puhverserverid. Igal puhverserveril on:

| Väli       | Tüüp    | Kirjeldus                                           |
| ---------- | ------- | --------------------------------------------------- |
| `id`       | UUID    | Unikaalne identifikaator                            |
| `name`     | String  | Inimloetav silt                                     |
| `type`     | String  | Protokoll: `http`, `https`, `socks5`                |
| `host`     | String  | Puhverserveri hostinimi või IP                      |
| `port`     | Täisarv | Pordi number                                        |
| `username` | String  | Kasutajanimi autentimine (puhkeolekus krüpteeritud) |
| `password` | String  | Auth parool (puhkeolekus krüpteeritud)              |
| `region`   | String  | Geograafilise piirkonna silt                        |
| `notes`    | String  | Vabatekstilised märkmed                             |
| `status`   | String  | `active` või `inactive`                             |
| `source`   | String  | `manual` või `oneproxy`                             |

### Puhverserveri loomine

**Juhtpaneeli kaudu:**

1. Mine aadressile** Seaded → Proxy**
2. Klõpsake** Lisa puhverserver**
3. Sisestage tüüp, host, port ja valikulised autentimismandaadid
4. Salvesta

**API kaudu:**

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

### Puhverserveri värskendamine

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Märkus.** Mandaadid säilivad, välja arvatud juhul, kui saadate selgesõnaliselt mittetühje asendusi. Tühjade stringide saatmine `username`/`password` jaoks säilitab salvestatud väärtused.

### Puhverserveri kustutamine

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Nimekirja puhverserverid

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Puhverserverite määramine ulatustele

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

### Tõhusa puhverserveri lahendamine

Kontrollige, millist puhverserverit antud ühenduse jaoks kasutatakse:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Tagastab lahendatud puhverserveri koos selle taseme (`account`, `provider` või `global`) ja allikaga.

### Hulgiülesanne

Määrake üks puhverserver korraga mitmele pakkujale või ühendusele:

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

Puhverserverid on lisatud**Backup/Restore** süsteem. Kui ekspordite oma OmniRoute konfiguratsiooni:

1. Mine aadressile** Armatuurlaud → Seaded → Varundamine**
2. Klõpsake** Ekspordi** — puhverserveri register ja ülesanded on kaasas
3. Taastamiseks klõpsake nuppu** Import** ja laadige üles varukoopiafail

Toetab ka puhverserveri register** katkestas host + port** — kui impordite puhverserveri, mis on juba olemas (sama host ja port), värskendatakse seda duplikaadi loomise asemel.

### Pärandränne

Kui konfigureerisite puhverserverid vanemas versioonis (eelregistris), migreerib OmniRoute need automaatselt:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

See juhtub üks kord esimesel käivitamisel pärast täiendamist. Kasutage uuesti käivitamiseks `migrateLegacyProxyConfigToRegistry({ force: true })`.

---

## 1 puhverserveri tasuta puhverserveri turg

> 🆕** Panustas [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (probleem [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integreerub** [1 puhverserver](https://1proxy-api.aitradepulse.com)** kogukonna platvorm, millele juurdepääsu pakkuda** sadu tasuta kinnitatud puhverservereid** kogu maailmast. See sobib suurepäraselt kasutajatele, kellel pole oma puhverserveri infrastruktuuri.

### Kuidas see töötab

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sünkroonimine** — OmniRoute toob kinnitatud puhverserverid 1-puhverserverist API
2. **Kauplus** — Puhverserverid salvestatakse `source = 'oneproxy'`-ga samasse `proxy_registry` tabelisse
3. **Filter** — Filtreeri protokolli, riigi, kvaliteediskoori järgi
4. **Pööra** — Valige parim puhverserver, kasutades kvaliteetseid, juhuslikke või järjestikuseid strateegiaid
5. **Automaatne lagunemine** — Ebaõnnestunud puhverserverite kvaliteediskoor väheneb; alla läve → märgitud passiivseks

### Puhverserverite sünkroonimine

**Juhtpaneeli kaudu:**

1. Mine aadressile** Seaded → 1 puhverserver** sakk
2. Klõpsake** "Sünkrooni kohe"**
3. Vaata statistikat: puhverserverid kokku, aktiivsete arv, keskmine kvaliteet, jaotus riikide kaupa

**API kaudu:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Puhverserverite filtreerimine

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

### Puhverserveri kvaliteediskoorid

Igal 1-puhverserveril on metaandmed:

| Väli            | Kirjeldus                                          |
| --------------- | -------------------------------------------------- |
| `qualityScore`  | Hinnang 0–100 alates 1 puhverserveri kinnitamisest |
| `latencyMs`     | Mõõdetud võrgu latentsusaeg                        |
| `anonymity`     | `transparent`, `anonymous` või `elite`             |
| `googleAccess`  | Kas puhverserver pääseb juurde Google teenustele   |
| `countryCode`   | Kahetäheline ISO riigikood                         |
| `lastValidated` | Viimase kinnitamise ajatempel                      |

Kvaliteediskoore kohandatakse dünaamiliselt:

- **Ebaõnnestunud taotlused** vähendage punktisummat 10 punkti võrra
- **Tulemus langeb ≤ 10-ni** → puhverserver on tähistatud kui `inactive`
- Mitteaktiivsed puhverserverid jäetakse pööramisest välja

### Rotatsioonistrateegiad

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

### Kaitselüliti

1 puhverserveri sünkroonimisel on sisseehitatud kaitselüliti:

- Pärast** 5 järjestikust sünkroonimistõrget** , edasised sünkroonimiskatsed on blokeeritud
- Lähtestage: `resetOneproxyCircuitBreaker()` või taaskäivitage server
- Sünkroonimise olek on saadaval aadressil `GET /api/settings/oneproxy?action=status`

### 1 puhverserveri tühjendamine

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Tuvastamisvastane ja varjamine

OmniRoute ei suuna liiklust ainult puhverserveri — kaudu, vaid muudab liikluse seaduslikuks:

### TLS Sõrmejälgede võltsimine

Kasutab `wreq-js` brauserilaadsete TLS -sõrmejälgede genereerimiseks, jättes mööda robotituvastussüsteemidest, mis märgivad mitte-brauseri TLS käepigistusi.

### CLI sõrmejälgede sobitamine

The**CLI sõrmejälje lüliti** (`Settings → Security`) järjestab HTTP päised ja JSON kehaväljad ümber, et need vastaksid natiivsete CLI kahendfailide täpsele signatuurile (Claude Code, Codex jne). See toimib** peal** puhverserver:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Sa saad mõlemad**IP maskeerimine** ja** taotleda autentsust** samaaegselt.

### Proxy IP säilitamine

Armatuurlaual olevad värvikoodiga märgid näitavad, milline puhverserveri tase on aktiivne:

| Märk | Tase      | Tähendus                                               |
| ---- | --------- | ------------------------------------------------------ |
| 🟢   | Globaalne | Kogu liiklus käib läbi selle puhverserveri             |
| 🟡   | Pakkuja   | Ainult selle teenusepakkuja liiklus on puhverserver    |
| 🔵   | Ühendus   | See konkreetne key/account kasutab seda puhverserverit |

Märk näitab ka kinnitamiseks lahendatud puhverserverit IP.

---

## Ülesvoolu puhverserveri režiimid

Pakkujate puhul, kes kasutavad CLIProxyAPI mustrit, toetab OmniRoute kolme ülesvoolu puhverserveri režiimi.

| Režiim        | Kirjeldus                                                       |
| ------------- | --------------------------------------------------------------- |
| `native`      | OmniRoute käsitleb puhverserveri marsruutimist otse (vaikimisi) |
| `cliproxyapi` | Delegeerib välisele CLIProxyAPI eksemplarile                    |
| `fallback`    | Proovib esmalt natiivset, langeb tagasi CLIProxyAPI             |

Konfigureerige teenusepakkuja kaupa:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Armatuurlaud UI

### Seaded → Puhverserveri vahekaart

- **Globaalne puhverserver** konfiguratsioon (seatud üks kord kogu liikluse jaoks)
- **Pakkuja puhverserver** alistab
- **Ühendusepõhine puhverserver** ülesandeid
- **Ühenduse test** konfigureeritud puhverserveri kaudu
- **Värvikoodiga märgid** näitab aktiivse puhverserveri taset

### Seaded → 1proxy Tab

- **Sünkrooni kohe** nuppu tasuta puhverserveri hankimiseks
- **Statistika kaardid** : Kokku, Aktiivne, Keskmine kvaliteet, Viimane sünkroonimine
- **Filtrid** : Protokoll, Riigikood, Minimaalne kvaliteet
- **Puhverserveri tabel** hosti, protokolli, riigi, kvaliteediskoori, latentsuse, anonüümsuse, Google juurdepääsuga
- **Sünkroonimise olek** success/failure jälgimise ja järjestikuste rikete loendusega paneel
- **Kustuta kõik** kõigi 1 puhverserveri kirjete eemaldamiseks

---

## API viide

### Puhverserveri seaded API

| meetod   | Lõpp-punkt                                     | Kirjeldus                                     |
| -------- | ---------------------------------------------- | --------------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Hankige puhverserveri täielik konfiguratsioon |
| `GET`    | `/api/settings/proxy?level=global`             | Hangi globaalne puhverserver                  |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Hankige teenusepakkuja puhverserver           |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Tõhusa puhverserveri lahendamine              |
| `PUT`    | `/api/settings/proxy`                          | Värskenda puhverserveri konfiguratsiooni      |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Eemaldage tasemel puhverserver                |

### Puhverserveri register API

| meetod   | Lõpp-punkt                                        | Kirjeldus                        |
| -------- | ------------------------------------------------- | -------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Loetlege kõik puhverserverid     |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Hankige ID puhverserver          |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Hankige puhverserveri ülesandeid |
| `POST`   | `/api/v1/management/proxies`                      | Loo puhverserver                 |
| `PATCH`  | `/api/v1/management/proxies`                      | Värskenda puhverserverit         |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Kustuta puhverserver             |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Sundkustutamine                  |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Hulgimääramine                   |
| `GET`    | `/api/v1/management/proxies/assignments`          | Loetle ülesanded                 |
| `GET`    | `/api/v1/management/proxies/health`               | Puhverserveri tervisestatistika  |

### Tunnelid API

Kui soovite puhverserveri kaudu väljamineva marsruutimise asemel oma OmniRoute eksemplari avada avalikule Internetile (Cloudflare/ngrok/Tailscale), vaadake [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunnel REST API asub `/api/tunnels/{cloudflared,ngrok,tailscale}/*` all ja on ülalkirjeldatud väljuva puhverserveri ahelaga ortogonaalne.

### 1 puhverserver API

| meetod   | Lõpp-punkt                             | Kirjeldus                               |
| -------- | -------------------------------------- | --------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Loetlege 1 puhverserver                 |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Hankige statistika + sünkroonimise olek |
| `GET`    | `/api/settings/oneproxy?action=status` | Hankige ainult sünkroonimise olek       |
| `POST`   | `/api/settings/oneproxy`               | Päästiku sünkroonimine                  |
| `POST`   | `/api/settings/oneproxy/rotate`        | Pöörake järgmisele puhverserverile      |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Kustuta üks                             |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Tühjenda kõik                           |

### Ülesvoolu puhverserver API

| meetod   | Lõpp-punkt                        | Kirjeldus                                       |
| -------- | --------------------------------- | ----------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Hangi ülesvoolu puhverserveri konfiguratsioon   |
| `PUT`    | `/api/upstream-proxy/:providerId` | Seadistage ülesvoolu puhverserveri režiim       |
| `DELETE` | `/api/upstream-proxy/:providerId` | Eemalda ülesvoolu puhverserveri konfiguratsioon |

---

## Keskkonnamuutujad

| Muutuv                | Vaikimisi | Kirjeldus                                                      |
| --------------------- | --------- | -------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`    | Enable SOCKS5 proxy support (default `true` in `.env.example`) |

---

## Veaotsing

### "SOCKS5 puhverserver on keelatud"

Määrake oma `.env` failis `ENABLE_SOCKS5_PROXY=true` ja taaskäivitage.

### "pistikupesa üles riputamine" vead puhverserveri kaudu

See on normaalne odavate puhverserverite puhul, mis katkestavad tühikäiguühendused. OmniRoute juba tegeleb sellega:

- Puhverserveri ühendustel elushoidmise keelamine (`keepAliveTimeout: 1`)
- Torujuhtmete ühendamise keelamine (`pipelining: 0`)
- Dispetšerite vahemällu salvestamine korduvate käepigistuste vältimiseks

Kui see püsib, proovige teist puhverserverit või kasutage 1 puhverserveri pööramise funktsiooni.

### "unsupported_country_region_territoorium" OAuth ajal

Veenduge, et puhverserver on konfigureeritud** enne** OAuth voolu käivitamine. OmniRoute suunab OAuth märgivahetuse konfigureeritud puhverserveri kaudu. Esmalt määrake globaalne või pakkujataseme puhverserver ja seejärel looge ühendus.

### Puhverserverit ei kasutata

Kontrollige resolutsiooni järjekorda:

1. Kinnitage `GET /api/settings/proxy?resolve=your-connection-id`
2. Kontrollige, kas puhverserver `status` on `active` (mitte `inactive`)
3. Veenduge, et puhverserveri määramise ulatus vastaks teie ühendusele

### 1 puhverserveri sünkroonimine ebaõnnestus

Kontrollige sünkroonimise olekut:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Kui `consecutiveFailures >= 5`, on kaitselüliti rakendunud. Lähtestamiseks taaskäivitage server või oodake käsitsi lähtestamist.

---

## Andmebaasi skeem

### `proxy_registry` tabel

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

### `proxy_assignments` tabel

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

## Puhverserveri tervisekontroll (v3.8.16 +)

OmniRoute's** puhverserveri kiire ebaõnnestumine** mehhanism (`src/lib/proxyHealth.ts`) tuvastab < 2s surnud puhverserverid kiire TCP -ühenduse kontrollimise kaudu, seejärel** salvestab tulemuse vahemällu** päringupõhise üldkulude vältimiseks.

### Kuidas see töötab

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

Ilma selleta blokeeriks surnud puhverserver kõik täieliku `PROXY_TIMEOUT_MS` taotlused (vaikimisi 30 sekundit), enne kui see ebaõnnestub.

### Häälestatavad keskkonnamuutujad

| Muutuv                       | Vaikimisi | Eesmärk                                          |
| ---------------------------- | --------- | ------------------------------------------------ |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`    | TCP ühenduse ajalõpp tervisekontrolli kohta      |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`   | Kui kaua tervisetulemus on vahemällu salvestatud |

**Soovitatavad väärtused:**

| Stsenaarium                      | Kiire ebaõnnestumise ajalõpp | Vahemälu TTL | Arutluskäik                                                                   |
| -------------------------------- | ---------------------------- | ------------ | ----------------------------------------------------------------------------- |
| Suure läbilaskevõimega API värav | 1500 ms                      | 60 000 ms    | Agressiivne tõrkekindel, pikem vahemälu kontrollide vähendamiseks             |
| Geo-jaotatud sõlmed              | 3000 ms                      | 15000 ms     | Aeglasemad võrgud vajavad rohkem aega; lühem vahemälu kiireks tõrkevahetuseks |
| Arendaja / testimine             | 1000 ms                      | 10000 ms     | Kiire iteratsioon kohalikel puhverserveritel                                  |
| Stealth / anti-tuvastus          | 2500 ms                      | 45000 ms     | Vältige kiiret sondeerimist, mis võib käivitada kiiruse piirid                |

### Puhverserveri tervise kontrollimine

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

`stale` lipp on `true`, kui vahemälu kirje on ületanud `HEALTH_CACHE_TTL_MS` ja järgmine päring käivitab uue kontrolli.

### Puhverserveri tüübi vaikesätted

Tervisekontrollis kasutatakse mõistlikke vaikeväärtusi, mis põhinevad URL skeemil:

| Skeem                      | Vaikimisi port |
| -------------------------- | -------------- |
| `http://`                  | 8080           |
| `https://`                 | 443            |
| `socks5://` / `socks5h://` | 1080           |

URL (`http://host:9999`) kohandatud pordid on alati skeemi vaikeseadete suhtes ülimuslikud.

---

## Puhverserveri analüüs ja jälgitavus

OmniRoute jälgib puhverserveri kasutamist, et aidata operaatoritel diagnoosida marsruutimise mustreid, latentsusaegu ja korduvaid tõrkeid.

### Mida jälgitakse

Iga konfigureeritud puhverserveri kaudu tehtud päringu puhul salvestab OmniRoute :

| Mõõdik       | Kirjeldus                                                    |
| ------------ | ------------------------------------------------------------ |
| `proxy_url`  | Täielik puhverserver URL (maskitud autentimismandaatidega)   |
| `provider`   | Ülesvoolu pakkuja ID (openai, antroopne jne)                 |
| `latency_ms` | Edasi-tagasi reisi koguaeg koos puhverserveri käepigistusega |
| `connect_ms` | TCP ainult ühenduse aeg                                      |
| `status`     | HTTP olekukood ülesvoolust                                   |
| `error`      | Kui päring ebaõnnestus, määrake veaklass                     |
| `timestamp`  | ISO 8601 UTC                                                 |

### Juurdepääs andmetele

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Tegelik lõpp-punkt on `/api/usage/proxy-logs` (vt `src/app/api/usage/proxy-logs/route.ts`). See lõpp-punkt toetab:

- `GET /api/usage/proxy-logs` — toodab puhverserveri logisid
- `DELETE /api/usage/proxy-logs` — tühjendage kõik puhverserveri logid

Koondstatistikat saab vajadusel otse `proxy_logs` tabelist SQL kaudu küsida. Armatuurlaud UI võib pakkuda koondvaateid.

### Levinud mustrid

**Tuvastage puhverserver** (vaheldub success/failure vahel):

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

**Leidke aeglased puhverserverid** (p95 latentsusaeg > 2s):

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

## Rotatsioonistrateegia otsustuspuu

Kui ulatusele on määratud mitu puhverserverit, kasutab OmniRoute a** rotatsioonistrateegia** et valida, millist iga päringu jaoks kasutada. Strateegia on konfigureeritud ulatuse tasemel (ülemaailmne, teenusepakkujapõhine, kontopõhine, kombinatsioonipõhine).

### Saadaolevad strateegiad

| strateegia            | Millal kasutada                             | Kompromiss                                                                             |
| --------------------- | ------------------------------------------- | -------------------------------------------------------------------------------------- |
| `quality` (vaikimisi) | Tootmine segakvaliteediga puhverserveritega | Soosib kõrge reitinguga puhverservereid; võivad madala reitinguga inimesed nälga jääda |
| `random`              | Koormuse jaotus, privaatsus                 | Ühtlane jaotus; ignoreerib kvaliteedisignaale                                          |
| `sequential`          | Silumine, deterministlik testimine          | Tsüklite järjekorras läbi puhverserverid; lihtne arutleda                              |

### Otsuste puu

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

## Automaatne rikete välistamine teie enda puhverserveritele

1-puhverserveri turukogum degradeerib juba automaatselt ebaõnnestunud puhverserverid iseseisvalt (vt [puhverserveri kvaliteediskoorid](#proxy-quality-scores) ). Puhverserveritele** sina** Registrisse lisatuna pakub tausta tervise ajakava (`src/lib/proxyHealth/scheduler.ts`) sama käitumist "välja surnud liige automaatselt ketist välja" ilma midagi kustutamata:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Kuidas see sobib mitme puhverserveri ahelasse:

1. Planeerija uurib iga registreeritud puhverserverit iga `PROXY_HEALTH_INTERVAL_MS` järel (vaikimisi 10 min; minimaalselt 1 min).
2. Pärast `PROXY_AUTO_REMOVE_AFTER` järjest** veenev** tõrkeid (tõeline ühenduse tõrge — ajalõpp või sondi sihtmärgi enda 5xx ei lähe kunagi arvesse, vt [Puhverserveri tervisekontroll](#proxy-health-checking-v3816) ), puhverserveri `status` on seatud väärtusele `dead`.
3. `dead` on üks olekutest, mille pool/rotation eraldusvõimega kasutatav elusoleku filter välistab, seega peatab ulatuse pööramine (ümber-robin / juhuslik / kleepuv / latentsus — vt [Rotation Strategy Decision Tree](#rotation-strategy-decision-tree) ) koheselt selle puhverserveri edastamise uutele päringutele. Ühtegi teist puhverserverit basseinis see ei mõjuta ja kogu bassein ei lange kunagi vaikselt tagasi otseühendusse — vt [4-tasemelise puhverserveri süsteemi](#4-level-proxy-system) tõrkesulgemise kaitset.
4. Planeerija uurib `dead` puhverservereid samal intervallil. Järgmine edukas sond pöörab `status` tagasi `active` ja see siseneb uuesti pöörlemisse — käsitsi uuesti lisamist pole vaja.

See on meelega** opt-in ja mittepurustavad** : vaikimisi loendab ja logib planeerija ainult tõrkeid (vt poliitikat C jaotises `decision.ts`) ja `PROXY_AUTO_DISABLE` ei kustuta kunagi rida — selleks on eraldiseisev, agressiivsem `PROXY_AUTO_REMOVE` lipp. Kui mõlemad on seatud väärtusele `true`, võidab `PROXY_AUTO_REMOVE` (kustutaval puhverserveril pole vahepealset pehmet keelamist kasu). Täieliku muutujate loendi leiate viitest [Environment Config](../reference/ENVIRONMENT.md).

---

> 📖** Seotud dokumentatsioon:**
>
> - [Kasutusjuhend](../guides/USER_GUIDE.md) — Üldine häälestus ja konfiguratsioon – [API Viide](../reference/API_REFERENCE.md) — Täielik API dokumentatsioon – [Keskkonna konfiguratsioon](../reference/ENVIRONMENT.md) — Kõik keskkonnamuutujad
