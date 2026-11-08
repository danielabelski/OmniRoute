# Compression Engines (Norsk)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompresjon er bygget rundt motorkontrakter. En modus kan kjøre én motor direkte (`caveman` eller `rtk`) eller en deterministisk stablet rørledning som kjører flere motorer i rekkefølge.

## Modi

| Modus        | Motorvei                                                                                  | Tiltenkt innspill                                            |
| ------------ | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| `off`        | ingen                                                                                     | Nøyaktig umiddelbar bevaring                                 |
| `lite`       | Caveman lite hjelpere                                                                     | Alltid-på-opprydding med lav risiko                          |
| `standard`   | Hulemann                                                                                  | Språkkondensering på naturlig språk                          |
| `aggressive` | Caveman + history/tool oppsummerere                                                       | Lange chat-økter                                             |
| `ultra`      | Caveman + beskjæringshjelpere                                                             | Gjenoppretting av kontekstgrense                             |
| `rtk`        | RTK                                                                                       | Terminal, shell, build, test og git-utgang                   |
| `omniglyph`  | OmniGlyph                                                                                 | Kontekst-som-bilde på den opprinnelige leverandørens ledning |
| `stacked`    | Rørledning. Standardinnstillingen er `session-dedup -> lite`. `rtk -> caveman` er opt-in. | Blandede verktøylogger og prosa, maksimale besparelser       |

### OmniGlyph kompresjonsprofiler

`omniglyph` motoren (pakke `omniglyph`, 1.4.0 +) aksepterer en navngitt semantisk profil, satt globalt gjennom `omniglyph.profile` i komprimeringsinnstillingene eller per trinn gjennom den stablede rørledningens trinnkonfigurasjon:

| Profil        | Grense                                                                                                     |
| ------------- | ---------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Misligholde. Policyen de publiserte kvitteringene målte — -bildesystem, verktøydokumenter og tett historie |
| `balanced`    | Holder live state native, beskytter de siste 8 svingene, kollapser eldre lukket historie                   |
| `coding-safe` | Holder autoritet, verktøyskjemaer og live verktøyutgang native, beskytter de siste 12 svingene             |
| `passthrough` | Ruter uten transformasjon; motoren hoppes over                                                             |

Profilen er en** tak, ikke et gulv** : `mergeCompressionProfileOptions` i pakken nekter å la en innringer overstyre gjenåpne en tapsbasert bane profilen stengt, så en per-trinns `preserveSystemPrompt: false` kan ikke reaktivere systemkomprimering under `coding-safe`.

Målt på denne kodebasen: `coding-safe` og `balanced` hever `minCompressChars` til sitt maksimum og beholder system, verktøyskjemaer og verktøyresultater native, slik at en økt som ikke har akkumulert historie ennå stopper ved `below_min_chars` og motoren transformerer ingenting. Det er derfor standarden er `aggressive` i stedet for den sikreste profilen.

Pakken løser sitt eget modellomfang og profil fra miljøkonfigurasjonen. OmniRoute delegerer aldri avgjørelsen: adapteren fester modellporten til pakkens mest restriktive omfang, så vertsmiljøinnstillinger kan bare begrense tillatelseslisten, aldri utvide den forbi OmniRoute målte kvitteringer.

## Motorregister

Registeret bor i `open-sse/services/compression/engines/registry.ts`. Motorer viser en delt kontrakt:

- `id`: stabil motor-ID som `caveman` eller `rtk`
- `apply(text, config)`: eldre utførelsesbane brukt av stablede rørledninger
- `compress(input, config)`: primær utførelsesbane som returnerer tekst + -statistikk
- `getConfigSchema()`: returnerer den JSON-skjema-lignende formen til gyldig konfig
- `validateConfig(config)`: returnerer `{ valid, errors[] }`

Registrering bruker `registerCompressionEngine(engine)` (eller `registerEngine` for avanserte tilfeller), som kaller `assertValidEngine()` og `validateConfig(defaultConfig)` før den godtas. Bruk `unregisterCompressionEngine(id)` for å fjerne en motor under drift.

