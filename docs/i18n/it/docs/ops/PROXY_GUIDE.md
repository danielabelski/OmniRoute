# 🌐 OmniRoute Proxy Guide (Italiano)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Bypassa i blocchi geografici, proteggi la tua identità e instrada il traffico AI attraverso qualsiasi proxy — con zero complessità di configurazione.**

OmniRoute include un sistema di gestione proxy completo che ti consente di instradare il traffico del provider AI upstream attraverso i proxy HTTP, HTTPS o SOCKS5. Se ti trovi in una regione bloccata, hai bisogno della rotazione IP o desideri un'impronta digitale invisibile — questa guida copre tutto.

---

## Sommario

- [Perché utilizzare i proxy?](#why-use-proxies)
- [Panoramica dell'architettura](#architecture-overview)
- [Sistema proxy a 4 livelli](#4-level-proxy-system)
- [Registro dei proxy (CRUD)](#proxy-registry-crud)
- [1mercato gratuito proxy](#1proxy-free-proxy-marketplace)
- [Rotazione per procura](#proxy-rotation)
- [Anti-rilevamento e azione furtiva](#anti-detection--stealth)
- [Modalità proxy upstream](#upstream-proxy-modes)
- [Cruscotto UI](#dashboard-ui)
- [API Riferimento](#api-reference)
- [Variabili d'ambiente](#environment-variables)
- [Risoluzione dei problemi](#troubleshooting)

---

## Perché utilizzare i proxy?

Molti fornitori AI limitano l’accesso in base alla regione geografica. Sviluppatori dentro** Russia, Cina, Iran, Cuba, Turchia** e altri paesi riscontrano errori come:

```
unsupported_country_region_territory
```

Anche al di fuori delle regioni bloccate, i proxy sono utili per:

| Caso d'uso            | Descrizione                                                              |
| --------------------- | ------------------------------------------------------------------------ |
| **Bypass geografico** | Accedi OpenAI, Anthropic, Codex, Copilot dai paesi bloccati              |
| **rotazione IP**      | Distribuisci le richieste su più IPs per evitare limitazioni di velocità |
| **Privacy**           | Nascondi il tuo vero IP dai fornitori a monte                            |
| **Conformità**        | Instradare il traffico attraverso giurisdizioni specifiche               |
| **Test**              | Simula richieste da diverse regioni                                      |

---

## Panoramica dell'architettura

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

### Componenti chiave

| Componente                | File                                         | Ruolo                                                                    |
| ------------------------- | -------------------------------------------- | ------------------------------------------------------------------------ |
| **Registro dei delegati** | `src/lib/db/proxies.ts`                      | CRUD per le voci proxy assegnazioni dell'ambito +                        |
| **Inviatore proxy**       | `open-sse/utils/proxyDispatcher.ts`          | Crea dispatcher `undici` ProxyAgent/SOCKS con memorizzazione nella cache |
| **Recupero proxy**        | `open-sse/utils/proxyFetch.ts`               | Avvolge `fetch()` con l'iniezione del dispatcher proxy                   |
| **Impostazioni Percorso** | `src/app/api/settings/proxy/route.ts`        | Configurazione proxy legacy API (GET/PUT/DELETE)                         |
| **Percorso di gestione**  | `src/app/api/v1/management/proxies/route.ts` | Registro di sistema CRUD API (GET/POST/PATCH/DELETE)                     |
| **1proxy DB**             | `src/lib/db/oneproxy.ts`                     | Persistenza del mercato proxy gratuito                                   |

---

## Stato proxy predefinito per i nuovi account

In** Impostazioni → Proxy → Configurazione globale** , utilizzo** Abilita il proxy per impostazione predefinita per le nuove connessioni** per scegliere lo stato proxy iniziale degli account fornitore appena aggiunti.

La nuova impostazione controlla lo stato proxy iniziale degli account provider appena aggiunti. Non modifica gli account esistenti né sostituisce il passaggio proxy globale. Il suo valore iniziale preserva il comportamento precedente. Disattivalo una volta per creare account futuri con proxy disabilitato per impostazione predefinita.

La preferenza viene memorizzata come `defaultNewConnectionProxyEnabled` tramite le Impostazioni API esistenti. Il valore predefinito è `true` quando non viene mai salvato. Il salvataggio `false` ha effetto per i nuovi account successivi senza riavvio. `POST /api/providers` accetta un booleano rigoroso opzionale `proxyEnabled`; uno `true` o `false` esplicito ha la precedenza sull'impostazione predefinita di creazione. L'omissione su un account duplicato o la riconnessione OAuth preserva lo stato memorizzato dell'account. I singoli account possono comunque essere abilitati o disabilitati in seguito.

I trasferimenti selettivi del provider utilizzano l'impostazione predefinita dell'installazione di destinazione per i nuovi account e preservano i criteri di destinazione quando si sostituiscono gli account esistenti. I commutatori proxy non sono campi di trasferimento portatili. Il ripristino completo del backup e la migrazione storica JSON/SQL mantengono la semantica di ripristino esistente, inclusi i valori dell'account salvati e le impostazioni predefinite dello schema legacy; anche un ripristino completo delle impostazioni può ripristinare questa preferenza.

Questa preferenza non assegna una delega né stabilisce che uno sia sano o in uso. Il routing effettivo dipende ancora dallo switch proxy globale e dalla configurazione proxy applicabile. I provider sintetici senza un account persistente, il traffico OAuth prima della creazione dell'account, i proxy environment/system e la rete di backend esterni non rientrano nel suo ambito.

## Sistema proxy a 4 livelli

OmniRoute supporta la configurazione proxy su** quattro ambiti indipendenti** , risolti in ordine di priorità:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Come funziona la risoluzione

Quando OmniRoute invia una richiesta a un provider upstream, chiama `resolveProxyForConnectionFromRegistry()` che controlla ogni livello in ordine:

1. **A livello di account** — Esiste un proxy assegnato a questa connessione specifica ID?
2. **A livello di fornitore** — Esiste un proxy assegnato a questo provider (ad esempio `openai`)?
3. **A livello globale** — È configurato un proxy globale?
4. **Nessuna delega** — Connessione diretta al provider.

Vince la prima partita. Ciò significa che puoi impostare un proxy globale come fallback ma sovrascriverlo per provider o connessioni specifici.

### Cosa viene proxy

| Tipo di traffico             | Procurato? | Note                                                 |
| ---------------------------- | ---------- | ---------------------------------------------------- |
| Completamenti della chat     | ✅         | Tutte le richieste `/v1/chat/completions`            |
| Incorporamenti               | ✅         | `/v1/embeddings`                                     |
| Generazione di immagini      | ✅         | `/v1/images/generations`                             |
| Audio (TTS/STT)              | ✅         | `/v1/audio/*`                                        |
| scambio di token OAuth       | ✅         | Risolve `unsupported_country_region_territory`       |
| Prove di connessione         | ✅         | Il pulsante "Verifica connessione" utilizza il proxy |
| Aggiornamento dei token      | ✅         | Rinnovamento dello sfondo OAuth                      |
| Sincronizzazione del modello | ✅         | Elenco e scoperta dei modelli                        |

---

## Registro dei proxy (CRUD)

Il registro dei proxy è una tabella SQLite (`proxy_registry`) che memorizza tutti i tuoi proxy. Ogni procura ha:

| Campo      | Tipo   | Descrizione                                         |
| ---------- | ------ | --------------------------------------------------- |
| `id`       | UUID   | Identificatore univoco                              |
| `name`     | Corda  | Etichetta leggibile dall'uomo                       |
| `type`     | Corda  | Protocollo: `http`, `https`, `socks5`               |
| `host`     | Corda  | Nome host proxy o IP                                |
| `port`     | Intero | Numero di porta                                     |
| `username` | Corda  | Nome utente autenticazione (crittografato a riposo) |
| `password` | Corda  | Password di autenticazione (crittografata a riposo) |
| `region`   | Corda  | Etichetta della regione geografica                  |
| `notes`    | Corda  | Note a testo libero                                 |
| `status`   | Corda  | `active` o `inactive`                               |
| `source`   | Corda  | `manual` o `oneproxy`                               |

### Creazione di un proxy

**Tramite dashboard:**

1. Vai a** Impostazioni → Proxy**
2. Clic** Aggiungi proxy**
3. Inserisci il tipo, l'host, la porta e le credenziali di autenticazione facoltative
4. Salva

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

### Aggiornamento di un proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Nota:** Le credenziali vengono conservate a meno che non si inviino esplicitamente sostituzioni non vuote. L'invio di stringhe vuote per `username`/`password` manterrà i valori memorizzati.

### Eliminazione di un proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Proxy di quotazione

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Assegnazione di proxy agli ambiti

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

### Risoluzione della delega effettiva

Controlla quale proxy verrebbe utilizzato per una determinata connessione:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Restituisce il proxy risolto con il suo livello (`account`, `provider` o `global`) e l'origine.

### Assegnazione in blocco

Assegna un proxy a più provider o connessioni contemporaneamente:

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

I proxy sono inclusi nel file**Backup/Restore** sistema. Quando esporti la configurazione OmniRoute :

1. Vai a** Dashboard → Impostazioni → Backup**
2. Clic** Esportare** Sono inclusi il registro e le assegnazioni del proxy —
3. Per ripristinare, fare clic su** Importare** e caricare il file di backup

Supporta anche il registro proxy** upsert dalla porta + dell'host** — se importi un proxy già esistente (stesso host e stessa porta), si aggiorna invece di creare un duplicato.

### Migrazione legacy

Se hai configurato i proxy in una versione precedente (pre-registro), OmniRoute li migra automaticamente:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Ciò accade una volta al primo avvio dopo l'aggiornamento. Usa `migrateLegacyProxyConfigToRegistry({ force: true })` per rieseguire.

---

## 1proxyMercato proxy gratuito

> 🆕** Contributo di [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Problema [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute si integra con il** [1 procura](https://1proxy-api.aitradepulse.com)** piattaforma comunitaria a cui fornire l'accesso** centinaia di proxy gratuiti e convalidati** da tutto il mondo. Questo è perfetto per gli utenti che non dispongono di una propria infrastruttura proxy.

### Come funziona

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sincronizzazione** — OmniRoute recupera i proxy convalidati dal 1proxy API
2. **Negozio** I proxy — vengono salvati nella stessa tabella `proxy_registry` con `source = 'oneproxy'`
3. **Filtro** — Filtra per protocollo, paese, punteggio di qualità
4. **Ruotare** — Scegli il proxy migliore utilizzando strategie di qualità, casuali o sequenziali
5. **Degradazione automatica** — I proxy falliti ottengono una riduzione del loro punteggio di qualità; sotto la soglia → contrassegnato come inattivo

### Sincronizzazione dei proxy

**Tramite dashboard:**

1. Vai a** Impostazioni → 1proxy** scheda
2. Clic** "Sincronizza ora"**
3. Visualizza le statistiche: proxy totali, conteggio attivo, qualità media, suddivisione per paese

**Via API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Proxy di filtraggio

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

### Punteggi di qualità proxy

Ogni proxy 1proxy viene fornito con metadati:

| Campo           | Descrizione                                |
| --------------- | ------------------------------------------ |
| `qualityScore`  | Valutazione 0-100 dalla convalida 1proxy   |
| `latencyMs`     | Latenza di rete misurata                   |
| `anonymity`     | `transparent`, `anonymous` o `elite`       |
| `googleAccess`  | Se il proxy può accedere ai servizi Google |
| `countryCode`   | Codice paese ISO di due lettere            |
| `lastValidated` | Timestamp dell'ultima convalida            |

I punteggi di qualità vengono adeguati dinamicamente:

- **Richieste non riuscite** ridurre il punteggio di 10 punti
- **Il punteggio scende a ≤ 10** Il proxy → è contrassegnato `inactive`
- I delegati inattivi sono esclusi dalla rotazione

### Strategie di rotazione

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

### Interruttore automatico

1proxy sync è dotato di un interruttore automatico integrato:

- Dopo** 5 errori di sincronizzazione consecutivi** , ulteriori tentativi di sincronizzazione verranno bloccati
- Reimposta con: `resetOneproxyCircuitBreaker()` o riavvia il server
- Lo stato di sincronizzazione è disponibile su `GET /api/settings/oneproxy?action=status`

### Cancellazione di 1 proxy proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-rilevamento e azione furtiva

OmniRoute non si limita a instradare il traffico attraverso un proxy — ma rende il traffico legittimo:

### TLS Spoofing delle impronte digitali

Utilizza `wreq-js` per generare impronte digitali TLS simili a browser, aggirando i sistemi di rilevamento dei bot che contrassegnano gli handshake TLS non browser.

### CLI Corrispondenza delle impronte digitali

IL**CLI Attiva/disattiva impronta digitale** (`Settings → Security`) riordina le intestazioni HTTP e i campi del corpo JSON in modo che corrispondano alla firma esatta dei binari CLI nativi (Claude Code, Codex, ecc.). Funziona** sopra** la procura:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Ottieni entrambi**IP mascheramento** E** richiedere l'autenticità** contemporaneamente.

### Conservazione del proxy IP

I badge con codice colore nella dashboard mostrano quale livello proxy è attivo:

| Distintivo | Livello     | Senso                                              |
| ---------- | ----------- | -------------------------------------------------- |
| 🟢         | Globale     | Tutto il traffico passa attraverso questo proxy    |
| 🟡         | Fornitore   | Solo il traffico di questo provider viene proxy    |
| 🔵         | Connessione | Questo specifico key/account utilizza questo proxy |

Il badge mostra anche il proxy IP risolto per la verifica.

---

## Modalità proxy upstream

Per i provider che utilizzano il modello CLIProxyAPI, OmniRoute supporta tre modalità proxy upstream:

| Modalità      | Descrizione                                                                 |
| ------------- | --------------------------------------------------------------------------- |
| `native`      | OmniRoute gestisce direttamente il routing proxy (impostazione predefinita) |
| `cliproxyapi` | Delegati a un'istanza CLIProxyAPI esterna                                   |
| `fallback`    | Prova prima il nativo, poi torna a CLIProxyAPI                              |

Configura per provider:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Cruscotto UI

### Impostazioni → Scheda Proxy

- **Procura globale** configurazione (impostata una volta per tutto il traffico)
- **Proxy per provider** sovrascrive
- **Proxy per connessione** incarichi
- **Prova di connessione** tramite proxy configurato
- **Badge con codice colore** mostrando il livello proxy attivo

### Impostazioni → 1proxy Scheda

- **Sincronizza ora** pulsante per recuperare proxy gratuiti
- **Carte statistiche** : Totale, Attivo, Qualità media, Ultima sincronizzazione
- **Filtri** : Protocollo, Codice Paese, Qualità min
- **Tabella delega** con host, protocollo, paese, punteggio di qualità, latenza, anonimato, accesso Google
- **Stato della sincronizzazione** pannello con tracciamento success/failure e conteggio dei guasti consecutivi
- **Cancella tutto** per rimuovere tutte le voci 1proxy

---

## API Riferimento

### Impostazioni proxy API

| Metodo   | Punto finale                                   | Descrizione                              |
| -------- | ---------------------------------------------- | ---------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Ottieni la configurazione proxy completa |
| `GET`    | `/api/settings/proxy?level=global`             | Ottieni proxy globale                    |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Ottieni il proxy del fornitore           |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Risolvere la delega effettiva            |
| `PUT`    | `/api/settings/proxy`                          | Aggiorna la configurazione del proxy     |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Rimuovi proxy a livello                  |

### Registro dei proxy API

| Metodo   | Punto finale                                      | Descrizione                    |
| -------- | ------------------------------------------------- | ------------------------------ |
| `GET`    | `/api/v1/management/proxies`                      | Elenca tutti i proxy           |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Ottieni proxy da ID            |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Ottieni incarichi di delega    |
| `POST`   | `/api/v1/management/proxies`                      | Crea procura                   |
| `PATCH`  | `/api/v1/management/proxies`                      | Aggiorna proxy                 |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Elimina proxy                  |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Forza l'eliminazione           |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Assegnazione in blocco         |
| `GET`    | `/api/v1/management/proxies/assignments`          | Elenca i compiti               |
| `GET`    | `/api/v1/management/proxies/health`               | Statistiche sulla salute proxy |

### Tunnel API

Per esporre la tua istanza OmniRoute all'Internet pubblica (Cloudflare/ngrok/Tailscale) invece di instradare in uscita tramite un proxy, consulta [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Il tunnel REST API si trova sotto `/api/tunnels/{cloudflared,ngrok,tailscale}/*` ed è ortogonale alla catena proxy in uscita documentata sopra.

### 1proxy API

| Metodo   | Punto finale                           | Descrizione                                           |
| -------- | -------------------------------------- | ----------------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Elenca 1 proxy proxy                                  |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Ottieni statistiche sullo stato di sincronizzazione + |
| `GET`    | `/api/settings/oneproxy?action=status` | Ottieni solo lo stato di sincronizzazione             |
| `POST`   | `/api/settings/oneproxy`               | Attiva la sincronizzazione                            |
| `POST`   | `/api/settings/oneproxy/rotate`        | Passa al proxy successivo                             |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Eliminane uno                                         |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Cancella tutto                                        |

### Proxy a monte API

| Metodo   | Punto finale                      | Descrizione                                  |
| -------- | --------------------------------- | -------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Ottieni la configurazione del proxy upstream |
| `PUT`    | `/api/upstream-proxy/:providerId` | Imposta la modalità proxy upstream           |
| `DELETE` | `/api/upstream-proxy/:providerId` | Rimuovi la configurazione del proxy upstream |

---

## Variabili d'ambiente

| Variabile             | Predefinito | Descrizione                                                              |
| --------------------- | ----------- | ------------------------------------------------------------------------ |
| `ENABLE_SOCKS5_PROXY` | `true`      | Abilita il supporto proxy SOCKS5 ( `true` predefinito in `.env.example`) |

---

## Risoluzione dei problemi

### "il proxy SOCKS5 è disabilitato"

Imposta `ENABLE_SOCKS5_PROXY=true` nel tuo file `.env` e riavvia.

### Errori di "socket hang up" tramite proxy

Questo è normale con proxy economici che interrompono le connessioni inattive. OmniRoute lo gestisce già:

- Disabilitare il keep-alive sulle connessioni proxy (`keepAliveTimeout: 1`)
- Disabilitazione del pipeline (`pipelining: 0`)
- Memorizzazione nella cache dei dispatcher per evitare strette di mano ripetute

Se il problema persiste, prova un proxy diverso o utilizza la funzione di rotazione 1proxy.

### "unsupported_country_region_territory" durante OAuth

Assicurati che il proxy sia configurato** Prima** avviare il flusso OAuth. OmniRoute instrada lo scambio di token OAuth attraverso il proxy configurato. Imposta prima un proxy globale o a livello di provider, quindi connettiti.

### Il proxy non viene utilizzato

Controlla l'ordine di risoluzione:

1. Verificare con `GET /api/settings/proxy?resolve=your-connection-id`
2. Controlla se il proxy `status` è `active` (non `inactive`)
3. Assicurati che l'ambito di assegnazione del proxy corrisponda alla tua connessione

### 1 sincronizzazione proxy non riuscita

Controlla lo stato della sincronizzazione:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Se `consecutiveFailures >= 5`, l'interruttore è scattato. Riavviare il server per eseguire il ripristino o attendere il ripristino manuale.

---

## Schema della banca dati

### `proxy_registry` Tabella

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

### `proxy_assignments` Tabella

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

## Controllo dello stato del proxy (v3.8.16 +)

OmniRoute's** proxy a fallimento rapido** il meccanismo (`src/lib/proxyHealth.ts`) rileva i proxy morti in < 2s tramite un rapido controllo della connessione TCP, quindi** memorizza il risultato nella cache** per evitare un sovraccarico per richiesta.

### Come funziona

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

Senza questo, un proxy morto bloccherebbe ogni richiesta per l'intero `PROXY_TIMEOUT_MS` (30 secondi predefiniti) prima di fallire.

### Variabili d'ambiente sintonizzabili

| Variabile                    | Predefinito | Scopo                                                                    |
| ---------------------------- | ----------- | ------------------------------------------------------------------------ |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`      | TCP timeout della connessione per controllo sanitario                    |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`     | Per quanto tempo un risultato di integrità viene memorizzato nella cache |

**Valori consigliati:**

| Scenario                       | Timeout di guasto rapido | Cache TTL | Ragionamento                                                                   |
| ------------------------------ | ------------------------ | --------- | ------------------------------------------------------------------------------ |
| Gateway API ad alto rendimento | 1500 ms                  | 60000 ms  | Fail-fast aggressivo, cache più lunga per ridurre i controlli                  |
| Nodi geodistribuiti            | 3000 ms                  | 15000 ms  | Le reti più lente richiedono più tempo; cache più breve per un failover rapido |
| Sviluppo/test                  | 1000ms                   | 10000 ms  | Iterazione rapida sui proxy locali                                             |
| Stealth/anti-rilevamento       | 2500 ms                  | 45000 ms  | Evitare sondaggi rapidi che potrebbero attivare limiti di frequenza            |

### Ispezione dell'integrità del proxy

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Il flag `stale` è `true` quando la voce della cache ha superato `HEALTH_CACHE_TTL_MS` e la richiesta successiva attiverà un nuovo controllo.

### Impostazioni predefinite per tipo proxy

Il controllo dello stato utilizza impostazioni predefinite sensate basate sullo schema URL :

| Schema                     | Porta predefinita |
| -------------------------- | ----------------- |
| `http://`                  | 8080              |
| `https://`                 | 443               |
| `socks5://` / `socks5h://` | 1080              |

Le porte personalizzate in URL (`http://host:9999`) hanno sempre la precedenza sullo schema predefinito.

---

## Analisi proxy e osservabilità

OmniRoute tiene traccia dell'utilizzo per proxy per aiutare gli operatori a diagnosticare modelli di routing, picchi di latenza ed errori ricorrenti.

### Cosa viene monitorato

Per ogni richiesta tramite proxy configurato, OmniRoute registra:

| Metrico      | Descrizione                                                       |
| ------------ | ----------------------------------------------------------------- |
| `proxy_url`  | Proxy completo URL (con credenziali di autenticazione mascherate) |
| `provider`   | Fornitore a monte ID (openai, antropico, ecc.)                    |
| `latency_ms` | Tempo totale di andata e ritorno incluso l'handshake proxy        |
| `connect_ms` | TCP connette solo il tempo                                        |
| `status`     | codice di stato HTTP da monte                                     |
| `error`      | Classe di errore se la richiesta non è riuscita                   |
| `timestamp`  | ISO 8601 UTC                                                      |

### Accesso ai dati

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Il vero punto finale è `/api/usage/proxy-logs` (vedi `src/app/api/usage/proxy-logs/route.ts`). Questo endpoint supporta:

- `GET /api/usage/proxy-logs` — recupera i log del proxy
- `DELETE /api/usage/proxy-logs` — cancella tutti i log del proxy

Se necessario, le statistiche aggregate possono essere interrogate direttamente dalla tabella `proxy_logs` tramite SQL. La dashboard UI può offrire visualizzazioni aggregate.

### Modelli comuni

**Rileva un proxy svolazzante** (alterna tra success/failure):

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

**Trova proxy lenti** (p95 latenza > 2s):

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

## Albero decisionale della strategia di rotazione

Quando più proxy vengono assegnati a un ambito, OmniRoute utilizza a** strategia di rotazione** per scegliere quale utilizzare per ogni richiesta. La strategia è configurata a livello di ambito (globale, per fornitore, per account, per combinazione).

### Strategie disponibili

| Strategia               | Quando usarlo                         | Scambio                                                                               |
| ----------------------- | ------------------------------------- | ------------------------------------------------------------------------------------- |
| `quality` (predefinito) | Produzione con proxy di qualità mista | Predilige proxy di alto rating; potrebbero far morire di fame quelli di basso livello |
| `random`                | Distribuzione del carico, privacy     | Distribuzione uniforme; ignora i segnali di qualità                                   |
| `sequential`            | Debug, test deterministici            | Scorre i proxy in ordine; facile ragionare                                            |

### Albero decisionale

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

## Esclusione automatica degli errori per i tuoi proxy

Il pool di marketplace 1proxy degrada già automaticamente i proxy non riusciti (vedi [Punteggi di qualità proxy](#proxy-quality-scores) ). Per i proxy** Voi** aggiunto al registro, lo scheduler dell'integrità in background (`src/lib/proxyHealth/scheduler.ts`) fornisce lo stesso comportamento "escludi automaticamente un membro morto dalla catena", senza eliminare nulla:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Come si inserisce in una catena multi-proxy:

1. Lo scheduler analizza ogni proxy registrato ogni `PROXY_HEALTH_INTERVAL_MS` (default 10 min; minimo 1 min).
2. Dopo `PROXY_AUTO_REMOVE_AFTER` consecutiva** conclusivo** in caso di errori (un vero errore di connessione — un timeout o il 5xx del target della sonda non conta mai, vedere [Controllo dello stato del proxy](#proxy-health-checking-v3816) ), `status` del proxy è impostato su `dead`.
3. `dead` è uno degli stati esclusi dal filtro dello stato vivo utilizzato dalla risoluzione pool/rotation, quindi la rotazione di un ambito (round robin / casuale / appiccicoso / latenza — vedere [Albero decisionale della strategia di rotazione](#rotation-strategy-decision-tree) ) interrompe immediatamente la consegna del proxy alle nuove richieste. Nessun altro proxy nel pool è interessato e l'intero pool non ricorre mai silenziosamente a una connessione diretta. — vedere la protezione a chiusura di errore [del sistema proxy a 4 livelli](#4-level-proxy-system).
4. Lo scheduler continua a sondare i proxy `dead` con lo stesso intervallo. La successiva sonda riuscita riporta `status` in `active` e rientra nella rotazione — senza che sia necessaria una nuova aggiunta manuale.

Questo è deliberatamente** opt-in e non distruttivo** : per impostazione predefinita lo scheduler conta e registra solo gli errori (vedere la policy C in `decision.ts`) e `PROXY_AUTO_DISABLE` non elimina mai una riga — a cui serve il flag `PROXY_AUTO_REMOVE` separato e più aggressivo. Se entrambi sono impostati su `true`, `PROXY_AUTO_REMOVE` vince (un proxy che sta per essere eliminato non ha alcuna utilità per una disabilitazione temporanea nel mezzo). Consulta il riferimento [alla configurazione dell'ambiente](../reference/ENVIRONMENT.md) per l'elenco completo delle variabili.

---

> 📖** Documentazione correlata:**
>
> - [Guida per l'utente](../guides/USER_GUIDE.md) — Impostazione e configurazione generale - [API Riferimento](../reference/API_REFERENCE.md) — Documentazione completa API - [Configurazione ambiente](../reference/ENVIRONMENT.md) — Tutte le variabili di ambiente
