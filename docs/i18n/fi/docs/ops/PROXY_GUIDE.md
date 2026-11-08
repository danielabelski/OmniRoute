# 🌐 OmniRoute Proxy Guide (Suomi)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Ohita maantieteelliset lohkot, suojaa henkilöllisyytesi ja reititä AI -liikenne minkä tahansa — välityspalvelimen kautta ilman monimutkaisuutta.**

OmniRoute sisältää täysin varustetun välityspalvelinhallintajärjestelmän, jonka avulla voit reitittää ylävirran AI palveluntarjoajan liikennettä HTTP, HTTPS tai SOCKS5 välityspalvelinten kautta. Oletpa sitten estetyllä alueella, tarvitset IP kiertoa tai haluat salata sormenjäljet — tämä opas kattaa kaiken.

---

## Sisällysluettelo

- [Miksi käyttää välityspalvelimia?](#why-use-proxies)
- [Arkkitehtuurin yleiskatsaus](#architecture-overview)
- [4-tason välityspalvelinjärjestelmä](#4-level-proxy-system)
- [Välityspalvelinrekisteri (CRUD)](#proxy-registry-crud)
- [1 välityspalvelin ilmainen markkinapaikka](#1proxy-free-proxy-marketplace)
- [Välityspalvelimen kierto](#proxy-rotation)
- [Havaitsemisen esto & Stealth](#anti-detection--stealth)
- [Ylävirran välityspalvelintilat](#upstream-proxy-modes)
- [Kojelauta UI](#dashboard-ui)
- [API Viite](#api-reference)
- [Ympäristömuuttujat](#environment-variables)
- [Vianetsintä](#troubleshooting)

---

## Miksi käyttää välityspalvelimia?

Monet AI palveluntarjoajat rajoittavat pääsyä maantieteellisen alueen mukaan. Kehittäjät sisään** Venäjä, Kiina, Iran, Kuuba, Turkki** ja muut maat kohtaavat virheitä, kuten:

```
unsupported_country_region_territory
```

Välityspalvelimet ovat hyödyllisiä myös estettyjen alueiden ulkopuolella:

| Käytä Case                  | Kuvaus                                                      |
| --------------------------- | ----------------------------------------------------------- |
| **Maantieteellinen ohitus** | Pääsy OpenAI, Anthropic, Codex, Copilot estetyistä maista   |
| **IP kierto**               | Jaa pyynnöt usealle IPs välttääksesi nopeuden rajoittamisen |
| **Yksityisyys**             | Piilota todellinen IP alkupään palveluntarjoajilta          |
| **Vaatimustenmukaisuus**    | Ohjaa liikenne tiettyjen lainkäyttöalueiden kautta          |
| **Testaus**                 | Simuloi pyyntöjä eri alueilta                               |

---

## Arkkitehtuurin yleiskatsaus

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

### Tärkeimmät komponentit

| Komponentti                     | Tiedosto                                     | Rooli                                                   |
| ------------------------------- | -------------------------------------------- | ------------------------------------------------------- |
| **Välityspalvelimen rekisteri** | `src/lib/db/proxies.ts`                      | CRUD välityspalvelinmerkinnöille + -laajuusmääritykset  |
| **Välityspalvelin Dispatcher**  | `open-sse/utils/proxyDispatcher.ts`          | Luo `undici` ProxyAgent/SOCKS -välittäjiä välimuistilla |
| **Välityspalvelimen haku**      | `open-sse/utils/proxyFetch.ts`               | Kääri `fetch()` välityspalvelimella                     |
| **Asetukset Reitti**            | `src/app/api/settings/proxy/route.ts`        | Vanha välityspalvelimen määritys API (GET/PUT/DELETE)   |
| **Hallintoreitti**              | `src/app/api/v1/management/proxies/route.ts` | Rekisteri CRUD API (GET/POST/PATCH/DELETE)              |
| **1 välityspalvelin DB**        | `src/lib/db/oneproxy.ts`                     | Ilmainen välityspalvelinmarkkinoiden pysyvyys           |

---

## Uusien tilien oletusvälityspalvelimen tila

sisään** Asetukset → Välityspalvelin → Yleiset asetukset** , käytä** Ota välityspalvelin oletuksena käyttöön uusille yhteyksille** valitaksesi uusien palveluntarjoajatilien alkuperäisen välityspalvelimen tilan.

Uusi asetus hallitsee äskettäin lisättyjen palveluntarjoajatilien alkuperäistä välityspalvelintilaa. Se ei muuta olemassa olevia tilejä tai korvaa yleistä välityspalvelinkytkintä. Sen alkuarvo säilyttää aiemman käyttäytymisen. Poista se käytöstä kerran, jos haluat luoda tulevia tilejä, joissa välityspalvelin on oletuksena pois käytöstä.

Asetus tallennetaan nimellä `defaultNewConnectionProxyEnabled` olemassa olevien asetusten API kautta. Se on oletuksena `true`, kun sitä ei koskaan tallennettu. `false` tallentaminen tulee voimaan seuraavissa uusissa tileissä ilman uudelleenkäynnistystä. `POST /api/providers` hyväksyy valinnaisen tiukan loogisen `proxyEnabled`; eksplisiittinen `true` tai `false` on etusijalla luomisoletusarvoon nähden. Päällekkäisen tilin puuttuminen tai OAuth reconnect säilyttää tilin tallennetun tilan. Yksittäiset tilit voidaan edelleen ottaa käyttöön tai poistaa käytöstä myöhemmin.

Valikoidut palveluntarjoajan siirrot käyttävät kohdeasennuksen oletusasetusta uusille tileille ja säilyttävät kohdekäytännön, kun nykyiset tilit korvataan. Välityspalvelimen kytkimet eivät ole siirrettäviä siirtokenttiä. Täysi varmuuskopion palautus ja historiallinen JSON/SQL -siirto säilyttävät nykyisen palautussemantiikkansa, mukaan lukien tallennetut tiliarvot ja vanhat skeeman oletusasetukset; täydellinen asetusten palautus voi myös palauttaa tämän asetuksen.

Tämä asetus ei määritä välityspalvelinta tai vahvista, että se on terve tai käytössä. Todellinen reititys riippuu edelleen yleisestä välityspalvelimen kytkimestä ja soveltuvista välityspalvelimen määrityksistä. Synteettiset palveluntarjoajat, joilla ei ole pysyvää tiliä, OAuth -liikenne ennen tilin luomista, environment/system -välityspalvelimet ja ulkoisten taustajärjestelmien verkot eivät kuulu sen soveltamisalaan.

## 4-tason välityspalvelinjärjestelmä

OmniRoute tukee välityspalvelimen määritystä osoitteessa** neljä itsenäistä kiikaritähtää** , ratkaistaan tärkeysjärjestyksessä:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Miten resoluutio toimii

Kun OmniRoute lähettää pyynnön ylävirran toimittajalle, se soittaa `resolveProxyForConnectionFromRegistry()`, joka tarkistaa jokaisen tason järjestyksessä:

1. **Tilitason** — Onko tälle tietylle yhteydelle ID määritetty välityspalvelin?
2. **Palveluntarjoajataso** — Onko tälle palveluntarjoajalle määritetty välityspalvelin (esim. `openai`)?
3. **Globaali taso** — Onko globaali välityspalvelin määritetty?
4. **Ei välityspalvelinta** — Suora yhteys palveluntarjoajaan.

Ensimmäinen ottelu voittaa. Tämä tarkoittaa, että voit asettaa globaalin välityspalvelimen varavaihtoehdoksi, mutta ohittaa sen tietyille palveluntarjoajille tai yhteyksille.

### Mitä välitetään

| Liikennetyyppi       | Välityspalvelin? | Huomautuksia                                       |
| -------------------- | ---------------- | -------------------------------------------------- |
| Chatin valmistuminen | ✅               | Kaikki `/v1/chat/completions` -pyynnöt             |
| Upotukset            | ✅               | `/v1/embeddings`                                   |
| Kuvan luominen       | ✅               | `/v1/images/generations`                           |
| Ääni (TTS/STT)       | ✅               | `/v1/audio/*`                                      |
| OAuth tokenin vaihto | ✅               | Ratkaisee `unsupported_country_region_territory`   |
| Yhteystestit         | ✅               | "Testaa yhteys" -painike käyttää välityspalvelinta |
| Tokenin päivitys     | ✅               | Tausta OAuth uusiminen                             |
| Mallin synkronointi  | ✅               | Mallien luettelointi ja löytäminen                 |

---

## Välityspalvelinrekisteri (CRUD)

Välityspalvelinrekisteri on SQLite taulukko (`proxy_registry`), joka tallentaa kaikki välityspalvelimesi. Jokaisella välityspalvelimella on:

| Ala        | Tyyppi       | Kuvaus                                  |
| ---------- | ------------ | --------------------------------------- |
| `id`       | UUID         | Ainutlaatuinen tunniste                 |
| `name`     | merkkijono   | Ihmisen luettava etiketti               |
| `type`     | merkkijono   | Protokolla: `http`, `https`, `socks5`   |
| `host`     | merkkijono   | Välityspalvelimen isäntänimi tai IP     |
| `port`     | Kokonaisluku | Portin numero                           |
| `username` | merkkijono   | Todennus käyttäjänimi (salattu levossa) |
| `password` | merkkijono   | Auth salasana (salattu levossa)         |
| `region`   | merkkijono   | Maantieteellisen alueen tunniste        |
| `notes`    | merkkijono   | Vapaatekstiset muistiinpanot            |
| `status`   | merkkijono   | `active` tai `inactive`                 |
| `source`   | merkkijono   | `manual` tai `oneproxy`                 |

### Välityspalvelimen luominen

**Kojelaudan kautta:**

1. Siirry osoitteeseen** Asetukset → Proxy**
2. Napsauta** Lisää välityspalvelin**
3. Täytä tyyppi, isäntä, portti ja valinnaiset todennustiedot
4. Tallentaa

**API kautta:**

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

### Välityspalvelimen päivittäminen

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Huomautus:** Tunnukset säilytetään, ellet nimenomaisesti lähetä ei-tyhjiä korvauksia. Tyhjien merkkijonojen lähettäminen `username`/`password` säilyttää tallennetut arvot.

### Välityspalvelimen poistaminen

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Listauksen välityspalvelimet

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Välityspalvelinten määrittäminen laajuuksille

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

### Tehokkaan välityspalvelimen ratkaiseminen

Tarkista, mitä välityspalvelinta käytettäisiin tietylle yhteydelle:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Palauttaa ratkaistun välityspalvelimen tason (`account`, `provider` tai `global`) ja lähteen kanssa.

### Joukkotehtävä

Määritä yksi välityspalvelin useille palveluntarjoajille tai yhteyksille kerralla:

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

Välityspalvelimet sisältyvät**Backup/Restore** järjestelmä. Kun viet OmniRoute kokoonpanosi:

1. Siirry osoitteeseen** Kojelauta → Asetukset → Varmuuskopio**
2. Napsauta** Viedä** — -välityspalvelinrekisteri ja tehtävät sisältyvät
3. Palauta napsauttamalla** Tuoda** ja lataa varmuuskopiotiedosto

Välityspalvelinrekisteri tukee myös** isäntä + portti** — jos tuot välityspalvelimen, joka on jo olemassa (sama isäntä ja portti), se päivittyy kaksoiskappaleen luomisen sijaan.

### Vanha siirto

Jos määritit välityspalvelimet vanhemmassa versiossa (esirekisteri), OmniRoute siirtää ne automaattisesti:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Tämä tapahtuu kerran ensimmäisellä käynnistyksellä päivityksen jälkeen. Käytä `migrateLegacyProxyConfigToRegistry({ force: true })` suorittaaksesi uudelleen.

---

## 1proxy Ilmainen välityspalvelinmarkkinapaikka

> 🆕** Kirjoittaja [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (ongelma [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integroituu** [1 välityspalvelin](https://1proxy-api.aitradepulse.com)** yhteisön alusta, johon pääsy on mahdollista** satoja ilmaisia, vahvistettuja välityspalvelimia** ympäri maailmaa. Tämä on täydellinen käyttäjille, joilla ei ole omaa välityspalvelininfrastruktuuria.

### Miten se toimii

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Synkronoi** — OmniRoute hakee vahvistetut välityspalvelimet 1-välityspalvelimelta API
2. **Store** — Välityspalvelimet tallennetaan samaan `proxy_registry` taulukkoon `source = 'oneproxy'` kanssa
3. **Suodattaa** — Suodata protokollan, maan tai laatupisteiden mukaan
4. **Kiertää** — Valitse paras välityspalvelin käyttämällä laatu-, satunnaisia tai peräkkäisiä strategioita
5. **Automaattinen hajoaminen** — Epäonnistuneiden välityspalvelinten laatupisteitä alennetaan; kynnyksen alapuolella → merkitty ei-aktiiviseksi

### Välityspalvelinten synkronointi

**Kojelaudan kautta:**

1. Siirry osoitteeseen** Asetukset → 1proxy** -välilehti
2. Napsauta** "Synkronoi nyt"**
3. Näytä tilastot: välityspalvelimet yhteensä, aktiivisten määrä, keskimääräinen laatu, erittely maittain

**API kautta:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Välityspalvelinten suodatus

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

### Välityspalvelimen laatupisteet

Jokaisen 1-välityspalvelimen mukana tulee metatiedot:

| Ala             | Kuvaus                                          |
| --------------- | ----------------------------------------------- |
| `qualityScore`  | 0-100 arvio 1 välityspalvelimen vahvistuksesta  |
| `latencyMs`     | Mitattu verkon latenssi                         |
| `anonymity`     | `transparent`, `anonymous` tai `elite`          |
| `googleAccess`  | Voiko välityspalvelin käyttää Google palveluita |
| `countryCode`   | Kaksikirjaiminen ISO -maakoodi                  |
| `lastValidated` | Viimeisimmän vahvistuksen aikaleima             |

Laatupisteitä säädetään dynaamisesti:

- **Epäonnistuneita pyyntöjä** pienentää pisteitä 10 pisteellä
- **Pisteet putoavat ≤ 10:een** → välityspalvelin on merkitty `inactive`
- Ei-aktiiviset välityspalvelimet jätetään kiertämisen ulkopuolelle

### Kiertostrategiat

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

### Katkaisija

1-välityspalvelimen synkronoinnissa on sisäänrakennettu katkaisija:

- Jälkeen** 5 peräkkäistä synkronointivirhettä** , lisäsynkronointiyritykset estetään
- Nollaa komennolla: `resetOneproxyCircuitBreaker()` tai käynnistä palvelin uudelleen
- Synkronoinnin tila on saatavilla osoitteessa `GET /api/settings/oneproxy?action=status`

### 1 välityspalvelimen välityspalvelinten tyhjentäminen

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Havaitsemisen esto & Stealth

OmniRoute ei vain ohjaa liikennettä välityspalvelimen — kautta, vaan saa liikenteen näyttämään lailliselta:

### TLS Sormenjälkihuijaus

Käyttää `wreq-js` luomaan selaimen kaltaisia TLS sormenjälkiä ohittaen bottien tunnistusjärjestelmät, jotka merkitsevät muiden kuin selaimen TLS kättelyjä.

### CLI Sormenjälkien täsmäys

The**CLI Sormenjälkikytkin** (`Settings → Security`) järjestää HTTP otsikot ja JSON -tekstikentät uudelleen vastaamaan alkuperäisten CLI binäärien (Claude koodi, Codex jne.) tarkkaa allekirjoitusta. Tämä toimii** päälle** välityspalvelin:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Saat molemmat**IP maskaus** ja** pyytää aitoutta** samanaikaisesti.

### Välityspalvelin IP Säilytys

Kojelaudan värikoodatut merkit osoittavat, mikä välityspalvelintaso on aktiivinen:

| Kunniamerkki | Taso              | Merkitys                                               |
| ------------ | ----------------- | ------------------------------------------------------ |
| 🟢           | Maailmanlaajuinen | Kaikki liikenne kulkee tämän välityspalvelimen kautta  |
| 🟡           | Palveluntarjoaja  | Vain tämän palveluntarjoajan liikenne välitetään       |
| 🔵           | Yhteys            | Tämä tietty key/account käyttää tätä välityspalvelinta |

Merkissä näkyy myös ratkaistu välityspalvelin IP vahvistusta varten.

---

## Ylävirran välityspalvelintilat

Palveluntarjoajille, jotka käyttävät CLIProxyAPI -mallia, OmniRoute tukee kolmea ylävirran välityspalvelintilaa:

| tila          | Kuvaus                                                              |
| ------------- | ------------------------------------------------------------------- |
| `native`      | OmniRoute käsittelee välityspalvelimen reitityksen suoraan (oletus) |
| `cliproxyapi` | Delegoi ulkoiseen CLIProxyAPI instanssiin                           |
| `fallback`    | Yrittää ensin alkuperäistä, palaa takaisin CLIProxyAPI              |

Määritä palveluntarjoajakohtaisesti:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Kojelauta UI

### Asetukset → Välityspalvelin-välilehti

- **Globaali välityspalvelin** määritykset (asetetaan kerran kaikelle liikenteelle)
- **Palveluntarjoajakohtainen välityspalvelin** ohittaa
- **Yhteyskohtainen välityspalvelin** tehtäviä
- **Yhteystesti** määritetyn välityspalvelimen kautta
- **Värikoodatut merkit** näyttää aktiivisen välityspalvelimen tason

### Asetukset → 1proxy Tab

- **Synkronoi nyt** -painiketta ilmaisten välityspalvelinten hakemiseksi
- **Tilastot kortit** : Yhteensä, aktiivinen, keskimääräinen laatu, viimeinen synkronointi
- **Suodattimet** : Protokolla, maakoodi, vähimmäislaatu
- **Välityspalvelintaulukko** isäntä, protokolla, maa, laatupisteet, latenssi, nimettömyys, Google -käyttö
- **Synkronoinnin tila** paneeli, jossa on success/failure -seuranta ja peräkkäisten vikojen määrä
- **Tyhjennä kaikki** poistaaksesi kaikki 1 välityspalvelinmerkinnät

---

## API Viite

### Välityspalvelimen asetukset API

| Menetelmä | Päätepiste                                     | Kuvaus                                   |
| --------- | ---------------------------------------------- | ---------------------------------------- |
| `GET`     | `/api/settings/proxy`                          | Hanki täysi välityspalvelimen kokoonpano |
| `GET`     | `/api/settings/proxy?level=global`             | Hanki globaali välityspalvelin           |
| `GET`     | `/api/settings/proxy?level=provider&id=openai` | Hanki palveluntarjoajan välityspalvelin  |
| `GET`     | `/api/settings/proxy?resolve=connectionId`     | Ratkaise tehokas välityspalvelin         |
| `PUT`     | `/api/settings/proxy`                          | Päivitä välityspalvelimen asetukset      |
| `DELETE`  | `/api/settings/proxy?level=provider&id=openai` | Poista välityspalvelin tasolta           |

### Välityspalvelinrekisteri API

| Menetelmä | Päätepiste                                        | Kuvaus                            |
| --------- | ------------------------------------------------- | --------------------------------- |
| `GET`     | `/api/v1/management/proxies`                      | Listaa kaikki välityspalvelimet   |
| `GET`     | `/api/v1/management/proxies?id=uuid`              | Hanki välityspalvelin ID          |
| `GET`     | `/api/v1/management/proxies?id=uuid&where_used=1` | Hanki välityspalvelintehtäviä     |
| `POST`    | `/api/v1/management/proxies`                      | Luo välityspalvelin               |
| `PATCH`   | `/api/v1/management/proxies`                      | Päivitä välityspalvelin           |
| `DELETE`  | `/api/v1/management/proxies?id=uuid`              | Poista välityspalvelin            |
| `DELETE`  | `/api/v1/management/proxies?id=uuid&force=1`      | Pakota poistaminen                |
| `POST`    | `/api/v1/management/proxies/bulk-assign`          | Joukkomääräys                     |
| `GET`     | `/api/v1/management/proxies/assignments`          | Listaa tehtävät                   |
| `GET`     | `/api/v1/management/proxies/health`               | Välityspalvelimen terveystilastot |

### Tunnelit API

Lisätietoja OmniRoute -ilmentymän paljastamisesta julkiselle Internetille (Cloudflare/ngrok/Tailscale) välityspalvelimen kautta lähtevän lähteen reitittämisen sijaan on kohdassa [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunneli REST API sijaitsee `/api/tunnels/{cloudflared,ngrok,tailscale}/*` alla ja on ortogonaalinen edellä dokumentoituun lähtevän välityspalvelimen ketjuun nähden.

### 1 välityspalvelin API

| Menetelmä | Päätepiste                             | Kuvaus                               |
| --------- | -------------------------------------- | ------------------------------------ |
| `GET`     | `/api/settings/oneproxy`               | Listaa 1 välityspalvelinta           |
| `GET`     | `/api/settings/oneproxy?action=stats`  | Hae tilastot + synkronoinnin tila    |
| `GET`     | `/api/settings/oneproxy?action=status` | Hae vain synkronoinnin tila          |
| `POST`    | `/api/settings/oneproxy`               | Triggerin synkronointi               |
| `POST`    | `/api/settings/oneproxy/rotate`        | Kierrä seuraavaan välityspalvelimeen |
| `DELETE`  | `/api/settings/oneproxy?id=uuid`       | Poista yksi                          |
| `DELETE`  | `/api/settings/oneproxy?clearAll=1`    | Tyhjennä kaikki                      |

### Ylävirran välityspalvelin API

| Menetelmä | Päätepiste                        | Kuvaus                                           |
| --------- | --------------------------------- | ------------------------------------------------ |
| `GET`     | `/api/upstream-proxy/:providerId` | Hanki ylävirran välityspalvelimen asetukset      |
| `PUT`     | `/api/upstream-proxy/:providerId` | Aseta ylävirran välityspalvelintila              |
| `DELETE`  | `/api/upstream-proxy/:providerId` | Poista ylävirran välityspalvelimen konfiguraatio |

---

## Ympäristömuuttujat

| Muuttuva              | Oletus | Kuvaus                                                                         |
| --------------------- | ------ | ------------------------------------------------------------------------------ |
| `ENABLE_SOCKS5_PROXY` | `true` | Ota SOCKS5 -välityspalvelimen tuki käyttöön (oletus `true` `.env.example`:ssä) |

---

## Vianetsintä

### "SOCKS5 -välityspalvelin on poistettu käytöstä"

Aseta `ENABLE_SOCKS5_PROXY=true` `.env` -tiedostoosi ja käynnistä uudelleen.

### "socket hang up" -virheet välityspalvelimen kautta

Tämä on normaalia halvoilla välityspalvelimilla, jotka katkaisevat tyhjäkäynnit. OmniRoute hoitaa tämän jo:

- Välityspalvelinyhteyksien säilymisen poistaminen käytöstä (`keepAliveTimeout: 1`)
- Liukujohdotuksen poistaminen käytöstä (`pipelining: 0`)
- Välittäjät välimuistiin toistuvien kättelyjen välttämiseksi

Jos se jatkuu, kokeile toista välityspalvelinta tai käytä 1-välityspalvelimen kiertotoimintoa.

### "unsupported_country_region_territory" OAuth aikana

Varmista, että välityspalvelin on määritetty** ennen** käynnistää OAuth virran. OmniRoute reitittää OAuth -merkkien vaihdon määritetyn välityspalvelimen kautta. Aseta ensin maailmanlaajuinen tai palveluntarjoajatason välityspalvelin ja muodosta sitten yhteys.

### Välityspalvelinta ei käytetä

Tarkista resoluutiojärjestys:

1. Tarkista `GET /api/settings/proxy?resolve=your-connection-id`
2. Tarkista, onko välityspalvelin `status` `active` (ei `inactive`)
3. Varmista, että välityspalvelimen määritysalue vastaa yhteyttäsi

### 1 välityspalvelimen synkronointi epäonnistui

Tarkista synkronoinnin tila:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Jos `consecutiveFailures >= 5`, katkaisija on lauennut. Käynnistä palvelin uudelleen nollataksesi tai odota manuaalista nollausta.

---

## Tietokantakaavio

### `proxy_registry`

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

### `proxy_assignments`

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

## Välityspalvelimen kuntotarkastus (v3.8.16 +)

OmniRoute's** välityspalvelin nopea epäonnistuminen** mekanismi (`src/lib/proxyHealth.ts`) havaitsee kuolleet välityspalvelimet < 2s:ssä nopean TCP yhteystarkistuksen avulla, sitten** tallentaa tuloksen välimuistiin** pyyntökohtaisten yleiskustannusten välttämiseksi.

### Miten se toimii

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

Ilman tätä kuollut välityspalvelin estäisi kaikki pyynnöt täydelle `PROXY_TIMEOUT_MS` (oletus 30s) ennen epäonnistumista.

### Viritettävät ympäristömuuttujat

| Muuttuva                     | Oletus  | Tarkoitus                                          |
| ---------------------------- | ------- | -------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | TCP yhteyden aikakatkaisu terveystarkastusta kohti |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | Kuinka kauan terveystulos on välimuistissa         |

**Suositellut arvot:**

| Skenaario                            | Nopea epäonnistumisen aikakatkaisu | Välimuisti TTL | Päättely                                                                                 |
| ------------------------------------ | ---------------------------------- | -------------- | ---------------------------------------------------------------------------------------- |
| Tehokas API -yhdyskäytävä            | 1500 ms                            | 60 000 ms      | Aggressiivinen vikanopea, pidempi välimuisti vähentää tarkistuksia                       |
| Maantieteellisesti hajautetut solmut | 3000 ms                            | 15 000 ms      | Hitaammat verkot tarvitsevat enemmän aikaa; lyhyempi välimuisti nopeaa vikasietoa varten |
| Kehittäjä / testaus                  | 1000 ms                            | 10 000 ms      | Nopea iterointi paikallisilla välityspalvelimilla                                        |
| Stealth / anti-detection             | 2500 ms                            | 45 000 ms      | Vältä nopeaa mittausta, joka voi laukaista nopeusrajoja                                  |

### Välityspalvelimen kunnon tarkastaminen

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

`stale` lippu on `true`, kun välimuistin merkintä on ylittänyt `HEALTH_CACHE_TTL_MS` ja seuraava pyyntö käynnistää uuden tarkistuksen.

### Välityspalvelimen tyypin oletukset

Terveystarkastuksessa käytetään järkeviä oletusarvoja URL mallin perusteella:

| Kaavio                     | Oletusportti |
| -------------------------- | ------------ |
| `http://`                  | 8080         |
| `https://`                 | 443          |
| `socks5://` / `socks5h://` | 1080         |

Mukautetut portit URL ssa (`http://host:9999`) ovat aina etusijalla järjestelmän oletusarvoon nähden.

---

## Välityspalvelinanalyysi ja havainnointi

OmniRoute seuraa välityspalvelinkohtaista käyttöä auttaakseen operaattoreita diagnosoimaan reititysmallit, latenssipiikit ja toistuvat viat.

### Mitä seurataan

Jokaiselle määritetyn välityspalvelimen kautta lähetetylle pyynnölle OmniRoute tallentaa:

| Metrinen     | Kuvaus                                                                    |
| ------------ | ------------------------------------------------------------------------- |
| `proxy_url`  | Täysi välityspalvelin URL (todennuskirjautumistiedot peitettynä)          |
| `provider`   | Ylävirran toimittaja ID (openai, antrooppinen jne.)                       |
| `latency_ms` | Edestakaisen matkan kokonaisaika, mukaan lukien välityspalvelimen kättely |
| `connect_ms` | TCP vain yhteysaika                                                       |
| `status`     | HTTP tilakoodi alkupäästä                                                 |
| `error`      | Virheluokka, jos pyyntö epäonnistui                                       |
| `timestamp`  | ISO 8601 UTC                                                              |

### Tietojen käyttö

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Todellinen päätepiste on `/api/usage/proxy-logs` (katso `src/app/api/usage/proxy-logs/route.ts`). Tämä päätepiste tukee:

- `GET /api/usage/proxy-logs` — noutaa välityspalvelimen lokit
- `DELETE /api/usage/proxy-logs` — tyhjennä kaikki välityspalvelimen lokit

Aggregaattitilastoja voi tarvittaessa kysyä suoraan `proxy_logs` taulukosta SQL kautta. Kojelauta UI voi tarjota yhdistettyjä näkymiä.

### Yleiset mallit

**Tunnista heiluva välityspalvelin** (vaihtelee success/failure):

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

**Etsi hitaita välityspalvelimia** (p95 latenssi > 2s):

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

## Kiertostrategian päätöspuu

Kun alueelle on määritetty useita välityspalvelimia, OmniRoute käyttää a** kiertostrategia** valita, kumpaa käytetään kuhunkin pyyntöön. Strategia määritetään laajuustasolla (maailmanlaajuinen, palveluntarjoajakohtainen, tilikohtainen, yhdistelmä).

### Käytettävissä olevat strategiat

| strategia          | Milloin käyttää                                   | Kompromissi                                                                  |
| ------------------ | ------------------------------------------------- | ---------------------------------------------------------------------------- |
| `quality` (oletus) | Tuotanto sekalaatuisten välityspalvelinten kanssa | Suosii korkealuokkaisia välityspalvelimia; voivat nääntyä matalapalkkaisille |
| `random`           | Kuormanjako, yksityisyys                          | Tasainen jakelu; jättää huomioimatta laatusignaalit                          |
| `sequential`       | Virheenkorjaus, deterministinen testaus           | Kiertää välityspalvelinten läpi järjestyksessä; helppo perustella            |

### Päätöspuu

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

## Omien välityspalvelinten automaattinen epäonnistumisen poissulkeminen

1proxy-markkinapaikan pooli heikentää jo automaattisesti epäonnistuneet välityspalvelimet (katso [Välityspalvelimen laatupisteet](#proxy-quality-scores) ). Välityspalvelimet** sinä** Rekisteriin lisätty taustaterveysajastin (`src/lib/proxyHealth/scheduler.ts`) tarjoaa saman "sulje pois kuollut jäsen ketjusta automaattisesti" -toiminnon poistamatta mitään:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Kuinka se sopii usean välityspalvelimen ketjuun:

1. Ajastin tutkii jokaisen rekisteröidyn välityspalvelimen joka `PROXY_HEALTH_INTERVAL_MS` (oletus 10 min; vähintään 1 min).
2. `PROXY_AUTO_REMOVE_AFTER` jälkeen peräkkäin** ratkaiseva** epäonnistumisia (todellinen yhteysvirhe — aikakatkaisu tai mittauskohteen oma 5xx ei koskaan laske, katso [Välityspalvelimen kunnon tarkistus](#proxy-health-checking-v3816) ), välityspalvelimen `status` on `dead`.
3. `dead` on yksi niistä tiloista, jotka pool/rotation -resoluution käyttämä alive-status-suodatin sulkee pois, joten laajuuden kierto (round-robin / random / sticky / latency — katso [Rotation Strategy Decision Tree](#rotation-strategy-decision-tree) ) lopettaa välittömästi välityspalvelimen luovuttamisen uusille pyynnöille. Tämä ei vaikuta muihin altaan välityspalvelimiin, eikä koko pooli koskaan palaa takaisin suoralle yhteydelle — katso [4-tason välityspalvelinjärjestelmän](#4-level-proxy-system) vikasuljettu suoja.
4. Ajastin tutkii `dead` välityspalvelimia samalla aikavälillä. Seuraava onnistunut anturi kääntää `status` takaisin `active` ksi ja se palaa kiertoon — manuaalista lisäystä ei vaadita.

Tämä on tarkoituksella** opt-in ja tuhoamaton** : oletusarvoisesti ajastin laskee ja kirjaa vain virheitä (katso käytäntö C kohdassa `decision.ts`), ja `PROXY_AUTO_DISABLE` ei koskaan poista riviä — jota varten erillinen, aggressiivisempi `PROXY_AUTO_REMOVE` lippu on tarkoitettu. Jos molemmat on asetettu arvoon `true`, `PROXY_AUTO_REMOVE` voittaa (poistettavissa olevalla välityspalvelimella ei ole käyttöä pehmeälle poistolle välissä). Katso koko muuttujaluettelo kohdasta [Environment Config](../reference/ENVIRONMENT.md).

---

> 📖** Asiaan liittyvä dokumentaatio:**
>
> - [Käyttöopas](../guides/USER_GUIDE.md) — Yleiset asetukset ja konfigurointi - [API Viite](../reference/API_REFERENCE.md) — Täydellinen API -dokumentaatio - [Environment Config](../reference/ENVIRONMENT.md) — Kaikki ympäristömuuttujat
