# Compression Engines (Slovenčina)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompresia je postavená na kontraktoch motora. Režim môže spúšťať jeden motor priamo (`caveman` alebo `rtk`) alebo deterministické naskladané potrubie, ktoré spúšťa viacero motorov v poradí.

## Režimy

| Režim        | Dráha motora                                                                               | Zamýšľaný vstup                                        |
| ------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------ |
| `off`        | žiadny                                                                                     | Presné rýchle uchovanie                                |
| `lite`       | Caveman lite pomocníci                                                                     | Neustále čistenie s nízkym rizikom                     |
| `standard`   | Jaskyniar                                                                                  | Rýchla kondenzácia v prirodzenom jazyku                |
| `aggressive` | Jaskynný muž + history/tool sumarizátorov                                                  | Dlhé rozhovory                                         |
| `ultra`      | Jaskyniar + pomocníkov na prerezávanie                                                     | Kontextové obmedzenie obnovy                           |
| `rtk`        | RTK                                                                                        | Výstup terminálu, shell, zostavenie, test a git        |
| `omniglyph`  | OmniGlyph                                                                                  | Kontext ako obrázok na kábli natívneho poskytovateľa   |
| `stacked`    | Potrubie. Predvolená požiadavka je `session-dedup -> lite`. `rtk -> caveman` je voliteľný. | Zmiešané protokoly nástrojov a próza, maximálne úspory |

### OmniGlyph kompresné profily

Motor `omniglyph` (balík `omniglyph`, 1.4.0 +) akceptuje pomenovaný sémantický profil, nastavený globálne cez `omniglyph.profile` v nastaveniach kompresie alebo podľa kroku cez konfiguráciu krokov skladaného potrubia:

| Profil        | Hranica                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Predvolené. Politika zverejnených príjmov merala obrazový systém —, dokumentáciu nástrojov a hustú históriu |
| `balanced`    | Udržuje živý stav natívny, chráni posledných 8 otáčok, zrúti staršiu uzavretú históriu                      |
| `coding-safe` | Udržuje autoritu, schémy nástrojov a živý výstup nástroja natívne, chráni posledných 12 otáčok              |
| `passthrough` | Trasy bez transformácie; motor je vynechaný                                                                 |

Profil je a** strop, nie podlahu** : `mergeCompressionProfileOptions` v balíku odmietne dovoliť volajúcemu, aby znovu otvoril stratový pruh, v ktorom bol profil uzavretý, takže `preserveSystemPrompt: false` na krok nemôže znova povoliť kompresiu systému pod `coding-safe`.

Merané na základe tejto kódovej základne: `coding-safe` a `balanced` zvyšujú `minCompressChars` na maximum a udržiavajú systém, schémy nástrojov a výsledky nástrojov natívne, takže relácia, ktorá ešte nenazbierala históriu, sa zastaví na `below_min_chars` a motor nič netransformuje. Preto je predvolená hodnota `aggressive` a nie najbezpečnejší profil.

Balík rieši svoj vlastný rozsah modelu a profil z konfigurácie prostredia. OmniRoute nikdy nedeleguje rozhodnutie: adaptér pripojí bránu modelu k najobmedzenejšiemu rozsahu balíka, takže nastavenia hostiteľského prostredia môžu zoznam povolených iba zúžiť, nikdy ho nerozšíriť za namerané príjmy OmniRoute.

## Register motorov

Register žije v `open-sse/services/compression/engines/registry.ts`. Motory odhaľujú zdieľanú zmluvu:

- `id`: stabilné ID motora, ako napríklad `caveman` alebo `rtk`
- `apply(text, config)`: staršia cesta vykonávania, ktorú používajú skladané potrubia
- `compress(input, config)`: primárna cesta vykonávania, ktorá vracia textové štatistiky +
- `getConfigSchema()`: vráti tvar podobný JSON schéme platnej konfigurácie
- `validateConfig(config)`: vráti `{ valid, errors[] }`

Registrácia používa `registerCompressionEngine(engine)` (alebo `registerEngine` pre pokročilé prípady), ktorý pred prijatím volá `assertValidEngine()` a `validateConfig(defaultConfig)`. Použite `unregisterCompressionEngine(id)` na odstránenie motora za behu.

`strategySelector.ts` registruje vstavané motory pred spustením kompresie. To umožňuje náhľadu, kompresii za behu, skladanému režimu, testom a budúcim nástrojom používať rovnakú cestu vykonávania.

### kompresia popisu MCP (súvisiace)

