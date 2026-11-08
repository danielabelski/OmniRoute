# 🌐 OmniRoute Proxy Guide (Slovenčina)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Obíďte geografické bloky, chráňte svoju identitu a smerujte prevádzku AI cez akýkoľvek proxy — s nulovou zložitosťou konfigurácie.**

OmniRoute obsahuje plnohodnotný systém správy proxy, ktorý vám umožňuje smerovať upstream prevádzku poskytovateľa AI cez proxy HTTP, HTTPS alebo SOCKS5. Či už ste v zablokovanej oblasti, potrebujete rotáciu IP alebo chcete tajné snímanie odtlačkov prstov — táto príručka pokrýva všetko.

---

## Obsah

- [Prečo používať proxy?](#why-use-proxies)
- [Prehľad architektúry](#architecture-overview)
- [4-úrovňový proxy systém](#4-level-proxy-system)
- [Register proxy (CRUD)](#proxy-registry-crud)
- [1 proxy bezplatný trh](#1proxy-free-proxy-marketplace)
- [Rotácia proxy](#proxy-rotation)
- [Anti-Detection & Stealth](#anti-detection--stealth)
- [Upstream proxy režimy](#upstream-proxy-modes)
- [Prístrojová doska UI](#dashboard-ui)
- [API Referencia](#api-reference)
- [Premenné prostredia](#environment-variables)
- [Riešenie problémov](#troubleshooting)

---

## Prečo používať proxy?

Mnoho poskytovateľov AI obmedzuje prístup podľa geografickej oblasti. Vývojári v** Rusko, Čína, Irán, Kuba, Turecko** a ďalšie krajiny sa stretávajú s chybami ako:

```
unsupported_country_region_territory
```

Dokonca aj mimo blokovaných oblastí sú servery proxy užitočné na:

| Prípad použitia             | Popis                                                                      |
| --------------------------- | -------------------------------------------------------------------------- |
| **Geografický obchvat**     | Prístup k OpenAI, Anthropic, Codex, Copilot z blokovaných krajín           |
| **rotácia IP**              | Rozdeľte požiadavky medzi viacero IPs, aby ste sa vyhli obmedzeniu sadzieb |
| **Ochrana osobných údajov** | Skryte svoju skutočnú IP pred poskytovateľmi proti prúdu                   |
| **Súlad**                   | Smerujte premávku cez konkrétne jurisdikcie                                |
| **Testovanie**              | Simulujte požiadavky z rôznych regiónov                                    |

---

## Prehľad architektúry

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

### Kľúčové komponenty

| Komponent            | Súbor                                        | Role                                                                            |
| -------------------- | -------------------------------------------- | ------------------------------------------------------------------------------- |
| **Register proxy**   | `src/lib/db/proxies.ts`                      | CRUD pre položky proxy priradenia rozsahu +                                     |
| **Proxy dispečer**   | `open-sse/utils/proxyDispatcher.ts`          | Vytvára `undici` ProxyAgent/SOCKS dispečerov s ukladaním do vyrovnávacej pamäte |
| **Načítanie proxy**  | `open-sse/utils/proxyFetch.ts`               | Zabalí `fetch()` injekciou proxy dispečera                                      |
| **Nastavenia Trasa** | `src/app/api/settings/proxy/route.ts`        | Konfigurácia starého servera proxy API (GET/PUT/DELETE)                         |
| **Manažérska cesta** | `src/app/api/v1/management/proxies/route.ts` | Register CRUD API (GET/POST/PATCH/DELETE)                                       |
| **1 proxy DB**       | `src/lib/db/oneproxy.ts`                     | Trvanlivosť na trhu proxy zadarmo                                               |

---

## Predvolený stav servera proxy pre nové účty

In** Nastavenia → Proxy → Globálna konfigurácia** , použite** Predvolene povoliť proxy pre nové pripojenia** vyberte počiatočný stav proxy novo pridaných účtov poskytovateľa.

Nové nastavenie riadi počiatočný stav proxy novo pridaných účtov poskytovateľa. Nezmení existujúce účty ani nenahradí globálny prepínač proxy. Jeho počiatočná hodnota zachováva predchádzajúce správanie. Ak chcete vytvoriť budúce účty s predvolene zakázaným serverom proxy, raz ho vypnite.

Predvoľba je uložená ako `defaultNewConnectionProxyEnabled` prostredníctvom existujúcich nastavení API. Keď sa neuloží, predvolene sa nastaví `true`. Uloženie `false` sa prejaví pri ďalších nových účtoch bez reštartu. `POST /api/providers` akceptuje voliteľné striktné booleovské `proxyEnabled`; explicitné `true` alebo `false` má prednosť pred predvoleným nastavením vytvorenia. Vynechanie duplicitného účtu alebo opätovné pripojenie OAuth zachová uložený stav tohto účtu. Jednotlivé účty je možné povoliť alebo zakázať aj neskôr.

Selektívne prenosy poskytovateľov používajú predvolené nastavenia cieľovej inštalácie pre nové účty a zachovávajú politiku cieľa pri nahrádzaní existujúcich účtov. Prepínače proxy nie sú prenosné polia prenosu. Úplná obnova zálohy a historická migrácia JSON/SQL si zachovávajú svoju existujúcu sémantiku obnovy, vrátane uložených hodnôt účtov a predvolených nastavení starých schém; úplné obnovenie nastavení môže tiež obnoviť túto predvoľbu.

Táto preferencia nepriraďuje proxy server ani neurčuje, že je v poriadku alebo sa používa. Skutočné smerovanie stále závisí od globálneho prepínača proxy a príslušnej konfigurácie proxy. Syntetickí poskytovatelia bez trvalého účtu, prevádzka OAuth pred vytvorením účtu, proxy servery environment/system a sieťovanie externých backendov sú mimo jej pôsobnosti.

## 4-úrovňový proxy systém

OmniRoute podporuje konfiguráciu proxy na** štyri nezávislé rozsahy** , vyriešené v poradí podľa priority:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Ako funguje rozlíšenie

Keď OmniRoute odošle požiadavku upstream poskytovateľovi, zavolá `resolveProxyForConnectionFromRegistry()`, ktorý skontroluje každú úroveň v poradí:

1. **Na úrovni účtu** — Je k tomuto konkrétnemu pripojeniu priradený proxy ID?
2. **Úroveň poskytovateľa** — Je k tomuto poskytovateľovi priradený proxy server (napr. `openai`)?
3. **Globálna úroveň** — Je nakonfigurovaný globálny proxy?
4. **Žiadny proxy** — Priame pripojenie k poskytovateľovi.

Prvý zápas vyhráva. To znamená, že môžete nastaviť globálny proxy server ako záložný, ale prepísať ho pre konkrétnych poskytovateľov alebo pripojenia.

### Čo sa sprostredkuje

| Typ premávky          | Sprostredkovaný? | Poznámky                                     |
| --------------------- | ---------------- | -------------------------------------------- |
| Dokončenia četu       | ✅               | Všetky požiadavky `/v1/chat/completions`     |
| Vloženie              | ✅               | `/v1/embeddings`                             |
| Generovanie obrazu    | ✅               | `/v1/images/generations`                     |
| Zvuk (TTS/STT)        | ✅               | `/v1/audio/*`                                |
| výmena tokenov OAuth  | ✅               | Rieši `unsupported_country_region_territory` |
| Testy pripojenia      | ✅               | Tlačidlo "Testovať pripojenie" používa proxy |
| Obnovenie tokenu      | ✅               | Obnovenie pozadia OAuth                      |
| Synchronizácia modelu | ✅               | Zoznam a objavovanie modelov                 |

---

## Register proxy (CRUD)

Register proxy je tabuľka SQLite (`proxy_registry`), v ktorej sú uložené všetky vaše servery proxy. Každý proxy má:

| Pole       | Typ        | Popis                                            |
| ---------- | ---------- | ------------------------------------------------ |
| `id`       | UUID       | Jedinečný identifikátor                          |
| `name`     | Reťazec    | Ľudsky čitateľný štítok                          |
| `type`     | Reťazec    | Protokol: `http`, `https`, `socks5`              |
| `host`     | Reťazec    | Názov hostiteľa proxy alebo IP                   |
| `port`     | Celé číslo | Číslo portu                                      |
| `username` | Reťazec    | Autorské meno používateľa (zašifrované v pokoji) |
| `password` | Reťazec    | Autorizačné heslo (zašifrované v pokoji)         |
| `region`   | Reťazec    | Označenie geografického regiónu                  |
| `notes`    | Reťazec    | Poznámky s voľným textom                         |
| `status`   | Reťazec    | `active` alebo `inactive`                        |
| `source`   | Reťazec    | `manual` alebo `oneproxy`                        |

### Vytvorenie proxy

**Cez Dashboard:**

1. Prejsť na** Nastavenia → Proxy**
2. Kliknite** Pridať proxy**
3. Vyplňte typ, hostiteľ, port a voliteľné autentizačné poverenia
4. Uložiť

**Cez API:**

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

### Aktualizácia proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Poznámka:** Poverenia sa zachovajú, pokiaľ výslovne nepošlete neprázdne náhrady. Odoslanie prázdnych reťazcov pre `username`/`password` zachová uložené hodnoty.

### Odstránenie proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Výpis proxy

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Priradenie proxy k rozsahom

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

### Riešenie efektívneho proxy

Skontrolujte, ktorý server proxy by sa použil pre dané pripojenie:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Vráti vyriešený server proxy s jeho úrovňou (`account`, `provider` alebo `global`) a zdrojom.

### Hromadné pridelenie

Priraďte jeden proxy server viacerým poskytovateľom alebo pripojeniam naraz:

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

Proxy sú zahrnuté v**Backup/Restore** systém. Keď exportujete konfiguráciu OmniRoute :

1. Prejsť na** Dashboard → Settings → Backup**
2. Kliknite** Exportovať** — proxy register a priradenia sú zahrnuté
3. Ak chcete obnoviť, kliknite** Importovať** a nahrajte záložný súbor

Register proxy tiež podporuje** upsert by host + port** — ak importujete server proxy, ktorý už existuje (rovnaký hostiteľ a port), aktualizuje sa namiesto vytvorenia duplikátu.

### Legacy Migration

Ak ste nakonfigurovali servery proxy v staršej verzii (predbežný register), OmniRoute ich automaticky migruje:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Stane sa to raz pri prvom spustení po inovácii. Na opätovné spustenie použite `migrateLegacyProxyConfigToRegistry({ force: true })`.

---

## 1 proxy bezplatný server proxy

> 🆕** Prispel [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (vydanie [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute sa integruje s** [1 proxy](https://1proxy-api.aitradepulse.com)** komunitná platforma na poskytovanie prístupu** stovky bezplatných overených serverov proxy** z celého sveta. Toto je ideálne pre používateľov, ktorí nemajú vlastnú proxy infraštruktúru.

### Ako to funguje

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Synchronizovať** — OmniRoute načíta overené proxy z 1 proxy API
2. **Obchod** — Proxy sú uložené v rovnakej tabuľke `proxy_registry` ako `source = 'oneproxy'`
3. **Filter** — Filtrujte podľa protokolu, krajiny, skóre kvality
4. **Otočiť** — Vyberte si najlepší proxy pomocou kvalitných, náhodných alebo sekvenčných stratégií
5. **Autodegradácia** — Neúspešným proxy sa zníži skóre kvality; pod prahom → označené ako neaktívne

### Synchronizácia serverov proxy

**Cez Dashboard:**

1. Prejsť na** Nastavenia → 1proxy** tab
2. Kliknite** "Synchronizovať teraz"**
3. Zobraziť štatistiky: celkový počet proxy serverov, aktívny počet, priemerná kvalita, rozdelenie podľa krajín

**Cez API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtrovanie proxy serverov

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

### Skóre kvality servera proxy

Každý 1 proxy server obsahuje metadáta:

| Pole            | Popis                                    |
| --------------- | ---------------------------------------- |
| `qualityScore`  | Hodnotenie 0-100 od overenia 1 proxy     |
| `latencyMs`     | Meraná latencia siete                    |
| `anonymity`     | `transparent`, `anonymous` alebo `elite` |
| `googleAccess`  | Či má proxy prístup k službám Google     |
| `countryCode`   | Dvojpísmenový kód krajiny ISO            |
| `lastValidated` | Časová pečiatka posledného overenia      |

Skóre kvality sa dynamicky upravujú:

- **Neúspešné žiadosti** znížiť skóre o 10 bodov
- **Skóre klesá na ≤ 10** → proxy je označený `inactive`
- Neaktívne proxy sú vylúčené z rotácie

### Stratégie rotácie

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

### Istič

1proxy synchronizácia má vstavaný istič:

- Po** 5 po sebe idúcich zlyhaní synchronizácie** , ďalšie pokusy o synchronizáciu sú zablokované
- Resetujte pomocou: `resetOneproxyCircuitBreaker()` alebo reštartujte server
- Stav synchronizácie je k dispozícii na `GET /api/settings/oneproxy?action=status`

### Vymazanie 1 proxy proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-Detection & Stealth

OmniRoute nesmeruje iba prenos cez proxy — ale robí to, aby vyzerala legitímne:

### TLS Spoofing odtlačkov prstov

Používa `wreq-js` na generovanie odtlačkov prstov TLS podobných prehliadaču, čím obchádza systémy detekcie botov, ktoré signalizujú podanie ruky TLS mimo prehliadača.

### CLI Zhoda odtlačkov prstov

The**CLI prepínač odtlačkov prstov** (`Settings → Security`) zmení poradie hlavičiek HTTP a polí tela JSON tak, aby zodpovedali presnému podpisu natívnych binárnych súborov CLI ( kód Claude, Codex atď.). Toto funguje** na vrchole** proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Dostanete oboje**IP maskovanie** a** požiadať o pravosť** súčasne.

### Zachovanie proxy IP

Farebne označené odznaky na paneli ukazujú, ktorá úroveň proxy je aktívna:

| Odznak | úroveň       | Význam                                                  |
| ------ | ------------ | ------------------------------------------------------- |
| 🟢     | globálne     | Všetka návštevnosť prechádza cez tento proxy server     |
| 🟡     | Poskytovateľ | Za proxy sa používa iba návštevnosť tohto poskytovateľa |
| 🔵     | Pripojenie   | Tento konkrétny key/account používa tento proxy         |

Odznak tiež zobrazuje vyriešený proxy IP na overenie.

---

## Upstream proxy režimy

Pre poskytovateľov, ktorí používajú vzor CLIProxyAPI, OmniRoute podporuje tri upstream proxy režimy:

| Režim         | Popis                                                     |
| ------------- | --------------------------------------------------------- |
| `native`      | OmniRoute spracováva smerovanie proxy priamo (predvolené) |
| `cliproxyapi` | Deleguje na externú inštanciu CLIProxyAPI                 |
| `fallback`    | Najprv skúsi natívne, vráti sa späť na CLIProxyAPI        |

Konfigurácia podľa poskytovateľa:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Prístrojová doska UI

### Nastavenia → Záložka proxy

- **Globálny proxy** konfigurácia (nastaví sa raz pre celú premávku)
- **Proxy podľa poskytovateľa** prepíše
- **Proxy podľa pripojenia** úlohy
- **Test pripojenia** cez nakonfigurovaný proxy
- **Farebne odlíšené odznaky** zobrazuje aktívnu úroveň proxy

### Nastavenia → 1proxy Tab

- **Synchronizovať teraz** tlačidlo na načítanie bezplatných serverov proxy
- **Štatistické karty** : Celkom, Aktívne, Priemerná kvalita, Posledná synchronizácia
- **Filtre** : Protokol, Kód krajiny, Min. kvalita
- **Proxy tabuľka** s hostiteľom, protokolom, krajinou, skóre kvality, latenciou, anonymitou, Google prístupom
- **Stav synchronizácie** panel so sledovaním success/failure a počtom po sebe idúcich porúch
- **Vymazať všetko** na odstránenie všetkých 1 proxy záznamov

---

## API Referencia

### Nastavenia proxy API

| Metóda   | Koncový bod                                    | Popis                                     |
| -------- | ---------------------------------------------- | ----------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Získajte úplnú konfiguráciu servera proxy |
| `GET`    | `/api/settings/proxy?level=global`             | Získajte globálny proxy                   |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Získajte proxy poskytovateľa              |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Vyriešte efektívny proxy server           |
| `PUT`    | `/api/settings/proxy`                          | Aktualizujte konfiguráciu servera proxy   |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Odstráňte proxy na úrovni                 |

### Register proxy API

| Metóda   | Koncový bod                                       | Popis                        |
| -------- | ------------------------------------------------- | ---------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Vypísať všetky servery proxy |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Získajte proxy od ID         |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Získajte úlohy proxy         |
| `POST`   | `/api/v1/management/proxies`                      | Vytvorte proxy               |
| `PATCH`  | `/api/v1/management/proxies`                      | Aktualizujte proxy           |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Odstrániť proxy              |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Vynútiť odstránenie          |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Hromadné pridelenie          |
| `GET`    | `/api/v1/management/proxies/assignments`          | Zoznam úloh                  |
| `GET`    | `/api/v1/management/proxies/health`               | Zdravotné štatistiky proxy   |

### Tunely API

Informácie o vystavení vašej inštancie OmniRoute verejnému internetu (Cloudflare/ngrok/Tailscale) namiesto smerovania odchádzajúcich cez server proxy nájdete [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunel REST API žije pod `/api/tunnels/{cloudflared,ngrok,tailscale}/*` a je ortogonálny k odchádzajúcemu proxy reťazcu zdokumentovanému vyššie.

### 1 proxy API

| Metóda   | Koncový bod                            | Popis                                    |
| -------- | -------------------------------------- | ---------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Zoznam 1 proxy serverov                  |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Získajte stav synchronizácie štatistík + |
| `GET`    | `/api/settings/oneproxy?action=status` | Získajte iba stav synchronizácie         |
| `POST`   | `/api/settings/oneproxy`               | Spustiť synchronizáciu                   |
| `POST`   | `/api/settings/oneproxy/rotate`        | Otočiť na ďalší proxy server             |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Odstrániť jednu                          |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Vymazať všetko                           |

### Upstream Proxy API

| Metóda   | Koncový bod                       | Popis                                            |
| -------- | --------------------------------- | ------------------------------------------------ |
| `GET`    | `/api/upstream-proxy/:providerId` | Získajte konfiguráciu servera proxy pre upstream |
| `PUT`    | `/api/upstream-proxy/:providerId` | Nastavte režim upstream proxy                    |
| `DELETE` | `/api/upstream-proxy/:providerId` | Odstráňte konfiguráciu upstream proxy            |

---

## Premenné prostredia

| Variabilné            | Predvolené | Popis                                                             |
| --------------------- | ---------- | ----------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`     | Povoliť podporu proxy SOCKS5 (predvolené `true` v `.env.example`) |

---

## Riešenie problémov

### "Proxy SOCKS5 je zakázaný"

Nastavte `ENABLE_SOCKS5_PROXY=true` v súbore `.env` a reštartujte.

### chyby "zavesenie zásuvky" cez proxy

To je normálne pri lacných serveroch proxy, ktoré prerušia nečinné pripojenia. OmniRoute to už rieši takto:

- Zakázanie udržiavania nažive na pripojeniach proxy (`keepAliveTimeout: 1`)
- Zakázanie potrubia (`pipelining: 0`)
- Ukladanie dispečerov do vyrovnávacej pamäte, aby sa zabránilo opakovanému podávaniu rúk

Ak to pretrváva, skúste iný proxy alebo použite funkciu rotácie 1 proxy.

### "unsupported_country_region_territory" počas OAuth

Uistite sa, že je server proxy nakonfigurovaný** predtým** spustenie toku OAuth. OmniRoute smeruje výmenu tokenov OAuth cez nakonfigurovaný server proxy. Najprv nastavte globálny proxy server alebo proxy na úrovni poskytovateľa a potom sa pripojte.

### Proxy sa nepoužíva

Skontrolujte poradie rozlíšenia:

1. Overte pomocou `GET /api/settings/proxy?resolve=your-connection-id`
2. Skontrolujte, či je proxy `status` `active` (nie `inactive`)
3. Uistite sa, že rozsah priradenia proxy zodpovedá vášmu pripojeniu

### 1 synchronizácia servera proxy zlyhala

Skontrolujte stav synchronizácie:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Ak `consecutiveFailures >= 5`, vypol sa istič. Reštartujte server na resetovanie alebo počkajte na manuálny reset.

---

## Schéma databázy

### Tabuľka `proxy_registry`

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

### Tabuľka `proxy_assignments`

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

## Kontrola stavu servera proxy (v3.8.16 +)

OmniRoute's** proxy rýchlo zlyhať** mechanizmus (`src/lib/proxyHealth.ts`) detekuje mŕtve proxy v < 2s prostredníctvom rýchlej kontroly pripojenia TCP, potom** uloží výsledok do vyrovnávacej pamäte** aby ste sa vyhli réžii na žiadosť.

### Ako to funguje

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

Bez toho by mŕtvy proxy blokoval každú požiadavku na plnú `PROXY_TIMEOUT_MS` (predvolene 30 s) pred zlyhaním.

### Laditeľné premenné prostredia

| Variabilné                   | Predvolené | Účel                                                          |
| ---------------------------- | ---------- | ------------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`     | Časový limit pripojenia TCP na kontrolu stavu                 |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`    | Ako dlho je uložený zdravotný výsledok do vyrovnávacej pamäte |

**Odporúčané hodnoty:**

| Scenár                      | Časový limit rýchleho zlyhania | Cache TTL | Zdôvodnenie                                                                                     |
| --------------------------- | ------------------------------ | --------- | ----------------------------------------------------------------------------------------------- |
| Vysoko priepustná brána API | 1500 ms                        | 60 000 ms | Agresívna, rýchla, dlhšia vyrovnávacia pamäť na zníženie počtu kontrol                          |
| Geo-distribuované uzly      | 3000 ms                        | 15 000 ms | Pomalšie siete potrebujú viac času; kratšia vyrovnávacia pamäť pre rýchle prepnutie pri zlyhaní |
| Vývoj / testovanie          | 1000 ms                        | 10 000 ms | Rýchla iterácia na lokálnych serveroch proxy                                                    |
| Stealth / antidetekcia      | 2500 ms                        | 45 000 ms | Vyhnite sa rýchlemu snímaniu, ktoré by mohlo spustiť limity frekvencie                          |

### Kontrola zdravia proxy

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Príznak `stale` je `true`, keď záznam cache prekročí `HEALTH_CACHE_TTL_MS` a ďalšia požiadavka spustí novú kontrolu.

### Predvolené nastavenia typu per-proxy

Kontrola stavu používa rozumné predvolené hodnoty založené na schéme URL :

| Schéma                     | Predvolený port |
| -------------------------- | --------------- |
| `http://`                  | 8080            |
| `https://`                 | 443             |
| `socks5://` / `socks5h://` | 1080            |

Vlastné porty v URL (`http://host:9999`) majú vždy prednosť pred predvolenou schémou.

---

## Proxy analytika a pozorovateľnosť

OmniRoute sleduje využitie na servery proxy a pomáha operátorom diagnostikovať vzory smerovania, špičky latencie a opakujúce sa zlyhania.

### Čo sa sleduje

Pre každú požiadavku cez nakonfigurovaný proxy server OmniRoute zaznamená:

| Metrické     | Popis                                                                      |
| ------------ | -------------------------------------------------------------------------- |
| `proxy_url`  | Úplný proxy URL (s maskovanými autorizačnými údajmi)                       |
| `provider`   | Upstream poskytovateľ ID (openai, antropický atď.)                         |
| `latency_ms` | Celkový čas spiatočnej cesty vrátane potriasania rúk prostredníctvom proxy |
| `connect_ms` | len čas pripojenia TCP                                                     |
| `status`     | stavový kód HTTP z upstreamu                                               |
| `error`      | Chybová trieda, ak žiadosť zlyhá                                           |
| `timestamp`  | ISO 8601 UTC                                                               |

### Prístup k údajom

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Skutočný koncový bod je `/api/usage/proxy-logs` (pozri `src/app/api/usage/proxy-logs/route.ts`). Tento koncový bod podporuje:

- `GET /api/usage/proxy-logs` — načíta protokoly proxy
- `DELETE /api/usage/proxy-logs` — vymazať všetky protokoly proxy

Súhrnné štatistiky je možné v prípade potreby vyhľadávať priamo z tabuľky `proxy_logs` cez SQL. Dashboard UI môže ponúkať súhrnné zobrazenia.

### Bežné vzory

**Zistiť flapping proxy** (strieda sa medzi success/failure):

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

**Nájdite pomalé servery proxy** (p95 latencia > 2s):

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

## Rozhodovací strom stratégie rotácie

Keď je k rozsahu priradených viacero proxy, OmniRoute používa a** rotačná stratégia** vybrať, ktorý z nich sa má použiť pre každú požiadavku. Stratégia je nakonfigurovaná na úrovni rozsahu (globálne, podľa poskytovateľa, podľa účtu, podľa kombinácie).

### Dostupné stratégie

| Stratégia              | Kedy použiť                               | Kompromis                                                                           |
| ---------------------- | ----------------------------------------- | ----------------------------------------------------------------------------------- |
| `quality` (predvolené) | Výroba s proxy servermi zmiešanej kvality | Uprednostňuje vysoko hodnotené servery proxy; môžu hladovať tie s nízkym hodnotením |
| `random`               | Rozloženie záťaže, súkromie               | Rovnomerné rozdelenie; ignoruje signály kvality                                     |
| `sequential`           | Ladenie, deterministické testovanie       | Prechádza cez proxy v poradí; ľahko uvažovať                                        |

### Rozhodovací strom

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

## Automatické vylúčenie zlyhania pre vaše vlastné proxy

Fond 1proxy marketplace už sám o sebe automaticky degraduje neúspešné proxy (pozrite si [Skóre kvality servera proxy](#proxy-quality-scores) ). Pre proxy** vy** pridaný do registra, plánovač stavu na pozadí (`src/lib/proxyHealth/scheduler.ts`) poskytuje rovnaké správanie „vylúčiť mŕtveho člena z reťazca automaticky“ bez toho, aby sa čokoľvek vymazalo:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Ako to zapadá do multi-proxy reťazca:

1. Plánovač testuje každého zaregistrovaného proxy každé `PROXY_HEALTH_INTERVAL_MS` (predvolené 10 min; minimálne 1 min).
2. Po `PROXY_AUTO_REMOVE_AFTER` po sebe** presvedčivé** zlyhania (skutočné zlyhanie pripojenia — časový limit alebo vlastný 5xx cieľa sondy sa nikdy nepočíta, pozrite si [Kontrola stavu servera proxy](#proxy-health-checking-v3816) ), `status` servera proxy je nastavené na `dead`.
3. `dead` je jedným zo stavov, ktoré filter aktívneho stavu používaný rozlíšením pool/rotation vylučuje, takže rotácia rozsahu (cyklus/náhodné / lepkavé / latencia — pozri [strom rozhodovania o stratégii rotácie](#rotation-strategy-decision-tree) ) okamžite zastaví odovzdávanie proxy novým požiadavkám. Nie sú ovplyvnené žiadne iné servery proxy v oblasti a celá oblasť sa nikdy ticho nevráti späť k priamemu pripojeniu — pozri [4-úrovňový systém proxy](#4-level-proxy-system) pri zatvorení zlyhania.
4. Plánovač neustále skúma proxy servery `dead` v rovnakom intervale. Ďalšia úspešná sonda prevráti `status` späť na `active` a znova sa dostane do rotácie — nie je potrebné manuálne opätovné pridávanie.

Toto je zámerne** opt-in a nedeštruktívne** : predvolene plánovač počíta a zaznamenáva len zlyhania (pozri politiku C v `decision.ts`) a `PROXY_AUTO_DISABLE` nikdy nevymaže riadok —, na čo slúži samostatný, agresívnejší príznak `PROXY_AUTO_REMOVE`. Ak sú obe nastavené na `true`, vyhráva `PROXY_AUTO_REMOVE` (proxy, ktorý sa má vymazať, nemá zmysel pre mäkké vypnutie medzi tým). Úplný zoznam premenných nájdete v príručke [Environment Config](../reference/ENVIRONMENT.md).

---

> 📖** Súvisiaca dokumentácia:**
>
> - [Používateľská príručka](../guides/USER_GUIDE.md) — Všeobecné nastavenie a konfigurácia - [API Referencia](../reference/API_REFERENCE.md) — Úplná dokumentácia API - [Konfigurácia prostredia](../reference/ENVIRONMENT.md) — Všetky premenné prostredia
