# 🌐 OmniRoute Proxy Guide (Svenska)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Gå förbi geografiska block, skydda din identitet och dirigera AI trafik genom valfri proxy- — med noll konfigurationskomplexitet.**

OmniRoute inkluderar ett fullfjädrat proxyhanteringssystem som låter dig dirigera uppströms AI leverantörstrafik genom HTTP, HTTPS eller SOCKS5 proxies. Oavsett om du befinner dig i ett blockerat område, behöver IP rotation eller vill ha smygfingeravtryck — täcker denna guide allt.

---

## Innehållsförteckning

- [Varför använda proxyservrar?](#why-use-proxies)
- [Arkitektur översikt](#architecture-overview)
- [4-nivå proxysystem](#4-level-proxy-system)
- [Proxyregistret (CRUD)](#proxy-registry-crud)
- [1proxy gratis marknadsplats](#1proxy-free-proxy-marketplace)
- [Proxy Rotation](#proxy-rotation)
- [Anti-detektion och smygande](#anti-detection--stealth)
- [Uppströms proxylägen](#upstream-proxy-modes)
- [Instrumentbräda UI](#dashboard-ui)
- [API referens](#api-reference)
- [Miljövariabler](#environment-variables)
- [Felsökning](#troubleshooting)

---

## Varför använda proxyservrar?

Många AI leverantörer begränsar åtkomsten efter geografisk region. Utvecklare i** Ryssland, Kina, Iran, Kuba, Turkiet** , och andra länder stöter på fel som:

```
unsupported_country_region_territory
```

Även utanför blockerade regioner är proxyservrar användbara för:

| Användningsfall              | Beskrivning                                                                |
| ---------------------------- | -------------------------------------------------------------------------- |
| **Geografisk förbikoppling** | Få tillgång till OpenAI, Anthropic, Codex, Copilot från blockerade länder  |
| **IP rotation**              | Fördela förfrågningar över flera IPs för att undvika hastighetsbegränsning |
| **Privatliv**                | Dölj din riktiga IP från uppströmsleverantörer                             |
| **Efterlevnad**              | Led trafik genom specifika jurisdiktioner                                  |
| **Testning**                 | Simulera förfrågningar från olika regioner                                 |

---

## Arkitektur översikt

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

### Nyckelkomponenter

| Komponent              | Fil                                          | Roll                                                     |
| ---------------------- | -------------------------------------------- | -------------------------------------------------------- |
| **Fullmaktsregistret** | `src/lib/db/proxies.ts`                      | CRUD för proxyposter + scope tilldelningar               |
| **Fullmaktssändare**   | `open-sse/utils/proxyDispatcher.ts`          | Skapar `undici` ProxyAgent/SOCKS -avsändare med cachning |
| **Hämta proxy**        | `open-sse/utils/proxyFetch.ts`               | Omsluter `fetch()` med proxy dispatcher-injektion        |
| **Inställningar Rutt** | `src/app/api/settings/proxy/route.ts`        | Äldre proxykonfiguration API (GET/PUT/DELETE)            |
| **Ledningsväg**        | `src/app/api/v1/management/proxies/route.ts` | Registry CRUD API (GET/POST/PATCH/DELETE)                |
| **1 proxy DB**         | `src/lib/db/oneproxy.ts`                     | Gratis proxy marknadsplats uthållighet                   |

---

## Standard proxystatus för nya konton

I** Inställningar → Proxy → Global konfiguration** , använda** Aktivera proxy som standard för nya anslutningar** för att välja det ursprungliga proxyläget för nyligen tillagda leverantörskonton.

Den nya inställningen styr det initiala proxytillståndet för nyligen tillagda leverantörskonton. Det ändrar inte befintliga konton eller ersätter den globala proxyswitchen. Dess initiala värde bevarar det tidigare beteendet. Stäng av den en gång för att skapa framtida konton med proxy inaktiverad som standard.

Inställningen lagras som `defaultNewConnectionProxyEnabled` genom de befintliga inställningarna API. Den har som standard `true` när den aldrig sparas. Att spara `false` träder i kraft för efterföljande nya konton utan omstart. `POST /api/providers` accepterar en valfri strikt boolesk `proxyEnabled`; en explicit `true` eller `false` har företräde framför skapandets standard. Utelämnande av ett dubblettkonto eller OAuth -återanslutning bevarar kontots lagrade tillstånd. Individuella konton kan fortfarande aktiveras eller inaktiveras efteråt.

Selektiva leverantörsöverföringar använder destinationsinstallationens standard för nya konton och behåller destinationspolicyn när befintliga konton ersätts. Proxyomkopplare är inte bärbara överföringsfält. Fullständig säkerhetskopieringsåterställning och historisk JSON/SQL -migrering behåller sin befintliga återställningssemantik, inklusive sparade kontovärden och äldre schemastandarder; en fullständig återställning av inställningar kan också återställa denna inställning.

Denna inställning tilldelar inte en proxy eller fastställer att en är frisk eller används. Faktisk routing beror fortfarande på den globala proxyswitchen och tillämplig proxykonfiguration. Syntetiska leverantörer utan ett beständigt konto, OAuth trafik innan kontot skapades, environment/system proxyer och externa backends nätverk ligger utanför dess räckvidd.

## 4-nivå proxysystem

OmniRoute stöder proxykonfiguration på** fyra oberoende omfattningar** , löst i prioriterad ordning:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Hur upplösning fungerar

När OmniRoute skickar en förfrågan till en uppströmsleverantör anropar den `resolveProxyForConnectionFromRegistry()` som kontrollerar varje nivå i ordning:

1. **Kontonivå** — Finns det en proxy tilldelad denna specifika anslutning ID?
2. **Leverantörsnivå** — Finns det en proxy tilldelad till denna leverantör (t.ex. `openai`)?
3. **Global nivå** — Finns det en global proxy konfigurerad?
4. **Ingen proxy** — Direktanslutning till leverantören.

Första matchen vinner. Det betyder att du kan ställa in en global proxy som reserv men åsidosätta den för specifika leverantörer eller anslutningar.

### Vad får proxy

| Trafiktyp            | Fullmakt? | Anteckningar                                 |
| -------------------- | --------- | -------------------------------------------- |
| Chattavslut          | ✅        | Alla `/v1/chat/completions` -förfrågningar   |
| Inbäddningar         | ✅        | `/v1/embeddings`                             |
| Bildgenerering       | ✅        | `/v1/images/generations`                     |
| Ljud (TTS/STT)       | ✅        | `/v1/audio/*`                                |
| OAuth token utbyte   | ✅        | Löser `unsupported_country_region_territory` |
| Anslutningstester    | ✅        | "Testa anslutning"-knappen använder proxy    |
| Token uppdatering    | ✅        | Bakgrund OAuth förnyelse                     |
| Modellsynkronisering | ✅        | Modelllistning och upptäckt                  |

---

## Proxyregistret (CRUD)

Proxyregistret är en SQLite tabell (`proxy_registry`) som lagrar alla dina proxyservrar. Varje proxy har:

| Fält       | Typ    | Beskrivning                          |
| ---------- | ------ | ------------------------------------ |
| `id`       | UUID   | Unik identifierare                   |
| `name`     | Sträng | Människoläsbar etikett               |
| `type`     | Sträng | Protokoll: `http`, `https`, `socks5` |
| `host`     | Sträng | Proxy värdnamn eller IP              |
| `port`     | Heltal | Portnummer                           |
| `username` | Sträng | Auth användarnamn (krypterat i vila) |
| `password` | Sträng | Auth-lösenord (krypterat i vila)     |
| `region`   | Sträng | Etikett för geografisk region        |
| `notes`    | Sträng | Fritextanteckningar                  |
| `status`   | Sträng | `active` eller `inactive`            |
| `source`   | Sträng | `manual` eller `oneproxy`            |

### Skapa en proxy

**Via instrumentpanelen:**

1. Gå till** Inställningar → Proxy**
2. Klick** Lägg till proxy**
3. Fyll i typ, värd, port och valfria autentiseringsuppgifter
4. Spara

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

### Uppdatera en proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Notera:** Inloggningsuppgifter bevaras om du inte uttryckligen skickar icke-tomma ersättningar. Att skicka tomma strängar för `username`/`password` kommer att behålla de lagrade värdena.

### Ta bort en proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Lista fullmakter

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Tilldela fullmakter till scopes

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

### Löser effektiv proxy

Kontrollera vilken proxy som skulle användas för en given anslutning:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Returnerar den lösta proxyn med dess nivå (`account`, `provider` eller `global`) och källa.

### Masstilldelning

Tilldela en proxy till flera leverantörer eller anslutningar samtidigt:

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

Fullmakt ingår i**Backup/Restore** system. När du exporterar din OmniRoute konfiguration:

1. Gå till** Dashboard → Inställningar → Backup**
2. Klick** Exportera** — proxy register och uppdrag ingår
3. Klicka på för att återställa** Importera** och ladda upp säkerhetskopian

Proxyregistret stöder också** upsert av värd + port** — om du importerar en proxy som redan finns (samma värd och port), uppdateras den istället för att skapa en dubblett.

### Äldre migration

Om du konfigurerade proxyservrar i en äldre version (förregistrering), migrerar OmniRoute dem automatiskt:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Detta händer en gång vid första uppstart efter uppgradering. Använd `migrateLegacyProxyConfigToRegistry({ force: true })` för att köra igen.

---

## 1proxy gratis proxymarknadsplats

> 🆕** Bidragit av [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (utgåva [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integreras med** [1 proxy](https://1proxy-api.aitradepulse.com)** gemenskapsplattform att ge tillgång till** hundratals gratis, validerade proxyservrar** från hela världen. Detta är perfekt för användare som inte har sin egen proxyinfrastruktur.

### Hur det fungerar

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Synkronisera** — OmniRoute hämtar validerade proxyservrar från 1proxy API
2. **Lagra** — Proxies sparas i samma `proxy_registry` tabell som `source = 'oneproxy'`
3. **Filtrera** — Filtrera efter protokoll, land, kvalitetspoäng
4. **Rotera** — Välj den bästa proxyn med hjälp av kvalitets-, slumpmässiga eller sekventiella strategier
5. **Automatisk nedbrytning** — Misslyckade proxyservrar får sitt kvalitetsresultat reducerat; under tröskelvärdet → markerat inaktivt

### Synkroniserar proxyer

**Via instrumentpanelen:**

1. Gå till** Inställningar → 1proxy** flik
2. Klick** "Synkronisera nu"**
3. Visa statistik: totala proxyservrar, aktivt antal, genomsnittlig kvalitet, uppdelning per land

**Via API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtrera proxyer

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

### Proxykvalitetsresultat

Varje 1proxy-proxy kommer med metadata:

| Fält            | Beskrivning                              |
| --------------- | ---------------------------------------- |
| `qualityScore`  | 0-100 betyg från 1 proxy-validering      |
| `latencyMs`     | Uppmätt nätverkslatens                   |
| `anonymity`     | `transparent`, `anonymous` eller `elite` |
| `googleAccess`  | Om proxyn kan komma åt Google tjänster   |
| `countryCode`   | Två bokstäver ISO landskod               |
| `lastValidated` | Tidsstämpel för senaste validering       |

Kvalitetspoäng justeras dynamiskt:

- **Misslyckade förfrågningar** minska poängen med 10 poäng
- **Poängen sjunker till ≤ 10** → proxy är märkt med `inactive`
- Inaktiva fullmakter exkluderas från rotation

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

### Strömbrytare

1proxy sync har en inbyggd strömbrytare:

- Efter** 5 synkroniseringsfel i följd** , blockeras ytterligare synkroniseringsförsök
- Återställ med: `resetOneproxyCircuitBreaker()` eller starta om servern
- Synkroniseringsstatus är tillgänglig på `GET /api/settings/oneproxy?action=status`

### Rensa 1proxy proxyer

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-detektion och smygande

OmniRoute dirigerar inte bara trafik genom en proxy — det får trafiken att se legitim ut:

### TLS Fingeravtryckspoofing

Använder `wreq-js` för att generera webbläsarliknande TLS -fingeravtryck och kringgår botdetekteringssystem som flaggar TLS -handskakningar som inte är webbläsare.

### CLI Fingeravtrycksmatchning

De**CLI Fingerprint Toggle** (`Settings → Security`) ordnar om HTTP rubriker och JSON -kroppsfält för att matcha den exakta signaturen för infödda CLI binärer (Claude -kod, Codex, etc.). Det här fungerar** ovanpå** proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Du får båda**IP maskering** och** begära äkthet** samtidigt.

### Proxy IP bevarande

Färgkodade märken i instrumentpanelen visar vilken proxynivå som är aktiv:

| Emblem | Nivå        | Menande                                          |
| ------ | ----------- | ------------------------------------------------ |
| 🟢     | Global      | All trafik går via denna proxy                   |
| 🟡     | Leverantör  | Endast denna leverantörs trafik är proxy         |
| 🔵     | Förbindelse | Denna specifika key/account använder denna proxy |

Märket visar också den lösta proxy IP för verifiering.

---

## Uppströms proxylägen

För leverantörer som använder CLIProxyAPI -mönstret stöder OmniRoute tre uppströms proxylägen:

| Läge          | Beskrivning                                             |
| ------------- | ------------------------------------------------------- |
| `native`      | OmniRoute hanterar proxy routing direkt (standard)      |
| `cliproxyapi` | Delegerar till en extern CLIProxyAPI instans            |
| `fallback`    | Försöker native först, faller tillbaka till CLIProxyAPI |

Konfigurera per leverantör:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Instrumentbräda UI

### Inställningar → Proxy Tab

- **Global proxy** konfiguration (ställ in en gång för all trafik)
- **Per leverantör proxy** åsidosätter
- **Per-anslutning proxy** uppdrag
- **Anslutningstest** genom konfigurerad proxy
- **Färgkodade märken** visar aktiv proxynivå

### Inställningar → 1proxy Tab

- **Synkronisera nu** knappen för att hämta gratis proxyservrar
- **Statistikkort** : Totalt, Aktivt, Genomsnittlig kvalitet, Senaste synkronisering
- **Filter** : Protokoll, Landskod, Min kvalitet
- **Fullmaktsbord** med värd, protokoll, land, kvalitetspoäng, latens, anonymitet, Google -åtkomst
- **Synkroniseringsstatus** panel med success/failure -spårning och antal fel i följd
- **Rensa alla** för att ta bort alla 1proxy-poster

---

## API referens

### Proxyinställningar API

| Metod    | Slutpunkt                                      | Beskrivning                       |
| -------- | ---------------------------------------------- | --------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Få fullständig proxykonfiguration |
| `GET`    | `/api/settings/proxy?level=global`             | Få global proxy                   |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Skaffa leverantörsproxy           |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Lös effektiv proxy                |
| `PUT`    | `/api/settings/proxy`                          | Uppdatera proxykonfiguration      |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Ta bort proxy på nivå             |

### Proxy Registry API

| Metod    | Slutpunkt                                         | Beskrivning              |
| -------- | ------------------------------------------------- | ------------------------ |
| `GET`    | `/api/v1/management/proxies`                      | Lista alla proxyservrar  |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Få proxy via ID          |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Få fullmaktsuppdrag      |
| `POST`   | `/api/v1/management/proxies`                      | Skapa proxy              |
| `PATCH`  | `/api/v1/management/proxies`                      | Uppdatera proxy          |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Ta bort proxy            |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Tvinga bort radering     |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Masstilldelning          |
| `GET`    | `/api/v1/management/proxies/assignments`          | Lista uppdrag            |
| `GET`    | `/api/v1/management/proxies/health`               | Hälsostatistik för proxy |

### Tunnlar API

För att exponera din OmniRoute instans för det offentliga internet (Cloudflare/ngrok/Tailscale) istället för att dirigera utgående via en proxy, se [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunneln REST API lever under `/api/tunnels/{cloudflared,ngrok,tailscale}/*` och är ortogonal mot den utgående proxykedjan som dokumenterats ovan.

### 1 proxy API

| Metod    | Slutpunkt                              | Beskrivning                     |
| -------- | -------------------------------------- | ------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Lista 1 proxyproxyer            |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Få statistik + sync status      |
| `GET`    | `/api/settings/oneproxy?action=status` | Få endast synkroniseringsstatus |
| `POST`   | `/api/settings/oneproxy`               | Utlösa synkronisering           |
| `POST`   | `/api/settings/oneproxy/rotate`        | Rotera till nästa proxy         |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Ta bort en                      |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Rensa alla                      |

### Upstream Proxy API

| Metod    | Slutpunkt                         | Beskrivning                          |
| -------- | --------------------------------- | ------------------------------------ |
| `GET`    | `/api/upstream-proxy/:providerId` | Hämta uppströms proxykonfiguration   |
| `PUT`    | `/api/upstream-proxy/:providerId` | Ställ in uppströms proxyläge         |
| `DELETE` | `/api/upstream-proxy/:providerId` | Ta bort uppströms proxykonfiguration |

---

## Miljövariabler

| Variabel              | Standard | Beskrivning                                                   |
| --------------------- | -------- | ------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`   | Aktivera SOCKS5 proxy-stöd (standard `true` i `.env.example`) |

---

## Felsökning

### "SOCKS5 proxy är inaktiverad"

Ställ in `ENABLE_SOCKS5_PROXY=true` i din `.env` fil och starta om.

### "socket häng upp"-fel via proxy

Detta är normalt med billiga proxyservrar som släpper inaktiva anslutningar. OmniRoute hanterar redan detta genom:

- Inaktivera Keep-alive på proxyanslutningar (`keepAliveTimeout: 1`)
- Inaktivera pipelining (`pipelining: 0`)
- Cacha avsändare för att undvika upprepade handskakningar

Om det kvarstår, prova en annan proxy eller använd funktionen 1proxy-rotation.

### "unsupported_country_region_territory" under OAuth

Se till att proxyn är konfigurerad** före** starta OAuth flödet. OmniRoute dirigerar OAuth -tokenutbyte genom den konfigurerade proxyn. Ställ in en global proxy eller proxy på leverantörsnivå först och anslut sedan.

### Proxy används inte

Kontrollera upplösningsordningen:

1. Verifiera med `GET /api/settings/proxy?resolve=your-connection-id`
2. Kontrollera om proxyn `status` är `active` (inte `inactive`)
3. Se till att proxytilldelningens omfattning matchar din anslutning

### 1 proxy-synkronisering misslyckas

Kontrollera synkroniseringsstatus:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Om `consecutiveFailures >= 5` har strömbrytaren löst ut. Starta om servern för att återställa, eller vänta på manuell återställning.

---

## Databasschema

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

OmniRoute s** proxy snabbt-misslyckas** mekanism (`src/lib/proxyHealth.ts`) upptäcker döda proxyservrar i < 2s via en snabb TCP -anslutningskontroll, sedan** cachar resultatet** för att undvika omkostnader per begäran.

### Hur det fungerar

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

Utan detta skulle en död proxy blockera varje begäran om hela `PROXY_TIMEOUT_MS` (standard 30s) innan den misslyckades.

### Avstämbara miljövariabler

| Variabel                     | Standard | Ändamål                                  |
| ---------------------------- | -------- | ---------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`   | TCP anslutningstimeout per hälsokontroll |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`  | Hur länge ett hälsoresultat cachelagras  |

**Rekommenderade värden:**

| Scenario                            | Snabb-fail timeout | Cache TTL | Resonemang                                                            |
| ----------------------------------- | ------------------ | --------- | --------------------------------------------------------------------- |
| API -gateway med hög genomströmning | 1500 ms            | 60 000 ms | Aggressiv felsnabb, längre cache för att minska kontrollerna          |
| Geofördelade noder                  | 3000 ms            | 15 000 ms | Långsammare nätverk behöver mer tid; kortare cache för snabb failover |
| Dev / testning                      | 1000 ms            | 10 000 ms | Snabb iteration på lokala proxyservrar                                |
| Stealth / antidetektering           | 2500ms             | 45 000 ms | Undvik snabb sondering som kan utlösa hastighetsgränser               |

### Inspektera proxy hälsa

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

`stale` flaggan är `true` när cache-posten har överskridit `HEALTH_CACHE_TTL_MS` och nästa begäran kommer att utlösa en ny kontroll.

### Standardinställningar för Per-proxytyp

Hälsokontrollen använder förnuftiga standardinställningar baserat på URL schemat:

| Schema                     | Standardport |
| -------------------------- | ------------ |
| `http://`                  | 8080         |
| `https://`                 | 443          |
| `socks5://` / `socks5h://` | 1080         |

Anpassade portar i URL (`http://host:9999`) har alltid företräde framför standardinställningen.

---

## Proxyanalys och observerbarhet

OmniRoute spårar användning per proxy för att hjälpa operatörer att diagnostisera routingmönster, latensspikar och återkommande fel.

### Vad spåras

För varje begäran via en konfigurerad proxy, registrerar OmniRoute :

| Metrisk      | Beskrivning                                              |
| ------------ | -------------------------------------------------------- |
| `proxy_url`  | Full proxy URL (med autentiseringsuppgifter maskerade)   |
| `provider`   | Uppströmsleverantör ID (openai, antropisk, etc.)         |
| `latency_ms` | Total tid för tur och retur inklusive proxy-handskakning |
| `connect_ms` | TCP endast anslutningstid                                |
| `status`     | HTTP -statuskod från uppströms                           |
| `error`      | Felklass om begäran misslyckades                         |
| `timestamp`  | ISO 8601 UTC                                             |

### Åtkomst till data

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Den verkliga slutpunkten är `/api/usage/proxy-logs` (se `src/app/api/usage/proxy-logs/route.ts`). Denna slutpunkt stöder:

- `GET /api/usage/proxy-logs` — hämta proxyloggar
- `DELETE /api/usage/proxy-logs` — rensa alla proxyloggar

Aggregerad statistik kan frågas direkt från `proxy_logs` tabellen via SQL om det behövs. Instrumentpanelen UI kan erbjuda aggregerade vyer.

### Vanliga mönster

**Upptäck en flaxande proxy** (växlar mellan success/failure):

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

**Hitta långsamma proxyservrar** (p95 latens > 2s):

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

## Beslutsträd för rotationsstrategi

När flera proxyservrar tilldelas ett scope, använder OmniRoute en** rotationsstrategi** för att välja vilken som ska användas för varje begäran. Strategin konfigureras på omfattningsnivå (global, per leverantör, per konto, per kombination).

### Tillgängliga strategier

| Strategi             | När ska användas                              | Avvägning                                                    |
| -------------------- | --------------------------------------------- | ------------------------------------------------------------ |
| `quality` (standard) | Produktion med fullmakter av blandad kvalitet | Föredrar högt rankade proxyservrar; kan svälta lågt rankade  |
| `random`             | Lastfördelning, integritet                    | Jämn fördelning; ignorerar kvalitetssignaler                 |
| `sequential`         | Felsökning, deterministisk testning           | Cyklar genom proxyservrar i ordning; lätt att resonera kring |

### Beslutsträd

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

## Automatisk uteslutning av fel för dina egna proxyservrar

1proxy-marknadsplatspoolen degraderar redan automatiskt misslyckade proxyservrar på egen hand (se [Proxykvalitetsresultat](#proxy-quality-scores) ). För fullmakt** du** läggs till i registret, ger bakgrundshälsoschemaläggaren (`src/lib/proxyHealth/scheduler.ts`) samma beteende "uteslut en död medlem från kedjan automatiskt", utan att ta bort någonting:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Hur det passar in i en multi-proxykedja:

1. Schemaläggaren sonderar varje registrerad proxy varje `PROXY_HEALTH_INTERVAL_MS` (standard 10 min; minst 1 min).
2. Efter `PROXY_AUTO_REMOVE_AFTER` i rad** avgörande** misslyckanden (ett verkligt anslutningsfel — en timeout eller sondmålets egen 5xx räknas aldrig, se [Proxy Health Checking](#proxy-health-checking-v3816) ), proxyns `status` är satt till `dead`.
3. `dead` är en av de statusar som filtret för levande status som används av pool/rotation upplösning utesluter, så en scopes rotation (round-robin / random / sticky / latency — se [Rotation Strategy Decision Tree](#rotation-strategy-decision-tree) ) slutar omedelbart att lämna ut den proxyn till nya förfrågningar. Inga andra proxyservrar i poolen påverkas, och hela poolen faller aldrig tyst tillbaka till en [direkt](#4-level-proxy-system) anslutning —
4. Schemaläggaren fortsätter att sondera `dead` proxyer på samma intervall. Nästa framgångsrika sond vänder `status` tillbaka till `active` och den återgår till rotation — ingen manuell återtillägg krävs.

Detta är medvetet** opt-in och oförstörande** : som standard räknar och loggar schemaläggaren bara fel (se policy C i `decision.ts`), och `PROXY_AUTO_DISABLE` tar aldrig bort en rad — som är vad den separata, mer aggressiva `PROXY_AUTO_REMOVE` flaggan är till för. Om båda är inställda på `true` vinner `PROXY_AUTO_REMOVE` (en proxy som ska raderas har ingen användning för en mjuk inaktivering däremellan). Se referensen [Environment Config](../reference/ENVIRONMENT.md) för hela variabellistan.

---

> 📖** Relaterad dokumentation:**
>
> - [Användarhandbok](../guides/USER_GUIDE.md) — Allmän inställning och konfiguration - [API Referens](../reference/API_REFERENCE.md) — Fullständig API -dokumentation - [Environment Config](../reference/ENVIRONMENT.md) — Alla miljövariabler
