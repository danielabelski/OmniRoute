# Compression Engines (Nederlands)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute compressie is opgebouwd rond motorcontracten. Een modus kan één engine rechtstreeks uitvoeren (`caveman` of `rtk`) of een deterministische gestapelde pijplijn die meerdere motoren achter elkaar uitvoert.

## Modi

| Modus        | Motorpad                                                                                  | Bedoelde invoer                                       |
| ------------ | ----------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| `off`        | geen                                                                                      | Exacte snelle conservering                            |
| `lite`       | Holbewoner lite helpers                                                                   | Always-on opschoning met laag risico                  |
| `standard`   | Holbewoner                                                                                | Snelle condensatie in natuurlijke taal                |
| `aggressive` | Caveman + history/tool samenvattingen                                                     | Lange chatsessies                                     |
| `ultra`      | Caveman + snoeihulpjes                                                                    | Herstel met contextlimiet                             |
| `rtk`        | RTK                                                                                       | Terminal-, shell-, build-, test- en git-uitvoer       |
| `omniglyph`  | OmniGlyph                                                                                 | Context-als-afbeelding op de native provider-draad    |
| `stacked`    | Pijpleiding. De standaardaanvraag is `session-dedup -> lite`. `rtk -> caveman` is opt-in. | Gemengde toollogboeken en proza, maximale besparingen |

### OmniGlyph -compressieprofielen

De `omniglyph` engine (pakket `omniglyph`, 1.4.0 +) accepteert een benoemd semantisch profiel, globaal ingesteld via `omniglyph.profile` in de compressie-instellingen of per stap door de stapconfiguratie van de gestapelde pijplijn:

| Profiel       | Grens                                                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Standaard. Het beleid dat in de gepubliceerde kwitanties werd gemeten, was — -afbeeldingssysteem, tooldocumentatie en dichte geschiedenis |
| `balanced`    | Houdt de live-status inheems, beschermt de laatste 8 beurten en laat de oudere gesloten geschiedenis instorten                            |
| `coding-safe` | Houdt autoriteit, toolschema's en live tool-uitvoer native, beschermt de laatste 12 beurten                                               |
| `passthrough` | Routes zonder transformatie; de motor wordt overgeslagen                                                                                  |

Het profiel is een** plafond, geen vloer** : `mergeCompressionProfileOptions` in het pakket weigert een beller te laten overschrijven, heropent een verliesgevende rijstrook en het profiel is gesloten, dus een `preserveSystemPrompt: false` per stap kan de systeemcompressie onder `coding-safe` niet opnieuw inschakelen.

Gemeten op deze codebase: `coding-safe` en `balanced` verhogen `minCompressChars` naar het maximum en houden systeem, toolschema's en toolresultaten native, dus een sessie die nog geen geschiedenis heeft verzameld, stopt bij `below_min_chars` en de engine transformeert niets. Daarom is de standaard `aggressive` in plaats van het veiligste profiel.

Het pakket lost zijn eigen modelbereik en profiel op vanuit zijn omgevingsconfiguratie. OmniRoute delegeert de beslissing nooit: de adapter pint de modelpoort op het meest restrictieve bereik van het pakket, zodat de instellingen van de hostomgeving de toelatingslijst alleen kunnen verkleinen en nooit verder kunnen uitbreiden dan de gemeten ontvangsten van OmniRoute.

## Motorregister

Het register bevindt zich in `open-sse/services/compression/engines/registry.ts`. Motoren leggen een gedeeld contract bloot:

- `id`: stabiele engine-ID zoals `caveman` of `rtk`
- `apply(text, config)`: verouderd uitvoeringspad dat wordt gebruikt door gestapelde pijplijnen
- `compress(input, config)`: primair uitvoeringspad dat tekst + statistieken retourneert
- `getConfigSchema()`: retourneert de JSON-Schema-achtige vorm van een geldige configuratie
- `validateConfig(config)`: retourneert `{ valid, errors[] }`

Registratie maakt gebruik van `registerCompressionEngine(engine)` (of `registerEngine` voor geavanceerde gevallen), die `assertValidEngine()` en `validateConfig(defaultConfig)` aanroept voordat deze wordt geaccepteerd. Gebruik `unregisterCompressionEngine(id)` om een engine tijdens runtime te verwijderen.

`strategySelector.ts` registreert de ingebouwde motoren voordat de compressie wordt uitgevoerd. Hierdoor kunnen previews, runtime-compressie, gestapelde modus, tests en toekomstige engine hetzelfde uitvoeringspad gebruiken.

