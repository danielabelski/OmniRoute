# 🌐 OmniRoute Proxy Guide (Bosanski)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Zaobiđite geografske blokove, zaštitite svoj identitet i usmjerite AI promet kroz bilo koji proxy — sa nultom složenošću konfiguracije.**

OmniRoute uključuje potpuno opremljen sistem upravljanja proxyjem koji vam omogućava da usmjerite uzvodni promet AI provajdera kroz HTTP, HTTPS ili SOCKS5 proxy. Bilo da se nalazite u blokiranoj regiji, trebate IP rotaciju ili želite prikriveno uzimanje otisaka prstiju — ovaj vodič pokriva sve.

---

## Sadržaj

- [Zašto koristiti proksije?](#why-use-proxies)
- [Pregled arhitekture](#architecture-overview)
- [Proxy sistem na 4 nivoa](#4-level-proxy-system)
- [Proxy registar (CRUD)](#proxy-registry-crud)
- [1proxy Free Marketplace](#1proxy-free-proxy-marketplace)
- [Proxy Rotation](#proxy-rotation)
- [Anti-Detection & Stealth](#anti-detection--stealth)
- [Upstream Proxy Modes](#upstream-proxy-modes)
- [Dashboard UI](#dashboard-ui)
- [API Reference](#api-reference)
- [Varijable okruženja](#environment-variables)
- [Rješavanje problema](#troubleshooting)

---

## Zašto koristiti proksije?

Mnogi AI provajderi ograničavaju pristup prema geografskoj regiji. Programeri u** Rusija, Kina, Iran, Kuba, Turska** , a druge zemlje nailaze na greške kao što su:

```
unsupported_country_region_territory
```

Čak i izvan blokiranih regija, proksiji su korisni za:

| Slučaj upotrebe           | Opis                                                                         |
| ------------------------- | ---------------------------------------------------------------------------- |
| **Geografska obilaznica** | Pristupite OpenAI, Anthropic, Codex, Copilot iz blokiranih zemalja           |
| **IP rotacija**           | Distribuirajte zahtjeve na više IPs kako biste izbjegli ograničavanje brzine |
| **Privatnost**            | Sakrijte svoju pravu IP od upstream provajdera                               |
| **Usklađenost**           | Usmjerite promet kroz određene jurisdikcije                                  |
| **Testiranje**            | Simulirajte zahtjeve iz različitih regija                                    |

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

| Komponenta           | File                                         | Uloga                                                    |
| -------------------- | -------------------------------------------- | -------------------------------------------------------- |
| **Proxy Registry**   | `src/lib/db/proxies.ts`                      | CRUD za proxy unose + dodjele opsega                     |
| **Proxy Dispatcher** | `open-sse/utils/proxyDispatcher.ts`          | Kreira `undici` ProxyAgent/SOCKS dispečere sa keširanjem |
| **Proxy Fetch**      | `open-sse/utils/proxyFetch.ts`               | Omotava `fetch()` sa injekcijom proxy dispečera          |
| **Postavke Ruta**    | `src/app/api/settings/proxy/route.ts`        | Naslijeđena proxy konfiguracija API (GET/PUT/DELETE)     |
| **Ruta upravljanja** | `src/app/api/v1/management/proxies/route.ts` | Registar CRUD API (GET/POST/PATCH/DELETE)                |
| **1proxy DB**        | `src/lib/db/oneproxy.ts`                     | Postojanost besplatnog proxy tržišta                     |

---

## Zadano stanje proxyja za nove račune

U** Postavke → Proxy → Globalna konfiguracija** , koristiti** Omogući proxy prema zadanim postavkama za nove veze** da odaberete početno stanje proxyja novododatih naloga provajdera.

Nova postavka kontrolira početno stanje proxyja novododatih računa provajdera. Ne mijenja postojeće račune niti zamjenjuje globalni proxy prekidač. Njegova početna vrijednost čuva prethodno ponašanje. Isključite ga jednom da kreirate buduće naloge s proxy onemogućenim prema zadanim postavkama.

Preference se pohranjuju kao `defaultNewConnectionProxyEnabled` kroz postojeće postavke API. Podrazumevano je `true` kada se nikada ne sačuva. Čuvanje `false` stupa na snagu za sljedeće nove račune bez ponovnog pokretanja. `POST /api/providers` prihvata opcioni strogi boolean `proxyEnabled`; eksplicitni `true` ili `false` ima prednost nad zadanim za kreiranje. Izostavljanje duplikata naloga ili OAuth ponovno povezivanje čuva pohranjeno stanje tog naloga. Pojedinačni računi se i dalje mogu omogućiti ili onemogućiti nakon toga.

Selektivni prijenosi provajdera koriste zadane postavke odredišne instalacije za nove račune i čuvaju politiku odredišta kada zamjenjuju postojeće račune. Proxy prekidači nisu prenosiva polja za prijenos. Potpuno obnavljanje sigurnosne kopije i historijska migracija JSON/SQL zadržavaju svoju postojeću semantiku vraćanja, uključujući sačuvane vrijednosti naloga i zadane postavke za naslijeđene šeme; potpuno vraćanje postavki također može vratiti ovu preferenciju.

Ova postavka ne dodjeljuje proxy niti utvrđuje da li je on zdrav ili u upotrebi. Stvarno usmjeravanje i dalje ovisi o globalnom proxy prekidaču i primjenjivoj proxy konfiguraciji. Sintetički provajderi bez trajnog naloga, OAuth saobraćaj pre kreiranja naloga, environment/system proksiji i spoljna pozadinska mreža su van njegovog delokruga.

## Proxy sistem na 4 nivoa

OmniRoute podržava proxy konfiguraciju na** četiri nezavisna opsega** , riješeno po prioritetu:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Kako Rezolucija radi

Kada OmniRoute pošalje zahtjev upstream provajderu, on poziva `resolveProxyForConnectionFromRegistry()` koji provjerava svaki nivo po redu:

1. **Na nivou naloga** — Postoji li proxy dodijeljen ovoj specifičnoj vezi ID?
2. **Nivo provajdera** — Postoji li proxy dodijeljen ovom provajderu (npr. `openai`)?
3. **Globalni nivo** — Da li je konfigurisan globalni proxy?
4. **Nema proxyja** — Direktna veza sa provajderom.

Prvi meč pobjeđuje. To znači da možete postaviti globalni proxy kao rezervni, ali ga nadjačati za određene dobavljače ili veze.

### Šta se proksira

| Vrsta saobraćaja      | Proksi? | Bilješke                                       |
| --------------------- | ------- | ---------------------------------------------- |
| Završetak ćaskanja    | ✅      | Svi `/v1/chat/completions` zahtjevi            |
| Embeddings            | ✅      | `/v1/embeddings`                               |
| Generisanje slike     | ✅      | `/v1/images/generations`                       |
| audio (TTS/STT)       | ✅      | `/v1/audio/*`                                  |
| OAuth razmjena tokena | ✅      | Rješava `unsupported_country_region_territory` |
| Testovi veze          | ✅      | Dugme "Test Connection" koristi proxy          |
| Osvježavanje tokena   | ✅      | Pozadinska obnova OAuth                        |
| Sinhronizacija modela | ✅      | Popis modela i otkriće                         |

---

## Proxy registar (CRUD)

Proxy registar je SQLite tabela (`proxy_registry`) koja pohranjuje sve vaše proxy servere. Svaki proxy ima:

| Polje      | Tip     | Opis                                               |
| ---------- | ------- | -------------------------------------------------- |
| `id`       | UUID    | Jedinstveni identifikator                          |
| `name`     | String  | Ljudski čitljiva etiketa                           |
| `type`     | String  | Protokol: `http`, `https`, `socks5`                |
| `host`     | String  | Proxy hostname ili IP                              |
| `port`     | Integer | Broj porta                                         |
| `username` | String  | Auth korisničko ime (šifrirano u mirovanju)        |
| `password` | String  | Lozinka za autentifikaciju (šifrirana u mirovanju) |
| `region`   | String  | Oznaka geografske regije                           |
| `notes`    | String  | Bilješke u slobodnom tekstu                        |
| `status`   | String  | `active` ili `inactive`                            |
| `source`   | String  | `manual` ili `oneproxy`                            |

### Kreiranje proxyja

**Preko kontrolne table:**

1. Idi na** Postavke → Proxy**
2. Kliknite** Dodaj proxy**
3. Popunite tip, host, port i opcionalne vjerodajnice
4. Sačuvaj

**Preko API:**

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

### Ažuriranje proxyja

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Napomena:** Akreditivi se čuvaju osim ako eksplicitno ne pošaljete neprazne zamjene. Slanje praznih stringova za `username`/`password` će zadržati pohranjene vrijednosti.

### Brisanje proxyja

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Listing Proxies

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Dodjeljivanje proksija opsegima

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

### Rješavanje efektivnog proxyja

Provjerite koji proxy bi se koristio za datu vezu:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Vraća razriješeni proxy s njegovim nivoom (`account`, `provider` ili `global`) i izvorom.

### Bulk Assignment

Dodijelite jedan proxy za više provajdera ili veza odjednom:

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

Proksiji su uključeni u**Backup/Restore** sistem. Kada izvezete svoju OmniRoute konfiguraciju:

1. Idi na** Kontrolna tabla → Postavke → Backup**
2. Kliknite** Izvoz** — proxy registar i dodjela su uključeni
3. Za vraćanje kliknite** Uvoz** i otpremite datoteku sigurnosne kopije

Proxy registar također podržava** upsert by host + port** — ako uvezete proxy koji već postoji (isti host i port), on se ažurira umjesto da kreira duplikat.

### Naslijeđene migracije

Ako ste konfigurirali proxy servere u starijoj verziji (pre-registry), OmniRoute ih automatski migrira:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Ovo se dešava jednom prilikom prvog pokretanja nakon nadogradnje. Koristite `migrateLegacyProxyConfigToRegistry({ force: true })` za ponovno pokretanje.

---

## 1proxy Free Proxy Marketplace

> 🆕** Priložio [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Izdanje [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute se integriše sa** [1proxy](https://1proxy-api.aitradepulse.com)** platforma zajednice kojoj treba omogućiti pristup** stotine besplatnih, provjerenih proksija** iz celog sveta. Ovo je savršeno za korisnike koji nemaju vlastitu proxy infrastrukturu.

### Kako radi

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sync** — OmniRoute dohvaća validirane proksije iz 1proxy API
2. **Store** — Proksiji se pohranjuju u istoj `proxy_registry` tabeli sa `source = 'oneproxy'`
3. **Filter** — Filtriraj po protokolu, zemlji, ocjeni kvalitete
4. **Rotiraj** — Odaberite najbolji proxy koristeći kvalitetne, nasumične ili sekvencijalne strategije
5. **Auto-degrade** — Neuspješnim proksijima se smanjuje ocjena kvaliteta; ispod praga → označen kao neaktivan

### Sinhronizacija proksija

**Preko kontrolne table:**

1. Idi na** Postavke → 1proxy** tab
2. Kliknite** "Sinhroniziraj sada"**
3. Pregledajte statistiku: ukupni proksiji, aktivni broj, prosječan kvalitet, raščlamba po zemljama

**Preko API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtriranje proksija

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

### Proxy ocjene kvalitete

Svaki 1proxy proxy dolazi s metapodacima:

| Polje           | Opis                                     |
| --------------- | ---------------------------------------- |
| `qualityScore`  | 0-100 ocjena od 1proxy validacije        |
| `latencyMs`     | Izmjereno kašnjenje mreže                |
| `anonymity`     | `transparent`, `anonymous` ili `elite`   |
| `googleAccess`  | Može li proxy pristupiti uslugama Google |
| `countryCode`   | Dvoslovni ISO kod zemlje                 |
| `lastValidated` | Vremenska oznaka posljednje validacije   |

Ocene kvaliteta se dinamički prilagođavaju:

- **Neuspjeli zahtjevi** smanjiti rezultat za 10 poena
- **Rezultat pada na ≤ 10** → proxy je označen `inactive`
- Neaktivni proksiji su isključeni iz rotacije

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

### Prekidač

1proxy sync ima ugrađeni prekidač:

- Poslije** 5 uzastopnih grešaka u sinhronizaciji** , daljnji pokušaji sinhronizacije su blokirani
- Resetujte sa: `resetOneproxyCircuitBreaker()` ili ponovo pokrenite server
- Status sinhronizacije je dostupan na `GET /api/settings/oneproxy?action=status`

### Brisanje 1proxy proksija

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-Detection & Stealth

OmniRoute ne usmjerava samo promet kroz proxy — već čini da promet izgleda legitimno:

### TLS Prevara otiska prsta

Koristi `wreq-js` za generiranje TLS otisaka prstiju poput pretraživača, zaobilazeći sisteme za detekciju botova koji označavaju TLS rukovanje koje nije pretraživač.

### CLI Uparivanje otiska prsta

The**CLI Prebacivanje otiska prsta** (`Settings → Security`) preuređuje HTTP zaglavlja i JSON polja tijela kako bi odgovarali tačnom potpisu izvornih CLI binarnih datoteka (Claude kod, Codex, itd.). Ovo radi** na vrhu** proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Dobijate oboje**IP masking** i** zatražiti autentičnost** istovremeno.

### Proxy IP Preservation

Značke označene bojama na kontrolnoj tabli pokazuju koji je proxy nivo aktivan:

| Značka | Nivo      | Značenje                                       |
| ------ | --------- | ---------------------------------------------- |
| 🟢     | Global    | Sav promet ide kroz ovaj proxy                 |
| 🟡     | Provajder | Samo promet ovog provajdera je proksi          |
| 🔵     | Veza      | Ovaj specifični key/account koristi ovaj proxy |

Značka također prikazuje riješeni proxy IP za verifikaciju.

---

## Upstream Proxy Modes

Za provajdere koji koriste CLIProxyAPI obrazac, OmniRoute podržava tri upstream proxy načina:

| Mode          | Opis                                                            |
| ------------- | --------------------------------------------------------------- |
| `native`      | OmniRoute upravlja proxy usmjeravanjem direktno (podrazumevano) |
| `cliproxyapi` | Delegati na eksternu CLIProxyAPI instancu                       |
| `fallback`    | Prvo pokušava native, vraća se na CLIProxyAPI                   |

Konfigurirajte po provajderu:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Dashboard UI

### Postavke → Proxy Tab

- **Globalni proxy** konfiguracija (podesite jednom za sav promet)
- **Proxy po provajderu** nadjačava
- **Proxy po konekciji** zadaci
- **Test veze** preko konfigurisanog proxyja
- **Značke označene bojama** prikazuje aktivni proxy nivo

### Postavke → 1proxy Tab

- **Sync Now** dugme za preuzimanje besplatnih proksija
- **Statistike kartice** : Ukupno, Aktivno, Pros. kvalitet, Zadnja sinhronizacija
- **Filteri** : Protokol, kod zemlje, minimalni kvalitet
- **Proxy table** sa domaćinom, protokolom, državom, ocjenom kvalitete, kašnjenjem, anonimnošću, Google pristupom
- **Status sinhronizacije** panel sa success/failure praćenjem i brojanjem uzastopnih kvarova
- **Obriši sve** da uklonite sve 1proxy unose

---

## API Reference

### Proxy postavke API

| Metoda   | Krajnja tačka                                  | Opis                                 |
| -------- | ---------------------------------------------- | ------------------------------------ |
| `GET`    | `/api/settings/proxy`                          | Preuzmite punu konfiguraciju proxyja |
| `GET`    | `/api/settings/proxy?level=global`             | Nabavite globalni proxy              |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Nabavite proxy provajdera            |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Riješite efektivni proxy             |
| `PUT`    | `/api/settings/proxy`                          | Ažurirajte proxy konfiguraciju       |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Uklonite proxy na nivou              |

### Proxy registar API

| Metoda   | Krajnja tačka                                     | Opis                         |
| -------- | ------------------------------------------------- | ---------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Navedite sve proksije        |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Nabavite proxy od ID         |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Dobijte proxy zadatke        |
| `POST`   | `/api/v1/management/proxies`                      | Kreirajte proxy              |
| `PATCH`  | `/api/v1/management/proxies`                      | Ažurirajte proxy             |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Izbriši proxy                |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Prisilno brisanje            |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Bulk assign                  |
| `GET`    | `/api/v1/management/proxies/assignments`          | Navedite zadatke             |
| `GET`    | `/api/v1/management/proxies/health`               | Proxy zdravstvene statistike |

### Tuneli API

Za izlaganje vaše OmniRoute instance javnom internetu (Cloudflare/ngrok/Tailscale) umjesto odlaznog rutiranja kroz proxy, pogledajte [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunel REST API živi pod `/api/tunnels/{cloudflared,ngrok,tailscale}/*` i ortogonan je na izlazni proxy lanac dokumentiran gore.

### 1proxy API

| Metoda   | Krajnja tačka                          | Opis                                       |
| -------- | -------------------------------------- | ------------------------------------------ |
| `GET`    | `/api/settings/oneproxy`               | Navedite 1proxy proxy                      |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Dobijte statistiku status sinhronizacije + |
| `GET`    | `/api/settings/oneproxy?action=status` | Dobijte samo status sinhronizacije         |
| `POST`   | `/api/settings/oneproxy`               | Sinhronizacija okidača                     |
| `POST`   | `/api/settings/oneproxy/rotate`        | Rotirajte na sljedeći proxy                |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Izbriši jednu                              |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Obriši sve                                 |

### Upstream Proxy API

| Metoda   | Krajnja tačka                     | Opis                                    |
| -------- | --------------------------------- | --------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Nabavite konfiguraciju upstream proxyja |
| `PUT`    | `/api/upstream-proxy/:providerId` | Postavite upstream proxy način rada     |
| `DELETE` | `/api/upstream-proxy/:providerId` | Uklonite upstream proxy konfiguraciju   |

---

## Varijable okruženja

| Varijabilna           | Default | Opis                                                             |
| --------------------- | ------- | ---------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`  | Omogući podršku za SOCKS5 proxy (zadani `true` u `.env.example`) |

---

## Rješavanje problema

### "SOCKS5 proxy je onemogućen"

Postavite `ENABLE_SOCKS5_PROXY=true` u svoju `.env` datoteku i ponovo pokrenite.

### "socket hang up" greške kroz proxy

Ovo je normalno sa jeftinim proksijima koji isključuju neaktivne veze. OmniRoute već rješava ovo na sljedeći način:

- Onemogućavanje održavanja na proxy vezama (`keepAliveTimeout: 1`)
- Onemogućavanje cjevovoda (`pipelining: 0`)
- Keširanje dispečera radi izbjegavanja ponovljenih rukovanja

Ako se nastavi, pokušajte s drugim proxyjem ili upotrijebite funkciju rotacije 1 proxy.

### "unsupported_country_region_territory" tokom OAuth

Provjerite je li proxy konfiguriran** prije** pokretanje OAuth toka. OmniRoute usmjerava OAuth razmjenu tokena kroz konfigurirani proxy. Prvo postavite globalni proxy ili proxy na nivou provajdera, a zatim se povežite.

### Proxy se ne koristi

Provjerite redoslijed rješavanja:

1. Potvrdite sa `GET /api/settings/proxy?resolve=your-connection-id`
2. Provjerite je li proxy `status` `active` (ne `inactive`)
3. Uvjerite se da opseg dodjele proxyja odgovara vašoj vezi

### 1proxy sinhronizacija nije uspjela

Provjerite status sinhronizacije:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Ako je `consecutiveFailures >= 5`, isključio se prekidač. Ponovo pokrenite server za resetovanje ili sačekajte ručno resetovanje.

---

## Šema baze podataka

### `proxy_registry` Table

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

### `proxy_assignments` Table

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

## Provjera ispravnosti proxyja (v3.8.16 +)

OmniRoute's** proxy brzi neuspjeh** mehanizam (`src/lib/proxyHealth.ts`) otkriva mrtve proxy servere u < 2s putem brze provjere TCP veze, a zatim** kešira rezultat** kako bi se izbjegla dodatna opterećenja po zahtjevu.

### Kako radi

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

Bez ovoga, mrtvi proxy bi blokirao svaki zahtjev za puni `PROXY_TIMEOUT_MS` (podrazumevano 30s) prije nego što ne uspije.

### Podesive varijable okruženja

| Varijabilna                  | Default | Svrha                                                   |
| ---------------------------- | ------- | ------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | TCP vremensko ograničenje veze po zdravstvenoj provjeri |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | Koliko dugo se zdravstveni rezultat sprema              |

**Preporučene vrijednosti:**

| Scenario                    | Fast-fail timeout | Cache TTL | Reasoning                                                                                |
| --------------------------- | ----------------- | --------- | ---------------------------------------------------------------------------------------- |
| Visoko propusni API gateway | 1500ms            | 60000ms   | Agresivni brzi, duži keš za smanjenje provjera                                           |
| Geo-distribuirani čvorovi   | 3000ms            | 15000ms   | Sporijim mrežama je potrebno više vremena; kraća keš memorija za brzi prelazak na grešku |
| Dev / testiranje            | 1000ms            | 10000ms   | Brza iteracija na lokalnim proksijima                                                    |
| Stealth / anti-detekcija    | 2500ms            | 45000ms   | Izbjegavajte brzo ispitivanje koje bi moglo pokrenuti ograničenja brzine                 |

### Provjera zdravlja proxyja

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Oznaka `stale` je `true` kada je unos u keš memoriju premašio `HEALTH_CACHE_TTL_MS` i sljedeći zahtjev će pokrenuti novu provjeru.

### Zadane postavke tipa po proksiju

Provjera zdravlja koristi razumne zadane postavke na osnovu URL šeme:

| Šema                       | Zadani port |
| -------------------------- | ----------- |
| `http://`                  | 8080        |
| `https://`                 | 443         |
| `socks5://` / `socks5h://` | 1080        |

Prilagođeni portovi u URL (`http://host:9999`) uvijek imaju prednost u odnosu na zadanu šemu.

---

## Analitika proxyja i uočljivost

OmniRoute prati upotrebu po proxy serveru kako bi pomogao operaterima da dijagnosticiraju obrasce rutiranja, skokove kašnjenja i ponavljajuće greške.

### Šta se prati

Za svaki zahtjev preko konfiguriranog proxyja, OmniRoute bilježi:

| Metric       | Opis                                                               |
| ------------ | ------------------------------------------------------------------ |
| `proxy_url`  | Potpuni proxy URL (sa maskiranim vjerodajnicama)                   |
| `provider`   | Upstream provajder ID (openai, anthropic, itd.)                    |
| `latency_ms` | Ukupno vrijeme povratnog puta uključujući rukovanje proxy serverom |
| `connect_ms` | samo vrijeme povezivanja TCP                                       |
| `status`     | HTTP statusni kod od uzvodno                                       |
| `error`      | Klasa greške ako zahtjev nije uspio                                |
| `timestamp`  | ISO 8601 UTC                                                       |

### Pristup podacima

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Prava krajnja tačka je `/api/usage/proxy-logs` (vidi `src/app/api/usage/proxy-logs/route.ts`). Ova krajnja tačka podržava:

- `GET /api/usage/proxy-logs` — preuzima proxy logove
- `DELETE /api/usage/proxy-logs` — obrišite sve proxy dnevnike

Agregatne statistike mogu se tražiti direktno iz `proxy_logs` tablice preko SQL ako je potrebno. Kontrolna tabla UI može ponuditi zbirne prikaze.

### Common Patterns

**Otkrijte proxy koji se kreće** (naizmenično između success/failure):

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

**Pronađite spore proxy servere** (latencija p95 > 2s):

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

## Stablo odlučivanja o strategiji rotacije

Kada je više proksija dodijeljeno opsegu, OmniRoute koristi a** strategija rotacije** da odaberete koju ćete koristiti za svaki zahtjev. Strategija je konfigurisana na nivou opsega (globalno, po provajderu, po nalogu, po kombinaciji).

### Dostupne strategije

| Strategija         | Kada koristiti                                  | Kompromis                                                                    |
| ------------------ | ----------------------------------------------- | ---------------------------------------------------------------------------- |
| `quality` (zadano) | Proizvodnja s proksijima mješovitog kvaliteta   | Favorizira proksije visoke ocjene; mogu izgladnjivati one sa niskim ocjenama |
| `random`           | Distribucija opterećenja, privatnost            | Ravnomjerna distribucija; ignoriše signale kvaliteta                         |
| `sequential`       | Otklanjanje grešaka, determinističko testiranje | Ciklusi kroz proxy po redu; lako rasuđivati                                  |

### Decision Tree

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

## Automatsko isključivanje grešaka za vaše vlastite proksije

1proxy marketplace pool već sam automatski degradira neuspjele proxy servere (pogledajte [ocjene kvaliteta proxy servera](#proxy-quality-scores) ). Za punomoćnike** ti** dodan u registar, planer zdravlja u pozadini (`src/lib/proxyHealth/scheduler.ts`) pruža isto ponašanje "automatski isključi mrtvog člana iz lanca", bez brisanja bilo čega:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Kako se uklapa u multi-proxy lanac:

1. Planer ispituje svaki registrovani proxy svaki `PROXY_HEALTH_INTERVAL_MS` (podrazumevano 10 min; minimalno 1 min).
2. Nakon `PROXY_AUTO_REMOVE_AFTER` uzastopno** konačan** kvarovi (stvarni neuspjeh veze — a timeout ili vlastiti 5xx ciljne sonde se nikada ne računa, pogledajte [Provjera zdravlja proksija](#proxy-health-checking-v3816) ), `status` proxyja je postavljen na `dead`.
3. `dead` je jedan od statusa koji filter statusa uživo koji koristi pool/rotation rezolucija isključuje, tako da rotacija opsega (round-robin / random / sticky / latency — vidi [Stablo strategije rotacije](#rotation-strategy-decision-tree) ) odmah prestaje da predaje taj proxy novim zahtjevima. Nije pogođen nijedan drugi proksi u grupi, a cijeli bazen se nikada ne vraća tiho na direktnu vezu — pogledajte [4-nivo proxy sistem](#4-level-proxy-system) koji se zatvara od greške.
4. Planer nastavlja da ispituje `dead` proksije u istom intervalu. Sljedeća uspješna sonda okreće `status` natrag na `active` i ponovo ulazi u rotaciju — nije potrebno ručno ponovno dodavanje.

Ovo je namerno** opt-in i nedestruktivni** : prema zadanim postavkama planer samo broji i evidentira greške (pogledajte politiku C u `decision.ts`), a `PROXY_AUTO_DISABLE` nikada ne briše red — čemu služi posebna, agresivnija `PROXY_AUTO_REMOVE` zastavica. Ako su oba postavljena na `true`, `PROXY_AUTO_REMOVE` pobjeđuje (proxy koji će biti obrisan nema koristi za soft-disable između). Pogledajte referencu [Environment Config](../reference/ENVIRONMENT.md) za punu listu varijabli.

---

> 📖** Povezana dokumentacija:**
>
> - [Korisnički vodič](../guides/USER_GUIDE.md) — Opće postavke i konfiguracija - [API Referenca](../reference/API_REFERENCE.md) — Kompletna API dokumentacija - [Konfiguracija okruženja](../reference/ENVIRONMENT.md) — Sve varijable okruženja
