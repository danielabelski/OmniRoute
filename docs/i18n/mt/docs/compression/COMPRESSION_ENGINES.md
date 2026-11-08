# Compression Engines (Malti)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

kompressjoni OmniRoute hija mibnija madwar kuntratti tal-magna. Modalità tista 'taħdem magna waħda direttament (`caveman` jew `rtk`) jew pipeline stacked deterministiku li tesegwixxi magni multipli fl-ordni.

## Modi

| Modalità     | Mogħdija tal-magna                                                                     | Input maħsub                                      |
| ------------ | -------------------------------------------------------------------------------------- | ------------------------------------------------- |
| `off`        | xejn                                                                                   | Preservazzjoni eżatta fil-pront                   |
| `lite`       | Caveman lite helpers                                                                   | Tindif dejjem fuq b'riskju baxx                   |
| `standard`   | Caveman                                                                                | Kondensazzjoni fil-pront tal-lingwa naturali      |
| `aggressive` | Caveman + history/tool summarizers                                                     | Sessjonijiet twal ta' chat                        |
| `ultra`      | Caveman + helpers taż-żbir                                                             | Irkupru tal-limitu tal-kuntest                    |
| `rtk`        | RTK                                                                                    | Terminal, qoxra, bini, test, u output git         |
| `omniglyph`  | OmniGlyph                                                                              | Context-as-image fuq il-wajer tal-fornitur nattiv |
| `stacked`    | Pipeline. It-talba default hija `session-dedup -> lite`. `rtk -> caveman` huwa opt-in. | Għodda mħallta zkuk u proża, iffrankar massimu    |

### profili kompressjoni OmniGlyph

Il-magna `omniglyph` (pakkett `omniglyph`, 1.4.0 +) taċċetta profil semantiku msemmi, issettjat globalment permezz `omniglyph.profile` fis-settings tal-kompressjoni jew kull pass permezz tal-konfigurazzjoni tal-pass tal-pipeline stacked:

| Profil        | Konfini                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Default. Il-politika l-irċevuti ppubblikati mkejla — immaġini sistema, għodda docs u storja densa           |
| `balanced`    | Iżomm istat ħajjin indiġeni, jipproteġi l-aħħar 8 dawriet, kollass istorja magħluqa eqdem                   |
| `coding-safe` | Iżomm l-awtorità, l-iskemi tal-għodda u l-output tal-għodda ħajjin indiġeni, jipproteġi l-aħħar 12-il dawra |
| `passthrough` | Rotot mingħajr trasformazzjoni; il-magna tinqabeż                                                           |

Il-profil huwa a** limitu, mhux art** : `mergeCompressionProfileOptions` fil-pakkett jirrifjuta li jħalli lil min iċempel jegħleb mill-ġdid jiftaħ korsija lossy il-profil magħluq, għalhekk `preserveSystemPrompt: false` għal kull pass ma jistax jerġa 'jippermetti l-kompressjoni tas-sistema taħt `coding-safe`.

Mkejla fuq din il-codebase: `coding-safe` u `balanced` jgħollu `minCompressChars` sal-massimu tiegħu u jżommu s-sistema, l-iskemi tal-għodda u r-riżultati tal-għodda indiġeni, għalhekk sessjoni li għadha ma akkumulatx storja tieqaf `below_min_chars` u l-magna ma tittrasforma xejn. Huwa għalhekk li l-inadempjenza hija `aggressive` aktar milli l-aktar profil sikur.

Il-pakkett isolvi l-ambitu u l-profil tal-mudell tiegħu stess mill-konfigurazzjoni tal-ambjent tiegħu. OmniRoute qatt ma jiddelega d-deċiżjoni: l-adapter pins il-bieb tal-mudell għall-ambitu l-aktar restrittiv tal-pakkett, sabiex is-settings tal-ambjent ospitanti jistgħu biss iċekknu l-allowlist, qatt ma jwessgħu lil hinn mill-irċevuti mkejla ta ' OmniRoute.

## Reġistru tal-Magna

Ir-registru joqghod `open-sse/services/compression/engines/registry.ts`. Magni jesponu kuntratt kondiviż:

- `id`: id tal-magna stabbli bħal `caveman` jew `rtk`
- `apply(text, config)`: mogħdija tal-eżekuzzjoni tal-wirt użata minn pipelines stacked
- `compress(input, config)`: mogħdija ta' eżekuzzjoni primarja li tirritorna t-test + stats
- `getConfigSchema()`: jirritorna l-forma bħal JSON-Schema tal-konfigurazzjoni valida
- `validateConfig(config)`: jirritorna `{ valid, errors[] }`

Ir-reġistrazzjoni tuża `registerCompressionEngine(engine)` (jew `registerEngine` għal każijiet avvanzati), li ssejjaħ `assertValidEngine()` u `validateConfig(defaultConfig)` qabel taċċetta. Uża `unregisterCompressionEngine(id)` biex tneħħi magna waqt ir-runtime.

