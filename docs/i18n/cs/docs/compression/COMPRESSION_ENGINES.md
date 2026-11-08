# Compression Engines (Čeština)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute komprese je postavena na kontraktech motoru. Režim může spouštět přímo jeden motor (`caveman` nebo `rtk`) nebo deterministický skládaný kanál, který spouští více motorů v pořadí.

## Režimy

| Režim        | Dráha motoru                                                                          | Zamýšlený vstup                                      |
| ------------ | ------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| `off`        | žádný                                                                                 | Přesná rychlá konzervace                             |
| `lite`       | Caveman lite pomocníci                                                                | Vždy zapnuté čištění s nízkým rizikem                |
| `standard`   | Barbar                                                                                | Rychlá kondenzace v přirozeném jazyce                |
| `aggressive` | Jeskynní muž + history/tool shrnutí                                                   | Dlouhé chatovací relace                              |
| `ultra`      | Caveman + pomocníky pro prořezávání                                                   | Obnova s omezením kontextu                           |
| `rtk`        | RTK                                                                                   | Terminál, shell, build, test a výstup git            |
| `omniglyph`  | OmniGlyph                                                                             | Kontext jako obrázek na nativním drátu poskytovatele |
| `stacked`    | Potrubí. Výchozí požadavek je `session-dedup -> lite`. `rtk -> caveman` je přihlášen. | Smíšené protokoly nástrojů a próza, maximální úspory |

### OmniGlyph kompresní profily

Modul `omniglyph` (balíček `omniglyph`, 1.4.0 +) přijímá pojmenovaný sémantický profil, nastavený globálně pomocí `omniglyph.profile` v nastavení komprese nebo po jednotlivých krocích v konfiguraci kroků složeného potrubí:

| Profil        | Hranice                                                                                                |
| ------------- | ------------------------------------------------------------------------------------------------------ |
| `aggressive`  | Výchozí. Politika zveřejněných účtenek měřila systém obrázků —, dokumentaci nástrojů a hustou historii |
| `balanced`    | Udržuje živý stav nativní, chrání posledních 8 kol, sbaluje starší uzavřenou historii                  |
| `coding-safe` | Udržuje autoritu, schémata nástrojů a živý výstup nástroje nativní, chrání posledních 12 otáček        |
| `passthrough` | Trasy bez transformace; motor je přeskočen                                                             |

Profil je a** strop, ne podlaha** : `mergeCompressionProfileOptions` v balíčku odmítá umožnit volajícímu přepsat znovuotevření ztrátového pruhu, v němž byl profil uzavřen, takže `preserveSystemPrompt: false` po jednotlivých krocích nemůže znovu povolit kompresi systému pod `coding-safe`.

Měřeno na této kódové základně: `coding-safe` a `balanced` zvyšují `minCompressChars` na maximum a udržují systém, schémata nástrojů a výsledky nástrojů nativní, takže relace, která dosud neshromáždila historii, se zastaví na `below_min_chars` a engine nic nemění. Proto je výchozí `aggressive` spíše než nejbezpečnější profil.

Balíček řeší svůj vlastní rozsah modelu a profil z konfigurace prostředí. OmniRoute nikdy nedeleguje rozhodnutí: adaptér připíná modelovou bránu do nejpřísnějšího rozsahu balíčku, takže nastavení hostitelského prostředí může pouze zúžit seznam povolených, nikdy jej rozšířit za naměřené příjmy OmniRoute.

## Registr motoru

Registr žije v `open-sse/services/compression/engines/registry.ts`. Motory odhalují sdílenou smlouvu:

- `id`: stabilní ID motoru, jako je `caveman` nebo `rtk`
- `apply(text, config)`: starší cesta provádění používaná skládanými potrubími
- `compress(input, config)`: cesta primárního provedení vracející textové statistiky +
- `getConfigSchema()`: Vrátí platný tvar konfigurace podobný JSON-Schema
- `validateConfig(config)`: vrátí `{ valid, errors[] }`

Registrace používá `registerCompressionEngine(engine)` (nebo `registerEngine` pro pokročilé případy), který před přijetím volá `assertValidEngine()` a `validateConfig(defaultConfig)`. Pomocí `unregisterCompressionEngine(id)` odeberte motor za běhu.

