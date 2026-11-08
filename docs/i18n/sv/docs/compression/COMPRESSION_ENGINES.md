# Compression Engines (Svenska)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompressionen är uppbyggd kring motorkontrakt. Ett läge kan köra en motor direkt (`caveman` eller `rtk`) eller en deterministisk staplad pipeline som kör flera motorer i ordning.

## Lägen

| Läge         | Motorväg                                                                                              | Avsedd input                                       |
| ------------ | ----------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| `off`        | ingen                                                                                                 | Exakt snabb bevarande                              |
| `lite`       | Caveman lite hjälpare                                                                                 | Alltid-på-rengöring med låg risk                   |
| `standard`   | Grottman                                                                                              | Snabbkondensering på naturligt språk               |
| `aggressive` | Grottman + history/tool sammanfattningar                                                              | Långa chattsessioner                               |
| `ultra`      | Caveman + beskärningshjälpare                                                                         | Återställning av kontextgräns                      |
| `rtk`        | RTK                                                                                                   | Terminal, shell, build, test och git output        |
| `omniglyph`  | OmniGlyph                                                                                             | Kontext-som-bild på den inbyggda leverantörskabeln |
| `stacked`    | Rörledning. Standardinställningen för begäran är `session-dedup -> lite`. `rtk -> caveman` är opt-in. | Blandade verktygsloggar och prosa, max besparingar |

### OmniGlyph kompressionsprofiler

`omniglyph` motorn (paketet `omniglyph`, 1.4.0 +) accepterar en namngiven semantisk profil, inställd globalt genom `omniglyph.profile` i komprimeringsinställningarna eller per steg genom den staplade pipelinens stegkonfiguration:

| Profil        | Gräns                                                                                                 |
| ------------- | ----------------------------------------------------------------------------------------------------- |
| `aggressive`  | Standard. Policyn för de publicerade kvittonen mätte — -bildsystem, verktygsdokument och tät historia |
| `balanced`    | Behåller live state native, skyddar de sista 8 varven, kollapsar äldre stängd historia                |
| `coding-safe` | Behåller auktoritet, verktygsscheman och levande verktygsutdata, skyddar de senaste 12 varven         |
| `passthrough` | Rutter utan omvandling; motorn hoppas över                                                            |

Profilen är en** tak, inte ett golv** : `mergeCompressionProfileOptions` i paketet vägrar att låta en anropare åsidosätta återöppna en förlustfil profilen stängd, så en `preserveSystemPrompt: false` per steg kan inte återaktivera systemkomprimering under `coding-safe`.

Mätt på denna kodbas: `coding-safe` och `balanced` höjer `minCompressChars` till sitt maximum och behåller system, verktygsscheman och verktygsresultat inbyggda, så en session som ännu inte har samlat på sig historik stannar vid `below_min_chars` och motorn transformerar ingenting. Det är därför som standard är `aggressive` snarare än den säkraste profilen.

Paketet löser sin egen modellomfattning och profil från sin miljökonfiguration. OmniRoute delegerar aldrig beslutet: adaptern stiftar modellporten till paketets mest restriktiva omfattning, så värdmiljöinställningar kan bara begränsa godkännandelistan, aldrig bredda den förbi OmniRoute uppmätta kvitton.

## Motorregistret

Registret bor i `open-sse/services/compression/engines/registry.ts`. Motorer visar ett delat kontrakt:

- `id`: stabilt motor-ID som `caveman` eller `rtk`
- `apply(text, config)`: äldre exekveringsväg som används av staplade pipelines
- `compress(input, config)`: primär exekveringsväg som returnerar text + statistik
- `getConfigSchema()`: returnerar den JSON-Schema-liknande formen för giltig konfiguration
- `validateConfig(config)`: returnerar `{ valid, errors[] }`

Registrering använder `registerCompressionEngine(engine)` (eller `registerEngine` för avancerade fall), som anropar `assertValidEngine()` och `validateConfig(defaultConfig)` innan den accepteras. Använd `unregisterCompressionEngine(id)` för att ta bort en motor under körning.

