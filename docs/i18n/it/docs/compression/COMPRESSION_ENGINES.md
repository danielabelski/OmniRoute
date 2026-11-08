# Compression Engines (Italiano)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

La compressione OmniRoute è costruita attorno ai contratti del motore. Una modalità può eseguire direttamente un motore (`caveman` o `rtk`) o una pipeline in pila deterministica che esegue più motori in ordine.

## Modalità

| Modalità     | Percorso del motore                                                                                                                | Ingresso previsto                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| `off`        | nessuno                                                                                                                            | Conservazione esatta e tempestiva                      |
| `lite`       | Aiutanti Caveman Lite                                                                                                              | Pulizia sempre attiva a basso rischio                  |
| `standard`   | Cavernicolo                                                                                                                        | Condensazione immediata del linguaggio naturale        |
| `aggressive` | Riassunti di Caveman + history/tool                                                                                                | Lunghe sessioni di chat                                |
| `ultra`      | Caveman + aiutanti per la potatura                                                                                                 | Recupero del limite del contesto                       |
| `rtk`        | RTK                                                                                                                                | Terminale, shell, build, test e output git             |
| `omniglyph`  | OmniGlyph                                                                                                                          | Contesto come immagine sul cavo del provider nativo    |
| `stacked`    | Conduttura. L'impostazione predefinita della richiesta è `session-dedup -> lite`. `rtk -> caveman` è un'opzione di partecipazione. | Registri di strumenti misti e prosa, massimo risparmio |

### profili di compressione OmniGlyph

Il motore `omniglyph` (pacchetto `omniglyph`, 1.4.0 +) accetta un profilo semantico denominato, impostato globalmente tramite `omniglyph.profile` nelle impostazioni di compressione o per passaggio tramite la configurazione dei passaggi della pipeline in pila:

| Profilo       | Confine                                                                                                                                |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Predefinito. La politica delle ricevute pubblicate ha misurato il sistema di immagini —, i documenti degli strumenti e la densa storia |
| `balanced`    | Mantiene lo stato live nativo, protegge gli ultimi 8 turni, comprime la cronologia chiusa più vecchia                                  |
| `coding-safe` | Mantiene nativi l'autorità, gli schemi degli strumenti e l'output degli strumenti live, protegge gli ultimi 12 turni                   |
| `passthrough` | Percorsi senza trasformazione; il motore è saltato                                                                                     |

Il profilo è a** soffitto, non un pavimento** : `mergeCompressionProfileOptions` nel pacchetto rifiuta di consentire a un chiamante di sovrascrivere di riaprire una corsia con perdita di dati chiusa dal profilo, quindi `preserveSystemPrompt: false` per passaggio non può riattivare la compressione del sistema in `coding-safe`.

Misurato su questa base di codice: `coding-safe` e `balanced` aumentano `minCompressChars` al suo massimo e mantengono nativi il sistema, gli schemi degli strumenti e i risultati degli strumenti, quindi una sessione che non ha ancora accumulato cronologia si ferma su `below_min_chars` e il motore non trasforma nulla. Questo è il motivo per cui l'impostazione predefinita è `aggressive` anziché il profilo più sicuro.

Il pacchetto risolve il proprio ambito e profilo del modello dalla configurazione dell'ambiente. OmniRoute non delega mai la decisione: l'adattatore fissa il gate del modello all'ambito più restrittivo del pacchetto, quindi le impostazioni dell'ambiente host possono solo restringere la lista consentita, mai ampliarla oltre le ricevute misurate di OmniRoute.

## Registro del motore

Il registro vive a `open-sse/services/compression/engines/registry.ts`. I motori espongono un contratto condiviso:

- `id`: ID motore stabile come `caveman` o `rtk`
- `apply(text, config)`: percorso di esecuzione legacy utilizzato dalle pipeline in pila
- `compress(input, config)`: percorso di esecuzione primario che restituisce il testo + stats
- `getConfigSchema()`: restituisce la forma simile a JSON-Schema della configurazione valida
- `validateConfig(config)`: restituisce `{ valid, errors[] }`

La registrazione utilizza `registerCompressionEngine(engine)` (o `registerEngine` per i casi avanzati), che chiama `assertValidEngine()` e `validateConfig(defaultConfig)` prima di accettare. Utilizzare `unregisterCompressionEngine(id)` per rimuovere un motore in fase di esecuzione.

