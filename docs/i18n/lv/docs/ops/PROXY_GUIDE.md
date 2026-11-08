# 🌐 OmniRoute Proxy Guide (Latviešu)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Apejiet ģeogrāfiskos blokus, aizsargājiet savu identitāti un maršrutējiet AI trafiku caur jebkuru starpniekserveri — bez konfigurācijas sarežģītības.**

OmniRoute ietver pilnvērtīgu starpniekservera pārvaldības sistēmu, kas ļauj maršrutēt augšupējo AI nodrošinātāja trafiku caur HTTP, HTTPS vai SOCKS5 starpniekserveriem. Neatkarīgi no tā, vai atrodaties bloķētā reģionā, nepieciešama IP rotācija vai vēlaties slepeni noņemt pirkstu nospiedumus — šajā rokasgrāmatā ir aprakstīts viss.

---

## Satura rādītājs

- [Kāpēc izmantot starpniekserveri?](#why-use-proxies)
- [Arhitektūras pārskats](#architecture-overview)
- [4 līmeņu starpniekservera sistēma](#4-level-proxy-system)
- [Starpniekservera reģistrs (CRUD)](#proxy-registry-crud)
- [1 starpniekserveris bezmaksas tirgus](#1proxy-free-proxy-marketplace)
- [Starpniekservera rotācija](#proxy-rotation)
- [Pretnoteikšana un slepenība](#anti-detection--stealth)
- [Augšupējie starpniekservera režīmi](#upstream-proxy-modes)
- [Informācijas panelis UI](#dashboard-ui)
- [API atsauce](#api-reference)
- [Vides mainīgie](#environment-variables)
- [Problēmu novēršana](#troubleshooting)

---

## Kāpēc izmantot starpniekserveri?

Daudzi AI pakalpojumu sniedzēji ierobežo piekļuvi pēc ģeogrāfiskā reģiona. Izstrādātāji iekšā** Krievija, Ķīna, Irāna, Kuba, Turcija** , un citās valstīs rodas šādas kļūdas:

```
unsupported_country_region_territory
```

Pat ārpus bloķētajiem reģioniem starpniekserveri ir noderīgi:

| Lietošanas gadījums         | Apraksts                                                                     |
| --------------------------- | ---------------------------------------------------------------------------- |
| **Ģeogrāfiskais apvedceļš** | Piekļūstiet OpenAI, Anthropic, Codex, Copilot no bloķētām valstīm            |
| **IP rotācija**             | Izplatiet pieprasījumus vairākos IPs, lai izvairītos no ātruma ierobežošanas |
| **Privātums**               | Paslēpiet savu īsto IP no iepriekšējiem pakalpojumu sniedzējiem              |
| **Atbilstība**              | Maršrutējiet satiksmi caur noteiktām jurisdikcijām                           |
| **Testēšana**               | Simulēt pieprasījumus no dažādiem reģioniem                                  |

---

## Arhitektūras pārskats

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

### Galvenās sastāvdaļas

| Komponents                     | Fails                                        | Loma                                                        |
| ------------------------------ | -------------------------------------------- | ----------------------------------------------------------- |
| **Starpniekservera reģistrs**  | `src/lib/db/proxies.ts`                      | CRUD starpniekservera ierakstiem + tvēruma piešķiršanai     |
| **Starpniekservera dispečers** | `open-sse/utils/proxyDispatcher.ts`          | Izveido `undici` ProxyAgent/SOCKS dispečerus ar kešatmiņu   |
| **Starpniekservera ielāde**    | `open-sse/utils/proxyFetch.ts`               | Aptin `fetch()` ar starpniekservera dispečera injekciju     |
| **Iestatījumi Maršruts**       | `src/app/api/settings/proxy/route.ts`        | Mantotā starpniekservera konfigurācija API (GET/PUT/DELETE) |
| **Pārvaldības maršruts**       | `src/app/api/v1/management/proxies/route.ts` | Reģistrs CRUD API (GET/POST/PATCH/DELETE)                   |
| **1 starpniekserveris DB**     | `src/lib/db/oneproxy.ts`                     | Bezmaksas starpniekservera tirgus noturība                  |

---

## Noklusējuma starpniekservera stāvoklis jauniem kontiem

In** Iestatījumi → Proxy → Globālā konfigurācija** , izmantojiet** Jauniem savienojumiem pēc noklusējuma iespējot starpniekserveri** lai izvēlētos tikko pievienoto pakalpojumu sniedzēja kontu sākotnējo starpniekservera stāvokli.

Jaunais iestatījums kontrolē tikko pievienoto pakalpojumu sniedzēja kontu sākotnējo starpniekservera stāvokli. Tas nemaina esošos kontus un neaizstāj globālo starpniekservera slēdzi. Tās sākotnējā vērtība saglabā iepriekšējo uzvedību. Vienreiz izslēdziet to, lai turpmāk izveidotu kontus ar atspējotu starpniekserveri pēc noklusējuma.

Preference tiek saglabāta kā `defaultNewConnectionProxyEnabled`, izmantojot esošos iestatījumus API. Pēc noklusējuma tas ir `true`, kad tas nekad nav saglabāts. `false` saglabāšana stājas spēkā nākamajiem jauniem kontiem bez restartēšanas. `POST /api/providers` pieņem neobligātu stingru Būla `proxyEnabled`; precīzs `true` vai `false` ir prioritārs pār izveides noklusējuma iestatījumu. Dublēta konta izlaišana vai OAuth reconnect saglabā šī konta saglabāto stāvokli. Atsevišķus kontus joprojām var iespējot vai atspējot pēc tam.

Selektīvajiem pakalpojumu sniedzēju pārsūtījumiem tiek izmantota mērķa instalācijas noklusējuma vērtība jauniem kontiem un tiek saglabāta mērķa politika, aizstājot esošos kontus. Starpniekservera slēdži nav pārnēsājami pārsūtīšanas lauki. Pilna dublējuma atjaunošana un vēsturiskā JSON/SQL migrācija saglabā esošo atjaunošanas semantiku, tostarp saglabātās konta vērtības un mantotās shēmas noklusējuma vērtības; pilna iestatījumu atjaunošana var arī atjaunot šo preferenci.

Šī preference nepiešķir starpniekserveri un nenosaka, ka tas ir vesels vai tiek lietots. Faktiskais maršrutēšana joprojām ir atkarīga no globālā starpniekservera slēdža un piemērojamās starpniekservera konfigurācijas. Sintētiskie pakalpojumu sniedzēji bez pastāvīga konta, OAuth trafika pirms konta izveides, environment/system starpniekserveri un ārējo aizmugursistēmu tīkli neietilpst tā darbības jomā.

## 4 līmeņu starpniekservera sistēma

OmniRoute atbalsta starpniekservera konfigurāciju vietnē** četri neatkarīgi tvērumi** , atrisināts prioritārā secībā:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Kā darbojas izšķirtspēja

Kad OmniRoute nosūta pieprasījumu augšupējam pakalpojumu sniedzējam, tas izsauc `resolveProxyForConnectionFromRegistry()`, kas pārbauda katru līmeni secībā:

1. **Konta līmenī** — Vai šim konkrētajam savienojumam ID ir piešķirts starpniekserveris?
2. **Pakalpojumu sniedzēja līmenis** — Vai šim pakalpojumu sniedzējam ir piešķirts starpniekserveris (piemēram, `openai`)?
3. **Globālais līmenis** — Vai ir konfigurēts globālais starpniekserveris?
4. **Nav starpniekservera** — Tiešs savienojums ar pakalpojumu sniedzēju.

Pirmajā mačā uzvara. Tas nozīmē, ka varat iestatīt globālo starpniekserveri kā atkāpšanos, bet ignorēt to konkrētiem pakalpojumu sniedzējiem vai savienojumiem.

### Kas tiek nosūtīts starpniekserveri

| Satiksmes veids        | Starpniekserveris? | Piezīmes                                              |
| ---------------------- | ------------------ | ----------------------------------------------------- |
| Tērzēšanas pabeigšana  | ✅                 | Visi `/v1/chat/completions` pieprasījumi              |
| Iegulumi               | ✅                 | `/v1/embeddings`                                      |
| Attēlu ģenerēšana      | ✅                 | `/v1/images/generations`                              |
| Audio (TTS/STT)        | ✅                 | `/v1/audio/*`                                         |
| OAuth žetonu apmaiņa   | ✅                 | Atrisina `unsupported_country_region_territory`       |
| Savienojuma testi      | ✅                 | Poga "Pārbaudīt savienojumu" izmanto starpniekserveri |
| Žetona atsvaidzināšana | ✅                 | Fona OAuth atjaunošana                                |
| Modeļa sinhronizācija  | ✅                 | Modeļu uzskaitījums un atklāšana                      |

---

## Starpniekservera reģistrs (CRUD)

Starpniekservera reģistrs ir SQLite tabula (`proxy_registry`), kurā tiek glabāti visi jūsu starpniekserveri. Katram starpniekserveram ir:

| Lauks      | Tips            | Apraksts                                         |
| ---------- | --------------- | ------------------------------------------------ |
| `id`       | UUID            | Unikāls identifikators                           |
| `name`     | Stīga           | Cilvēkam salasāma etiķete                        |
| `type`     | Stīga           | Protokols: `http`, `https`, `socks5`             |
| `host`     | Stīga           | Starpniekservera saimniekdatora nosaukums vai IP |
| `port`     | Vesels skaitlis | Porta numurs                                     |
| `username` | Stīga           | Auth lietotājvārdu (šifrēts miera stāvoklī)      |
| `password` | Stīga           | Auth parole (šifrēta miera stāvoklī)             |
| `region`   | Stīga           | Ģeogrāfiskā reģiona etiķete                      |
| `notes`    | Stīga           | Brīvā teksta piezīmes                            |
| `status`   | Stīga           | `active` vai `inactive`                          |
| `source`   | Stīga           | `manual` vai `oneproxy`                          |

### Starpniekservera izveide

**Izmantojot informācijas paneli:**

1. Dodieties uz** Iestatījumi → starpniekserveris**
2. Noklikšķiniet** Pievienojiet starpniekserveri**
3. Ievadiet veidu, resursdatoru, portu un neobligātos autentifikācijas akreditācijas datus
4. Saglabāt

**Pa API:**

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

### Starpniekservera atjaunināšana

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Piezīme:** Akreditācijas dati tiek saglabāti, ja vien jūs nepārprotami nenosūtāt aizvietotājus, kas nav tukši. Nosūtot tukšas virknes `username`/`password`, saglabātās vērtības tiks saglabātas.

### Starpniekservera dzēšana

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Sarakstu starpniekserveri

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Starpniekserveru piešķiršana tvērumam

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

### Efektīva starpniekservera atrisināšana

Pārbaudiet, kurš starpniekserveris tiks izmantots konkrētajam savienojumam:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Atgriež atrisināto starpniekserveri ar tā līmeni (`account`, `provider` vai `global`) un avotu.

### Lielapjoma uzdevums

Piešķiriet vienu starpniekserveri vairākiem pakalpojumu sniedzējiem vai savienojumiem vienlaikus:

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

Starpniekserveri ir iekļauti**Backup/Restore** sistēma. Kad eksportējat savu OmniRoute konfigurāciju:

1. Dodieties uz** Informācijas panelis → Iestatījumi → Dublēšana**
2. Noklikšķiniet** Eksportēt** — starpniekservera reģistrs un uzdevumi ir iekļauti
3. Lai atjaunotu, noklikšķiniet uz** Importēt** un augšupielādējiet dublējuma failu

Atbalsta arī starpniekservera reģistrs** upsert by uzņēmēja + ports** — ja importējat jau esošu starpniekserveri (tas pats resursdators un ports), tas tiek atjaunināts, nevis izveidots dublikāts.

### Mantotā migrācija

Ja starpniekserverus konfigurējāt vecākā versijā (iepriekšreģistrā), OmniRoute tos automātiski migrē:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Tas notiek vienu reizi, pirmo reizi startējot pēc jaunināšanas. Izmantojiet `migrateLegacyProxyConfigToRegistry({ force: true })`, lai atkārtoti palaistu.

---

## 1proxy Bezmaksas starpniekservera tirgus

> 🆕** Ieguldīja [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (izdevums [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integrējas ar** [1 starpniekserveris](https://1proxy-api.aitradepulse.com)** kopienas platforma, kurai nodrošināt piekļuvi** simtiem bezmaksas, apstiprinātu starpniekserveru** no visas pasaules. Tas ir lieliski piemērots lietotājiem, kuriem nav savas starpniekservera infrastruktūras.

### Kā tas darbojas

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sinhronizēt** — OmniRoute ienes apstiprinātos starpniekserverus no 1proxy API
2. **Veikals** — Starpniekserveri tiek saglabāti tajā pašā `proxy_registry` tabulā ar `source = 'oneproxy'`
3. **Filtrs** — Filtrēt pēc protokola, valsts, kvalitātes rādītāja
4. **Pagriezt** — Izvēlieties labāko starpniekserveri, izmantojot kvalitātes, nejaušas vai secīgas stratēģijas
5. **Automātiska degradācija** — Neveiksmīgiem starpniekserveriem tiek samazināts kvalitātes rādītājs; zem sliekšņa → atzīmēts kā neaktīvs

### Starpniekserveru sinhronizēšana

**Izmantojot informācijas paneli:**

1. Dodieties uz** Iestatījumi → 1proxy** cilne
2. Noklikšķiniet** "Sinhronizēt tūlīt"**
3. Skatīt statistiku: kopējais starpniekserveru skaits, aktīvo skaits, vidējā kvalitāte, sadalījums pa valstīm

**Pa API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Starpniekserveru filtrēšana

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

### Starpniekservera kvalitātes rādītāji

Katram 1 starpniekserveram ir metadati:

| Lauks           | Apraksts                                               |
| --------------- | ------------------------------------------------------ |
| `qualityScore`  | Vērtējums 0–100 no 1 starpniekservera validācijas      |
| `latencyMs`     | Izmērītais tīkla latentums                             |
| `anonymity`     | `transparent`, `anonymous` vai `elite`                 |
| `googleAccess`  | Vai starpniekserveris var piekļūt Google pakalpojumiem |
| `countryCode`   | Divu burtu ISO valsts kods                             |
| `lastValidated` | Pēdējās validācijas laikspiedols                       |

Kvalitātes rādītāji tiek dinamiski pielāgoti:

- **Neizdevušies pieprasījumi** samazināt rezultātu par 10 punktiem
- **Rezultāts samazinās līdz ≤ 10** → starpniekserveris ir atzīmēts `inactive`
- Neaktīvie starpniekserveri tiek izslēgti no rotācijas

### Rotācijas stratēģijas

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

### Strāvas slēdzis

1 starpniekservera sinhronizācijai ir iebūvēts ķēdes pārtraucējs:

- Pēc** 5 secīgas sinhronizācijas kļūmes** , turpmākie sinhronizācijas mēģinājumi ir bloķēti
- Atiestatiet ar: `resetOneproxyCircuitBreaker()` vai restartējiet serveri
- Sinhronizācijas statuss ir pieejams vietnē `GET /api/settings/oneproxy?action=status`

### 1 starpniekservera starpniekserveru notīrīšana

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Pretnoteikšana un slepenība

OmniRoute ne tikai maršrutē satiksmi caur starpniekserveri — bet arī liek satiksmei izskatīties likumīgai:

### TLS Pirkstu nospiedumu viltošana

Izmanto `wreq-js`, lai ģenerētu pārlūkprogrammai līdzīgus TLS pirkstu nospiedumus, apejot robotu noteikšanas sistēmas, kas atzīmē TLS rokasspiedienus, kas nav pārlūkprogrammas.

### CLI pirkstu nospiedumu saskaņošana

The**CLI pirkstu nospiedumu pārslēgšana** (`Settings → Security`) pārkārto HTTP galvenes un JSON pamatteksta laukus, lai tie precīzi atbilstu vietējo CLI bināro failu parakstam (Claude kods, Codex utt.). Tas darbojas** virsū** starpniekserveris:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Jūs saņemat abus**IP maskēšana** un** pieprasīt autentiskumu** vienlaikus.

### Proxy IP saglabāšana

Informācijas paneļa krāsu kodētas emblēmas parāda, kurš starpniekservera līmenis ir aktīvs:

| Žetons | Līmenis               | Nozīme                                                  |
| ------ | --------------------- | ------------------------------------------------------- |
| 🟢     | Globāli               | Visa satiksme notiek caur šo starpniekserveri           |
| 🟡     | Pakalpojumu sniedzējs | Tiek nodrošināta tikai šī pakalpojumu sniedzēja trafika |
| 🔵     | Savienojums           | Šis konkrētais key/account izmanto šo starpniekserveri  |

Emblēma parāda arī pārbaudīto starpniekserveri IP verifikācijai.

---

## Augšupējie starpniekservera režīmi

Pakalpojumu sniedzējiem, kuri izmanto CLIProxyAPI modeli, OmniRoute atbalsta trīs augšpuses starpniekservera režīmus.

| Režīms        | Apraksts                                                             |
| ------------- | -------------------------------------------------------------------- |
| `native`      | OmniRoute tieši apstrādā starpniekservera maršrutēšanu (noklusējums) |
| `cliproxyapi` | Delegāti ārējai CLIProxyAPI instancei                                |
| `fallback`    | Vispirms izmēģina vietējo, atgriežas pie CLIProxyAPI                 |

Konfigurēt katram pakalpojumu sniedzējam:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Informācijas panelis UI

### Iestatījumi → starpniekservera cilne

- **Globālais starpniekserveris** konfigurācija (iestatīt vienreiz visai satiksmei)
- **Katra nodrošinātāja starpniekserveris** ignorē
- **Savienojuma starpniekserveris** uzdevumiem
- **Savienojuma pārbaude** izmantojot konfigurētu starpniekserveri
- **Krāsu kodētas nozīmītes** rāda aktīvo starpniekservera līmeni

### Iestatījumi → 1proxy Tab

- **Sinhronizēt tūlīt** pogu, lai ielādētu bezmaksas starpniekserverus
- **Statistikas kartes** : Kopā, Aktīvs, Vidējā kvalitāte, Pēdējā sinhronizācija
- **Filtri** : protokols, valsts kods, minimālā kvalitāte
- **Starpniekserveru tabula** ar resursdatoru, protokolu, valsti, kvalitātes rādītāju, latentumu, anonimitāti, Google piekļuvi
- **Sinhronizācijas statuss** panelis ar success/failure izsekošanu un secīgu kļūdu skaitu
- **Notīrīt visu** lai noņemtu visus 1 starpniekservera ierakstus

---

## API atsauce

### Starpniekservera iestatījumi API

| Metode   | Galapunkts                                     | Apraksts                                         |
| -------- | ---------------------------------------------- | ------------------------------------------------ |
| `GET`    | `/api/settings/proxy`                          | Iegūstiet pilnu starpniekservera konfigurāciju   |
| `GET`    | `/api/settings/proxy?level=global`             | Iegūstiet globālo starpniekserveri               |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Iegūstiet pakalpojumu sniedzēja starpniekserveri |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Atrisiniet efektīvu starpniekserveri             |
| `PUT`    | `/api/settings/proxy`                          | Atjaunināt starpniekservera konfigurāciju        |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Noņemiet starpniekserveri līmenī                 |

### Starpniekservera reģistrs API

| Metode   | Galapunkts                                        | Apraksts                                  |
| -------- | ------------------------------------------------- | ----------------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Uzskaitiet visus starpniekserverus        |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Iegūstiet starpniekserveri, izmantojot ID |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Iegūstiet starpniekservera uzdevumus      |
| `POST`   | `/api/v1/management/proxies`                      | Izveidojiet starpniekserveri              |
| `PATCH`  | `/api/v1/management/proxies`                      | Atjaunināt starpniekserveri               |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Dzēst starpniekserveri                    |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Piespiedu dzēšana                         |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Lielapjoma piešķiršana                    |
| `GET`    | `/api/v1/management/proxies/assignments`          | Uzskaitiet uzdevumus                      |
| `GET`    | `/api/v1/management/proxies/health`               | Starpniekservera veselības statistika     |

### Tuneļi API

Lai atklātu savu OmniRoute gadījumu publiskajam internetam (Cloudflare/ngrok/Tailscale), nevis maršrutētu izejošos caur starpniekserveri, skatiet [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunelis REST API atrodas zem `/api/tunnels/{cloudflared,ngrok,tailscale}/*` un ir ortogonāls iepriekš dokumentētajai izejošajai starpniekservera ķēdei.

### 1 starpniekserveris API

| Metode   | Galapunkts                             | Apraksts                                        |
| -------- | -------------------------------------- | ----------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Norādiet 1 starpniekserverus                    |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Iegūstiet statistikas + sinhronizācijas statusu |
| `GET`    | `/api/settings/oneproxy?action=status` | Iegūstiet tikai sinhronizācijas statusu         |
| `POST`   | `/api/settings/oneproxy`               | Aktivizētāja sinhronizācija                     |
| `POST`   | `/api/settings/oneproxy/rotate`        | Pagriezt uz nākamo starpniekserveri             |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Dzēst vienu                                     |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Notīrīt visu                                    |

### Augšpuses starpniekserveris API

| Metode   | Galapunkts                        | Apraksts                                           |
| -------- | --------------------------------- | -------------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Iegūstiet augšpuses starpniekservera konfigurāciju |
| `PUT`    | `/api/upstream-proxy/:providerId` | Iestatiet augšpuses starpniekservera režīmu        |
| `DELETE` | `/api/upstream-proxy/:providerId` | Noņemt augšējo starpniekservera konfigurāciju      |

---

## Vides mainīgie

| Mainīgs               | Noklusējums | Apraksts                                                                      |
| --------------------- | ----------- | ----------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`      | Iespējot SOCKS5 starpniekservera atbalstu (noklusējuma `true` `.env.example`) |

---

## Problēmu novēršana

### "SOCKS5 starpniekserveris ir atspējots"

Iestatiet `ENABLE_SOCKS5_PROXY=true` savā `.env` failā un restartējiet.

### "Socket hang up" kļūdas, izmantojot starpniekserveri

Tas ir normāli, ja tiek izmantoti lēti starpniekserveri, kas pārtrauc dīkstāves savienojumus. OmniRoute to jau apstrādā:

- Uzturēšanas atspējošana starpniekservera savienojumiem (`keepAliveTimeout: 1`)
- Cauruļvadu atspējošana (`pipelining: 0`)
- Dispečeru saglabāšana kešatmiņā, lai izvairītos no atkārtotiem rokasspiedieniem

Ja tā joprojām pastāv, izmēģiniet citu starpniekserveri vai izmantojiet 1 starpniekservera rotācijas funkciju.

### "unsupported_country_region_territory" OAuth laikā

Pārliecinieties, vai starpniekserveris ir konfigurēts** pirms tam** uzsākot OAuth plūsmu. OmniRoute maršrutē OAuth pilnvaru apmaiņu, izmantojot konfigurēto starpniekserveri. Vispirms iestatiet globālo vai pakalpojumu sniedzēja līmeņa starpniekserveri un pēc tam izveidojiet savienojumu.

### Starpniekserveris netiek izmantots

Pārbaudiet izšķirtspējas secību:

1. Pārbaudiet ar `GET /api/settings/proxy?resolve=your-connection-id`
2. Pārbaudiet, vai starpniekserveris `status` ir `active` (nevis `inactive`)
3. Pārliecinieties, vai starpniekservera piešķiršanas tvērums atbilst jūsu savienojumam

### 1 starpniekservera sinhronizācija neizdodas

Pārbaudiet sinhronizācijas statusu:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Ja `consecutiveFailures >= 5`, ķēdes pārtraucējs ir nostrādājis. Restartējiet serveri, lai atiestatītu, vai gaidiet manuālu atiestatīšanu.

---

## Datu bāzes shēma

### `proxy_registry` tabula

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

### `proxy_assignments` tabula

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

## Starpniekservera veselības pārbaude (v3.8.16 +)

OmniRoute's** starpniekserveris ātri neveiksmīgs** mehānisms (`src/lib/proxyHealth.ts`) nosaka mirušos starpniekserverus < 2s, izmantojot ātru TCP savienojuma pārbaudi, pēc tam** kešatmiņā saglabā rezultātu** lai izvairītos no pieskaitāmām izmaksām pēc pieprasījuma.

### Kā tas darbojas

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

Bez šī starpniekserveris bloķētu katru pieprasījumu pēc pilnas `PROXY_TIMEOUT_MS` (noklusējuma 30 s) pirms neveiksmes.

### Noskaņojami vides mainīgie

| Mainīgs                      | Noklusējums | Mērķis                                                |
| ---------------------------- | ----------- | ----------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`      | TCP savienojuma noildze vienai veselības pārbaudei    |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`     | Cik ilgi veselības rezultāts tiek saglabāts kešatmiņā |

**Ieteicamās vērtības:**

| Scenārijs                        | Ātrās neveiksmes taimauts | Kešatmiņa TTL | Spriešana                                                                       |
| -------------------------------- | ------------------------- | ------------- | ------------------------------------------------------------------------------- |
| Augstas caurlaidības API vārteja | 1500 ms                   | 60 000 ms     | Agresīva atteices, garāka kešatmiņa, lai samazinātu pārbaudes                   |
| Ģeogrāfiski sadalīti mezgli      | 3000 ms                   | 15000 ms      | Lēnākiem tīkliem nepieciešams vairāk laika; īsāka kešatmiņa ātrai kļūmjpārlēcei |
| Izstrādātājs/testēšana           | 1000 ms                   | 10000 ms      | Ātra iterācija uz vietējiem starpniekserveriem                                  |
| Maskēšanās / pretatklāšana       | 2500 ms                   | 45000 ms      | Izvairieties no ātras zondēšanas, kas var izraisīt ātruma ierobežojumus         |

### Proxy veselības pārbaude

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

`stale` karodziņš ir `true`, ja kešatmiņas ieraksts ir pārsniedzis `HEALTH_CACHE_TTL_MS` un nākamais pieprasījums aktivizēs jaunu pārbaudi.

### Starpniekservera tipa noklusējuma iestatījumi

Veselības pārbaudē tiek izmantoti saprātīgi noklusējuma iestatījumi, pamatojoties uz URL shēmu:

| Shēma                      | Noklusējuma ports |
| -------------------------- | ----------------- |
| `http://`                  | 8080              |
| `https://`                 | 443               |
| `socks5://` / `socks5h://` | 1080              |

Pielāgotie porti URL (`http://host:9999`) vienmēr ir prioritāri pār shēmas noklusējuma iestatījumiem.

---

## Starpniekservera analīze un novērojamība

OmniRoute izseko starpniekservera lietojumu, lai palīdzētu operatoriem diagnosticēt maršrutēšanas modeļus, latentuma lēcienus un atkārtotas kļūmes.

### Kas ir izsekots

Katram pieprasījumam, izmantojot konfigurētu starpniekserveri, OmniRoute ieraksta:

| Metrika      | Apraksts                                                                            |
| ------------ | ----------------------------------------------------------------------------------- |
| `proxy_url`  | Pilns starpniekserveris URL (ar maskētiem autentifikācijas akreditācijas datiem)    |
| `provider`   | Augšējais pakalpojumu sniedzējs ID (openai, antropisks utt.)                        |
| `latency_ms` | Kopējais brauciena laiks turp un atpakaļ, ieskaitot starpniekservera rokasspiedienu |
| `connect_ms` | TCP tikai savienojuma laiks                                                         |
| `status`     | HTTP statusa kods no augšpuses                                                      |
| `error`      | Kļūdu klase, ja pieprasījums neizdevās                                              |
| `timestamp`  | ISO 8601 UTC                                                                        |

### Piekļuve datiem

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Patiesais beigu punkts ir `/api/usage/proxy-logs` (sk. `src/app/api/usage/proxy-logs/route.ts`). Šis galapunkts atbalsta:

- `GET /api/usage/proxy-logs` — izgūst starpniekservera žurnālus
- `DELETE /api/usage/proxy-logs` — notīrīt visus starpniekservera žurnālus

Ja nepieciešams, apkopoto statistiku var pieprasīt tieši no `proxy_logs` tabulas, izmantojot SQL. Informācijas panelis UI var piedāvāt apkopotus skatus.

### Kopējie modeļi

**Noteikt plīvojošu starpniekserveri** (mijas starp success/failure):

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

**Atrodiet lēnos starpniekserverus** (p95 latentums > 2s):

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

## Rotācijas stratēģijas lēmumu koks

Ja tvērumam ir piešķirti vairāki starpniekserveri, OmniRoute izmanto a** rotācijas stratēģija** lai izvēlētos, kuru izmantot katram pieprasījumam. Stratēģija ir konfigurēta tvēruma līmenī (globāli, katram nodrošinātājam, vienam kontam, vienam kombinētam).

### Pieejamās stratēģijas

| stratēģija              | Kad lietot                                        | Kompromiss                                                                  |
| ----------------------- | ------------------------------------------------- | --------------------------------------------------------------------------- |
| `quality` (noklusējums) | Ražošana ar jauktas kvalitātes starpniekserveriem | Dod priekšroku augsta līmeņa starpniekserveriem; var badoties maznovērtētie |
| `random`                | Slodzes sadale, privātums                         | Vienmērīga izplatīšana; ignorē kvalitātes signālus                          |
| `sequential`            | Atkļūdošana, deterministiskā pārbaude             | Pārvietojas caur starpniekserveriem secībā; viegli pamatot                  |

### Lēmumu koks

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

## Automātiska kļūmju izslēgšana jūsu starpniekserveriem

1 starpniekservera tirgus kopums jau pats automātiski degradē neizdevušos starpniekserverus (skatiet [Starpniekservera kvalitātes rādītājus](#proxy-quality-scores) ). Starpniekserveriem** tu** Pievienots reģistram, fona veselības plānotājs (`src/lib/proxyHealth/scheduler.ts`) nodrošina tādu pašu darbību "automātiski izslēgt mirušu dalībnieku no ķēdes", neko neizdzēšot:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Kā tas iekļaujas vairāku starpniekserveru ķēdē:

1. Plānotājs pārbauda katru reģistrēto starpniekserveri ik pēc `PROXY_HEALTH_INTERVAL_MS` (noklusējuma 10 min; vismaz 1 min).
2. Pēc `PROXY_AUTO_REMOVE_AFTER` pēc kārtas** pārliecinošs** kļūmes (reāla savienojuma kļūme — noildze vai paša zondes mērķa 5xx nekad netiek skaitītas, skatiet [sadaļu Starpniekservera stāvokļa pārbaude](#proxy-health-checking-v3816) ), starpniekservera `status` ir iestatīts uz `dead`.
3. `dead` ir viens no statusiem, ko izslēdz dzīvā statusa filtrs, ko izmanto pool/rotation izšķirtspēja, tāpēc tvēruma rotācija (apkārtējā diapazona / nejauša / lipīga / latentuma — skat. [Rotācijas stratēģijas lēmumu koku](#rotation-strategy-decision-tree) ) nekavējoties pārtrauc šī starpniekservera nodošanu jauniem pieprasījumiem. Netiek ietekmēti nekādi citi baseina starpniekserveri, un viss baseins nekad klusībā neatgriežas tiešā savienojumā — Skatiet [4 līmeņu starpniekservera sistēmas](#4-level-proxy-system) atteices aizvēršanas aizsargu.
4. Plānotājs turpina pārbaudīt `dead` starpniekserverus tajā pašā intervālā. Nākamā veiksmīgā zonde pārvērš `status` atpakaļ uz `active`, un tā atkārtoti ieslēdzas — rotācijā, nav nepieciešama manuāla atkārtota pievienošana.

Tas ir apzināti** izvēles un nesagraujošas** : pēc noklusējuma plānotājs tikai uzskaita un reģistrē kļūmes (skatiet politiku C `decision.ts`), un `PROXY_AUTO_DISABLE` nekad neizdzēš rindu — un tam ir paredzēts atsevišķs, agresīvāks `PROXY_AUTO_REMOVE` karodziņš. Ja abi ir iestatīti uz `true`, uzvar `PROXY_AUTO_REMOVE` (starpniekserveris, kuru drīzumā paredzēts dzēst, nav izmantojams mīkstajai atspējošanai starp tām). Pilnu mainīgo sarakstu skatiet sadaļā [Environment Config](../reference/ENVIRONMENT.md).

---

> 📖** Saistītā dokumentācija:**
>
> - [Lietotāja rokasgrāmata](../guides/USER_GUIDE.md) — Vispārīga iestatīšana un konfigurācija - [API Atsauce](../reference/API_REFERENCE.md) — Pilna API dokumentācija - [Vides konfigurācija](../reference/ENVIRONMENT.md) — Visi vides mainīgie