`strategySelector.ts` registruje vestavěné motory před spuštěním komprese. To umožňuje náhled, kompresi za běhu, skládaný režim, testy a budoucí motory používat stejnou cestu provádění.

### komprese popisu MCP (související)

Samostatný registr komprimuje metadata popisu nástroje MCP na úrovni registru — viz `open-sse/mcp-server/descriptionCompressor.ts` a [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Znovu používá pravidla Caveman, ale pracuje s metadaty nástroje, nikoli s daty požadavků.

### Další vestavěné motory

Kromě Caveman, RTK a LLMLingua-2 registr dodává několik specializovaných bezztrátových/strukturálních motorů (používaných naskládanými potrubími, hřišti a testy):

| Motor         | Id              | Co to dělá                                                                                                                                                                |
| ------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): Nahrazuje velké souvislé textové bloky odkazy s adresou obsahu, takže bloky repeated/large jsou odeslány jednou a poté se na ně odkazuje. |
| světlá výška  | `headroom`      | SmartCrusher (H3 + N5): bezztrátové tabulkové zhutnění homogenního užitečného zatížení JSON-pole do sloupcové formy `[N rows]`.                                           |
| ionizátor     | `ionizer`       | vzorkování řádků Head/middle/tail pro velmi velké homogenní bloky s uložením elidovaného středu jako odkazu s adresou obsahu CCR.                                         |
| session-dedup | `session-dedup` | Křížová deduplikace zaměřená na obsah (inspirovaná TokenMizer): odstraňuje text, který se již zobrazil v dřívějších kolech stejné relace.                                 |

**instrukce CCR načítání protokolu (#8033):** když poprvé CCR nahradí ≥ 1 blok v požadavku, engine přidá jednu idempotentní zprávu `system` (vedoucí s hlídačem `[CCR protocol]` ), která volajícího naučí značku → tool contract: co značka `[CCR retrieve hash=<24hex> chars=N]` znamená, že hash musí být zkopírován doslovně (všech 24 hexadecimálních znaků, které nebyly nalezeny), jsou pravděpodobně chybně zkopírovány a `[dedup:ref sha=...]` — „ohlédnout se do historie“, nikoli „zavolat nástroj“. Poznámka je vstříknuta** pouze tehdy, když inzerovaný `tools[]` volajícího prokáže, že může skutečně dosáhnout `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — obyčejný volající kompatibilní s OpenAI bez tohoto nástroje nikdy neobdrží pokyn k volání něčeho, na co nemůže dosáhnout. Idempotence je vynucena skenováním historie zpráv pro hlídače před podáním injekce, takže vícekolové požadavky (které přehrají předchozí zprávy) neskládají poznámku jednou za kolo.

## Barbar

Režim Caveman se zaměřuje na sémantickou kondenzaci normální prózy:

- zachovává bloky kódu, URLs, JSON, cesty a strukturovaná data
- odstraňuje výplň, hedging, opakovaný kontext a verbózní spojovací fráze
- podporuje jazykové balíčky pravidel souborů v `open-sse/services/compression/rules/`
- zůstává k dispozici prostřednictvím starších režimů `standard`, `aggressive` a `ultra`

Povrch palubní desky je `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream hlásí `~75%` méně výstupních tokenů, průměrné úspory výstupu `65%` v benchmarcích s rozsahem `22-87%` a nástroj pro kompresi vstupu `~46%`. OmniRoute používá Caveman vstupní číslo při dokumentování skládaných úspor prompt/context ; Výstupní režim Caveman zůstává samostatnou funkcí odezvy a chování.

## RTK

Režim RTK se zaměřuje na výstup příkazů a nástrojů:

- detekuje výstupní třídy, jako jsou `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testy, sestavení TypeScript/Vite/Webpack, ESLint, npm audit/installs, Docker protokoly, shell `find`/`grep`, trasování zásobníku a obecné protokoly
- aplikuje 49 JSON filtrů z `open-sse/services/compression/engines/rtk/filters/`
- podporuje deklarativní potrubí ve stylu RTK: ANSI stripping, replacement, match-output short-circuit, strip/keep lines, per-line zkrácení, head/tail/max-line zkrácení a záložní zdroj při vyprázdnění
- podporuje důvěryhodné projektové filtry v `.rtk/filters.json` a globální filtry v `DATA_DIR/rtk/filters.json`
- stripuje ANSI sekvence, progresivní šum, opakované řádky a neužitečné standardy
- zachovává proveditelná selhání, varování, souhrny, změněné soubory a kontext
- může volitelně zachovat redigovaný nezpracovaný výstup pro recovery/debugging prostřednictvím ověřených cest správy

Povrch palubní desky je `Dashboard -> Context & Cache -> RTK`.

Provozní podrobnosti o vlastních filtrech, důvěře, ověřování a obnově nezpracovaného výstupu živě v [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream hlásí úspory `60-90%` pro kompresi výstupu příkazů. Jeho příklad README ukazuje 30minutovou relaci kódu Claude přecházející z tokenů `~118,000` na `~23,900` nebo `79.7%` uložené.

## LLMLingua-2 (sémantické prořezávání)

provede se režim LLMLingua-2** prořezávání sémantických tokenů** na próze pomocí malého klasifikátoru tokenu ONNX, který doplňuje enginy Caveman a RTK založené na pravidlech:

- komprimuje prózu pouze v nesystémových zprávách; oplocené bloky kódu a další zachované konstrukce se nikdy nemění
- spouští backend `@atjsh/llmlingua-2` (ONNX přes `@huggingface/transformers`) v pracovním vláknu, takže odvození modelu nikdy neblokuje smyčku událostí požadavku
- je** stohovatelné** (`stackPriority` 35): ve složeném potrubí běží za strukturálními motory (CCR, session-dedup, headroom, Caveman), ale před `ultra`, protože sémantické ořezávání je nejúčinnější na již strukturálně komprimovaném textu — např. `rtk -> caveman -> llmlingua`
- **selhání se otevře při jakékoli chybě** (chybí volitelná deps, worker spawn, model load, inference nebo timeout) → původní text je vrácen nezměněn, nikdy chyba

Umístění motoru: `open-sse/services/compression/engines/llmlingua/`. Povrch palubní desky je `Dashboard -> Context & Cache -> LLMLingua`.

### Modelky

Výchozí model je**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, rychle). Vyšší přesnost** BERT-základna** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) je k dispozici prostřednictvím pole konfigurace motoru `model`. `@huggingface/transformers` líně stáhne vybraný model z hubu HuggingFace do `${DATA_DIR}/models/llmlingua` při prvním volání (`modelStore.ts`); přepsání konfigurace `modelPath` jej místo toho nasměruje na místní kopii (offline / instalace se vzduchovou mezerou).

