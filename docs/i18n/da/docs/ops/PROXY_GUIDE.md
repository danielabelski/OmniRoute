# 🌐 OmniRoute Proxy Guide (Dansk)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Omgå geografiske blokeringer, beskyt din identitet, og diriger AI -trafik gennem enhver proxy- — med nul konfigurationskompleksitet.**

OmniRoute inkluderer et fuldt udstyret proxy-administrationssystem, der lader dig dirigere opstrøms AI udbydertrafik gennem HTTP, HTTPS eller SOCKS5 proxyer. Uanset om du er i et blokeret område, har brug for IP rotation eller ønsker stealth fingeraftryk — dækker denne guide alt.

---

## Indholdsfortegnelse

- [Hvorfor bruge fuldmagter?](#why-use-proxies)
- [Arkitektur oversigt](#architecture-overview)
- [4-niveau proxy system](#4-level-proxy-system)
- [Proxy Registry (CRUD)](#proxy-registry-crud)
- [1proxy gratis markedsplads](#1proxy-free-proxy-marketplace)
- [Proxy rotation](#proxy-rotation)
- [Anti-detektion og stealth](#anti-detection--stealth)
- [Opstrøms proxytilstande](#upstream-proxy-modes)
- [Dashboard UI](#dashboard-ui)
- [API reference](#api-reference)
- [Miljøvariabler](#environment-variables)
- [Fejlfinding](#troubleshooting)

---

## Hvorfor bruge fuldmagter?

Mange AI udbydere begrænser adgangen efter geografisk område. Udviklere i** Rusland, Kina, Iran, Cuba, Tyrkiet** , og andre lande støder på fejl som:

```
unsupported_country_region_territory
```

Selv uden for blokerede områder er proxyer nyttige til:

| Use Case              | Beskrivelse                                                                 |
| --------------------- | --------------------------------------------------------------------------- |
| **Geografisk bypass** | Få adgang til OpenAI, Anthropic, Codex, Copilot fra blokerede lande         |
| **IP rotation**       | Fordel anmodninger på tværs af flere IPs for at undgå hastighedsbegrænsning |
| **Privatliv**         | Skjul din rigtige IP fra upstream-udbydere                                  |
| **Overholdelse**      | Led trafik gennem specifikke jurisdiktioner                                 |
| **Afprøvning**        | Simuler anmodninger fra forskellige regioner                                |

---

## Arkitektur oversigt

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

### Nøglekomponenter

| Komponent               | Fil                                          | Rolle                                                     |
| ----------------------- | -------------------------------------------- | --------------------------------------------------------- |
| **Fuldmagtsregister**   | `src/lib/db/proxies.ts`                      | CRUD for proxy-indgange + -omfangstildelinger             |
| **Fuldmægtig afsender** | `open-sse/utils/proxyDispatcher.ts`          | Opretter `undici` ProxyAgent/SOCKS -afsendere med caching |
| **Fuldmagtshentning**   | `open-sse/utils/proxyFetch.ts`               | Omslutter `fetch()` med proxy dispatcher-injektion        |
| **Indstillinger Rute**  | `src/app/api/settings/proxy/route.ts`        | Ældre proxy-konfiguration API (GET/PUT/DELETE)            |
| **Ledelsesrute**        | `src/app/api/v1/management/proxies/route.ts` | Registry CRUD API (GET/POST/PATCH/DELETE)                 |
| **1 proxy DB**          | `src/lib/db/oneproxy.ts`                     | Gratis proxy markedsplads persistens                      |

---

## Standard proxy-tilstand for nye konti

I** Indstillinger → Proxy → Global konfiguration** , brug** Aktiver proxy som standard for nye forbindelser** for at vælge den oprindelige proxy-tilstand for nyligt tilføjede udbyderkonti.

Den nye indstilling styrer den indledende proxy-tilstand for nyligt tilføjede udbyderkonti. Det ændrer ikke eksisterende konti eller erstatter den globale proxy-switch. Dens startværdi bevarer den tidligere adfærd. Slå det fra én gang for at oprette fremtidige konti med proxy deaktiveret som standard.

Præferencen gemmes som `defaultNewConnectionProxyEnabled` gennem de eksisterende indstillinger API. Den er som standard `true` når den aldrig bliver gemt. At gemme `false` træder i kraft for efterfølgende nye konti uden genstart. `POST /api/providers` accepterer en valgfri streng boolesk `proxyEnabled`; en eksplicit `true` eller `false` har forrang over oprettelsesstandarden. Udeladelse af en dubletkonto eller OAuth genopret forbindelse bevarer denne kontos lagrede tilstand. Individuelle konti kan stadig aktiveres eller deaktiveres efterfølgende.

Selektive udbyderoverførsler bruger destinationsinstallationens standard for nye konti og bevarer destinationspolitikken, når eksisterende konti erstattes. Proxy-skift er ikke bærbare overførselsfelter. Fuld backupgendannelse og historisk JSON/SQL -migrering bevarer deres eksisterende gendannelsessemantik, inklusive gemte kontoværdier og ældre skemastandarder; en fuld gendannelse af indstillinger kan også gendanne denne præference.

Denne præference tildeler ikke en proxy eller fastslår, at en er sund eller i brug. Den faktiske routing afhænger stadig af den globale proxy-switch og gældende proxy-konfiguration. Syntetiske udbydere uden en vedvarende konto, OAuth -trafik før kontooprettelse, environment/system proxyer og eksterne backends' netværk er uden for dets omfang.

## 4-niveau proxy system

OmniRoute understøtter proxy-konfiguration på** fire uafhængige områder** , løst i prioriteret rækkefølge:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Sådan fungerer opløsning

Når OmniRoute sender en anmodning til en upstream-udbyder, kalder den `resolveProxyForConnectionFromRegistry()`, som kontrollerer hvert niveau i rækkefølge:

1. **Kontoniveau** — Er der tildelt en proxy til denne specifikke forbindelse ID?
2. **Udbyder-niveau** — Er der tildelt en proxy til denne udbyder (f.eks. `openai`)?
3. **Globalt niveau** — Er der konfigureret en global proxy?
4. **Ingen proxy** — Direkte forbindelse til udbyderen.

Den første kamp vinder. Det betyder, at du kan indstille en global proxy som en reserve, men tilsidesætte den for specifikke udbydere eller forbindelser.

### Hvad får fuldmagt

| Trafik type            | Fuldmagt? | Noter                                        |
| ---------------------- | --------- | -------------------------------------------- |
| Chatafslutninger       | ✅        | Alle `/v1/chat/completions` anmodninger      |
| Indlejringer           | ✅        | `/v1/embeddings`                             |
| Billedgenerering       | ✅        | `/v1/images/generations`                     |
| Lyd (TTS/STT)          | ✅        | `/v1/audio/*`                                |
| OAuth token udveksling | ✅        | Løser `unsupported_country_region_territory` |
| Forbindelsestest       | ✅        | Knappen "Test forbindelse" bruger proxy      |
| Token opdatering       | ✅        | Baggrund OAuth fornyelse                     |
| Model sync             | ✅        | Modelliste og opdagelse                      |

---

## Proxy Registry (CRUD)

Proxy-registret er en SQLite tabel (`proxy_registry`), der gemmer alle dine proxyer. Hver proxy har:

| Felt       | Type   | Beskrivelse                                 |
| ---------- | ------ | ------------------------------------------- |
| `id`       | UUID   | Unik identifikator                          |
| `name`     | Snor   | Etiket, der kan læses af mennesker          |
| `type`     | Snor   | Protokol: `http`, `https`, `socks5`         |
| `host`     | Snor   | Proxy-værtsnavn eller IP                    |
| `port`     | Heltal | Portnummer                                  |
| `username` | Snor   | Auth brugernavn (krypteret i hvile)         |
| `password` | Snor   | Godkendelsesadgangskode (krypteret i hvile) |
| `region`   | Snor   | Etiket for geografisk område                |
| `notes`    | Snor   | Fritekstnoter                               |
| `status`   | Snor   | `active` eller `inactive`                   |
| `source`   | Snor   | `manual` eller `oneproxy`                   |

### Oprettelse af en proxy

**Via Dashboard:**

1. Gå til** Indstillinger → Proxy**
2. Klik** Tilføj proxy**
3. Udfyld legitimationsoplysningerne for type, vært, port og valgfri godkendelse
4. Spare

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

### Opdatering af en proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Note:** Legitimationsoplysninger bevares, medmindre du udtrykkeligt sender ikke-tomme erstatninger. Sending af tomme strenge for `username`/`password` vil beholde de lagrede værdier.

### Sletning af en proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Listefuldmagter

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Tildeling af fuldmagter til Scopes

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

### Løsning af effektiv proxy

Tjek hvilken proxy der vil blive brugt til en given forbindelse:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Returnerer den løste proxy med dens niveau (`account`, `provider` eller `global`) og kilde.

### Bulk tildeling

Tildel én proxy til flere udbydere eller forbindelser på én gang:

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

Fuldmagter er inkluderet i**Backup/Restore** system. Når du eksporterer din OmniRoute konfiguration:

1. Gå til** Dashboard → Indstillinger → Backup**
2. Klik** Eksportere** — proxy registry og opgaver er inkluderet
3. Klik på for at gendanne** Importere** og upload backup-filen

Proxy-registret understøtter også** upsert af vært + port** — hvis du importerer en proxy, der allerede eksisterer (samme vært og port), opdateres den i stedet for at oprette en dublet.

### Ældre migration

Hvis du konfigurerede proxyer i en ældre version (præ-registrering), migrerer OmniRoute dem automatisk:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Dette sker én gang ved første opstart efter opgradering. Brug `migrateLegacyProxyConfigToRegistry({ force: true })` til at køre igen.

---

## 1proxy gratis proxy markedsplads

> 🆕** Bidraget af [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (udgave [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integreres med** [1 proxy](https://1proxy-api.aitradepulse.com)** fællesskabsplatform at give adgang til** hundredvis af gratis, validerede fuldmagter** fra hele verden. Dette er perfekt til brugere, der ikke har deres egen proxy-infrastruktur.

### Hvordan det virker

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Synkroniser** — OmniRoute henter validerede proxyer fra 1proxy API
2. **Butik** — Proxies gemmes i den samme `proxy_registry` tabel som `source = 'oneproxy'`
3. **Filter** — Filtrer efter protokol, land, kvalitetsscore
4. **Rotere** — Vælg den bedste proxy ved hjælp af kvalitets-, tilfældige eller sekventielle strategier
5. **Automatisk nedbrydning** — Mislykkede fuldmagter får deres kvalitetsscore reduceret; under tærskel → markeret inaktiv

### Synkroniserer proxyer

**Via Dashboard:**

1. Gå til** Indstillinger → 1proxy** fanen
2. Klik** "Synkroniser nu"**
3. Se statistikker: samlede fuldmagter, aktivt antal, gennemsnitlig kvalitet, opdeling efter land

**Via API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtrering af proxyer

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

### Proxy kvalitetsresultater

Hver 1proxy proxy leveres med metadata:

| Felt            | Beskrivelse                                   |
| --------------- | --------------------------------------------- |
| `qualityScore`  | 0-100 rating fra 1 proxy validering           |
| `latencyMs`     | Målt netværksforsinkelse                      |
| `anonymity`     | `transparent`, `anonymous` eller `elite`      |
| `googleAccess`  | Om proxyen kan få adgang til Google tjenester |
| `countryCode`   | To bogstaver ISO landekode                    |
| `lastValidated` | Tidsstempel for sidste validering             |

Kvalitetsresultater justeres dynamisk:

- **Mislykkede anmodninger** reducere scoren med 10 point
- **Resultatet falder til ≤ 10** → proxy er markeret med `inactive`
- Inaktive fuldmagter er udelukket fra rotation

### Rotationsstrategier

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

### Strømafbryder

1proxy sync har en indbygget afbryder:

- Efter** 5 på hinanden følgende synkroniseringsfejl** , blokeres yderligere synkroniseringsforsøg
- Nulstil med: `resetOneproxyCircuitBreaker()` eller genstart serveren
- Synkroniseringsstatus er tilgængelig på `GET /api/settings/oneproxy?action=status`

### Rydning af 1 proxy proxyer

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-detektion og stealth

OmniRoute dirigerer ikke kun trafik gennem en proxy — det får trafikken til at se legitim ud:

### TLS Fingeraftrykspoofing

Bruger `wreq-js` til at generere browserlignende TLS -fingeraftryk og omgår botdetektionssystemer, der markerer ikke-browser TLS håndtryk.

### CLI Fingerprint Matching

De**CLI Fingerprint Toggle** (`Settings → Security`) omarrangerer HTTP -overskrifter og JSON -legemefelter for at matche den nøjagtige signatur af native CLI binære filer (Claude kode, Codex, osv.). Dette virker** ovenpå** proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Du får begge dele**IP maskering** og** anmode om ægthed** samtidigt.

### Proxy IP Bevarelse

Farvekodede badges i dashboardet viser, hvilket proxyniveau der er aktivt:

| Badge | Niveau      | Mening                                          |
| ----- | ----------- | ----------------------------------------------- |
| 🟢    | Global      | Al trafik går gennem denne proxy                |
| 🟡    | Udbyder     | Kun denne udbyders trafik er proxy              |
| 🔵    | Forbindelse | Denne specifikke key/account bruger denne proxy |

Badget viser også den løste proxy IP til verifikation.

---

## Opstrøms proxytilstande

For udbydere, der bruger CLIProxyAPI -mønsteret, understøtter OmniRoute tre upstream proxy-tilstande:

| Mode          | Beskrivelse                                          |
| ------------- | ---------------------------------------------------- |
| `native`      | OmniRoute håndterer proxy-routing direkte (standard) |
| `cliproxyapi` | Delegerer til en ekstern CLIProxyAPI instans         |
| `fallback`    | Prøver native først, falder tilbage til CLIProxyAPI  |

Konfigurer pr. udbyder:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Dashboard UI

### Indstillinger → Proxy Tab

- **Global proxy** konfiguration (indstil én gang for al trafik)
- **Proxy pr. udbyder** tilsidesætter
- **Per-forbindelse proxy** opgaver
- **Tilslutningstest** gennem konfigureret proxy
- **Farvekodede badges** viser aktivt proxy-niveau

### Indstillinger → 1proxy Tab

- **Synkroniser nu** knappen for at hente gratis proxyer
- **Statistik kort** : Total, Aktiv, Gns. kvalitet, Sidste synkronisering
- **Filtre** : Protokol, landekode, min. kvalitet
- **Proxy bord** med vært, protokol, land, kvalitetsscore, latency, anonymitet, Google -adgang
- **Synkroniseringsstatus** panel med success/failure -sporing og fortløbende fejlantal
- **Ryd alle** for at fjerne alle 1proxy-poster

---

## API reference

### Proxyindstillinger API

| Metode   | Slutpunkt                                      | Beskrivelse                 |
| -------- | ---------------------------------------------- | --------------------------- |
| `GET`    | `/api/settings/proxy`                          | Få fuld proxy-konfiguration |
| `GET`    | `/api/settings/proxy?level=global`             | Få global proxy             |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Få udbyder proxy            |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Løs effektiv proxy          |
| `PUT`    | `/api/settings/proxy`                          | Opdater proxy-konfiguration |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Fjern proxy på niveau       |

### Proxy Registry API

| Metode   | Slutpunkt                                         | Beskrivelse                |
| -------- | ------------------------------------------------- | -------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Liste over alle fuldmagter |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Få proxy ved ID            |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Få fuldmagtsopgaver        |
| `POST`   | `/api/v1/management/proxies`                      | Opret proxy                |
| `PATCH`  | `/api/v1/management/proxies`                      | Opdater proxy              |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Slet proxy                 |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Tving sletning             |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Massetildeling             |
| `GET`    | `/api/v1/management/proxies/assignments`          | Liste opgaver              |
| `GET`    | `/api/v1/management/proxies/health`               | Proxy sundhedsstatistik    |

### Tunneler API

For at udsætte din OmniRoute instans for det offentlige internet (Cloudflare/ngrok/Tailscale) i stedet for at dirigere udgående gennem en proxy, se [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunnelen REST API lever under `/api/tunnels/{cloudflared,ngrok,tailscale}/*` og er ortogonal i forhold til den udgående proxy-kæde, der er dokumenteret ovenfor.

### 1 proxy API

| Metode   | Slutpunkt                              | Beskrivelse                  |
| -------- | -------------------------------------- | ---------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Liste 1 proxy proxyer        |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Få statistik + sync status   |
| `GET`    | `/api/settings/oneproxy?action=status` | Få kun synkroniseringsstatus |
| `POST`   | `/api/settings/oneproxy`               | Udløs synkronisering         |
| `POST`   | `/api/settings/oneproxy/rotate`        | Roter til næste proxy        |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Slet en                      |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Ryd alle                     |

### Upstream Proxy API

| Metode   | Slutpunkt                         | Beskrivelse                        |
| -------- | --------------------------------- | ---------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Hent upstream proxy-konfiguration  |
| `PUT`    | `/api/upstream-proxy/:providerId` | Indstil upstream proxy-tilstand    |
| `DELETE` | `/api/upstream-proxy/:providerId` | Fjern upstream proxy-konfiguration |

---

## Miljøvariabler

| Variabel              | Misligholdelse | Beskrivelse                                                     |
| --------------------- | -------------- | --------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`         | Aktiver SOCKS5 proxy support (standard `true` i `.env.example`) |

---

## Fejlfinding

### "SOCKS5 proxy er deaktiveret"

Indstil `ENABLE_SOCKS5_PROXY=true` i din `.env` fil og genstart.

### "socket hæng op" fejl via proxy

Dette er normalt med billige proxyer, der dropper inaktive forbindelser. OmniRoute håndterer allerede dette ved at:

- Deaktivering af Keep-alive på proxyforbindelser (`keepAliveTimeout: 1`)
- Deaktivering af pipelining (`pipelining: 0`)
- Caching af koordinatorer for at undgå gentagne håndtryk

Hvis det fortsætter, prøv en anden proxy eller brug funktionen 1proxy rotation.

### "unsupported_country_region_territory" under OAuth

Sørg for, at proxyen er konfigureret** før** starter OAuth flowet. OmniRoute dirigerer OAuth -tokenudveksling gennem den konfigurerede proxy. Indstil først en global proxy eller proxy på udbyderniveau, og opret derefter forbindelse.

### Proxy bliver ikke brugt

Tjek opløsningsrækkefølgen:

1. Bekræft med `GET /api/settings/proxy?resolve=your-connection-id`
2. Tjek, om proxyen `status` er `active` (ikke `inactive`)
3. Sørg for, at proxy-tildelingsomfanget matcher din forbindelse

### Synkronisering af 1 proxy mislykkedes

Tjek synkroniseringsstatus:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Hvis `consecutiveFailures >= 5`, er afbryderen udløst. Genstart serveren for at nulstille, eller vent på manuel nulstilling.

---

## Database skema

### `proxy_registry` bord

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

### `proxy_assignments` bord

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

## Proxy-sundhedstjek (v3.8.16 +)

OmniRoute** proxy hurtigt-fejl** mekanisme (`src/lib/proxyHealth.ts`) registrerer døde proxyer i < 2s via et hurtigt TCP forbindelsestjek,** cacher resultatet** for at undgå overhead pr. anmodning.

### Hvordan det virker

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

Uden dette ville en død proxy blokere hver anmodning om den fulde `PROXY_TIMEOUT_MS` (standard 30s), før den mislykkedes.

### Justerbare miljøvariabler

| Variabel                     | Misligholdelse | Formål                                        |
| ---------------------------- | -------------- | --------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`         | TCP forbindelsestimeout pr. sundhedstjek      |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`        | Hvor længe et sundhedsresultat er cachelagret |

**Anbefalede værdier:**

| Scenarie                    | Fast-fail timeout | Cache TTL | Ræsonnement                                                                  |
| --------------------------- | ----------------- | --------- | ---------------------------------------------------------------------------- |
| High-throughput API gateway | 1500 ms           | 60000ms   | Aggressiv fejl-hurtig, længere cache for at reducere kontrol                 |
| Geo-distribuerede noder     | 3000 ms           | 15000ms   | Langsommere netværk har brug for mere tid; kortere cache for hurtig failover |
| Udvikler / test             | 1000 ms           | 10.000 ms | Hurtig iteration på lokale fuldmagter                                        |
| Stealth / anti-detektion    | 2500ms            | 45000ms   | Undgå hurtig sondering, der kan udløse hastighedsgrænser                     |

### Inspicering af fuldmagtssundhed

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

`stale` flaget er `true`, når cache-indgangen har overskredet `HEALTH_CACHE_TTL_MS`, og den næste anmodning vil udløse en ny kontrol.

### Standardindstillinger for Per-Proxy Type

Sundhedstjekket bruger fornuftige standardindstillinger baseret på URL skemaet:

| Ordning                    | Standard port |
| -------------------------- | ------------- |
| `http://`                  | 8080          |
| `https://`                 | 443           |
| `socks5://` / `socks5h://` | 1080          |

Brugerdefinerede porte i URL (`http://host:9999`) har altid forrang over skemastandarden.

---

## Proxyanalyse og observerbarhed

OmniRoute sporer per-proxy-brug for at hjælpe operatører med at diagnosticere routingmønstre, latency-spidser og tilbagevendende fejl.

### Hvad er sporet

For hver anmodning gennem en konfigureret proxy, registrerer OmniRoute :

| Metrisk      | Beskrivelse                                                 |
| ------------ | ----------------------------------------------------------- |
| `proxy_url`  | Fuld proxy URL (med auth-legitimationsoplysninger maskeret) |
| `provider`   | Upstream-udbyder ID (openai, antropisk osv.)                |
| `latency_ms` | Samlet tur-retur-tid inklusive proxy-håndtryk               |
| `connect_ms` | TCP kun tilslutningstid                                     |
| `status`     | HTTP statuskode fra opstrøms                                |
| `error`      | Fejlklasse hvis anmodningen mislykkedes                     |
| `timestamp`  | ISO 8601 UTC                                                |

### Adgang til data

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Det rigtige endepunkt er `/api/usage/proxy-logs` (se `src/app/api/usage/proxy-logs/route.ts`). Dette endepunkt understøtter:

- `GET /api/usage/proxy-logs` — hente proxy logs
- `DELETE /api/usage/proxy-logs` — ryd alle proxy-logfiler

Samlet statistik kan forespørges direkte fra `proxy_logs` tabellen via SQL, hvis det er nødvendigt. Dashboard UI kan tilbyde samlede visninger.

### Fælles mønstre

**Opdag en flagrende proxy** (skifter mellem success/failure):

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

**Find langsomme proxyer** (p95 latens > 2s):

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

## Rotationsstrategi beslutningstræ

Når flere proxyer er tildelt til et omfang, bruger OmniRoute en** rotationsstrategi** at vælge, hvilken der skal bruges til hver anmodning. Strategien konfigureres på omfangsniveau (globalt, pr. udbyder, pr. konto, pr. kombination).

### Tilgængelige strategier

| Strategi             | Hvornår skal bruges                           | Afvejning                                                       |
| -------------------- | --------------------------------------------- | --------------------------------------------------------------- |
| `quality` (standard) | Produktion med fuldmagter af blandet kvalitet | favoriserer højt vurderede fuldmagter; kan sulte lavt vurderede |
| `random`             | Belastningsfordeling, privatliv               | Jævn fordeling; ignorerer kvalitetssignaler                     |
| `sequential`         | Debugging, deterministisk test                | Cykler gennem fuldmagter i rækkefølge; let at ræsonnere om      |

### Beslutningstræ

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

## Automatisk fejludelukkelse for dine egne fuldmagter

1proxy markedspladspuljen nedbryder allerede automatisk mislykkede proxyer af sig selv (se [Proxykvalitetsresultater](#proxy-quality-scores) ). Til fuldmagter** du** tilføjet til registreringsdatabasen, giver baggrundssundhedsplanlæggeren (`src/lib/proxyHealth/scheduler.ts`) den samme "udelukke et dødt medlem fra kæden automatisk" adfærd uden at slette noget:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Sådan passer det ind i en multi-proxy-kæde:

1. Planlæggeren sonderer hver registreret proxy hver `PROXY_HEALTH_INTERVAL_MS` (standard 10 min; minimum 1 min).
2. Efter `PROXY_AUTO_REMOVE_AFTER` i træk** afgørende** fejl (en reel forbindelsesfejl — en timeout eller sondemålets egen 5xx tæller aldrig, se [Proxy Health Checking](#proxy-health-checking-v3816) ), proxyens `status` er sat til `dead`.
3. `dead` er en af de statusser, som live-status-filteret, der bruges af pool/rotation opløsning, udelukker, så en scopes rotation (round-robin / random / sticky / latency — se [Rotation Strategy Decision Tree](#rotation-strategy-decision-tree) ) stopper straks med at give den proxy til nye anmodninger. Ingen andre proxyer i poolen er påvirket, og hele poolen falder aldrig lydløst tilbage til en [direkte](#4-level-proxy-system) forbindelse —
4. Planlæggeren bliver ved med at sondere `dead` proxyer i det samme interval. Den næste vellykkede sonde vender `status` tilbage til `active`, og den går igen i rotation — der kræves ingen manuel gentilføjelse.

Dette er bevidst** opt-in og ikke-destruktiv** : Som standard tæller og logger skemalæggeren kun fejl (se politik C i `decision.ts`), og `PROXY_AUTO_DISABLE` sletter aldrig en række — det er det, det separate, mere aggressive `PROXY_AUTO_REMOVE` flag er til for. Hvis begge er sat til `true`, vinder `PROXY_AUTO_REMOVE` (en proxy, der er ved at blive slettet, kan ikke bruges til en soft-deaktivering imellem). Se [Environment Config-](../reference/ENVIRONMENT.md) referencen for den fulde variabelliste.

---

> 📖** Relateret dokumentation:**
>
> - [Brugervejledning](../guides/USER_GUIDE.md) — Generel opsætning og konfiguration - [API Reference](../reference/API_REFERENCE.md) — Fuld API dokumentation - [Environment Config](../reference/ENVIRONMENT.md) — Alle miljøvariabler
