# Compression Engines (Filipino)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute compression ay binuo sa paligid ng mga kontrata ng engine. Ang isang mode ay maaaring direktang magpatakbo ng isang makina (`caveman` o `rtk`) o isang deterministikong stacked pipeline na nagpapatakbo ng maraming makina sa pagkakasunud-sunod.

## Mga mode

| Mode         | Daan ng makina                                                                                  | Nilayong input                              |
| ------------ | ----------------------------------------------------------------------------------------------- | ------------------------------------------- |
| `off`        | wala                                                                                            | Eksaktong maagap na pangangalaga            |
| `lite`       | Caveman lite helpers                                                                            | Low-risk na laging naka-on na paglilinis    |
| `standard`   | taong maninira sa lungga                                                                        | Mabilis na condensation ng natural na wika  |
| `aggressive` | Caveman + history/tool summarizers                                                              | Mahabang chat session                       |
| `ultra`      | Caveman + pruning helpers                                                                       | Context-limit recovery                      |
| `rtk`        | RTK                                                                                             | Terminal, shell, build, test, at git output |
| `omniglyph`  | OmniGlyph                                                                                       | Context-as-image sa native provider wire    |
| `stacked`    | Pipeline. Ang default ng kahilingan ay `session-dedup -> lite`. `rtk -> caveman` ay nag-opt-in. | Pinaghalong tool logs at prose, max savings |

### OmniGlyph compression profile

Ang `omniglyph` engine (package `omniglyph`, 1.4.0 +) ay tumatanggap ng pinangalanang semantic profile, na itinakda sa buong mundo sa pamamagitan ng `omniglyph.profile` sa mga setting ng compression o bawat hakbang sa pamamagitan ng stacked pipeline's step config:

| Profile       | Hangganan                                                                                                                 |
| ------------- | ------------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Default. Ang patakaran na sinukat ng mga na-publish na resibo — images system, tool docs at siksik na kasaysayan          |
| `balanced`    | Pinapanatili ang live na native ng estado, pinoprotektahan ang huling 8 pagliko, i-collapse ang mas lumang closed history |
| `coding-safe` | Pinapanatiling native ang awtoridad, mga schema ng tool at live na tool, pinoprotektahan ang huling 12 pagliko            |
| `passthrough` | Mga ruta nang hindi nagbabago; nilaktawan ang makina                                                                      |

Ang profile ay a** kisame, hindi sahig** : `mergeCompressionProfileOptions` sa package ay tumangging hayaan ang isang tumatawag na mag-override na muling buksan ang isang lossy lane na isinara ang profile, kaya ang isang per-step `preserveSystemPrompt: false` ay hindi maaaring muling paganahin ang compression ng system sa ilalim ng `coding-safe`.

Sinusukat sa codebase na ito: itinaas `coding-safe` at `balanced` `minCompressChars` sa maximum nito at panatilihing native ang system, mga schema ng tool, at mga resulta ng tool, kaya ang session na hindi pa nakakaipon ng history ay tumitigil sa `below_min_chars` at ang makina ay walang pagbabago. Kaya naman ang default ay `aggressive` kaysa sa pinakaligtas na profile.

Niresolba ng package ang sarili nitong saklaw at profile ng modelo mula sa configuration ng kapaligiran nito. OmniRoute hindi kailanman nagde-delegate ng desisyon: inilalagay ng adapter ang gate ng modelo sa pinakamahigpit na saklaw ng package, kaya ang mga setting ng kapaligiran ng host ay maaari lamang paliitin ang allowlist, hindi kailanman palawakin ito sa mga sinusukat na resibo ng OmniRoute.

## Rehistro ng Engine

Ang rehistro ay nakatira sa `open-sse/services/compression/engines/registry.ts`. Inilalantad ng mga makina ang isang nakabahaging kontrata:

- `id`: stable engine id gaya ng `caveman` o `rtk`
- `apply(text, config)`: legacy execution path na ginagamit ng mga nakasalansan na pipeline
- `compress(input, config)`: pangunahing execution path na nagbabalik ng text + stats
- `getConfigSchema()`: ibinabalik ang JSON-Schema-like na hugis ng wastong config
- `validateConfig(config)`: nagbabalik `{ valid, errors[] }`

Gumagamit ang pagpaparehistro ng `registerCompressionEngine(engine)` (o `registerEngine` para sa mga advanced na kaso), na tumatawag `assertValidEngine()` at `validateConfig(defaultConfig)` bago tanggapin. Gamitin ang `unregisterCompressionEngine(id)` upang alisin ang isang makina sa runtime.

Inirerehistro ng `strategySelector.ts` ang mga built-in na makina bago tumakbo ang compression. Nagbibigay-daan ito sa preview, runtime compression, stacked mode, mga pagsubok, at mga engine sa hinaharap na gamitin ang parehong execution path.

