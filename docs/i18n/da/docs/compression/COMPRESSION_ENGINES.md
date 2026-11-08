# Compression Engines (Dansk)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompression er bygget op omkring motorkontrakter. En tilstand kan køre én motor direkte (`caveman` eller `rtk`) eller en deterministisk stablet pipeline, der udfører flere motorer i rækkefølge.

## Tilstande

| Mode         | Motorvej                                                                                | Tilsigtet input                                         |
| ------------ | --------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| `off`        | ingen                                                                                   | Præcis hurtig bevaring                                  |
| `lite`       | Caveman lite hjælpere                                                                   | Altid oprydning med lav risiko                          |
| `standard`   | Hulemand                                                                                | Naturlig sprog prompt kondensering                      |
| `aggressive` | Caveman + history/tool opsummerere                                                      | Lange chatsessioner                                     |
| `ultra`      | Caveman + beskæringshjælpere                                                            | Gendannelse af kontekstgrænse                           |
| `rtk`        | RTK                                                                                     | Terminal, shell, build, test og git output              |
| `omniglyph`  | OmniGlyph                                                                               | Kontekst-som-billede på den oprindelige udbyder-ledning |
| `stacked`    | Rørledning. Standardanmodningen er `session-dedup -> lite`. `rtk -> caveman` er opt-in. | Blandede værktøjslogs og prosa, max besparelser         |

### OmniGlyph kompressionsprofiler

`omniglyph` motoren (pakke `omniglyph`, 1.4.0 +) accepterer en navngivet semantisk profil, indstillet globalt gennem `omniglyph.profile` i kompressionsindstillingerne eller pr. trin gennem den stablede pipelines trinkonfiguration:

| Profil        | Grænse                                                                                                               |
| ------------- | -------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Misligholdelse. Politikken de offentliggjorte kvitteringer målte — -billedsystem, værktøjsdokumenter og tæt historie |
| `balanced`    | Holder live state native, beskytter de sidste 8 drejninger, kollapser ældre lukket historie                          |
| `coding-safe` | Bevarer autoritet, værktøjsskemaer og live værktøjsoutput native, beskytter de sidste 12 drejninger                  |
| `passthrough` | Ruter uden transformation; motoren springes over                                                                     |

Profilen er en** loft, ikke et gulv** : `mergeCompressionProfileOptions` i pakken nægter at lade en opkalds tilsidesætte genåbne en tabsgivende bane profilen lukket, så en per-trin `preserveSystemPrompt: false` kan ikke genaktivere systemkomprimering under `coding-safe`.

Målt på denne kodebase: `coding-safe` og `balanced` hæver `minCompressChars` til sit maksimum og beholder system, værktøjsskemaer og værktøjsresultater native, så en session, der endnu ikke har akkumuleret historie, stopper ved `below_min_chars`, og motoren transformerer intet. Derfor er standarden `aggressive` i stedet for den sikreste profil.

Pakken løser sit eget modelomfang og profil fra sin miljøkonfiguration. OmniRoute uddelegerer aldrig beslutningen: Adapteren fastgør modelporten til pakkens mest restriktive omfang, så værtsmiljøindstillinger kan kun indsnævre tilladelseslisten, aldrig udvide den forbi OmniRoute målte kvitteringer.

## Motorregister

Registret bor i `open-sse/services/compression/engines/registry.ts`. Motorer afslører en delt kontrakt:

- `id`: stabilt motor-id såsom `caveman` eller `rtk`
- `apply(text, config)`: ældre eksekveringssti brugt af stablede pipelines
- `compress(input, config)`: primær udførelsessti, der returnerer tekst + -statistik
- `getConfigSchema()`: returnerer den JSON-skema-lignende form af gyldig konfiguration
- `validateConfig(config)`: returnerer `{ valid, errors[] }`

Registrering bruger `registerCompressionEngine(engine)` (eller `registerEngine` for avancerede tilfælde), som kalder `assertValidEngine()` og `validateConfig(defaultConfig)` før accept. Brug `unregisterCompressionEngine(id)` til at fjerne en motor under drift.