`strategySelector.ts` registrerer de innebygde motorene før kompresjonen går. Dette lar forhåndsvisning, kjøretidskomprimering, stablet modus, tester og fremtidige motorer bruke samme utførelsesvei.

### MCP beskrivelseskomprimering (relatert)

Et eget register komprimerer metadata MCP verktøybeskrivelse på registernivå — se `open-sse/mcp-server/descriptionCompressor.ts` og [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Den gjenbruker Caveman-regler, men opererer på verktøymetadata, ikke forespørselsnyttelast.

### Ekstra innebygde motorer

Utover Caveman, RTK og LLMLingua-2, sender registeret flere spesialiserte tapsfrie / strukturelle motorer (brukt av stablede rørledninger, lekeplassen og tester):

| Motor         | ID              | Hva den gjør                                                                                                                                                                   |
| ------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): erstatter store sammenhengende tekstblokker med innholdsadresserte referanser, så repeated/large blokker sendes én gang og refereres deretter. |
| takhøyde      | `headroom`      | SmartCrusher (H3 + N5): tapsfri tabellkomprimering av homogene JSON-array-nyttelaster til en søyleformet `[N rows]` form.                                                      |
| ionisator     | `ionizer`       | Head/middle/tail radsampling for veldig store homogene blokker, lagrer den eliderte midten som en CCR -innholdsadressert referanse.                                            |
| session-dedup | `session-dedup` | Innholdsadressert kryssvendingsdeduplisering (TokenMizer-inspirert): fjerner tekst som allerede er sett i tidligere svinger i samme økt.                                       |