Samostatný register komprimuje metadáta popisu nástroja MCP na úrovni registra — pozri `open-sse/mcp-server/descriptionCompressor.ts` a [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Opätovne používa pravidlá Caveman, ale pracuje s metadátami nástroja, nie s požadovanými užitočnými zaťaženiami.

### Ďalšie vstavané motory

Okrem Caveman, RTK a LLMLingua-2, register dodáva niekoľko špecializovaných bezstratových / štrukturálnych motorov (používaných v naskladaných potrubiach, na ihrisku a testoch):

| Motor               | Id              | Čo to robí                                                                                                                                                             |
| ------------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR                 | `ccr`           | Content-Compress-Retrieve (H4): nahrádza veľké súvislé textové bloky odkazmi s adresou obsahu, takže bloky repeated/large sa odosielajú raz a potom sa na ne odkazuje. |
| priestor nad hlavou | `headroom`      | SmartCrusher (H3 + N5): bezstratové tabuľkové zhutnenie homogénnych užitočných zaťažení poľa JSON do stĺpcovej formy `[N rows]`.                                       |
| ionizátor           | `ionizer`       | vzorkovanie riadkov Head/middle/tail pre veľmi veľké homogénne bloky, ukladanie elidovaného stredu ako referencie s adresou obsahu CCR.                                |
| session-dedup       | `session-dedup` | Deduplikácia krížového obratu adresovaná podľa obsahu (inšpirovaná TokenMizer): odstraňuje text, ktorý ste už videli v predchádzajúcich častiach tej istej relácie.    |

**CCR inštrukcia protokolu načítania (#8033):** pri prvom CCR nahradí ≥ 1 blok v požiadavke, engine pridá jednu, idempotentnú `system` správu (vedúcu so `[CCR protocol]` sentinelom), ktorá volajúceho naučí značku → tool kontrakt: čo značka `[CCR retrieve hash=<24hex> chars=N]` znamená, že hash musí byť skopírovaný doslovne (všetkých 24 hexadecimálnych znakov `[dedup:ref sha=...]` — „obzri sa do histórie“, nie „zavolaj nástroj“. Poznámka je vstreknutá** len vtedy, keď inzerovaný `tools[]` volajúceho dokáže, že skutočne môže dosiahnuť `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — obyčajný volajúci kompatibilný s OpenAI bez tohto nástroja nikdy nedostane pokyn na zavolanie niečoho, čo nemôže dosiahnuť. Idempotencia je vynútená skenovaním histórie správ pre sentinel pred podaním injekcie, takže viackolové požiadavky (ktoré prehrávajú predchádzajúce správy) neukladajú poznámku raz za kolo.

## Jaskyniar

Režim Caveman sa zameriava na sémantickú kondenzáciu normálnej prózy:

- zachováva bloky kódu, URLs, JSON, cesty a štruktúrované údaje
- odstraňuje výplň, hedging, opakovaný kontext a verbózne spojovacie frázy
- podporuje balíky pravidiel pre súbory v jazyku `open-sse/services/compression/rules/`
- zostáva k dispozícii prostredníctvom starších režimov `standard`, `aggressive` a `ultra`

Povrch palubnej dosky je `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream uvádza `~75%` menej výstupných tokenov, priemerné úspory výstupu `65%` v benchmarkoch s rozsahom `22-87%` a nástroj na kompresiu vstupu `~46%`. OmniRoute používa vstupné číslo Caveman pri dokumentovaní nahromadených úspor prompt/context ; Výstupný režim Caveman zostáva samostatnou funkciou odozvy a správania.

## RTK

Režim RTK sa zameriava na výstup príkazov a nástrojov:

- zisťuje výstupné triedy ako `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testy, zostavy TypeScript/Vite/Webpack, ESLint, npm audit/installs, Docker protokoly, shell `find`/`grep`, stopy zásobníka a všeobecné protokoly
- aplikuje 49 JSON filtrov z `open-sse/services/compression/engines/rtk/filters/`
- podporuje deklaratívny kanál v štýle RTK: odizolovanie ANSI, nahradenie, skrat na výstupe, strip/keep linky, skrátenie na jeden riadok, skrátenie head/tail/max-line a núdzový režim pri vyprázdnení
- podporuje filtre projektov s dôveryhodnou bránou v `.rtk/filters.json` a globálne filtre v `DATA_DIR/rtk/filters.json`
- stripuje ANSI sekvencie, progresívny šum, opakujúce sa riadky a neužitočný štandard
- zachováva vykonateľné zlyhania, varovania, súhrny, zmenené súbory a kontext chvosta
- môže voliteľne zachovať upravený nespracovaný výstup pre recovery/debugging prostredníctvom overených ciest správy

Povrch palubnej dosky je `Dashboard -> Context & Cache -> RTK`.

Prevádzkové podrobnosti o vlastných filtroch, dôvere, overovaní a obnove surového výstupu v [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream hlási úspory `60-90%` pre kompresiu výstupu príkazov. Jeho príklad README ukazuje 30-minútovú reláciu kódu Claude prechádzajúcu z tokenov `~118,000` na `~23,900` alebo uložený `79.7%`.

## LLMLingua-2 (sémantické prerezávanie)

vykoná sa režim LLMLingua-2** orezávanie sémantických tokenov** na prózu s použitím malého klasifikátora tokenov ONNX, ktorý dopĺňa motory Caveman a RTK založené na pravidlách:

- komprimuje prózu iba v nesystémových správach; oplotené bloky kódu a iné zachované konštrukcie sa nikdy nemenia
- spúšťa backend `@atjsh/llmlingua-2` (ONNX cez `@huggingface/transformers`) v pracovnom vlákne, takže odvodenie modelu nikdy neblokuje slučku udalostí požiadavky
- je** stohovateľné** (`stackPriority` 35): v nahromadenom potrubí beží za štrukturálnymi motormi (CCR, session-dedup, headroom, Caveman), ale pred `ultra`, keďže sémantické orezávanie je najúčinnejšie na už štrukturálne komprimovanom texte — napr `rtk -> caveman -> llmlingua`
- **zlyhanie sa otvorí pri akejkoľvek chybe** (chýbajúce voliteľné deps, worker spawn, model load, inferencia alebo timeout) → pôvodný text sa vráti nezmenený, nikdy chyba

Umiestnenie motora: `open-sse/services/compression/engines/llmlingua/`. Povrch palubnej dosky je `Dashboard -> Context & Cache -> LLMLingua`.

### Modelky

Predvolený model je**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, rýchlo). Vyššia presnosť** BERT-základňa** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) je dostupný cez pole konfigurácie motora `model`. `@huggingface/transformers` lenivo stiahne vybraný model z centra HuggingFace do `${DATA_DIR}/models/llmlingua` pri prvom volaní (`modelStore.ts`); prepísanie konfigurácie `modelPath` ho namiesto toho nasmeruje na lokálnu kópiu (offline / inštalácie so vzduchovou medzerou).

### Voliteľné závislosti a inštalácia na požiadanie

Orezávateľný LLMLingua runtime peer stack je** voliteľné** . Dva balíky sú deklarované ako `optionalDependencies` v `package.json` a uchovávané** externé** podľa produkčnej zostavy (`scripts/build/prepublish.ts` ich nespája):

| Balíček              | Verzia (pin) | Poznámky                                       |
| -------------------- | ------------ | ---------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`      | Vstupný balík; vyhlási ostatných za rovesníkov |
| `js-tiktoken`        | `^1.0.20`    | Tokenizer                                      |

`@huggingface/transformers` je pripnutý na `^4.2.0` (zdieľaný s miestnou cestou vloženia a tiež sledovaný v samostatnom balíku); `@atjsh/llmlingua-2@2.0.5` sa na ňom zhoduje so `"^3.5.2 || ^4.0.0"`, takže sú podporované Transformers.js v3 aj v4. Od verzie 2.0.4 už `@atjsh/llmlingua-2` nevyžaduje `@tensorflow/tfjs`, čím sa zo zásobníka SLM odstránil najväčší samostatný prispievateľ (TensorFlow.js). Iba dva vyššie uvedené balíky sú orezané SLM peermi. Štandardný `npm install` (dev) nainštaluje voliteľný zásobník automaticky, pokiaľ nie sú vynechané voliteľné závislosti.

**Prečo na požiadanie:** balík publikovaný npm, samostatný balík a obrazová loď Docker** bez** tieto deps zostať štíhly. Keď chýbajú, brána závislosti pracovníka (sonda rozlíšenia `@atjsh/llmlingua-2` v `worker.ts`) zlyhá a motor** zlyhanie - otvára sa ticho** — výber LLMLingua sa stane nefunkčným (text sa vráti nezmenený, nezaznamená sa žiadna chyba). Ak ho chcete aktivovať v orezanom prostredí, nainštalujte voliteľný zásobník:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Odstránenie `@tensorflow/tfjs` (2.0.4 +) eliminuje predtým dominantného prispievateľa ~ 800 MB — zostávajúca stopa je transformers.js + onnxruntime-node runtime plus model TinyBERT (~ 57 MB) stiahnutý pri prvom použití (nie cez npm).

Na prostredie:

- **Dev / `npm install`** — sa nainštaluje automaticky, pokiaľ neprejdete `--omit=optional` (alebo `--no-optional`). Nie je potrebná žiadna akcia.
- **Globálne npm (`npm i -g omniroute`) / samostatné** — spustite príkaz install uvedený vyššie v adresári nainštalovaného balíka alebo preinštalujte bez vynechania voliteľných deps.
- **Docker** — pridajte príkaz install do odvodenej vrstvy obrazu; zverejnený obrázok dodáva tenký dizajn.
- **VPS (PM2)** — nainštalujte do `node_modules` aplikácie, potom reštartujte proces, aby pracovník znova otestoval bránu.
- **Samostatný Raw Next (`npm run build` → `.build/next/standalone/server.js`)** — samostatné trasovacie lode NEITHER pracovníka ani voliteľné oddelenia, takže motor sa ticho zlyhá a otvorí. `scripts/build/colocate-standalone.mjs` znova aplikuje oboje (pracovník vytvorí + optional-dep closure do samostatného stromu); spustí sa automaticky cez hák `postbuild` npm po každom zostavení. Idempotentný, odolný proti zlyhaniam, keď chýbajú deps.

**Overte, či je aktívny:** s vybraným LLMLingua sa skutočná próza v skutočnosti zmenší (motor sa zastaví pri poruche otvárania) a prvá požiadavka spustí sťahovanie modelu do `${DATA_DIR}/models/llmlingua`. Brána zámerne skúma iba `@atjsh/llmlingua-2` — ostatní partneri sú len ESM a `require.resolve` na nich vrhá, aj keď sú prítomné — takže pracovník sa stále zlyhá a otvorí sa, ak niektorý z partnerov skutočne chýba v čase `import()`.

## Skladané potrubia

Skladaný režim spúšťa kroky potrubia v poradí. Predvolená hodnota je:

```txt
rtk -> caveman
```

Použite to pre relácie kódovacieho agenta, kde výzva kombinuje výstup príkazu s ľudskou alebo asistentskou prózou. RTK najprv redukuje hlučné protokoly nástrojov, potom Caveman skomprimuje zostávajúci prirodzený jazyk.

Kroky potrubia sú konfigurované pomocou `stackedPipeline` v nastaveniach kompresie alebo prostredníctvom kombá kompresie.

Keď oba motory znížia rovnaké prípustné užitočné zaťaženie, zlúčenina úspory:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Stromový filter dostupnosti

Inteligentný filter stromu dostupnosti MCP je vrstva kompresie po spustení, ktorá beží na MCP** výsledky nástroja** , nie na výzvy alebo kontext. Zameriava sa na podrobný strom prístupnosti a užitočné zaťaženie snímok prehliadača vrátené nástrojmi, ako sú servery MCP Playwright, používanie počítača a automatizácia prehliadača.

### Čo to robí

1. **Odstraňovanie hluku** — odstráni prázdne položky generic/text (`- generic:`, `- text: ""`)
2. **Súrodenecký kolaps** — keď ≥ `collapseThreshold` (predvolené 30) po sebe idúce riadky sú štrukturálne opakovania, zbalí ich do prvých `collapseKeepHead` (predvolených 10) riadkov + súhrn počtu + posledných `collapseKeepTail` (predvolených 5) riadkov
3. **Zachovanie ref** Kotvy — `[ref=eXX]` požadované Playwright/computer-use sa nikdy nedotknú
4. **Tvrdé skrátenie** — ak text po zbalení stále presahuje hodnotu `maxTextChars` (predvolená hodnota 50 000), skráti sa pomocou navigačnej rady, aby agent mohol pokračovať v práci

### Umiestnenie motora

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfigurácia

Riadené `compression.mcpAccessibility` v globálnych nastaveniach (migrácia 056). Predvolená konfigurácia:

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

Filter sa aplikuje iba na užitočné zaťaženia výsledkov nástroja, ktorých `type` je `"text"` a ktorých dĺžka presahuje `minLengthToProcess`. Nemá vplyv na okamžitú kompresiu alebo požadované užitočné zaťaženie.

### Očakávané úspory

60 – 80 % na výsledky nástroja na vytváranie snímok prehliadača v závislosti od zložitosti stránky. Algoritmus zrútenia je O(n) v počte riadkov a pridáva zanedbateľnú latenciu.

### Tento filter vs. kompresné motory vyššie

| Aspekt    | Jaskynný muž / RTK / Skladaný | MCP filter dostupnosti                 |
| --------- | ----------------------------- | -------------------------------------- |
| Cieľ      | Požiadavky / kontext          | výsledky nástroja MCP                  |
| Spúšťač   | Nastavenie kompresného režimu | `compression.mcpAccessibility.enabled` |
| Rozsah    | Všetky správy SSE             | Iba výsledky nástroja                  |
| Ref kotvy | N/A                           | Bezpodmienečne zachované               |

---

## Kompresné kombá

Kompresné kombá sú pomenované kompresné profily, ktoré možno priradiť ku kombám smerovania:

- `compression_combos`: ukladá režim, kanál, konfiguráciu RTK, konfiguráciu jazyka a predvolenú značku
- `compression_combo_assignments`: mapuje komprimačné kombo na smerovacie kombo
- integrácia runtime rieši priradenú komprimačnú kombináciu pred prepísaním generickej kombinácie
- analýzy zahŕňajú `compression_combo_id` a `engine`

Povrch palubnej dosky: `Dashboard -> Context & Cache -> Compression Combos`.

## Predpoklady / sprievodca operátora (CCR & session-dedup)

CCR (`ccr`) a `session-dedup` nahradia alebo vynechajú text a ponechajú a** marker** pozadu. Táto časť je referenciou pre operátora na zapojenie klienta, čítanie dvoch značiek a načítanie alebo diagnostiku elided obsahu. Mechanika každého motora je uvedená vyššie; toto je vrstva „ako to spustím“.

### Transporty a koncové body

Server MCP, ktorý odhaľuje nástroje CCR, je možné dosiahnuť tromi spôsobmi. Predvolený základ URL je `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Doprava                                  | URL / príkaz                            | Poznámky                                                                                                                                           |
| ---------------------------------------- | --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Streamovateľné HTTP (klient, odporúčané) | `http://localhost:20128/api/mcp/stream` | Koncový bod, s ktorým hovoria súčasní klienti MCP.                                                                                                 |
| Legacy SSE singleton                     | `http://localhost:20128/api/mcp/sse`    | Staršia singletonová doprava. to** zatvára** streamovateľné relácie; použite klientov `streamable-http` proti `/api/mcp/stream`, nie proti tomuto. |
| stdio                                    | `omniroute --mcp`                       | Pre konfiguráciu IDE MCP, ktorá spúšťa proces. Neexistuje žiadna vlajka `--dev` ; `omniroute --mcp` je vstupný bod stdio.                          |

### Úložné vrstvy (čo prežije reštart)

CCR je a** dvojvrstvový** uložiť, nie iba v pamäti:

- **Horúca úroveň v pamäti** — na blok 2 MiB, na istinu 16 MiB, globálne 64 MiB. Vstupy sú štandardne nastavené na 24 h TTL (maximálne 7 dní). Úplné načítanie MCP z pamäte je obmedzené na 256 KiB; čokoľvek väčšie je stále dosiahnuteľné prostredníctvom režimov ranged / grep.
- **Odolná vrstva SQLite** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, predvolene zapnuté) — podporuje vrstvu v pamäti, takže blok prežije vysťahovanie LRU, reštart alebo pristátie na inom mieste. Riadok si zachováva TTL bloku, takže blok za jeho TTL je preč z oboch vrstiev.

