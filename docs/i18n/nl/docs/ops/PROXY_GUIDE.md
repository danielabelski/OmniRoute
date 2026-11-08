# 🌐 OmniRoute Proxy Guide (Nederlands)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Omzeil geografische blokkades, bescherm uw identiteit en leid AI verkeer via elke — -proxy zonder enige configuratiecomplexiteit.**

OmniRoute bevat een volledig proxybeheersysteem waarmee u upstream-verkeer van AI provider kunt routeren via HTTP, HTTPS of SOCKS5 -proxy's. Of je je nu in een geblokkeerde regio bevindt, IP rotatie nodig hebt of stealth-vingerafdrukken — wilt, deze gids behandelt alles.

---

## Inhoudsopgave

- [Waarom proxy's gebruiken?](#why-use-proxies)
- [Architectuuroverzicht](#architecture-overview)
- [Proxysysteem met 4 niveaus](#4-level-proxy-system)
- [Proxy-register (CRUD)](#proxy-registry-crud)
- [1proxy Gratis marktplaats](#1proxy-free-proxy-marketplace)
- [Proxy-rotatie](#proxy-rotation)
- [Anti-detectie en stealth](#anti-detection--stealth)
- [Upstream-proxymodi](#upstream-proxy-modes)
- [Dashboard UI](#dashboard-ui)
- [API Referentie](#api-reference)
- [Omgevingsvariabelen](#environment-variables)
- [Problemen oplossen](#troubleshooting)

---

## Waarom proxy's gebruiken?

Veel AI aanbieders beperken de toegang per geografische regio. Ontwikkelaars binnen** Rusland, China, Iran, Cuba, Turkije** , en andere landen komen fouten tegen zoals:

```
unsupported_country_region_territory
```

Zelfs buiten geblokkeerde regio's zijn proxy's nuttig voor:

| Gebruikscasus           | Beschrijving                                                             |
| ----------------------- | ------------------------------------------------------------------------ |
| **Geografische bypass** | Toegang tot OpenAI, Anthropic, Codex, Copilot vanuit geblokkeerde landen |
| **IP rotatie**          | Verdeel verzoeken over meerdere IPs om snelheidsbeperkingen te voorkomen |
| **Privacy**             | Verberg uw echte IP voor upstream-providers                              |
| **Naleving**            | Leid het verkeer door specifieke rechtsgebieden                          |
| **Testen**              | Simuleer verzoeken uit verschillende regio's                             |

---

## Architectuuroverzicht

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

### Belangrijkste componenten

| Onderdeel              | Bestand                                      | Rol                                                       |
| ---------------------- | -------------------------------------------- | --------------------------------------------------------- |
| **Proxy-register**     | `src/lib/db/proxies.ts`                      | CRUD voor proxy-invoer + scope-toewijzingen               |
| **Proxy-verzender**    | `open-sse/utils/proxyDispatcher.ts`          | Creëert `undici` ProxyAgent/SOCKS dispatchers met caching |
| **Proxy ophalen**      | `open-sse/utils/proxyFetch.ts`               | Wraps `fetch()` met proxy-dispatcher-injectie             |
| **Instellingen Route** | `src/app/api/settings/proxy/route.ts`        | Verouderde proxyconfiguratie API (GET/PUT/DELETE)         |
| **Beheerroute**        | `src/app/api/v1/management/proxies/route.ts` | Register CRUD API (GET/POST/PATCH/DELETE)                 |
| **1proxy DB**          | `src/lib/db/oneproxy.ts`                     | Gratis volharding op de proxymarktplaats                  |

---

## Standaardproxystatus voor nieuwe accounts

In** Instellingen → Proxy → Algemene configuratie** , gebruik** Schakel proxy standaard in voor nieuwe verbindingen** om de initiële proxystatus van nieuw toegevoegde provideraccounts te kiezen.

De nieuwe instelling bepaalt de initiële proxystatus van nieuw toegevoegde provideraccounts. Het verandert geen bestaande accounts en vervangt de globale proxy-switch niet. De initiële waarde behoudt het eerdere gedrag. Schakel het één keer uit om toekomstige accounts te maken waarbij proxy standaard is uitgeschakeld.

De voorkeur wordt opgeslagen als `defaultNewConnectionProxyEnabled` via de bestaande Instellingen API. Het is standaard `true` als het nooit wordt opgeslagen. Het opslaan `false` wordt zonder herstart van kracht voor volgende nieuwe accounts. `POST /api/providers` accepteert een optionele strikte booleaanse `proxyEnabled`; een expliciete `true` of `false` heeft voorrang op de standaardinstelling voor het aanmaken. Als u een dubbel account weglaat of OAuth opnieuw verbindt, blijft de opgeslagen status van dat account behouden. Individuele accounts kunnen daarna nog steeds worden in- of uitgeschakeld.

Selectieve provideroverdrachten gebruiken de standaardinstellingen van de doelinstallatie voor nieuwe accounts en behouden het bestemmingsbeleid bij het vervangen van bestaande accounts. Proxyschakelaars zijn geen draagbare overdrachtsvelden. Volledig back-upherstel en historische JSON/SQL -migratie behouden hun bestaande herstelsemantiek, inclusief opgeslagen accountwaarden en verouderde schemastandaarden; een volledig herstel van de instellingen kan deze voorkeur ook herstellen.

Deze voorkeur kent geen proxy toe en stelt niet vast dat iemand gezond of in gebruik is. De daadwerkelijke routering is nog steeds afhankelijk van de globale proxyschakelaar en de toepasselijke proxyconfiguratie. Synthetische providers zonder een permanent account, OAuth verkeer vóór het aanmaken van een account, environment/system proxy's en externe backends-netwerken vallen buiten het bereik ervan.

## Proxysysteem met 4 niveaus

OmniRoute ondersteunt proxyconfiguratie op** vier onafhankelijke scopes** , opgelost in prioriteitsvolgorde:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Hoe resolutie werkt

Wanneer OmniRoute een verzoek naar een upstream-provider stuurt, roept het `resolveProxyForConnectionFromRegistry()` aan, die elk niveau in de volgende volgorde controleert:

1. **Accountniveau** — Is er een proxy toegewezen aan deze specifieke verbinding ID?
2. **Provider-niveau** — Is er een proxy toegewezen aan deze provider (bijvoorbeeld `openai`)?
3. **Mondiaal niveau** — Is er een globale proxy geconfigureerd?
4. **Geen proxy** — Directe verbinding met de provider.

De eerste wedstrijd wint. Dit betekent dat u een globale proxy kunt instellen als reserve, maar deze kunt overschrijven voor specifieke providers of verbindingen.

### Wat wordt proxy

| Verkeerstype             | Gevolmachtigd? | Opmerkingen                                         |
| ------------------------ | -------------- | --------------------------------------------------- |
| Chat-voltooiingen        | ✅             | Alle `/v1/chat/completions` verzoeken               |
| Inbedding                | ✅             | `/v1/embeddings`                                    |
| Beeldgeneratie           | ✅             | `/v1/images/generations`                            |
| Audio (TTS/STT)          | ✅             | `/v1/audio/*`                                       |
| OAuth -tokenuitwisseling | ✅             | Lost `unsupported_country_region_territory`         |
| Verbindingstests         | ✅             | De knop "Verbinding testen" maakt gebruik van proxy |
| Token vernieuwen         | ✅             | Achtergrond OAuth vernieuwing                       |
| Modelsynchronisatie      | ✅             | Modelvermelding en ontdekking                       |

---

## Proxy-register (CRUD)

Het proxyregister is een SQLite tabel (`proxy_registry`) waarin al uw proxy's zijn opgeslagen. Elke proxy heeft:

| Veld       | Type         | Beschrijving                                |
| ---------- | ------------ | ------------------------------------------- |
| `id`       | UUID         | Unieke identificatie                        |
| `name`     | Snaar        | Voor mensen leesbaar etiket                 |
| `type`     | Snaar        | Protocol: `http`, `https`, `socks5`         |
| `host`     | Snaar        | Proxy-hostnaam of IP                        |
| `port`     | Geheel getal | Poortnummer                                 |
| `username` | Snaar        | Auth-gebruikersnaam (versleuteld in rust)   |
| `password` | Snaar        | Verificatiewachtwoord (versleuteld in rust) |
| `region`   | Snaar        | Label voor geografische regio               |
| `notes`    | Snaar        | Vrije tekst notities                        |
| `status`   | Snaar        | `active` of `inactive`                      |
| `source`   | Snaar        | `manual` of `oneproxy`                      |

### Een proxy maken

**Via Dashboard:**

1. Ga naar** Instellingen → Proxy**
2. Klik** Proxy toevoegen**
3. Vul het type, de host, de poort en optionele verificatiereferenties in
4. Redden

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

### Een proxy bijwerken

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Opmerking:** Inloggegevens blijven behouden, tenzij u expliciet niet-lege vervangingen verzendt. Als u lege tekenreeksen voor `username`/`password` verzendt, blijven de opgeslagen waarden behouden.

### Een proxy verwijderen

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Volmachten vermelden

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Proxy's toewijzen aan scopes

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

### Effectieve proxy oplossen

Controleer welke proxy voor een bepaalde verbinding zou worden gebruikt:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Retourneert de opgeloste proxy met zijn niveau (`account`, `provider` of `global`) en bron.

### Bulktoewijzing

Wijs één proxy toe aan meerdere providers of verbindingen tegelijk:

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

Volmachten zijn opgenomen in de**Backup/Restore** systeem. Wanneer u uw OmniRoute configuratie exporteert:

1. Ga naar** Dashboard → Instellingen → -up**
2. Klik** Exporteren** — proxy register en opdrachten zijn inbegrepen
3. Klik op om te herstellen** Importeren** en upload het back-upbestand

Het proxyregister ondersteunt ook** upsert door host + poort** — als u een proxy importeert die al bestaat (dezelfde host en poort), wordt deze bijgewerkt in plaats van een duplicaat te maken.

### Verouderde migratie

Als je proxy's in een oudere versie (pre-registratie) hebt geconfigureerd, migreert OmniRoute deze automatisch:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Dit gebeurt één keer bij de eerste keer opstarten na de upgrade. Gebruik `migrateLegacyProxyConfigToRegistry({ force: true })` om opnieuw uit te voeren.

---

## 1proxy Gratis proxymarktplaats

> 🆕** Bijgedragen door [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (probleem [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integreert met de** [1proxy](https://1proxy-api.aitradepulse.com)** communityplatform waartoe toegang kan worden verleend** honderden gratis, gevalideerde proxy's** van over de hele wereld. Dit is perfect voor gebruikers die niet over een eigen proxy-infrastructuur beschikken.

### Hoe het werkt

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Synchroniseren** — OmniRoute haalt gevalideerde proxy's op van de 1proxy API
2. **Winkel** — proxy's worden opgeslagen in dezelfde `proxy_registry` tabel met `source = 'oneproxy'`
3. **Filter** — Filter op protocol, land, kwaliteitsscore
4. **Draaien** — Kies de beste proxy met behulp van kwaliteits-, willekeurige of sequentiële strategieën
5. **Automatische degradatie** — Mislukte proxy's krijgen een lagere kwaliteitsscore; onder drempelwaarde → gemarkeerd als inactief

### Proxy's synchroniseren

**Via Dashboard:**

1. Ga naar** Instellingen → 1proxy** tabblad
2. Klik** "Nu synchroniseren"**
3. Bekijk statistieken: totaal aantal proxy's, actieve telling, gemiddelde kwaliteit, uitsplitsing per land

**Via API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Proxy's filteren

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

### Proxykwaliteitsscores

Elke 1proxy-proxy wordt geleverd met metadata:

| Veld            | Beschrijving                                   |
| --------------- | ---------------------------------------------- |
| `qualityScore`  | 0-100 beoordeling van 1proxy-validatie         |
| `latencyMs`     | Gemeten netwerklatentie                        |
| `anonymity`     | `transparent`, `anonymous` of `elite`          |
| `googleAccess`  | Of de proxy toegang heeft tot Google -services |
| `countryCode`   | Tweeletterige ISO landcode                     |
| `lastValidated` | Tijdstempel van de laatste validatie           |

Kwaliteitsscores worden dynamisch aangepast:

- **Mislukte verzoeken** verlaag de score met 10 punten
- **Score daalt naar ≤ 10** → proxy is gemarkeerd met `inactive`
- Inactieve proxy's zijn uitgesloten van rotatie

### Rotatiestrategieën

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

### Stroomonderbreker

De 1proxy-synchronisatie heeft een ingebouwde stroomonderbreker:

- Na** 5 opeenvolgende synchronisatiefouten** , worden verdere synchronisatiepogingen geblokkeerd
- Reset met: `resetOneproxyCircuitBreaker()` of start de server opnieuw op
- De synchronisatiestatus is beschikbaar op `GET /api/settings/oneproxy?action=status`

### 1proxy-proxy's wissen

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-detectie en stealth

OmniRoute leidt niet alleen verkeer door een proxy — het zorgt ervoor dat het verkeer er legitiem uitziet:

### TLS Vingerafdrukspoofing

Gebruikt `wreq-js` om browserachtige TLS vingerafdrukken te genereren, waarbij botdetectiesystemen worden omzeild die niet-browser TLS handshakes markeren.

### CLI -vingerafdrukmatching

De**CLI Vingerafdrukschakelaar** (`Settings → Security`) herschikt HTTP headers en JSON body-velden zodat ze overeenkomen met de exacte handtekening van native CLI binaire bestanden (Claude Code, Codex, enz.). Dit werkt** bovenop** de proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Je krijgt beide**IP maskeren** En** authenticiteit vragen** tegelijkertijd.

### Proxy IP

Kleurgecodeerde badges in het dashboard laten zien welk proxyniveau actief is:

| Kenteken | Niveau     | Betekenis                                                |
| -------- | ---------- | -------------------------------------------------------- |
| 🟢       | Globaal    | Al het verkeer gaat via deze proxy                       |
| 🟡       | Aanbieder  | Alleen het verkeer van deze provider wordt geproxyd      |
| 🔵       | Verbinding | Deze specifieke key/account maakt gebruik van deze proxy |

De badge toont ook de opgeloste proxy IP ter verificatie.

---

## Upstream-proxymodi

Voor providers die het CLIProxyAPI patroon gebruiken, ondersteunt OmniRoute drie upstream-proxymodi:

| Modus         | Beschrijving                                               |
| ------------- | ---------------------------------------------------------- |
| `native`      | OmniRoute verwerkt proxyroutering rechtstreeks (standaard) |
| `cliproxyapi` | Gemachtigden naar een extern CLIProxyAPI exemplaar         |
| `fallback`    | Probeert eerst native, valt terug op CLIProxyAPI           |

Configureer per provider:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Dashboard UI

### Instellingen → Tabblad Proxy

- **Mondiale proxy** configuratie (eenmalig ingesteld voor al het verkeer)
- **Proxy per provider** overschrijft
- **Proxy per verbinding** opdrachten
- **Verbindingstest** via geconfigureerde proxy
- **Kleurgecodeerde badges** toont actief proxyniveau

### Instellingen → 1proxy Tab

- **Synchroniseer nu** knop om gratis proxy's op te halen
- **Statistieken kaarten** : Totaal, Actief, Gemiddelde kwaliteit, Laatste synchronisatie
- **Filters** : Protocol, Landcode, Min. Kwaliteit
- **Proxy-tabel** met host, protocol, land, kwaliteitsscore, latentie, anonimiteit, Google -toegang
- **Synchronisatiestatus** paneel met success/failure -tracking en opeenvolgende fouttellingen
- **Alles wissen** om alle 1proxy-vermeldingen te verwijderen

---

## API Referentie

### Proxy-instellingen API

| Methode  | Eindpunt                                       | Beschrijving                         |
| -------- | ---------------------------------------------- | ------------------------------------ |
| `GET`    | `/api/settings/proxy`                          | Krijg de volledige proxyconfiguratie |
| `GET`    | `/api/settings/proxy?level=global`             | Krijg een globale proxy              |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Providerproxy ophalen                |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Effectieve proxy oplossen            |
| `PUT`    | `/api/settings/proxy`                          | Proxyconfiguratie bijwerken          |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Verwijder proxy op niveau            |

### Proxyregister API

| Methode  | Eindpunt                                          | Beschrijving                    |
| -------- | ------------------------------------------------- | ------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Maak een lijst van alle proxy's |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Ontvang proxy door ID           |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Ontvang proxy-toewijzingen      |
| `POST`   | `/api/v1/management/proxies`                      | Proxy maken                     |
| `PATCH`  | `/api/v1/management/proxies`                      | Proxy bijwerken                 |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Proxy verwijderen               |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Forceer verwijderen             |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Bulktoewijzing                  |
| `GET`    | `/api/v1/management/proxies/assignments`          | Lijst opdrachten                |
| `GET`    | `/api/v1/management/proxies/health`               | Proxy-gezondheidsstatistieken   |

### Tunnels API

Zie [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) voor het blootstellen van uw OmniRoute instantie aan het openbare internet (Cloudflare/ngrok/Tailscale) in plaats van uitgaand verkeer via een proxy te routeren. De tunnel REST API leeft onder `/api/tunnels/{cloudflared,ngrok,tailscale}/*` en staat loodrecht op de uitgaande proxyketen die hierboven is gedocumenteerd.

### 1proxy API

| Methode  | Eindpunt                               | Beschrijving                                 |
| -------- | -------------------------------------- | -------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Lijst 1proxy-proxy's                         |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Ontvang statistieken + -synchronisatiestatus |
| `GET`    | `/api/settings/oneproxy?action=status` | Alleen synchronisatiestatus ophalen          |
| `POST`   | `/api/settings/oneproxy`               | Synchronisatie activeren                     |
| `POST`   | `/api/settings/oneproxy/rotate`        | Draai naar de volgende proxy                 |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Verwijder er één                             |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Alles wissen                                 |

### Upstream Proxy API

| Methode  | Eindpunt                          | Beschrijving                            |
| -------- | --------------------------------- | --------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Upstream-proxyconfiguratie ophalen      |
| `PUT`    | `/api/upstream-proxy/:providerId` | Stel de upstream-proxymodus in          |
| `DELETE` | `/api/upstream-proxy/:providerId` | Verwijder de upstream-proxyconfiguratie |

---

## Omgevingsvariabelen

| Variabel              | Standaard | Beschrijving                                                               |
| --------------------- | --------- | -------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`    | Schakel SOCKS5 proxy-ondersteuning in (standaard `true` in `.env.example`) |

---

## Problemen oplossen

### "SOCKS5 proxy is uitgeschakeld"

Stel `ENABLE_SOCKS5_PROXY=true` in uw `.env` bestand in en start opnieuw op.

### "socket hang up"-fouten via proxy

Dit is normaal bij goedkope proxy's die inactieve verbindingen verbreken. OmniRoute regelt dit al door:

- Keep-alive op proxyverbindingen uitschakelen (`keepAliveTimeout: 1`)
- Pipelining uitschakelen (`pipelining: 0`)
- Dispatchers in cache plaatsen om herhaalde handdrukken te voorkomen

Als het probleem zich blijft voordoen, probeer dan een andere proxy of gebruik de functie 1proxy-rotatie.

### "unsupported_country_region_territory" tijdens OAuth

Zorg ervoor dat de proxy is geconfigureerd** voor** het starten van de OAuth stroom. OmniRoute routeert OAuth -tokenuitwisseling via de geconfigureerde proxy. Stel eerst een globale proxy of proxy op providerniveau in en maak vervolgens verbinding.

### Proxy wordt niet gebruikt

Controleer de resolutievolgorde:

1. Verifieer met `GET /api/settings/proxy?resolve=your-connection-id`
2. Controleer of de proxy `status` `active` is (niet `inactive`)
3. Zorg ervoor dat het bereik van de proxytoewijzing overeenkomt met uw verbinding

### 1proxy-synchronisatie mislukt

Controleer de synchronisatiestatus:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Als `consecutiveFailures >= 5` is de stroomonderbreker geactiveerd. Start de server opnieuw op om deze opnieuw in te stellen, of wacht op een handmatige reset.

---

## Databaseschema

### `proxy_registry` Tabel

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

### `proxy_assignments` Tabel

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

## Proxystatuscontrole (v3.8.16 +)

OmniRoute's** proxy snel mislukt** mechanisme (`src/lib/proxyHealth.ts`) detecteert dode proxy's in < 2s via een snelle TCP -verbindingscontrole, en vervolgens** slaat het resultaat op in de cache** om overhead per aanvraag te voorkomen.

### Hoe het werkt

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

Zonder dit zou een dode proxy elk verzoek om de volledige `PROXY_TIMEOUT_MS` (standaard 30 seconden) blokkeren voordat het mislukte.

### Afstembare omgevingsvariabelen

| Variabel                     | Standaard | Doel                                                        |
| ---------------------------- | --------- | ----------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`    | TCP -verbindingstime-out per statuscheck                    |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`   | Hoe lang een gezondheidsresultaat in de cache wordt bewaard |

**Aanbevolen waarden:**

| Scenario                        | Time-out bij snelle mislukking | Cache TTL | Redenering                                                                      |
| ------------------------------- | ------------------------------ | --------- | ------------------------------------------------------------------------------- |
| API -gateway met hoge doorvoer  | 1500 ms                        | 60000 ms  | Agressieve, snelle, langere cache om controles te verminderen                   |
| Geo-gedistribueerde knooppunten | 3000 ms                        | 15000 ms  | Langzamere netwerken hebben meer tijd nodig; kortere cache voor snelle failover |
| Ontwikkelen/testen              | 1000 ms                        | 10000 ms  | Snelle iteratie op lokale proxy's                                               |
| Stealth / anti-detectie         | 2500 ms                        | 45000 ms  | Vermijd snelle sondes die snelheidslimieten kunnen activeren                    |

### Proxystatus inspecteren

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

De `stale` vlag is `true` wanneer de cache-invoer `HEALTH_CACHE_TTL_MS` heeft overschreden en het volgende verzoek een nieuwe controle zal activeren.

### Standaardwaarden per proxytype

De health check maakt gebruik van verstandige standaardwaarden op basis van het URL schema:

| Schema                     | Standaardpoort |
| -------------------------- | -------------- |
| `http://`                  | 8080           |
| `https://`                 | 443            |
| `socks5://` / `socks5h://` | 1080           |

Aangepaste poorten in de URL (`http://host:9999`) hebben altijd voorrang op de schemastandaard.

---

## Proxyanalyse en waarneembaarheid

OmniRoute houdt het gebruik per proxy bij om operators te helpen bij het diagnosticeren van routeringspatronen, latentiepieken en terugkerende fouten.

### Wat wordt bijgehouden

Voor elk verzoek via een geconfigureerde proxy registreert OmniRoute :

| Metrisch     | Beschrijving                                           |
| ------------ | ------------------------------------------------------ |
| `proxy_url`  | Volledige proxy URL (met gemaskeerde auth-referenties) |
| `provider`   | Upstream-aanbieder ID (openai, antropisch, etc.)       |
| `latency_ms` | Totale retourtijd inclusief proxy-handshake            |
| `connect_ms` | alleen TCP connect-tijd                                |
| `status`     | HTTP -statuscode van stroomopwaarts                    |
| `error`      | Foutklasse als verzoek mislukt                         |
| `timestamp`  | ISO 8601 UTC                                           |

### Toegang tot de gegevens

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Het echte eindpunt is `/api/usage/proxy-logs` (zie `src/app/api/usage/proxy-logs/route.ts`). Dit eindpunt ondersteunt:

- `GET /api/usage/proxy-logs` — proxylogboeken ophalen
- `DELETE /api/usage/proxy-logs` — wis alle proxylogboeken

Geaggregeerde statistieken kunnen indien nodig rechtstreeks vanuit de `proxy_logs` tabel worden opgevraagd via SQL. Het dashboard UI biedt mogelijk geaggregeerde weergaven.

### Algemene patronen

**Detecteer een flapperende proxy** (wisselt af tussen success/failure):

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

**Vind trage proxy's** (p95 latentie > 2s):

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

## Beslisboom voor rotatiestrategie

Wanneer meerdere proxy's aan een bereik zijn toegewezen, gebruikt OmniRoute a** rotatie strategie** om te kiezen welke u voor elk verzoek wilt gebruiken. De strategie wordt geconfigureerd op scopeniveau (globaal, per provider, per account, per combo).

### Beschikbare strategieën

| Strategie             | Wanneer te gebruiken                         | Afruil                                                                                            |
| --------------------- | -------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| `quality` (standaard) | Productie met proxy's van gemengde kwaliteit | Geeft de voorkeur aan proxy's met een hoge rating; kunnen degenen met een lage rating verhongeren |
| `random`              | Belastingverdeling, privacy                  | Gelijkmatige distributie; negeert kwaliteitssignalen                                              |
| `sequential`          | Debuggen, deterministisch testen             | Bladert op volgorde door proxy's; gemakkelijk om over te redeneren                                |

### Beslissingsboom

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

## Automatische uitsluiting van storingen voor uw eigen proxy's

De 1proxy-marktplaatspool degradeert mislukte proxy's al automatisch (zie [Proxykwaliteitsscores](#proxy-quality-scores) ). Voor proxy's** Jij** toegevoegd aan het register, biedt de achtergrondgezondheidsplanner (`src/lib/proxyHealth/scheduler.ts`) hetzelfde gedrag "een dood lid automatisch uitsluiten van de keten", zonder iets te verwijderen:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Hoe het past in een keten met meerdere proxy's:

1. De planner onderzoekt elke geregistreerde proxy elke `PROXY_HEALTH_INTERVAL_MS` (standaard 10 min; minimaal 1 min).
2. Na `PROXY_AUTO_REMOVE_AFTER` opeenvolgend** overtuigend** fouten (een echte verbindingsfout — een time-out of de eigen 5xx van het probe-doel telt nooit, zie [Proxy Health Checking](#proxy-health-checking-v3816) ), de `status` van de proxy is ingesteld op `dead`.
3. `dead` is een van de statussen die het levend-statusfilter dat door pool/rotation -resolutie wordt gebruikt, uitsluit, dus de rotatie van een scope (round-robin / willekeurig / sticky / latency — zie [Rotatiestrategie Beslissingsboom](#rotation-strategy-decision-tree) ) stopt onmiddellijk met het overhandigen van die proxy aan nieuwe verzoeken. Er worden geen andere proxy's in de pool beïnvloed, en de hele pool valt nooit stilletjes terug naar een directe verbinding — de [4-niveau proxy-systeem](#4-level-proxy-system) fail-closed guard.
4. De planner blijft `dead` proxy's op hetzelfde interval onderzoeken. De volgende succesvolle sonde draait `status` terug naar `active` en keert terug naar de rotatie — Handmatig opnieuw toevoegen is niet nodig.

Dit is opzettelijk** opt-in en niet-destructief** : standaard telt en registreert de planner alleen fouten (zie beleid C in `decision.ts`), en `PROXY_AUTO_DISABLE` verwijdert nooit een rij — daar is de afzonderlijke, agressievere `PROXY_AUTO_REMOVE` vlag voor. Als beide zijn ingesteld op `true`, wint `PROXY_AUTO_REMOVE` (een proxy die op het punt staat te worden verwijderd heeft geen zin voor een zachte uitschakeling ertussen). Zie de [Environment Config-](../reference/ENVIRONMENT.md) referentie voor de volledige lijst met variabelen.

---

> 📖** Gerelateerde documentatie:**
>
> - [Gebruikershandleiding](../guides/USER_GUIDE.md) — Algemene installatie en configuratie - [API Referentie](../reference/API_REFERENCE.md) — Volledige API documentatie - [Omgevingsconfiguratie](../reference/ENVIRONMENT.md) — Alle omgevingsvariabelen