**CCR gjenopprettingsprotokollinstruksjon (#8033):** første gang CCR erstatter ≥ 1 blokk i en forespørsel, legger motoren en enkelt, idempotent `system` -melding (som leder med `[CCR protocol]` vaktposten) som lærer den som ringer markøren → verktøykontrakten: hva en `[CCR retrieve hash=<24hex> chars=N]` markør betyr, at hashen må kopieres ordrett (alle 24 heksede tegn — feilkopi er sannsynligvis ikke funnet en årsak til feil-kopier) `[dedup:ref sha=...]` -markør betyr "se tilbake i historien", ikke "ring verktøyet". Seddelen er injisert** bare når anroperens annonserte `tools[]` beviser at den faktisk kan nå `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — en vanlig OpenAI-kompatibel oppringer uten det verktøyet mottar aldri en instruksjon om å ringe noe den ikke kan nå. Idempotens håndheves ved å skanne meldingshistorikken for vaktposten før injisering, slik at forespørsler om flere svinger (som spiller av tidligere meldinger på nytt) ikke stables lappen en gang per tur.

## Hulemann

Caveman-modus fokuserer på semantisk kondensering av normal prosa:

- bevarer kodeblokker, URLs, JSON, baner og strukturerte data
- fjerner filler, hedging, gjentatt kontekst og detaljerte bindende fraseringer
- støtter språkbevisste filregelpakker i `open-sse/services/compression/rules/`
- forblir tilgjengelig gjennom de gamle `standard`, `aggressive` og `ultra` -modusene

Dashbordoverflaten er `Dashboard -> Context & Cache -> Caveman`.

Caveman oppstrøms rapporterer `~75%` færre output tokens, `65%` gjennomsnittlige output besparelser i benchmarks med en `22-87%` range, og et `~46%` input-compression tool. OmniRoute bruker Caveman-inndatanummeret når han dokumenterer stablede prompt/context sparinger; Caveman-utgangsmodus forblir en separat respons-atferdsfunksjon.

## RTK

RTK modus fokuserer på kommando- og verktøyutgang:

- oppdager utgangsklasser som `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go -tester, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logger, shell `find`/`grep`, stackspor og generiske logger
- bruker 49 JSON filtre fra `open-sse/services/compression/engines/rtk/filters/`
- støtter den deklarative pipeline i RTK-stil: ANSI stripping, replace, match-output kortslutning, strip/keep linjer, per-line trunkering, head/tail/max-line trunkering og on-empty fallback
- støtter trust-gatede prosjektfiltre i `.rtk/filters.json` og globale filtre i `DATA_DIR/rtk/filters.json`
- striper ANSI -sekvenser, fremdriftsstøy, gjentatte linjer og lite hjelpsom kjeleplate
- bevarer handlingsbare feil, advarsler, sammendrag, endrede filer og halekontekst
- kan valgfritt beholde redigert råutgang for recovery/debugging gjennom autentiserte administrasjonsruter

Dashbordoverflaten er `Dashboard -> Context & Cache -> RTK`.

Driftsdetaljer for tilpassede filtre, tillit, verifisering og gjenoppretting av råutdata live i [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK oppstrøms rapporterer `60-90%` besparelser for kommando-utdata-komprimering. README eksemplet viser en 30-minutters Claude Code-økt som går fra `~118,000` tokens til `~23,900`, eller `79.7%` lagret.

## LLMLingua-2 (semantisk beskjæring)

LLMLingua-2 modus utfører** semantisk tokenbeskjæring** på prosa ved å bruke en liten ONNX -tokenklassifisering, som komplementerer de regelbaserte Caveman- og RTK -motorene:

- komprimerer kun prosa i ikke-systemmeldinger; inngjerdede kodeblokker og andre bevarte konstruksjoner blir aldri endret
- kjører `@atjsh/llmlingua-2` backend (ONNX via `@huggingface/transformers`) i en arbeidstråd, så modellslutning blokkerer aldri forespørselshendelsesløkken
- er** stables** (`stackPriority` 35): i en stablet pipeline kjører den etter strukturmotorene (CCR, session-dedup, headroom, Caveman) men før `ultra`, siden semantisk beskjæring er mest effektiv på allerede strukturelt komprimert tekst — f.eks. `rtk -> caveman -> llmlingua`
- **feil-åpner ved enhver feil** (mangler valgfrie deps, worker spawn, modellbelastning, inferens eller tidsavbrudd) → den opprinnelige teksten returneres uendret, aldri en feil

Motorens plassering: `open-sse/services/compression/engines/llmlingua/`. Overflaten på dashbordet er `Dashboard -> Context & Cache -> LLMLingua`.

### Modeller

Standardmodellen er**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, rask). En høyere nøyaktighet** BERT-base** modell (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) er tilgjengelig via motorkonfigurasjonsfeltet `model`. `@huggingface/transformers` laster ned den valgte modellen dovent fra HuggingFace Hub til `${DATA_DIR}/models/llmlingua` ved det første anropet (`modelStore.ts`); en `modelPath` -konfigurasjonsoverstyring peker den mot en lokal kopi i stedet (offline/installasjoner uten luft).

### Valgfrie avhengigheter og installasjon på forespørsel

Den beskjærbare LLMLingua runtime peer-stabelen er** valgfri** . To pakker er deklarert som `optionalDependencies` i `package.json` og beholdes** utvendig** av produksjonsbygget (`scripts/build/prepublish.ts` pakker dem ikke):

| Pakke                | Versjon (pinne) | Notater                                           |
| -------------------- | --------------- | ------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`         | Inngangspakke; erklærer de andre som jevnaldrende |
| `js-tiktoken`        | `^1.0.20`       | Tokenizer                                         |

`@huggingface/transformers` er festet til `^4.2.0` (delt med den lokale innebyggingsbanen og spores også inn i den frittstående pakken); `@atjsh/llmlingua-2@2.0.5` peer på den med `"^3.5.2 || ^4.0.0"`, så både Transformers.js v3 og v4 støttes. Siden 2.0.4 krever `@atjsh/llmlingua-2` ikke lenger `@tensorflow/tfjs`, som fjernet den største enkeltbidragsyteren (TensorFlow.js) fra SLM stakken. Bare de to pakkene ovenfor er beskjærbare SLM kamerater. En standard `npm install` (dev) installerer den valgfrie stabelen automatisk med mindre valgfrie avhengigheter er utelatt.

**Hvorfor på forespørsel:** den npm-publiserte pakken, den frittstående pakken og Docker -bildeskipet** uten** disse deps for å holde seg slank. Når de er fraværende, svikter arbeiderens avhengighetsport (en `@atjsh/llmlingua-2` resolve probe i `worker.ts`) og motoren** fail-åpner stille** — å velge LLMLingua blir en no-op (tekst returnert uendret, ingen feil logget). For å aktivere den i et beskjært miljø, installer den valgfrie stabelen:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` fjerningen (2.0.4 +) eliminerer den tidligere dominerende ~ 800 MB bidragsyteren — det gjenværende fotavtrykket er transformers.js + onnxruntime-node-kjøretidene, pluss TinyBERT modellen (~ 57 MB) lastet ned ved første bruk (ikke via npm).

Per miljø:

- **Dev / `npm install`** — installeres automatisk med mindre du passerte `--omit=optional` (eller `--no-optional`). Ingen handling nødvendig.
- **Global npm (`npm i -g omniroute`) / frittstående** — kjør installeringskommandoen ovenfor i den installerte pakkekatalogen, eller installer på nytt uten å utelate valgfrie deps.
- **Docker** — legg til installeringskommandoen i et avledet bildelag; det publiserte bildet leveres slankt av design.
- **VPS (PM2)** — installer i appens `node_modules`, og start deretter prosessen på nytt slik at arbeideren undersøker porten på nytt.
- **Raw Next frittstående (`npm run build` → `.build/next/standalone/server.js`)** — den frittstående sporingen sendes NEITHER arbeideren eller de valgfrie depsene, så motoren feilåpnes stille. `scripts/build/colocate-standalone.mjs` bruker begge på nytt (worker esbuild + optional-dep closure inn i det frittstående treet); den kjører automatisk via `postbuild` npm-kroken etter hvert bygg. Idempotent, feilmyk når deps er fraværende.

**Bekreft at den er aktiv:** med LLMLingua valgt, krymper ekte prosa faktisk (motoren stopper feilåpning), og den første forespørselen utløser modellnedlastingen til `${DATA_DIR}/models/llmlingua`. Porten sonderer med vilje bare `@atjsh/llmlingua-2` — de andre peerne er ESM-only og `require.resolve` kaster på dem selv når de er tilstede — slik at arbeideren fortsatt feil-åpner hvis noen peer virkelig mangler på `import()` tidspunktet.

## Stablede rørledninger

Stablet modus kjører rørledningstrinn i rekkefølge. Standard er:

```txt
rtk -> caveman
```

Bruk dette for koding-agent-sesjoner der en ledetekst kombinerer kommandoutgang med menneskelig eller assistentprosa. RTK reduserer støyende verktøylogger først, deretter komprimerer Caveman gjenværende naturlig språk.

Rørledningstrinn er konfigurert med `stackedPipeline` i kompresjonsinnstillinger eller gjennom kompresjonskombinasjoner.

Når begge motorene reduserer den samme kvalifiserte nyttelasten, vil sparesammensetningen:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Tilgjengelighetstrefilter

MCP accessibility-tree smart-filteret er et komprimeringslag etter utførelse som kjører på MCP** verktøyresultater** , ikke på ledetekster eller kontekst. Den retter seg mot det detaljerte tilgjengelighetstreet og nettleserens snapshot-nyttelaster som returneres av verktøy som Playwright, datamaskinbruk og nettleserautomatisering MCP servere.

### Hva den gjør

1. **Støyfjerning** — fjerner tomme generic/text -oppføringer (`- generic:`, `- text: ""`)
2. **Søsken kollapser** — når ≥ `collapseThreshold` (standard 30) påfølgende linjer er strukturelle repetisjoner, kollapser dem til de første `collapseKeepHead` (standard 10) linjene + en oppsummering av antall + de siste `collapseKeepTail` (standard 5) linjene
3. **Ref konservering** — `[ref=eXX]` -ankere som kreves av Playwright/computer-use, berøres aldri
4. **Hard avkorting** — hvis teksten etter kollaps fortsatt overstiger `maxTextChars` (standard 50 000), avkortes med et navigasjonshint slik at agenten kan fortsette å jobbe

### Motorens plassering

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfigurasjon

Kontrollert av `compression.mcpAccessibility` i globale innstillinger (migrering 056). Standard konfigurasjon:

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

Filteret brukes bare på nyttelaster med verktøyresultater hvis `type` er `"text"` og hvis lengde overstiger `minLengthToProcess`. Det påvirker ikke promptkomprimering eller forespørselsnyttelast.

### Forventet besparelse

60–80 % på resultater av nettleserøyeblikksbilder, avhengig av sidens kompleksitet. Kollapsalgoritmen er O(n) i linjetelling og legger til ubetydelig latens.

### Dette filteret kontra kompresjonsmotorene ovenfor

| Aspekt     | Hulemann / RTK / stablet          | MCP tilgjengelighetsfilter             |
| ---------- | --------------------------------- | -------------------------------------- |
| Mål        | Forespørsler/kontekst             | MCP -verktøyresultater                 |
| Avtrekker  | Innstilling av komprimeringsmodus | `compression.mcpAccessibility.enabled` |
| Omfang     | Alle SSE -meldinger               | Kun verktøyresultater                  |
| Ref ankere | N/A                               | Bevart ubetinget                       |

---

## Komprimeringskombinasjoner

Kompresjonskombinasjoner er navngitte komprimeringsprofiler som kan tilordnes til rutingkombinasjoner:

- `compression_combos`: lagrer modus, pipeline, RTK config, language config og standardmarkør
- `compression_combo_assignments`: kartlegger en kompresjonskombinasjon til en rutingkombinasjon
- runtime-integrasjon løser en tildelt kompresjonskombinasjon før generisk kombinasjon overstyrer
- analyser inkluderer `compression_combo_id` og `engine`

Dashbordoverflate: `Dashboard -> Context & Cache -> Compression Combos`.

## Forutsetninger / operatørveiledning (CCR & session-dedup)

CCR (`ccr`) og `session-dedup` erstatter eller fjerner tekst og la a** markør** bak. Denne delen er operatørreferansen for å koble en klient opp, lese de to markørene og hente eller diagnostisere det eliderte innholdet. Mekanikken til hver motor er dekket ovenfor; dette er "hvordan kjører jeg det"-laget.

### Transporter og endepunkter

MCP serveren som avslører CCR verktøyene kan nås på tre måter. Standardbasen URL er `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transportere                      | URL / kommando                          | Notater                                                                                                                        |
| --------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Streambar HTTP (klient, anbefalt) | `http://localhost:20128/api/mcp/stream` | Endepunktet gjeldende MCP klienter snakker med.                                                                                |
| Legacy SSE singleton              | `http://localhost:20128/api/mcp/sse`    | Eldre singleton transport. Den** lukkes** streambare økter; bruk `streamable-http` klienter mot `/api/mcp/stream`, ikke denne. |
| stdio                             | `omniroute --mcp`                       | For IDE MCP config som skaper prosessen. Det er ikke noe `--dev` flagg; `omniroute --mcp` er inngangspunktet for stdio.        |

### Lagringsnivåer (det som overlever en omstart)

CCR er en** to-lags** butikk, ikke bare i minnet:

- **Varmt nivå i minnet** — per-blokk cap 2 MiB, per-principal 16 MiB, global 64 MiB. Oppføringer er som standard en 24 timers TTL (maksimalt 7 dager). Full MCP henting fra minnet er begrenset til 256 KiB; noe større er fortsatt tilgjengelig gjennom ranged / grep-modusene.
- **Slitesterk SQLite -lag** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, på som standard) — støtter minnenivået slik at en blokk overlever LRU utkastelse, en omstart eller en gjenoppretting som lander på en annen instans. Raden beholder blokkens TTL, så en blokk forbi TTL er borte fra begge nivåene.