Tri stráže udržujú odolnú vrstvu ohraničenú — a blok zostáva iba v pamäti, keď:

1. blok sa skončil** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. runtime je cloud runtime (bez lokálneho disku);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Takže „blok zmizol“ nie je príbeh o plošnom reštarte: blok sub-512 KB na lokálnom, necloudovom runtime prežije reštart cez trvanlivú vrstvu, kým sa jeho TTL nevyčerpá. Premennú nájdete v časti [Referenčné informácie o prostredí](../reference/ENVIRONMENT.md).

### Dve značky

| Marker                                | Význam                                                                                                                                                              | Čo by mal model robiť                                                                                                                                                                             |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Bol uložený veľký blok s adresným obsahom.                                                                                                                          | Zavolajte `omniroute_ccr_retrieve` s** 24-hexový hash skopírovaný doslovne** aby sa vrátil pôvodný text.                                                                                          |
| `[dedup:ref sha=…]`                   | `session-dedup` elidovaný text, ktorý už bol odoslaný v predchádzajúcom kole tej istej relácie. Toto je** úmyselné obzretie sa späť** , nejde o stratu alebo chybu. | Do** nie** zavolajte akýkoľvek nástroj a urobte to** nie** skús to "rekonštruovať". Prvý výskyt textu je kanonická kópia; aktuálny obrat sa nikdy neprepíše, pri neskoršom obrate sa deduplikuje. |