### MCP beschrijving compressie (gerelateerd)

Een afzonderlijk register comprimeert de metagegevens MCP -toolbeschrijving op registerniveau — zie `open-sse/mcp-server/descriptionCompressor.ts` en [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Het hergebruikt de Caveman-regels, maar werkt op basis van tool-metagegevens en niet op verzoek-payloads.

### Extra ingebouwde motoren

Naast Caveman, RTK en LLMLingua-2 verzendt het register verschillende gespecialiseerde verliesvrije / structurele motoren (gebruikt door gestapelde pijpleidingen, de speeltuin en tests):

| Motor        | Identiteitskaart | Wat het doet                                                                                                                                                                                   |
| ------------ | ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR          | `ccr`            | Content-Compress-Retrieve (H4): vervangt grote aaneengesloten tekstblokken door inhoudsgerichte referenties, zodat repeated/large blokken één keer worden verzonden en daarna worden verwezen. |
| hoofdruimte  | `headroom`       | SmartCrusher (H3 + N5): verliesloze tabellarische compactie van homogene JSON-array-payloads in een kolomvormige `[N rows]` vorm.                                                              |
| ionisator    | `ionizer`        | Head/middle/tail -rijbemonstering voor zeer grote homogene blokken, waarbij het weggelaten midden wordt opgeslagen als een CCR -inhoudsgerichte referentie.                                    |
| sessie-dedup | `session-dedup`  | Op inhoud geadresseerde cross-turn deduplicatie (op TokenMizer geïnspireerd): verwijdert tekst die al in eerdere beurten van dezelfde sessie te zien was.                                      |

**CCR ophaalprotocolinstructie (#8033):** de eerste keer dat CCR ≥ 1-blok in een verzoek vervangt, plaatst de engine een enkel, idempotent `system` -bericht (leidend met de `[CCR protocol]` schildwacht) en leert de beller het marker → toolcontract: wat een `[CCR retrieve hash=<24hex> chars=N]` marker betekent, dat de hash woordelijk moet worden gekopieerd (alle 24 hexadecimale karakters — verkeerd gekopieerde hashes zijn de waarschijnlijke oorzaak van "blok niet gevonden" -missers), en dat een `[dedup:ref sha=...]` marker "terugkijken" betekent in de geschiedenis", en niet "roep de tool". Het briefje wordt geïnjecteerd** alleen wanneer de door de beller geadverteerde `tools[]` bewijst dat hij `omniroute_ccr_retrieve` daadwerkelijk kan bereiken** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — een eenvoudige OpenAI-compatibele aanroeper zonder dat hulpmiddel ontvangt nooit een instructie om iets aan te roepen dat het niet kan bereiken. Idempotentie wordt afgedwongen door de berichtgeschiedenis van de schildwacht te scannen voordat deze wordt geïnjecteerd, zodat verzoeken voor meerdere beurten (die eerdere berichten herhalen) het briefje niet één keer per beurt stapelen.

## Holbewoner

Caveman-modus richt zich op semantische condensatie van normaal proza:

- behoudt codeblokken, URLs, JSON, paden en gestructureerde gegevens
- verwijdert opvulling, hedging, herhaalde context en uitgebreide verbindende frasering
- ondersteunt taalbewuste bestandsregelpakketten in `open-sse/services/compression/rules/`
- blijft beschikbaar via de oude `standard`, `aggressive` en `ultra` modi

Het dashboardoppervlak is `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream rapporteert `~75%` minder outputtokens, `65%` gemiddelde outputbesparingen in benchmarks met een `22-87%` bereik en een `~46%` input-compressietool. OmniRoute gebruikt het invoernummer van Caveman bij het documenteren van gestapelde prompt/context besparingen; De Caveman-uitvoermodus blijft een aparte reactie-gedragsfunctie.

## RTK

RTK modus richt zich op opdracht- en gereedschapsuitvoer:

- detecteert uitvoerklassen zoals `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go tests, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, stacktraces en generieke logs
- past 49 JSON -filters van `open-sse/services/compression/engines/rtk/filters/` toe
- ondersteunt de declaratieve pijplijn in RTK-stijl: ANSI strippen, vervangen, match-output kortsluiting, strip/keep lijnen, afkapping per regel, head/tail/max-line afkapping en on-lege fallback
- ondersteunt trust-gated projectfilters in `.rtk/filters.json` en globale filters in `DATA_DIR/rtk/filters.json`
- strips ANSI reeksen, voortgangsruis, herhaalde regels en nutteloze standaardtekst
- bewaart bruikbare fouten, waarschuwingen, samenvattingen, gewijzigde bestanden en staartcontext
- kan optioneel geredigeerde onbewerkte uitvoer voor recovery/debugging behouden via geverifieerde beheerroutes

Het dashboardoppervlak is `Dashboard -> Context & Cache -> RTK`.

Operationele details voor aangepaste filters, vertrouwen, verificatie en herstel van onbewerkte uitvoer zijn live in [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream rapporteert `60-90%` besparingen voor compressie van opdrachtuitvoer. Het README voorbeeld toont een Claude codesessie van 30 minuten, gaande van `~118,000` tokens naar `~23,900`, of `79.7%` opgeslagen.

## LLMLingua-2 (semantisch snoeien)

LLMLingua-2 modus wordt uitgevoerd** semantische token-snoei** over proza met behulp van een kleine ONNX tokenclassificator, als aanvulling op de op regels gebaseerde Caveman- en RTK engines:

- comprimeert proza alleen in niet-systeemberichten; omheinde codeblokken en andere bewaarde constructies worden nooit gewijzigd
- voert de `@atjsh/llmlingua-2` backend uit (ONNX via `@huggingface/transformers`) in een werkthread, zodat modelinferentie nooit de verzoekgebeurtenislus blokkeert
- is** stapelbaar** (`stackPriority` 35): in een gestapelde pijplijn loopt het na de structurele motoren (CCR, session-dedup, headroom, Caveman) maar vóór `ultra`, omdat semantisch snoeien het meest effectief is op reeds structureel gecomprimeerde tekst — bijv. `rtk -> caveman -> llmlingua`
- **fail-open bij elke fout** (ontbrekende optionele deps, worker spawn, model laden, gevolgtrekking of time-out) → de originele tekst wordt ongewijzigd geretourneerd, nooit een fout

Motorlocatie: `open-sse/services/compression/engines/llmlingua/`. Het dashboardoppervlak is `Dashboard -> Context & Cache -> LLMLingua`.

### Modellen

Het standaardmodel is**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, snel). Een hogere nauwkeurigheid** BERT-basis** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) is beschikbaar via het veld engine config `model`. `@huggingface/transformers` downloadt het geselecteerde model lui van de HuggingFace Hub naar `${DATA_DIR}/models/llmlingua` bij de eerste oproep (`modelStore.ts`); een `modelPath` -configuratieoverschrijving verwijst het in plaats daarvan naar een lokale kopie (offline / air-gapped installaties).

### Optionele afhankelijkheden en installatie op aanvraag

De snoeibare LLMLingua runtime peer-stack is** optioneel** . Twee pakketten worden in `package.json` gedeclareerd als `optionalDependencies` en bewaard** extern** door de productiebuild (`scripts/build/prepublish.ts` bundelt ze niet):

| Pakket               | Versie (pin) | Opmerkingen                                       |
| -------------------- | ------------ | ------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`      | Toegangspakket; verklaart de anderen als gelijken |
| `js-tiktoken`        | `^1.0.20`    | Tokenizer                                         |

`@huggingface/transformers` is vastgezet op `^4.2.0` (gedeeld met het lokale inbeddingspad en ook getraceerd in de zelfstandige bundel); `@atjsh/llmlingua-2@2.0.5` peert erop met `"^3.5.2 || ^4.0.0"`, dus zowel Transformers.js v3 als v4 worden ondersteund. Sinds 2.0.4 heeft `@atjsh/llmlingua-2` niet langer `@tensorflow/tfjs` nodig, waardoor de grootste bijdrager (TensorFlow.js) uit de SLM stack is verwijderd. Alleen de twee bovenstaande pakketten zijn snoeibare SLM peers. Een standaard `npm install` (dev) installeert de optionele stapel automatisch, tenzij optionele afhankelijkheden worden weggelaten.

**Waarom op aanvraag:** het door npm gepubliceerde pakket, de zelfstandige bundel en het Docker imageschip** zonder** deze afdelingen om slank te blijven. Als ze afwezig zijn, mislukt de afhankelijkheidspoort van de werknemer (een `@atjsh/llmlingua-2` oplossingssonde in `worker.ts`) en de motor** gaat geruisloos open** — selecteren LLMLingua wordt een no-op (tekst wordt ongewijzigd geretourneerd, geen fout geregistreerd). Om het in een gesnoeide omgeving te activeren, installeert u de optionele stapel:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

De `@tensorflow/tfjs` verwijdering (2.0.4 +) elimineert de voorheen dominante ~ 800 MB bijdrager — De resterende footprint is de transformers.js + onnxruntime-node runtimes, plus het TinyBERT model (~ 57 MB) gedownload bij het eerste gebruik (niet via npm).

Per omgeving:

- **Ontwikkelaar / `npm install`** — automatisch geïnstalleerd, tenzij je `--omit=optional` (of `--no-optional`) hebt doorgegeven. Geen actie nodig.
- **Globaal npm (`npm i -g omniroute`) / standalone** — voer de install-opdracht hierboven uit in de geïnstalleerde pakketmap, of installeer opnieuw zonder optionele deps.
- **Docker** — voeg de install-opdracht toe aan een afgeleide afbeeldingslaag; de gepubliceerde afbeelding wordt slank van ontwerp geleverd.
- **VPS (PM2)** — installeert u in `node_modules` van de app en start u het proces opnieuw zodat de medewerker de poort opnieuw onderzoekt.
- **Raw Next standalone (`npm run build` → `.build/next/standalone/server.js`)** — de standalone trace verzendt NEITHER de worker noch de optionele deps, dus de engine gaat stilletjes open. `scripts/build/colocate-standalone.mjs` past beide opnieuw toe (worker esbuild + optioneel-dep sluiting in de zelfstandige boom); het loopt na elke build automatisch via de `postbuild` npm hook. Idempotent, fail-soft als deps afwezig zijn.

**Controleer of het actief is:** als LLMLingua is geselecteerd, wordt het echte proza feitelijk kleiner (de engine stopt met het fail-openen), en het eerste verzoek activeert het downloaden van het model naar `${DATA_DIR}/models/llmlingua`. De poort onderzoekt opzettelijk alleen `@atjsh/llmlingua-2` — de andere peers zijn alleen ESM en `require.resolve` gooit erop, zelfs als — aanwezig is, zodat de werker nog steeds faalt als een peer echt ontbreekt op `import()` tijd.

## Gestapelde pijpleidingen

In de gestapelde modus worden pijplijnstappen op volgorde uitgevoerd. De standaardinstelling is:

```txt
rtk -> caveman
```

Gebruik dit voor coderingsagentsessies waarbij een prompt opdrachtuitvoer combineert met menselijk of assistent-proza. RTK reduceert eerst luidruchtige toollogs, daarna comprimeert Caveman de resterende natuurlijke taal.

Pijplijnstappen worden geconfigureerd met `stackedPipeline` in compressie-instellingen of via compressiecombo's.

Wanneer beide motoren hetzelfde in aanmerking komende laadvermogen verminderen, worden de volgende besparingen gerealiseerd:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Toegankelijkheidsboomfilter

Het slimme filter voor de toegankelijkheidsboom MCP is een compressielaag na de uitvoering die op MCP draait** gereedschap resultaten** , niet op aanwijzingen of context. Het richt zich op de uitgebreide toegankelijkheidsboom en browser-snapshot-payloads die worden geretourneerd door tools als Playwright, computergebruik en MCP -servers voor browserautomatisering.

### Wat het doet

1. **Ruis strippen** — verwijdert lege generic/text items (`- generic:`, `- text: ""`)
2. **Instorting van broer of zus** — wanneer ≥ `collapseThreshold` (standaard 30) opeenvolgende regels structurele herhalingen zijn, vouwt deze samen in de eerste `collapseKeepHead` (standaard 10) regels + een tellingsoverzicht + de laatste `collapseKeepTail` (standaard 5) regels
3. **Ref-behoud** — `[ref=eXX]` -ankers vereist door Playwright/computer-use worden nooit aangeraakt
4. **Harde afkorting** — als de tekst na het samenvouwen nog steeds groter is dan `maxTextChars` (standaard 50.000), wordt deze afgekapt met een navigatiehint zodat de agent kan blijven werken

### Locatie van de motor

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Configuratie

Gecontroleerd door `compression.mcpAccessibility` in globale instellingen (migratie 056). Standaardconfiguratie:

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

Het filter wordt alleen toegepast op payloads met gereedschapsresultaten waarvan `type` `"text"` is en waarvan de lengte groter is dan `minLengthToProcess`. Het heeft geen invloed op promptcompressie of verzoekpayloads.

### Verwachte besparingen

60-80% van de resultaten van de browser snapshot tool, afhankelijk van de complexiteit van de pagina. Het samenvouwalgoritme is O(n) in het aantal regels en voegt een verwaarloosbare latentie toe.

### Dit filter versus de compressiemotoren hierboven

| Aspect           | Holbewoner / RTK / Gestapeld | MCP toegankelijkheidsfilter            |
| ---------------- | ---------------------------- | -------------------------------------- |
| Doel             | Vraag prompts / context aan  | MCP toolresultaten                     |
| Trekker          | Instelling compressiemodus   | `compression.mcpAccessibility.enabled` |
| Domein           | Alle SSE -berichten          | Alleen gereedschapsresultaten          |
| Raadpleeg ankers | N/A                          | Onvoorwaardelijk bewaard               |

---

## Compressie combo's

Compressiecombo's worden compressieprofielen genoemd die kunnen worden toegewezen aan routeringscombo's:

- `compression_combos`: winkelmodus, pijplijn, RTK -configuratie, taalconfiguratie en standaardmarkering
- `compression_combo_assignments`: wijst een compressiecombo toe aan een routeringscombo
- runtime-integratie lost een toegewezen compressiecombo op voordat generieke combo's worden overschreven
- analyses omvatten `compression_combo_id` en `engine`

Dashboardoppervlak: `Dashboard -> Context & Cache -> Compression Combos`.

## Vereisten / operatorhandleiding (CCR & sessie-dedup)

CCR (`ccr`) en `session-dedup` vervangen of verwijderen tekst en laten a achter** markering** achter. Dit gedeelte is de referentie voor de operator voor het aansluiten van een client, het lezen van de twee markeringen en het ophalen of diagnosticeren van de weggelaten inhoud. De mechanica van elke motor wordt hierboven besproken; dit is de laag "hoe voer ik het uit".

### Transporten en eindpunten

De MCP server waarop de CCR tools beschikbaar zijn, kan op drie manieren worden bereikt. De standaardbasis URL is `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Vervoer                              | URL / commando                          | Opmerkingen                                                                                                                     |
| ------------------------------------ | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Streambare HTTP (client, aanbevolen) | `http://localhost:20128/api/mcp/stream` | Het eindpunt waarmee huidige MCP clients praten.                                                                                |
| Legacy SSE singleton                 | `http://localhost:20128/api/mcp/sse`    | Ouder singletonvervoer. Het** sluit** streambare sessies; gebruik `streamable-http` clients tegen `/api/mcp/stream`, niet deze. |
| stdio                                | `omniroute --mcp`                       | Voor IDE MCP configuratie die het proces voortbrengt. Er is geen `--dev` vlag; `omniroute --mcp` is het stdio-ingangspunt.      |

### Opslaglagen (wat een herstart overleeft)

CCR is een** tweeledig** opslaan, niet alleen in het geheugen:

- **Hot in-memory-laag** — per blok cap 2 MiB, per hoofdsom 16 MiB, globaal 64 MiB. Inzendingen hebben standaard een periode van 24 TTL (maximaal 7 dagen). Het volledige ophalen MCP uit het geheugen is beperkt tot 256 KiB; alles wat groter is, is nog steeds bereikbaar via de ranged / grep-modi.
- **Duurzame SQLite -laag** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, standaard aan) — ondersteunt de laag in het geheugen, zodat een blok LRU uitzetting, een herstart of een herstellanding op een andere instantie overleeft. De rij behoudt de TTL van het blok, dus een blok voorbij zijn TTL is van beide niveaus verdwenen.