Tre vakter holder det holdbare nivået avgrenset — en blokk forblir bare minnet når:

1. blokken er over** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. kjøretiden er en skykjøring (ingen lokal disk);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Så "blokken forsvant" er ikke en generell omstartshistorie: en sub-512 KB blokk på en lokal, ikke-sky-kjøretid overlever en omstart via det varige nivået til dens TTL går tom. Se [miljøreferanse](../reference/ENVIRONMENT.md) for variabelen.

### De to markørene

| Markør                                | Betydning                                                                                                                                     | Hva modellen skal gjøre                                                                                                                                                                                                 |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | En stor blokk ble lagret innholdsadressert.                                                                                                   | Ring `omniroute_ccr_retrieve` med** 24-hex hash kopiert ordrett** for å få tilbake den opprinnelige teksten.                                                                                                            |
| `[dedup:ref sha=…]`                   | `session-dedup` elided tekst allerede sendt i en tidligere tur i samme økt. Dette er en** bevisst tilbakeblikk** , ikke et tap eller en feil. | Gjøre** ikke** ring ethvert verktøy og gjør det** ikke** prøv å "rekonstruere" det. Den første forekomsten av teksten er den kanoniske kopien; den gjeldende svingen skrives aldri om, den dedupes ved en senere sving. |