`strategySelector.ts` registrerar de inbyggda motorerna innan kompressionen körs. Detta låter förhandsgranskning, körtidskomprimering, staplat läge, tester och framtida motorer använda samma exekveringsväg.

### MCP beskrivningskomprimering (relaterad)

Ett separat register komprimerar MCP verktygsbeskrivningsmetadata på registernivå — se `open-sse/mcp-server/descriptionCompressor.ts` och [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Den återanvänder Caveman-regler men arbetar på verktygsmetadata, inte begärda nyttolaster.

### Ytterligare inbyggda motorer

Utöver Caveman, RTK och LLMLingua-2 skickar registret flera specialiserade förlustfria/strukturella motorer (används av staplade pipelines, lekplatsen och tester):

| Motor         | Id              | Vad den gör                                                                                                                                                                  |
| ------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): ersätter stora sammanhängande textblock med innehållsadresserade referenser, så repeated/large block skickas en gång och refereras därefter. |
| fri höjd      | `headroom`      | SmartCrusher (H3 + N5): förlustfri tabellkomprimering av homogena JSON-array-nyttolaster till en kolumnär `[N rows]` form.                                                   |
| jonisator     | `ionizer`       | Head/middle/tail -radsampling för mycket stora homogena block, lagrar den eliderade mitten som en CCR -innehållsadresserad referens.                                         |
| session-dedup | `session-dedup` | Innehållsadresserad deduplicering av tvärsväng (TokenMizer-inspirerad): eliminerar text som redan setts i tidigare svängar av samma session.                                 |