Spätný pohľad `[dedup:ref]` je zámerné rozhodnutie protokolu, — neexistuje žiadna rekonštrukcia pred odoslaním. Berte to tak, že „presný text už bol na drôte skôr v tejto relácii.“

### Predpoklady klienta

- **Kľúč (stdio):** volajúci stdio nenesie žiadnu identitu na žiadosť, takže sa autentifikuje pomocou `OMNIROUTE_API_KEY` (nastavené v `env` servera MCP ). Bez neho je volajúci anonymný a nástroje, ktoré vyžadujú príkazcu, sa môžu znehodnotiť.
- **`tools[]` je predpokladom injekcie.** Vloží sa inštrukcia protokolu načítania CCR (#8033).** iba** keď inzerovaný `tools[]` v požiadavke dokáže, že klient môže skutočne dosiahnuť `omniroute_ccr_retrieve`. Zhoda je zhoda koncového segmentu ohraničená oddeľovačom (`__`, `.`, `/`, `:`) — nikdy nie holý podreťazec —, takže názov v mennom priestore, ako napríklad `mcp__gateway__omniroute_ccr_retrieve` sa stále počíta. Chýbajúci alebo nezodpovedajúci `tools[]` znamená, že inštrukcia _nie je_ vložená podľa návrhu.
- **`codemode:false` (klienti OpenCode ).** OpenCode je predvolene nastavený na režim kódu, ktorý inzeruje iba svoje natívne nástroje pre model a** nie** vložte nástroje MCP do natívneho zoznamu `tools[]`. Nastavte `codemode: false` na záznam servera MCP, aby boli nástroje `omniroute_ccr_*` inzerované. Toto je a** klienta** nastavenie, nie OmniRoute. Zatiaľ nie je vložená inštrukcia CCR : OpenCode pomenúva nástroj `<server>_<tool>`, takže server s názvom `omniroute` odhaľuje `omniroute_omniroute_ccr_retrieve` a `_` nie je jedným zo zodpovedajúcich oddeľovačov.
- **Riaditeľky.** Ukladanie a získavanie sú izolované na overený princíp (na kľúč API ). Kľúč vidí iba svoje vlastné bloky.

### Rozsahy na nástroj

Presadzovanie rozsahu je vždy zapnuté pre úzky rozsah volaní HTTP/SSE. Nástroje `omniroute_` CCR vyžadujú:

| Nástroj                  | Rozsah              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Chýbajúci rozsah vráti an** výsledok chyby nástroja MCP** (`isError: true`, nie HTTP 403 — `403 LOCAL_ONLY` je samostatné overenie ochrany trasy spätnou slučkou): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimálny diaľkový kľúč môže obsahovať `mcp:connect` (autorizuje len lokálne vyňatie `/api/mcp/` ) plus špecifický rozsah read/write ktorý potrebuje.

### Klientska matica

| Klient                | Doprava                                      | Konfigurácia na použitie                                                                                                                                                                                                                                    | `tools[]` inzerované? (inštrukcia → CCR bola vstreknutá)                                                                                                                                     |
| --------------------- | -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kód            | streamovateľný-http                          | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                           | Áno — s podporou MCP; injekčne.                                                                                                                                                              |
| Cursor / Cline        | `stdio`** alebo** `streamable-http`          | stdio: `omniroute --mcp` so `OMNIROUTE_API_KEY` v `env`; alebo vzdialený vstup MCP smerujúci na `http://localhost:20128/api/mcp/stream` (pozrite si [Inštalačný sprievodca → MCP Konfigurácia klienta](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Áno — propaguje nástroje `omniroute_ccr_*`.                                                                                                                                                  |
| OpenCode              | streamovateľný-http                          | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` plus `codemode: false`                                                                                                                                                             | Nástroje inzerované iba s `codemode: false`; inštrukcia stále nie je vložená, pretože `omniroute_omniroute_ccr_retrieve` sa nezhoduje (pozri [Predpoklady klienta](#client-prerequisites) ). |
| Kompatibilné s OpenAI | HTTP kompatibilná s OpenAI (dokončenie četu) | štandardný klient dokončenia chatu proti koncovému bodu kompatibilnému s OpenAI                                                                                                                                                                             | **Nikdy** — obyčajnému volajúcemu kompatibilnému s OpenAI sa nikdy nepovie, aby zavolal nástroj, a inštrukcia sa nevloží.                                                                    |

### Limity načítania a stránkovanie

Výsledky textu nástroja MCP sú orezané okolo `mcpAccessibility.maxTextChars` (predvolené `50000`). Načítanie bloku `full` je obmedzené na 256 KiB —** neexistuje žiadne neobmedzené úplné načítanie** . Keď je `chars=N` bloku veľké, namiesto vytiahnutia celej veci ho stránkujte:

- Základné pravidlo:**`chars > 40000` → použite `mode`** , nikdy holé plné.
- `mode:"grep"` — regulárny výraz `pattern` zhodný riadok po riadku, až 1 000 zodpovedajúcich riadkov (`unique: true` kvapky sa opakuje), najlacnejšie pre "nájsť jeden riadok, ktorý potrebujem."
- `mode:"lines"` — 1-indexovaný riadkový rozsah; potrebuje `start` aj `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` riadky.
- `mode:"stats"` — počet riadkov, znakov a bajtov bez tela.

Použite `mode:"lines"` s `start`/`end` na prechádzku dlhým blokom stránok, namiesto toho, aby ste požadovali celú vec naraz.

### Pomenovanie nástroja

Nástroj na načítanie sa momentálne volá `omniroute_ccr_retrieve` (predpona `omniroute_` je datované riešenie pre kolízie názvov medzi servermi). Čistejší názov nástroja s ohraničenou príponou a oprava výsledkov MCP JSON skrátená v strede reťazca sú sledované ako upstream follow-up; táto stránka dokumentuje iba aktuálne správanie pri dodávke.

### Životný cyklus relácie

Streamovateľné-HTTP relácie sú nečinné a server ich zbiera; nečinné okno je konštanta `MCP_SESSION_IDLE_MS` (odkazovaná názvom, nie pevne zakódovanou hodnotou, takže táto stránka sa pri zmene nehýbe). Príznakom nečinne zozbieranej relácie je HTTP 404 s `Unknown Mcp-Session-Id` — nápravou je opätovné pripojenie alebo reštart relácie,** nie** na otočenie kľúča, zmenu rozsahu alebo premenovanie nástroja.

## API povrch

| Trasa                                  | Účel                                                                    |
| -------------------------------------- | ----------------------------------------------------------------------- |
| `/api/settings/compression`            | Globálne nastavenia kompresie (zahŕňa konfiguráciu `mcpAccessibility` ) |
| `/api/compression/preview`             | Ukážka akéhokoľvek režimu kompresie                                     |
| `/api/compression/language-packs`      | Zoznam dostupných jazykových balíkov Caveman                            |
| `/api/context/caveman/config`          | Nastavenia jaskynného muža alias                                        |
| `/api/context/rtk/config`              | predvolené nastavenia a nastavenia RTK                                  |
| `/api/context/rtk/filters`             | katalóg filtrov RTK                                                     |
| `/api/context/rtk/test`                | RTK preview/test koncový bod                                            |
| `/api/context/rtk/raw-output/[id]`     | Overené zredukované obnovenie surového výstupu                          |
| `/api/context/combos`                  | Kompresná kombinácia CRUD                                               |
| `/api/context/combos/[id]/assignments` | Smerovanie-kombo priradenie CRUD                                        |
| `/api/context/analytics`               | Alias analýzy kompresie                                                 |

Manažérske trasy vyžadujú manažérsku autentifikáciu alebo kontrolu politiky kľúča API.

## Nástroje MCP

Kompresia odhaľuje päť nástrojov MCP :

| Nástroj                             | Rozsah              | Účel                                                  |
| ----------------------------------- | ------------------- | ----------------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Nastavenia, analytika, štatistiky vyrovnávacej pamäte |
| `omniroute_compression_configure`   | `write:compression` | Aktualizujte globálne nastavenia                      |
| `omniroute_set_compression_engine`  | `write:compression` | Nastavte režim a voliteľné potrubie                   |
| `omniroute_list_compression_combos` | `read:compression`  | Zoznam komprimačných kombinácií                       |
| `omniroute_compression_combo_stats` | `read:compression`  | Prečítajte si analýzu combo/engine                    |

## Rozsah a vylúčenia

**Vložky nie sú nikdy komprimované.** `open-sse/handlers/embeddings.ts` nikdy nevolá žiadny kompresný motor — telá request/response prechádzajú priamo k vykonávateľovi nedotknuté. Toto je dnes štrukturálne (vkladanie a dokončovanie chatu sú nesúvislé obslužné nástroje), nie je to kontrola za behu, ale znamená to, že problém s vektorovým skreslením v #8034 nemá na ceste vkladania žiadny povrch.

**Per-model/endpoint vylučovací filter (#8034).** Pre dokončenie chatu môže operátor pomenovať ID modelu / ciele `provider/model`, ktoré sa nikdy nesmú komprimovať — zábradlie, ktoré je užitočné, ak sa kompresia niekedy pripojí bližšie k ceste susediacej s vložením, a vo všeobecnosti je užitočná pre akýkoľvek model, pre ktorý záleží na presných bajtoch po bajtoch (deterministické hodnoty, predpony citlivé na vyrovnávaciu pamäť atď.).

- Pole nastavení: `exclusions?: string[]` na globálnej konfigurácii kompresie (`GET`/`PUT /api/settings/compression`), zachované prostredníctvom existujúceho priestoru názvov kompresie `key_value` (`src/lib/db/compression.ts`) — žiadna nová tabuľka.
- Karta Dashboard:** Dashboard → Kompresia → Vylúčenia** (`/dashboard/compression/exclusions`).
- Syntax vzoru: `*` je jediný zástupný znak. Každý ďalší metaznak regulárneho výrazu vo vzore je pred zhodou escapovaný, takže `gpt-5.6` sa zhoduje iba s doslovným reťazcom, nikdy nie `gpt-5x6` (ReDoS-safe, bounded, žiadne vnorené kvantifikátory). Vzory sa bez ohľadu na veľkosť písmen zhodujú s holým ID modelu aj so zloženým `provider/model` — `gpt-5-6`, `openai/gpt-5-6` a `openai/*`, pričom samotné `*` vylučuje každý model.
- Zhoda: `isCompressionExcluded()` / `normalizeCompressionExclusions()` v `open-sse/services/compression/exclusions.ts`. `chatCore.ts` skontroluje vylúčený cieľ hneď po vyriešení nastavení kompresie,** pred spustením akéhokoľvek motora** a zaobchádza so zhodou presne tak, ako keby bola kompresia globálne zakázaná — telo požiadavky je dokázateľne bajtovo identické. Preskočenie sa zaznamená cez `writeCompressionSkip(..., "excluded")` pre viditeľnosť analýzy.
- Predvolené (zoznam empty/absent ): identické so správaním pred #8034 — nie je vylúčené nič.

## Známe obmedzenia

- **LLMLingua-2 (SLM) vyžaduje spoločne umiestnené voliteľné deps.** Pracovník beží v produkčnej zostave iba vtedy, keď sú kolegovia `@atjsh/llmlingua-2` + spoločne umiestnení do `dist/node_modules` (pozri `scripts/build/colocateOptionals.mjs`, #4286). Bez nich sa zlyhanie motora otvorí (vráti pôvodný text). Pracovné rozlíšenie už nezávisí od `import.meta.url` (zomrie v samostatnom balíku) — sa ukotví na runtime cwd / `argv[1]`.
- **Jazykové balíčky Caveman `de` / `fr` / `ja` sú čiastočné.** Dodávajú pravidlá `context` + `filler` + `structural`, ale žiadne balíčky `dedup` / `ultra`, takže intenzita `ultra` nie je pre tieto jazyky silnejšia ako `full` (používajú iba svoje vlastné pravidlá — neexistuje žiadny tichý návrat k anglickým pravidlám `dedup`/`ultra`, ktoré by poškodili cudzí text). `en` / `es` / `id` / `pt-BR` sú dokončené. Príspevky `dedup.json` + `ultra.json` pre čiastočné balíčky sú vítané.
- **Skladaná telemetria uvádza iba motory, ktoré sa komprimovali.** Krok naskladaného potrubia, ktorého motor bežal, ale priniesol 0 % úsporu, vracia `stats:null` a preto sa neobjavuje v `engineBreakdown` — na nerozoznanie od kroku, ktorý bol preskočený. Rozlíšenie „beží, 0 %“ od „vynechaných“ by si vyžadovalo zmenu modelu rozdelenia a je odložené.

## Validácia

Zamerané brány pre túto oblasť sú:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