### MCP paglalarawan compression (kaugnay)

Ang isang hiwalay na registry ay nag-compress ng MCP tool ng paglalarawan ng metadata sa registry-level — tingnan `open-sse/mcp-server/descriptionCompressor.ts` at [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Ginagamit nitong muli ang mga panuntunan ng Caveman ngunit gumagana sa tool metadata, hindi humihiling ng mga payload.

### Mga karagdagang built-in na makina

Higit pa sa Caveman, RTK, at LLMLingua-2, nagpapadala ang registry ng ilang espesyal na lossless / structural engine (ginagamit ng mga stacked pipeline, playground, at mga pagsubok):

| makina        | Id              | Ano ang ginagawa nito                                                                                                                                                                                                  |
| ------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): pinapalitan ang malalaking magkakadikit na text block ng mga content-addressed reference, kaya ang mga repeated/large block ay ipinapadala nang isang beses at isinangguni pagkatapos. |
| headroom      | `headroom`      | SmartCrusher (H3 + N5): lossless tabular compaction ng homogenous JSON-array payloads sa isang columnar `[N rows]` form.                                                                                               |
| ionizer       | `ionizer`       | Head/middle/tail row sampling para sa napakalaking homogenous na mga bloke, na iniimbak ang elided middle bilang isang CCR content-addressed reference.                                                                |
| session-dedup | `session-dedup` | Cross-turn deduplication na naka-address sa content (TokenMizer-inspired): tinatanggal ang text na nakita na sa mga naunang pagliko ng parehong session.                                                               |