`strategySelector.ts` jirreġistra l-magni built-in qabel il-kompressjoni runs. Dan jippermetti preview, kompressjoni runtime, mod f'munzelli, testijiet, u magni futuri jużaw l-istess mogħdija ta 'eżekuzzjoni.

### MCP deskrizzjoni kompressjoni (relatata)

Reġistru separat jikkompressa l-metadata tad-deskrizzjoni tal-għodda MCP fil-livell tar-reġistru — ara `open-sse/mcp-server/descriptionCompressor.ts` u [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Terġa' tuża r-regoli ta' Caveman iżda topera fuq metadejta tal-għodda, mhux titlob payloads.

### Magni built-in addizzjonali

Lil hinn minn Caveman, RTK, u LLMLingua-2, ir-reġistru jibgħat diversi magni speċjalizzati mingħajr telf / strutturali (użati minn pajpijiet f'munzelli, il-bitħa, u testijiet):

| Magna           | Id              | X'tagħmel                                                                                                                                                                                                          |
| --------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CCR             | `ccr`           | Content-Compress-Retrieve (H4): jissostitwixxi blokki kbar ta' test kontigwi b'referenzi indirizzati għall-kontenut, għalhekk il-blokki repeated/large jintbagħtu darba u jiġu referenzjati minn hemm 'il quddiem. |
| spazju għar-ras | `headroom`      | SmartCrusher (H3 + N5): kompattazzjoni tabulari mingħajr telf ta' payloads ta' firxa JSON omoġenja f'forma `[N rows]` kolonni.                                                                                     |
| jonizzatur      | `ionizer`       | Teħid ta' kampjuni ta' ringiela Head/middle/tail għal blokki omoġenji kbar ħafna, li jaħżnu n-nofs elidju bħala referenza indirizzata għall-kontenut CCR.                                                          |
| sessjoni-dedup  | `session-dedup` | Deduplication cross-turn indirizzata mill-kontenut (ispirata minn TokenMizer): test elides li diġà deher f'dawriet preċedenti tal-istess sessjoni.                                                                 |

**CCR retrieve-protocol instruction (#8033):** l-ewwel darba CCR jissostitwixxi ≥ 1 blokk f'talba, il-magna tipprependi messaġġ `system` wieħed, idempotent (li jwassal mas-sentinel `[CCR protocol]` ) li jgħallem lil min iċempel il-markatur → tool contract: xi tfisser markatur `[CCR retrieve hash=<24hex> chars=N]`, li l-hash irid jiġi kkupjat verbatim (l-24 karattru hex- — ma jkunux ikkupjati ) misjuba" miss), u li markatur `[dedup:ref sha=...]` ifisser "ħares lura fl-istorja", mhux "sejħa l-għodda". In-nota hija injettata** biss meta l `tools[]` reklamat ta' min iċempel juri li fil-fatt jista' jilħaq `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — sejjieħ sempliċi kompatibbli ma' OpenAI mingħajr dik l-għodda qatt ma jirċievi struzzjoni biex isejjaħ xi ħaġa li ma jistax jilħaq. L-idempotenza hija infurzata billi tiskennja l-istorja tal-messaġġi għas-sentinella qabel ma tinjetta, għalhekk talbiet b'ħafna dawra (li jerġgħu jirreaġixxu messaġġi minn qabel) ma jġorrux in-nota darba kull dawra.

## Caveman

Il-mod Caveman jiffoka fuq il-kondensazzjoni semantika tal-proża normali:

- tippreserva l-blokki tal-kodiċi, URLs, JSON, mogħdijiet, u data strutturata
- ineħħi l-mili, il-hedging, il-kuntest ripetut, u l-frażi konnettiv verbose
- jappoġġja pakketti ta' regoli ta' fajls konxji tal-lingwa `open-sse/services/compression/rules/`
- jibqa' disponibbli permezz tal-modi `standard`, `aggressive`, u `ultra` tal-legat

Il-wiċċ tad-dashboard huwa `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream jirrapporta `~75%` inqas tokens tal-output, iffrankar medju tal-output `65%` f'benchmarks b'firxa `22-87%`, u għodda ta 'kompressjoni ta' input `~46%`. OmniRoute juża n-numru tal-input-side Caveman meta jiddokumenta tfaddil prompt/context f'munzelli; Il-mod ta 'output ta' Caveman jibqa' karatteristika separata ta 'rispons-imġieba.

## RTK

Il-mod RTK jiffoka fuq il-kmand u l-output tal-għodda:

- jiskopri klassijiet ta' output bħal `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go tests, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, stack traces, u zkuk ġeneriċi
- japplika 49 JSON filtru minn `open-sse/services/compression/engines/rtk/filters/`
- jappoġġja l-pipeline dikjarattiv tal-istil RTK: ANSI tqaxxir, sostituzzjoni, short-circuit ta 'output ta' match, linji strip/keep, truncation għal kull linja, truncation head/tail/max-line, u fallback fuq vojt
- jappoġġa filtri tal-proġetti trust-gated `.rtk/filters.json` u filtri globali `DATA_DIR/rtk/filters.json`
- strixxi ANSI sekwenzi, storbju progress, linji ripetuti, u boilerplate mhux utli
- jippreserva fallimenti azzjonabbli, twissijiet, sommarji, fajls mibdula, u kuntest ta 'denb
- jista' b'mod fakultattiv iżomm l-output mhux maħdum redat għal recovery/debugging permezz ta' rotot ta' ġestjoni awtentikati

Il-wiċċ tad-dashboard huwa `Dashboard -> Context & Cache -> RTK`.

Dettalji operattivi għal filtri tad-dwana, fiduċja, verifika, u rkupru ta 'output mhux maħdum ħajjin [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream jirrapporta tfaddil `60-90%` għall-kompressjoni tal-kmand-output. L-eżempju README tiegħu juri sessjoni tal-Kodiċi Claude ta’ 30 minuta li tmur minn tokens `~118,000` għal `~23,900`, jew `79.7%` salvati.

## LLMLingua-2 (Żbir Semantiku)

LLMLingua-2 mode twettaq** żbir token semantiku** fuq proża bl-użu ta’ klassifikatur ta’ token ONNX żgħir, li jikkumplimenta l-magni Caveman u RTK ibbażati fuq ir-regoli:

- tikkompressa proża f'messaġġi mhux tas-sistema biss; blokki tal-kodiċi magħluqa u kostruzzjonijiet ippreservati oħra qatt ma jinbidlu
- imexxi l-backend `@atjsh/llmlingua-2` (ONNX permezz `@huggingface/transformers`) f'ħajt tal-ħaddiem, għalhekk l-inferenza tal-mudell qatt ma timblokka l-linja tal-avveniment tat-talba
- huwa** li jista' jiġi stivat** (`stackPriority` 35): f'pipeline stacked jimxi wara l-magni strutturali (CCR, session-dedup, headroom, Caveman ) iżda qabel `ultra`, peress li ż-żbir semantiku huwa l-aktar effettiv fuq test diġà kompressat strutturalment — eż. `rtk -> caveman -> llmlingua`
- **fail-fetaħ fuq kwalunkwe żball** (nieqsin deps fakultattivi, spawn tal-ħaddiema, tagħbija tal-mudell, inferenza, jew timeout) → it-test oriġinali jintbagħat mhux mibdul, qatt żball

Post tal-magna: `open-sse/services/compression/engines/llmlingua/`. Il-wiċċ tad-dashboard huwa `Dashboard -> Context & Cache -> LLMLingua`.

### Mudelli

Il-mudell default huwa**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, fast). Preċiżjoni ogħla** BERT-bażi** mudell (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) huwa disponibbli permezz tal-konfigurazzjoni tal-magna `model` field. `@huggingface/transformers` jniżżel il-mudell magħżul bil-għażż mill- HuggingFace Hub `${DATA_DIR}/models/llmlingua` fl-ewwel sejħa (`modelStore.ts`); a `modelPath` konfig override tippontaha lejn kopja lokali minflok (offline / air-gapped installs).

### Dipendenzi fakultattivi u installazzjoni fuq talba

Il-munzell tal-pari runtime LLMLingua prunable huwa** fakultattiv** . Żewġ pakketti huma ddikjarati bħala `optionalDependencies` `package.json` u miżmuma** esterni** mill-bini tal-produzzjoni (`scripts/build/prepublish.ts` ma jgħaqqadhomx):

| Pakkett              | Verżjoni (pin) | Noti                                                   |
| -------------------- | -------------- | ------------------------------------------------------ |
| `@atjsh/llmlingua-2` | `2.0.5`        | Pakkett tad-dħul; jiddikjara lill-oħrajn bħala sħabhom |
| `js-tiktoken`        | `^1.0.20`      | Tokenizer                                              |

`@huggingface/transformers` huwa ippinjat `^4.2.0` (kondiviż mal-mogħdija tal-inkorporazzjonijiet lokali u traċċat ukoll fil-pakkett waħdu); `@atjsh/llmlingua-2@2.0.5` peers fuqha `"^3.5.2 || ^4.0.0"`, għalhekk kemm Transformers.js v3 kif ukoll v4 huma appoġġjati. Minn 2.0.4, `@atjsh/llmlingua-2` m'għadux jeħtieġ `@tensorflow/tfjs`, li neħħa l-akbar kontributur wieħed (TensorFlow.js) mill-munzell SLM. Iż-żewġ pakketti ta' hawn fuq biss huma peers SLM prunable. `npm install` standard (dev) jinstalla l-munzell fakultattiv awtomatikament sakemm ma jitħallewx barra dipendenzi fakultattivi.

**Għaliex on-demand:** il-pakkett ippubblikat mill-npm, il-pakkett waħdu, u l-vapur tal-immaġni Docker** mingħajr** dawn deps biex jibqgħu SLIM. Meta jkunu assenti, il-bieb tad-dipendenza tal-ħaddiem (sonda `@atjsh/llmlingua-2` resolve `worker.ts`) ifalli u l-magna** fail-jiftaħ skiet** — li jagħżel LLMLingua isir no-op (it-test lura mhux mibdul, l-ebda żball illoggjat). Biex tattivah f'ambjent imnaddaf, installa l-munzell fakultattiv:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

It-tneħħija `@tensorflow/tfjs` (2.0.4 +) telimina l-kontributur ~ 800 MB li qabel kien dominanti — il-footprint li jifdal huwa l-runtimes transformers.js + onnxruntime-node, flimkien mal-mudell TinyBERT (~ 57 MB) imniżżel fl-ewwel użu (not).

Għal kull ambjent:

- **Dev / `npm install`** — installat awtomatikament sakemm ma tkunx għaddiet `--omit=optional` (jew `--no-optional`). Ebda azzjoni meħtieġa.
- **Global npm (`npm i -g omniroute`) / standalone** — ħaddem il-kmand tal-installazzjoni hawn fuq ġewwa d-direttorju tal-pakketti installati, jew installa mill-ġdid mingħajr ma tħalli barra d-deps fakultattivi.
- **Docker** — żid il-kmand tal-installazzjoni f'saff tal-immaġni derivati; l-immaġni ppubblikata vapuri SLIM bid-disinn.
- **VPS (PM2)** — install fis `node_modules` tal-app, imbagħad erġa ibda l-proċess sabiex il-ħaddiem jerġa 'jisonda l-gate.
- **Raw Next standalone (`npm run build` → `.build/next/standalone/server.js`)** — il-vapuri tat-traċċa waħedhom NEITHER il-ħaddiem u lanqas id-deps fakultattivi, sabiex il-magna skiet fail-ftuħ. `scripts/build/colocate-standalone.mjs` jerġa' japplika t-tnejn (ħaddiem esbuild + optional-dep closure fis-siġra waħedha); taħdem awtomatikament permezz tal-ganċ `postbuild` npm wara kull bini. Idempotenti, fail-soft meta d-deps huma assenti.

**Ivverifika li hija attiva:** LLMLingua magħżula, proża reali fil-fatt tiċkien (il-magna tieqaf milli tiftaħ), u l-ewwel talba tixpruna t-tniżżil tal-mudell `${DATA_DIR}/models/llmlingua`. Il-bieb intenzjonalment sondi biss `@atjsh/llmlingua-2` — il-pari l-oħra huma ESM-biss u `require.resolve` jitfa fuqhom anke meta preżenti — sabiex il-ħaddiem xorta fail-ftuħ jekk xi peer ikun ġenwinament nieqes fil-ħin `import()`.

## Pipelines f'munzelli

Mod f'munzelli tmexxi passi tal-pipeline fl-ordni. In-nuqqas huwa:

```txt
rtk -> caveman
```

Uża dan għal sessjonijiet ta' aġent ta' kodifikazzjoni fejn pront jikkombina l-output tal-kmand ma' proża umana jew ta' assistent. RTK inaqqas zkuk tal-għodda storbjużi l-ewwel, imbagħad Caveman jikkompressa l-lingwa naturali li fadal.

Il-passi tal-pipeline huma kkonfigurati `stackedPipeline` f'settings ta 'kompressjoni jew permezz ta' combos ta 'kompressjoni.

Meta ż-żewġ magni jnaqqsu l-istess tagħbija eliġibbli, kompost ta' tfaddil:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Filtru tas-Siġra tal-Aċċessibilità

Il-filtru intelliġenti tas-siġra ta' aċċessibbiltà MCP huwa saff ta' kompressjoni ta' wara l-eżekuzzjoni li jaħdem fuq MCP** riżultati tal-għodda** , mhux fuq prompts jew kuntest. Hija timmira s-siġra tal-aċċessibbiltà verbose u l-pajloads tal-istampa tal-browser ritornati minn għodod bħal Playwright, użu tal-kompjuter, u servers MCP tal-awtomazzjoni tal-browser.

### X'tagħmel

1. **Tqaxxir tal-istorbju** — tneħħi entrati generic/text vojta (`- generic:`, `- text: ""`)
2. **Kollass aħwa** — meta ≥ `collapseThreshold` (default 30) linji konsekuttivi huma ripetizzjonijiet strutturali, kollasshom fl-ewwel `collapseKeepHead` (default 10) linji + sommarju tal-għadd + l-aħħar `collapseKeepTail` (default 5) linji
3. **Ref preservazzjoni** — `[ref=eXX]` ankri mitluba minn Playwright/computer-use qatt ma jintmess
4. **Truncation iebes** — jekk it-test wara l-kollass għadu jaqbeż `maxTextChars` (default 50,000), jonqos b'ħjiel ta' navigazzjoni sabiex l-aġent ikun jista' jkompli jaħdem

### Post tal-magna

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfigurazzjoni

Ikkontrollat minn `compression.mcpAccessibility` f'ambjenti globali (migrazzjoni 056). Konfigurazzjoni default:

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

Il-filtru huwa applikat biss għal payloads li jirriżultaw mill-għodda li `type` tagħhom huwa `"text"` u li t-tul tagħhom jaqbeż `minLengthToProcess`. Ma taffettwax il-kompressjoni fil-pront jew it-talba payloads.

### Iffrankar mistenni

60–80% fuq ir-riżultati tal-għodda tal-istampar tal-browser, skont il-kumplessità tal-paġna. L-algoritmu tal-kollass huwa O(n) fl-għadd tal-linji u jżid latenza negliġibbli.

### Dan il-filtru vs il-magni tal-kompressjoni hawn fuq

| Aspett    | Caveman / RTK / Stacked            | MCP filtru accessibility               |
| --------- | ---------------------------------- | -------------------------------------- |
| Mira      | Talba prompts / kuntest            | MCP tool results                       |
| Trigger   | Issettjar tal-mod ta 'kompressjoni | `compression.mcpAccessibility.enabled` |
| Ambitu    | Messaggi kollha SSE                | Riżultati tal-għodda biss              |
| Ref ankri | N/A                                | Ippreservat bla kundizzjoni            |

---

## Kompressjoni Combos

Il-kompressjonijiet tal-kompressjoni jissejħu profili tal-kompressjoni li jistgħu jiġu assenjati lil combos tar-routing:

- `compression_combos`: jaħżen il-mod, pipeline, konfigurazzjoni RTK, konfigurazzjoni tal-lingwa, u markatur default
- `compression_combo_assignments`: jimmappja kombinazzjoni ta' kompressjoni għal combo tar-routing
- L-integrazzjoni tal-runtime issolvi combo ta' kompressjoni assenjat qabel ma l-combo ġeneriku jegħleb
- analytics jinkludu `compression_combo_id` u `engine`

Wiċċ tad-dashboard: `Dashboard -> Context & Cache -> Compression Combos`.

## Prerekwiżiti / gwida għall-operatur (CCR & session-dedup)

CCR (`ccr`) u `session-dedup` jissostitwixxu jew elide test u jħallu a** markatur** wara. Din it-taqsima hija r-referenza tal-operatur għall-wajers ta 'klijent, il-qari taż-żewġ markaturi, u l-irkupru jew id-dijanjosi tal-kontenut elided. Mekkaniċi ta 'kull magna huma koperti hawn fuq; dan huwa s-saff "kif nista' nmexxiha".

### Trasporti u endpoints

Is-server MCP li jesponi l-għodod CCR jista 'jintlaħaq tliet modi. Il-bażi default URL hija `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Trasport                               | URL / kmand                             | Noti                                                                                                                                    |
| -------------------------------------- | --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| HTTP Streamable (klijent, rakkomandat) | `http://localhost:20128/api/mcp/stream` | L-endpoint attwali MCP klijenti jitkellmu miegħu.                                                                                       |
| Legacy SSE singleton                   | `http://localhost:20128/api/mcp/sse`    | Trasport singleton anzjani. Huwa** jagħlaq** sessjonijiet streamable; uża `streamable-http` clients kontra `/api/mcp/stream`, mhux dan. |
| stdio                                  | `omniroute --mcp`                       | Għal IDE MCP config li tbid il-proċess. M'hemm l-ebda bandiera `--dev` ; `omniroute --mcp` huwa l-punt tad-dħul stdio.                  |

### Saffi tal-ħażna (dak li jibqa' ħaj minn bidu mill-ġdid)

CCR hija a** żewġ saffi** maħżen, mhux fil-memorja biss:

- **Saff sħun fil-memorja** — per-block cap 2 MiB, per-principal 16 MiB, global 64 MiB. L-iskrizzjonijiet default għal 24 h TTL (massimu 7 ijiem). L-irkupru sħiħ MCP mill-memorja huwa limitat għal 256 KiB; xi ħaġa akbar għadha tintlaħaq permezz tal-modi ranged / grep.
- **Saff SQLite durabbli** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, on by default) — jappoġġa l-livell fil-memorja sabiex blokka tibqa 'ħajja żgumbrament LRU, restart, jew irkuprar inżul f'istanza oħra. Ir-ringiela żżomm iż- TTL tal-blokk , għalhekk blokk li jgħaddi TTL tiegħu jkun marret miż-żewġ saffi.

Tliet gwardji jżommu s-saff dejjiemi marbut — blokka tibqa' memorja biss meta:

1. il-blokk spiċċa** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. ir-runtime huwa sħaba runtime (l-ebda disk lokali);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Allura "il-blokk sparixxa" mhix storja ta' bidu mill-ġdid kutra: blokka sub-512 KB fuq runtime lokali, mhux sħaba tibqa' ħaj minn bidu mill-ġdid permezz tal-livell durabbli sakemm jispiċċa TTL tagħha. Ara [referenza għall-Ambjent](../reference/ENVIRONMENT.md) għall-varjabbli.

### Iż-żewġ markaturi

| Marker                                | Tifsira                                                                                                                                           | X'għandu jagħmel il-mudell                                                                                                                                                                                      |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Blokk kbir kien maħżun kontenut indirizzat.                                                                                                       | Ċempel `omniroute_ccr_retrieve` mal-** 24-hex hash ikkupjat verbatim** biex tikseb it-test oriġinali lura.                                                                                                      |
| `[dedup:ref sha=…]`                   | `session-dedup` elided test diġà mibgħut f'dawra aktar kmieni tal-istess sessjoni. Din hija an** ħarsa intenzjonata lura** , mhux telf jew żball. | Do** le** sejħa kwalunkwe għodda u tagħmel** le** ipprova "jibni mill-ġdid". L-ewwel okkorrenza tat-test hija l-kopja kanonika; id-dawra attwali qatt ma tinkiteb mill-ġdid, hija deduppata f'dawra aktar tard. |

Il-ħarsa lura `[dedup:ref]` hija deċiżjoni deliberata ta' protokoll — m'hemm l-ebda rikostruzzjoni minn qabel. Ittrattaha bħala "dan it-test eżatt kien diġà fuq il-wajer aktar kmieni f'din is-sessjoni."

### Prerekwiżiti tal-klijenti

- **Ċavetta (stdio):** min iċempel stdio ma jġorr l-ebda identità għal kull talba, għalhekk jawtentika `OMNIROUTE_API_KEY` (settjat fil- `env` tas-server MCP ). Mingħajrha min iċempel huwa anonimu u għodod li jeħtieġu prinċipali jistgħu jiddegradaw.
- **`tools[]` hija l-prekundizzjoni tal-injezzjoni.** L-istruzzjoni CCR retrieve-protocol (#8033) hija injettata** biss** meta l- `tools[]` reklamat tat-talba jipprova li l-klijent jista 'attwalment jilħaq `omniroute_ccr_retrieve`. It-taqbila hija taqbila ta' segment ta' wara mdawra b'separatur (`__`, `.`, `/`, `:`) — qatt ma substring vojta — għalhekk isem spazjat bl-isem bħal `mcp__gateway__omniroute_ccr_retrieve` għadu jgħodd. `tools[]` assenti jew li ma jaqbilx ifisser li l-istruzzjoni hija _mhux_ injettata, bid-disinn.
- **`codemode:false` ( klijenti OpenCode ).** OpenCode default għall-Modalità tal-Kodiċi, li tirreklama biss l-għodod indiġeni tagħha lill-mudell u** ma** poġġi għodod MCP fuq il-lista nattiva `tools[]`. Issettja `codemode: false` fuq id-dħul tas-server MCP sabiex l-għodod `omniroute_ccr_*` jiġu reklamati. Din hija a** klijent** setting, mhux OmniRoute wahda. L-istruzzjoni CCR għadha ma tiġix injettata: OpenCode issemmi għodda `<server>_<tool>`, għalhekk server imsejjaħ `omniroute` jesponi `omniroute_omniroute_ccr_retrieve`, u `_` mhuwiex wieħed mis-separaturi mqabbla.
- **Prinċipali.** Il-ħażna u l-irkupru huma iżolati għal kull prinċipal awtentikat (għal kull ċavetta API ). Ċavetta tara l-blokki tagħha stess biss.

### Ambiti għal kull għodda

L-infurzar tal-ambitu huwa dejjem mixgħul għal min iċempel HTTP/SSE b'ambitu dejjaq. L-għodod CCR `omniroute_` jeħtieġu:

| Għodda                   | Ambitu              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Ambitu nieqes jirritorna an**MCP tool error result** (`isError: true`, mhux HTTP 403 — iż- `403 LOCAL_ONLY` hija l-awth separata tal-loopback route-guard): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Ċavetta remota minima tista 'żżomm `mcp:connect` (jawtorizza l- `/api/mcp/` local-only carve-out) flimkien mal-ambitu read/write speċifiku li teħtieġ.

### Matriċi tal-klijenti

| Klijent                | Trasport                                        | Konfigurazzjoni biex tuża                                                                                                                                                                                                                               | `tools[]` reklamata? (struzzjoni → CCR injettata)                                                                                                                                                    |
| ---------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude Code            | streamable-http                                 | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                       | Iva — MCP-kapaci; injettat.                                                                                                                                                                          |
| Cursor / Cline         | `stdio`** jew** `streamable-http`               | stdio: `omniroute --mcp` with `OMNIROUTE_API_KEY` in `env`; jew daħla MCP remota li tipponta lejn `http://localhost:20128/api/mcp/stream` (ara [Gwida ta' Setup → MCP Konfigurazzjoni tal-Klijent](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Iva — jirreklama l-għodda `omniroute_ccr_*`.                                                                                                                                                         |
| OpenCode               | streamable-http                                 | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, flimkien ma `codemode: false`                                                                                                                                                 | Għodod reklamati biss bi `codemode: false`; l-istruzzjoni għadha mhix injettata, minħabba li `omniroute_omniroute_ccr_retrieve` ma taqbilx (ara [Prerekwiżiti tal-Klijent](#client-prerequisites) ). |
| Kompatibbli ma' OpenAI | HTTP kompatibbli mal-OpenAI (kompleti taċ-chat) | klijent standard ta 'chat-completions kontra l-endpoint kompatibbli ma' OpenAI                                                                                                                                                                          | **Qatt** — sejjieħ sempliċi kompatibbli mal-OpenAI qatt ma jingħad li jsejjaħ l-għodda, u l-istruzzjoni ma tiġix injettata.                                                                          |

### Limiti ta' rkupru u paġinazzjoni

Ir-riżultati tat-test tal-għodda MCP huma maqtugħin madwar `mcpAccessibility.maxTextChars` (default `50000`). A `full` retrieve ta 'blokk huwa limitat għal 256 KiB —** m'hemm l-ebda irkupru sħiħ bla limitu** . Meta `chars=N` ta 'blokk ikun kbir, iċċempjaha minflok tiġbed il-ħaġa sħiħa:

- Regola ġenerali:**`chars > 40000` → uża `mode`** , qatt ma vojta sħiħa.
- `mode:"grep"` — regex `pattern` imqabbla linja b'linja, sa 1,000 linja li jaqblu (`unique: true` drops repeats), l-irħas għal "sib il-linja waħda li għandi bżonn."
- `mode:"lines"` — firxa linja indiċjata 1; jeħtieġ kemm `start` kif ukoll `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` lines.
- `mode:"stats"` — linja, karattru, u l-għadd tal-byte mingħajr il-korp.

Uża `mode:"lines"` ma `start`/`end` biex timxi blokka twila fil-paġni aktar milli titlob il-ħaġa sħiħa f'daqqa.

### Ismijiet tal-għodda

L-għodda tal-irkuprar bħalissa hija msejħa `omniroute_ccr_retrieve` (il-prefiss `omniroute_` huwa soluzzjoni datata għall-ħabtiet tal-ismijiet bejn is-server). Isem ta' għodda b'suffiss limitat aktar nadif u soluzzjoni għal riżultati MCP JSON maqtugħin f'nofs is-sekwenza huma ssorveljati bħala segwitu upstream; din il-paġna tiddokumenta l-imġieba kurrenti, mibgħuta biss.

### Ċiklu tal-ħajja tas-sessjoni

Sessjonijiet Streamable-HTTP idle out u s-server jaħsadhom; it-tieqa idle hija l-kostanti `MCP_SESSION_IDLE_MS` (referenzjata bl-isem, mhux valur hardcoded, għalhekk din il-paġna ma tgħaddix meta tinbidel). Is-sintomu ta' sessjoni idle-reaped huwa HTTP 404 `Unknown Mcp-Session-Id` — ir-rimedju huwa li terġa' tgħaqqad jew terġa' tibda s-sessjoni,** le** biex iddawwar ċavetta, tibdel ambitu, jew tibdel isem għodda.

## API Wifi

| Rotta                                  | Għan                                                                    |
| -------------------------------------- | ----------------------------------------------------------------------- |
| `/api/settings/compression`            | Issettjar tal-kompressjoni globali (jinkludi `mcpAccessibility` config) |
| `/api/compression/preview`             | Preview kwalunkwe mod ta 'kompressjoni                                  |
| `/api/compression/language-packs`      | Elenka l-pakketti tal-lingwa Caveman disponibbli                        |
| `/api/context/caveman/config`          | Caveman settings alias                                                  |
| `/api/context/rtk/config`              | RTK defaults u settings                                                 |
| `/api/context/rtk/filters`             | katalogu tal-filtru RTK                                                 |
| `/api/context/rtk/test`                | RTK preview/test endpoint                                               |
| `/api/context/rtk/raw-output/[id]`     | Irkupru tal-output mhux ipproċessat awtentikat                          |
| `/api/context/combos`                  | Compression combo CRUD                                                  |
| `/api/context/combos/[id]/assignments` | Routing-combo assignment CRUD                                           |
| `/api/context/analytics`               | Psewdonimi tal-analiżi tal-kompressjoni                                 |

Ir-rotot tal-ġestjoni jeħtieġu awtentikazzjoni tal-ġestjoni jew kontrolli tal-politika tal-API-key.

## MCP Għodda

Il-kompressjoni tesponi ħames għodod MCP :

| Għodda                              | Ambitu              | Għan                                    |
| ----------------------------------- | ------------------- | --------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Settings, analiżi, stats tal-cache      |
| `omniroute_compression_configure`   | `write:compression` | Aġġorna s-settings globali              |
| `omniroute_set_compression_engine`  | `write:compression` | Issettja l-mod u l-pipeline fakultattiv |
| `omniroute_list_compression_combos` | `read:compression`  | Lista combos ta 'kompressjoni           |
| `omniroute_compression_combo_stats` | `read:compression`  | combo/engine analytics                  |

## Skop u esklużjonijiet

**L-inkorporazzjonijiet qatt ma huma kkompressati.** `open-sse/handlers/embeddings.ts` qatt ma ssejjaħ l-ebda magna tal-kompressjoni — il-korpi request/response jgħaddu dritt lejn l-eżekutur mhux mittiefsa. Dan huwa strutturali llum (l-embeddings u t-tlestijiet taċ-chat huma disjoint handlers), mhux verifika tar-runtime, iżda dan ifisser li t-tħassib dwar id-distorsjoni tal-vettur #8034 m'għandu l-ebda wiċċ ta 'espożizzjoni fil-mogħdija tal-inkorporazzjonijiet.

**Per-model/endpoint exclusion filter (#8034).** Għat-tlestija taċ-chat, operatur jista' jsemmi miri tal-mudell ids / `provider/model` li qatt m'għandhom jiġu kkompressati — a guardrail utli jekk il-kompressjoni hija qatt wired eqreb lejn mogħdija ta' ħdejn inkorporati aktar tard, u ġeneralment utli għal kwalunkwe mudell li tiegħu eżattament byte-għal-byte kwistjonijiet fil-pront (evals deterministiċi, prefissi sensittivi għall-cache, eċċ).

- Settings field: `exclusions?: string[]` fuq il-konfigurazzjoni tal-kompressjoni globali (`GET`/`PUT /api/settings/compression`), ppersistew permezz tal-ispazju tal-isem tal-kompressjoni eżistenti `key_value` (`src/lib/db/compression.ts`) — l-ebda tabella ġdida.
- Tab tad-daxxbord:** Dashboard → Kompressjoni → Esklużjonijiet** (`/dashboard/compression/exclusions`).
- Sintassi tal-mudell: `*` hija l-unika wildcard. Kull metakaratteru regex ieħor f'mudell huwa maħruba qabel it-tqabbil, għalhekk `gpt-5.6` jaqbel mas-sekwenza letterali biss, qatt ma `gpt-5x6` (ReDoS-safe, bounded, no nested quantifiers). Il-mudelli jaqblu b'mod insensittiv għall-każ kemm mal-id tal-mudell vojt kif ukoll mal- `provider/model` kompost — `gpt-5-6`, `openai/gpt-5-6`, u `openai/*` ix-xogħol kollu, u `*` waħdu jeskludi kull mudell.
- Tqabbil: `isCompressionExcluded()` / `normalizeCompressionExclusions()` fi `open-sse/services/compression/exclusions.ts`. `chatCore.ts` jiċċekkja l-mira eskluża eżatt wara li ssolvi l-issettjar tal-kompressjoni,** qabel ma taħdem xi magna** , u tittratta taqbila eżattament bħall-kompressjoni li hija diżattivata globalment — il-korp tat-talba huwa b'mod evidenti identiku għall-byte. L-iskip huwa rreġistrat permezz ta' `writeCompressionSkip(..., "excluded")` għal viżibilità analitika.
- Default (lista empty/absent ): identiku għal pre-#8034 imġieba — xejn mhu eskluż.

## Limitazzjonijiet magħrufa

- **LLMLingua-2 (SLM) teħtieġ deps fakultattivi ko-lokati.** Il-ħaddiem jaħdem biss fi produzzjoni build meta `@atjsh/llmlingua-2` + peers ikunu ko-lokati `dist/node_modules` (ara `scripts/build/colocateOptionals.mjs`, #4286). Mingħajrhom il-magna fail-open (jirritorna t-test oriġinali). Ir-riżoluzzjoni tal-ħaddiem m'għadhiex tiddependi fuq `import.meta.url` (tmut fil-pakkett waħdu) — hija ankra fuq ir-runtime cwd / `argv[1]`.
- **Il-pakketti tal-lingwa Caveman `de` / `fr` / `ja` huma parzjali.** Jibgħatu regoli `context` + `filler` + `structural` iżda l-ebda pakketti `dedup` / `ultra`, għalhekk l-intensità `ultra` mhix aktar b'saħħitha minn `full` għal dawk il-lingwi (huma jużaw biss ir-regoli tagħhom stess — m'hemm l-ebda tnaqqis siekta għar-regoli Ingliżi `dedup`/`ultra`, li mangle test barrani). `en` / `es` / `id` / `pt-BR` huma kompluti. Kontribuzzjonijiet ta' `dedup.json` + `ultra.json` għall-pakketti parzjali huma milqugħa.
- **Telemetrija f'munzelli telenka biss magni li kkompressaw.** Stacked-pipeline step li l-magna tiegħu dam imma pproduċiet 0 % ta' tfaddil `stats:null` u għalhekk ma jidhirx `engineBreakdown` — indistingwibbli minn pass li nqabeż. Id-distinzjoni ta' "ra, 0 %" minn "qabża" tkun teħtieġ bidla fil-mudell ta' tqassim u hija differita.

## Validazzjoni

Il-gradi ffukati għal din iż-żona huma:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