Drie bewakers houden de duurzame laag begrensd — een blok blijft alleen geheugen wanneer:

1. het blok is voorbij** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. de runtime is een cloudruntime (geen lokale schijf);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Dus "het blok is verdwenen" is geen algemeen herstartverhaal: een sub-512 KB blok op een lokale, niet-cloud-runtime overleeft een herstart via de duurzame laag totdat de TTL opraakt. Zie [Omgevingsreferentie](../reference/ENVIRONMENT.md) voor de variabele.

### De twee markeringen

| Markering                             | Betekenis                                                                                                                                                          | Wat het model zou moeten doen                                                                                                                                                                                                                      |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Een groot blok werd inhoudelijk geadresseerd opgeslagen.                                                                                                           | Bel `omniroute_ccr_retrieve` met de** 24-hexade hash letterlijk gekopieerd** om de originele tekst terug te krijgen.                                                                                                                               |
| `[dedup:ref sha=…]`                   | `session-dedup` heeft tekst weggelaten die al in een eerdere beurt van dezelfde sessie was verzonden. Dit is een** doelbewuste terugblik** , geen verlies of fout. | Doen** niet** bel een willekeurig hulpmiddel en doe het** niet** probeer het te ‘reconstrueren’. De eerste keer dat de tekst voorkomt is de canonieke kopie; de huidige beurt wordt nooit herschreven, maar wordt bij een latere beurt ontdubbeld. |