**pagtuturo ng CCR retrieve-protocol (#8033):** sa unang pagkakataon na pinapalitan ng CCR ≥ 1 block sa isang kahilingan, ang makina ay naghahanda ng isang solong, idempotent `system` na mensahe (nangunguna sa `[CCR protocol]` sentinel) na nagtuturo sa tumatawag ng marker → tool contract: kung ano ang ibig sabihin ng `[CCR retrieve hash=<24hex> chars=N]` marker, na ang hash ay dapat kopyahin sa verbatim (lahat ng 24 hex na character — ay malamang na hindi nakopya ng "harang") Ang ibig sabihin `[dedup:ref sha=...]` marker ay "tumingin sa kasaysayan", hindi "tawagan ang tool". Ang tala ay tinuturok** kapag napatunayan lamang ng ina-advertise na `tools[]` ng tumatawag na maaabot talaga nito `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — isang simpleng OpenAI-compatible na tumatawag na walang tool na iyon ay hindi kailanman nakakatanggap ng tagubilin na tumawag sa isang bagay na hindi nito maabot. Ang Idempotency ay ipinapatupad sa pamamagitan ng pag-scan sa history ng mensahe para sa sentinel bago mag-inject, kaya ang mga kahilingang multi-turn (na nagre-replay ng mga naunang mensahe) ay hindi nagsasalansan ng tala nang isang beses bawat pagliko.

## taong maninira sa lungga

Ang mode ng Caveman ay nakatuon sa semantic condensation ng normal na prosa:

- pinapanatili ang mga bloke ng code, URLs, JSON, mga landas, at nakabalangkas na data
- inaalis ang filler, hedging, paulit-ulit na konteksto, at verbose connective phrasing
- sumusuporta sa language-aware na mga file rule pack sa `open-sse/services/compression/rules/`
- nananatiling available sa pamamagitan ng legacy `standard`, `aggressive`, at `ultra` mode

Ang ibabaw ng dashboard ay `Dashboard -> Context & Cache -> Caveman`.

Nag-uulat ang Caveman upstream ng `~75%` mas kaunting mga output token, `65%` average na matitipid sa output sa mga benchmark na may hanay ng `22-87%`, at isang `~46%` input-compression tool. Ginagamit ng OmniRoute ang numero sa gilid ng input ng Caveman kapag nagdodokumento ng mga nakasalansan na matitipid prompt/context ; Ang mode ng output ng Caveman ay nananatiling isang hiwalay na tampok na pag-uugali sa pagtugon.

## RTK

Nakatuon ang RTK mode sa command at tool na output:

- nakakakita ng mga klase ng output gaya ng `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go tests, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, stack traces, at generic logs
- nalalapat ang 49 JSON filter mula sa `open-sse/services/compression/engines/rtk/filters/`
- sumusuporta sa RTK-style declarative pipeline: ANSI stripping, replace, match-output short-circuit, strip/keep lines, per-line truncation, head/tail/max-line truncation, at on-empty fallback
- Sinusuportahan ang trust-gated na mga filter ng proyekto sa `.rtk/filters.json` at mga pandaigdigang filter sa `DATA_DIR/rtk/filters.json`
- tinatanggal ang mga pagkakasunud-sunod ANSI, umuusad na ingay, paulit-ulit na linya, at hindi nakakatulong na boilerplate
- pinapanatili ang mga naaaksyunan na pagkabigo, mga babala, mga buod, mga binagong file, at konteksto ng buntot
- maaaring opsyonal na mapanatili ang na-redact na raw na output para sa recovery/debugging sa pamamagitan ng mga na-authenticate na ruta ng pamamahala

Ang ibabaw ng dashboard ay `Dashboard -> Context & Cache -> RTK`.

Mga detalye ng pagpapatakbo para sa mga custom na filter, tiwala, pag-verify, at pagbawi ng raw-output nang live sa [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream ay nag-uulat ng `60-90%` savings para sa command-output compression. README halimbawa nito ay nagpapakita ng 30 minutong Claude Code session na mula `~118,000` token hanggang `~23,900`, o `79.7%` na na-save.

## LLMLingua-2 (Semantic Pruning)

gumaganap LLMLingua-2 mode** semantic token pruning** sa prosa gamit ang isang maliit ONNX token classifier, na umaakma sa mga engine na nakabatay sa panuntunan na Caveman at RTK :

- nag-compress ng prosa sa mga mensaheng hindi sistema lamang; Ang mga nabakuran na bloke ng code at iba pang napanatili na mga konstruksyon ay hindi kailanman binabago
- pinapatakbo ang `@atjsh/llmlingua-2` backend (ONNX sa pamamagitan ng `@huggingface/transformers`) sa isang thread ng manggagawa, kaya hindi kailanman hinaharangan ng inference ng modelo ang loop ng kaganapan ng kahilingan
- ay** nasasalansan** (`stackPriority` 35): sa isang stacked pipeline ito ay tumatakbo pagkatapos ng structural engines (CCR, session-dedup, headroom, Caveman) ngunit bago ang `ultra`, dahil ang semantic pruning ay pinakaepektibo sa naka-structurally-compressed na text — hal `rtk -> caveman -> llmlingua`
- **mabibigo-bubukas sa anumang error** (nawawalang opsyonal na deps, worker spawn, model load, inference, o timeout) → ang orihinal na text ay ibinalik nang hindi nabago, hindi kailanman isang error

Lokasyon ng makina: `open-sse/services/compression/engines/llmlingua/`. Ang ibabaw ng dashboard ay `Dashboard -> Context & Cache -> LLMLingua`.

### Mga modelo

Ang default na modelo ay**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, mabilis). Isang mas mataas na katumpakan** BERT-base** modelo (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) ay available sa pamamagitan ng engine config `model` field. Tamad na dina-download ng `@huggingface/transformers` ang napiling modelo mula sa HuggingFace Hub papunta sa `${DATA_DIR}/models/llmlingua` sa unang tawag (`modelStore.ts`); itinuturo ito ng isang `modelPath` config override sa isang lokal na kopya sa halip (offline / air-gapped na mga pag-install).

### Mga opsyonal na dependency at on-demand na pag-install

Ang prunable LLMLingua runtime peer stack ay** opsyonal** . Dalawang pakete ang idineklara bilang `optionalDependencies` sa `package.json` at pinananatili** panlabas** sa pamamagitan ng pagbuo ng produksyon ( hindi ibinu-bundle ng `scripts/build/prepublish.ts` ang mga ito):

| Package              | Bersyon (pin) | Mga Tala                                                |
| -------------------- | ------------- | ------------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`       | Entry package; ipinapahayag ang iba bilang mga kapantay |
| `js-tiktoken`        | `^1.0.20`     | Tokenizer                                               |

`@huggingface/transformers` ay naka-pin sa `^4.2.0` (ibinahagi sa lokal na landas ng mga pag-embed at na-trace din sa standalone na bundle); `@atjsh/llmlingua-2@2.0.5` ay nakikipag-peer dito gamit ang `"^3.5.2 || ^4.0.0"`, kaya parehong Transformers.js v3 at v4 ay sinusuportahan. Mula noong 2.0.4, hindi na nangangailangan ang `@atjsh/llmlingua-2` `@tensorflow/tfjs`, na nag-alis ng pinakamalaking nag-iisang contributor (TensorFlow.js) mula sa SLM stack. Tanging ang dalawang pakete sa itaas ay prunable SLM peer. Awtomatikong ini-install ng karaniwang `npm install` (dev) ang opsyonal na stack maliban kung ang mga opsyonal na dependencies ay tinanggal.

**Bakit on-demand:** ang npm-published package, ang standalone na bundle, at ang Docker image ship** walang** itong mga deps para manatiling slim. Kapag wala sila, ang gate ng dependency ng manggagawa (isang `@atjsh/llmlingua-2` solve probe sa `worker.ts`) ay nabigo at ang makina** mabibigo-nagbubukas ng tahimik** Ang pagpili ng — LLMLingua ay nagiging isang no-op (ang teksto ay ibinalik nang hindi nabago, walang error na naka-log). Upang i-activate ito sa isang pruned environment, i-install ang opsyonal na stack:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Ang `@tensorflow/tfjs` removal (2.0.4 +) ay nag-aalis ng dating nangingibabaw ~ 800 MB contributor — ang natitirang footprint ay ang transformers.js + onnxruntime-node runtime, kasama ang TinyBERT model (~ 57 MB) na na-download sa unang paggamit (hindi sa pamamagitan ng npm).

Bawat kapaligiran:

- **Dev / `npm install`** Awtomatikong naka-install — maliban kung naipasa mo `--omit=optional` (o `--no-optional`). Walang kinakailangang aksyon.
- **Global npm (`npm i -g omniroute`) / standalone** — patakbuhin ang install command sa itaas sa loob ng naka-install na direktoryo ng package, o muling i-install nang hindi inaalis ang mga opsyonal na deps.
- **Docker** — idagdag ang utos sa pag-install sa isang hinangong layer ng imahe; ang nai-publish na imahe ships slim sa pamamagitan ng disenyo.
- **VPS (PM2)** — i-install sa `node_modules` ng app, pagkatapos ay i-restart ang proseso upang muling suriin ng manggagawa ang gate.
- **Raw Next standalone (`npm run build` → `.build/next/standalone/server.js`)** — ang standalone trace ships NEITHER ang manggagawa o ang mga opsyonal na deps, kaya tahimik na nabigo ang makina. muling inilalapat `scripts/build/colocate-standalone.mjs` ang dalawa (ang manggagawa ay nagtatayo + opsyonal-dep na pagsasara sa standalone na puno); awtomatiko itong tumatakbo sa pamamagitan ng `postbuild` npm hook pagkatapos ng bawat build. Idempotent, fail-soft kapag wala ang deps.

**I-verify na ito ay aktibo:** kapag pinili LLMLingua, talagang lumiliit ang tunay na prose (hihinto ang pagbukas ng makina), at ang unang kahilingan ay nagti-trigger ng pag-download ng modelo sa `${DATA_DIR}/models/llmlingua`. Ang gate ay sadyang probe lamang `@atjsh/llmlingua-2` — ang iba pang mga kapantay ay ESM-lamang at `require.resolve` ihagis sa kanila kahit na naroroon — kaya ang manggagawa pa rin mabibigo-bubuksan kung ang anumang mga kapantay ay tunay na nawawala sa `import()` oras.

## Mga nakasalansan na Pipeline

Ang stacked mode ay nagpapatakbo ng mga pipeline na hakbang sa pagkakasunud-sunod. Ang default ay:

```txt
rtk -> caveman
```

Gamitin ito para sa mga session ng coding-agent kung saan pinagsasama ng prompt ang output ng command sa human o assistant prose. Binabawasan muna RTK ang maingay na mga log ng tool, pagkatapos ay i-compress ng Caveman ang natitirang natural na wika.

Ang mga hakbang sa pipeline ay na-configure gamit ang `stackedPipeline` sa mga setting ng compression o sa pamamagitan ng mga combo ng compression.

Kapag binawasan ng parehong engine ang parehong karapat-dapat na kargamento, savings compound:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Accessibility Tree Filter

Ang MCP accessibility-tree smart filter ay isang post-execution compression layer na tumatakbo sa MCP** resulta ng tool** , hindi sa mga senyas o konteksto. Tina-target nito ang verbose accessibility-tree at browser snapshot payload na ibinalik ng mga tool tulad ng Playwright, computer-use, at browser-automation MCP server.

### Ano ang ginagawa nito

1. **Pagtanggal ng ingay** inalis — ang walang laman na mga entry generic/text (`- generic:`, `- text: ""`)
2. **Pagbagsak ng magkapatid** — kapag ≥ `collapseThreshold` (default 30) na magkakasunod na linya ay structural repeats, i-collapse ang mga ito sa unang `collapseKeepHead` (default 10) na linya + a count summary + ang huling `collapseKeepTail` (default 5) na linya
3. **Ref pangangalaga** — `[ref=eXX]` na anchor na kinakailangan ng Playwright/computer-use ay hindi kailanman ginalaw
4. **Matigas na pagputol** — kung ang text pagkatapos ng pag-collapse ay lumampas pa rin sa `maxTextChars` (default na 50,000), pinuputol ito gamit ang isang pahiwatig sa pag-navigate upang patuloy na magtrabaho ang ahente

### Lokasyon ng makina

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Configuration

Kinokontrol ng `compression.mcpAccessibility` sa mga pandaigdigang setting (migration 056). Default na config:

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

Inilapat lamang ang filter sa mga payload ng resulta ng tool na ang `type` ay `"text"` at ang haba ay lumampas sa `minLengthToProcess`. Hindi ito nakakaapekto sa agarang compression o humiling ng mga payload.

### Inaasahang pagtitipid

60–80% sa mga resulta ng tool sa snapshot ng browser, depende sa pagiging kumplikado ng page. Ang algorithm ng pagbagsak ay O(n) sa bilang ng linya at nagdaragdag ng hindi gaanong latency.

### Ang filter na ito kumpara sa mga compression engine sa itaas

| Aspeto     | Caveman / RTK / Stacked            | MCP accessibility filter               |
| ---------- | ---------------------------------- | -------------------------------------- |
| Target     | Humiling ng mga prompt / konteksto | mga resulta MCP tool                   |
| Trigger    | Setting ng compression mode        | `compression.mcpAccessibility.enabled` |
| Saklaw     | Lahat ng SSE messages              | Mga resulta ng tool lamang             |
| Ref anchor | N/A                                | Iniingatan nang walang kondisyon       |

---

## Combos ng Compression

Ang mga compression combo ay pinangalanang mga compression profile na maaaring italaga sa mga routing combo:

- `compression_combos`: stores mode, pipeline, RTK config, language config, at default marker
- `compression_combo_assignments`: nagmamapa ng compression combo sa isang routing combo
- Niresolba ng runtime integration ang isang nakatalagang compression combo bago mag-override ang generic na combo
- Kasama sa analytics `compression_combo_id` at `engine`

Ibabaw ng dashboard: `Dashboard -> Context & Cache -> Compression Combos`.

## Mga kinakailangan / gabay ng operator (CCR at session-dedup)

CCR (`ccr`) at `session-dedup` palitan o tanggalin ang text at mag-iwan ng a** pananda** sa likod. Ang seksyong ito ay ang sanggunian ng operator para sa pag-wire ng isang kliyente, pagbabasa ng dalawang marker, at pagkuha o pag-diagnose ng elided na nilalaman. Ang mga mekanika ng bawat makina ay sakop sa itaas; ito ang layer na "paano ko ito papatakbuhin".

### Mga transportasyon at endpoint

Ang MCP server na naglalantad sa mga tool CCR ay maaaring maabot sa tatlong paraan. Ang default na base URL ay `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transportasyon                                | URL / utos                              | Mga Tala                                                                                                                                                     |
| --------------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Streamable na HTTP (kliyente, inirerekomenda) | `http://localhost:20128/api/mcp/stream` | Ang endpoint na kasalukuyang kinakausap ng mga kliyente MCP.                                                                                                 |
| Legacy SSE singleton                          | `http://localhost:20128/api/mcp/sse`    | Mas lumang singleton na transportasyon. Ito** nagsasara** streamable session; gumamit ng mga `streamable-http` client laban sa `/api/mcp/stream`, hindi ito. |
| stdio                                         | `omniroute --mcp`                       | Para sa IDE MCP config na nagpapalabas ng proseso. Walang `--dev` flag; `omniroute --mcp` ay ang stdio entry point.                                          |

### Mga tier ng storage (kung ano ang makakaligtas sa pag-restart)

CCR ay a** dalawang baitang** tindahan, hindi sa memorya-lamang:

- **Mainit na in-memory tier** — per-block cap 2 MiB, per-principal 16 MiB, global 64 MiB. Default ang mga entry sa isang 24 h TTL (maximum na 7 araw). Ang buong MCP retrieval mula sa memorya ay nililimitahan sa 256 KiB; anumang mas malaki ay maaabot pa rin sa pamamagitan ng ranged / grep mode.
- **Matibay na tier SQLite** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, naka-on bilang default) ibina-back — ang in-memory na tier upang ang isang bloke ay makaligtas LRU eviction, isang restart, o isang retrieve landing sa ibang pagkakataon. Pinapanatili ng row ang TTL ng bloke, kaya ang isang bloke na lampas sa TTL nito ay nawala mula sa magkabilang tier.

