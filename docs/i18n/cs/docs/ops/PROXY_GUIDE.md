# 🌐 OmniRoute Proxy Guide (Čeština)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Obejít geografické bloky, chránit svou identitu a směrovat provoz AI přes jakýkoli proxy — s nulovou složitostí konfigurace.**

OmniRoute obsahuje plně vybavený systém správy proxy, který vám umožňuje směrovat provoz poskytovatele AI směrem nahoru přes proxy HTTP, HTTPS nebo SOCKS5. Ať už jste v zablokované oblasti, potřebujete rotaci IP nebo chcete tajné snímání otisků prstů — tato příručka pokryje vše.

---

## Obsah

- [Proč používat proxy?](#why-use-proxies)
- [Přehled architektury](#architecture-overview)
- [4úrovňový proxy systém](#4-level-proxy-system)
- [Proxy registr (CRUD)](#proxy-registry-crud)
- [1 proxy Free Marketplace](#1proxy-free-proxy-marketplace)
- [Proxy rotace](#proxy-rotation)
- [Anti-Detection & Stealth](#anti-detection--stealth)
- [Upstream proxy režimy](#upstream-proxy-modes)
- [Palubní deska UI](#dashboard-ui)
- [API Reference](#api-reference)
- [Proměnné prostředí](#environment-variables)
- [Odstraňování problémů](#troubleshooting)

---

## Proč používat proxy?

Mnoho poskytovatelů AI omezuje přístup podle zeměpisné oblasti. Vývojáři v** Rusko, Čína, Írán, Kuba, Turecko** a další země se setkávají s chybami jako:

```
unsupported_country_region_territory
```

Dokonce i mimo blokované oblasti jsou proxy užitečné pro:

| Use Case                | Popis                                                                     |
| ----------------------- | ------------------------------------------------------------------------- |
| **Geografický obchvat** | Přístup k OpenAI, Anthropic, Codex, Copilot z blokovaných zemí            |
| **IP rotace**           | Distribuujte požadavky mezi více IPs, abyste se vyhnuli omezení rychlosti |
| **Soukromí**            | Skryjte své skutečné IP před upstream poskytovateli                       |
| **Dodržování**          | Směrujte provoz přes konkrétní jurisdikce                                 |
| **Testování**           | Simulujte požadavky z různých regionů                                     |

---

## Přehled architektury

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

### Klíčové komponenty

| Komponent            | Soubor                                       | Role                                                                  |
| -------------------- | -------------------------------------------- | --------------------------------------------------------------------- |
| **Proxy registr**    | `src/lib/db/proxies.ts`                      | CRUD pro položky proxy přiřazení rozsahu +                            |
| **Proxy dispečer**   | `open-sse/utils/proxyDispatcher.ts`          | Vytváří dispečery `undici` ProxyAgent/SOCKS s ukládáním do mezipaměti |
| **Načítání proxy**   | `open-sse/utils/proxyFetch.ts`               | Zabalí `fetch()` pomocí vložení proxy dispečera                       |
| **Nastavení Trasa**  | `src/app/api/settings/proxy/route.ts`        | Starší konfigurace proxy API (GET/PUT/DELETE)                         |
| **Manažerská cesta** | `src/app/api/v1/management/proxies/route.ts` | Registr CRUD API (GET/POST/PATCH/DELETE)                              |
| **1 proxy DB**       | `src/lib/db/oneproxy.ts`                     | Trvanlivost na trhu proxy zdarma                                      |

---

## Výchozí stav proxy pro nové účty

V** Nastavení → Proxy → Globální konfigurace** , použití** Ve výchozím nastavení povolit pro nová připojení proxy** vyberte počáteční stav proxy nově přidaných účtů poskytovatelů.

Nové nastavení řídí počáteční stav proxy nově přidaných účtů poskytovatelů. Nemění stávající účty ani nenahrazuje globální přepínač proxy. Jeho počáteční hodnota zachovává předchozí chování. Jednou jej vypněte, chcete-li vytvářet budoucí účty se serverem proxy ve výchozím nastavení vypnutým.

Předvolba je uložena jako `defaultNewConnectionProxyEnabled` prostřednictvím existujících Nastavení API. Výchozí hodnota je `true`, když se nikdy neuloží. Uložení `false` se projeví pro další nové účty bez restartu. `POST /api/providers` přijímá volitelný přísný booleovský `proxyEnabled`; explicitní `true` nebo `false` má přednost před výchozím nastavením vytvoření. Vynechání duplicitního účtu nebo opětovné připojení OAuth zachová uložený stav tohoto účtu. Jednotlivé účty lze povolit nebo zakázat i poté.

Převody selektivních poskytovatelů používají výchozí nastavení cílové instalace pro nové účty a zachovávají zásady cíle při nahrazování stávajících účtů. Přepínače proxy nejsou přenosná pole přenosu. Úplné obnovení zálohy a historická migrace JSON/SQL si zachovají svou stávající sémantiku obnovení, včetně uložených hodnot účtů a výchozích výchozích nastavení schémat; úplné obnovení nastavení může také obnovit tuto předvolbu.

Tato předvolba nepřiřazuje proxy ani neurčuje, že je v pořádku nebo se používá. Skutečné směrování stále závisí na globálním přepínači proxy a příslušné konfiguraci proxy. Syntetičtí poskytovatelé bez trvalého účtu, provoz OAuth před vytvořením účtu, proxy servery environment/system a síťování externích backendů jsou mimo jeho rozsah.

## 4úrovňový proxy systém

OmniRoute podporuje konfiguraci proxy na** čtyři nezávislé obory** , vyřešeno v pořadí priority:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Jak rozlišení funguje

Když OmniRoute odešle požadavek upstreamovému poskytovateli, zavolá `resolveProxyForConnectionFromRegistry()`, který zkontroluje každou úroveň v pořadí:

1. **Na úrovni účtu** — Je k tomuto konkrétnímu připojení přiřazen proxy ID?
2. **Úroveň poskytovatele** — Je tomuto poskytovateli přiřazen proxy (např. `openai`)?
3. **Globální úroveň** — Je nakonfigurován globální proxy?
4. **Žádný proxy** — Přímé připojení k poskytovateli.

První zápas vyhrává. To znamená, že můžete nastavit globální proxy jako záložní, ale přepsat jej pro konkrétní poskytovatele nebo připojení.

### Co se prodlouží

| Typ provozu          | Proxed? | Poznámky                                    |
| -------------------- | ------- | ------------------------------------------- |
| Dokončení chatu      | ✅      | Všechny požadavky `/v1/chat/completions`    |
| Vložení              | ✅      | `/v1/embeddings`                            |
| Generování obrazu    | ✅      | `/v1/images/generations`                    |
| Zvuk (TTS/STT)       | ✅      | `/v1/audio/*`                               |
| výměna tokenů OAuth  | ✅      | Řeší `unsupported_country_region_territory` |
| Testy připojení      | ✅      | Tlačítko "Test připojení" používá proxy     |
| Obnovení tokenu      | ✅      | Obnovení pozadí OAuth                       |
| Synchronizace modelu | ✅      | Výpis modelu a objev                        |

---

## Proxy registr (CRUD)

Registr proxy je tabulka SQLite (`proxy_registry`), která ukládá všechny vaše proxy. Každý proxy má:

| Pole       | Typ        | Popis                                        |
| ---------- | ---------- | -------------------------------------------- |
| `id`       | UUID       | Jedinečný identifikátor                      |
| `name`     | Řetězec    | Lidsky čitelný štítek                        |
| `type`     | Řetězec    | Protokol: `http`, `https`, `socks5`          |
| `host`     | Řetězec    | Proxy název hostitele nebo IP                |
| `port`     | Celé číslo | Číslo portu                                  |
| `username` | Řetězec    | Auth uživatelské jméno (zašifrováno v klidu) |
| `password` | Řetězec    | Ověřovací heslo (zašifrováno v klidu)        |
| `region`   | Řetězec    | Štítek zeměpisné oblasti                     |
| `notes`    | Řetězec    | Poznámky s volným textem                     |
| `status`   | Řetězec    | `active` nebo `inactive`                     |
| `source`   | Řetězec    | `manual` nebo `oneproxy`                     |

### Vytvoření proxy

**Prostřednictvím řídicího panelu:**

1. Přejít na** Nastavení → Proxy**
2. Klikněte** Přidat proxy**
3. Vyplňte typ, hostitele, port a volitelné autentizační údaje
4. Uložit

**Přes API:**

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

### Aktualizace proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Poznámka:** Pověření jsou zachována, pokud výslovně nepošlete neprázdné náhrady. Odeslání prázdných řetězců pro `username`/`password` zachová uložené hodnoty.

### Odstranění proxy

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

### Přiřazení proxy k oborům

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

### Řešení efektivního proxy

Zkontrolujte, který proxy by byl použit pro dané připojení:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Vrátí vyřešený proxy s jeho úrovní (`account`, `provider` nebo `global`) a zdrojem.

### Hromadné přiřazení

Přiřazení jednoho proxy více poskytovatelům nebo připojením najednou:

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

Proxy jsou součástí**Backup/Restore** systém. Když exportujete konfiguraci OmniRoute :

1. Přejít na** Dashboard → Settings → Backup**
2. Klikněte** Vývozní** — proxy registr a přiřazení jsou zahrnuty
3. Pro obnovení klikněte** Importovat** a nahrajte záložní soubor

Registr proxy také podporuje** upsert by host + port** — pokud importujete proxy, která již existuje (stejný hostitel a port), aktualizuje se namísto vytvoření duplikátu.

### Legacy Migration

Pokud jste nakonfigurovali proxy ve starší verzi (předběžný registr), OmniRoute je automaticky migruje:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

To se stane jednou při prvním spuštění po upgradu. Pro opětovné spuštění použijte `migrateLegacyProxyConfigToRegistry({ force: true })`.

---

## 1proxy Free Proxy Marketplace

> 🆕** Přispěl [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (vydání [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute se integruje s** [1 proxy](https://1proxy-api.aitradepulse.com)** komunitní platforma, ke které má být přístup** stovky bezplatných, ověřených proxy** z celého světa. To je ideální pro uživatele, kteří nemají vlastní infrastrukturu proxy.

### Jak to funguje

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Synchronizovat** — OmniRoute načte ověřené proxy z 1 proxy API
2. **Obchod** — Proxy jsou uloženy ve stejné tabulce `proxy_registry` jako `source = 'oneproxy'`
3. **Filtr** — Filtrujte podle protokolu, země, skóre kvality
4. **Střídat** — Vyberte nejlepší proxy pomocí kvalitních, náhodných nebo sekvenčních strategií
5. **Autodegradace** — Neúspěšným proxy se sníží skóre kvality; pod prahem → označeno jako neaktivní

### Synchronizace proxy

**Prostřednictvím řídicího panelu:**

1. Přejít na** Nastavení → 1proxy** tab
2. Klikněte** "Synchronizovat nyní"**
3. Zobrazit statistiky: celkový počet proxy, aktivní počet, průměrná kvalita, rozdělení podle zemí

**Přes API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtrování proxy

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

### Skóre kvality proxy

Každý 1 proxy server je dodáván s metadaty:

| Pole            | Popis                                        |
| --------------- | -------------------------------------------- |
| `qualityScore`  | Hodnocení 0-100 od ověření 1 proxy           |
| `latencyMs`     | Změřená latence sítě                         |
| `anonymity`     | `transparent`, `anonymous` nebo `elite`      |
| `googleAccess`  | Zda může proxy přistupovat ke službám Google |
| `countryCode`   | Dvoupísmenný kód země ISO                    |
| `lastValidated` | Časové razítko posledního ověření            |

Skóre kvality se dynamicky upravují:

- **Neúspěšné požadavky** snížit skóre o 10 bodů
- **Skóre klesá na ≤ 10** → proxy je označena `inactive`
- Neaktivní proxy jsou z rotace vyloučeny

### Strategie rotace

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

### Jistič

1proxy synchronizace má vestavěný jistič:

- Po** 5 po sobě jdoucích selhání synchronizace** , další pokusy o synchronizaci jsou blokovány
- Resetujte pomocí: `resetOneproxyCircuitBreaker()` nebo restartujte server
- Stav synchronizace je k dispozici na `GET /api/settings/oneproxy?action=status`

### Vymazání 1 proxy proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-Detection & Stealth

OmniRoute nejen směruje provoz přes proxy — ale provoz vypadá legitimně:

### TLS Falšování otisků prstů

Využívá `wreq-js` ke generování otisků prstů TLS podobných prohlížeči, čímž obchází systémy detekce botů, které signalizují handshake TLS bez prohlížeče.

### CLI Porovnání otisků prstů

The**CLI Přepínání otisků prstů** (`Settings → Security`) změní pořadí hlaviček HTTP a těles těla JSON tak, aby odpovídaly přesnému podpisu nativních binárních souborů CLI (kód Claude, Codex atd.). Tohle funguje** na vrcholu** proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Dostanete obojí**IP maskování** a** požadovat pravost** zároveň.

### Zachování proxy IP

Barevně odlišené odznaky na řídicím panelu ukazují, která úroveň proxy je aktivní:

| Odznak | Úroveň       | Význam                                                  |
| ------ | ------------ | ------------------------------------------------------- |
| 🟢     | Globální     | Veškerý provoz prochází tímto proxy serverem            |
| 🟡     | Poskytovatel | Přes proxy se používá pouze provoz tohoto poskytovatele |
| 🔵     | Spojení      | Tento konkrétní key/account používá tento proxy         |

Odznak také zobrazuje vyřešený proxy IP pro ověření.

---

## Upstream proxy režimy

Pro poskytovatele, kteří používají vzor CLIProxyAPI, OmniRoute podporuje tři upstream proxy režimy:

| Režim         | Popis                                                |
| ------------- | ---------------------------------------------------- |
| `native`      | OmniRoute zpracovává směrování proxy přímo (výchozí) |
| `cliproxyapi` | Deleguje na externí instanci CLIProxyAPI             |
| `fallback`    | Nejprve zkusí nativní, spadne zpět na CLIProxyAPI    |

Konfigurace podle poskytovatele:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Palubní deska UI

### Nastavení → Záložka Proxy

- **Globální proxy** konfigurace (nastavit jednou pro veškerý provoz)
- **Proxy podle poskytovatele** přepíše
- **Proxy podle připojení** úkoly
- **Test připojení** přes nakonfigurovaný proxy
- **Barevně odlišené odznaky** zobrazující aktivní úroveň proxy

### Nastavení → 1proxy Tab

- **Synchronizovat nyní** tlačítko pro načtení bezplatných proxy
- **Karty statistik** : Celkem, Aktivní, Prům. kvalita, Poslední synchronizace
- **Filtry** : Protokol, Kód země, Min. kvalita
- **Proxy tabulka** s hostitelem, protokolem, zemí, skóre kvality, latencí, anonymitou, Google přístupem
- **Stav synchronizace** panel se sledováním success/failure a počtem po sobě jdoucích poruch
- **Vymazat vše** pro odstranění všech 1 proxy záznamů

---

## API Reference

### Nastavení proxy API

| Metoda   | Koncový bod                                    | Popis                             |
| -------- | ---------------------------------------------- | --------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Získejte úplnou konfiguraci proxy |
| `GET`    | `/api/settings/proxy?level=global`             | Získejte globální proxy           |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Získejte proxy poskytovatele      |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Vyřešte efektivní proxy           |
| `PUT`    | `/api/settings/proxy`                          | Aktualizujte konfiguraci proxy    |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Odebrat proxy na úrovni           |

### Proxy registr API

| Metoda   | Koncový bod                                       | Popis                      |
| -------- | ------------------------------------------------- | -------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Vypsat všechny proxy       |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Získejte proxy od ID       |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Získejte přiřazení proxy   |
| `POST`   | `/api/v1/management/proxies`                      | Vytvořit proxy             |
| `PATCH`  | `/api/v1/management/proxies`                      | Aktualizovat proxy         |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Smazat proxy               |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Vynutit smazání            |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Hromadné přiřazení         |
| `GET`    | `/api/v1/management/proxies/assignments`          | Seznam úkolů               |
| `GET`    | `/api/v1/management/proxies/health`               | Zdravotní statistiky proxy |

### Tunely API

Informace o vystavení instance OmniRoute veřejnému internetu (Cloudflare/ngrok/Tailscale) namísto směrování odchozích zpráv přes proxy naleznete v [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunel REST API žije pod `/api/tunnels/{cloudflared,ngrok,tailscale}/*` a je ortogonální k odchozímu proxy řetězci popsanému výše.

### 1 proxy API

| Metoda   | Koncový bod                            | Popis                                   |
| -------- | -------------------------------------- | --------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Seznam 1 proxy proxy                    |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Získejte stav synchronizace statistik + |
| `GET`    | `/api/settings/oneproxy?action=status` | Získat pouze stav synchronizace         |
| `POST`   | `/api/settings/oneproxy`               | Spustit synchronizaci                   |
| `POST`   | `/api/settings/oneproxy/rotate`        | Otočit na další proxy                   |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Smazat jednu                            |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Vymazat vše                             |

### Upstream proxy API

| Metoda   | Koncový bod                       | Popis                               |
| -------- | --------------------------------- | ----------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Získejte konfiguraci upstream proxy |
| `PUT`    | `/api/upstream-proxy/:providerId` | Nastavte upstream proxy režim       |
| `DELETE` | `/api/upstream-proxy/:providerId` | Odebrat konfiguraci upstream proxy  |

---

## Proměnné prostředí

| Variabilní            | Výchozí | Popis                                                          |
| --------------------- | ------- | -------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`  | Povolit podporu proxy SOCKS5 (výchozí `true` v `.env.example`) |

---

## Odstraňování problémů

### "SOCKS5 proxy je zakázáno"

Nastavte `ENABLE_SOCKS5_PROXY=true` v souboru `.env` a restartujte.

### chyby "zavěšení zásuvky" prostřednictvím serveru proxy

To je normální u levných serverů proxy, které přeruší nečinná připojení. OmniRoute to již řeší takto:

- Zakázání udržování naživu u připojení proxy (`keepAliveTimeout: 1`)
- Deaktivace zřetězení (`pipelining: 0`)
- Ukládání dispečerů do mezipaměti, aby se zabránilo opakovanému podání ruky

Pokud přetrvává, zkuste jiný proxy nebo použijte funkci rotace 1 proxy.

### "unsupported_country_region_territory" během OAuth

Ujistěte se, že je nakonfigurován proxy** před** spuštění toku OAuth. OmniRoute směruje výměnu tokenů OAuth přes nakonfigurovaný proxy server. Nejprve nastavte globální proxy nebo proxy na úrovni poskytovatele a poté se připojte.

### Proxy se nepoužívá

Zkontrolujte pořadí rozlišení:

1. Ověřte pomocí `GET /api/settings/proxy?resolve=your-connection-id`
2. Zkontrolujte, zda je proxy `status` `active` (ne `inactive`)
3. Ujistěte se, že rozsah přiřazení proxy odpovídá vašemu připojení

### 1 synchronizace proxy se nezdařila

Zkontrolujte stav synchronizace:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Pokud `consecutiveFailures >= 5`, jistič se vypnul. Restartujte server pro resetování nebo počkejte na ruční reset.

---

## Schéma databáze

### Tabulka `proxy_registry`

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

### Tabulka `proxy_assignments`

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

## Kontrola stavu serveru proxy (v3.8.16 +)

OmniRoute's** proxy rychlé selhání** mechanismus (`src/lib/proxyHealth.ts`) detekuje mrtvé proxy v < 2s pomocí rychlé kontroly připojení TCP, poté** uloží výsledek do mezipaměti** abyste se vyhnuli režii na žádost.

### Jak to funguje

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

Bez toho by mrtvý proxy blokoval každý požadavek na plnou `PROXY_TIMEOUT_MS` (výchozí 30s), než by selhal.

### Laditelné proměnné prostředí

| Variabilní                   | Výchozí | Účel                                              |
| ---------------------------- | ------- | ------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | časový limit připojení TCP na kontrolu stavu      |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | Jak dlouho je výsledek stavu uložen do mezipaměti |

**Doporučené hodnoty:**

| Scénář                    | Časový limit rychlého selhání | Cache TTL | Uvažování                                                                                   |
| ------------------------- | ----------------------------- | --------- | ------------------------------------------------------------------------------------------- |
| Vysokokapacitní brána API | 1500 ms                       | 60 000 ms | Agresivní rychlost při selhání, delší mezipaměť pro snížení počtu kontrol                   |
| Geo-distribuované uzly    | 3000 ms                       | 15 000 ms | Pomalejší sítě potřebují více času; kratší mezipaměť pro rychlé převzetí služeb při selhání |
| Vývoj / testování         | 1000 ms                       | 10 000 ms | Rychlá iterace na lokálních proxy                                                           |
| Stealth / anti-detekce    | 2500 ms                       | 45 000 ms | Vyhněte se rychlému snímání, které by mohlo spustit limity frekvence                        |

### Kontrola stavu proxy

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Příznak `stale` je `true`, když záznam mezipaměti překročí `HEALTH_CACHE_TTL_MS` a další požadavek spustí novou kontrolu.

### Výchozí nastavení typu Per-Proxy

Kontrola stavu používá rozumné výchozí hodnoty založené na schématu URL :

| Systém                     | Výchozí port |
| -------------------------- | ------------ |
| `http://`                  | 8080         |
| `https://`                 | 443          |
| `socks5://` / `socks5h://` | 1080         |

Vlastní porty v URL (`http://host:9999`) mají vždy přednost před výchozím schématem.

---

## Proxy Analytics a pozorovatelnost

OmniRoute sleduje využití per-proxy a pomáhá operátorům diagnostikovat vzory směrování, špičky latence a opakující se selhání.

### Co je sledováno

Pro každý požadavek prostřednictvím nakonfigurovaného proxy zaznamená OmniRoute :

| Metrický     | Popis                                                |
| ------------ | ---------------------------------------------------- |
| `proxy_url`  | Úplný proxy URL (s maskovanými přihlašovacími údaji) |
| `provider`   | Upstream poskytovatel ID (openai, antropický atd.)   |
| `latency_ms` | Celková doba zpáteční cesty včetně handshake proxy   |
| `connect_ms` | pouze čas připojení TCP                              |
| `status`     | stavový kód HTTP z upstreamu                         |
| `error`      | Chybová třída, pokud požadavek selhal                |
| `timestamp`  | ISO 8601 UTC                                         |

### Přístup k datům

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Skutečný koncový bod je `/api/usage/proxy-logs` (viz `src/app/api/usage/proxy-logs/route.ts`). Tento koncový bod podporuje:

- `GET /api/usage/proxy-logs` — načte protokoly proxy
- `DELETE /api/usage/proxy-logs` — vymazat všechny protokoly proxy

Souhrnné statistiky lze v případě potřeby dotazovat přímo z tabulky `proxy_logs` prostřednictvím SQL. Řídicí panel UI může nabízet souhrnná zobrazení.

### Společné vzory

**Zjistěte flapping proxy** (střídá se mezi success/failure):

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

**Najděte pomalé proxy** (p95 latence > 2s):

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

## Rozhodovací strom strategie rotace

Když je k oboru přiřazeno více proxy, OmniRoute používá a** rotační strategie** vybrat, který z nich použít pro každý požadavek. Strategie je nakonfigurována na úrovni rozsahu (globální, na poskytovatele, na účet, na kombinaci).

### Dostupné strategie

| Strategie           | Kdy použít                        | Kompromis                                                                   |
| ------------------- | --------------------------------- | --------------------------------------------------------------------------- |
| `quality` (výchozí) | Výroba se smíšenou kvalitou proxy | Upřednostňuje vysoce hodnocené proxy; mohou hladovět ty s nízkým hodnocením |
| `random`            | Rozložení zátěže, soukromí        | Rovnoměrné rozložení; ignoruje signály kvality                              |
| `sequential`        | Ladění, deterministické testování | Cykluje přes proxy v pořadí; snadno uvažovat                                |

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

## Automatické vyloučení selhání pro vaše vlastní proxy

Fond tržiště 1proxy již sám o sobě automaticky degraduje neúspěšné proxy (viz [Skóre kvality proxy](#proxy-quality-scores) ). Pro proxy** Vy** přidaný do registru, plánovač stavu na pozadí (`src/lib/proxyHealth/scheduler.ts`) poskytuje stejné chování „vyloučit mrtvého člena z řetězce automaticky“, aniž by se cokoli smazalo:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Jak to zapadá do multi-proxy řetězce:

1. Plánovač testuje každý registrovaný proxy každých `PROXY_HEALTH_INTERVAL_MS` (výchozí 10 min; minimálně 1 min).
2. Po `PROXY_AUTO_REMOVE_AFTER` po sobě** přesvědčivé** selhání (skutečné selhání připojení — časový limit nebo vlastní 5xx cíle sondy se nikdy nepočítá, viz [Kontrola stavu proxy](#proxy-health-checking-v3816) ), `status` proxy je nastaveno na `dead`.
3. `dead` je jedním ze stavů, které filtr živého stavu používaný rozlišením pool/rotation vylučuje, takže rotace rozsahu (cyklus/náhodné / lepivé / latence — viz [strom rozhodnutí o strategii rotace](#rotation-strategy-decision-tree) ) okamžitě přestane poskytovat proxy novým požadavkům. Nejsou ovlivněny žádné další proxy ve fondu a celý fond se nikdy tiše nevrátí zpět k přímému připojení — viz [4úrovňový systém proxy](#4-level-proxy-system) proti selhání zavření.
4. Plánovač udržuje sondování `dead` proxy ve stejném intervalu. Další úspěšná sonda převrátí `status` zpět na `active` a znovu vstoupí do rotace — bez nutnosti ručního opětovného přidání.

To je schválně** opt-in a nedestruktivní** : ve výchozím nastavení plánovač počítá a zaznamenává pouze selhání (viz zásada C v `decision.ts`) a `PROXY_AUTO_DISABLE` nikdy neodstraní řádek — k čemuž slouží samostatný agresivnější příznak `PROXY_AUTO_REMOVE`. Pokud jsou oba nastaveny na `true`, vyhraje `PROXY_AUTO_REMOVE` (proxy, který má být smazán, nemá využití pro měkké vypnutí mezi tím). Úplný seznam proměnných naleznete v Referenční příručce [konfigurace prostředí](../reference/ENVIRONMENT.md).

---

> 📖** Související dokumentace:**
>
> - [Uživatelská příručka](../guides/USER_GUIDE.md) — Obecné nastavení a konfigurace - [API Reference](../reference/API_REFERENCE.md) — Úplná dokumentace API - [Konfigurace prostředí](../reference/ENVIRONMENT.md) — Všechny proměnné prostředí