### Volitelné závislosti a instalace na vyžádání

Ořezatelný LLMLingua runtime peer stack je** volitelný** . Dva balíčky jsou v `package.json` deklarovány jako `optionalDependencies` a jsou uchovávány** externí** podle produkčního sestavení (`scripts/build/prepublish.ts` je nesdružuje):

| Balík                | Verze (pin) | Poznámky                                        |
| -------------------- | ----------- | ----------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`     | Vstupní balíček; prohlásí ostatní za vrstevníky |
| `js-tiktoken`        | `^1.0.20`   | Tokenizer                                       |

`@huggingface/transformers` je připnuto na `^4.2.0` (sdíleno s místní cestou vložení a také trasováno do samostatného balíčku); `@atjsh/llmlingua-2@2.0.5` se na něm shoduje s `"^3.5.2 || ^4.0.0"`, takže jsou podporovány Transformers.js v3 i v4. Od verze 2.0.4 již `@atjsh/llmlingua-2` nevyžaduje `@tensorflow/tfjs`, což odstranilo největšího jediného přispěvatele (TensorFlow.js) ze zásobníku SLM. Pouze dva výše uvedené balíčky jsou ořezatelné SLM peery. Standardní `npm install` (dev) nainstaluje volitelný zásobník automaticky, pokud nejsou vynechány volitelné závislosti.

**Proč na vyžádání:** balíček publikovaný npm, samostatný balíček a obrazová loď Docker** bez** tyto deps zůstat štíhlý. Když nejsou přítomny, brána závislosti pracovníka (sonda rozlišení `@atjsh/llmlingua-2` v `worker.ts`) selže a motor** selhání-otevře se tiše** — výběrem LLMLingua se stane neoperace (text vrácen nezměněn, žádná chyba zaznamenána). Chcete-li jej aktivovat v omezeném prostředí, nainstalujte volitelný zásobník:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Odstranění `@tensorflow/tfjs` (2.0.4 +) eliminuje dříve dominantního přispěvatele ~ 800 MB — zbývající stopa je běhová prostředí transformers.js + onnxruntime-node plus model TinyBERT (~ 57 MB) stažený při prvním použití (ne prostřednictvím npm).

Pro prostředí:

- **Dev / `npm install`** — se nainstaluje automaticky, pokud neprojdete `--omit=optional` (nebo `--no-optional`). Není potřeba žádná akce.
- **Globální npm (`npm i -g omniroute`) / samostatný** — spusťte výše uvedený příkaz install v adresáři nainstalovaného balíčku nebo přeinstalujte bez vynechání volitelných deps.
- **Docker** — přidat příkaz install do odvozené vrstvy obrazu; publikovaný obrázek je navržen jako tenký.
- **VPS (PM2)** — nainstalujte do `node_modules` aplikace, poté restartujte proces, aby pracovník znovu otestoval bránu.
- **Raw Next samostatný (`npm run build` → `.build/next/standalone/server.js`)** — samostatné trasovací lodě NEITHER pracovníka ani volitelná oddělení, takže motor se tiše porouchá-otevře. `scripts/build/colocate-standalone.mjs` znovu použije obojí (pracovní esbuild + optional-dep closure do samostatného stromu); běží automaticky přes `postbuild` npm hook po každém sestavení. Idempotentní, odolný proti selhání, když chybí deps.

**Ověřte, zda je aktivní:** s vybraným LLMLingua se skutečná próza ve skutečnosti zmenší (motor se zastaví při selhání otevírání) a první požadavek spustí stažení modelu do `${DATA_DIR}/models/llmlingua`. Brána záměrně sonduje pouze `@atjsh/llmlingua-2` — ostatní peery jsou pouze ESM a `require.resolve` na ně hází, i když jsou přítomny — takže pracovník stále selže a otevře se, pokud některý z peerů v době `import()` skutečně chybí.

## Skládané potrubí

Skládaný režim provádí kroky potrubí v pořadí. Výchozí hodnota je:

```txt
rtk -> caveman
```

Použijte to pro relace kódovacího agenta, kde výzva kombinuje výstup příkazu s lidskou nebo asistentskou prózou. RTK nejprve redukuje hlučné protokoly nástrojů, poté Caveman komprimuje zbývající přirozený jazyk.

Kroky potrubí se konfigurují pomocí `stackedPipeline` v nastavení komprese nebo pomocí kombinací komprese.

Když oba motory sníží stejné způsobilé užitečné zatížení, sloučenina úspory:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Stromový filtr přístupnosti

Inteligentní filtr stromu dostupnosti MCP je vrstva komprese po spuštění, která běží na MCP** výsledky nástroje** , nikoli na výzvy nebo kontext. Zaměřuje se na podrobný strom přístupnosti a užitečné zatížení snímků prohlížeče vrácené nástroji jako Playwright, computer-use a browser-automation servers MCP.

### Co to dělá

1. **Odstraňování hluku** — odstraní prázdné položky generic/text (`- generic:`, `- text: ""`)
2. **Sourozenecký kolaps** — když ≥ `collapseThreshold` (výchozí 30) po sobě jdoucí řádky jsou strukturální opakování, sbalí je do prvních `collapseKeepHead` (výchozí 10) řádků + souhrn počtu + posledních `collapseKeepTail` (výchozí 5) řádků
3. **Ref konzervace** Kotvy — `[ref=eXX]` požadované Playwright/computer-use se nikdy nedotýkají
4. **Tvrdé zkrácení** — pokud text po sbalení stále překračuje `maxTextChars` (výchozí 50 000), zkrátí se pomocí navigačního náznaku, aby agent mohl pokračovat v práci

### Umístění motoru

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfigurace

Ovládá se `compression.mcpAccessibility` v globálním nastavení (migrace 056). Výchozí konfigurace:

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

Filtr se aplikuje pouze na užitečná zatížení výsledků nástroje, jejichž `type` je `"text"` a jejichž délka přesahuje `minLengthToProcess`. Neovlivňuje okamžitou kompresi nebo vyžádané užitečné zatížení.

### Očekávané úspory

60–80 % na výsledky nástroje pro snímky prohlížeče v závislosti na složitosti stránky. Algoritmus kolapsu je O(n) v počtu řádků a přidává zanedbatelnou latenci.

### Tento filtr vs. kompresní motory výše

| Aspekt    | Caveman / RTK / Stacked      | MCP filtr přístupnosti                 |
| --------- | ---------------------------- | -------------------------------------- |
| Cíl       | Výzvy / kontext požadavků    | výsledky nástroje MCP                  |
| Spoušť    | Nastavení kompresního režimu | `compression.mcpAccessibility.enabled` |
| Rozsah    | Všechny zprávy SSE           | Pouze výsledky nástroje                |
| Ref kotvy | N/A                          | Bezpodmínečně zachováno                |

---

## Kompresní kombinace

Komprimační komba jsou pojmenované kompresní profily, které lze přiřadit směrovacím kombám:

- `compression_combos`: ukládá režim, kanál, konfiguraci RTK, konfiguraci jazyka a výchozí značku
- `compression_combo_assignments`: mapuje kompresní kombo na routovací kombo
- integrace za běhu řeší přiřazené kompresní kombo před přepsáním generického komba
- analytiky zahrnují `compression_combo_id` a `engine`

Povrch palubní desky: `Dashboard -> Context & Cache -> Compression Combos`.

## Předpoklady / průvodce operátora (CCR & session-dedup)

CCR (`ccr`) a `session-dedup` nahradí nebo vynechá text a ponechá a** značka** za. Tato část je referenčním bodem pro operátora pro zapojení klienta, čtení dvou značek a načítání nebo diagnostiku elidovaného obsahu. Mechanika každého motoru je popsána výše; toto je vrstva „jak to spustím“.

### Transporty a koncové body

K serveru MCP, který odhaluje nástroje CCR se lze dostat třemi způsoby. Výchozí základní URL je `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Doprava                                  | URL / příkaz                            | Poznámky                                                                                                                               |
| ---------------------------------------- | --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Streamovatelné HTTP (klient, doporučeno) | `http://localhost:20128/api/mcp/stream` | Koncový bod, se kterým aktuální klienti MCP mluví.                                                                                     |
| Starší SSE singleton                     | `http://localhost:20128/api/mcp/sse`    | Starší singleton transport. To** zavírá** streamovatelné relace; použijte `streamable-http` klienty proti `/api/mcp/stream`, ne tento. |
| stdio                                    | `omniroute --mcp`                       | Pro konfiguraci IDE MCP, která spustí proces. Neexistuje žádná vlajka `--dev` ; `omniroute --mcp` je vstupní bod stdio.                |