Pinapanatili ng tatlong guwardiya ang matibay na tier bounded — a block ay nananatiling memory-only kapag:

1. tapos na ang block** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. ang runtime ay isang cloud runtime (walang lokal na disk);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Kaya't ang "nawala ang block" ay hindi isang blanket restart story: ang isang sub-512 KB block sa isang lokal, hindi cloud runtime ay nakaligtas sa isang pag-restart sa pamamagitan ng matibay na tier hanggang sa maubos TTL nito. Tingnan [ang Environment reference](../reference/ENVIRONMENT.md) para sa variable.

### Ang dalawang marker

| Marker                                | Ibig sabihin                                                                                                                                                  | Ano ang dapat gawin ng modelo                                                                                                                                                                                                                       |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Isang malaking bloke ang nakaimbak na naka-address sa nilalaman.                                                                                              | Tawagan `omniroute_ccr_retrieve` gamit ang** 24-hex hash na kinopya ng verbatim** upang maibalik ang orihinal na teksto.                                                                                                                            |
| `[dedup:ref sha=…]`                   | `session-dedup` elided text na naipadala na sa naunang turn ng parehong session. Ito ay isang** sinadyang pagbabalik tanaw** , hindi pagkawala o pagkakamali. | Gawin** hindi** tumawag sa anumang tool at gawin** hindi** subukang "muling buuin" ito. Ang unang paglitaw ng teksto ay ang kanonikal na kopya; ang kasalukuyang pagliko ay hindi kailanman muling isinulat, ito ay nababawas sa ibang pagkakataon. |