`strategySelector.ts` registrerer de indbyggede motorer, før kompressionen kører. Dette lader forhåndsvisning, runtime-komprimering, stablet tilstand, tests og fremtidige motorer bruge den samme eksekveringssti.

### MCP beskrivelse komprimering (relateret)

Et separat register komprimerer metadata MCP -værktøjsbeskrivelse på registreringsniveau — se `open-sse/mcp-server/descriptionCompressor.ts` og [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Det genbruger Caveman-regler, men opererer på værktøjsmetadata, ikke anmodningsnyttelast.

### Ekstra indbyggede motorer

Ud over Caveman, RTK og LLMLingua-2 sender registreringsdatabasen adskillige specialiserede tabsfrie/strukturelle motorer (brugt af stablede rørledninger, legepladsen og tests):

| Motor         | Id              | Hvad den gør                                                                                                                                                                  |
| ------------- | --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): erstatter store sammenhængende tekstblokke med indholdsadresserede referencer, så repeated/large blokke sendes én gang og refereres derefter. |
| frihøjde      | `headroom`      | SmartCrusher (H3 + N5): tabsfri tabelkomprimering af homogene JSON-array-nyttelaster til en søjleformet `[N rows]` form.                                                      |
| ionisator     | `ionizer`       | Head/middle/tail række prøvetagning for meget store homogene blokke, lagring af den eliderede midte som en CCR indholdsadresseret reference.                                  |
| session-dedup | `session-dedup` | Indholdsadresseret cross-turn deduplication (TokenMizer-inspireret): fjerner tekst, der allerede er set i tidligere vendinger i samme session.                                |

**CCR retrieve-protokol instruktion (#8033):** første gang CCR erstatter ≥ 1 blok i en anmodning, sætter motoren en enkelt, idempotent `system` -meddelelse (førende med `[CCR protocol]` vagtposten), der lærer den, der ringer, markøren → værktøjskontrakten: hvad en `[CCR retrieve hash=<24hex> chars=N]` markør betyder, at hashen skal kopieres ordret (alle 24 hex-tegn — fejlkopier er sandsynligt årsagen til, at der ikke er fundet en fejl-kopi) `[dedup:ref sha=...]` markør betyder "se tilbage i historien", ikke "kald værktøjet". Sedlen er injiceret** kun når opkalderens annoncerede `tools[]` beviser, at den faktisk kan nå `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — en almindelig OpenAI-kompatibel opkalder uden det værktøj modtager aldrig en instruktion om at kalde noget, den ikke kan nå. Idempotens håndhæves ved at scanne beskedhistorikken for vagtposten før indsprøjtning, så multi-turn-anmodninger (som afspiller tidligere beskeder) stables ikke sedlen én gang pr.

## Hulemand

Caveman-tilstand fokuserer på semantisk kondensering af normal prosa:

- bevarer kodeblokke, URLs, JSON, stier og strukturerede data
- fjerner fyldstof, afdækning, gentagen kontekst og verbose bindende frasering
- understøtter sprogbevidste filregelpakker i `open-sse/services/compression/rules/`
- forbliver tilgængelig gennem de ældre tilstande `standard`, `aggressive` og `ultra`

Instrumentbrættets overflade er `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream rapporterer `~75%` færre output-tokens, `65%` gennemsnitlige outputbesparelser i benchmarks med et `22-87%` område og et `~46%` input-komprimeringsværktøj. OmniRoute bruger Caveman input-side-nummeret, når de dokumenterer stablede prompt/context besparelser; Caveman-outputtilstand forbliver en separat respons-adfærdsfunktion.

## RTK

RTK tilstand fokuserer på kommando- og værktøjsoutput:

- registrerer outputklasser såsom `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go tests, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, stack traces og generiske logfiler
- anvender 49 JSON -filtre fra `open-sse/services/compression/engines/rtk/filters/`
- understøtter den deklarative pipeline i RTK-stil: ANSI stripping, replace, match-output kortslutning, strip/keep linjer, per-line trunkering, head/tail/max-line trunkering og on-empty fallback
- understøtter trust-gated projektfiltre i `.rtk/filters.json` og globale filtre i `DATA_DIR/rtk/filters.json`
- stripper ANSI sekvenser, fremskridtsstøj, gentagne linjer og uhensigtsmæssig kedelplade
- bevarer handlingsbare fejl, advarsler, oversigter, ændrede filer og halekontekst
- kan valgfrit beholde redigeret rå output for recovery/debugging gennem autentificerede administrationsruter

Instrumentbrættets overflade er `Dashboard -> Context & Cache -> RTK`.

Driftsdetaljer for brugerdefinerede filtre, tillid, verifikation og gendannelse af rå-output live i [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream rapporterer `60-90%` besparelser for kommando-output-komprimering. Dens README eksempel viser en 30-minutters Claude Code-session, der går fra `~118,000` tokens til `~23,900`, eller `79.7%` gemt.

## LLMLingua-2 (semantisk beskæring)

LLMLingua-2 tilstand udføres** semantisk token beskæring** om prosa ved hjælp af en lille ONNX -tokenklassificering, der komplementerer de regelbaserede Caveman- og RTK -motorer:

- komprimerer kun prosa i ikke-systemmeddelelser; indhegnede kodeblokke og andre bevarede konstruktioner ændres aldrig
- kører `@atjsh/llmlingua-2` backend (ONNX via `@huggingface/transformers`) i en arbejdstråd, så modelinferens blokerer aldrig anmodningshændelsesløkken
- er** stabelbar** (`stackPriority` 35): i en stablet pipeline kører den efter de strukturelle motorer (CCR, session-dedup, headroom, Caveman) men før `ultra`, da semantisk beskæring er mest effektiv på allerede strukturelt komprimeret tekst — f.eks. `rtk -> caveman -> llmlingua`
- **fejl-åbner ved enhver fejl** (mangler valgfri deps, worker spawn, model load, inferens eller timeout) → den originale tekst returneres uændret, aldrig en fejl

Motorplacering: `open-sse/services/compression/engines/llmlingua/`. Instrumentbrættets overflade er `Dashboard -> Context & Cache -> LLMLingua`.

### Modeller

Standardmodellen er**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, hurtig). En højere nøjagtighed** BERT-base** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) er tilgængelig via motorkonfigurationsfeltet `model`. `@huggingface/transformers` downloader den valgte model dovent fra HuggingFace Hub til `${DATA_DIR}/models/llmlingua` ved det første opkald (`modelStore.ts`); en `modelPath` -konfigurationstilsidesættelse peger den på en lokal kopi i stedet for (offline/installationer uden luft).