**CCR retrieve-protocol instruktion (#8033):** första gången CCR ersätter ≥ 1 block i en förfrågan lägger motorn ett enda, idempotent `system` -meddelande (som leder med `[CCR protocol]` vaktposten) som lär den som ringer markören → verktygskontraktet: vad en `[CCR retrieve hash=<24hex> chars=N]` markör betyder, att hashen måste kopieras ordagrant (alla 24 hex-tecken — misshes är troligen orsaken till miss-kopierade) `[dedup:ref sha=...]` markör betyder "titta tillbaka i historien", inte "ringa upp verktyget". Sedeln är injicerad** endast när uppringarens annonserade `tools[]` bevisar att den faktiskt kan nå `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — en vanlig OpenAI-kompatibel anropare utan det verktyget får aldrig en instruktion att anropa något den inte kan nå. Idempotens upprätthålls genom att skanna meddelandehistoriken för vaktposten innan injicering, så flervändningsförfrågningar (som spelar om tidigare meddelanden) staplar inte sedeln en gång per tur.

## Grottman

Caveman-läget fokuserar på semantisk kondensering av normal prosa:

- bevarar kodblock, URLs, JSON, sökvägar och strukturerad data
- tar bort filler, säkring, upprepad kontext och mångsidiga bindande fraser
- stöder språkmedvetna filregelpaket i `open-sse/services/compression/rules/`
- förblir tillgänglig via de äldre lägena `standard`, `aggressive` och `ultra`

Instrumentbrädans yta är `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream rapporterar `~75%` färre output tokens, `65%` genomsnittliga output besparingar i benchmarks med ett `22-87%` intervall och ett `~46%` input-compression tool. OmniRoute använder numret på ingångssidan på Caveman när de dokumenterar staplade prompt/context besparingar; Grottmansutgångsläge förblir en separat funktion för responsbeteende.

## RTK

RTK läget fokuserar på kommando och verktygsutgång:

- upptäcker utdataklasser som `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go -tester, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, stack traces och generiska loggar
- tillämpar 49 JSON -filter från `open-sse/services/compression/engines/rtk/filters/`
- stöder den deklarativa pipeline i RTK-stil: ANSI -stripping, ersätt, match-output-kortslutning, strip/keep -linjer, per-line trunkering, head/tail/max-line -trunkering och on-empty fallback
- stöder trust-gated projektfilter i `.rtk/filters.json` och globala filter i `DATA_DIR/rtk/filters.json`
- strippar ANSI sekvenser, framstegsbrus, upprepade rader och ohjälpsam beskrivning
- bevarar handlingsbara misslyckanden, varningar, sammanfattningar, ändrade filer och svanskontext
- kan valfritt behålla redigerad råutgång för recovery/debugging genom autentiserade hanteringsvägar

Instrumentbrädans yta är `Dashboard -> Context & Cache -> RTK`.

Driftsinformation för anpassade filter, lita på, verifiera och återställning av råutdata live i [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK uppströms rapporterar `60-90%` besparingar för kommando-utgångskomprimering. Dess README exempel visar en 30-minuters Claude Code-session som går från `~118,000` tokens till `~23,900`, eller `79.7%` sparad.

## LLMLingua-2 (semantisk beskärning)

LLMLingua-2 -läget utförs** semantisk tokenbeskärning** på prosa med hjälp av en liten ONNX -tokenklassificerare, som kompletterar de regelbaserade Caveman- och RTK -motorerna:

- komprimerar endast prosa i icke-systemmeddelanden; inhägnade kodblock och andra bevarade konstruktioner ändras aldrig
- kör `@atjsh/llmlingua-2` backend (ONNX via `@huggingface/transformers`) i en arbetstråd, så modellinferens blockerar aldrig request-händelseloopen
- är** stapelbar** (`stackPriority` 35): i en staplad pipeline körs den efter de strukturella motorerna (CCR, session-dedup, headroom, Caveman) men före `ultra`, eftersom semantisk beskärning är mest effektiv på redan strukturellt komprimerad text — t.ex. `rtk -> caveman -> llmlingua`
- **misslyckas öppnas vid något fel** (saknar valfria deps, worker spawn, modellladdning, slutledning eller timeout) → originaltexten returneras oförändrad, aldrig ett fel

Motorns plats: `open-sse/services/compression/engines/llmlingua/`. Instrumentbrädans yta är `Dashboard -> Context & Cache -> LLMLingua`.

### Modeller

Standardmodellen är**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, snabb). En högre noggrannhet** BERT-bas** modell (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) är tillgänglig via motorkonfigurationsfältet `model`. `@huggingface/transformers` laddar ner den valda modellen lätt från HuggingFace hubben till `${DATA_DIR}/models/llmlingua` vid det första samtalet (`modelStore.ts`); en `modelPath` -konfigurationsöverstyrning pekar den mot en lokal kopia istället (offline/installationer med luftgap).

### Valfria beroenden och installation på begäran

Den beskärbara LLMLingua runtime peer-stacken är** frivillig** . Två paket deklareras som `optionalDependencies` i `package.json` och behålls** extern** av produktionsbygget (`scripts/build/prepublish.ts` paketerar dem inte):

| Paket                | Version (stift) | Anteckningar                                 |
| -------------------- | --------------- | -------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`         | Entrépaket; förklarar de andra som jämnåriga |
| `js-tiktoken`        | `^1.0.20`       | Tokenizer                                    |

`@huggingface/transformers` är fäst vid `^4.2.0` (delas med den lokala inbäddningsvägen och spåras även in i det fristående paketet); `@atjsh/llmlingua-2@2.0.5` pekar på den med `"^3.5.2 || ^4.0.0"`, så både Transformers.js v3 och v4 stöds. Sedan 2.0.4 kräver `@atjsh/llmlingua-2` inte längre `@tensorflow/tfjs`, vilket tog bort den största enskilda bidragsgivaren (TensorFlow.js) från SLM stacken. Endast de två paketen ovan är beskärbara SLM kamrater. En standard `npm install` (dev) installerar den valfria stacken automatiskt om inte valfria beroenden utelämnas.

**Varför på begäran:** det npm-publicerade paketet, det fristående paketet och Docker bildskeppet** utan** dessa deps för att hålla sig smal. När de är frånvarande, misslyckas arbetarens beroendeport (en `@atjsh/llmlingua-2` resolve probe i `worker.ts`) och motorn** fail-öppnar tyst** — att välja LLMLingua blir en no-op (texten returneras oförändrad, inget fel loggas). För att aktivera den i en beskuren miljö, installera den valfria stacken:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` borttagningen (2.0.4 +) eliminerar den tidigare dominerande ~ 800 MB -bidragsgivaren — det återstående fotavtrycket är transformers.js + onnxruntime-nodens körtider, plus TinyBERT modellen (~ 57 MB) som laddades ner vid första användningen (inte via npm).

Per miljö:

- **Dev / `npm install`** — installeras automatiskt om du inte klarat `--omit=optional` (eller `--no-optional`). Ingen åtgärd behövs.
- **Global npm (`npm i -g omniroute`) / fristående** — kör installationskommandot ovan i den installerade paketkatalogen, eller installera om utan att utelämna valfria deps.
- **Docker** — lägg till kommandot installation i ett härlett bildlager; den publicerade bilden levereras smal till sin design.
- **VPS (PM2)** — installera i appens `node_modules`, starta sedan om processen så att arbetaren undersöker porten igen.
- **Raw Next fristående (`npm run build` → `.build/next/standalone/server.js`)** — det fristående spåret NEITHER arbetaren eller de valfria depsen, så att motorn tyst misslyckas. `scripts/build/colocate-standalone.mjs` återtillämpar båda (arbetarens esbuild + optional-dep stängning i det fristående trädet); den körs automatiskt via `postbuild` npm-kroken efter varje build. Idempotent, misslyckad när deps saknas.

**Kontrollera att den är aktiv:** med LLMLingua valt, krymper verklig prosa faktiskt (motorn slutar att misslyckas), och den första begäran utlöser modellnedladdningen till `${DATA_DIR}/models/llmlingua`. Grinden sonderar avsiktligt endast `@atjsh/llmlingua-2` — de andra peers är ESM-endast och `require.resolve` kastar på dem även när de är närvarande — så arbetaren fortfarande misslyckas-öppnar om någon peer verkligen saknas vid `import()` tidpunkten.

## Staplade rörledningar

Stacked mode kör pipeline steg i ordning. Standard är:

```txt
rtk -> caveman
```

Använd detta för kodningsagentsessioner där en prompt kombinerar kommandoutmatning med mänsklig eller assistentprosa. RTK reducerar bullriga verktygsloggar först, sedan komprimerar Caveman återstående naturliga språk.

Pipeline-stegen konfigureras med `stackedPipeline` i kompressionsinställningar eller genom kompressionskombinationer.

När båda motorerna minskar samma kvalificerade nyttolast, blir besparingar:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Accessibility Tree Filter

MCP accessibility-tree smart filter är ett komprimeringslager efter exekvering som körs på MCP** verktygsresultat** , inte på uppmaningar eller sammanhang. Den riktar sig till det omfattande tillgänglighetsträdet och webbläsarens ögonblicksbildnyttolaster som returneras av verktyg som Playwright, datoranvändning och webbläsarautomation MCP -servrar.

### Vad den gör

1. **Brusreducering** — tar bort tomma generic/text poster (`- generic:`, `- text: ""`)
2. **Syskon kollapsar** — när ≥ `collapseThreshold` (standard 30) på varandra följande rader är strukturella upprepningar, kollapsar dem till de första `collapseKeepHead` (standard 10) raderna + en sammanfattning av antalet + de sista `collapseKeepTail` (standard 5) raderna
3. **Ref konservering** — `[ref=eXX]` -ankare som krävs av Playwright/computer-use vidrörs aldrig
4. **Hård trunkering** — om texten efter komprimering fortfarande överstiger `maxTextChars` (standard 50 000), trunkeras med en navigeringstips så att agenten kan fortsätta arbeta

### Motorns plats

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfiguration

Styrs av `compression.mcpAccessibility` i globala inställningar (migrering 056). Standardkonfiguration:

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

Filtret tillämpas endast på nyttolaster med verktygsresultat vars `type` är `"text"` och vars längd överstiger `minLengthToProcess`. Det påverkar inte promptkomprimering eller nyttolaster för begäran.

### Förväntade besparingar

60–80 % på resultat från webbläsarens ögonblicksbildverktyg, beroende på sidans komplexitet. Kollapsalgoritmen är O(n) i radantal och lägger till försumbar latens.

### Detta filter kontra kompressionsmotorerna ovan

| Aspekt     | Grottman / RTK / Stacked         | MCP tillgänglighetsfilter              |
| ---------- | -------------------------------- | -------------------------------------- |
| Mål        | Begäranrop/kontext               | MCP verktygets resultat                |
| Utlösare   | Inställning av komprimeringsläge | `compression.mcpAccessibility.enabled` |
| Omfattning | Alla SSE meddelanden             | Endast verktygsresultat                |
| Ref ankare | N/A                              | Bevarad villkorslöst                   |

---

## Kompressionskombinationer

Kompressionskombinationer är namngivna komprimeringsprofiler som kan tilldelas till routingkombinationer:

- `compression_combos`: lagrar läge, pipeline, RTK config, language config och standardmarkör
- `compression_combo_assignments`: mappar en kompressionskombo till en routingkombination
- runtime integration löser en tilldelad kompressionskombination innan generisk kombination åsidosätter
- analys inkluderar `compression_combo_id` och `engine`

Instrumentbrädans yta: `Dashboard -> Context & Cache -> Compression Combos`.

## Förutsättningar / operatörsguide (CCR & session-dedup)

CCR (`ccr`) och `session-dedup` ersätter eller eliminerar text och lämnar a** markör** bakom. Det här avsnittet är operatörsreferens för att koppla upp en klient, läsa de två markörerna och hämta eller diagnostisera det avlägsnade innehållet. Mekanik för varje motor täcks ovan; detta är lagret "hur kör jag det".

### Transporter och slutpunkter

MCP servern som exponerar CCR verktygen kan nås på tre sätt. Standardbasen URL är `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transport                              | URL / kommando                          | Anteckningar                                                                                                                        |
| -------------------------------------- | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Streambar HTTP (klient, rekommenderas) | `http://localhost:20128/api/mcp/stream` | Den slutpunkt som nuvarande MCP klienter pratar med.                                                                                |
| Legacy SSE singleton                   | `http://localhost:20128/api/mcp/sse`    | Äldre singeltransport. Det** stänger** streambara sessioner; använd `streamable-http` klienter mot `/api/mcp/stream`, inte den här. |
| stdio                                  | `omniroute --mcp`                       | För IDE MCP config som skapar processen. Det finns ingen `--dev` flagga; `omniroute --mcp` är ingångspunkten för stdio.             |

### Lagringsnivåer (det som överlever en omstart)

CCR är en** två skikt** butik, inte bara i minnet:

- **Het minnesnivå** — per block cap 2 MiB, per-principal 16 MiB, global 64 MiB. Poster som standard är 24 h TTL (max 7 dagar). Full MCP -hämtning från minnet är begränsad till 256 KiB; allt större är fortfarande tillgängligt via avstånds-/grep-lägena.
- **Slitstark SQLite tier** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, på som standard) — backar minnesnivån så att ett block överlever LRU vräkning, en omstart eller en återhämtning som landar på en annan instans. Raden behåller blockets TTL, så ett block förbi dess TTL är borta från båda nivåerna.