### Úložné vrstvy (co přežije restart)

CCR je a** dvouvrstvý** úložiště, nikoli pouze v paměti:

- **Horká vrstva v paměti** — na blok cap 2 MiB, na jistinu 16 MiB, globální 64 MiB. Výchozí nastavení je 24 h TTL (maximálně 7 dní). Plné načítání MCP z paměti je omezeno na 256 KiB; cokoli většího je stále dosažitelné prostřednictvím režimů ranged / grep.
- **Odolná vrstva SQLite** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, ve výchozím nastavení zapnuto) — zálohuje vrstvu v paměti, takže blok přežije vystěhování LRU, restart nebo přistání načtení v jiné instanci. Řádek si zachovává TTL bloku, takže blok za jeho TTL je pryč z obou vrstev.

Tři strážci udržují odolnou úroveň — a blok zůstává pouze v paměti, když:

1. blok je u konce** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. běhové prostředí je cloudové běhové prostředí (bez místního disku);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Takže „blok zmizel“ není příběh o plošném restartu: blok sub-512 KB na místním necloudovém běhovém prostředí přežije restart přes trvanlivou vrstvu, dokud nedojde jeho TTL. Proměnnou viz [Reference prostředí](../reference/ENVIRONMENT.md).

### Dvě značky

| Marker                                | Význam                                                                                                                                 | Co by měl model dělat                                                                                                                                                                                |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Byl uložen velký blok s adresným obsahem.                                                                                              | Zavolejte `omniroute_ccr_retrieve` s** 24hexový hash doslovně zkopírován** získat zpět původní text.                                                                                                 |
| `[dedup:ref sha=…]`                   | `session-dedup` elidovaný text již odeslaný v dřívějším kole stejné relace. Toto je** záměrné ohlédnutí** , není to ztráta nebo chyba. | Dělat** ne** zavolejte jakýkoli nástroj a udělejte to** ne** zkuste to "zrekonstruovat". První výskyt textu je kanonický opis; aktuální tah se nikdy nepřepisuje, při pozdějším tahu se deduplikuje. |