### Valgfri afhængigheder og on-demand installation

Den beskærbare LLMLingua runtime peer-stack er** valgfri** . To pakker er erklæret som `optionalDependencies` i `package.json` og opbevares** ydre** af produktionsbygningen (`scripts/build/prepublish.ts` samler dem ikke):

| Pakke                | Version (pin) | Noter                                             |
| -------------------- | ------------- | ------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`       | Indgangspakke; erklærer de andre som jævnaldrende |
| `js-tiktoken`        | `^1.0.20`     | Tokenizer                                         |

`@huggingface/transformers` er fastgjort til `^4.2.0` (delt med den lokale indlejringssti og spores også ind i det selvstændige bundt); `@atjsh/llmlingua-2@2.0.5` peer på det med `"^3.5.2 || ^4.0.0"`, så både Transformers.js v3 og v4 er understøttet. Siden 2.0.4 kræver `@atjsh/llmlingua-2` ikke længere `@tensorflow/tfjs`, hvilket fjernede den største enkeltbidragyder (TensorFlow.js) fra SLM stakken. Kun de to ovenstående pakker kan beskæres SLM peers. En standard `npm install` (dev) installerer den valgfri stak automatisk, medmindre valgfrie afhængigheder udelades.

**Hvorfor on-demand:** den npm-publicerede pakke, den selvstændige pakke og Docker -billedskibet** uden** disse deps for at forblive slanke. Når de er fraværende, svigter arbejderens afhængighedsgate (en `@atjsh/llmlingua-2` resolve-probe i `worker.ts`), og motoren** fejl-åbner lydløst** — at vælge LLMLingua bliver en no-op (tekst returneres uændret, ingen fejl logget). For at aktivere det i et beskåret miljø skal du installere den valgfri stak:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` fjernelsen (2.0.4 +) eliminerer den tidligere dominerende ~ 800 MB bidragyder — det resterende fodaftryk er transformers.js + onnxruntime-node runtimes, plus TinyBERT modellen (~ 57 MB) downloadet ved første brug (ikke via npm).