Tre skydd håller den hållbara nivån avgränsad — ett block förblir endast minne när:

1. blocket är över** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. körtiden är en molntid (ingen lokal disk);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Så "blocket försvann" är inte en generell omstartshistoria: ett sub-512 KB block på en lokal körtid utan moln överlever en omstart via den hållbara nivån tills dess TTL tar slut. Se [miljöreferens](../reference/ENVIRONMENT.md) för variabeln.

### De två markörerna

| Markör                                | Menande                                                                                                                                                     | Vad modellen ska göra                                                                                                                                                                                                         |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Ett stort block lagrades innehållsadresserat.                                                                                                               | Ring `omniroute_ccr_retrieve` med** 24-hex hash kopierad ordagrant** för att få tillbaka originaltexten.                                                                                                                      |
| `[dedup:ref sha=…]`                   | `session-dedup` elided text som redan skickats i en tidigare tur av samma session. Detta är en** avsiktlig tillbakablick** , inte en förlust eller ett fel. | Do** inte** ring vilket verktyg som helst och gör** inte** försök att "rekonstruera" det. Den första förekomsten av texten är den kanoniska kopian; den aktuella svängen skrivs aldrig om, den deduperas vid en senare sväng. |

`[dedup:ref]` -tillbakablicken är ett avsiktligt protokollbeslut — det finns ingen pre-send-rekonstruktion. Behandla det som "exakt den här texten fanns redan på tråden tidigare under den här sessionen."

