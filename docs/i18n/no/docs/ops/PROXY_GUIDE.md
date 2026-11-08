# 🌐 OmniRoute Proxy Guide (Norsk)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Omgå geografiske blokkeringer, beskytt identiteten din og rute AI -trafikk gjennom en hvilken som helst proxy- — med null konfigurasjonskompleksitet.**

OmniRoute inkluderer et fullverdig proxy-administrasjonssystem som lar deg rute oppstrøms AI leverandørtrafikk gjennom HTTP, HTTPS eller SOCKS5 proxyer. Enten du er i et blokkert område, trenger IP rotasjon eller vil ha stealth fingeravtrykk — dekker denne veiledningen alt.

---

## Innholdsfortegnelse

- [Hvorfor bruke proxyer?](#why-use-proxies)
- [Oversikt over arkitektur](#architecture-overview)
- [4-nivå proxy-system](#4-level-proxy-system)
- [Fullmaktsregister (CRUD)](#proxy-registry-crud)
- [1proxy gratis markedsplass](#1proxy-free-proxy-marketplace)
- [Proxy-rotasjon](#proxy-rotation)
- [Anti-deteksjon og stealth](#anti-detection--stealth)
- [Oppstrøms proxy-moduser](#upstream-proxy-modes)
- [Dashboard UI](#dashboard-ui)
- [API Referanse](#api-reference)
- [Miljøvariabler](#environment-variables)
- [Feilsøking](#troubleshooting)

---

## Hvorfor bruke proxyer?

Mange AI leverandører begrenser tilgangen etter geografisk region. Utviklere i** Russland, Kina, Iran, Cuba, Tyrkia** , og andre land støter på feil som:

```
unsupported_country_region_territory
```

Selv utenfor blokkerte områder er proxyer nyttige for:

| Bruk Case             | Beskrivelse                                                         |
| --------------------- | ------------------------------------------------------------------- |
| **Geografisk bypass** | Få tilgang til OpenAI, Anthropic, Codex, Copilot fra blokkerte land |
| **IP rotasjon**       | Fordel forespørsler på flere IPs for å unngå hastighetsbegrensning  |
| **Privatliv**         | Skjul din ekte IP fra oppstrømsleverandører                         |
| **Overholdelse**      | Ruter trafikk gjennom spesifikke jurisdiksjoner                     |
| **Testing**           | Simuler forespørsler fra forskjellige regioner                      |

---

## Oversikt over arkitektur

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

### Nøkkelkomponenter

| Komponent              | Fil                                          | Rolle                                                         |
| ---------------------- | -------------------------------------------- | ------------------------------------------------------------- |
| **Fullmaktsregister**  | `src/lib/db/proxies.ts`                      | CRUD for proxy-oppføringer + scope-tilordninger               |
| **Fullmaktsavsender**  | `open-sse/utils/proxyDispatcher.ts`          | Oppretter `undici` ProxyAgent/SOCKS -ekspeditører med caching |
| **Fullmaktshenting**   | `open-sse/utils/proxyFetch.ts`               | Omslutter `fetch()` med proxy-dispatcher-injeksjon            |
| **Innstillinger Rute** | `src/app/api/settings/proxy/route.ts`        | Eldre proxy-konfigurasjon API (GET/PUT/DELETE)                |
| **Forvaltningsrute**   | `src/app/api/v1/management/proxies/route.ts` | Register CRUD API (GET/POST/PATCH/DELETE)                     |
| **1 proxy DB**         | `src/lib/db/oneproxy.ts`                     | Gratis proxy markedsplass utholdenhet                         |

---

## Standard proxy-status for nye kontoer

I** Innstillinger → Proxy → Global konfigurasjon** , bruk** Aktiver proxy som standard for nye tilkoblinger** for å velge den opprinnelige proxy-statusen for nylig lagt til leverandørkontoer.

Den nye innstillingen kontrollerer den opprinnelige proxy-statusen til nylig lagt til leverandørkontoer. Den endrer ikke eksisterende kontoer eller erstatter den globale proxy-svitsjen. Startverdien bevarer den forrige oppførselen. Slå den av én gang for å opprette fremtidige kontoer med proxy deaktivert som standard.

Preferansen lagres som `defaultNewConnectionProxyEnabled` gjennom de eksisterende innstillingene API. Den er standard til `true` når den aldri lagres. Lagring av `false` trer i kraft for påfølgende nye kontoer uten omstart. `POST /api/providers` aksepterer en valgfri streng boolsk `proxyEnabled`; en eksplisitt `true` eller `false` har forrang over opprettelsesstandarden. Utelatelse av en duplikatkonto eller OAuth reconnect bevarer kontoens lagrede tilstand. Individuelle kontoer kan fortsatt aktiveres eller deaktiveres etterpå.

Selektive leverandøroverføringer bruker destinasjonsinstallasjonens standard for nye kontoer og bevarer destinasjonspolicyen når de erstatter eksisterende kontoer. Proxy-vekslere er ikke bærbare overføringsfelt. Full sikkerhetskopigjenoppretting og historisk JSON/SQL -migrering beholder sin eksisterende gjenopprettingssemantikk, inkludert lagrede kontoverdier og eldre skjemastandarder; en fullstendig gjenoppretting av innstillinger kan også gjenopprette denne preferansen.

Denne preferansen tildeler ikke en proxy eller fastslår at en er sunn eller i bruk. Faktisk ruting avhenger fortsatt av den globale proxy-svitsjen og gjeldende proxy-konfigurasjon. Syntetiske leverandører uten en vedvarende konto, OAuth -trafikk før kontooppretting, environment/system proxyer og eksterne backends nettverk er utenfor omfanget.

## 4-nivå proxy-system

OmniRoute støtter proxy-konfigurasjon på** fire uavhengige omfang** , løst i prioritert rekkefølge:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Hvordan oppløsning fungerer

Når OmniRoute sender en forespørsel til en oppstrømsleverandør, kaller den `resolveProxyForConnectionFromRegistry()` som sjekker hvert nivå i rekkefølge:

1. **Kontonivå** — Er det en proxy tilordnet denne spesifikke tilkoblingen ID?
2. **Leverandørnivå** — Er det en proxy tilordnet denne leverandøren (f.eks. `openai`)?
3. **Globalt nivå** — Er det konfigurert en global proxy?
4. **Ingen proxy** — Direkte tilkobling til leverandøren.

Den første kampen vinner. Dette betyr at du kan angi en global proxy som en reserve, men overstyre den for spesifikke leverandører eller tilkoblinger.

### Hva får fullmakt

| Trafikktype            | Fullmakt? | Notater                                      |
| ---------------------- | --------- | -------------------------------------------- |
| Chatfullføringer       | ✅        | Alle `/v1/chat/completions` forespørsler     |
| Innstøpninger          | ✅        | `/v1/embeddings`                             |
| Bildegenerering        | ✅        | `/v1/images/generations`                     |
| Lyd (TTS/STT)          | ✅        | `/v1/audio/*`                                |
| OAuth token utveksling | ✅        | Løser `unsupported_country_region_territory` |
| Tilkoblingstester      | ✅        | "Test tilkobling"-knappen bruker proxy       |
| Token-oppdatering      | ✅        | Bakgrunn OAuth fornyelse                     |
| Modellsynkronisering   | ✅        | Modellliste og funn                          |

---

## Fullmaktsregister (CRUD)

Proxy-registeret er en SQLite tabell (`proxy_registry`) som lagrer alle proxyene dine. Hver proxy har:

| Felt       | Type    | Beskrivelse                          |
| ---------- | ------- | ------------------------------------ |
| `id`       | UUID    | Unik identifikator                   |
| `name`     | String  | Etikett som kan leses av mennesker   |
| `type`     | String  | Protokoll: `http`, `https`, `socks5` |
| `host`     | String  | Proxy-vertsnavn eller IP             |
| `port`     | Heltall | Portnummer                           |
| `username` | String  | Auth-brukernavn (kryptert i hvile)   |
| `password` | String  | Auth-passord (kryptert i hvile)      |
| `region`   | String  | Etikett for geografisk område        |
| `notes`    | String  | Fritekstnotater                      |
| `status`   | String  | `active` eller `inactive`            |
| `source`   | String  | `manual` eller `oneproxy`            |

### Opprette en proxy

**Via Dashboard:**

1. Gå til** Innstillinger → Proxy**
2. Klikk** Legg til proxy**
3. Fyll inn påloggingsinformasjonen for type, vert, port og valgfri autentisering
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

### Oppdatering av en proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Note:** Legitimasjonen er bevart med mindre du eksplisitt sender ikke-tomme erstatninger. Sending av tomme strenger for `username`/`password` vil beholde de lagrede verdiene.

### Sletting av en proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Oppføringsfullmakter

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Tilordne fullmakter til Scopes

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

### Løser effektiv proxy

Sjekk hvilken proxy som skal brukes for en gitt tilkobling:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Returnerer den løste proxyen med nivået (`account`, `provider` eller `global`) og kilden.

### Masseoppdrag

Tilordne én proxy til flere leverandører eller tilkoblinger samtidig:

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

Fullmakter er inkludert i**Backup/Restore** system. Når du eksporterer OmniRoute konfigurasjonen:

1. Gå til** Dashboard → Innstillinger → Backup**
2. Klikk** Eksport** — proxy-register og oppdrag er inkludert
3. Klikk på for å gjenopprette** Import** og last opp sikkerhetskopifilen

Proxy-registeret støtter også** upsert av vert + port** — hvis du importerer en proxy som allerede eksisterer (samme vert og port), oppdateres den i stedet for å lage en duplikat.

### Eldre migrasjon

Hvis du konfigurerte proxyer i en eldre versjon (pre-register), migrerer OmniRoute dem automatisk:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Dette skjer én gang ved første oppstart etter oppgradering. Bruk `migrateLegacyProxyConfigToRegistry({ force: true })` for å kjøre på nytt.

---

## 1proxy gratis proxy-markedsplass

> 🆕** Bidraget av [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (utgave [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integreres med** [1 proxy](https://1proxy-api.aitradepulse.com)** fellesskapsplattform å gi tilgang til** hundrevis av gratis, validerte proxyer** fra hele verden. Dette er perfekt for brukere som ikke har sin egen proxy-infrastruktur.

### Hvordan det fungerer

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Synkroniser** — OmniRoute henter validerte proxyer fra 1proxy API
2. **Lager** — Proxyer lagres i samme `proxy_registry` tabell som `source = 'oneproxy'`
3. **Filter** — Filtrer etter protokoll, land, kvalitetspoeng
4. **Rotere** — Velg den beste proxyen ved å bruke kvalitets-, tilfeldige eller sekvensielle strategier
5. **Automatisk nedbrytning** — Mislykkede fullmakter får redusert kvalitetspoengsum; under terskel → markert som inaktiv

### Synkroniserer proxyer

**Via Dashboard:**

1. Gå til** Innstillinger → 1proxy** fanen
2. Klikk** "Synkroniser nå"**
3. Se statistikk: totalt antall fullmakter, antall aktive, gjennomsnittlig kvalitet, fordeling etter land

**Via API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtrering av proxyer

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

### Proxy kvalitetspoeng

Hver 1proxy proxy kommer med metadata:

| Felt            | Beskrivelse                                    |
| --------------- | ---------------------------------------------- |
| `qualityScore`  | 0-100 rangering fra 1 proxy-validering         |
| `latencyMs`     | Målt nettverksforsinkelse                      |
| `anonymity`     | `transparent`, `anonymous` eller `elite`       |
| `googleAccess`  | Om proxyen kan få tilgang til Google tjenester |
| `countryCode`   | To-bokstavs ISO -landskode                     |
| `lastValidated` | Tidsstempel for siste validering               |

Kvalitetspoeng justeres dynamisk:

- **Mislykkede forespørsler** redusere poengsummen med 10 poeng
- **Poengsummen synker til ≤ 10** → proxy er merket med `inactive`
- Inaktive fullmakter er ekskludert fra rotasjon

### Rotasjonsstrategier

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

### Strømbryter

1proxy sync har en innebygd kretsbryter:

- Etter** 5 påfølgende synkroniseringsfeil** , blokkeres ytterligere synkroniseringsforsøk
- Tilbakestill med: `resetOneproxyCircuitBreaker()` eller start serveren på nytt
- Synkroniseringsstatus er tilgjengelig på `GET /api/settings/oneproxy?action=status`

### Sletting av 1proxy proxyer

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-deteksjon og stealth

OmniRoute ruter ikke bare trafikk gjennom en proxy — det får trafikken til å se legitim ut:

### TLS Fingeravtrykkspoofing

Bruker `wreq-js` til å generere nettleserlignende TLS -fingeravtrykk, og omgår botdeteksjonssystemer som flagger TLS -håndtrykk som ikke er nettlesere.

### CLI Fingerprint Matching

De**CLI Fingerprint Toggle** (`Settings → Security`) omorganiserer HTTP overskrifter og JSON kroppsfelt for å matche den nøyaktige signaturen til opprinnelige CLI binærfiler (Claude -kode, Codex, etc.). Dette fungerer** på toppen av** proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Du får begge deler**IP maskering** og** be om autentisitet** samtidig.

### Proxy IP Bevaring

Fargekodede merker i dashbordet viser hvilket proxy-nivå som er aktivt:

| Skilt | Nivå        | Betydning                                       |
| ----- | ----------- | ----------------------------------------------- |
| 🟢    | Global      | All trafikk går gjennom denne proxyen           |
| 🟡    | Leverandør  | Bare denne leverandørens trafikk er proxy       |
| 🔵    | Forbindelse | Denne spesifikke key/account bruker denne proxy |

Merket viser også den løste proxy IP for verifisering.

---

## Oppstrøms proxy-moduser

For leverandører som bruker CLIProxyAPI -mønsteret, støtter OmniRoute tre oppstrøms proxy-moduser:

| Modus         | Beskrivelse                                         |
| ------------- | --------------------------------------------------- |
| `native`      | OmniRoute håndterer proxy-ruting direkte (standard) |
| `cliproxyapi` | Delegerer til en ekstern CLIProxyAPI instans        |
| `fallback`    | Prøver native først, faller tilbake til CLIProxyAPI |

Konfigurer per leverandør:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Dashboard UI

### Innstillinger → Proxy Tab

- **Global proxy** konfigurasjon (sett én gang for all trafikk)
- **Per-leverandør proxy** overstyrer
- **Proxy per tilkobling** oppdrag
- **Tilkoblingstest** gjennom konfigurert proxy
- **Fargekodede merker** viser aktivt proxy-nivå

### Innstillinger → 1proxy Tab

- **Synkroniser nå** knappen for å hente gratis proxyer
- **Statistikk kort** : Total, Aktiv, Gj.sn. kvalitet, Siste synkronisering
- **Filtre** : Protokoll, Landskode, Min kvalitet
- **Fullmaktstabell** med vert, protokoll, land, kvalitetspoeng, ventetid, anonymitet, Google -tilgang
- **Synkroniseringsstatus** panel med success/failure -sporing og påfølgende feiltelling
- **Fjern alle** for å fjerne alle 1proxy-oppføringer

---

## API Referanse

### Proxy-innstillinger API

| Metode   | Endepunkt                                      | Beskrivelse                  |
| -------- | ---------------------------------------------- | ---------------------------- |
| `GET`    | `/api/settings/proxy`                          | Få full proxy-konfigurasjon  |
| `GET`    | `/api/settings/proxy?level=global`             | Få global proxy              |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Få leverandørproxy           |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Løs effektiv proxy           |
| `PUT`    | `/api/settings/proxy`                          | Oppdater proxy-konfigurasjon |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Fjern proxy på nivå          |

### Fullmaktsregister API

| Metode   | Endepunkt                                         | Beskrivelse               |
| -------- | ------------------------------------------------- | ------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | List opp alle fullmakter  |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Få proxy av ID            |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Få proxy-oppdrag          |
| `POST`   | `/api/v1/management/proxies`                      | Opprett proxy             |
| `PATCH`  | `/api/v1/management/proxies`                      | Oppdater proxy            |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Slett proxy               |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Tving sletting            |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Massetilordning           |
| `GET`    | `/api/v1/management/proxies/assignments`          | List opp oppgaver         |
| `GET`    | `/api/v1/management/proxies/health`               | Helsestatistikk for proxy |

### Tunneler API

For å eksponere OmniRoute forekomsten din for det offentlige Internett (Cloudflare/ngrok/Tailscale) i stedet for å rute utgående gjennom en proxy, se [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunnelen REST API lever under `/api/tunnels/{cloudflared,ngrok,tailscale}/*` og er ortogonal til den utgående proxy-kjeden som er dokumentert ovenfor.

### 1 proxy API

| Metode   | Endepunkt                              | Beskrivelse                  |
| -------- | -------------------------------------- | ---------------------------- |
| `GET`    | `/api/settings/oneproxy`               | List opp 1 proxy-fullmakter  |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Få statistikk + sync status  |
| `GET`    | `/api/settings/oneproxy?action=status` | Få kun synkroniseringsstatus |
| `POST`   | `/api/settings/oneproxy`               | Utløs synkronisering         |
| `POST`   | `/api/settings/oneproxy/rotate`        | Roter til neste proxy        |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Slett en                     |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Fjern alle                   |

### Oppstrøms proxy API

| Metode   | Endepunkt                         | Beskrivelse                         |
| -------- | --------------------------------- | ----------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Få oppstrøms proxy-konfigurasjon    |
| `PUT`    | `/api/upstream-proxy/:providerId` | Sett oppstrøms proxy-modus          |
| `DELETE` | `/api/upstream-proxy/:providerId` | Fjern oppstrøms proxy-konfigurasjon |

---

## Miljøvariabler

| Variabel              | Misligholde | Beskrivelse                                                    |
| --------------------- | ----------- | -------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`      | Aktiver SOCKS5 proxy-støtte (standard `true` i `.env.example`) |

---

## Feilsøking

### "SOCKS5 proxy er deaktivert"

Sett `ENABLE_SOCKS5_PROXY=true` i `.env` filen og start på nytt.

### "socket henge opp" feil via proxy

Dette er normalt med billige proxyer som slipper ledige tilkoblinger. OmniRoute håndterer allerede dette ved:

- Deaktivering av keep-alive på proxy-tilkoblinger (`keepAliveTimeout: 1`)
- Deaktivering av pipelining (`pipelining: 0`)
- Bufre sender for å unngå gjentatte håndtrykk

Hvis det vedvarer, prøv en annen proxy eller bruk 1proxy-rotasjonsfunksjonen.

### "unsupported_country_region_territory" under OAuth

Kontroller at proxyen er konfigurert** før** starter OAuth strømmen. OmniRoute ruter OAuth -tokenutveksling gjennom den konfigurerte proxyen. Angi først en global proxy eller proxy på leverandørnivå, og koble deretter til.

### Proxy blir ikke brukt

Sjekk oppløsningsrekkefølgen:

1. Bekreft med `GET /api/settings/proxy?resolve=your-connection-id`
2. Sjekk om proxyen `status` er `active` (ikke `inactive`)
3. Sørg for at proxy-tildelingsomfanget samsvarer med tilkoblingen din

### 1 proxy-synkronisering mislykkes

Sjekk synkroniseringsstatusen:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Hvis `consecutiveFailures >= 5`, har effektbryteren løst ut. Start serveren på nytt for å tilbakestille, eller vent på manuell tilbakestilling.

---

## Databaseskjema

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

## Proxy Health Checking (v3.8.16 +)

OmniRoute sine** proxy rask-mislykkes** mekanisme (`src/lib/proxyHealth.ts`) oppdager døde proxyer i < 2s via en rask TCP -tilkoblingssjekk, deretter** cacher resultatet** for å unngå overhead per forespørsel.

### Hvordan det fungerer

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

Uten dette ville en død proxy blokkert hver forespørsel om full `PROXY_TIMEOUT_MS` (standard 30s) før den mislyktes.

### Justerbare miljøvariabler

| Variabel                     | Misligholde | Hensikt                                       |
| ---------------------------- | ----------- | --------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`      | TCP tidsavbrudd for tilkobling per helsesjekk |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`     | Hvor lenge et helseresultat er bufret         |

**Anbefalte verdier:**

| Scenario                             | Fast-fail timeout | Cache TTL | Argumentasjon                                                     |
| ------------------------------------ | ----------------- | --------- | ----------------------------------------------------------------- |
| API gateway med høy gjennomstrømning | 1500 ms           | 60 000 ms | Aggressiv feil-rask, lengre hurtigbuffer for å redusere sjekker   |
| Geo-distribuerte noder               | 3000 ms           | 15 000 ms | Tregere nettverk trenger mer tid; kortere cache for rask failover |
| Utvikler / testing                   | 1000 ms           | 10 000 ms | Rask iterasjon på lokale fullmakter                               |
| Stealth / anti-deteksjon             | 2500 ms           | 45 000 ms | Unngå rask sondering som kan utløse hastighetsgrenser             |

### Inspiserer fullmaktshelse

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

`stale` flagget er `true` når cache-oppføringen har overskredet `HEALTH_CACHE_TTL_MS` og neste forespørsel vil utløse en ny sjekk.

### Standarder per proxy-type

Helsesjekken bruker fornuftige standardinnstillinger basert på URL skjemaet:

| Opplegg                    | Standard port |
| -------------------------- | ------------- |
| `http://`                  | 8080          |
| `https://`                 | 443           |
| `socks5://` / `socks5h://` | 1080          |

Egendefinerte porter i URL (`http://host:9999`) har alltid forrang over skjemastandarden.

---

## Proxy-analyse og observerbarhet

OmniRoute sporer per-proxy-bruk for å hjelpe operatører med å diagnostisere rutingmønstre, latency-spiker og tilbakevendende feil.

### Hva spores

For hver forespørsel gjennom en konfigurert proxy, registrerer OmniRoute :

| Metrisk      | Beskrivelse                                             |
| ------------ | ------------------------------------------------------- |
| `proxy_url`  | Full proxy URL (med autentiseringslegitimasjon maskert) |
| `provider`   | Oppstrømsleverandør ID (openai, antropisk, etc.)        |
| `latency_ms` | Total tur-retur-tid inkludert proxy-håndtrykk           |
| `connect_ms` | TCP kun tilkoblingstid                                  |
| `status`     | HTTP statuskode fra oppstrøms                           |
| `error`      | Feilklasse hvis forespørselen mislyktes                 |
| `timestamp`  | ISO 8601 UTC                                            |

### Få tilgang til dataene

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Det virkelige endepunktet er `/api/usage/proxy-logs` (se `src/app/api/usage/proxy-logs/route.ts`). Dette endepunktet støtter:

- `GET /api/usage/proxy-logs` — hente proxy-logger
- `DELETE /api/usage/proxy-logs` — slett alle proxy-logger

Samlet statistikk kan søkes direkte fra `proxy_logs` tabellen via SQL om nødvendig. Dashbordet UI kan tilby samlede visninger.

### Vanlige mønstre

**Oppdag en flagrende proxy** (veksler mellom success/failure):

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

**Finn trege proxyer** (p95 latens > 2s):

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

## Rotasjonsstrategi beslutningstre

Når flere proxyer er tilordnet et omfang, bruker OmniRoute en** rotasjonsstrategi** å velge hvilken som skal brukes for hver forespørsel. Strategien konfigureres på omfangsnivå (globalt, per leverandør, per konto, per kombinasjon).

### Tilgjengelige strategier

| Strategi             | Når du skal bruke                             | Avveining                                                   |
| -------------------- | --------------------------------------------- | ----------------------------------------------------------- |
| `quality` (standard) | Produksjon med fullmakter av blandet kvalitet | favoriserer høyt rangerte proxyer; kan sulte lavt rangerte  |
| `random`             | Lastfordeling, personvern                     | Jevn fordeling; ignorerer kvalitetssignaler                 |
| `sequential`         | Debugging, deterministisk testing             | Sykler gjennom proxyer i rekkefølge; lett å resonnere rundt |

### Beslutningstre

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

## Automatisk utestenging av feil for dine egne proxyer

1proxy markedsplass-poolen degraderer allerede mislykkede proxyer automatisk på egen hånd (se [Proxy-kvalitetspoeng](#proxy-quality-scores) ). For fullmakter** du** lagt til i registeret, gir bakgrunnshelseplanleggeren (`src/lib/proxyHealth/scheduler.ts`) den samme "ekskluder et dødt medlem fra kjeden automatisk", uten å slette noe:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Slik passer den inn i en multi-proxy-kjede:

1. Planleggeren sonderer hver registrerte proxy hver `PROXY_HEALTH_INTERVAL_MS` (standard 10 min; minimum 1 min).
2. Etter `PROXY_AUTO_REMOVE_AFTER` på rad** avgjørende** feil (en reell tilkoblingsfeil — en timeout eller sondemålets egen 5xx teller aldri, se [Proxy Health Checking](#proxy-health-checking-v3816) ), proxyens `status` er satt til `dead`.
3. `dead` er en av statusene som live-status-filteret som brukes av pool/rotation oppløsning utelukker, så et skops rotasjon (round-robin / random / sticky / latency — se [Rotation Strategy Decision Tree](#rotation-strategy-decision-tree) ) slutter umiddelbart å gi den proxyen til nye forespørsler. Ingen andre proxyer i bassenget er berørt, og hele bassenget faller aldri stille tilbake til en direkte forbindelse — se [4-Level Proxy System](#4-level-proxy-system) feillukket vakt.
4. Planleggeren fortsetter å undersøke `dead` proxyer på samme intervall. Den neste vellykkede sonden snur `status` tilbake til `active` og den går inn igjen i rotasjon — uten manuell re-add.

Dette er bevisst** opt-in og ikke-destruktiv** : som standard teller og logger planleggeren bare feil (se policy C i `decision.ts`), og `PROXY_AUTO_DISABLE` sletter aldri en rad — som er det det separate, mer aggressive `PROXY_AUTO_REMOVE` flagget er til for. Hvis begge er satt til `true`, vinner `PROXY_AUTO_REMOVE` (en proxy som skal slettes har ingen bruk for en myk deaktivering i mellom). Se [Environment Config-](../reference/ENVIRONMENT.md) referansen for hele variabellisten.

---

> 📖** Relatert dokumentasjon:**
>
> - [Brukerveiledning](../guides/USER_GUIDE.md) — Generell oppsett og konfigurasjon - [API Referanse](../reference/API_REFERENCE.md) — Full API dokumentasjon - [Environment Config](../reference/ENVIRONMENT.md) — Alle miljøvariabler