Per miljø:

- **Dev / `npm install`** — installeres automatisk, medmindre du har bestået `--omit=optional` (eller `--no-optional`). Ingen handling nødvendig.
- **Global npm (`npm i -g omniroute`) / standalone** — kør installeringskommandoen ovenfor inde i den installerede pakkemappe, eller geninstaller uden at udelade valgfri deps.
- **Docker** — tilføje installationskommandoen i et afledt billedlag; det offentliggjorte billede er slankt af designet.
- **VPS (PM2)** — installer i appens `node_modules`, og genstart derefter processen, så arbejderen undersøger porten igen.
- **Raw Next selvstændig (`npm run build` → `.build/next/standalone/server.js`)** — den selvstændige sporing sendes NEITHER arbejderen eller de valgfri deps, så motoren stille fejl-åbner. `scripts/build/colocate-standalone.mjs` genanvender begge (worker esbuild + optional-dep lukning i det selvstændige træ); den kører automatisk via `postbuild` npm hook efter hver build. Idempotent, fejl-blød, når deps er fraværende.

**Bekræft, at den er aktiv:** med LLMLingua valgt, krymper ægte prosa faktisk (motoren stopper med at åbne fejl), og den første anmodning udløser modeldownload til `${DATA_DIR}/models/llmlingua`. Porten sonderer med vilje kun `@atjsh/llmlingua-2` — de andre peers er ESM-only og `require.resolve` kaster på dem, selv når de er til stede — så arbejderen stadig fejl-åbner, hvis nogen peer virkelig mangler på `import()` tidspunktet.

## Stablede rørledninger

Stablet tilstand kører pipeline-trin i rækkefølge. Standard er:

```txt
rtk -> caveman
```

Brug dette til kodningsagentsessioner, hvor en prompt kombinerer kommandooutput med menneskelig eller assistentprosa. RTK reducerer først støjende værktøjslogfiler, derefter komprimerer Caveman det resterende naturlige sprog.

Pipeline-trin konfigureres med `stackedPipeline` i kompressionsindstillinger eller gennem kompressionskombinationer.

Når begge motorer reducerer den samme kvalificerede nyttelast, vil besparelserne være:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Tilgængelighedstræfilter

MCP accessibility-tree smart filter er et post-execution komprimeringslag, der kører på MCP** værktøjs resultater** , ikke på prompter eller kontekst. Det er rettet mod det udførlige tilgængelighedstræ og browser-snapshot-nyttelast, der returneres af værktøjer som Playwright, computerbrug og browser-automatisering MCP servere.

### Hvad den gør

1. **Støjfjerning** — fjerner tomme generic/text indgange (`- generic:`, `- text: ""`)
2. **Søskende falder sammen** — når ≥ `collapseThreshold` (standard 30) fortløbende linjer er strukturelle gentagelser, kollapser dem i de første `collapseKeepHead` (standard 10) linjer + en optællingsoversigt + de sidste `collapseKeepTail` (standard 5) linjer
3. **Ref konservering** — `[ref=eXX]` -ankre, der kræves af Playwright/computer-use røres aldrig
4. **Hård afskæring** — hvis teksten efter sammenbrud stadig overstiger `maxTextChars` (standard 50.000), afkortes med et navigationstip, så agenten kan fortsætte med at arbejde

### Motorens placering

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfiguration

Styret af `compression.mcpAccessibility` i globale indstillinger (migrering 056). Standard konfiguration:

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

Filteret anvendes kun på værktøjsresultatnyttelast, hvis `type` er `"text"`, og hvis længde overstiger `minLengthToProcess`. Det påvirker ikke promptkomprimering eller anmodningsnyttelast.

### Forventet besparelse

