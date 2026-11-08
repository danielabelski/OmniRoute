# 🌐 OmniRoute Proxy Guide (Magyar)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Kerülje meg a földrajzi blokkokat, védje meg személyazonosságát, és irányítsa AI forgalmat bármely — proxy-n keresztül, anélkül, hogy a konfiguráció bonyolult.**

OmniRoute tartalmaz egy teljes funkcionalitású proxykezelő rendszert, amely lehetővé teszi AI szolgáltató felfelé irányuló forgalmának HTTP, HTTPS vagy SOCKS5 proxykon keresztül történő irányítását. Függetlenül attól, hogy blokkolt régióban tartózkodik, IP forgatásra van szüksége, vagy lopakodó — ujjlenyomatot szeretne venni, ez az útmutató mindenre kiterjed.

---

## Tartalomjegyzék

- [Miért használjunk proxykat?](#why-use-proxies)
- [Építészet áttekintése](#architecture-overview)
- [4 szintű proxy rendszer](#4-level-proxy-system)
- [Proxy Registry (CRUD)](#proxy-registry-crud)
- [1proxy ingyenes piactér](#1proxy-free-proxy-marketplace)
- [Proxy forgatás](#proxy-rotation)
- [Anti-Detection & Stealth](#anti-detection--stealth)
- [Upstream proxy módok](#upstream-proxy-modes)
- [Műszerfal UI](#dashboard-ui)
- [API Referencia](#api-reference)
- [Környezeti változók](#environment-variables)
- [Hibaelhárítás](#troubleshooting)

---

## Miért használjunk proxykat?

Sok AI szolgáltató földrajzi régió szerint korlátozza a hozzáférést. Fejlesztők itt** Oroszország, Kína, Irán, Kuba, Törökország** , és más országokban olyan hibák jelentkeznek, mint:

```
unsupported_country_region_territory
```

A proxyk még a blokkolt régiókon kívül is hasznosak:

| Használati eset      | Leírás                                                                          |
| -------------------- | ------------------------------------------------------------------------------- |
| **Földrajzi kitérő** | Hozzáférés OpenAI, Anthropic, Codex, Copilot eléréséhez a letiltott országokból |
| **IP forgás**        | Ossza el a kéréseket több IPs között, hogy elkerülje a sebességkorlátozást      |
| **Magánélet**        | Rejtse el valódi IP ját az upstream szolgáltatók elől                           |
| **Megfelelés**       | A forgalom meghatározott joghatóságokon keresztül történő átirányítása          |
| **Tesztelés**        | Szimulálja a különböző régiókból érkező kéréseket                               |

---

## Építészet áttekintése

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

### Kulcsfontosságú komponensek

| Összetevő                     | Fájl                                         | Szerep                                                                |
| ----------------------------- | -------------------------------------------- | --------------------------------------------------------------------- |
| **Proxy Registry**            | `src/lib/db/proxies.ts`                      | CRUD proxy bejegyzésekhez + hatókör hozzárendelésekhez                |
| **Meghatalmazott diszpécser** | `open-sse/utils/proxyDispatcher.ts`          | `undici` ProxyAgent/SOCKS diszpécsereket hoz létre gyorsítótárazással |
| **Proxy letöltése**           | `open-sse/utils/proxyFetch.ts`               | `fetch()` becsomagolja proxy diszpécser injekcióval                   |
| **Beállítások Útvonal**       | `src/app/api/settings/proxy/route.ts`        | Legacy proxy config API (GET/PUT/DELETE)                              |
| **Menedzsment útvonal**       | `src/app/api/v1/management/proxies/route.ts` | Registry CRUD API (GET/POST/PATCH/DELETE)                             |
| **1 proxy DB**                | `src/lib/db/oneproxy.ts`                     | Ingyenes proxy piactér kitartása                                      |

---

## Alapértelmezett proxy állapot az új fiókokhoz

In** Beállítások → Proxy → Globális konfiguráció** , használja** Alapértelmezés szerint engedélyezze a proxyt az új kapcsolatokhoz** az újonnan hozzáadott szolgáltatói fiókok kezdeti proxyállapotának kiválasztásához.

Az új beállítás szabályozza az újonnan hozzáadott szolgáltatói fiókok kezdeti proxy állapotát. Nem módosítja a meglévő fiókokat, és nem cseréli le a globális proxykapcsolót. Kezdeti értéke megőrzi a korábbi viselkedést. Kapcsolja ki egyszer, ha jövőbeli fiókokat szeretne létrehozni úgy, hogy a proxy alapértelmezés szerint le van tiltva.

A preferenciát a `defaultNewConnectionProxyEnabled` néven tárolja a meglévő API beállításokon keresztül. Alapértelmezés szerint `true`, amikor soha nem menti. `false` mentése a következő új fiókoknál újraindítás nélkül lép életbe. `POST /api/providers` elfogad egy opcionális szigorú logikai `proxyEnabled`; az explicit `true` vagy `false` elsőbbséget élvez a létrehozási alapértelmezett értékkel szemben. A duplikált fiók kihagyása vagy OAuth reconnect megőrzi a fiók tárolt állapotát. Az egyéni fiókok ezután is engedélyezhetők vagy letilthatók.

A szelektív szolgáltatói átvitel a céltelepítés alapértelmezett beállításait használja az új fiókokhoz, és megőrzi a célházirendet a meglévő fiókok cseréjekor. A proxy kapcsolók nem hordozható átviteli mezők. A teljes biztonsági másolat-visszaállítás és a történelmi JSON/SQL -migráció megtartja meglévő visszaállítási szemantikáját, beleértve a mentett fiókértékeket és a régi séma alapértelmezett beállításait; a beállítások teljes visszaállítása is visszaállíthatja ezt a preferenciát.

Ez a beállítás nem rendel hozzá proxyt, és nem állapítja meg, hogy az egészséges vagy használatban van-e. A tényleges útválasztás továbbra is a globális proxykapcsolótól és az alkalmazandó proxykonfigurációtól függ. A megőrzött fiók nélküli szintetikus szolgáltatók, a fiók létrehozása előtti OAuth forgalom, environment/system proxy-k és a külső háttérrendszerek hálózata nem tartozik a hatálya alá.

## 4 szintű proxy rendszer

OmniRoute támogatja a proxykonfigurációt a címen** négy független szkóp** , prioritási sorrendben megoldva:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Hogyan működik a felbontás

Amikor OmniRoute kérelmet küld egy upstream szolgáltatónak, meghívja `resolveProxyForConnectionFromRegistry()`, amely sorrendben ellenőrzi az egyes szinteket:

1. **Fiókszintű** — Van proxy hozzárendelve ehhez a konkrét ID kapcsolathoz?
2. **Szolgáltatói szintű** — Hozzá van rendelve proxy ehhez a szolgáltatóhoz (pl. `openai`)?
3. **Globális szinten** — Van globális proxy konfigurálva?
4. **Nincs proxy** — Közvetlen kapcsolat a szolgáltatóval.

Az első meccs nyer. Ez azt jelenti, hogy beállíthat egy globális proxyt tartalékként, de felülírhatja azt bizonyos szolgáltatók vagy kapcsolatok esetén.

### Mit kap proxyként

| Forgalom típusa       | Meghatalmazott? | Megjegyzések                                    |
| --------------------- | --------------- | ----------------------------------------------- |
| Csevegés befejezése   | ✅              | Minden `/v1/chat/completions` kérés             |
| Beágyazások           | ✅              | `/v1/embeddings`                                |
| Képgenerálás          | ✅              | `/v1/images/generations`                        |
| Hang (TTS/STT)        | ✅              | `/v1/audio/*`                                   |
| OAuth tokencsere      | ✅              | Megoldja `unsupported_country_region_territory` |
| Csatlakozási tesztek  | ✅              | A "Kapcsolat tesztelése" gomb proxyt használ    |
| Token frissítése      | ✅              | Háttér OAuth megújulás                          |
| Modell szinkronizálás | ✅              | Modell listázás és felfedezés                   |

---

## Proxy Registry (CRUD)

A proxy-nyilvántartás egy SQLite tábla (`proxy_registry`), amely az összes proxyt tárolja. Minden proxy rendelkezik:

| Mező       | Írja be    | Leírás                                                      |
| ---------- | ---------- | ----------------------------------------------------------- |
| `id`       | UUID       | Egyedi azonosító                                            |
| `name`     | Húr        | Ember által olvasható címke                                 |
| `type`     | Húr        | Protokoll: `http`, `https`, `socks5`                        |
| `host`     | Húr        | Proxy gazdagépnév vagy IP                                   |
| `port`     | Egész szám | Port száma                                                  |
| `username` | Húr        | Felhasználónév hitelesítés (nyugalmi állapotban titkosítva) |
| `password` | Húr        | Hitelesítési jelszó (nyugalmi állapotban titkosítva)        |
| `region`   | Húr        | Földrajzi régió címke                                       |
| `notes`    | Húr        | Szabad szövegű jegyzetek                                    |
| `status`   | Húr        | `active` vagy `inactive`                                    |
| `source`   | Húr        | `manual` vagy `oneproxy`                                    |

### Proxy létrehozása

**Az irányítópulton keresztül:**

1. Menj ide** Beállítások → Proxy**
2. Kattintson** Proxy hozzáadása**
3. Adja meg a típust, a gazdagépet, a portot és az opcionális hitelesítési adatokat
4. Megtakarítás

**API keresztül:**

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

### Proxy frissítése

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Jegyzet:** A hitelesítési adatok megmaradnak, hacsak nem küld kifejezetten nem üres pótlásokat. `username`/`password` üres karakterláncainak elküldése megtartja a tárolt értékeket.

### Proxy törlése

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Listázási proxyk

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Proxyk hozzárendelése hatókörhöz

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

### A hatékony proxy feloldása

Ellenőrizze, hogy egy adott kapcsolathoz melyik proxy kerül felhasználásra:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Visszaadja a feloldott proxyt a szintjével (`account`, `provider` vagy `global`) és a forrással együtt.

### Tömeges kiosztás

Egy proxy hozzárendelése több szolgáltatóhoz vagy kapcsolathoz egyszerre:

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

A proxyk benne vannak a**Backup/Restore** rendszer. A OmniRoute konfiguráció exportálásakor:

1. Menj ide** Irányítópult → Beállítások → Biztonsági mentés**
2. Kattintson** Export** — proxy registry és hozzárendelések szerepelnek benne
3. A visszaállításhoz kattintson a gombra** Importálás** és töltse fel a biztonsági másolatot

A proxy registry is támogatja** a gazdagép + portja által feltöltve** — ha már létező proxyt importál (ugyanaz a gazdagép és port), akkor a duplikáció létrehozása helyett frissít.

### Örökségi migráció

Ha a proxykat egy régebbi verzióban (előzetes regisztrációs adatbázisban) konfigurálta, OmniRoute automatikusan migrálja őket:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Ez egyszer történik meg a frissítés utáni első indításkor. Használja `migrateLegacyProxyConfigToRegistry({ force: true })` az újrafutáshoz.

---

## 1proxy Ingyenes proxy piactér

> 🆕** Közreműködött: [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) ( [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) probléma)

OmniRoute integrálódik a** [1 proxy](https://1proxy-api.aitradepulse.com)** közösségi platform, amelyhez hozzáférést biztosít** több száz ingyenes, ellenőrzött proxy** a világ minden tájáról. Ez tökéletes azoknak a felhasználóknak, akik nem rendelkeznek saját proxy infrastruktúrával.

### Hogyan működik

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Szinkronizál** — OmniRoute lekéri az érvényesített proxykat az 1proxy API ről
2. **Bolt** — A proxykat ugyanabba a `proxy_registry` táblába menti a rendszer, mint `source = 'oneproxy'`
3. **Szűrő** — Szűrés protokoll, ország, minőségi pontszám szerint
4. **Forog** — Válassza ki a legjobb proxyt minőségi, véletlenszerű vagy szekvenciális stratégiák használatával
5. **Automatikus lebontás** — A sikertelen proxyk minőségi pontszámuk csökken; küszöb alatti → inaktívként van megjelölve

### Proxyk szinkronizálása

**Az irányítópulton keresztül:**

1. Menj ide** Beállítások → 1proxy** lapon
2. Kattintson** "Szinkronizálás most"**
3. Statisztikák megtekintése: összes proxy, aktív szám, átlagos minőség, országonkénti bontás

**API keresztül:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Proxyk szűrése

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

### Proxy minőségi pontszámok

Minden 1proxy proxyhoz metaadatok tartoznak:

| Mező            | Leírás                                      |
| --------------- | ------------------------------------------- |
| `qualityScore`  | 0-100 értékelés 1proxy érvényesítésből      |
| `latencyMs`     | Mért hálózati késleltetés                   |
| `anonymity`     | `transparent`, `anonymous` vagy `elite`     |
| `googleAccess`  | A proxy hozzáfér-e Google szolgáltatásokhoz |
| `countryCode`   | Kétbetűs ISO országkód                      |
| `lastValidated` | Az utolsó érvényesítés időbélyege           |

A minőségi pontszámok dinamikusan korrigálódnak:

- **Sikertelen kérések** csökkentse a pontszámot 10 ponttal
- **A pontszám ≤ 10-re csökken** → proxy `inactive` jelölésű
- Az inaktív proxyk ki vannak zárva a forgatásból

### Rotációs stratégiák

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

### Áramköri megszakító

Az 1proxy szinkron beépített megszakítóval rendelkezik:

- Után** 5 egymást követő szinkronizálási hiba** , a további szinkronizálási kísérletek le vannak tiltva
- Állítsa vissza a következővel: `resetOneproxyCircuitBreaker()` vagy indítsa újra a szervert
- A szinkronizálási állapot a `GET /api/settings/oneproxy?action=status` oldalon érhető el

### 1proxy proxyk törlése

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-Detection & Stealth

OmniRoute nem csak egy proxy — keresztül irányítja a forgalmat, hanem legitimnek tűnik:

### TLS Ujjlenyomat-hamisítás

`wreq-js` segítségével böngészőszerű TLS ujjlenyomatokat generál, megkerülve a nem böngésző TLS kézfogásait jelző botészlelő rendszereket.

### CLI Ujjlenyomat-illesztés

A**CLI ujjlenyomat kapcsoló** (`Settings → Security`) átrendezi HTTP fejléceket és JSON törzsmezőket, hogy megfeleljenek a natív CLI binárisok (Claude kód, Codex stb.) pontos aláírásának. Ez működik** tetején** a proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Mindkettőt megkapod**IP maszkolás** és** hitelességet kérni** egyidejűleg.

### Proxy IP megőrzése

Az irányítópulton színkódolt jelvények mutatják, hogy melyik proxyszint aktív:

| Jelvény | Szint       | Jelentése                                                 |
| ------- | ----------- | --------------------------------------------------------- |
| 🟢      | Globális    | Az összes forgalom ezen a proxyn keresztül megy keresztül |
| 🟡      | Szolgáltató | Csak ennek a szolgáltatónak a forgalma proxyzott          |
| 🔵      | Kapcsolat   | Ez a konkrét key/account ezt a proxyt használja           |

A jelvényen az ellenőrzéshez szükséges megoldott proxy IP is látható.

---

## Upstream proxy módok

A CLIProxyAPI mintát használó szolgáltatók esetében OmniRoute három upstream proxy módot támogat:

| Mód           | Leírás                                                              |
| ------------- | ------------------------------------------------------------------- |
| `native`      | OmniRoute közvetlenül kezeli a proxy-útválasztást (alapértelmezett) |
| `cliproxyapi` | Külső CLIProxyAPI példányhoz delegál                                |
| `fallback`    | Először natíval próbálkozik, visszaesik CLIProxyAPI ra              |

Konfigurálás szolgáltatónként:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Műszerfal UI

### Beállítások → Proxy Tab

- **Globális proxy** konfiguráció (egyszer beállítva az összes forgalomhoz)
- **Szolgáltatónkénti proxy** felülírja
- **Kapcsolatonkénti proxy** feladatokat
- **Csatlakozási teszt** konfigurált proxy segítségével
- **Színes jelvények** aktív proxyszintet mutat

### Beállítások → 1proxy Tab

- **Szinkronizálás most** gombot az ingyenes proxyk lekéréséhez
- **Statisztikai kártyák** : Összes, Aktív, Átl. minőség, Utolsó szinkron
- **Szűrők** : Protokoll, Országkód, Minimális minőség
- **Proxy táblázat** gazdagéppel, protokollal, országgal, minőségi pontszámmal, késleltetéssel, névtelenséggel, Google hozzáféréssel
- **Szinkronizálás állapota** panel success/failure követéssel és egymást követő hibaszámlálással
- **Összes törlése** az összes 1proxy bejegyzés eltávolításához

---

## API Referencia

### Proxy beállítások API

| Módszer  | Végpont                                        | Leírás                                 |
| -------- | ---------------------------------------------- | -------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Töltse le a teljes proxy konfigurációt |
| `GET`    | `/api/settings/proxy?level=global`             | Szerezzen be globális proxyt           |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Szerezze be a szolgáltatói proxyt      |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Hatékony proxy feloldása               |
| `PUT`    | `/api/settings/proxy`                          | Frissítse a proxy konfigurációját      |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Távolítsa el a proxyt a szinten        |

### Proxy Registry API

| Módszer  | Végpont                                           | Leírás                           |
| -------- | ------------------------------------------------- | -------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Sorolja fel az összes proxyt     |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Proxy beszerzése a ID            |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Proxy-hozzárendelések beszerzése |
| `POST`   | `/api/v1/management/proxies`                      | Proxy létrehozása                |
| `PATCH`  | `/api/v1/management/proxies`                      | Frissítse a proxyt               |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Proxy törlése                    |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Törlés kényszerítése             |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Tömeges hozzárendelés            |
| `GET`    | `/api/v1/management/proxies/assignments`          | Feladatok listázása              |
| `GET`    | `/api/v1/management/proxies/health`               | Proxy egészségügyi statisztika   |

### Alagutak API

Ha OmniRoute példányt a nyilvános internetnek (Cloudflare/ngrok/Tailscale) szeretné megjeleníteni a proxyn keresztüli kimenő útválasztás helyett, tekintse meg [TUNNELS_GUIDE.md fájlt](./TUNNELS_GUIDE.md). A REST API alagút `/api/tunnels/{cloudflared,ngrok,tailscale}/*` alatt található, és merőleges a fent dokumentált kimenő proxyláncra.

### 1 proxy API

| Módszer  | Végpont                                | Leírás                                  |
| -------- | -------------------------------------- | --------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Soroljon fel 1 proxy proxyt             |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Statisztikák + szinkronizálási állapota |
| `GET`    | `/api/settings/oneproxy?action=status` | Csak a szinkronizálási állapot lekérése |
| `POST`   | `/api/settings/oneproxy`               | Trigger szinkronizálás                  |
| `POST`   | `/api/settings/oneproxy/rotate`        | Forgatás a következő proxyra            |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Törölj egyet                            |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Minden törlése                          |

### Upstream Proxy API

| Módszer  | Végpont                           | Leírás                                        |
| -------- | --------------------------------- | --------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Szerezze be az upstream proxy konfigurációját |
| `PUT`    | `/api/upstream-proxy/:providerId` | Állítsa be az upstream proxy módot            |
| `DELETE` | `/api/upstream-proxy/:providerId` | Távolítsa el az upstream proxybeállítást      |

---

## Környezeti változók

| Változó               | Alapértelmezett | Leírás                                                                         |
| --------------------- | --------------- | ------------------------------------------------------------------------------ |
| `ENABLE_SOCKS5_PROXY` | `true`          | SOCKS5 proxy támogatás engedélyezése (alapértelmezett `true` a `.env.example`) |

---

## Hibaelhárítás

### "SOCKS5 proxy le van tiltva"

Állítsa be `ENABLE_SOCKS5_PROXY=true` `.env` fájlban, és indítsa újra.

### "Socket hang up" hibák proxyn keresztül

Ez normális az olcsó proxykkal, amelyek megszakítják a tétlen kapcsolatokat. OmniRoute ezt már kezeli:

- Az életben tartás letiltása a proxykapcsolatokon (`keepAliveTimeout: 1`)
- Csővezetékezés letiltása (`pipelining: 0`)
- A diszpécserek gyorsítótárazása az ismételt kézfogások elkerülése érdekében

Ha továbbra is fennáll, próbáljon ki egy másik proxyt, vagy használja az 1proxy rotációs funkciót.

### "nem támogatott_ország_régió_területe" OAuth során

Győződjön meg arról, hogy a proxy be van állítva** előtt** elindítva a OAuth áramlást. OmniRoute OAuth tokencserét a konfigurált proxyn keresztül irányítja. Először állítson be egy globális vagy szolgáltatói szintű proxyt, majd csatlakozzon.

### A proxy nincs használatban

Ellenőrizze a felbontás sorrendjét:

1. Ellenőrizze `GET /api/settings/proxy?resolve=your-connection-id`
2. Ellenőrizze, hogy a `status` proxy `active` (nem `inactive`)
3. Győződjön meg arról, hogy a proxy-hozzárendelési hatókör megegyezik a kapcsolattal

### 1 proxy szinkronizálási hiba

Ellenőrizze a szinkronizálás állapotát:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Ha `consecutiveFailures >= 5`, akkor a megszakító kioldott. Indítsa újra a kiszolgálót a visszaállításhoz, vagy várja meg a kézi visszaállítást.

---

## Adatbázis séma

### `proxy_registry` táblázat

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

### `proxy_assignments` táblázat

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

## Proxy állapotának ellenőrzése (v3.8.16 +)

OmniRoute's** proxy gyors sikertelen** mechanizmus (`src/lib/proxyHealth.ts`) gyors TCP kapcsolatellenőrzéssel észleli a halott proxykat < 2s-ben, majd** gyorsítótárazza az eredményt** kérésenkénti rezsi elkerülése érdekében.

### Hogyan működik

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

E nélkül egy halott proxy blokkolna minden kérést a teljes `PROXY_TIMEOUT_MS` ra (alapértelmezett 30 másodperc), mielőtt meghiúsulna.

### Hangolható környezeti változók

| Változó                      | Alapértelmezett | Cél                                                          |
| ---------------------------- | --------------- | ------------------------------------------------------------ |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`          | TCP kapcsolat időtúllépés állapotellenőrzésenként            |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`         | Mennyi ideig tárolják az állapottal kapcsolatos eredményeket |

**Ajánlott értékek:**

| Forgatókönyv                       | Gyors hibaidőtúllépés | Gyorsítótár TTL | Érvelés                                                                                              |
| ---------------------------------- | --------------------- | --------------- | ---------------------------------------------------------------------------------------------------- |
| Nagy áteresztőképességű API átjáró | 1500 ms               | 60000 ms        | Agresszív, hibamentes, hosszabb gyorsítótár az ellenőrzések csökkentése érdekében                    |
| Földrajzilag elosztott csomópontok | 3000 ms               | 15000 ms        | A lassabb hálózatokhoz több időre van szükség; rövidebb gyorsítótár a gyors feladatátvétel érdekében |
| Fejlesztő / tesztelés              | 1000 ms               | 10000 ms        | Gyors iteráció helyi proxykon                                                                        |
| Lopakodó / anti-detektálás         | 2500 ms               | 45000 ms        | Kerülje a gyors szondázást, amely sebességkorlátozást válthat ki                                     |

### A proxy állapotának ellenőrzése

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

A `stale` jelző `true`, ha a gyorsítótár bejegyzése meghaladja `HEALTH_CACHE_TTL_MS`, és a következő kérés új ellenőrzést indít el.

### Proxytípusonkénti alapértelmezések

Az állapotfelmérés ésszerű alapértelmezéseket használ a URL séma alapján:

| Rendszer                   | Alapértelmezett port |
| -------------------------- | -------------------- |
| `http://`                  | 8080                 |
| `https://`                 | 443                  |
| `socks5://` / `socks5h://` | 1080                 |

A URL (`http://host:9999`) egyéni portjai mindig elsőbbséget élveznek a séma alapértelmezett értékével szemben.

---

## Proxy elemzés és megfigyelhetőség

OmniRoute nyomon követi a proxyhasználatot, hogy segítse a kezelőket az útválasztási minták, a késleltetési csúcsok és az ismétlődő hibák diagnosztizálásában.

### Mi van nyomon

OmniRoute minden, konfigurált proxyn keresztül érkező kéréshez rögzíti:

| Metrikus     | Leírás                                                        |
| ------------ | ------------------------------------------------------------- |
| `proxy_url`  | Teljes proxy URL (maszkolt hitelesítési adatokkal)            |
| `provider`   | Upstream szolgáltató ID (openai, antropikus stb.)             |
| `latency_ms` | Az oda-vissza út teljes ideje, beleértve a proxy-kézfogást is |
| `connect_ms` | TCP csak csatlakozási idő                                     |
| `status`     | HTTP állapotkód upstreamről                                   |
| `error`      | Hibaosztály, ha a kérés sikertelen                            |
| `timestamp`  | ISO 8601 UTC                                                  |

### Hozzáférés az adatokhoz

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

A valódi végpont a `/api/usage/proxy-logs` (lásd `src/app/api/usage/proxy-logs/route.ts`). Ez a végpont támogatja:

- `GET /api/usage/proxy-logs` — proxy naplók lekérése
- `DELETE /api/usage/proxy-logs` — minden proxynapló törlése

Az összesített statisztikák közvetlenül a `proxy_logs` táblából kérdezhetők le SQL keresztül, ha szükséges. A UI irányítópult összesített nézeteket kínálhat.

### Gyakori minták

**Egy csapkodó proxy észlelése** (felváltva success/failure között):

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

**Keressen lassú proxykat** (p95 késleltetés > 2s):

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

## Rotációs stratégia döntési fa

Ha egy hatókörhöz több proxy is hozzá van rendelve, OmniRoute a** rotációs stratégia** hogy melyiket használja az egyes kérésekhez. A stratégia a hatókör szintjén van konfigurálva (globális, szolgáltatónként, fiókonként, kombinációnként).

### Elérhető stratégiák

| Stratégia                   | Mikor kell használni                    | Trade-off                                                                           |
| --------------------------- | --------------------------------------- | ----------------------------------------------------------------------------------- |
| `quality` (alapértelmezett) | Gyártás vegyes minőségű proxykkal       | Előnyben részesíti a magas besorolású proxykat; éhezhetnek az alacsony minősítésűek |
| `random`                    | Terheléselosztás, adatvédelem           | Egyenletes elosztás; figyelmen kívül hagyja a minőségi jeleket                      |
| `sequential`                | Hibakeresés, determinisztikus tesztelés | Sorrendben köröz a proxykon; könnyű érvelni                                         |

### Döntési fa

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

## Automatikus meghibásodási kizárás a saját proxyk számára

Az 1proxy piactér pool már önmagában is automatikusan lebontja a meghibásodott proxykat (lásd: [Proxy minőségi pontszámok](#proxy-quality-scores) ). A proxyknak** te** A rendszerleíró adatbázishoz hozzáadva a háttér állapotütemező (`src/lib/proxyHealth/scheduler.ts`) ugyanazt a "halott tag automatikus kizárása a láncból" viselkedést nyújtja anélkül, hogy bármit is törölne:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Hogyan illeszkedik egy több proxy láncba:

1. Az ütemező minden regisztrált proxyt minden `PROXY_HEALTH_INTERVAL_MS` után megvizsgál (alapértelmezett 10 perc; minimum 1 perc).
2. `PROXY_AUTO_REMOVE_AFTER` után egymást követő** meggyőző** hibák (valódi kapcsolati hiba — egy időtúllépés vagy a vizsgáló célpont saját 5xx-je soha nem számít, lásd: [Proxy állapotellenőrzés](#proxy-health-checking-v3816) ), a proxy `status` értéke `dead`.
3. `dead` egyike azoknak az állapotoknak, amelyeket pool/rotation felbontás által használt élő állapot szűrő kizár, így a hatókör forgatása (körbefutó / véletlenszerű / ragadós / késleltetési — lásd: [Rotációs stratégia döntési fa](#rotation-strategy-decision-tree) ) azonnal leállítja a proxy átadását az új kéréseknek. A készletben lévő [többi](#4-level-proxy-system) proxyt ez nem érinti, és az egész készlet soha nem esik vissza csendben egy közvetlen kapcsolatra —
4. Az ütemező folyamatosan vizsgálja `dead` proxykat ugyanazon az időközönként. A következő sikeres szonda visszafordítja `status` `active` -re, és újra belép — forgásba, nincs szükség kézi újraadásra.

Ez szándékosan** opt-in és roncsolásmentes** : alapértelmezés szerint az ütemező csak a hibákat számolja és naplózza (lásd a C házirendet `decision.ts`-ban), és `PROXY_AUTO_DISABLE` soha nem törli a — sort, erre szolgál a különálló, agresszívebb `PROXY_AUTO_REMOVE` jelző. Ha mindkettő `true` értékre van állítva, `PROXY_AUTO_REMOVE` nyer (a törlés előtt álló proxynak nincs értelme a közöttük lévő soft-disable-nak). A teljes változólistát az [Environment Config](../reference/ENVIRONMENT.md) hivatkozásban találja.

---

> 📖** Kapcsolódó dokumentáció:**
>
> - [Felhasználói útmutató](../guides/USER_GUIDE.md) — Általános beállítás és konfiguráció - [API Referencia](../reference/API_REFERENCE.md) — Teljes API dokumentáció - [Környezeti konfiguráció](../reference/ENVIRONMENT.md) — Minden környezeti változó
