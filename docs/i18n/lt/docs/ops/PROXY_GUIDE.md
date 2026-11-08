# 🌐 OmniRoute Proxy Guide (Lietuvių)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Apeikite geografinius blokus, apsaugokite savo tapatybę ir nukreipkite AI srautą per bet kurį įgaliotąjį — kurio konfigūracija nėra sudėtinga.**

OmniRoute apima visas funkcijas turinčią tarpinio serverio valdymo sistemą, leidžiančią nukreipti AI teikėjo srautą prieš srovę per HTTP, HTTPS arba SOCKS5 tarpinius serverius. Nesvarbu, ar esate užblokuotame regione, jums reikia IP pasukimo, ar norite slapto pirštų atspaudų — šiame vadove rasite viską.

---

## Turinys

- [Kodėl naudoti tarpinius serverius?](#why-use-proxies)
- [Architektūros apžvalga](#architecture-overview)
- [4 lygių tarpinio serverio sistema](#4-level-proxy-system)
- [Tarpinio serverio registras (CRUD)](#proxy-registry-crud)
- [1 tarpinio serverio nemokama prekyvietė](#1proxy-free-proxy-marketplace)
- [Tarpinio serverio rotacija](#proxy-rotation)
- [Aptikimo apsauga ir slaptumas](#anti-detection--stealth)
- [Prieš srovę tarpinio serverio režimai](#upstream-proxy-modes)
- [Prietaisų skydelis UI](#dashboard-ui)
- [API nuoroda](#api-reference)
- [Aplinkos kintamieji](#environment-variables)
- [Trikčių šalinimas](#troubleshooting)

---

## Kodėl naudoti tarpinius serverius?

Daugelis AI teikėjų riboja prieigą pagal geografinį regioną. Kūrėjai į** Rusija, Kinija, Iranas, Kuba, Turkija** , ir kitose šalyse susiduriama su tokiomis klaidomis:

```
unsupported_country_region_territory
```

Netgi už blokuotų regionų ribų tarpiniai serveriai yra naudingi:

| Naudojimo dėklas            | Aprašymas                                                              |
| --------------------------- | ---------------------------------------------------------------------- |
| **Geografinis aplinkkelis** | Pasiekite OpenAI, Anthropic, Codex, Copilot iš užblokuotų šalių        |
| **IP sukimasis**            | Paskirstykite užklausas keliose IPs, kad išvengtumėte greičio ribojimo |
| **Privatumas**              | Paslėpkite savo tikrąjį IP nuo tiekėjų                                 |
| **Atitiktis**               | Nukreipkite eismą per konkrečias jurisdikcijas                         |
| **Testavimas**              | Imituoti užklausas iš skirtingų regionų                                |

---

## Architektūros apžvalga

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

### Pagrindiniai komponentai

| Komponentas                     | Failas                                       | Vaidmuo                                                            |
| ------------------------------- | -------------------------------------------- | ------------------------------------------------------------------ |
| **Tarpinio serverio registras** | `src/lib/db/proxies.ts`                      | CRUD tarpinio serverio įrašams + apimties priskyrimams             |
| **Įgaliotasis dispečeris**      | `open-sse/utils/proxyDispatcher.ts`          | Sukuria `undici` ProxyAgent/SOCKS dispečerius su talpyklos kaupimu |
| **Tarpinio serverio gavimas**   | `open-sse/utils/proxyFetch.ts`               | Apvynioja `fetch()` su proxy dispečerine injekcija                 |
| **Nustatymai Maršrutas**        | `src/app/api/settings/proxy/route.ts`        | Sena tarpinio serverio konfigūracija API (GET/PUT/DELETE)          |
| **Valdymo maršrutas**           | `src/app/api/v1/management/proxies/route.ts` | Registras CRUD API (GET/POST/PATCH/DELETE)                         |
| **1proxy DB**                   | `src/lib/db/oneproxy.ts`                     | Nemokama tarpinio serverio rinkos atkaklumas                       |

---

## Numatytoji tarpinio serverio būsena naujoms paskyroms

Į** Nustatymai → Proxy → Visuotinė konfigūracija** , naudoti** Įgalinti tarpinį serverį pagal numatytuosius nustatymus naujiems ryšiams** norėdami pasirinkti pradinę naujai pridėtų teikėjo paskyrų tarpinio serverio būseną.

Naujasis nustatymas valdo pradinę naujai pridėtų teikėjo paskyrų tarpinio serverio būseną. Tai nekeičia esamų paskyrų ir nepakeičia visuotinio tarpinio serverio jungiklio. Jo pradinė vertė išsaugo ankstesnį elgesį. Vieną kartą išjunkite, kad ateityje sukurtumėte paskyras su pagal numatytuosius nustatymus išjungtu tarpiniu serveriu.

Nuostata išsaugoma kaip `defaultNewConnectionProxyEnabled` per esamus nustatymus API. Numatytoji reikšmė yra `true` kai niekada neišsaugota. Išsaugomas `false` galioja paskesnėms naujoms paskyroms nepaleidžiant iš naujo. `POST /api/providers` priima pasirenkamą griežtą loginį `proxyEnabled`; aiškus `true` arba `false` turi viršenybę prieš numatytąjį kūrimo nustatymą. Pasikartojančios paskyros praleidimas arba OAuth Reconnect“ išsaugo tos paskyros išsaugotą būseną. Vėliau asmenines paskyras vis tiek galima įjungti arba išjungti.

Atrankiniai teikėjo perkėlimai naudoja numatytosios paskirties vietos diegimo nustatymus naujoms paskyroms ir išsaugo paskirties politiką, kai pakeičiamos esamos paskyros. Tarpinio serverio perjungikliai nėra nešiojami perdavimo laukai. Visiškas atsarginės kopijos atkūrimas ir istorinis JSON/SQL perkėlimas išlaiko esamą atkūrimo semantiką, įskaitant išsaugotas paskyros vertes ir senos schemos numatytuosius nustatymus; visiškas nustatymų atkūrimas taip pat gali atkurti šią nuostatą.

Ši nuostata nepriskiria įgaliotojo serverio ir nenustato, kad jis yra sveikas arba naudojamas. Faktinis maršruto parinkimas vis tiek priklauso nuo visuotinio tarpinio serverio jungiklio ir taikomos tarpinio serverio konfigūracijos. Sintetiniai paslaugų teikėjai be nuolatinės paskyros, OAuth srautas prieš sukuriant paskyrą, environment/system tarpiniai serveriai ir išorinių užpakalinių sistemų tinklai nepatenka į jo taikymo sritį.

## 4 lygių tarpinio serverio sistema

OmniRoute palaiko tarpinio serverio konfigūraciją** keturios nepriklausomos taikymo srities** , išspręsta prioritetine tvarka:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Kaip veikia raiška

Kai OmniRoute siunčia užklausą tiekėjui tiekėjui, jis iškviečia `resolveProxyForConnectionFromRegistry()`, kuris patikrina kiekvieną lygį eilės tvarka:

1. **Paskyros lygiu** — Ar šiam konkrečiam ryšiui ID yra priskirtas tarpinis serveris?
2. **Teikėjo lygis** — Ar šiam teikėjui yra priskirtas tarpinis serveris (pvz., `openai`)?
3. **Pasaulinio lygio** — Ar sukonfigūruotas pasaulinis tarpinis serveris?
4. **Nėra įgaliotojo serverio** — Tiesioginis ryšys su teikėju.

Pirmosios rungtynės laimi. Tai reiškia, kad galite nustatyti visuotinį tarpinį serverį kaip atsarginį, bet nepaisyti jo konkretiems teikėjams ar ryšiams.

### Kas gauna tarpinį serverį

| Eismo tipas              | Tarpinis serveris? | Pastabos                                           |
| ------------------------ | ------------------ | -------------------------------------------------- |
| Pokalbių užbaigimai      | ✅                 | Visi `/v1/chat/completions` prašymai               |
| Įterpimai                | ✅                 | `/v1/embeddings`                                   |
| Vaizdo generavimas       | ✅                 | `/v1/images/generations`                           |
| Garsas (TTS/STT)         | ✅                 | `/v1/audio/*`                                      |
| OAuth žetonų keitimas    | ✅                 | Išsprendžia `unsupported_country_region_territory` |
| Ryšio testai             | ✅                 | Mygtukas „Išbandyti ryšį“ naudoja tarpinį serverį  |
| Žetono atnaujinimas      | ✅                 | Fono OAuth atnaujinimas                            |
| Modelio sinchronizavimas | ✅                 | Modelių sąrašas ir atradimas                       |

---

## Tarpinio serverio registras (CRUD)

Tarpinių serverių registras yra SQLite lentelė (`proxy_registry`), kurioje saugomi visi tarpiniai serveriai. Kiekvienas įgaliotasis serveris turi:

| Laukas     | Tipas              | Aprašymas                                            |
| ---------- | ------------------ | ---------------------------------------------------- |
| `id`       | UUID               | Unikalus identifikatorius                            |
| `name`     | Styga              | Žmonėms skaitoma etiketė                             |
| `type`     | Styga              | Protokolas: `http`, `https`, `socks5`                |
| `host`     | Styga              | Tarpinio serverio prieglobos pavadinimas arba IP     |
| `port`     | Sveikasis skaičius | Prievado numeris                                     |
| `username` | Styga              | Auth vartotojo vardas (užšifruotas ramybės būsenoje) |
| `password` | Styga              | Auth slaptažodis (užšifruotas ramybės būsenoje)      |
| `region`   | Styga              | Geografinio regiono etiketė                          |
| `notes`    | Styga              | Laisvo teksto pastabos                               |
| `status`   | Styga              | `active` arba `inactive`                             |
| `source`   | Styga              | `manual` arba `oneproxy`                             |

### Tarpinio serverio kūrimas

**Per prietaisų skydelį:**

1. Eiti į** Nustatymai → Proxy**
2. Spustelėkite** Pridėti tarpinį serverį**
3. Įveskite tipą, pagrindinį kompiuterį, prievadą ir pasirenkamus autentifikavimo kredencialus
4. Išsaugoti

**Per API:**

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

### Tarpinio serverio atnaujinimas

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Pastaba:** Kredencialai išsaugomi, nebent aiškiai siunčiate netuščius pakaitalus. Siunčiant tuščias `username`/`password` eilutes išsaugomos išsaugotos reikšmės.

### Tarpinio serverio ištrynimas

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Įgaliotieji serveriai sąraše

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Tarpinių serverių priskyrimas taikymo sričiai

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

### Efektyvaus tarpinio serverio sprendimas

Patikrinkite, kuris tarpinis serveris būtų naudojamas tam tikram ryšiui:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Grąžina išspręstą tarpinį serverį su jo lygiu (`account`, `provider` arba `global`) ir šaltiniu.

### Masinis priskyrimas

Priskirkite vieną tarpinį serverį keliems teikėjams ar ryšiams vienu metu:

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

Įgaliotieji serveriai yra įtraukti į**Backup/Restore** sistema. Kai eksportuojate OmniRoute konfigūraciją:

1. Eiti į** Prietaisų skydelis → Nustatymai → Atsarginė kopija**
2. Spustelėkite** Eksportuoti** — tarpinio serverio registras ir užduotys yra įtrauktos
3. Norėdami atkurti, spustelėkite** Importuoti** ir įkelkite atsarginės kopijos failą

Tarpinio serverio registras taip pat palaiko** įjungtas priimančiojo + prievado** — jei importuojate jau egzistuojantį tarpinį serverį (tas pats pagrindinis kompiuteris ir prievadas), jis atnaujinamas, o ne sukuria dublikatą.

### Palikimo migracija

Jei tarpinius serverius sukonfigūravote senesnėje versijoje (išankstiniame registre), OmniRoute automatiškai juos perkelia:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Tai nutinka vieną kartą pirmą kartą paleidžiant po atnaujinimo. Norėdami paleisti iš naujo, naudokite `migrateLegacyProxyConfigToRegistry({ force: true })`.

---

## 1proxy Nemokama tarpinio serverio prekyvietė

> 🆕** Prisidėjo [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) ( [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) problema)

OmniRoute integruojasi su** [1 tarpinis serveris](https://1proxy-api.aitradepulse.com)** bendruomenės platforma, prie kurios galima suteikti prieigą** šimtai nemokamų, patvirtintų tarpinių serverių** iš viso pasaulio. Tai puikiai tinka vartotojams, kurie neturi savo tarpinio serverio infrastruktūros.

### Kaip tai veikia

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sinchronizuoti** — OmniRoute paima patvirtintus tarpinius serverius iš 1proxy API
2. **Parduotuvė** — Tarpiniai serveriai išsaugomi toje pačioje `proxy_registry` lentelėje su `source = 'oneproxy'`
3. **Filtruoti** — Filtruoti pagal protokolą, šalį, kokybės balą
4. **Pasukti** — Pasirinkite geriausią tarpinį serverį naudodami kokybiškas, atsitiktines arba nuoseklias strategijas
5. **Automatinis pablogėjimas** — Nepavykusių tarpinių serverių kokybės balas sumažinamas; žemiau slenksčio → pažymėtas kaip neaktyvus

### Tarpinių serverių sinchronizavimas

**Per prietaisų skydelį:**

1. Eiti į** → 1proxy nustatymai** skirtuką
2. Spustelėkite** „Sinchronizuoti dabar“**
3. Žiūrėti statistiką: bendras tarpinių serverių skaičius, aktyvių skaičius, vidutinė kokybė, suskirstymas pagal šalį

**Per API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Tarpinių serverių filtravimas

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

### Tarpinio serverio kokybės balai

Kiekvienas tarpinis serveris yra su metaduomenimis:

| Laukas          | Aprašymas                                             |
| --------------- | ----------------------------------------------------- |
| `qualityScore`  | 0–100 įvertinimas iš 1 tarpinio serverio patvirtinimo |
| `latencyMs`     | Išmatuota tinklo delsa                                |
| `anonymity`     | `transparent`, `anonymous` arba `elite`               |
| `googleAccess`  | Ar tarpinis serveris gali pasiekti Google paslaugas   |
| `countryCode`   | Dviejų raidžių ISO šalies kodas                       |
| `lastValidated` | Paskutinio patvirtinimo laiko žyma                    |

Kokybės balai koreguojami dinamiškai:

- **Nepavykusios užklausos** sumažinti rezultatą 10 taškų
- **Rezultatas sumažėja iki ≤ 10** → tarpinis serveris pažymėtas `inactive`
- Neaktyvūs tarpiniai serveriai neįtraukiami į sukimąsi

### Rotacijos strategijos

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

### Grandinės pertraukiklis

1proxy sinchronizavimas turi įmontuotą grandinės pertraukiklį:

- Po to** 5 iš eilės sinchronizavimo gedimai** , tolesni sinchronizavimo bandymai blokuojami
- Iš naujo nustatykite naudodami: `resetOneproxyCircuitBreaker()` arba paleiskite serverį iš naujo
- Sinchronizavimo būsena pasiekiama adresu `GET /api/settings/oneproxy?action=status`

### 1 tarpinio serverio išvalymas

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Aptikimo apsauga ir slaptumas

OmniRoute ne tik nukreipia srautą per tarpinį serverį — bet ir leidžia eismui atrodyti teisėtai:

### TLS Pirštų atspaudų klastojimas

Naudoja `wreq-js` į naršyklę panašiems TLS pirštų atspaudams generuoti, aplenkdamas robotų aptikimo sistemas, kurios pažymi ne naršyklės TLS rankų paspaudimus.

### CLI pirštų atspaudų atitikimas

The**CLI pirštų atspaudų perjungiklis** (`Settings → Security`) pertvarko HTTP antraštes ir JSON kūno laukus, kad tiksliai atitiktų vietinių CLI dvejetainių failų parašą (Claude kodas, Codex ir kt.). Tai veikia** ant viršaus** įgaliotasis serveris:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Gauni abu**IP maskavimas** ir** prašyti autentiškumo** vienu metu.

### Proxy IP išsaugojimas

Spalvomis pažymėti ženkleliai prietaisų skydelyje rodo, kuris tarpinio serverio lygis yra aktyvus:

| Ženklas | Lygis      | Reikšmė                                              |
| ------- | ---------- | ---------------------------------------------------- |
| 🟢      | Pasaulinis | Visas srautas eina per šį tarpinį serverį            |
| 🟡      | Teikėjas   | Perduotas tik šio teikėjo srautas                    |
| 🔵      | Ryšys      | Šis konkretus key/account naudoja šį tarpinį serverį |

Ženklelyje taip pat rodomas patvirtintas tarpinis serveris IP.

---

## Prieš srovę tarpinio serverio režimai

Tiekėjams, kurie naudoja CLIProxyAPI šabloną, OmniRoute palaiko tris tarpinio serverio režimus:

| Režimas       | Aprašymas                                                            |
| ------------- | -------------------------------------------------------------------- |
| `native`      | OmniRoute tiesiogiai tvarko tarpinio serverio maršrutą (numatytasis) |
| `cliproxyapi` | Įgalioja išorinį CLIProxyAPI egzempliorių                            |
| `fallback`    | Pirmiausia bando gimtoji, grįžta į CLIProxyAPI                       |

Konfigūruoti pagal teikėją:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Prietaisų skydelis UI

### Nustatymai → Proxy Tab

- **Pasaulinis tarpinis serveris** konfigūracija (nustatyti vieną kartą visam srautui)
- **Tiekėjo įgaliotasis serveris** nepaiso
- **Tarpinis serveris vienam ryšiui** užduotys
- **Ryšio testas** per sukonfigūruotą tarpinį serverį
- **Spalvoti ženkleliai** rodomas aktyvus tarpinio serverio lygis

### Nustatymai → 1proxy Tab

- **Sinchronizuoti dabar** mygtuką, kad gautumėte nemokamus tarpinius serverius
- **Statistikos kortelės** : bendras, aktyvus, vidutinė kokybė, paskutinis sinchronizavimas
- **Filtrai** : protokolas, šalies kodas, minimali kokybė
- **Proxy lentelė** su priegloba, protokolu, šalimi, kokybės balu, delsa, anonimiškumu, Google prieiga
- **Sinchronizavimo būsena** skydelis su success/failure sekimu ir nuosekliu gedimų skaičiumi
- **Išvalyti viską** kad pašalintumėte visus 1 tarpinio serverio įrašus

---

## API nuoroda

### Tarpinio serverio nustatymai API

| Metodas  | Galutinis taškas                               | Aprašymas                                    |
| -------- | ---------------------------------------------- | -------------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Gaukite visą tarpinio serverio konfigūraciją |
| `GET`    | `/api/settings/proxy?level=global`             | Gaukite visuotinį tarpinį serverį            |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Gaukite teikėjo tarpinį serverį              |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Išspręskite veiksmingą tarpinį serverį       |
| `PUT`    | `/api/settings/proxy`                          | Atnaujinkite tarpinio serverio konfigūraciją |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Pašalinkite tarpinį serverį lygiu            |

### Tarpinio serverio registras API

| Metodas  | Galutinis taškas                                  | Aprašymas                              |
| -------- | ------------------------------------------------- | -------------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Išvardykite visus tarpinius serverius  |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Gaukite tarpinį serverį iš ID          |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Gaukite tarpinio serverio užduotis     |
| `POST`   | `/api/v1/management/proxies`                      | Sukurti tarpinį serverį                |
| `PATCH`  | `/api/v1/management/proxies`                      | Atnaujinti tarpinį serverį             |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Ištrinti tarpinį serverį               |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Priverstinai ištrinti                  |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Masinis priskyrimas                    |
| `GET`    | `/api/v1/management/proxies/assignments`          | Užduočių sąrašas                       |
| `GET`    | `/api/v1/management/proxies/health`               | Tarpinio serverio sveikatos statistika |

### Tuneliai API

Jei norite, kad OmniRoute egzempliorius būtų rodomas viešajam internetui (Cloudflare/ngrok/Tailscale), o ne nukreipti išeinamąjį ryšį per tarpinį serverį, žr. [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunelis REST API yra po `/api/tunnels/{cloudflared,ngrok,tailscale}/*` ir yra statmenas pirmiau dokumentuotai išeinančiajai tarpinio serverio grandinei.

### 1proxy API

| Metodas  | Galutinis taškas                       | Aprašymas                                   |
| -------- | -------------------------------------- | ------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Išvardykite 1 tarpinius serverius           |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Gaukite statistiką + sinchronizavimo būsena |
| `GET`    | `/api/settings/oneproxy?action=status` | Gaukite tik sinchronizavimo būseną          |
| `POST`   | `/api/settings/oneproxy`               | Trigerio sinchronizavimas                   |
| `POST`   | `/api/settings/oneproxy/rotate`        | Pasukti į kitą įgaliotąjį serverį           |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Ištrinti vieną                              |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Išvalyti viską                              |

### Prieš srovę tarpinis serveris API

| Metodas  | Galutinis taškas                  | Aprašymas                                        |
| -------- | --------------------------------- | ------------------------------------------------ |
| `GET`    | `/api/upstream-proxy/:providerId` | Gaukite tarpinio serverio konfigūraciją          |
| `PUT`    | `/api/upstream-proxy/:providerId` | Nustatykite tarpinio serverio režimą prieš srovę |
| `DELETE` | `/api/upstream-proxy/:providerId` | Pašalinkite tarpinio serverio konfigūraciją      |

---

## Aplinkos kintamieji

| Kintamasis            | Numatytoji | Aprašymas                                                                       |
| --------------------- | ---------- | ------------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`     | Įgalinti SOCKS5 tarpinio serverio palaikymą (numatytasis `true` `.env.example`) |

---

## Trikčių šalinimas

### „SOCKS5 tarpinis serveris išjungtas“

Savo `.env` faile nustatykite `ENABLE_SOCKS5_PROXY=true` ir paleiskite iš naujo.

### „Socket Hang up“ klaidos per tarpinį serverį

Tai normalu naudojant pigius tarpinius serverius, kurie nutraukia tuščiosios eigos ryšius. OmniRoute tai jau tvarko:

- Išjungti tarpinio serverio ryšį (`keepAliveTimeout: 1`)
- Dujotiekio išjungimas (`pipelining: 0`)
- Dispečerių kaupimas talpykloje, kad būtų išvengta pasikartojančių rankų paspaudimų

Jei jis išlieka, išbandykite kitą tarpinį serverį arba naudokite 1 tarpinio serverio sukimosi funkciją.

### „nepalaikoma_šalies_regiono_teritorija“ OAuth metu

Įsitikinkite, kad tarpinis serveris sukonfigūruotas** prieš** pradedant OAuth srautą. OmniRoute nukreipia OAuth prieigos raktų mainus per sukonfigūruotą tarpinį serverį. Pirmiausia nustatykite visuotinį arba teikėjo lygio tarpinį serverį, tada prisijunkite.

### Tarpinis serveris nenaudojamas

Patikrinkite rezoliucijos tvarką:

1. Patvirtinkite naudodami `GET /api/settings/proxy?resolve=your-connection-id`
2. Patikrinkite, ar tarpinis serveris `status` yra `active` (ne `inactive`)
3. Įsitikinkite, kad tarpinio serverio priskyrimo sritis atitinka jūsų ryšį

### 1 tarpinio serverio sinchronizavimas nepavyko

Patikrinkite sinchronizavimo būseną:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Jei `consecutiveFailures >= 5`, suveikė grandinės pertraukiklis. Iš naujo paleiskite serverį, kad nustatytumėte iš naujo, arba palaukite, kol bus nustatytas iš naujo.

---

## Duomenų bazės schema

### `proxy_registry` lentelė

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

### `proxy_assignments` lentelė

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

## Tarpinio serverio būklės tikrinimas (v3.8.16 +)

OmniRoute's** tarpinis serveris greitai nepavyksta** mechanizmas (`src/lib/proxyHealth.ts`) aptinka mirusius tarpinius serverius < 2s, atlikdamas greitą TCP ryšio patikrinimą, tada** išsaugo rezultatą** kad išvengtumėte papildomų išlaidų pagal užklausą.

### Kaip tai veikia

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

Be to, neveikiantis tarpinis serveris blokuotų kiekvieną visos `PROXY_TIMEOUT_MS` užklausą (numatytasis 30 s), kol nepavyks.

### Derinami aplinkos kintamieji

| Kintamasis                   | Numatytoji | Tikslas                                                  |
| ---------------------------- | ---------- | -------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`     | TCP ryšio skirtasis laikas vienam sveikatos patikrinimui |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`    | Kiek laiko talpykloje saugomas sveikatos rezultatas      |

**Rekomenduojamos vertės:**

| Scenarijus                      | Greitas nesėkmės skirtasis laikas | Talpykla TTL | Samprotavimas                                                                          |
| ------------------------------- | --------------------------------- | ------------ | -------------------------------------------------------------------------------------- |
| Didelio našumo API vartai       | 1500 ms                           | 60 000 ms    | Agresyvi greita, ilgesnė talpykla, siekiant sumažinti patikrinimus                     |
| Geografiškai paskirstyti mazgai | 3000 ms                           | 15 000 ms    | Lėtesniems tinklams reikia daugiau laiko; trumpesnė talpykla, skirta greitai perjungti |
| Kūrėjas / testavimas            | 1000 ms                           | 10 000 ms    | Greita iteracija vietiniuose tarpiniuose serveriuose                                   |
| Slaptas / anti-aptikimas        | 2500 ms                           | 45 000 ms    | Venkite greito zondavimo, kuris gali sukelti greičio ribas                             |

### Proxy sveikatos tikrinimas

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

`stale` vėliava yra `true`, kai talpyklos įrašas viršija `HEALTH_CACHE_TTL_MS`, o kita užklausa suaktyvins naują patikrinimą.

### Numatytieji tarpinio serverio tipo nustatymai

Būklės patikrinime naudojami protingi numatytieji nustatymai, pagrįsti URL schema:

| Schema                     | Numatytasis prievadas |
| -------------------------- | --------------------- |
| `http://`                  | 8080                  |
| `https://`                 | 443                   |
| `socks5://` / `socks5h://` | 1080                  |

Pasirinktiniai prievadai URL (`http://host:9999`) visada turi viršenybę prieš numatytuosius schemos nustatymus.

---

## Tarpinio serverio analizė ir stebėjimas

OmniRoute seka tarpinio serverio naudojimą, kad padėtų operatoriams diagnozuoti maršruto šablonus, delsos šuolius ir pasikartojančius gedimus.

### Kas sekama

Kiekvienai užklausai per sukonfigūruotą tarpinį serverį OmniRoute įrašo:

| Metrika      | Aprašymas                                                                            |
| ------------ | ------------------------------------------------------------------------------------ |
| `proxy_url`  | Visas tarpinis serveris URL (su užmaskuotais autentifikavimo kredencialais)          |
| `provider`   | ID tiekėjas (openai, antropinis ir kt.)                                              |
| `latency_ms` | Visas kelionės pirmyn ir atgal laikas, įskaitant tarpinio serverio rankos paspaudimą |
| `connect_ms` | TCP tik prisijungimo laikas                                                          |
| `status`     | HTTP būsenos kodas iš prieš srovę                                                    |
| `error`      | Klaidos klasė, jei užklausa nepavyko                                                 |
| `timestamp`  | ISO 8601 UTC                                                                         |

### Prieiga prie duomenų

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Tikrasis galutinis taškas yra `/api/usage/proxy-logs` (žr. `src/app/api/usage/proxy-logs/route.ts`). Šis galutinis taškas palaiko:

- `GET /api/usage/proxy-logs` — gauti tarpinio serverio žurnalus
- `DELETE /api/usage/proxy-logs` — išvalyti visus tarpinio serverio žurnalus

Jei reikia, apibendrintos statistikos užklausą galima pateikti tiesiai iš `proxy_logs` lentelės per SQL. Prietaisų skydelyje UI gali būti pateikti bendri rodiniai.

### Įprasti modeliai

**Aptikti besiplečiantį tarpinį serverį** (pakaitomis tarp success/failure):

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

**Raskite lėtus tarpinius serverius** (p95 delsa > 2s):

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

## Rotacijos strategijos sprendimų medis

Kai apimčiai priskiriami keli tarpiniai serveriai, OmniRoute naudoja a** rotacijos strategija** pasirinkti, kurį naudoti kiekvienai užklausai. Strategija sukonfigūruojama apimties lygiu (visuotiniu, tiekėjo, paskyros, derinio).

### Galimos strategijos

| strategija              | Kada naudoti                                    | Kompromisas                                                                            |
| ----------------------- | ----------------------------------------------- | -------------------------------------------------------------------------------------- |
| `quality` (numatytasis) | Gamyba su mišrios kokybės tarpiniais serveriais | Pirmenybę teikia aukšto įvertinimo tarpiniams serveriams; gali badauti žemai vertinami |
| `random`                | Krovinių paskirstymas, privatumas               | Tolygus paskirstymas; nepaiso kokybės signalų                                          |
| `sequential`            | Derinimas, deterministinis testavimas           | Pereina tarpinius serverius eilės tvarka; lengva samprotauti                           |

### Sprendimų medis

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

## Automatinis gedimų pašalinimas jūsų įgaliotiesiems serveriams

1proxy prekyvietės telkinys jau automatiškai pablogina nepavykusius tarpinius serverius (žr. [Tarpinio serverio kokybės balus](#proxy-quality-scores) ). Įgaliotiesiems serveriams** tu** pridėtas prie registro, fono būklės planavimo priemonė (`src/lib/proxyHealth/scheduler.ts`) užtikrina tą patį veiksmą „automatiškai pašalinti mirusį narį iš grandinės“ nieko neištrindama:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Kaip jis tinka kelių tarpinių serverių grandinei:

1. Planavimo priemonė tikrina kiekvieną registruotą tarpinį serverį kas `PROXY_HEALTH_INTERVAL_MS` (numatytasis 10 min.; mažiausiai 1 min.).
2. Po `PROXY_AUTO_REMOVE_AFTER` iš eilės** įtikinamas** gedimų (tikras ryšio sutrikimas — a timeout arba zondo taikinio 5xx niekada neskaičiuojami, žr. [Tarpinio serverio būklės patikrinimas](#proxy-health-checking-v3816) ), tarpinio serverio `status` nustatytas į `dead`.
3. `dead` yra viena iš būsenų, kurių neįtraukia pool/rotation skiriamosios gebos naudojamas gyvos būsenos filtras, todėl apimties sukimasis (apvalus / atsitiktinis / lipnus / latentinis — žr. [sukimosi strategijos sprendimų medį](#rotation-strategy-decision-tree) ) nedelsiant nustoja perduoti tą įgaliotąjį serverį naujoms užklausoms. Neveikia jokie kiti tarpiniai serveriai, o visas baseinas niekada tyliai negrįžta prie tiesioginio ryšio — žr. [4 lygių tarpinio serverio sistemos](#4-level-proxy-system) gedimų uždarymo apsaugą.
4. Planuoklis nuolat tikrina `dead` tarpinius serverius tuo pačiu intervalu. Kitas sėkmingas zondas apverčia `status` atgal į `active` ir vėl pradeda suktis — nereikia rankiniu būdu pakartotinai pridėti.

Tai yra sąmoningai** pasirenkamas ir nedestruktyvus** : pagal numatytuosius nustatymus planuoklis skaičiuoja ir registruoja tik klaidas (žr. politiką C, esančią `decision.ts`), o `PROXY_AUTO_DISABLE` niekada nepanaikina — eilutės, tam skirta atskira, agresyvesnė `PROXY_AUTO_REMOVE` vėliavėlė. Jei abu nustatyti į `true`, laimi `PROXY_AUTO_REMOVE` (tarpinis serveris, kurį ketinama ištrinti, nenaudoja minkšto išjungimo tarp jų). Visą kintamųjų sąrašą rasite [aplinkos konfigūracijos](../reference/ENVIRONMENT.md) nuorodoje.

---

> 📖** Susiję dokumentai:**
>
> - [Vartotojo vadovas](../guides/USER_GUIDE.md) — Bendra sąranka ir konfigūracija – [API Nuoroda](../reference/API_REFERENCE.md) — Visa API dokumentacija – [Aplinkos konfigūracija](../reference/ENVIRONMENT.md) — Visi aplinkos kintamieji