60–80 % på resultaterne af browsersnapshotværktøjer, afhængigt af sidens kompleksitet. Kollapsalgoritmen er O(n) i linjeantal og tilføjer ubetydelig latenstid.

### Dette filter kontra kompressionsmotorerne ovenfor

| Aspekt    | Hulemand / RTK / Stablet            | MCP tilgængelighedsfilter              |
| --------- | ----------------------------------- | -------------------------------------- |
| Mål       | Request prompts / kontekst          | MCP værktøj resultater                 |
| Udløser   | Indstilling af kompressionstilstand | `compression.mcpAccessibility.enabled` |
| Omfang    | Alle SSE beskeder                   | Kun værktøjsresultater                 |
| Ref ankre | N/A                                 | Bevares ubetinget                      |

---

## Kompressionskombinationer

Kompressionskombinationer er navngivne kompressionsprofiler, der kan tildeles til routingkombinationer:

- `compression_combos`: gemmer tilstand, pipeline, RTK config, sprog config og standardmarkør
- `compression_combo_assignments`: kortlægger en kompressionskombination til en routingkombination
- Runtime-integration løser en tildelt kompressionskombination før generisk kombination tilsidesætter
- analyser omfatter `compression_combo_id` og `engine`

Dashboard overflade: `Dashboard -> Context & Cache -> Compression Combos`.

## Forudsætninger / operatørvejledning (CCR & session-dedup)

CCR (`ccr`) og `session-dedup` erstatter eller fjerner tekst og efterlader en** markør** bagved. Dette afsnit er operatørreferencen til at tilslutte en klient, læse de to markører og hente eller diagnosticere det fjernede indhold. Mekanik af hver motor er dækket ovenfor; dette er laget "hvordan kører jeg det".

### Transporter og endepunkter

MCP serveren, der afslører CCR værktøjerne, kan nås på tre måder. Standardbasen URL er `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transportere                       | URL / kommando                          | Noter                                                                                                                              |
| ---------------------------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Streambar HTTP (klient, anbefales) | `http://localhost:20128/api/mcp/stream` | Det slutpunkt, de nuværende MCP klienter taler med.                                                                                |
| Legacy SSE singleton               | `http://localhost:20128/api/mcp/sse`    | Ældre singleton transport. Det** lukker** streambare sessioner; brug `streamable-http` klienter mod `/api/mcp/stream`, ikke denne. |
| stdio                              | `omniroute --mcp`                       | For IDE MCP config, der afføder processen. Der er ikke noget `--dev` flag; `omniroute --mcp` er stdio-indgangspunktet.             |

### Lagerniveauer (hvad overlever en genstart)

CCR er en** to-lags** butik, ikke kun i hukommelsen:

- **Hot in-memory tier** — pr. blok hætte 2 MiB, pr. hovedstol 16 MiB, global 64 MiB. Indgange er som standard en 24 h TTL (maksimalt 7 dage). Fuld MCP -hentning fra hukommelsen er begrænset til 256 KiB; alt større er stadig tilgængeligt gennem ranged / grep-tilstandene.
- **Holdbar SQLite tier** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, tændt som standard) — bakker hukommelsesniveauet, så en blok overlever LRU eviction, en genstart eller en retrieve-landing på en anden instans. Rækken beholder blokkens TTL, så en blok forbi dens TTL er væk fra begge niveauer.

Tre vagter holder den holdbare tier afgrænset — en blok forbliver kun hukommelse, når:

1. blokken er forbi** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. runtime er en cloud runtime (ingen lokal disk);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Så "blokken forsvandt" er ikke en generel genstartshistorie: en sub-512 KB blok på en lokal, ikke-sky-runtime overlever en genstart via det holdbare niveau, indtil dens TTL løber tør. Se [miljøreference](../reference/ENVIRONMENT.md) for variablen.

### De to markører