Ang `[dedup:ref]` look-back ay isang sadyang desisyon sa protocol — walang pre-send na muling pagtatayo. Tratuhin ito bilang "nasa wire na ang eksaktong text na ito sa unang bahagi ng session na ito."

### Mga kinakailangan ng kliyente

- **Susi (stdio):** ang isang stdio caller ay walang dalang pagkakakilanlan sa bawat kahilingan, kaya ito ay nagpapatotoo gamit ang `OMNIROUTE_API_KEY` (nakatakda sa MCP server ng `env`). Kung wala ito ang tumatawag ay hindi nagpapakilala at ang mga tool na nangangailangan ng isang punong-guro ay maaaring bumaba.
- **`tools[]` ay ang iniksyon precondition.** Ang CCR retrieve-protocol instruction (#8033) ay ini-inject** lamang** kapag napatunayan ng ina-advertise `tools[]` ng kahilingan na talagang maabot ng kliyente ang `omniroute_ccr_retrieve`. Ang tugma ay isang trailing-segment na tugma na nililimitahan ng isang separator (`__`, `.`, `/`, `:`) — hindi kailanman isang bare substring — kaya ang namespaced na pangalan gaya ng `mcp__gateway__omniroute_ccr_retrieve` ay binibilang pa rin. Ang isang absent o hindi tumutugmang `tools[]` ay nangangahulugan na ang pagtuturo ay _hindi_ iniksyon, ayon sa disenyo.
- **`codemode:false` (mga kliyente OpenCode ).** Nagde-default OpenCode sa Code Mode, na nag-a-advertise lamang ng mga native na tool nito sa modelo at** hindi** ilagay ang MCP tools sa native `tools[]` list. Itakda ang `codemode: false` sa MCP server entry para mai-advertise ang `omniroute_ccr_*` tools. Ito ay isang** kliyente** setting, hindi isang OmniRoute. Hindi pa nito nai-inject ang pagtuturo CCR : pinangalanan OpenCode ang isang tool `<server>_<tool>`, kaya inilalantad ng server na tinatawag na `omniroute` `omniroute_omniroute_ccr_retrieve`, at `_` ay hindi isa sa mga katugmang separator.
- **Mga principal.** Ang storage at retrieval ay nakahiwalay sa bawat authenticated na principal (bawat API key). Nakikita lamang ng isang susi ang sarili nitong mga bloke.

### Saklaw ng bawat tool

Palaging naka-on ang pagpapatupad ng saklaw para sa mga tumatawag HTTP/SSE na may makitid na saklaw. Ang `omniroute_` CCR tool ay nangangailangan ng:

| Tool                     | Saklaw              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Ang isang nawawalang saklaw ay nagbabalik ng isang** resulta ng error MCP tool** (`isError: true`, hindi isang HTTP 403 — ang `403 LOCAL_ONLY` ay ang hiwalay na loopback route-guard auth): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Ang isang minimal na remote key ay maaaring humawak ng `mcp:connect` (nagpapahintulutan ang `/api/mcp/` local-only carve-out) kasama ang partikular na saklaw read/write na kailangan nito.

### Matrix ng kliyente

| Kliyente          | Transportasyon                                   | Config na gagamitin                                                                                                                                                                                                                                             | nag-advertise `tools[]` ? (→ CCR na pagtuturo ay na-injected)                                                                                                                                                                     |
| ----------------- | ------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude Code       | streamable-http                                  | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                               | Oo — MCP-capable; tinurok.                                                                                                                                                                                                        |
| Cursor / Cline    | `stdio`** o** `streamable-http`                  | stdio: `omniroute --mcp` na may `OMNIROUTE_API_KEY` sa `env`; o isang remote MCP entry na tumuturo sa `http://localhost:20128/api/mcp/stream` (tingnan [ang Gabay sa Pag-setup → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Oo — i-advertise ang `omniroute_ccr_*` tools.                                                                                                                                                                                     |
| OpenCode          | streamable-http                                  | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, kasama ang `codemode: false`                                                                                                                                                          | Mga tool na ina-advertise lamang gamit ang `codemode: false`; ang pagtuturo ay hindi pa rin nai-inject, dahil `omniroute_omniroute_ccr_retrieve` ay hindi tumutugma (tingnan [ang Client prerequisites](#client-prerequisites) ). |
| OpenAI-compatible | OpenAI-compatible HTTP (mga pagkumpleto ng chat) | karaniwang kliyente ng pagkumpleto ng chat laban sa endpoint na katugma sa OpenAI                                                                                                                                                                               | **Hindi kailanman** — isang simpleng OpenAI-compatible na tumatawag ay hindi kailanman sinabihan na tawagan ang tool, at ang pagtuturo ay hindi ini-inject.                                                                       |

### Mga limitasyon sa pagkuha at pagination

Ang mga resulta ng teksto MCP tool ay pinuputol sa paligid ng `mcpAccessibility.maxTextChars` (default `50000`). Ang `full` retrieve ng isang block ay nililimitahan sa 256 KiB —** walang unbounded full retrieve** . Kapag malaki ang `chars=N` ng isang bloke, pahinain ito sa halip na hilahin ang buong bagay:

- Panuntunan ng hinlalaki:**`chars > 40000` → gumamit ng `mode`** , hindi kailanman isang hubad na puno.
- `mode:"grep"` — regex `pattern` na tumugma sa bawat linya, hanggang sa 1,000 tugmang linya (`unique: true` drops repeats), pinakamurang para sa "hanapin ang isang linya na kailangan ko."
- `mode:"lines"` — isang 1-index na hanay ng linya; nangangailangan ng parehong `start` at `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` na mga linya.
- `mode:"stats"` — line, character, at byte na mga bilang nang walang body.

Gamitin `mode:"lines"` na may `start`/`end` upang maglakad ng mahabang bloke sa mga pahina sa halip na hilingin ang kabuuan nang sabay-sabay.

### Pangalan ng tool

Ang retrieve tool ay kasalukuyang pinangalanang `omniroute_ccr_retrieve` (ang `omniroute_` prefix ay isang may petsang workaround para sa cross-server name collisions). Ang isang mas malinis na bounded-suffix na pangalan ng tool at isang pag-aayos para sa MCP JSON na mga resulta na pinutol sa kalagitnaan ng string ay sinusubaybayan bilang upstream follow-up; ang pahinang ito ay nagdodokumento ng kasalukuyang, ipinadalang gawi lamang.

### Siklo ng buhay ng session

Idle out ang mga streamable-HTTP session at inaani sila ng server; ang idle window ay ang `MCP_SESSION_IDLE_MS` constant (na tinutukoy ng pangalan, hindi isang hardcoded na halaga, kaya hindi naaanod ang page na ito kapag nagbago ito). Ang sintomas ng isang idle-reaped session ay isang HTTP 404 na may `Unknown Mcp-Session-Id` — ang remedyo ay upang muling kumonekta o i-restart ang session,** hindi** upang i-rotate ang isang key, baguhin ang isang saklaw, o palitan ang pangalan ng isang tool.

## API Ibabaw

| Ruta                                   | Layunin                                                                          |
| -------------------------------------- | -------------------------------------------------------------------------------- |
| `/api/settings/compression`            | Mga pangkalahatang setting ng compression (kasama ang `mcpAccessibility` config) |
| `/api/compression/preview`             | I-preview ang anumang compression mode                                           |
| `/api/compression/language-packs`      | Ilista ang mga available na pack ng wika ng Caveman                              |
| `/api/context/caveman/config`          | alias ng mga setting ng Caveman                                                  |
| `/api/context/rtk/config`              | mga default at setting RTK                                                       |
| `/api/context/rtk/filters`             | katalogo ng filter RTK                                                           |
| `/api/context/rtk/test`                | RTK preview/test endpoint                                                        |
| `/api/context/rtk/raw-output/[id]`     | Na-authenticate na na-redact na raw-output recovery                              |
| `/api/context/combos`                  | Compression combo CRUD                                                           |
| `/api/context/combos/[id]/assignments` | Pagruruta-combo assignment CRUD                                                  |
| `/api/context/analytics`               | alias ng compression analytics                                                   |

Nangangailangan ang mga ruta ng pamamahala ng pagpapatotoo sa pamamahala o mga pagsusuri sa patakaran ng API-key.

## MCP Tools

Inilalantad ng compression ang limang MCP tool:

| Tool                                | Saklaw              | Layunin                                 |
| ----------------------------------- | ------------------- | --------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Mga setting, analytics, cache stats     |
| `omniroute_compression_configure`   | `write:compression` | I-update ang mga pandaigdigang setting  |
| `omniroute_set_compression_engine`  | `write:compression` | Itakda ang mode at opsyonal na pipeline |
| `omniroute_list_compression_combos` | `read:compression`  | Maglista ng mga combo ng compression    |
| `omniroute_compression_combo_stats` | `read:compression`  | Basahin ang combo/engine analytics      |

## Saklaw at mga pagbubukod

**Ang mga pag-embed ay hindi kailanman na-compress.** Hindi kailanman tinatawag ng `open-sse/handlers/embeddings.ts` ang anumang compression engine — ang mga katawan request/response ay dumiretso sa executor nang hindi nagalaw. Ito ay istruktura ngayon (ang mga pag-embed at pagkumpleto ng chat ay magkahiwalay na mga humahawak), hindi isang runtime check, ngunit nangangahulugan ito na ang vector-distortion concern sa #8034 ay walang exposure surface sa embeddings path.

**filter ng pagbubukod Per-model/endpoint (#8034).** Para sa mga pagkumpleto ng chat, maaaring pangalanan ng operator ang mga modelong id / `provider/model` na mga target na hindi kailanman dapat i-compress — isang guardrail na kapaki-pakinabang kung ang compression ay naka-wire na mas malapit sa isang embeddings-adjacent path sa ibang pagkakataon, at sa pangkalahatan ay kapaki-pakinabang para sa anumang modelo na ang eksaktong byte-for-byte na prompt ay mahalaga (deterministic evals, cache-sensitive prefix, atbp.).

- Field ng mga setting: `exclusions?: string[]` sa global compression config (`GET`/`PUT /api/settings/compression`), nagpatuloy sa pamamagitan ng umiiral na `key_value` compression namespace (`src/lib/db/compression.ts`) — walang bagong talahanayan.
- Tab ng dashboard:** Dashboard → Compression → Mga Pagbubukod** (`/dashboard/compression/exclusions`).
- Pattern syntax: `*` ay ang tanging wildcard. Ang bawat iba pang regex metacharacter sa isang pattern ay na-escape bago tumugma, kaya `gpt-5.6` ay tumutugma sa literal na string lamang, hindi kailanman `gpt-5x6` (ReDoS-safe, bounded, walang nested quantifiers). Ang mga pattern ay tumutugma sa case-insensitively laban sa hubad na modelo id at ang `provider/model` composite — `gpt-5-6`, `openai/gpt-5-6`, at `openai/*` lahat ay gumagana, at `*` lamang ay hindi kasama ang bawat modelo.
- Pagtutugma: `isCompressionExcluded()` / `normalizeCompressionExclusions()` sa `open-sse/services/compression/exclusions.ts`. sinusuri ng `chatCore.ts` ang ibinukod na target pagkatapos malutas ang mga setting ng compression,** bago paandarin ang anumang makina** , at tinatrato ang isang tugma nang eksakto tulad ng compression na hindi pinagana sa buong mundo — ang request body ay provably byte-identical. Ang paglaktaw ay naitala sa pamamagitan ng `writeCompressionSkip(..., "excluded")` para sa kakayahang makita ng analytics.
- Default (empty/absent list): kapareho ng pre-#8034 gawi — walang ibinukod.

## Mga kilalang limitasyon

- **LLMLingua-2 (SLM) ay nangangailangan ng mga opsyonal na deps.** Tumatakbo lang ang manggagawa sa isang production build kapag `@atjsh/llmlingua-2` + peer ay co-located sa `dist/node_modules` (tingnan ang `scripts/build/colocateOptionals.mjs`, #4286). Kung wala ang mga ito ang makina ay mabibigo-bubukas (ibinabalik ang orihinal na teksto). Ang resolusyon ng manggagawa ay hindi na nakasalalay sa `import.meta.url` (namamatay ito sa standalone na bundle) — ito ay naka-angkla sa runtime cwd / `argv[1]`.
- **Ang mga pack ng wika ng Caveman `de` / `fr` / `ja` ay bahagyang.** Nagpapadala sila `context` + `filler` + `structural` na mga panuntunan ngunit walang `dedup` / `ultra` pack, kaya ang intensity `ultra` ay hindi mas malakas kaysa sa `full` para sa mga wikang iyon (ginagamit lang nila ang sarili nilang mga panuntunan — walang silent fall-back sa English `dedup`/`ultra` rules, na makakasira ng banyagang text). `en` / `es` / `id` / `pt-BR` ay kumpleto na. Tinatanggap ang mga kontribusyon ng `dedup.json` + `ultra.json` para sa mga partial pack.
- **Inililista lang ng stacked telemetry ang mga engine na nag-compress.** Ang isang stacked-pipeline na hakbang na ang makina ay tumakbo ngunit nakagawa ng 0 % na matitipid ay nagbabalik `stats:null` at sa gayon ay hindi lumalabas sa `engineBreakdown` — na hindi nakikilala mula sa isang hakbang na nilaktawan. Ang pagkilala sa "ran, 0 %" mula sa "nilaktawan" ay mangangailangan ng pagbabago ng breakdown-model at ipinagpaliban.

## Pagpapatunay

Ang mga nakatutok na gate para sa lugar na ito ay:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