### Kundens förutsättningar

- **Nyckel (stdio):** en stdio-anropare har ingen identitet per begäran, så den autentiserar med `OMNIROUTE_API_KEY` (inställd i MCP -serverns `env`). Utan den är den som ringer anonym och verktyg som kräver en huvudman kan försämras.
- **`tools[]` är injektionsförutsättningen.** CCR -hämtningsprotokollinstruktionen (#8033) injiceras** endast** när begärans annonserade `tools[]` bevisar att klienten faktiskt kan nå `omniroute_ccr_retrieve`. Matchningen är en efterföljande segmentmatchning avgränsad av en separator (`__`, `.`, `/`, `:`) — aldrig en blottad delsträng — så ett namnavgränsat namn som `mcp__gateway__omniroute_ccr_retrieve` räknas fortfarande. En frånvarande eller icke-matchande `tools[]` betyder att instruktionen _inte_ injiceras, av design.
- **`codemode:false` (OpenCode klienter).** OpenCode har som standard kodläge, som endast annonserar sina ursprungliga verktyg till modellen och** inte** sätt MCP verktyg på den inbyggda `tools[]` listan. Ställ in `codemode: false` på MCP serverposten så att `omniroute_ccr_*` verktygen annonseras. Detta är en** klient** inställning, inte en OmniRoute. Den får inte CCR instruktionen injicerad än: OpenCode namnger ett verktyg `<server>_<tool>`, så en server som heter `omniroute` exponerar `omniroute_omniroute_ccr_retrieve`, och `_` är inte en av de matchade separatorerna.
- **Rektorer.** Lagring och hämtning är isolerade per autentiserad principal (per API nyckel). En nyckel ser bara sina egna block.

### Omfattningar per verktyg

Tillämpning av räckvidden är alltid på för HTTP/SSE -anropare med snäv omfattning. `omniroute_` CCR verktygen kräver:

| Verktyg                  | Omfattning          |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

En saknad scope returnerar en**MCP verktygsfel resultat** (`isError: true`, inte en HTTP 403 — `403 LOCAL_ONLY` är den separata loopback route-guard auth): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` En minimal fjärrnyckel kan hålla `mcp:connect` (godkänner `/api/mcp/` lokal-endast utskärning) plus det specifika read/write scope den behöver.

### Klientmatris

| Klient            | Transport                                    | Konfiguration att använda                                                                                                                                                                                                                                  | `tools[]` annonseras? (→ CCR instruktion injicerad)                                                                                                                                                              |
| ----------------- | -------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kod        | streambar-http                               | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                          | Ja — MCP-kompatibel; injiceras.                                                                                                                                                                                  |
| Cursor / Cline    | `stdio`** eller** `streamable-http`          | stdio: `omniroute --mcp` med `OMNIROUTE_API_KEY` i `env`; eller en fjärransluten MCP -ingång som pekar på `http://localhost:20128/api/mcp/stream` (se [Installationsguide → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Ja — annonsera `omniroute_ccr_*` verktygen.                                                                                                                                                                      |
| OpenCode          | streambar-http                               | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` plus `codemode: false`                                                                                                                                                            | Verktyg som endast annonseras med `codemode: false`; instruktionen är fortfarande inte injicerad, eftersom `omniroute_omniroute_ccr_retrieve` inte matchar (se [Klientförutsättningar](#client-prerequisites) ). |
| OpenAI-kompatibel | OpenAI-kompatibel HTTP (chatkompletteringar) | standard chat-completions-klient mot den OpenAI-kompatibla slutpunkten                                                                                                                                                                                     | **Aldrig** — en vanlig OpenAI-kompatibel anropare blir aldrig tillsagd att ringa verktyget, och instruktionen injiceras inte.                                                                                    |

### Hämtningsgränser & paginering

MCP -verktygets textresultat klipps runt `mcpAccessibility.maxTextChars` (standard `50000`). En `full` -hämtning av ett block är begränsad till 256 KiB —** det finns ingen obegränsad fullständig återhämtning** . När ett blocks `chars=N` är stort, bläddra det istället för att dra det hela:

- Tumregel:**`chars > 40000` → använd en `mode`** , aldrig en bar full.
- `mode:"grep"` — regex `pattern` matchade rad för rad, upp till 1 000 matchande rader (`unique: true` tappar upprepningar), billigast för "hitta den rad jag behöver."
- `mode:"lines"` — ett 1-indexerat linjeintervall; behöver både `start` och `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` linjer.
- `mode:"stats"` — rad, tecken och byte räknas utan kroppen.

Använd `mode:"lines"` med `start`/`end` för att gå ett långt block i sidor istället för att begära allt på en gång.

### Namngivning av verktyg

Hämtningsverktyget heter för närvarande `omniroute_ccr_retrieve` ( `omniroute_` prefixet är en daterad lösning för namnkollisioner över servrar). Ett renare bounded-suffix-verktygsnamn och en fix för MCP JSON resultat trunkerad mittsträng spåras som uppströmsuppföljningar; den här sidan dokumenterar endast det aktuella, skickade beteendet.

### Sessionens livscykel

Streamable-HTTP-sessioner tar slut och servern skördar dem; det inaktiva fönstret är `MCP_SESSION_IDLE_MS` konstanten (referens med namn, inte ett hårdkodat värde, så den här sidan glider inte när den ändras). Symptomet på en inaktiv session är en HTTP 404 med `Unknown Mcp-Session-Id` — botemedlet är att återansluta eller starta om sessionen,** inte** för att rotera en nyckel, ändra ett omfång eller byta namn på ett verktyg.

## API yta

| Rutt                                   | Ändamål                                                                   |
| -------------------------------------- | ------------------------------------------------------------------------- |
| `/api/settings/compression`            | Globala komprimeringsinställningar (inkluderar `mcpAccessibility` config) |
| `/api/compression/preview`             | Förhandsgranska valfritt komprimeringsläge                                |
| `/api/compression/language-packs`      | Lista tillgängliga Caveman-språkpaket                                     |
| `/api/context/caveman/config`          | Caveman inställningar alias                                               |
| `/api/context/rtk/config`              | RTK standardinställningar och inställningar                               |
| `/api/context/rtk/filters`             | RTK filterkatalog                                                         |
| `/api/context/rtk/test`                | RTK preview/test slutpunkt                                                |
| `/api/context/rtk/raw-output/[id]`     | Autentiserad redigerad återställning av rå-output                         |
| `/api/context/combos`                  | Kompressionskombo CRUD                                                    |
| `/api/context/combos/[id]/assignments` | Routing-combo tilldelning CRUD                                            |
| `/api/context/analytics`               | Kompressionsanalysalias                                                   |

Hanteringsvägar kräver hanteringsautentisering eller API-nyckelkontroller.

## MCP Verktyg

Kompression avslöjar fem MCP verktyg:

| Verktyg                             | Omfattning          | Ändamål                                 |
| ----------------------------------- | ------------------- | --------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Inställningar, analyser, cachestatistik |
| `omniroute_compression_configure`   | `write:compression` | Uppdatera globala inställningar         |
| `omniroute_set_compression_engine`  | `write:compression` | Ställ in läge och valfri pipeline       |
| `omniroute_list_compression_combos` | `read:compression`  | Lista kompressionskombinationer         |
| `omniroute_compression_combo_stats` | `read:compression`  | Läs combo/engine analytics              |

## Omfattning & undantag

**Inbäddningar komprimeras aldrig.** `open-sse/handlers/embeddings.ts` kallar aldrig någon kompressionsmotor — request/response kropparna passerar direkt till exekutorn orörda. Detta är strukturellt idag (inbäddningar och chattavslut är osammanhängande hanterare), inte en körtidskontroll, men det betyder att vektordistorsionsproblemet i #8034 inte har någon exponeringsyta i inbäddningsvägen.

**Per-model/endpoint exkluderingsfilter (#8034).** För chattslutföranden kan en operatör namnge modell-ID/ `provider/model` -mål som aldrig får komprimeras — ett skyddsräcke användbart om komprimering någonsin kopplas närmare en inbäddningsväg intill, och generellt användbar för alla modeller vars exakta byte-för-byte-prompt spelar roll (deterministiska evaler, cachekänsliga prefix, etc.).

- Inställningsfält: `exclusions?: string[]` på den globala komprimeringskonfigurationen (`GET`/`PUT /api/settings/compression`), kvarstår via den befintliga `key_value` -komprimeringsnamnrymden (`src/lib/db/compression.ts`) — ingen ny tabell.
- Dashboard-flik:** Dashboard → Komprimering → Exklusioner** (`/dashboard/compression/exclusions`).
- Mönstersyntax: `*` är det enda jokertecken. Varannan regex-metatecken i ett mönster escapes före matchning, så `gpt-5.6` matchar endast den bokstavliga strängen, aldrig `gpt-5x6` (ReDoS-safe, bounded, inga kapslade kvantifierare). Mönster matchar skiftlägesokänsligt mot både det blotta modell-id:t och `provider/model` -kompositen — `gpt-5-6`, `openai/gpt-5-6` och `openai/*` fungerar alla, och enbart `*` utesluter varje modell.
- Matchande: `isCompressionExcluded()` / `normalizeCompressionExclusions()` i `open-sse/services/compression/exclusions.ts`. `chatCore.ts` kontrollerar det uteslutna målet direkt efter att ha löst komprimeringsinställningarna,** innan någon motor går** , och behandlar en matchning exakt som att komprimering är globalt inaktiverad — förfrågningskroppen är bevisligen byte-identisk. Överhoppningen spelas in via `writeCompressionSkip(..., "excluded")` för analyssynlighet.
- Standard (empty/absent lista): identisk med beteendet före #8034 — ingenting är uteslutet.

## Kända begränsningar

- **LLMLingua-2 (SLM) kräver samlokaliserade valfria deps.** Arbetaren kör bara i en produktionsbyggnad när `@atjsh/llmlingua-2` + peers är samlokaliserade i `dist/node_modules` (se `scripts/build/colocateOptionals.mjs`, #4286). Utan dem öppnar motorn fel (returnerar originaltexten). Arbetarupplösningen beror inte längre på `import.meta.url` (den dör i det fristående paketet) — det förankras på runtime cwd / `argv[1]`.
- **Caveman språkpaket `de` / `fr` / `ja` är partiella.** De skickar `context` + `filler` + `structural` regler men inga `dedup` / `ultra` paket, så `ultra` intensiteten är inte starkare än `full` för dessa språk (de använder bara sina egna regler — det finns ingen tyst återgång till de engelska `dedup`/`ultra` -reglerna, vilket skulle mangla utländsk text). `en` / `es` / `id` / `pt-BR` är klara. Bidrag av `dedup.json` + `ultra.json` för delpaketen är välkomna.
- **Staplad telemetri listar bara motorer som har komprimerats.** Ett steg med staplade rörledningar vars motor gick men gav 0 % besparingar ger `stats:null` och visas därför inte i `engineBreakdown` — som inte kan skiljas från ett steg som hoppades över. Att skilja "kör, 0 %" från "hoppad" skulle kräva en förändring av nedbrytningsmodellen och skjuts upp.

## Godkännande

De fokuserade portarna för detta område är:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