| Markør                                | Mening                                                                                                                                                       | Hvad modellen skal gøre                                                                                                                                                                                      |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `[CCR retrieve hash=<24hex> chars=N]` | En stor blok blev lagret indholdsadresseret.                                                                                                                 | Ring til `omniroute_ccr_retrieve` med** 24-hex hash kopieret ordret** for at få den oprindelige tekst tilbage.                                                                                               |
| `[dedup:ref sha=…]`                   | `session-dedup` slettet tekst, der allerede er sendt i en tidligere omgang i samme session. Dette er en** bevidst tilbageblik** , ikke et tab eller en fejl. | Gør** ikke** ring til ethvert værktøj og gør** ikke** prøv at "rekonstruere" det. Den første forekomst af teksten er den kanoniske kopi; den aktuelle tur omskrives aldrig, den deduperes ved en senere tur. |

`[dedup:ref]` -tilbageblikket er en bevidst protokolbeslutning — der er ingen rekonstruktion på forhånd. Behandl det som "denne præcise tekst var allerede på ledningen tidligere i denne session."

### Kundens forudsætninger

- **Nøgle (stdio):** en stdio-opkalder har ingen identitet pr. anmodning, så den godkendes med `OMNIROUTE_API_KEY` (indstillet i MCP -serverens `env`). Uden den er den, der ringer, anonym, og værktøjer, der kræver en rektor, kan forringes.
- **`tools[]` er injektionsforudsætningen.** CCR retrieve-protokol-instruktionen (#8033) injiceres** kun** når anmodningens annoncerede `tools[]` beviser, at klienten faktisk kan nå `omniroute_ccr_retrieve`. Matchet er et efterfølgende segment-match afgrænset af en separator (`__`, `.`, `/`, `:`) — aldrig en blottet understreng — så et navneinddelt navn som `mcp__gateway__omniroute_ccr_retrieve` tæller stadig. En fraværende eller ikke-matchende `tools[]` betyder, at instruktionen er _ikke_ injiceret, designmæssigt.
- **`codemode:false` (OpenCode klienter).** OpenCode er som standard kodetilstand, som kun annoncerer dets oprindelige værktøjer til modellen og** gør ikke** sæt MCP værktøjer på den oprindelige `tools[]` liste. Indstil `codemode: false` på MCP serverposten, så `omniroute_ccr_*` værktøjerne annonceres. Dette er en** klient** indstilling, ikke en OmniRoute. Den får ikke CCR instruktionen injiceret endnu: OpenCode navngiver et værktøj `<server>_<tool>`, så en server kaldet `omniroute` eksponerer `omniroute_omniroute_ccr_retrieve`, og `_` er ikke en af de matchede separatorer.
- **Rektorer.** Opbevaring og hentning er isoleret pr. godkendt principal (pr. API nøgle). En nøgle ser kun sine egne blokke.

### Omfang pr. værktøj

Håndhævelse af omfanget er altid aktiveret for HTTP/SSE opkaldere med snævert omfang. `omniroute_` CCR -værktøjerne kræver:

| Værktøj                  | Omfang              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Et manglende omfang returnerer en**MCP værktøj fejl resultat** (`isError: true`, ikke en HTTP 403 — `403 LOCAL_ONLY` er den separate loopback route-guard auth): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` En minimal fjernnøgle kan holde `mcp:connect` (autoriserer `/api/mcp/` lokal-kun udskæring) plus det specifikke read/write omfang, den har brug for.

### Klientmatrix

| Klient            | Transportere                              | Konfiguration til brug                                                                                                                                                                                                                                     | `tools[]` annonceret? (→ CCR instruktion indsprøjtet)                                                                                                                                                      |
| ----------------- | ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kode       | streambar-http                            | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                          | Ja — MCP-kompatibel; injiceret.                                                                                                                                                                            |
| Cursor / Cline    | `stdio`** eller** `streamable-http`       | stdio: `omniroute --mcp` med `OMNIROUTE_API_KEY` i `env`; eller en ekstern MCP indgang, der peger på `http://localhost:20128/api/mcp/stream` (se [Installationsvejledning → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Ja — reklamerer for `omniroute_ccr_*` værktøjerne.                                                                                                                                                         |
| OpenCode          | streambar-http                            | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` plus `codemode: false`                                                                                                                                                            | Værktøjer annonceret kun med `codemode: false`; instruktionen er stadig ikke injiceret, fordi `omniroute_omniroute_ccr_retrieve` ikke stemmer overens (se [Klientforudsætninger](#client-prerequisites) ). |
| OpenAI-kompatibel | OpenAI-kompatibel HTTP (chatafslutninger) | standard chat-afslutningsklient mod det OpenAI-kompatible slutpunkt                                                                                                                                                                                        | **Aldrig** — en almindelig OpenAI-kompatibel opkalder bliver aldrig bedt om at ringe til værktøjet, og instruktionen injiceres ikke.                                                                       |

### Hentningsgrænser og paginering

MCP -værktøjets tekstresultater klippes omkring `mcpAccessibility.maxTextChars` (standard `50000`). En `full` hentning af en blok er begrænset til 256 KiB —** der er ingen ubegrænset fuld hentning** . Når en bloks `chars=N` er stor, skal du bladre den i stedet for at trække det hele:

- Tommelfingerregel:**`chars > 40000` → brug en `mode`** , aldrig en bar fuld.
- `mode:"grep"` — regex `pattern` matchede linje for linje, op til 1.000 matchende linjer (`unique: true` drops gentagelser), billigste for "find den ene linje, jeg har brug for."
- `mode:"lines"` — et 1-indekseret linjeområde; har brug for både `start` og `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` linjer.
- `mode:"stats"` — linje, tegn og byte tæller uden brødteksten.

Brug `mode:"lines"` med `start`/`end` til at gå en lang blok i sider i stedet for at anmode om det hele på én gang.

### Navngivning af værktøj

Hentningsværktøjet hedder i øjeblikket `omniroute_ccr_retrieve` ( `omniroute_` præfikset er en dateret løsning for kryds-servernavnekollisioner). Et renere afgrænset suffiksværktøjsnavn og en rettelse for MCP JSON resultater trunkeret midtstreng spores som opstrøms opfølgninger; denne side dokumenterer kun den aktuelle, afsendte adfærd.

### Sessions livscyklus

Streambare-HTTP-sessioner går i tomgang, og serveren høster dem; det inaktive vindue er `MCP_SESSION_IDLE_MS` konstanten (refereret til ved navn, ikke en hårdkodet værdi, så denne side driver ikke, når den ændres). Symptomet på en inaktiv session er en HTTP 404 med `Unknown Mcp-Session-Id` — midlet er at genoprette forbindelsen eller genstarte sessionen,** ikke** for at rotere en nøgle, ændre et omfang eller omdøbe et værktøj.

## API overflade

| Rute                                   | Formål                                                                    |
| -------------------------------------- | ------------------------------------------------------------------------- |
| `/api/settings/compression`            | Globale komprimeringsindstillinger (inkluderer `mcpAccessibility` config) |
| `/api/compression/preview`             | Se forhåndsvisning af enhver komprimeringstilstand                        |
| `/api/compression/language-packs`      | Liste over tilgængelige Caveman-sprogpakker                               |
| `/api/context/caveman/config`          | Caveman indstillinger alias                                               |
| `/api/context/rtk/config`              | RTK standarder og indstillinger                                           |
| `/api/context/rtk/filters`             | RTK filter katalog                                                        |
| `/api/context/rtk/test`                | RTK preview/test slutpunkt                                                |
| `/api/context/rtk/raw-output/[id]`     | Autentificeret redigeret raw-output-gendannelse                           |
| `/api/context/combos`                  | Kompression combo CRUD                                                    |
| `/api/context/combos/[id]/assignments` | Routing-combo tildeling CRUD                                              |
| `/api/context/analytics`               | Kompressionsanalysealias                                                  |

Administrationsruter kræver administrationsgodkendelse eller kontrol af API-nøgler.

## MCP værktøj

Kompression afslører fem MCP værktøjer:

| Værktøj                             | Omfang              | Formål                                   |
| ----------------------------------- | ------------------- | ---------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Indstillinger, analyser, cache-statistik |
| `omniroute_compression_configure`   | `write:compression` | Opdater globale indstillinger            |
| `omniroute_set_compression_engine`  | `write:compression` | Indstil tilstand og valgfri pipeline     |
| `omniroute_list_compression_combos` | `read:compression`  | Liste kompressionskombinationer          |
| `omniroute_compression_combo_stats` | `read:compression`  | Læs combo/engine analytics               |

## Omfang og undtagelser

**Indlejringer komprimeres aldrig.** `open-sse/handlers/embeddings.ts` kalder aldrig nogen kompressionsmotor — request/response kroppene passerer direkte til udføreren uberørt. Dette er strukturelt i dag (indlejringer og chat-afslutninger er usammenhængende behandlere), ikke et runtime-tjek, men det betyder, at vektor-forvrængningsproblemet i #8034 ikke har nogen eksponeringsoverflade i indlejringsstien.

**Per-model/endpoint ekskluderingsfilter (#8034).** Til chat-afslutninger kan en operatør navngive model-id'er / `provider/model` -mål, der aldrig må komprimeres — et autoværn, som er nyttigt, hvis komprimering nogensinde forbindes tættere på en indlejrings-tilstødende sti senere, og generelt nyttig for enhver model, hvis nøjagtige byte-for-byte-prompt har betydning (deterministiske evaler, cache-følsomme præfikser osv.).

- Indstillingsfelt: `exclusions?: string[]` på den globale komprimeringskonfiguration (`GET`/`PUT /api/settings/compression`), fortsatte via det eksisterende `key_value` -komprimeringsnavneområde (`src/lib/db/compression.ts`) — ingen ny tabel.
- Fanen Dashboard:** Dashboard → Kompression → Ekskluderinger** (`/dashboard/compression/exclusions`).
- Mønstersyntaks: `*` er det eneste jokertegn. Hvert andet regex-metategn i et mønster escapes før matchning, så `gpt-5.6` matcher kun den bogstavelige streng, aldrig `gpt-5x6` (ReDoS-safe, bounded, ingen indlejrede kvantifikatorer). Mønstre matcher uafhængigt af store og `provider/model` bogstaver mod både det blottede model-id og det sammensatte — `gpt-5-6`, `openai/gpt-5-6` og `openai/*` fungerer alle, og `*` alene udelukker hver model.
- Matchende: `isCompressionExcluded()` / `normalizeCompressionExclusions()` i `open-sse/services/compression/exclusions.ts`. `chatCore.ts` kontrollerer det ekskluderede mål lige efter at have løst komprimeringsindstillinger,** før nogen motor kører** , og behandler et match nøjagtigt som at komprimering er globalt deaktiveret — anmodningsteksten er beviseligt byte-identisk. Overspringningen optages via `writeCompressionSkip(..., "excluded")` for analytisk synlighed.
- Standard (empty/absent liste): identisk med før-#8034 adfærd — intet er udelukket.

## Kendte begrænsninger

- **LLMLingua-2 (SLM) kræver samplacerede valgfri deps.** Arbejderen kører kun i en produktionsbygning, når `@atjsh/llmlingua-2` + peers er samlokaliseret i `dist/node_modules` (se `scripts/build/colocateOptionals.mjs`, #4286). Uden dem åbner motoren fejl (returnerer den originale tekst). Arbejderopløsning afhænger ikke længere af `import.meta.url` (den dør i det selvstændige bundt) — den forankrer på runtime cwd / `argv[1]`.
- **Caveman sprogpakker `de` / `fr` / `ja` er delvise.** De sender `context` + `filler` + `structural` regler, men ingen `dedup` / `ultra` pakker, så `ultra` intensiteten er ikke stærkere end `full` for disse sprog (de bruger kun deres egne regler — der er ingen stille tilbagegang til de engelske `dedup`/`ultra` -regler, som ville ødelægge fremmed tekst). `en` / `es` / `id` / `pt-BR` er færdige. Bidrag af `dedup.json` + `ultra.json` til delpakkerne er velkomne.
- **Stablet telemetri viser kun motorer, der er komprimeret.** Et stablet-pipeline-trin, hvis motor kørte, men producerede 0 % besparelse, returnerer `stats:null` og vises derfor ikke i `engineBreakdown` — der ikke kan skelnes fra et trin, der blev sprunget over. At skelne "løb, 0 %" fra "sprunget over" ville kræve en ændring af nedbrydningsmodel og udskydes.

## Validering

De fokuserede porte til dette område er:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