`[dedup:ref]` -tilbakeblikket er en bevisst protokollavgjørelse — det er ingen rekonstruksjon før sending. Behandle det som "denne nøyaktige teksten var allerede på ledningen tidligere i denne økten."

### Kundens forutsetninger

- **Nøkkel (stdio):** en stdio-anroper har ingen identitet per forespørsel, så den autentiserer med `OMNIROUTE_API_KEY` (sett i MCP -serverens `env`). Uten den er innringeren anonym og verktøy som krever en rektor kan forringes.
- **`tools[]` er injeksjonsforutsetningen.** CCR -hentingsprotokollinstruksjonen (#8033) injiseres** bare** når forespørselens annonserte `tools[]` beviser at klienten faktisk kan nå `omniroute_ccr_retrieve`. Matchen er en etterfølgende segmentmatch avgrenset av en separator (`__`, `.`, `/`, `:`) — aldri en bare delstreng — så et navn med navn som `mcp__gateway__omniroute_ccr_retrieve` teller fortsatt. En fraværende eller ikke-matchende `tools[]` betyr at instruksjonen er _ikke_ injisert, etter design.
- **`codemode:false` (OpenCode klienter).** OpenCode er som standard kodemodus, som kun annonserer de opprinnelige verktøyene til modellen og** ikke** legg MCP verktøy på den opprinnelige `tools[]` listen. Sett `codemode: false` på MCP -serveroppføringen slik at `omniroute_ccr_*` verktøyene blir annonsert. Dette er en** klient** innstilling, ikke en OmniRoute. Den får ikke CCR instruksjonen injisert ennå: OpenCode navngir et verktøy `<server>_<tool>`, så en server kalt `omniroute` eksponerer `omniroute_omniroute_ccr_retrieve`, og `_` er ikke en av de matchende skilletegnene.
- **Rektorer.** Lagring og henting er isolert per autentisert hovedperson (per API nøkkel). En nøkkel ser bare sine egne blokker.

### Omfang per verktøy

Omfangshåndhevelse er alltid på for HTTP/SSE -anropere med smale områder. `omniroute_` CCR verktøyene krever:

| Verktøy                  | Omfang              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Et manglende omfang returnerer en**MCP verktøy feil resultat** (`isError: true`, ikke en HTTP 403 — `403 LOCAL_ONLY` er den separate loopback-rutevakt-authoriseringen): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` En minimal fjernnøkkel kan inneholde `mcp:connect` (autoriserer `/api/mcp/` local-only carve-out) pluss det spesifikke read/write omfanget den trenger.

### Klientmatrise

| Klient            | Transportere                              | Konfigurasjon å bruke                                                                                                                                                                                                                                        | `tools[]` annonsert? (→ CCR instruksjon injisert)                                                                                                                                                       |
| ----------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kode       | streambar-http                            | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                            | Ja — MCP-kompatible; injisert.                                                                                                                                                                          |
| Cursor / Cline    | `stdio`** eller** `streamable-http`       | stdio: `omniroute --mcp` med `OMNIROUTE_API_KEY` i `env`; eller en ekstern MCP -oppføring som peker på `http://localhost:20128/api/mcp/stream` (se [Installasjonsveiledning → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Ja — annonsere `omniroute_ccr_*` verktøyene.                                                                                                                                                            |
| OpenCode          | streambar-http                            | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` pluss `codemode: false`                                                                                                                                                             | Verktøy som kun annonseres med `codemode: false`; instruksjonen er fortsatt ikke injisert, fordi `omniroute_omniroute_ccr_retrieve` ikke samsvarer (se [Klientforutsetninger](#client-prerequisites) ). |
| OpenAI-kompatibel | OpenAI-kompatibel HTTP (chatfullføringer) | standard chat-fullføringsklient mot det OpenAI-kompatible endepunktet                                                                                                                                                                                        | **Aldri** — en vanlig OpenAI-kompatibel oppringer blir aldri bedt om å ringe verktøyet, og instruksjonen blir ikke injisert.                                                                            |

### Hentingsgrenser og paginering

MCP -verktøytekstresultater klippes rundt `mcpAccessibility.maxTextChars` (standard `50000`). En `full` henting av en blokk er begrenset til 256 KiB —** det er ingen ubegrenset full gjenfinning** . Når `chars=N` til en blokk er stor, kan du bladre den i stedet for å trekke hele greia:

- Tommelfingerregel:**`chars > 40000` → bruk en `mode`** , aldri bare full.
- `mode:"grep"` — regex `pattern` matchet linje for linje, opptil 1000 matchende linjer (`unique: true` dropper gjentakelser), billigste for "finn den ene linjen jeg trenger."
- `mode:"lines"` — et 1-indeksert linjeområde; trenger både `start` og `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` linjer.
- `mode:"stats"` — linje, tegn og byte teller uten kroppen.

Bruk `mode:"lines"` med `start`/`end` for å gå en lang blokk i sider i stedet for å be om hele på en gang.

### Navn på verktøy

Gjenopprettingsverktøyet heter for øyeblikket `omniroute_ccr_retrieve` ( `omniroute_` prefikset er en datert løsning for navnekollisjoner på tvers av servere). Et renere avgrenset suffiksverktøynavn og en rettelse for MCP JSON resultater avkortet midtstreng spores som oppstrøms oppfølginger; denne siden dokumenterer kun gjeldende, sendt oppførsel.

### Øktens livssyklus

Streambare HTTP-økter går på tomgang og serveren høster dem; det inaktive vinduet er `MCP_SESSION_IDLE_MS` konstanten (referert til ved navn, ikke en hardkodet verdi, så denne siden driver ikke når den endres). Symptomet på en inaktiv økt er en HTTP 404 med `Unknown Mcp-Session-Id` — løsningen er å koble til på nytt eller starte økten på nytt,** ikke** for å rotere en nøkkel, endre et omfang eller gi nytt navn til et verktøy.

## API Overflate

| Rute                                   | Hensikt                                                                   |
| -------------------------------------- | ------------------------------------------------------------------------- |
| `/api/settings/compression`            | Globale komprimeringsinnstillinger (inkluderer `mcpAccessibility` config) |
| `/api/compression/preview`             | Forhåndsvis enhver komprimeringsmodus                                     |
| `/api/compression/language-packs`      | Liste tilgjengelige Caveman-språkpakker                                   |
| `/api/context/caveman/config`          | Caveman innstillinger alias                                               |
| `/api/context/rtk/config`              | RTK standarder og innstillinger                                           |
| `/api/context/rtk/filters`             | RTK filterkatalog                                                         |
| `/api/context/rtk/test`                | RTK preview/test endepunkt                                                |
| `/api/context/rtk/raw-output/[id]`     | Autentisert redigert gjenoppretting av råutdata                           |
| `/api/context/combos`                  | Kompresjonskombinasjon CRUD                                               |
| `/api/context/combos/[id]/assignments` | Ruting-kombinasjonsoppgave CRUD                                           |
| `/api/context/analytics`               | Alias for komprimeringsanalyse                                            |

Administrasjonsruter krever administrasjonsautentisering eller kontroller av API-nøkler.

## MCP verktøy

Komprimering avslører fem MCP verktøy:

| Verktøy                             | Omfang              | Hensikt                                  |
| ----------------------------------- | ------------------- | ---------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Innstillinger, analyser, cachestatistikk |
| `omniroute_compression_configure`   | `write:compression` | Oppdater globale innstillinger           |
| `omniroute_set_compression_engine`  | `write:compression` | Still inn modus og valgfri rørledning    |
| `omniroute_list_compression_combos` | `read:compression`  | List kompresjonskombinasjoner            |
| `omniroute_compression_combo_stats` | `read:compression`  | Les combo/engine analytics               |

## Omfang og unntak

**Innebygginger komprimeres aldri.** `open-sse/handlers/embeddings.ts` kaller aldri noen kompresjonsmotor — request/response kroppene passerer rett til eksekutøren urørt. Dette er strukturelt i dag (innbygginger og chatfullføringer er usammenhengende behandlere), ikke en kjøretidssjekk, men det betyr at vektorforvrengningsproblemet i #8034 ikke har noen eksponeringsoverflate i innbyggingsbanen.

**Per-model/endpoint eksklusjonsfilter (#8034).** For chatfullføringer kan en operatør navngi modell-ID-er / `provider/model` -mål som aldri må komprimeres — et autovern nyttig hvis komprimering noen gang kobles nærmere en innbyggings-tilstøtende bane senere, og generelt nyttig for alle modeller hvis eksakte byte-for-byte-prompt betyr noe (deterministiske evaler, cache-sensitive prefikser, etc.).

- Innstillingsfelt: `exclusions?: string[]` på den globale komprimeringskonfigurasjonen (`GET`/`PUT /api/settings/compression`), vedvarte via det eksisterende `key_value` -komprimeringsnavneområdet (`src/lib/db/compression.ts`) — ingen ny tabell.
- Dashboard-fane:** Dashboard → Komprimering → -ekskluderinger** (`/dashboard/compression/exclusions`).
- Mønstersyntaks: `*` er det eneste jokertegnet. Annenhvert regex-metategn i et mønster escapes før matching, så `gpt-5.6` samsvarer kun med den bokstavelige strengen, aldri `gpt-5x6` (ReDoS-safe, bounded, ingen nestede kvantifiserere). Mønstre samsvarer uten store og små bokstaver mot både den bare modell-ID og `provider/model` kompositten — `gpt-5-6`, `openai/gpt-5-6` og `openai/*` fungerer alle, og `*` alene ekskluderer hver modell.
- Matchende: `isCompressionExcluded()` / `normalizeCompressionExclusions()` i `open-sse/services/compression/exclusions.ts`. `chatCore.ts` sjekker det ekskluderte målet rett etter å ha løst komprimeringsinnstillingene,** før noen motor går** , og behandler en kamp nøyaktig som at komprimering er globalt deaktivert — forespørselsteksten er beviselig byte-identisk. Hoppet registreres via `writeCompressionSkip(..., "excluded")` for analysesynlighet.
- Standard (empty/absent liste): identisk med pre-#8034 atferd — ingenting er ekskludert.

## Kjente begrensninger

- **LLMLingua-2 (SLM) krever samlokaliserte valgfrie deps.** Arbeideren kjører bare i en produksjonsbygning når `@atjsh/llmlingua-2` + kolleger er samlokalisert i `dist/node_modules` (se `scripts/build/colocateOptionals.mjs`, #4286). Uten dem åpner motoren feil (returnerer originalteksten). Arbeideroppløsning avhenger ikke lenger av `import.meta.url` (den dør i den frittstående pakken) — den forankrer på kjøretidscwd / `argv[1]`.
- **Caveman språkpakker `de` / `fr` / `ja` er delvise.** De sender `context` + `filler` + `structural` regler, men ingen `dedup` / `ultra` pakker, så `ultra` intensiteten er ikke sterkere enn `full` for disse språkene (de bruker bare sine egne regler — det er ingen stille fall-tilbake til de engelske `dedup`/`ultra` -reglene, som ville mangle utenlandsk tekst). `en` / `es` / `id` / `pt-BR` er fullført. Bidrag av `dedup.json` + `ultra.json` for delpakkene er velkomne.
- **Stablet telemetri viser bare motorer som er komprimert.** Et stablet-rørledningstrinn hvis motor gikk, men ga 0 % besparelse, gir `stats:null` og vises derfor ikke i `engineBreakdown` — som ikke kan skilles fra et trinn som ble hoppet over. Å skille "løp, 0 %" fra "hoppet over" vil kreve en endring av sammenbruddsmodellen og blir utsatt.

## Validering

De fokuserte portene for dette området er:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
