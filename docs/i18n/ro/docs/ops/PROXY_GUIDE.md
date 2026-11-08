# 🌐 OmniRoute Proxy Guide (Română)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Ocoliți blocurile geografice, protejați-vă identitatea și direcționați traficul AI prin orice proxy — cu complexitate de configurare zero.**

OmniRoute include un sistem de gestionare a proxy complet care vă permite să direcționați traficul furnizorului AI în amonte prin proxy HTTP, HTTPS sau SOCKS5. Indiferent dacă vă aflați într-o regiune blocată, aveți nevoie de rotație IP sau doriți amprenta ascunsă — acest ghid acoperă totul.

---

## Cuprins

- [De ce să folosiți proxy?](#why-use-proxies)
- [Privire de ansamblu asupra arhitecturii](#architecture-overview)
- [Sistem proxy pe 4 niveluri](#4-level-proxy-system)
- [Registrul proxy (CRUD)](#proxy-registry-crud)
- [1 piață gratuită de proxy](#1proxy-free-proxy-marketplace)
- [Rotație proxy](#proxy-rotation)
- [Anti-Detecție și Stealth](#anti-detection--stealth)
- [Moduri proxy în amonte](#upstream-proxy-modes)
- [Tabloul de bord UI](#dashboard-ui)
- [API Referință](#api-reference)
- [Variabile de mediu](#environment-variables)
- [Depanare](#troubleshooting)

---

## De ce să folosiți proxy?

Mulți furnizori AI restricționează accesul în funcție de regiune geografică. Dezvoltatorii în** Rusia, China, Iran, Cuba, Turcia** și alte țări întâmpină erori precum:

```
unsupported_country_region_territory
```

Chiar și în afara regiunilor blocate, proxy-urile sunt utile pentru:

| Caz de utilizare       | Descriere                                                            |
| ---------------------- | -------------------------------------------------------------------- |
| **Ocolire geografică** | Accesați OpenAI, Anthropic, Codex, Copilot din țările blocate        |
| **IP rotație**         | Distribuiți cererile în mai multe IPs pentru a evita limitarea ratei |
| **Confidențialitate**  | Ascundeți IP dvs. real de la furnizorii din amonte                   |
| **Conformitate**       | Dirijați traficul prin jurisdicții specifice                         |
| **Testare**            | Simulați cereri din diferite regiuni                                 |

---

## Privire de ansamblu asupra arhitecturii

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

### Componente cheie

| Componentă             | Fişier                                       | Rol                                                  |
| ---------------------- | -------------------------------------------- | ---------------------------------------------------- |
| **Registrul proxy**    | `src/lib/db/proxies.ts`                      | CRUD pentru intrările proxy atribuirea domeniului +  |
| **Dispecer proxy**     | `open-sse/utils/proxyDispatcher.ts`          | Creează dispeceri `undici` ProxyAgent/SOCKS cu cache |
| **Preluare proxy**     | `open-sse/utils/proxyFetch.ts`               | Înfășoară `fetch()` cu injecție de dispecer proxy    |
| **Setări Rută**        | `src/app/api/settings/proxy/route.ts`        | Configurație proxy moștenită API (GET/PUT/DELETE)    |
| **Ruta de management** | `src/app/api/v1/management/proxies/route.ts` | Registry CRUD API (GET/POST/PATCH/DELETE)            |
| **1 proxy DB**         | `src/lib/db/oneproxy.ts`                     | Persistență gratuită pe piața de proxy               |

---

## Starea proxy implicită pentru conturile noi

În** Setări → Proxy → Configurare globală** , folosiți** Activați proxy în mod implicit pentru conexiuni noi** pentru a alege starea proxy inițială a conturilor de furnizor nou adăugate.

Noua setare controlează starea proxy inițială a conturilor de furnizor nou adăugate. Nu modifică conturile existente și nu înlocuiește comutatorul proxy global. Valoarea sa inițială păstrează comportamentul anterior. Dezactivați-l o dată pentru a crea conturi viitoare cu proxy dezactivat în mod prestabilit.

Preferința este stocată ca `defaultNewConnectionProxyEnabled` prin setările existente API. Este implicit la `true` când nu este salvat niciodată. Salvarea `false` intră în vigoare pentru conturile noi ulterioare fără repornire. `POST /api/providers` acceptă un `proxyEnabled` boolean strict opțional; un `true` sau `false` explicit are prioritate față de valoarea implicită de creare. Omiterea unui cont duplicat sau reconectarea OAuth păstrează starea stocată a contului respectiv. Conturile individuale pot fi activate sau dezactivate ulterior.

Transferurile selective de furnizori folosesc configurația implicită a instalării de destinație pentru conturile noi și păstrează politica de destinație atunci când înlocuiesc conturile existente. Comutarile proxy nu sunt câmpuri de transfer portabile. Restaurarea completă de rezervă și migrarea istorică JSON/SQL își păstrează semantica de restaurare existentă, inclusiv valorile contului salvat și valorile implicite ale schemei moștenite; o restaurare completă a setărilor poate restabili și această preferință.

Această preferință nu atribuie un proxy și nu stabilește că unul este sănătos sau în uz. Rutarea reală depinde în continuare de comutatorul proxy global și de configurația proxy aplicabilă. Furnizorii sintetici fără un cont persistent, traficul OAuth înainte de crearea contului, proxy-urile environment/system și rețelele backend-urilor externe sunt în afara domeniului său de aplicare.

## Sistem proxy pe 4 niveluri

OmniRoute acceptă configurarea proxy la** patru domenii independente** , rezolvate in ordinea prioritatilor:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Cum funcționează rezoluția

Când OmniRoute trimite o solicitare către un furnizor din amonte, apelează `resolveProxyForConnectionFromRegistry()` care verifică fiecare nivel în ordine:

1. **La nivel de cont** — Există un proxy alocat acestei conexiuni specifice ID?
2. **La nivel de furnizor** — Există un proxy alocat acestui furnizor (de exemplu, `openai`)?
3. **La nivel global** — Există un proxy global configurat?
4. **Fără proxy** — Conexiune directă cu furnizorul.

Primul meci câștigă. Aceasta înseamnă că puteți seta un proxy global ca alternativă, dar îl puteți înlocui pentru anumiți furnizori sau conexiuni.

### Ce devine proxy

| Tip de trafic           | Proxy? | Note                                           |
| ----------------------- | ------ | ---------------------------------------------- |
| Finalizări de chat      | ✅     | Toate cererile `/v1/chat/completions`          |
| Înglobări               | ✅     | `/v1/embeddings`                               |
| Generarea imaginii      | ✅     | `/v1/images/generations`                       |
| Audio (TTS/STT)         | ✅     | `/v1/audio/*`                                  |
| schimb de jetoane OAuth | ✅     | Rezolvă `unsupported_country_region_territory` |
| Teste de conectare      | ✅     | Butonul „Testează conexiunea” folosește proxy  |
| Reîmprospătare simbol   | ✅     | Reînnoire OAuth de fundal                      |
| Sincronizarea modelului | ✅     | Listarea modelelor și descoperirea             |

---

## Registrul proxy (CRUD)

Registrul proxy este un tabel SQLite (`proxy_registry`) care stochează toate proxy-urile dvs. Fiecare proxy are:

| Domeniu    | Tip    | Descriere                                               |
| ---------- | ------ | ------------------------------------------------------- |
| `id`       | UUID   | Identificator unic                                      |
| `name`     | Şir    | Etichetă care poate fi citită de om                     |
| `type`     | Şir    | Protocol: `http`, `https`, `socks5`                     |
| `host`     | Şir    | Nume de gazdă proxy sau IP                              |
| `port`     | Întreg | Numărul portului                                        |
| `username` | Şir    | Nume de utilizator de autentificare (criptat în repaus) |
| `password` | Şir    | Parola de autentificare (criptată în repaus)            |
| `region`   | Şir    | Etichetă de regiune geografică                          |
| `notes`    | Şir    | Note cu text liber                                      |
| `status`   | Şir    | `active` sau `inactive`                                 |
| `source`   | Şir    | `manual` sau `oneproxy`                                 |

### Crearea unui proxy

**Prin tabloul de bord:**

1. Du-te la** Setări → Proxy**
2. Clic** Adăugați proxy**
3. Completați tipul, gazda, portul și acreditările de autentificare opționale
4. Salva

**Prin API:**

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

### Actualizarea unui proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Nota:** Acreditările sunt păstrate, cu excepția cazului în care trimiteți în mod explicit înlocuitori care nu sunt goale. Trimiterea șirurilor goale pentru `username`/`password` va păstra valorile stocate.

### Ștergerea unui proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Listarea proxy-urilor

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Atribuirea proxy-urilor pentru domenii

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

### Rezolvarea proxy-ului eficient

Verificați ce proxy ar fi utilizat pentru o anumită conexiune:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Returnează proxy-ul rezolvat cu nivelul său (`account`, `provider` sau `global`) și sursa.

### Atribuire în bloc

Atribuiți un proxy mai multor furnizori sau conexiuni simultan:

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

Proxy-urile sunt incluse în**Backup/Restore** sistem. Când exportați configurația OmniRoute :

1. Du-te la** Tabloul de bord → Setări → Backup**
2. Clic** Export** Registrul proxy — și atribuțiile sunt incluse
3. Pentru a restabili, faceți clic** Import** și încărcați fișierul de rezervă

Registrul proxy acceptă, de asemenea** upsert de portul gazdă +** — dacă importați un proxy care există deja (aceeași gazdă și același port), acesta se actualizează în loc să creeze un duplicat.

### Migrație moștenită

Dacă ați configurat proxy-uri într-o versiune mai veche (pre-registry), OmniRoute le migrează automat:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Acest lucru se întâmplă o dată la prima pornire după upgrade. Folosiți `migrateLegacyProxyConfigToRegistry({ force: true })` pentru a rula din nou.

---

## 1 piață proxy gratuită

> 🆕** Contribuție de [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Problema [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute se integrează cu** [1 proxy](https://1proxy-api.aitradepulse.com)** platformă comunitară pentru a oferi acces la** sute de proxy-uri gratuite, validate** din întreaga lume. Acest lucru este perfect pentru utilizatorii care nu au propria infrastructură proxy.

### Cum funcționează

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sincronizare** — OmniRoute preia proxy-urile validate din 1proxy API
2. **Magazin** — Proxy-urile sunt salvate în același tabel `proxy_registry` cu `source = 'oneproxy'`
3. **Filtra** — Filtrați după protocol, țară, scor de calitate
4. **Roti** — Alegeți cel mai bun proxy folosind strategii de calitate, aleatorii sau secvenţiale
5. **Auto-degradare** — Proxy-urile eșuate își reduc scorul de calitate; sub pragul → marcat ca inactiv

### Sincronizarea proxy-urilor

**Prin tabloul de bord:**

1. Du-te la** Setări → 1proxy** fila
2. Clic** „Sincronizează acum”**
3. Vedeți statistici: total proxy, număr activ, calitate medie, defalcare în funcție de țară

**Prin API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtrarea proxy-urilor

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

### Scoruri de calitate proxy

Fiecare proxy 1 proxy vine cu metadate:

| Domeniu         | Descriere                                    |
| --------------- | -------------------------------------------- |
| `qualityScore`  | Evaluare 0-100 de la validarea 1proxy        |
| `latencyMs`     | Latența rețelei măsurată                     |
| `anonymity`     | `transparent`, `anonymous` sau `elite`       |
| `googleAccess`  | Dacă proxy-ul poate accesa serviciile Google |
| `countryCode`   | Cod de țară ISO din două litere              |
| `lastValidated` | Marca temporală a ultimei validări           |

Scorurile de calitate sunt ajustate dinamic:

- **Solicitări nereușite** reduce scorul cu 10 puncte
- **Scorul scade la ≤ 10** proxy → este marcat `inactive`
- Proxy-urile inactive sunt excluse din rotație

### Strategii de rotație

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

### Întrerupător

Sincronizarea 1proxy are un întrerupător de circuit încorporat:

- După** 5 erori consecutive de sincronizare** , încercările ulterioare de sincronizare sunt blocate
- Resetați cu: `resetOneproxyCircuitBreaker()` sau reporniți serverul
- Starea de sincronizare este disponibilă la `GET /api/settings/oneproxy?action=status`

### Ștergerea 1 proxy-uri

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-Detecție și Stealth

OmniRoute nu direcționează doar traficul printr-un proxy — ci face ca traficul să pară legitim:

### TLS Fingerprint Spoofing

Utilizează `wreq-js` pentru a genera amprente TLS asemănătoare browserului, ocolind sistemele de detectare a botului care semnalează strângeri de mână TLS non-browser.

### CLI Potrivirea amprentei

The**CLI Comutare amprentă digitală** (`Settings → Security`) reordonează anteturile HTTP și câmpurile de corp JSON pentru a se potrivi cu semnătura exactă a binarelor CLI native ( Cod Claude, Codex etc.). Acest lucru funcționează** deasupra** proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Le primești pe amândouă**IP mascare** şi** cere autenticitate** simultan.

### Proxy IP Conservare

Insignele cu coduri de culoare din tabloul de bord arată ce nivel de proxy este activ:

| Insigna | Nivel     | Sens                                             |
| ------- | --------- | ------------------------------------------------ |
| 🟢      | Global    | Tot traficul trece prin acest proxy              |
| 🟡      | Furnizor  | Numai traficul acestui furnizor este proxy       |
| 🔵      | Conexiune | Acest key/account specific folosește acest proxy |

Insigna arată, de asemenea, proxy-ul IP rezolvat pentru verificare.

---

## Moduri proxy în amonte

Pentru furnizorii care folosesc modelul CLIProxyAPI, OmniRoute acceptă trei moduri proxy în amonte:

| Modul         | Descriere                                             |
| ------------- | ----------------------------------------------------- |
| `native`      | OmniRoute gestionează direct rutarea proxy (implicit) |
| `cliproxyapi` | Delegați la o instanță CLIProxyAPI externă            |
| `fallback`    | Încearcă mai întâi nativ, se întoarce la CLIProxyAPI  |

Configurați pentru fiecare furnizor:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Tabloul de bord UI

### Setări → Proxy

- **Proxy global** configurație (setată o dată pentru tot traficul)
- **Proxy pentru fiecare furnizor** suprascrie
- **Proxy per conexiune** sarcinile
- **Test de conectare** prin proxy configurat
- **Ecusoane cu coduri de culori** care arată nivelul proxy activ

### Setări → 1Proxy Tab

- **Sincronizează acum** butonul pentru a prelua proxy-uri gratuite
- **Cărți cu statistici** : Total, Activ, Calitate medie, Ultima sincronizare
- **Filtre** : Protocol, Cod de țară, Calitate min
- **Tabel proxy** cu gazdă, protocol, țară, scor de calitate, latență, anonimat, acces Google
- **Starea de sincronizare** panou cu urmărire success/failure și număr de erori consecutive
- **Ștergeți tot** pentru a elimina toate intrările 1proxy

---

## API Referință

### Setări proxy API

| Metodă   | Punct final                                    | Descriere                            |
| -------- | ---------------------------------------------- | ------------------------------------ |
| `GET`    | `/api/settings/proxy`                          | Obțineți configurația proxy completă |
| `GET`    | `/api/settings/proxy?level=global`             | Obțineți proxy global                |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Obțineți proxy de furnizor           |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Rezolvați proxy eficient             |
| `PUT`    | `/api/settings/proxy`                          | Actualizați configurația proxy       |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Eliminați proxy la nivel             |

### Registrul proxy API

| Metodă   | Punct final                                       | Descriere                    |
| -------- | ------------------------------------------------- | ---------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Listați toți proxy-urile     |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Obțineți proxy prin ID       |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Obțineți sarcini proxy       |
| `POST`   | `/api/v1/management/proxies`                      | Creați proxy                 |
| `PATCH`  | `/api/v1/management/proxies`                      | Actualizați proxy            |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Ștergeți proxy               |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Ștergerea forțată            |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Atribuire în bloc            |
| `GET`    | `/api/v1/management/proxies/assignments`          | Listează sarcinile           |
| `GET`    | `/api/v1/management/proxies/health`               | Statistici de sănătate proxy |

### Tuneluri API

Pentru a vă expune instanța OmniRoute la internetul public (Cloudflare/ngrok/Tailscale) în loc de rutare de ieșire printr-un proxy, consultați [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunelul REST API trăiește sub `/api/tunnels/{cloudflared,ngrok,tailscale}/*` și este ortogonal cu lanțul proxy de ieșire documentat mai sus.

### 1 proxy API

| Metodă   | Punct final                            | Descriere                                    |
| -------- | -------------------------------------- | -------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Listați 1 proxy proxy                        |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Obțineți starea de sincronizare + statistici |
| `GET`    | `/api/settings/oneproxy?action=status` | Obțineți doar starea de sincronizare         |
| `POST`   | `/api/settings/oneproxy`               | Declanșează sincronizarea                    |
| `POST`   | `/api/settings/oneproxy/rotate`        | Rotiți la următorul proxy                    |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Șterge unul                                  |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Ștergeți totul                               |

### Upstream Proxy API

| Metodă   | Punct final                       | Descriere                               |
| -------- | --------------------------------- | --------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Obțineți configurația proxy în amonte   |
| `PUT`    | `/api/upstream-proxy/:providerId` | Setați modul proxy în amonte            |
| `DELETE` | `/api/upstream-proxy/:providerId` | Eliminați configurația proxy din amonte |

---

## Variabile de mediu

| Variabilă             | Implicit | Descriere                                                          |
| --------------------- | -------- | ------------------------------------------------------------------ |
| `ENABLE_SOCKS5_PROXY` | `true`   | Activați suportul proxy SOCKS5 (implicit `true` în `.env.example`) |

---

## Depanare

### „Proxy-ul SOCKS5 este dezactivat”

Setați `ENABLE_SOCKS5_PROXY=true` în fișierul dvs. `.env` și reporniți.

### erori "socket hang up" prin proxy

Acest lucru este normal în cazul proxy-urilor ieftine care renunță la conexiunile inactive. OmniRoute se ocupă deja de acest lucru prin:

- Dezactivarea menținerii în viață pe conexiunile proxy (`keepAliveTimeout: 1`)
- Dezactivarea conductei (`pipelining: 0`)
- Memorarea în cache a dispecerilor pentru a evita strângerile repetate de mână

Dacă persistă, încercați un alt proxy sau utilizați funcția de rotație 1proxy.

### „unsupported_country_region_territory” în timpul OAuth

Asigurați-vă că proxy-ul este configurat** înainte** pornind fluxul OAuth. OmniRoute direcționează schimbul de token OAuth prin proxy-ul configurat. Setați mai întâi un proxy global sau la nivel de furnizor, apoi conectați-vă.

### Proxy nu este folosit

Verificați ordinea de rezoluție:

1. Verificați cu `GET /api/settings/proxy?resolve=your-connection-id`
2. Verificați dacă proxy-ul `status` este `active` (nu `inactive`)
3. Asigurați-vă că domeniul de atribuire a proxy-ului se potrivește conexiunii dvs

### 1 sincronizare proxy eșuată

Verificați starea de sincronizare:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Dacă `consecutiveFailures >= 5`, întrerupătorul s-a declanșat. Reporniți serverul pentru resetare sau așteptați resetarea manuală.

---

## Schema bazei de date

### `proxy_registry` Masa

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

### `proxy_assignments` Masa

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

## Verificarea sănătății proxy (v3.8.16 +)

OmniRoute lui** proxy fast-fail** mecanismul (`src/lib/proxyHealth.ts`) detectează proxy-urile nefuncționale în < 2s printr-o verificare rapidă a conexiunii TCP, apoi** memorează în cache rezultatul** pentru a evita cheltuielile generale pentru fiecare cerere.

### Cum funcționează

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

Fără aceasta, un proxy mort ar bloca fiecare cerere pentru `PROXY_TIMEOUT_MS` complet (30 de secunde implicit) înainte de a eșua.

### Variabile de mediu reglabile

| Variabilă                    | Implicit | Scop                                                            |
| ---------------------------- | -------- | --------------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`   | TCP timeout pentru conexiune per verificarea stării de sănătate |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`  | Cât timp este stocat în cache un rezultat de sănătate           |

**Valori recomandate:**

| Scenariu                  | Timeout pentru eșec rapid | Cache TTL | Raţionament                                                                           |
| ------------------------- | ------------------------- | --------- | ------------------------------------------------------------------------------------- |
| Gateway API de mare debit | 1500 ms                   | 60000 ms  | Cache agresivă, rapidă, mai lungă pentru a reduce verificările                        |
| Noduri geo-distribuite    | 3000 ms                   | 15000 ms  | Rețelele mai lente au nevoie de mai mult timp; cache mai scurtă pentru failover rapid |
| Dezvoltare / testare      | 1000 ms                   | 10000 ms  | Iterație rapidă pe proxy-uri locale                                                   |
| Stealth / anti-detecție   | 2500 ms                   | 45000 ms  | Evitați sondarea rapidă care ar putea declanșa limite de viteză                       |

### Inspectarea sănătății proxy

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Indicatorul `stale` este `true` atunci când intrarea în cache a depășit `HEALTH_CACHE_TTL_MS` și următoarea solicitare va declanșa o nouă verificare.

### Valori implicite pentru tipul de proxy

Verificarea sănătății folosește valori implicite sensibile bazate pe schema URL :

| Sistem                     | Port implicit |
| -------------------------- | ------------- |
| `http://`                  | 8080          |
| `https://`                 | 443           |
| `socks5://` / `socks5h://` | 1080          |

Porturile personalizate din URL (`http://host:9999`) au întotdeauna prioritate față de schema implicită.

---

## Analiză proxy și observabilitate

OmniRoute urmărește utilizarea per-proxy pentru a ajuta operatorii să diagnosticheze modelele de rutare, vârfurile de latență și eșecurile recurente.

### Ce este urmărit

Pentru fiecare solicitare printr-un proxy configurat, OmniRoute înregistrează:

| Metric       | Descriere                                                            |
| ------------ | -------------------------------------------------------------------- |
| `proxy_url`  | Proxy complet URL (cu acreditările de autentificare mascate)         |
| `provider`   | Furnizorul din amonte ID (openai, antropic etc.)                     |
| `latency_ms` | Timp total de călătorie dus-întors, inclusiv strângere de mână proxy |
| `connect_ms` | TCP numai timp de conectare                                          |
| `status`     | codul de stare HTTP din amonte                                       |
| `error`      | Clasa de eroare dacă cererea a eșuat                                 |
| `timestamp`  | ISO 8601 UTC                                                         |

### Accesarea Datelor

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Punctul final real este `/api/usage/proxy-logs` (vezi `src/app/api/usage/proxy-logs/route.ts`). Acest punct final acceptă:

- `GET /api/usage/proxy-logs` — preia jurnalele proxy
- `DELETE /api/usage/proxy-logs` — șterge toate jurnalele proxy

Statisticile agregate pot fi interogate direct din tabelul `proxy_logs` prin SQL dacă este necesar. Tabloul de bord UI poate oferi vizualizări agregate.

### Modele comune

**Detectați un proxy care se zbate** (alternează între success/failure):

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

**Găsiți proxy lente** (p95 latență > 2s):

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

## Arborele de decizie al strategiei de rotație

Când mai multe proxy sunt alocate unui domeniu, OmniRoute utilizează a** strategia de rotație** pentru a alege pe care să o utilizați pentru fiecare cerere. Strategia este configurată la nivel de domeniu (global, per-furnizor, per-cont, per-combo).

### Strategii disponibile

| Strategie            | Când să utilizați                           | Schimbul                                                                           |
| -------------------- | ------------------------------------------- | ---------------------------------------------------------------------------------- |
| `quality` (implicit) | Producție cu proxy de calitate mixtă        | Favorizează proxy-urile cu rating ridicat; îi pot înfometei pe cei cu cote scăzute |
| `random`             | Distribuția încărcăturii, confidențialitate | Distribuție uniformă; ignoră semnalele de calitate                                 |
| `sequential`         | Depanare, testare deterministă              | Ciclează prin proxy în ordine; ușor de raționat                                    |

### Arborele de decizie

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

## Excluderea automată a erorilor pentru propriile proxy

Grupul de piață de proxy 1 degradează deja automat proxy-urile eșuate pe cont propriu (consultați [Scorurile de calitate proxy](#proxy-quality-scores) ). Pentru proxy** tu** adăugat la registru, programatorul de sănătate de fundal (`src/lib/proxyHealth/scheduler.ts`) oferă același comportament „excluderea automată a unui membru mort din lanț”, fără a șterge nimic:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Cum se potrivește într-un lanț multi-proxy:

1. Planificatorul verifică fiecare proxy înregistrat la fiecare `PROXY_HEALTH_INTERVAL_MS` (implicit 10 min; minim 1 min).
2. Dupa `PROXY_AUTO_REMOVE_AFTER` consecutiv** concludentă** eșecuri (o defecțiune reală a conexiunii — un timeout sau propriul 5xx al țintei probei nu contează niciodată, consultați [Verificarea sănătății proxy](#proxy-health-checking-v3816) ), `status` al proxy-ului este setat la `dead`.
3. `dead` este una dintre stările pe care filtrul de stare activă utilizat de rezoluția pool/rotation le exclude, astfel încât rotația unui domeniu (round-robin / aleatoriu / sticky / latency — vezi [Arborele de decizie al strategiei de rotație](#rotation-strategy-decision-tree) ) încetează imediat să predea acel proxy noilor cereri. Niciun alt proxy din pool nu este afectat, iar întregul pool nu revine niciodată în tăcere la o conexiune directă — vezi [sistemul de proxy cu 4 niveluri](#4-level-proxy-system) de protecție închisă.
4. Programatorul continuă să verifice proxy-urile `dead` în același interval. Următoarea sondă de succes întoarce `status` înapoi la `active` și reintră în rotația — nu este necesară adăugarea manuală.

Acest lucru este în mod deliberat** opt-in și non-distructiv** : în mod implicit, planificatorul numără și înregistrează numai eșecurile (vezi politica C în `decision.ts`), iar `PROXY_AUTO_DISABLE` nu șterge niciodată un rând — pentru care este indicatorul separat, mai agresiv `PROXY_AUTO_REMOVE`. Dacă ambele sunt setate la `true`, `PROXY_AUTO_REMOVE` câștigă (un proxy pe cale de a fi șters nu are nici un folos pentru o dezactivare soft între ele). Consultați referința [Environment Config](../reference/ENVIRONMENT.md) pentru lista completă de variabile.

---

> 📖** Documentatie aferenta:**
>
> - [Ghidul utilizatorului](../guides/USER_GUIDE.md) — Configurare generală și configurare - [API Referință](../reference/API_REFERENCE.md) — Documentație completă API - [Environment Config](../reference/ENVIRONMENT.md) — Toate variabilele de mediu