De `[dedup:ref]` -terugblik is een bewuste protocolbeslissing — Er is geen pre-send-reconstructie. Behandel het als "deze exacte tekst was al eerder in deze sessie aan de orde."

### Vereisten voor klanten

- **Toets (stdio):** een stdio-beller heeft geen identiteit per verzoek, dus authenticeert deze met `OMNIROUTE_API_KEY` (ingesteld in de `env` van de MCP server). Zonder dit is de beller anoniem en kunnen tools waarvoor een opdrachtgever nodig is, verslechteren.
- **`tools[]` is de injectievoorwaarde.** De CCR retrieve-protocol instructie (#8033) wordt geïnjecteerd** alleen** wanneer de geadverteerde `tools[]` van het verzoek bewijst dat de client daadwerkelijk `omniroute_ccr_retrieve` kan bereiken. De overeenkomst is een overeenkomst met een volgsegment, begrensd door een scheidingsteken (`__`, `.`, `/`, `:`) — nooit een kale subtekenreeks —, dus een naamruimtenaam zoals `mcp__gateway__omniroute_ccr_retrieve` telt nog steeds. Een afwezige of niet-overeenkomende `tools[]` betekent dat de instructie _niet_ is geïnjecteerd, door het ontwerp.
- **`codemode:false` (OpenCode clients).** OpenCode gebruikt standaard de Codemodus, die alleen de eigen tools aan het model adverteert en** niet** plaats MCP tools op de native `tools[]` lijst. Stel `codemode: false` in op de MCP serveringang zodat de `omniroute_ccr_*` tools worden geadverteerd. Dit is een** cliënt** instelling, niet een OmniRoute instelling. De CCR instructie wordt nog niet geïnjecteerd: OpenCode noemt een tool `<server>_<tool>`, dus een server met de naam `omniroute` stelt `omniroute_omniroute_ccr_retrieve` bloot, en `_` is niet een van de overeenkomende scheidingstekens.
- **opdrachtgevers.** Het opslaan en ophalen gebeurt geïsoleerd per geauthenticeerde opdrachtgever (per API sleutel). Een sleutel ziet alleen zijn eigen blokken.

### Scopes per gereedschap

Het afdwingen van het bereik is altijd ingeschakeld voor HTTP/SSE bellers met een beperkt bereik. De `omniroute_` CCR tools vereisen:

| Hulpmiddel               | Domein              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Een ontbrekend bereik retourneert een**MCP toolfoutresultaat** (`isError: true`, niet een HTTP 403 — de `403 LOCAL_ONLY` is de afzonderlijke loopback route-guard auth): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Een minimale externe sleutel kan `mcp:connect` bevatten (autoriseert de `/api/mcp/` alleen lokale carve-out) plus de specifieke read/write scope die het nodig heeft.

### Klantenmatrix

| Cliënt            | Vervoer                                     | Configuratie om te gebruiken                                                                                                                                                                                                                             | `tools[]` geadverteerd? (→ CCR instructie geïnjecteerd)                                                                                                                                                               |
| ----------------- | ------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude -code      | streambaar-http                             | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                        | Ja — MCP-compatibel; geïnjecteerd.                                                                                                                                                                                    |
| Cursor / Cline    | `stdio`** of** `streamable-http`            | stdio: `omniroute --mcp` met `OMNIROUTE_API_KEY` in `env`; of een externe MCP -invoer die naar `http://localhost:20128/api/mcp/stream` wijst (zie [Installatiehandleiding → MCP Clientconfiguratie](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Ja — maakt reclame voor de `omniroute_ccr_*` tools.                                                                                                                                                                   |
| OpenCode          | streambaar-http                             | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plus `codemode: false`                                                                                                                                                         | Tools die alleen worden geadverteerd met `codemode: false`; de instructie is nog steeds niet geïnjecteerd, omdat `omniroute_omniroute_ccr_retrieve` niet overeenkomt (zie [Clientvereisten](#client-prerequisites) ). |
| OpenAI-compatibel | OpenAI-compatibele HTTP (chat-voltooiingen) | standaard chat-voltooiingsclient tegen het OpenAI-compatibele eindpunt                                                                                                                                                                                   | **Nooit** — een gewone OpenAI-compatibele beller krijgt nooit te horen dat hij de tool moet aanroepen, en de instructie wordt niet geïnjecteerd.                                                                      |

### Ophaallimieten en paginering

MCP tooltekstresultaten worden rond `mcpAccessibility.maxTextChars` geknipt (standaard `50000`). Het ophalen van een `full` blok is beperkt tot 256 KiB —** er is geen onbegrensd volledig ophalen** . Wanneer de `chars=N` van een blok groot is, kunt u deze pagina's maken in plaats van het hele ding te trekken:

- Vuistregel:**`chars > 40000` → gebruik een `mode`** , nooit een kaal vol.
- `mode:"grep"` — regex `pattern` komt regel voor regel overeen, tot 1.000 overeenkomende regels (`unique: true` laat herhalingen vallen), het goedkoopst voor "vind de enige regel die ik nodig heb."
- `mode:"lines"` — een 1-geïndexeerd lijnbereik; heeft zowel `start` als `end` nodig.
- `mode:"head"` / `mode:"tail"` — first/last `n` lijnen.
- `mode:"stats"` — lijn-, teken- en bytetellingen zonder de hoofdtekst.

Gebruik `mode:"lines"` met `start`/`end` om een lang blok in pagina's te doorlopen in plaats van het hele ding in één keer op te vragen.

### Naamgeving van gereedschap

De ophaaltool heet momenteel `omniroute_ccr_retrieve` (het voorvoegsel `omniroute_` is een verouderde oplossing voor botsingen tussen servernamen). Een schonere toolnaam met een begrensd achtervoegsel en een oplossing voor MCP JSON resultaten die midden in de tekenreeks worden afgekapt, worden bijgehouden als upstream-follow-ups; deze pagina documenteert alleen het huidige, verzonden gedrag.

### Sessielevenscyclus

Streamable-HTTP-sessies vallen uit en de server plukt ze; het inactieve venster is de `MCP_SESSION_IDLE_MS` constante (waarnaar wordt verwezen met de naam, geen hardgecodeerde waarde, zodat deze pagina niet afwijkt als deze verandert). Het symptoom van een inactieve sessie is een HTTP 404 met `Unknown Mcp-Session-Id` — De remedie is om opnieuw verbinding te maken of de sessie opnieuw te starten,** niet** om een sleutel te draaien, een bereik te wijzigen of een gereedschap te hernoemen.

## API oppervlak

| Route                                  | Doel                                                                          |
| -------------------------------------- | ----------------------------------------------------------------------------- |
| `/api/settings/compression`            | Algemene compressie-instellingen (inclusief `mcpAccessibility` -configuratie) |
| `/api/compression/preview`             | Bekijk een voorbeeld van elke compressiemodus                                 |
| `/api/compression/language-packs`      | Maak een lijst van beschikbare Caveman-taalpakketten                          |
| `/api/context/caveman/config`          | Alias voor instellingen voor Caveman                                          |
| `/api/context/rtk/config`              | RTK standaardinstellingen en -instellingen                                    |
| `/api/context/rtk/filters`             | RTK -filtercatalogus                                                          |
| `/api/context/rtk/test`                | RTK preview/test eindpunt                                                     |
| `/api/context/rtk/raw-output/[id]`     | Geauthenticeerd geredigeerd herstel van onbewerkte uitvoer                    |
| `/api/context/combos`                  | Compressie combo CRUD                                                         |
| `/api/context/combos/[id]/assignments` | Routering-combo-toewijzing CRUD                                               |
| `/api/context/analytics`               | Alias voor compressieanalyse                                                  |

Beheerroutes vereisen beheerauthenticatie of API-sleutelbeleidscontroles.

## MCP Gereedschap

Compressie legt vijf MCP tools bloot:

| Hulpmiddel                          | Domein              | Doel                                      |
| ----------------------------------- | ------------------- | ----------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Instellingen, analyses, cachestatistieken |
| `omniroute_compression_configure`   | `write:compression` | Update de algemene instellingen           |
| `omniroute_set_compression_engine`  | `write:compression` | Stel de modus en optionele pijplijn in    |
| `omniroute_list_compression_combos` | `read:compression`  | Geef compressiecombo's weer               |
| `omniroute_compression_combo_stats` | `read:compression`  | Lees combo/engine -analyses               |

## Reikwijdte en uitsluitingen

**Insluitingen worden nooit gecomprimeerd.** `open-sse/handlers/embeddings.ts` noemt nooit een compressiemotor — de request/response lichamen gaan onaangeroerd rechtstreeks naar de executeur. Dit is tegenwoordig structureel (insluitingen en voltooiingen van chats zijn disjuncte handlers), geen runtimecontrole, maar het betekent dat het probleem van vectorvervorming in #8034 geen blootstellingsoppervlak heeft in het inbeddingspad.

**Per-model/endpoint uitsluitingsfilter (#8034).** Voor het voltooien van chats kan een operator model-ID's / `provider/model` -doelen benoemen die nooit mogen worden gecomprimeerd — een vangrail, handig als de compressie later ooit dichter bij een pad aangrenzend aan de insluitingen wordt aangesloten, en in het algemeen nuttig voor elk model waarvan de exacte byte-voor-byte-prompt ertoe doet (deterministische evaluaties, cache-gevoelige voorvoegsels, enz.).

- Instellingenveld: `exclusions?: string[]` in de globale compressieconfiguratie (`GET`/`PUT /api/settings/compression`), gehandhaafd via de bestaande `key_value` -compressienaamruimte (`src/lib/db/compression.ts`) — geen nieuwe tabel.
- Dashboard-tabblad:** Dashboard → Compressie → Uitsluitingen** (`/dashboard/compression/exclusions`).
- Patroonsyntaxis: `*` is het enige jokerteken. Elk ander regex-metateken in een patroon wordt geëscaped voordat het wordt gematcht, dus `gpt-5.6` komt alleen overeen met de letterlijke tekenreeks, nooit `gpt-5x6` (ReDoS-veilig, begrensd, geen geneste kwantoren). Patronen komen hoofdletterongevoelig overeen met zowel de kale model-ID als de `provider/model` -composiet — `gpt-5-6`, `openai/gpt-5-6` en `openai/*` werken allemaal, en `*` alleen sluit elk model uit.
- Matching: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` controleert het uitgesloten doel direct na het oplossen van de compressie-instellingen,** voordat er een motor draait** , en behandelt een match precies zoals compressie globaal wordt uitgeschakeld, — de verzoektekst aantoonbaar byte-identiek is. Het overslaan wordt geregistreerd via `writeCompressionSkip(..., "excluded")` voor zichtbaarheid van analyses.
- Standaard (empty/absent lijst): identiek aan pre-#8034 gedrag — niets is uitgesloten.

## Bekende beperkingen

- **LLMLingua-2 (SLM) vereist co-located optionele deps.** De werker draait alleen in een productiebuild wanneer `@atjsh/llmlingua-2` + peers zich in `dist/node_modules` bevinden (zie `scripts/build/colocateOptionals.mjs`, #4286). Zonder deze mislukt de motor (retourneert de originele tekst). De resolutie van de werker is niet langer afhankelijk van `import.meta.url` (het sterft in de zelfstandige bundel) — het verankert op de runtime cwd / `argv[1]`.
- **Caveman-taalpakketten `de` / `fr` / `ja` zijn gedeeltelijk.** Ze verzenden `context` + `filler` + `structural` regels, maar geen `dedup` / `ultra` pakketten, dus `ultra` intensiteit is niet sterker dan `full` voor die talen (ze gebruiken alleen hun eigen regels, — er is geen stille terugval naar de Engelse `dedup`/`ultra` -regels, die buitenlandse tekst zouden verminken). `en` / `es` / `id` / `pt-BR` zijn voltooid. Bijdragen van `dedup.json` + `ultra.json` voor de gedeeltelijke pakketten zijn welkom.
- **Gestapelde telemetrie vermeldt alleen motoren die zijn gecomprimeerd.** Een gestapelde pijplijnstap waarvan de motor draaide maar 0% besparing opleverde, retourneert `stats:null` en verschijnt dus niet in `engineBreakdown` — niet te onderscheiden van een stap die werd overgeslagen. Het onderscheiden van "uitgevoerd, 0%" van "overgeslagen" zou een wijziging van het analysemodel vereisen en wordt uitgesteld.

## Geldigmaking

De gerichte poorten voor dit gebied zijn:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
