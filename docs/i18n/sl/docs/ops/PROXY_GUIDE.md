# 🌐 OmniRoute Proxy Guide (Slovenščina)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Zaobidite geografske bloke, zaščitite svojo identiteto in usmerite promet AI prek katerega koli posrednika — brez zapletenosti konfiguracije.**

OmniRoute vključuje sistem za upravljanje proxyja s polnimi funkcijami, ki vam omogoča usmerjanje prometa ponudnika AI navzgor prek proxyjev HTTP, HTTPS ali SOCKS5. Ne glede na to, ali ste v blokiranem območju, potrebujete rotacijo IP ali želite prikriti prstni odtis — ta vodnik pokriva vse.

---

## Kazalo

- [Zakaj uporabljati posrednike?](#why-use-proxies)
- [Pregled arhitekture](#architecture-overview)
- [4-nivojski proxy sistem](#4-level-proxy-system)
- [Register posrednikov (CRUD)](#proxy-registry-crud)
- [1proxy Free Marketplace](#1proxy-free-proxy-marketplace)
- [Proxy rotacija](#proxy-rotation)
- [Preprečevanje odkrivanja in prikrivanje](#anti-detection--stealth)
- [Upstream proxy načini](#upstream-proxy-modes)
- [Nadzorna plošča UI](#dashboard-ui)
- [Referenca API](#api-reference)
- [Spremenljivke okolja](#environment-variables)
- [Odpravljanje težav](#troubleshooting)

---

## Zakaj uporabljati posrednike?

Mnogi ponudniki AI omejujejo dostop glede na geografsko regijo. Razvijalci v** Rusija, Kitajska, Iran, Kuba, Turčija** in druge države naletijo na napake, kot so:

```
unsupported_country_region_territory
```

Celo zunaj blokiranih regij so posredniki uporabni za:

| Primer uporabe           | Opis                                                                |
| ------------------------ | ------------------------------------------------------------------- |
| **Geografska obvoznica** | Dostop do OpenAI, Anthropic, Codex, Copilot iz blokiranih držav     |
| **vrtenje IP**           | Porazdelite zahteve med več IPs, da se izognete omejevanju hitrosti |
| **Zasebnost**            | Skrijte svoj pravi IP pred višjimi ponudniki                        |
| **Skladnost**            | Usmerite promet skozi določene jurisdikcije                         |
| **Testiranje**           | Simulirajte zahteve iz različnih regij                              |

---

## Pregled arhitekture

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

### Ključne komponente

| Komponenta                 | Datoteka                                     | Vloga                                                         |
| -------------------------- | -------------------------------------------- | ------------------------------------------------------------- |
| **Register pooblaščencev** | `src/lib/db/proxies.ts`                      | CRUD za proxy vnose dodelitev obsega +                        |
| **Proxy dispečer**         | `open-sse/utils/proxyDispatcher.ts`          | Ustvari odpremnike `undici` ProxyAgent/SOCKS s predpomnjenjem |
| **Proxy Fetch**            | `open-sse/utils/proxyFetch.ts`               | Ovije `fetch()` z vbrizgavanjem proxy dispecherja             |
| **Nastavitve poti**        | `src/app/api/settings/proxy/route.ts`        | Podedovana konfiguracija proxyja API (GET/PUT/DELETE)         |
| **Management Route**       | `src/app/api/v1/management/proxies/route.ts` | Register CRUD API (GET/POST/PATCH/DELETE)                     |
| **1proxy DB**              | `src/lib/db/oneproxy.ts`                     | Vztrajnost brezplačne tržnice proxy                           |

---

## Privzeto stanje posrednika za nove račune

noter** Nastavitve → Proxy → Globalna konfiguracija** , uporabite** Privzeto omogoči proxy za nove povezave** da izberete začetno stanje posrednika za novo dodane račune ponudnika.

Nova nastavitev nadzira začetno stanje proxyja na novo dodanih računov ponudnika. Ne spremeni obstoječih računov ali zamenja globalnega proxy stikala. Njegova začetna vrednost ohranja prejšnje vedenje. Enkrat ga izklopite, če želite v prihodnje ustvariti račune s privzeto onemogočenim proxyjem.

Nastavitve so shranjene kot `defaultNewConnectionProxyEnabled` prek obstoječih nastavitev API. Ko ni nikoli shranjen, je privzeto nastavljen na `true`. Shranjevanje `false` začne veljati za naslednje nove račune brez ponovnega zagona. `POST /api/providers` sprejme neobvezno strogo logično `proxyEnabled`; eksplicitni `true` ali `false` ima prednost pred privzeto vrednostjo za ustvarjanje. Opustitev podvojenega računa ali ponovne povezave OAuth ohrani shranjeno stanje tega računa. Posamezne račune lahko pozneje še vedno omogočite ali onemogočite.

Selektivni prenosi ponudnika uporabljajo privzeto vrednost ciljne namestitve za nove račune in ohranijo ciljno politiko pri zamenjavi obstoječih računov. Proxy preklopi niso prenosna polja za prenos. Obnovitev popolne varnostne kopije in zgodovinska selitev JSON/SQL ohranita obstoječo semantiko obnovitve, vključno s shranjenimi vrednostmi računa in privzetimi vrednostmi stare sheme; popolna obnovitev nastavitev lahko obnovi tudi to nastavitev.

Ta preferenca ne dodeli posrednika ali ugotovi, da je ta zdrav ali v uporabi. Dejansko usmerjanje je še vedno odvisno od globalnega stikala proxy in ustrezne konfiguracije proxyja. Sintetični ponudniki brez vztrajnega računa, promet OAuth pred ustvarjanjem računa, posredniki environment/system in mreženje zunanjih ozadij so zunaj njegovega obsega.

## 4-nivojski proxy sistem

OmniRoute podpira konfiguracijo proxyja na** štirje neodvisni obsegi** , rešeno po prednostnem vrstnem redu:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Kako deluje reševanje

Ko OmniRoute pošlje zahtevo zgornjemu ponudniku, pokliče `resolveProxyForConnectionFromRegistry()`, ki preveri vsako raven po vrstnem redu:

1. **Na ravni računa** — Ali je tej specifični povezavi ID dodeljen proxy?
2. **Na ravni ponudnika** — Ali je temu ponudniku dodeljen proxy (npr. `openai`)?
3. **Na svetovni ravni** — Ali je konfiguriran globalni proxy?
4. **Brez posrednika** — Neposredna povezava s ponudnikom.

Prva tekma zmaga. To pomeni, da lahko nastavite globalni proxy kot nadomestni, vendar ga preglasite za določene ponudnike ali povezave.

### Kaj se posreduje

| Vrsta prometa           | Proxied? | Opombe                                        |
| ----------------------- | -------- | --------------------------------------------- |
| Zaključki klepeta       | ✅       | Vse zahteve `/v1/chat/completions`            |
| Vdelave                 | ✅       | `/v1/embeddings`                              |
| Generiranje slike       | ✅       | `/v1/images/generations`                      |
| Zvok (TTS/STT)          | ✅       | `/v1/audio/*`                                 |
| izmenjava žetonov OAuth | ✅       | Rešuje `unsupported_country_region_territory` |
| Testi povezav           | ✅       | Gumb "Preizkusi povezavo" uporablja proxy     |
| Osvežitev žetona        | ✅       | Obnova OAuth v ozadju                         |
| Sinhronizacija modela   | ✅       | Seznam modelov in odkrivanje                  |

---

## Register posrednikov (CRUD)

Register proxyjev je tabela SQLite (`proxy_registry`), ki shranjuje vse vaše proxyje. Vsak proxy ima:

| Polje      | Vrsta        | Opis                                                   |
| ---------- | ------------ | ------------------------------------------------------ |
| `id`       | UUID         | Enolični identifikator                                 |
| `name`     | Niz          | Človeku berljiva etiketa                               |
| `type`     | Niz          | Protokol: `http`, `https`, `socks5`                    |
| `host`     | Niz          | Ime gostitelja posrednika ali IP                       |
| `port`     | Celo število | Številka vrat                                          |
| `username` | Niz          | Uporabniško ime za preverjanje (šifrirano v mirovanju) |
| `password` | Niz          | Geslo za avtorizacijo (šifrirano v mirovanju)          |
| `region`   | Niz          | Oznaka geografske regije                               |
| `notes`    | Niz          | Opombe s prostim besedilom                             |
| `status`   | Niz          | `active` ali `inactive`                                |
| `source`   | Niz          | `manual` ali `oneproxy`                                |

### Ustvarjanje proxyja

**Prek nadzorne plošče:**

1. Pojdi na** Nastavitve → proxy**
2. Kliknite** Dodaj proxy**
3. Izpolnite vrsto, gostitelja, vrata in izbirne poverilnice za avt
4. Shrani

**Prek API:**

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

### Posodabljanje proxyja

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Opomba:** Poverilnice se ohranijo, razen če izrecno pošljete neprazne zamenjave. Pošiljanje praznih nizov za `username`/`password` bo ohranilo shranjene vrednosti.

### Brisanje proxyja

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Posredniki za seznam

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Dodeljevanje posrednikov obsegom

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

### Razreševanje učinkovitega posrednika

Preverite, kateri proxy bi bil uporabljen za dano povezavo:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Vrne razrešen proxy z njegovo ravnjo (`account`, `provider` ali `global`) in izvorom.

### Množična dodelitev

En proxy dodelite več ponudnikom ali povezavam hkrati:

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

Proxyji so vključeni v**Backup/Restore** sistem. Ko izvozite svojo konfiguracijo OmniRoute :

1. Pojdi na** Nadzorna plošča → Nastavitve → Varnostno kopiranje**
2. Kliknite** Izvozi** — proxy register in dodelitve so vključeni
3. Če želite obnoviti, kliknite** Uvozi** in naložite datoteko varnostne kopije

Podpira tudi proxy register** upsert z vrati gostitelja +** — če uvozite proxy, ki že obstaja (isti gostitelj in vrata), se posodobi namesto ustvarjanja dvojnika.

### Selitev podedovanja

Če ste proxy konfigurirali v starejši različici (predregistracija), jih OmniRoute samodejno preseli:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

To se zgodi enkrat ob prvem zagonu po nadgradnji. Za ponovni zagon uporabite `migrateLegacyProxyConfigToRegistry({ force: true })`.

---

## 1proxy Free Proxy Marketplace

> 🆕** Prispeval [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Izdaja [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute se integrira z** [1proxy](https://1proxy-api.aitradepulse.com)** platforma skupnosti za zagotavljanje dostopa** na stotine brezplačnih potrjenih posrednikov** z vsega sveta. To je kot nalašč za uporabnike, ki nimajo lastne infrastrukture proxy.

### Kako deluje

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sinhronizacija** — OmniRoute pridobi potrjene proxyje iz 1proxy API
2. **Trgovina** — Proxyji so shranjeni v isti tabeli `proxy_registry` kot `source = 'oneproxy'`
3. **Filter** — Filtriraj po protokolu, državi, oceni kakovosti
4. **Zasukaj** — Izberite najboljši proxy z uporabo kakovostnih, naključnih ali zaporednih strategij
5. **Samodejna razgradnja** — Neuspelim posrednikom se zniža ocena kakovosti; pod pragom → označeno kot neaktivno

### Sinhronizacija posrednikov

**Prek nadzorne plošče:**

1. Pojdi na** Nastavitve → 1proxy** zavihek
2. Kliknite** "Sinhroniziraj zdaj"**
3. Ogled statistike: skupni posredniki, število aktivnih, povprečna kakovost, razčlenitev po državah

**Prek API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtriranje posrednikov

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

### Približne ocene kakovosti

Vsak proxy 1proxy ima metapodatke:

| Polje           | Opis                                       |
| --------------- | ------------------------------------------ |
| `qualityScore`  | Ocena 0-100 iz preverjanja 1proxy          |
| `latencyMs`     | Izmerjena zakasnitev omrežja               |
| `anonymity`     | `transparent`, `anonymous` ali `elite`     |
| `googleAccess`  | Ali lahko proxy dostopa do storitev Google |
| `countryCode`   | Dvočrkovna koda države ISO                 |
| `lastValidated` | Časovni žig zadnjega preverjanja           |

Ocene kakovosti se dinamično prilagajajo:

- **Neuspele zahteve** znižati rezultat za 10 točk
- **Rezultat pade na ≤ 10** → proxy ima oznako `inactive`
- Neaktivni posredniki so izključeni iz rotacije

### Strategije rotacije

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

### Odklopnik

1proxy sync ima vgrajen odklopnik:

- Po** 5 zaporednih napak pri sinhronizaciji** , so nadaljnji poskusi sinhronizacije blokirani
- Ponastavite z: `resetOneproxyCircuitBreaker()` ali znova zaženite strežnik
- Stanje sinhronizacije je na voljo na `GET /api/settings/oneproxy?action=status`

### Čiščenje posrednikov 1proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Preprečevanje odkrivanja in prikrivanje

OmniRoute ne samo usmerja prometa prek proxyja — ampak naredi promet videti legitimen:

### TLS Prevara prstnih odtisov

Uporablja `wreq-js` za generiranje prstnih odtisov TLS, podobnih brskalniku, mimo sistemov za zaznavanje botov, ki označujejo rokovanja TLS ki niso v brskalniku.

### ujemanje prstnih odtisov CLI

The**CLI Preklop prstnih odtisov** (`Settings → Security`) preureja glave HTTP in polja telesa JSON, da se ujemajo z natančnim podpisom izvornih binarnih datotek CLI (koda Claude, Codex itd.). To deluje** na vrhu** posrednik:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Dobiš oboje** maskiranje IP** in** zahtevati pristnost** istočasno.

### Proxy IP Ohranjanje

Barvno kodirane značke na nadzorni plošči kažejo, katera raven proxyja je aktivna:

| Značka | Raven    | Pomen                                     |
| ------ | -------- | ----------------------------------------- |
| 🟢     | Globalno | Ves promet gre skozi ta proxy             |
| 🟡     | Ponudnik | Proxy je samo promet tega ponudnika       |
| 🔵     | Povezava | Ta posebna key/account uporablja ta proxy |

Značka prikazuje tudi razrešen proxy IP za preverjanje.

---

## Upstream proxy načini

Za ponudnike, ki uporabljajo vzorec CLIProxyAPI, OmniRoute podpira tri načine posredniškega strežnika navzgor:

| Način         | Opis                                                       |
| ------------- | ---------------------------------------------------------- |
| `native`      | OmniRoute obravnava neposredno proxy usmerjanje (privzeto) |
| `cliproxyapi` | Pooblastila za zunanji primerek CLIProxyAPI                |
| `fallback`    | Najprej poskusi izvorno, se vrne na CLIProxyAPI            |

Konfiguriraj po ponudniku:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Nadzorna plošča UI

### Nastavitve zavihek Proxy →

- **Globalni posrednik** konfiguracija (nastavljena enkrat za ves promet)
- **Proxy na ponudnika** preglasi
- **Proxy na povezavo** naloge
- **Test povezave** prek konfiguriranega proxyja
- **Barvno kodirane značke** prikazuje aktivno raven posrednika

### Nastavitve → 1proxy Tab

- **Sinhroniziraj zdaj** gumb za pridobivanje brezplačnih proxyjev
- **Statistične kartice** : skupno, aktivno, povprečna kakovost, zadnja sinhronizacija
- **Filtri** : protokol, koda države, minimalna kakovost
- **Proxy tabela** z gostiteljem, protokolom, državo, oceno kakovosti, zakasnitvijo, anonimnostjo, dostopom Google
- **Stanje sinhronizacije** plošča s sledenjem success/failure in številom zaporednih napak
- **Počisti vse** da odstranite vse vnose 1proxy

---

## Referenca API

### Nastavitve proxyja API

| Metoda   | Končna točka                                   | Opis                                    |
| -------- | ---------------------------------------------- | --------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Pridobite popolno konfiguracijo proxyja |
| `GET`    | `/api/settings/proxy?level=global`             | Pridobite globalni proxy                |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Pridobite proxy ponudnika               |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Razreši učinkovit proxy                 |
| `PUT`    | `/api/settings/proxy`                          | Posodobite konfiguracijo proxyja        |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Odstrani proxy na ravni                 |

### Register posrednikov API

| Metoda   | Končna točka                                      | Opis                             |
| -------- | ------------------------------------------------- | -------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Seznam vseh posrednikov          |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Pridobite proxy prek ID          |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Pridobite dodelitve posrednikov  |
| `POST`   | `/api/v1/management/proxies`                      | Ustvari proxy                    |
| `PATCH`  | `/api/v1/management/proxies`                      | Posodobi proxy                   |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Izbriši proxy                    |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Prisilno brisanje                |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Množična dodelitev               |
| `GET`    | `/api/v1/management/proxies/assignments`          | Seznam nalog                     |
| `GET`    | `/api/v1/management/proxies/health`               | Približna zdravstvena statistika |

### Predori API

Za izpostavljanje vašega primerka OmniRoute javnemu internetu (Cloudflare/ngrok/Tailscale) namesto usmerjanja odhodnih prek proxyja glejte [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Predor REST API živi pod `/api/tunnels/{cloudflared,ngrok,tailscale}/*` in je pravokoten na zgoraj dokumentirano izhodno proxy verigo.

### 1proxy API

| Metoda   | Končna točka                           | Opis                                         |
| -------- | -------------------------------------- | -------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Seznam 1proxy proxyjev                       |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Pridobite statistiko stanja sinhronizacije + |
| `GET`    | `/api/settings/oneproxy?action=status` | Pridobite samo stanje sinhronizacije         |
| `POST`   | `/api/settings/oneproxy`               | Sinhronizacija sprožilca                     |
| `POST`   | `/api/settings/oneproxy/rotate`        | Zavrti na naslednji proxy                    |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Izbriši enega                                |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Počisti vse                                  |

### Upstream Proxy API

| Metoda   | Končna točka                      | Opis                                             |
| -------- | --------------------------------- | ------------------------------------------------ |
| `GET`    | `/api/upstream-proxy/:providerId` | Pridobite konfiguracijo proxyja navzgor          |
| `PUT`    | `/api/upstream-proxy/:providerId` | Nastavite način proxy navzgor                    |
| `DELETE` | `/api/upstream-proxy/:providerId` | Odstranite konfiguracijo strežnika proxy navzgor |

---

## Spremenljivke okolja

| Spremenljivka         | Privzeto | Opis                                                               |
| --------------------- | -------- | ------------------------------------------------------------------ |
| `ENABLE_SOCKS5_PROXY` | `true`   | Omogoči podporo za proxy SOCKS5 (privzeto `true` v `.env.example`) |

---

## Odpravljanje težav

### "SOCKS5 proxy je onemogočen"

Nastavite `ENABLE_SOCKS5_PROXY=true` v datoteko `.env` in znova zaženite.

### napake "socket hang up" prek proxyja

To je običajno pri poceni proxyjih, ki prekinejo nedejavne povezave. OmniRoute to že obravnava z:

- Onemogočanje vzdrževanja pri povezavah proxy (`keepAliveTimeout: 1`)
- Onemogočanje cevovoda (`pipelining: 0`)
- Predpomnjenje dispečerjev, da se izognete ponavljajočim se rokovanjem

Če se nadaljuje, poskusite z drugim proxyjem ali uporabite funkcijo rotacije 1proxy.

### "unsupported_country_region_territory" med OAuth

Prepričajte se, da je proxy konfiguriran** prej** zagon toka OAuth. OmniRoute usmerja izmenjavo žetonov OAuth prek konfiguriranega proxyja. Najprej nastavite globalni proxy ali proxy na ravni ponudnika, nato se povežite.

### Proxy se ne uporablja

Preverite vrstni red reševanja:

1. Preveri z `GET /api/settings/proxy?resolve=your-connection-id`
2. Preverite, ali je proxy `status` `active` (ne `inactive`)
3. Prepričajte se, da obseg dodelitve posrednika ustreza vaši povezavi

### 1proxy sinhronizacija ni uspela

Preverite stanje sinhronizacije:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Če je `consecutiveFailures >= 5`, se je sprožil odklopnik. Znova zaženite strežnik za ponastavitev ali počakajte na ročno ponastavitev.

---

## Shema baze podatkov

### tabela `proxy_registry`

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

### tabela `proxy_assignments`

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

## Preverjanje stanja proxyja (v3.8.16 +)

OmniRoute** proxy fast-fail** mehanizem (`src/lib/proxyHealth.ts`) zazna mrtve posredniške strežnike v < 2s prek hitrega preverjanja povezave TCP, nato** predpomni rezultat** da se izognete dodatnim stroškom na zahtevo.

### Kako deluje

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

Brez tega bi mrtev proxy blokiral vsako zahtevo za celotno `PROXY_TIMEOUT_MS` (privzeto 30 s), preden bi odpovedal.

### Nastavljive spremenljivke okolja

| Spremenljivka                | Privzeto | Namen                                                                 |
| ---------------------------- | -------- | --------------------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`   | časovna omejitev povezave TCP na pregled zdravja                      |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`  | Kako dolgo je rezultat zdravstvenega stanja shranjen v predpomnilniku |

**Priporočene vrednosti:**

| Scenarij                          | Časovna omejitev za hitro napako | Predpomnilnik TTL | Utemeljitev                                                                    |
| --------------------------------- | -------------------------------- | ----------------- | ------------------------------------------------------------------------------ |
| Prehod API z visoko zmogljivostjo | 1500 ms                          | 60000 ms          | Agresiven fail-fast, daljši predpomnilnik za zmanjšanje preverjanj             |
| Geografsko porazdeljena vozlišča  | 3000 ms                          | 15000 ms          | Počasnejša omrežja potrebujejo več časa; krajši predpomnilnik za hitro preklop |
| Dev / testiranje                  | 1000 ms                          | 10000 ms          | Hitra ponovitev na lokalnih proxyjih                                           |
| Stealth / proti zaznavanju        | 2500 ms                          | 45000 ms          | Izogibajte se hitremu sondiranju, ki bi lahko sprožilo omejitve hitrosti       |

### Pregled proxy Health

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Zastavica `stale` je `true`, ko vnos v predpomnilnik preseže `HEALTH_CACHE_TTL_MS` in bo naslednja zahteva sprožila novo preverjanje.

### Privzete nastavitve za vrsto posrednika

Preverjanje zdravja uporablja razumne privzete vrednosti na podlagi sheme URL :

| Shema                      | Privzeta vrata |
| -------------------------- | -------------- |
| `http://`                  | 8080           |
| `https://`                 | 443            |
| `socks5://` / `socks5h://` | 1080           |

Vrata po meri v URL (`http://host:9999`) imajo vedno prednost pred privzeto shemo.

---

## Proxy Analytics in opazljivost

OmniRoute sledi uporabi posameznega posrednika, da pomaga operaterjem diagnosticirati vzorce usmerjanja, skoke zakasnitev in ponavljajoče se napake.

### Kaj se spremlja

Za vsako zahtevo prek konfiguriranega proxyja OmniRoute zabeleži:

| metrika      | Opis                                                              |
| ------------ | ----------------------------------------------------------------- |
| `proxy_url`  | Celoten proxy URL (s prikritimi poverilnicami)                    |
| `provider`   | Upstream ponudnik ID (openai, anthropic itd.)                     |
| `latency_ms` | Skupni čas povratnega potovanja, vključno z rokovanjem posrednika |
| `connect_ms` | samo čas povezovanja TCP                                          |
| `status`     | koda stanja HTTP od zgoraj                                        |
| `error`      | Razred napake, če zahteva ni uspela                               |
| `timestamp`  | ISO 8601 UTC                                                      |

### Dostop do podatkov

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Prava končna točka je `/api/usage/proxy-logs` (glejte `src/app/api/usage/proxy-logs/route.ts`). Ta končna točka podpira:

- `GET /api/usage/proxy-logs` — pridobi dnevnike strežnika proxy
- `DELETE /api/usage/proxy-logs` — počisti vse dnevnike strežnika proxy

Po potrebi lahko zbirne statistike poizvedujete neposredno iz tabele `proxy_logs` prek SQL. Nadzorna plošča UI lahko ponuja zbirne poglede.

### Pogosti vzorci

**Zaznaj plapolni proxy** (izmenično med success/failure):

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

**Poiščite počasne posrednike** (p95 zakasnitev > 2s):

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

## Odločitveno drevo strategije rotacije

Ko je obsegu dodeljenih več posrednikov, OmniRoute uporablja a** strategijo rotacije** da izberete, katero želite uporabiti za vsako zahtevo. Strategija je konfigurirana na ravni obsega (globalno, na ponudnika, na račun, na kombinacijo).

### Razpoložljive strategije

| Strategija           | Kdaj uporabiti                                 | Kompromis                                                                      |
| -------------------- | ---------------------------------------------- | ------------------------------------------------------------------------------ |
| `quality` (privzeto) | Produkcija s posredniki mešane kakovosti       | Daje prednost pooblaščencem z visoko oceno; lahko stradajo tiste z nizko oceno |
| `random`             | Porazdelitev bremena, zasebnost                | Enakomerna porazdelitev; ignorira kakovostne signale                           |
| `sequential`         | Odpravljanje napak, deterministično testiranje | Kroži skozi posrednike po vrstnem redu; enostavno sklepati                     |

### Drevo odločitev

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

## Samodejna izključitev napak za vaše lastne posrednike

Skupina tržnice 1proxy že sama samodejno poslabša neuspešne posrednike (glejte [Ocene kakovosti posrednikov](#proxy-quality-scores) ). Za pooblaščence** ti** dodan v register, razporejevalnik zdravja v ozadju (`src/lib/proxyHealth/scheduler.ts`) zagotavlja enako vedenje "samodejno izključi mrtvega člana iz verige", ne da bi karkoli izbrisal:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Kako se prilega verigi z več posredniki:

1. Razporejevalnik preišče vsak registriran proxy vsak `PROXY_HEALTH_INTERVAL_MS` (privzeto 10 min; najmanj 1 min).
2. Po `PROXY_AUTO_REMOVE_AFTER` zaporedni** dokončno** napake (resnična napaka povezave — časovna omejitev ali lastni cilj sonde 5xx nikoli ne šteje, glejte [Preverjanje zdravja proxyja](#proxy-health-checking-v3816) ), je `status` proxyja nastavljen na `dead`.
3. `dead` je eno od stanj, ki jih filter živega stanja, ki ga uporablja resolucija pool/rotation izključuje, tako da kroženje obsega (krožno / naključno / lepljivo / zakasnitev — glejte [Odločitveno drevo strategije vrtenja](#rotation-strategy-decision-tree) ) takoj preneha predajati ta proxy novim zahtevam. To ne vpliva na noben drug strežnik proxy v bazenu in celoten bazen se nikoli tiho ne vrne na neposredno povezavo — glejte [4-nivojsko zaščito pred zaprtjem sistema proxy](#4-level-proxy-system).
4. Razporejevalnik še naprej preiskuje posrednike `dead` v istem intervalu. Naslednja uspešna sonda obrne `status` nazaj na `active` in ponovno vstopi v rotacijo — ročno ponovno dodajanje ni potrebno.

To je namerno** opt-in in nedestruktivno** : razporejevalnik privzeto samo šteje in beleži napake (glejte pravilnik C v `decision.ts`), `PROXY_AUTO_DISABLE` pa nikoli ne izbriše vrstice — čemur je namenjena ločena, bolj agresivna zastavica `PROXY_AUTO_REMOVE`. Če sta oba nastavljena na `true`, `PROXY_AUTO_REMOVE` zmaga (proxy, ki bo kmalu izbrisan, ne potrebuje vmesnega mehkega onemogočanja). Za celoten seznam spremenljivk glejte referenco [Environment Config](../reference/ENVIRONMENT.md).

---

> 📖** Povezana dokumentacija:**
>
> - [Uporabniški priročnik](../guides/USER_GUIDE.md) — Splošna nastavitev in konfiguracija - [Referenca API](../reference/API_REFERENCE.md) — Celotna dokumentacija API - [Konfiguracija okolja](../reference/ENVIRONMENT.md) — Vse spremenljivke okolja