Zpětný pohled `[dedup:ref]` je záměrné rozhodnutí protokolu — neexistuje žádná rekonstrukce před odesláním. Považujte to za „přesný text byl na drátě již dříve v této relaci“.

### Předpoklady klienta

- **Klíč (stdio):** volající stdio nenese žádnou identitu na žádost, takže se ověřuje pomocí `OMNIROUTE_API_KEY` (nastaveno v `env` serveru MCP ). Bez něj je volající anonymní a nástroje, které vyžadují příkazce, mohou degradovat.
- **`tools[]` je předpokladem injekce.** Instrukce CCR retrieve-protocol (#8033) je injektována** pouze** když inzerovaný `tools[]` požadavku prokáže, že klient může skutečně dosáhnout `omniroute_ccr_retrieve`. Shoda je shoda koncového segmentu ohraničená oddělovačem (`__`, `.`, `/`, `:`) — nikdy není holý podřetězec —, takže se stále počítá název se jmenným prostorem, jako je `mcp__gateway__omniroute_ccr_retrieve`. Chybějící nebo neodpovídající `tools[]` znamená, že instrukce _není_ vložena, podle návrhu.
- **`codemode:false` (klienti OpenCode ).** OpenCode je výchozím režimem kódu, který inzeruje pouze své nativní nástroje pro model a** ne** vložte nástroje MCP do nativního seznamu `tools[]`. Nastavte `codemode: false` na záznam serveru MCP, aby byly nástroje `omniroute_ccr_*` inzerovány. Toto je a** klienta** nastavení, ne OmniRoute. Instrukce CCR ještě nebyla vložena: OpenCode pojmenovává nástroj `<server>_<tool>`, takže server zvaný `omniroute` odhaluje `omniroute_omniroute_ccr_retrieve` a `_` není jedním ze shodných oddělovačů.
- **Ředitelé.** Úložiště a načítání jsou izolovány na ověřený principál (na klíč API ). Klíč vidí pouze své vlastní bloky.

### Rozsahy na nástroj

Vynucení rozsahu je vždy zapnuto pro úzkoprofilové HTTP/SSE volající. Nástroje `omniroute_` CCR vyžadují:

| Nástroj                  | Rozsah              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Chybějící rozsah vrátí an** výsledek chyby nástroje MCP** (`isError: true`, ne HTTP 403 — `403 LOCAL_ONLY` je samostatné ověření zpětné smyčky route-guard): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimální dálkový klíč může obsahovat `mcp:connect` (autorizuje pouze místní vyjmutí `/api/mcp/` ) plus specifický rozsah read/write který potřebuje.

### Klientská matice

| Klient                | Doprava                                      | Konfigurace k použití                                                                                                                                                                                                                           | `tools[]` inzerováno? (Vstrčena instrukce → CCR )                                                                                                                                       |
| --------------------- | -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kód            | streamovatelný-http                          | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                               | Ano — s podporou MCP; injekčně.                                                                                                                                                         |
| Cursor / Cline        | `stdio`** nebo** `streamable-http`           | stdio: `omniroute --mcp` se `OMNIROUTE_API_KEY` v `env`; nebo vzdálený vstup MCP ukazující na `http://localhost:20128/api/mcp/stream` (viz [Průvodce nastavením → MCP Konfigurace klienta](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Ano — inzeruje nástroje `omniroute_ccr_*`.                                                                                                                                              |
| OpenCode              | streamovatelný-http                          | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` plus `codemode: false`                                                                                                                                                 | Nástroje inzerované pouze u `codemode: false`; instrukce stále není vložena, protože `omniroute_omniroute_ccr_retrieve` neodpovídá (viz [Předpoklady klienta](#client-prerequisites) ). |
| kompatibilní s OpenAI | HTTP kompatibilní s OpenAI (dokončení chatu) | standardní klient pro dokončení chatu proti koncovému bodu kompatibilnímu s OpenAI                                                                                                                                                              | **Nikdy** — obyčejnému volajícímu kompatibilnímu s OpenAI se nikdy neřekne, aby nástroj zavolal, a instrukce se nevloží.                                                                |

### Limity načítání a stránkování

Výsledky textu nástroje MCP jsou oříznuty kolem `mcpAccessibility.maxTextChars` (výchozí `50000`). Načtení `full` bloku je omezeno na 256 KiB —** neexistuje žádné neomezené úplné načtení** . Když je `chars=N` bloku velké, místo vytažení celé věci ho stránkujte:

- Základní pravidlo:**`chars > 40000` → použijte `mode`** , nikdy holý plný.
- `mode:"grep"` — regulární výraz `pattern` spárovaný řádek po řádku, až 1 000 odpovídajících řádků (`unique: true` se opakuje), nejlevnější pro "najít jeden řádek, který potřebuji."
- `mode:"lines"` — 1-indexovaný rozsah řádků; potřebuje `start` i `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` řádky.
- `mode:"stats"` — počet řádků, znaků a bajtů bez těla.

Použijte `mode:"lines"` s `start`/`end` k procházení dlouhého bloku na stránkách, místo abyste požadovali celou věc najednou.

### Pojmenování nástroje

Nástroj načítání se aktuálně jmenuje `omniroute_ccr_retrieve` (předpona `omniroute_` je zastaralé řešení pro kolize názvů mezi servery). Čistší název nástroje s omezenou příponou a oprava výsledků MCP JSON zkrácená uprostřed řetězce jsou sledovány jako upstream navazující; tato stránka dokumentuje pouze aktuální chování při dodávce.

### Životní cyklus relace

Streamovatelné relace HTTP jsou nečinné a server je sbírá; nečinné okno je konstanta `MCP_SESSION_IDLE_MS` (odkazovaná jménem, nikoli pevně zakódovanou hodnotou, takže tato stránka se při změně neposune). Příznakem nečinně sklízené relace je HTTP 404 s `Unknown Mcp-Session-Id` — nápravou je opětovné připojení nebo restart relace,** ne** pro otočení klíče, změnu rozsahu nebo přejmenování nástroje.

## API povrch

| Trasa                                  | Účel                                                                   |
| -------------------------------------- | ---------------------------------------------------------------------- |
| `/api/settings/compression`            | Globální nastavení komprese (zahrnuje konfiguraci `mcpAccessibility` ) |
| `/api/compression/preview`             | Náhled libovolného režimu komprese                                     |
| `/api/compression/language-packs`      | Seznam dostupných jazykových balíčků Caveman                           |
| `/api/context/caveman/config`          | Alias nastavení Caveman                                                |
| `/api/context/rtk/config`              | výchozí a nastavení RTK                                                |
| `/api/context/rtk/filters`             | Katalog filtrů RTK                                                     |
| `/api/context/rtk/test`                | RTK preview/test koncový bod                                           |
| `/api/context/rtk/raw-output/[id]`     | Ověřené obnovení nezpracovaného výstupu                                |
| `/api/context/combos`                  | Kompresní kombinace CRUD                                               |
| `/api/context/combos/[id]/assignments` | Směrování-kombo přiřazení CRUD                                         |
| `/api/context/analytics`               | Alias analýzy komprese                                                 |

Cesty správy vyžadují ověření správy nebo kontroly zásad API klíče.

## Nástroje MCP

Komprese odhaluje pět nástrojů MCP :

| Nástroj                             | Rozsah              | Účel                                        |
| ----------------------------------- | ------------------- | ------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Nastavení, analytika, statistiky mezipaměti |
| `omniroute_compression_configure`   | `write:compression` | Aktualizujte globální nastavení             |
| `omniroute_set_compression_engine`  | `write:compression` | Nastavte režim a volitelné potrubí          |
| `omniroute_list_compression_combos` | `read:compression`  | Seznam kompresních kombinací                |
| `omniroute_compression_combo_stats` | `read:compression`  | Přečtěte si analýzu combo/engine            |

## Rozsah a výjimky

**Vložení se nikdy nekomprimuje.** `open-sse/handlers/embeddings.ts` nikdy nevolá žádný kompresní motor — těla request/response přejdou přímo k exekutorovi nedotčená. To je dnes strukturální (vkládání a dokončování chatu jsou nesouvislé obslužné nástroje), nikoli kontrola za běhu, ale znamená to, že obava z vektorového zkreslení v #8034 nemá v cestě vkládání žádný povrch.

**filtr vyloučení Per-model/endpoint (#8034).** Pro dokončení chatu může operátor pojmenovat id modelu / cíle `provider/model`, které se nikdy nesmí komprimovat — zábradlí, které je užitečné, pokud je komprese někdy připojena blíže k cestě sousedící s vložením, a obecně užitečná pro jakýkoli model, u kterého záleží na přesném bajtu po bajtu (deterministické hodnoty, předpony citlivé na mezipaměť atd.).

- Pole nastavení: `exclusions?: string[]` na globální konfiguraci komprese (`GET`/`PUT /api/settings/compression`), přetrvává prostřednictvím existujícího jmenného prostoru komprese `key_value` (`src/lib/db/compression.ts`) — žádná nová tabulka.
- Karta Dashboard:** Dashboard → Komprese → Výjimky** (`/dashboard/compression/exclusions`).
- Syntaxe vzoru: `*` je jediný zástupný znak. Každý další metaznak regulárního výrazu ve vzoru je před párováním escapován, takže `gpt-5.6` odpovídá pouze doslovnému řetězci, nikdy ne `gpt-5x6` (ReDoS-safe, bounded, žádné vnořené kvantifikátory). Vzory se bez ohledu na velikost písmen shodují s holým ID modelu a složeným `provider/model` — `gpt-5-6`, `openai/gpt-5-6` a `openai/*` všechny fungují a samotné `*` vylučuje každý model.
- Shoda: `isCompressionExcluded()` / `normalizeCompressionExclusions()` v `open-sse/services/compression/exclusions.ts`. `chatCore.ts` zkontroluje vyloučený cíl hned po vyřešení nastavení komprese,** před spuštěním jakéhokoli motoru** a zachází se shodou přesně tak, jako kdyby byla komprese globálně zakázána — tělo požadavku je prokazatelně bajtově identické. Přeskočení je zaznamenáno pomocí `writeCompressionSkip(..., "excluded")` pro viditelnost analýzy.
- Výchozí ( seznam empty/absent ): identické s chováním před #8034 — není vyloučeno nic.

## Známá omezení

- **LLMLingua-2 (SLM) vyžaduje společně umístěná volitelná oddělení.** Pracovník běží v produkčním sestavení pouze tehdy, když jsou kolegové `@atjsh/llmlingua-2` + umístěni společně do `dist/node_modules` (viz `scripts/build/colocateOptionals.mjs`, #4286). Bez nich dojde k selhání motoru (vrátí původní text). Pracovní rozlišení již nezávisí na `import.meta.url` (zemře v samostatném balíčku) — je ukotveno na runtime cwd / `argv[1]`.
- **Jazykové balíčky Caveman `de` / `fr` / `ja` jsou částečné.** Dodávají pravidla `context` + `filler` + `structural`, ale žádné balíčky `dedup` / `ultra`, takže intenzita `ultra` není pro tyto jazyky silnější než `full` (používají pouze svá vlastní pravidla — neexistuje žádný tichý návrat k anglickým pravidlům `dedup`/`ultra`, která by zkazila cizí text). `en` / `es` / `id` / `pt-BR` jsou kompletní. Příspěvky `dedup.json` + `ultra.json` pro dílčí balíčky jsou vítány.
- **Složená telemetrie uvádí pouze motory, které byly komprimovány.** Krok složeného potrubí, jehož motor běžel, ale produkoval 0 % úspor, vrací `stats:null` a proto se neobjevuje v `engineBreakdown` — k nerozeznání od kroku, který byl přeskočen. Rozlišení „běžel, 0 %“ od „přeskočeno“ by vyžadovalo změnu modelu členění a je odloženo.

## Validace

Zaměřené brány pro tuto oblast jsou:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