`strategySelector.ts` registra i motori integrati prima dell'esecuzione della compressione. Ciò consente all'anteprima, alla compressione runtime, alla modalità in pila, ai test e ai motori futuri di utilizzare lo stesso percorso di esecuzione.

### compressione della descrizione MCP (correlata)

Un registro separato comprime i metadati della descrizione dello strumento MCP a livello di registro — vedere `open-sse/mcp-server/descriptionCompressor.ts` e [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Riutilizza le regole Caveman ma opera sui metadati dello strumento, non sulle richieste di payload.

### Motori integrati aggiuntivi

Oltre a Caveman, RTK e LLMLingua-2, il registro fornisce diversi motori specializzati senza perdite/strutturali (utilizzati da condutture impilate, parco giochi e test):

| Motore         | Id              | Cosa fa                                                                                                                                                                                                          |
| -------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR            | `ccr`           | Content-Compress-Retrieve (H4): sostituisce grandi blocchi di testo contigui con riferimenti indirizzati al contenuto, quindi i blocchi repeated/large vengono inviati una volta e successivamente referenziati. |
| altezza libera | `headroom`      | SmartCrusher (H3 + N5): compattazione tabulare senza perdite di carichi utili di array JSON omogenei in una forma `[N rows]` colonnare.                                                                          |
| ionizzatore    | `ionizer`       | campionamento di righe Head/middle/tail per blocchi omogenei molto grandi, memorizzando il centro eliso come riferimento indirizzato al contenuto CCR.                                                           |
| sessione-deup  | `session-dedup` | Deduplicazione cross-turn indirizzata al contenuto (ispirata a TokenMizer): elide il testo già visto nei turni precedenti della stessa sessione.                                                                 |

**CCR istruzione del protocollo di recupero (#8033):** la prima volta che CCR sostituisce ≥ 1 blocco in una richiesta, il motore antepone un singolo messaggio `system` idempotente (che porta con la sentinella `[CCR protocol]` ) insegnando al chiamante il contratto dello strumento marcatore → : cosa significa un marcatore `[CCR retrieve hash=<24hex> chars=N]`, che l'hash deve essere copiato alla lettera (tutti i 24 caratteri esadecimali — gli hash copiati erroneamente sono la probabile causa di "blocco non trovato") e che un marcatore `[dedup:ref sha=...]` significa "guarda indietro" nella storia", non "chiama lo strumento". La nota viene iniettata** solo quando lo `tools[]` pubblicizzato del chiamante dimostra che può effettivamente raggiungere `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — un semplice chiamante compatibile con OpenAI senza quello strumento non riceve mai un'istruzione per chiamare qualcosa che non può raggiungere. L'idempotenza viene applicata eseguendo la scansione della cronologia dei messaggi per la sentinella prima dell'iniezione, quindi le richieste a più turni (che riproducono i messaggi precedenti) non impilano la nota una volta per turno.

## Cavernicolo

La modalità Caveman si concentra sulla condensazione semantica della prosa normale:

- preserva blocchi di codice, URLs, JSON, percorsi e dati strutturati
- rimuove riempitivi, coperture, contesto ripetuto e frasi connettive verbose
- supporta i pacchetti di regole di file compatibili con la lingua in `open-sse/services/compression/rules/`
- rimane disponibile tramite le modalità legacy `standard`, `aggressive` e `ultra`

La superficie del cruscotto è `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream riporta `~75%` meno token di output, `65%` risparmi di output medi nei benchmark con un intervallo `22-87%` e uno strumento di compressione di input `~46%`. OmniRoute utilizza il numero sul lato input di Caveman quando documenta i risparmi prompt/context in pila; La modalità di output Caveman rimane una caratteristica di comportamento di risposta separata.

## RTK

La modalità RTK si concentra sull'output del comando e dello strumento:

- rileva classi di output come `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go tests, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, stack traces e log generici
- applica 49 filtri JSON da `open-sse/services/compression/engines/rtk/filters/`
- supporta la pipeline dichiarativa in stile RTK: rimozione ANSI, sostituzione, cortocircuito dell'output corrispondente, linee strip/keep, troncamento per riga, troncamento head/tail/max-line e fallback su vuoto
- supporta filtri di progetto con controllo attendibile in `.rtk/filters.json` e filtri globali in `DATA_DIR/rtk/filters.json`
- rimuove le sequenze ANSI, il rumore di avanzamento, le righe ripetute e il boilerplate inutile
- preserva gli errori risolvibili, gli avvisi, i riepiloghi, i file modificati e il contesto finale
- può facoltativamente conservare l'output grezzo redatto per recovery/debugging attraverso percorsi di gestione autenticati

La superficie del cruscotto è `Dashboard -> Context & Cache -> RTK`.

I dettagli operativi per filtri personalizzati, attendibilità, verifica e ripristino di output non elaborati sono disponibili in [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream riporta i risparmi `60-90%` per la compressione dell'output dei comandi. Il suo esempio README mostra una sessione di codice Claude di 30 minuti che passa dai token `~118,000` a `~23,900` o `79.7%` salvati.

## LLMLingua-2 (potatura semantica)

La modalità LLMLingua-2 viene eseguita** potatura semantica dei token** sulla prosa utilizzando un piccolo classificatore di token ONNX, che integra i motori Caveman e RTK basati su regole:

- comprime la prosa solo nei messaggi non di sistema; i blocchi di codice protetti e altri costrutti conservati non vengono mai modificati
- esegue il backend `@atjsh/llmlingua-2` (ONNX tramite `@huggingface/transformers`) in un thread di lavoro, quindi l'inferenza del modello non blocca mai il ciclo degli eventi della richiesta
- È** impilabile** (`stackPriority` 35): in una pipeline impilata viene eseguito dopo i motori strutturali (CCR, session-dedup, headroom, Caveman) ma prima di `ultra`, poiché la potatura semantica è più efficace su testo già compresso strutturalmente — eg `rtk -> caveman -> llmlingua`
- **si apre in caso di errore** (mancano funzioni facoltative, spawn del lavoratore, caricamento del modello, inferenza o timeout) → il testo originale viene restituito invariato, mai un errore

Posizione del motore: `open-sse/services/compression/engines/llmlingua/`. La superficie del cruscotto è `Dashboard -> Context & Cache -> LLMLingua`.

### Modelli

Il modello predefinito è**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, veloce). Una precisione più elevata** Base BERT** Il modello (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) è disponibile tramite il campo `model` di configurazione del motore. `@huggingface/transformers` scarica pigramente il modello selezionato dall'hub HuggingFace in `${DATA_DIR}/models/llmlingua` alla prima chiamata (`modelStore.ts`); un override della configurazione `modelPath` lo punta invece a una copia locale (installazioni offline/air gap).

### Dipendenze opzionali e installazione su richiesta

Lo stack peer runtime LLMLingua potabile è** opzionale** . Due pacchetti vengono dichiarati come `optionalDependencies` in `package.json` e mantenuti** esterno** dalla build di produzione (`scripts/build/prepublish.ts` non li raggruppa):

| Pacchetto            | Versione (perno) | Note                                             |
| -------------------- | ---------------- | ------------------------------------------------ |
| `@atjsh/llmlingua-2` | `2.0.5`          | Pacchetto ingresso; dichiara gli altri come pari |
| `js-tiktoken`        | `^1.0.20`        | Tokenizzatore                                    |

`@huggingface/transformers` è bloccato su `^4.2.0` (condiviso con il percorso degli incorporamenti locali e anche tracciato nel bundle autonomo); `@atjsh/llmlingua-2@2.0.5` esegue il peer su di esso con `"^3.5.2 || ^4.0.0"`, quindi sono supportati sia Transformers.js v3 che v4. Dalla versione 2.0.4, `@atjsh/llmlingua-2` non richiede più `@tensorflow/tfjs`, il che ha rimosso il singolo contributore più grande (TensorFlow.js) dallo stack SLM. Solo i due pacchetti sopra riportati sono peer SLM potabili. Uno `npm install` standard (dev) installa automaticamente lo stack opzionale a meno che non vengano omesse dipendenze opzionali.

**Perché su richiesta:** il pacchetto pubblicato da npm, il pacchetto autonomo e la spedizione dell'immagine Docker** senza** questi deps per rimanere magri. Quando sono assenti, il gate di dipendenza del lavoratore (una sonda di risoluzione `@atjsh/llmlingua-2` in `worker.ts`) fallisce e il motore** fail-si apre silenziosamente** — selezionando LLMLingua diventa un no-op (testo restituito invariato, nessun errore registrato). Per attivarlo in un ambiente ridotto, installa lo stack opzionale:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

La rimozione `@tensorflow/tfjs` (2.0.4 +) elimina il contributore ~ 800 MB precedentemente dominante — l'impronta rimanente è costituita dai runtime transformers.js + onnxruntime-node, più il modello TinyBERT (~ 57 MB) scaricato al primo utilizzo (non tramite npm).

Per ambiente:

- **Dev/ `npm install`** — installato automaticamente a meno che tu non abbia passato `--omit=optional` (o `--no-optional`). Nessuna azione necessaria.
- **Npm globale (`npm i -g omniroute`)/autonomo** — esegui il comando di installazione sopra all'interno della directory del pacchetto installato o reinstallalo senza omettere deps facoltativo.
- **Docker** — aggiunge il comando di installazione in un livello di immagine derivato; l'immagine pubblicata è snella in base alla progettazione.
- **VPS (PM2)** — installare nello `node_modules` dell'app, quindi riavviare il processo in modo che il lavoratore riesamini il cancello.
- **Raw Next autonomo (`npm run build` → `.build/next/standalone/server.js`)** — la traccia autonoma spedisce NEITHER il lavoratore né i dipendenti facoltativi, quindi il motore si apre silenziosamente con errore. `scripts/build/colocate-standalone.mjs` li riapplica entrambi (worker esbuild + optional-dep closing nell'albero autonomo); viene eseguito automaticamente tramite l'hook `postbuild` npm dopo ogni build. Idempotente, fail-soft quando i deps sono assenti.

**Verifica che sia attivo:** con LLMLingua selezionato, la prosa reale si restringe effettivamente (il motore interrompe l'apertura in caso di errore) e la prima richiesta attiva il download del modello in `${DATA_DIR}/models/llmlingua`. Il gate sonda intenzionalmente solo `@atjsh/llmlingua-2` — gli altri peer sono solo ESM e `require.resolve` li lancia anche quando sono presenti — in modo che il lavoratore si apra comunque con errore se qualche peer è effettivamente mancante al momento `import()`.

## Condutture impilate

La modalità in pila esegue i passaggi della pipeline in ordine. L'impostazione predefinita è:

```txt
rtk -> caveman
```

Utilizzarlo per le sessioni dell'agente di codifica in cui un prompt combina l'output del comando con la prosa umana o dell'assistente. RTK riduce innanzitutto i log degli strumenti rumorosi, quindi Caveman comprime il linguaggio naturale rimanente.

I passaggi della pipeline vengono configurati con `stackedPipeline` nelle impostazioni di compressione o tramite combo di compressione.

Quando entrambi i motori riducono lo stesso carico utile ammissibile, i risparmi si sommano:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Filtro albero di accessibilità

Il filtro intelligente dell'albero dell'accessibilità MCP è un livello di compressione post-esecuzione eseguito su MCP** risultati dello strumento** , non su prompt o contesto. Si rivolge ai payload dettagliati dell'albero di accessibilità e delle istantanee del browser restituiti da strumenti come Playwright, server MCP per l'uso del computer e l'automazione del browser.

### Cosa fa

1. **Eliminazione del rumore** — rimuove le voci generic/text vuote (`- generic:`, `- text: ""`)
2. **Crollo del fratello** — quando ≥ `collapseThreshold` (default 30) righe consecutive sono ripetizioni strutturali, le comprime nelle prime righe `collapseKeepHead` (default 10) + un riepilogo del conteggio + le ultime righe `collapseKeepTail` (default 5)
3. **Conservazione del rif** Gli ancoraggi — `[ref=eXX]` richiesti da Playwright/computer-use non vengono mai toccati
4. **Troncamento duro** — se il testo dopo la compressione supera ancora `maxTextChars` (50.000 predefinito), viene troncato con un suggerimento di navigazione in modo che l'agente possa continuare a lavorare

### Posizione del motore

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Configurazione

Controllato da `compression.mcpAccessibility` nelle impostazioni globali (migrazione 056). Configurazione predefinita:

```json
{
  "enabled": true,
  "maxTextChars": 50000,
  "collapseThreshold": 30,
  "collapseKeepHead": 10,
  "collapseKeepTail": 5,
  "minLengthToProcess": 2000
}
```

Il filtro viene applicato solo ai payload dei risultati dello strumento la cui `type` è `"text"` e la cui lunghezza supera `minLengthToProcess`. Non influisce sulla compressione rapida né sui payload delle richieste.

### Risparmio atteso

60–80% sui risultati dello strumento snapshot del browser, a seconda della complessità della pagina. L'algoritmo di collasso è O(n) nel conteggio delle righe e aggiunge una latenza trascurabile.

### Questo filtro rispetto ai motori di compressione sopra

| Aspetto     | Cavernicolo / RTK / Stacked                 | filtro di accessibilità MCP            |
| ----------- | ------------------------------------------- | -------------------------------------- |
| Bersaglio   | Richiedi suggerimenti/contesto              | Risultati dello strumento MCP          |
| Grilletto   | Impostazione della modalità di compressione | `compression.mcpAccessibility.enabled` |
| Ambito      | Tutti i messaggi SSE                        | Solo risultati dello strumento         |
| Rif. ancore | N/A                                         | Conservato incondizionatamente         |

---

## Combo di compressione

Le combo di compressione sono denominate profili di compressione che possono essere assegnati alle combo di routing:

- `compression_combos`: memorizza la modalità, la pipeline, la configurazione RTK, la configurazione della lingua e l'indicatore predefinito
- `compression_combo_assignments`: mappa una combo di compressione su una combo di routing
- l'integrazione runtime risolve una combinazione di compressione assegnata prima che la combinazione generica sovrascriva
- le analisi includono `compression_combo_id` e `engine`

Superficie del cruscotto: `Dashboard -> Context & Cache -> Compression Combos`.

## Prerequisiti/guida per l'operatore (CCR e sessione-dedup)

CCR (`ccr`) e `session-dedup` sostituiscono o elidono il testo e lasciano a** marcatore** dietro. Questa sezione è il riferimento dell'operatore per collegare un client, leggere i due marcatori e recuperare o diagnosticare il contenuto eliso. La meccanica di ciascun motore è trattata sopra; questo è il livello "come faccio a eseguirlo".

### Trasporti ed endpoint

Il server MCP che espone gli strumenti CCR può essere raggiunto in tre modi. La base URL predefinita è `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Trasporto                             | URL /comando                            | Note                                                                                                                                     |
| ------------------------------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| HTTP streaming (cliente, consigliato) | `http://localhost:20128/api/mcp/stream` | L'endpoint con cui parlano i client MCP attuali.                                                                                         |
| Legacy SSE singleton                  | `http://localhost:20128/api/mcp/sse`    | Trasporto singleton precedente. Esso** chiude** sessioni streaming; usa i client `streamable-http` contro `/api/mcp/stream`, non questo. |
| stdio                                 | `omniroute --mcp`                       | Per IDE MCP config che genera il processo. Non esiste un flag `--dev` ; `omniroute --mcp` è il punto di ingresso stdio.                  |

### Livelli di archiviazione (cosa sopravvive al riavvio)

CCR è un** a due livelli** store, non solo in memoria:

- **Livello in memoria attivo** — limite massimo per blocco 2 MiB, per principale 16 MiB, globale 64 MiB. Per impostazione predefinita, le iscrizioni sono impostate su 24 TTL (massimo 7 giorni). Il recupero completo MCP dalla memoria è limitato a 256 KiB; qualsiasi cosa più grande è ancora raggiungibile attraverso le modalità ranged/grep.
- **Livello SQLite durevole** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, attivo per impostazione predefinita) — supporta il livello in memoria in modo che un blocco sopravviva all'eliminazione LRU, a un riavvio o a un recupero su un'altra istanza. La riga mantiene lo TTL del blocco, quindi un blocco oltre il suo TTL viene eliminato da entrambi i livelli.

Tre guardie mantengono delimitato il livello durevole — un blocco rimane di sola memoria quando:

1. il blocco è finito** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. il runtime è un runtime cloud (nessun disco locale);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Quindi "il blocco è scomparso" non è una storia di riavvio generale: un blocco sub-512 KB su un runtime locale non cloud sopravvive a un riavvio tramite il livello durevole fino all'esaurimento del suo TTL. Vedere [Riferimento all'ambiente](../reference/ENVIRONMENT.md) per la variabile.

### I due marcatori

| Marcatore                             | Senso                                                                                                                                                              | Cosa dovrebbe fare il modello                                                                                                                                                                                           |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Un blocco di grandi dimensioni è stato archiviato con indirizzo del contenuto.                                                                                     | Chiama `omniroute_ccr_retrieve` con il** Hash a 24 esadecimali copiato alla lettera** per recuperare il testo originale.                                                                                                |
| `[dedup:ref sha=…]`                   | `session-dedup` testo eliso già inviato in un turno precedente della stessa sessione. Questo è un** sguardo indietro intenzionale** , non una perdita o un errore. | Fare** non** chiama qualsiasi strumento e fai** non** provare a "ricostruirlo". La prima occorrenza del testo è la copia canonica; il turno corrente non viene mai riscritto, viene deduplicato in un turno successivo. |

La `[dedup:ref]` look-back è una decisione deliberata del protocollo, — non esiste una ricostruzione pre-invio. Trattalo come se "questo testo esatto fosse già trasmesso in rete all'inizio di questa sessione".

### Prerequisiti del cliente

- **Chiave (stdio):** un chiamante stdio non ha identità per richiesta, quindi si autentica con `OMNIROUTE_API_KEY` (impostato nel `env` del server MCP ). Senza di esso il chiamante è anonimo e gli strumenti che richiedono un principale potrebbero deteriorarsi.
- **`tools[]` è la precondizione dell'iniezione.** Viene iniettata l'istruzione del protocollo di recupero CCR (#8033).** soltanto** quando lo `tools[]` pubblicizzato della richiesta dimostra che il cliente può effettivamente raggiungere `omniroute_ccr_retrieve`. La corrispondenza è una corrispondenza del segmento finale delimitata da un separatore (`__`, `.`, `/`, `:`) — mai una semplice sottostringa — quindi un nome con spazio dei nomi come `mcp__gateway__omniroute_ccr_retrieve` conta comunque. Uno `tools[]` assente o non corrispondente significa che l'istruzione _non_ è stata iniettata, in base alla progettazione.
- **`codemode:false` (client OpenCode ).** OpenCode per impostazione predefinita è Code Mode, che pubblicizza solo i suoi strumenti nativi sul modello e** no** inserisci gli strumenti MCP nell'elenco `tools[]` nativo. Imposta `codemode: false` sulla voce del server MCP in modo che gli strumenti `omniroute_ccr_*` vengano pubblicizzati. Questo è un** cliente** impostazione, non OmniRoute. Non viene ancora inserita l'istruzione CCR : OpenCode nomina uno strumento `<server>_<tool>`, quindi un server chiamato `omniroute` espone `omniroute_omniroute_ccr_retrieve` e `_` non è uno dei separatori corrispondenti.
- **Principali.** L'archiviazione e il recupero sono isolati per entità autenticata (per chiave API ). Una chiave vede solo i propri blocchi.

### Ambiti per strumento

L'applicazione dell'ambito è sempre attiva per i chiamanti HTTP/SSE con ambito ristretto. Gli strumenti `omniroute_` CCR richiedono:

| Attrezzo                 | Ambito              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Un ambito mancante restituisce un** Risultato dell'errore dello strumento MCP** (`isError: true`, non HTTP 403 — `403 LOCAL_ONLY` è l'autenticazione di protezione del percorso di loopback separata): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Una chiave remota minima può contenere `mcp:connect` (autorizza il carve-out `/api/mcp/` solo locale) più l'ambito read/write specifico di cui ha bisogno.

### Matrice cliente

| Cliente                | Trasporto                                        | Configurazione da utilizzare                                                                                                                                                                                                                          | `tools[]` pubblicizzato? (istruzione → CCR inserita)                                                                                                                                                              |
| ---------------------- | ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Codice Claude          | streaming-http                                   | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                     | Sì — compatibile con MCP; iniettato.                                                                                                                                                                              |
| Cursor / Cline         | `stdio`** O** `streamable-http`                  | stdio: `omniroute --mcp` con `OMNIROUTE_API_KEY` in `env`; o una voce MCP remota che punta a `http://localhost:20128/api/mcp/stream` (vedi [Guida all'installazione → MCP Configurazione client](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Sì — pubblicizza gli strumenti `omniroute_ccr_*`.                                                                                                                                                                 |
| OpenCode               | streaming-http                                   | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, più `codemode: false`                                                                                                                                                       | Strumenti pubblicizzati solo con `codemode: false`; l'istruzione non è ancora stata iniettata perché `omniroute_omniroute_ccr_retrieve` non corrisponde (vedi [Prerequisiti del client](#client-prerequisites) ). |
| Compatibile con OpenAI | HTTP compatibile con OpenAI (completamenti chat) | client standard di completamento chat rispetto all'endpoint compatibile con OpenAI                                                                                                                                                                    | **Mai** — a un semplice chiamante compatibile con OpenAI non viene mai detto di chiamare lo strumento e l'istruzione non viene iniettata.                                                                         |

### Limiti di recupero e impaginazione

I risultati del testo dello strumento MCP vengono ritagliati attorno a `mcpAccessibility.maxTextChars` (default `50000`). Il recupero `full` di un blocco è limitato a 256 KiB —** non esiste un recupero completo illimitato** . Quando `chars=N` di un blocco è grande, paginalo invece di estrarre il tutto:

- Regola pratica:**`chars > 40000` → usa uno `mode`** , mai completamente nudo.
- `mode:"grep"` — regex `pattern` abbinato riga per riga, fino a 1.000 righe corrispondenti (`unique: true` elimina le ripetizioni), più economico per "trovare la riga di cui ho bisogno".
- `mode:"lines"` — un intervallo di linee indicizzate a 1; ha bisogno sia `start` che `end`.
- linee `mode:"head"` / `mode:"tail"` — first/last `n`.
- `mode:"stats"` — conteggio di righe, caratteri e byte senza il corpo.

Usa `mode:"lines"` con `start`/`end` per percorrere un lungo blocco di pagine anziché richiedere tutto in una volta.

### Denominazione degli strumenti

Lo strumento di recupero è attualmente denominato `omniroute_ccr_retrieve` (il prefisso `omniroute_` è una soluzione datata per le collisioni di nomi tra server). Un nome dello strumento con suffisso delimitato più pulito e una correzione per i risultati MCP JSON troncati a metà stringa vengono tracciati come follow-up upstream; questa pagina documenta solo il comportamento attuale della spedizione.

### Ciclo di vita della sessione

Le sessioni HTTP streaming sono inattive e il server le raccoglie; la finestra inattiva è la costante `MCP_SESSION_IDLE_MS` (a cui fa riferimento il nome, non un valore codificato, quindi questa pagina non va alla deriva quando cambia). Il sintomo di una sessione inattiva è uno HTTP 404 con `Unknown Mcp-Session-Id` — il rimedio è riconnettersi o riavviare la sessione,** non** per ruotare una chiave, modificare un ambito o rinominare uno strumento.

## API Superficie

| Itinerario                             | Scopo                                                                    |
| -------------------------------------- | ------------------------------------------------------------------------ |
| `/api/settings/compression`            | Impostazioni di compressione globali (include `mcpAccessibility` config) |
| `/api/compression/preview`             | Anteprima di qualsiasi modalità di compressione                          |
| `/api/compression/language-packs`      | Elenca i pacchetti linguistici Caveman disponibili                       |
| `/api/context/caveman/config`          | Alias delle impostazioni di Caveman                                      |
| `/api/context/rtk/config`              | Impostazioni e impostazioni predefinite RTK                              |
| `/api/context/rtk/filters`             | Catalogo dei filtri RTK                                                  |
| `/api/context/rtk/test`                | punto finale RTK preview/test                                            |
| `/api/context/rtk/raw-output/[id]`     | Recupero dell'output raw redatto e autenticato                           |
| `/api/context/combos`                  | Combo di compressione CRUD                                               |
| `/api/context/combos/[id]/assignments` | Assegnazione combo routing CRUD                                          |
| `/api/context/analytics`               | Alias di analisi di compressione                                         |

I percorsi di gestione richiedono l'autenticazione della gestione o i controlli dei criteri della chiave API.

## MCP Strumenti

La compressione espone cinque strumenti MCP :

| Attrezzo                            | Ambito              | Scopo                                          |
| ----------------------------------- | ------------------- | ---------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Impostazioni, analisi, statistiche della cache |
| `omniroute_compression_configure`   | `write:compression` | Aggiorna le impostazioni globali               |
| `omniroute_set_compression_engine`  | `write:compression` | Imposta la modalità e la pipeline opzionale    |
| `omniroute_list_compression_combos` | `read:compression`  | Elenca le combo di compressione                |
| `omniroute_compression_combo_stats` | `read:compression`  | Leggi l'analisi combo/engine                   |

## Ambito ed esclusioni

**Gli incorporamenti non vengono mai compressi.** `open-sse/handlers/embeddings.ts` non chiama mai alcun motore di compressione — i corpi request/response passano direttamente all'esecutore intatti. Questo è strutturale oggi (gli incorporamenti e i completamenti della chat sono gestori disgiunti), non un controllo di runtime, ma significa che il problema della distorsione vettoriale in #8034 non ha superficie di esposizione nel percorso degli incorporamenti.

**filtro di esclusione Per-model/endpoint (#8034).** Per i completamenti della chat, un operatore può nominare ID modello/obiettivi `provider/model` che non devono mai essere compressi — un guardrail utile se la compressione viene mai collegata più vicino a un percorso adiacente agli incorporamenti in seguito e generalmente utile per qualsiasi modello il cui prompt esatto byte per byte è importante (valutazioni deterministiche, prefissi sensibili alla cache, ecc.).

- Campo Impostazioni: `exclusions?: string[]` nella configurazione di compressione globale (`GET`/`PUT /api/settings/compression`), persistente tramite lo spazio dei nomi di compressione `key_value` esistente (`src/lib/db/compression.ts`) — nessuna nuova tabella.
- Scheda Dashboard:** Dashboard → Compressione → Esclusioni** (`/dashboard/compression/exclusions`).
- Sintassi del modello: `*` è l'unico carattere jolly. Ogni altro metacarattere regex in un modello viene sottoposto a escape prima della corrispondenza, quindi `gpt-5.6` corrisponde solo alla stringa letterale, mai `gpt-5x6` (reDoS-safe, limitato, senza quantificatori nidificati). I modelli corrispondono senza distinzione tra maiuscole e minuscole sia rispetto all'ID del modello semplice che al composito `provider/model` — `gpt-5-6`, `openai/gpt-5-6` e `openai/*` funzionano tutti e `*` da solo esclude ogni modello.
- Corrispondenza: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` controlla la destinazione esclusa subito dopo aver risolto le impostazioni di compressione,** prima che qualsiasi motore venga avviato** e tratta una corrispondenza esattamente come se la compressione fosse disabilitata globalmente — il corpo della richiesta è probabilmente identico in byte. Il salto viene registrato tramite `writeCompressionSkip(..., "excluded")` per la visibilità analitica.
- Default (lista empty/absent ): identico al comportamento pre-#8034 — nulla è escluso.

## Limitazioni note

- **LLMLingua-2 (SLM) richiede unità facoltative co-localizzate.** Il lavoratore viene eseguito solo in una build di produzione quando i peer `@atjsh/llmlingua-2` + sono co-locati in `dist/node_modules` (vedere `scripts/build/colocateOptionals.mjs`, #4286). Senza di essi il motore si apre in modo fallito (restituisce il testo originale). La risoluzione del lavoratore non dipende più da `import.meta.url` (muore nel pacchetto autonomo) — si ancora al runtime cwd / `argv[1]`.
- **I pacchetti linguistici Caveman `de` / `fr` / `ja` sono parziali.** Spediscono le regole `context` + `filler` + `structural` ma non i pacchetti `dedup` / `ultra`, quindi l'intensità `ultra` non è più forte di `full` per quelle lingue (usano solo le proprie regole — non esiste un silenzioso ripiego alle regole `dedup`/`ultra` inglesi, che macilicherebbero il testo straniero). `en` / `es` / `id` / `pt-BR` sono completi. Sono benvenuti i contributi di `dedup.json` + `ultra.json` per i pacchetti parziali.
- **La telemetria in pila elenca solo i motori compressi.** Una fase della pipeline in pila il cui motore ha funzionato ma ha prodotto uno 0% di risparmio restituisce `stats:null` e quindi non appare in `engineBreakdown` — indistinguibile da una fase che è stata saltata. Distinguere "eseguito, 0%" da "saltato" richiederebbe una modifica del modello di guasto ed è rinviato.

## Validazione

I cancelli focalizzati per quest'area sono:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
