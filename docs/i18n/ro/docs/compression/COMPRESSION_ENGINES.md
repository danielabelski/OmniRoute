# Compression Engines (Română)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

Compresia OmniRoute este construită în jurul contractelor de motor. Un mod poate rula direct un motor (`caveman` sau `rtk`) sau o conductă stivuită deterministă care execută mai multe motoare în ordine.

## Moduri

| Modul        | Calea motorului                                                                         | Intrare intenționată                             |
| ------------ | --------------------------------------------------------------------------------------- | ------------------------------------------------ |
| `off`        | nici unul                                                                               | Conservare exactă promptă                        |
| `lite`       | Caveman Lite helpers                                                                    | Curățare permanentă cu risc scăzut               |
| `standard`   | Omul cavernelor                                                                         | Condens rapid în limbaj natural                  |
| `aggressive` | Rezumate caveman + history/tool                                                         | Sesiuni lungi de chat                            |
| `ultra`      | Caveman + ajutoare de tăiere                                                            | Recuperare limită de context                     |
| `rtk`        | RTK                                                                                     | Terminal, shell, build, test și ieșire git       |
| `omniglyph`  | OmniGlyph                                                                               | Context-ca imagine pe firul furnizorului nativ   |
| `stacked`    | Conductă. Cererea implicită este `session-dedup -> lite`. `rtk -> caveman` este opt-in. | Bușteni de scule mixte și proză, economii maxime |

### profile de compresie OmniGlyph

Motorul `omniglyph` (pachetul `omniglyph`, 1.4.0 +) acceptă un profil semantic numit, setat global prin `omniglyph.profile` în setările de compresie sau pe pas prin configurația pasului conductei stivuite:

| Profil        | Hotar                                                                                                                  |
| ------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Implicit. Politica chitanțelor publicate a măsurat sistemul de imagini —, documentele instrumentului și istoricul dens |
| `balanced`    | Păstrează starea de viață nativă, protejează ultimele 8 viraje, prăbușește istoricul închis mai vechi                  |
| `coding-safe` | Păstrează autoritatea, schemele de instrumente și ieșirea instrumentelor live native, protejează ultimele 12 ture      |
| `passthrough` | Trasee fără transformare; motorul este sarit                                                                           |

Profilul este a** tavan, nu podea** : `mergeCompressionProfileOptions` din pachet refuză să permită apelantului să anuleze redeschiderea unei benzi cu pierderi profil închis, astfel încât un `preserveSystemPrompt: false` la pas nu poate reactiva compresia sistemului sub `coding-safe`.

Măsurat pe această bază de cod: `coding-safe` și `balanced` ridică `minCompressChars` la maximum și păstrează sistemul, schemele de instrumente și rezultatele instrumentelor native, deci o sesiune care nu a acumulat încă istoric se oprește la `below_min_chars` și motorul nu transformă nimic. De aceea, implicit este mai degrabă `aggressive` decât cel mai sigur profil.

Pachetul își rezolvă propriul domeniu de aplicare și profil din configurația mediului. OmniRoute nu deleagă niciodată decizia: adaptorul fixează poarta modelului la cel mai restrictiv domeniu de aplicare al pachetului, astfel încât setările mediului gazdă nu pot decât să restrângă lista de permise, să nu o extindă niciodată dincolo de chitanțele măsurate ale OmniRoute.

## Registrul motorului

Registrul locuiește în `open-sse/services/compression/engines/registry.ts`. Motoarele expun un contract comun:

- `id`: id-ul motor stabil, cum ar `caveman` sau `rtk`
- `apply(text, config)`: calea de execuție moștenită utilizată de conductele stivuite
- `compress(input, config)`: calea de execuție primară care returnează text + stats
- `getConfigSchema()`: returnează forma JSON-Schema-like a configurației valide
- `validateConfig(config)`: returnează `{ valid, errors[] }`

Înregistrarea folosește `registerCompressionEngine(engine)` (sau `registerEngine` pentru cazuri avansate), care apelează `assertValidEngine()` și `validateConfig(defaultConfig)` înainte de a accepta. Utilizați `unregisterCompressionEngine(id)` pentru a elimina un motor în timpul rulării.

`strategySelector.ts` înregistrează motoarele încorporate înainte de rularea compresiei. Acest lucru permite previzualizării, compresiei de rulare, modul stivuit, testele și motoarele viitoare să utilizeze aceeași cale de execuție.

### MCP descriere compresie (relativ)

Un registru separat comprimă metadatele descrierii instrumentului MCP la nivel de registru — vezi `open-sse/mcp-server/descriptionCompressor.ts` și [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Refolosește regulile Caveman, dar operează pe metadatele instrumentului, nu solicită încărcături utile.

### Motoare suplimentare incorporate

Dincolo de Caveman, RTK și LLMLingua-2, registrul oferă mai multe motoare specializate fără pierderi / structurale (utilizate de conducte stivuite, locul de joacă și teste):

| Motor             | Id              | Ce face                                                                                                                                                                                           |
| ----------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR               | `ccr`           | Content-Compress-Retrieve (H4): înlocuiește blocurile mari de text învecinate cu referințe adresate conținutului, astfel încât blocurile repeated/large sunt trimise o dată și referite ulterior. |
| spațiu pentru cap | `headroom`      | SmartCrusher (H3 + N5): compactare tabelară fără pierderi a sarcinilor utile JSON omogene într-o formă `[N rows]` coloană.                                                                        |
| ionizator         | `ionizer`       | eșantionarea rândurilor Head/middle/tail pentru blocuri omogene foarte mari, stocând mijlocul elidizat ca referință adresată conținutului CCR.                                                    |
| sesiune-dedus     | `session-dedup` | Deduplicarea încrucișată încrucișată de conținut (inspirată de TokenMizer): elidează textul deja văzut în rândurile anterioare ale aceleiași sesiuni.                                             |

**Instrucțiunea de preluare a protocolului CCR (#8033):** prima dată când CCR înlocuiește blocul ≥ 1 într-o solicitare, motorul adaugă un singur mesaj `system` idempotent (conducând cu sentinelul `[CCR protocol]` ) învățând apelantul marcatorul instrumentul → contract: ce înseamnă un marker `[CCR retrieve hash=<24hex> chars=N]`, că hash-ul trebuie copiat literal (toate cele 24 de caractere — nu sunt cauzate probabil de erori de blocare). găsit" ratează), și că un marker `[dedup:ref sha=...]` înseamnă "priviți înapoi în istorie", nu "sunați instrumentul". Nota este injectată** numai atunci când `tools[]` anunțat de apelant demonstrează că poate ajunge efectiv `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` în `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — un apelant simplu compatibil OpenAI fără acel instrument nu primește niciodată o instrucțiune să apeleze ceva la care nu poate ajunge. Idempotenta este impusă prin scanarea istoricului mesajelor pentru santinelă înainte de injectare, astfel încât cererile cu mai multe ture (care reda mesajele anterioare) nu stivuiesc nota o dată pe tură.

## Omul cavernelor

Modul Caveman se concentrează pe condensarea semantică a prozei normale:

- păstrează blocurile de cod, URLs, JSON, căile și datele structurate
- elimină umplerea, acoperirea, contextul repetat și frazele conjunctive verbose
- acceptă pachete de reguli de fișiere care știe limba în `open-sse/services/compression/rules/`
- rămâne disponibil prin modurile vechi `standard`, `aggressive` și `ultra`

Suprafața tabloului de bord este `Dashboard -> Context & Cache -> Caveman`.

Caveman în amonte raportează `~75%` mai puține jetoane de ieșire, `65%` economii medii de ieșire în benchmark-uri cu un interval `22-87%` și un instrument de compresie de intrare `~46%`. OmniRoute folosește numărul din partea de intrare a Caveman atunci când documentează economiile prompt/context stivuite; Modul de ieșire Caveman rămâne o caracteristică separată de răspuns-comportament.

## RTK

Modul RTK se concentrează pe comandă și instrumente:

- detectează clase de ieșire, cum ar fi `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go tests, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logs, shell `find`/`grep`, stiva urme și jurnalele generice
- aplică 49 de filtre JSON de `open-sse/services/compression/engines/rtk/filters/`
- acceptă conducta declarativă în stil RTK: ANSI stripping, replace, match-output short-circuit, linii strip/keep, trunchiere pe linie, trunchiere head/tail/max-line și fallback on-empty
- acceptă filtre de proiect bazate pe încredere în `.rtk/filters.json` și filtre globale în `DATA_DIR/rtk/filters.json`
- secvențe ANSI, zgomot de progres, linii repetate și boilerplate inutil
- păstrează eșecurile acționabile, avertismentele, rezumatele, fișierele modificate și contextul final
- poate reține opțional rezultatul brut redactat pentru recovery/debugging prin rute de gestionare autentificate

Suprafața tabloului de bord este `Dashboard -> Context & Cache -> RTK`.

Detalii operaționale pentru filtre personalizate, încredere, verificare și recuperarea rezultatelor brute live în [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK în amonte raportează economii `60-90%` pentru compresia comandă-ieșire. Exemplul său README arată o sesiune de cod Claude de 30 de minute care trece de la jetoane `~118,000` la `~23,900` sau `79.7%` salvat.

## LLMLingua-2 (Tăiere semantică)

modul LLMLingua-2 funcționează** tăierea cu simbol semantic** pe proză folosind un mic clasificator de jetoane ONNX, completând motoarele Caveman și RTK bazate pe reguli:

- comprimă proza numai în mesaje non-sistem; blocurile de cod îngrădite și alte construcții păstrate nu sunt niciodată modificate
- rulează backend-ul `@atjsh/llmlingua-2` (ONNX prin `@huggingface/transformers`) într-un fir de lucru, astfel încât inferența modelului nu blochează niciodată bucla de eveniment de solicitare
- este** stivuibile** (`stackPriority` 35): într-o conductă stivuită, rulează după motoarele structurale (CCR, session-dedup, headroom, Caveman ) dar înainte de `ultra`, deoarece tăierea semantică este cea mai eficientă pe textul deja comprimat structural — de exemplu `rtk -> caveman -> llmlingua`
- **fail-deschide la orice eroare** (lipsesc dep-uri opționale, generarea lucrătorului, încărcarea modelului, inferența sau expirarea timpului) → textul original este returnat neschimbat, niciodată o eroare

Locația motorului: `open-sse/services/compression/engines/llmlingua/`. Suprafața tabloului de bord este `Dashboard -> Context & Cache -> LLMLingua`.

### Modele

Modelul implicit este**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, rapid). O precizie mai mare** BERT-bază** modelul (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) este disponibil prin câmpul `model` config motor. `@huggingface/transformers` descarcă leneș modelul selectat din HuggingFace Hub în `${DATA_DIR}/models/llmlingua` la primul apel (`modelStore.ts`); o modificare a configurației `modelPath` îl indică în schimb către o copie locală (instalări offline / cu aer întrerupt).

### Dependențe opționale și instalare la cerere

Stiva de peer time LLMLingua care poate fi tăiată este** opțional** . Două pachete sunt declarate ca `optionalDependencies` în `package.json` și păstrate** extern** prin construcția de producție (`scripts/build/prepublish.ts` nu le grupează):

| Pachet               | Versiune (pin) | Note                                                  |
| -------------------- | -------------- | ----------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`        | Pachetul de intrare; îi declară pe ceilalţi ca semeni |
| `js-tiktoken`        | `^1.0.20`      | Tokenizer                                             |

`@huggingface/transformers` este fixat la `^4.2.0` (partajat cu calea de încorporare locală și, de asemenea, urmărit în pachetul independent); `@atjsh/llmlingua-2@2.0.5` se conectează cu `"^3.5.2 || ^4.0.0"`, deci sunt acceptate atât Transformers.js v3, cât și v4. Din 2.0.4, `@atjsh/llmlingua-2` nu mai necesită `@tensorflow/tfjs`, care a eliminat cel mai mare contributor unic (TensorFlow.js) din stiva SLM. Doar cele două pachete de mai sus sunt egali SLM care pot fi tăiate. Un `npm install` standard (dev) instalează automat stiva opțională, cu excepția cazului în care dependențele opționale sunt omise.

**De ce la cerere:** pachetul publicat de npm, pachetul independent și imaginea Docker** fără** aceste deps să rămână subțiri. Când acestea lipsesc, poarta de dependență a lucrătorului (o sondă de rezolvare `@atjsh/llmlingua-2` în `worker.ts`) eșuează și motorul** fail-se deschide în tăcere** — selectând LLMLingua devine un no-op (textul returnat neschimbat, nicio eroare înregistrată). Pentru a-l activa într-un mediu tăiat, instalați stiva opțională:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Eliminarea `@tensorflow/tfjs` (2.0.4 +) elimină contributorul ~ 800 MB dominant anterior — amprenta rămasă este timpii de rulare transformers.js + onnxruntime-node, plus modelul TinyBERT (~ 57 MB) descărcat la prima utilizare (nu t).

Pe mediu:

- **Dev / `npm install`** — instalat automat, cu excepția cazului în care ați trecut `--omit=optional` (sau `--no-optional`). Nu este necesară nicio acțiune.
- **Npm global (`npm i -g omniroute`) / independent** — rulează comanda de instalare de mai sus în directorul pachetului instalat sau reinstalează fără a omite dep-urile opționale.
- **Docker** — adaugă comanda de instalare într-un strat de imagine derivat; imaginea publicată este subțire prin design.
- **VPS (PM2)** — se instalează în `node_modules` al aplicației, apoi repornește procesul, astfel încât lucrătorul să re-sonda poarta.
- **Raw Next standalone (`npm run build` → `.build/next/standalone/server.js`)** — navele de urmărire de sine stătătoare NEITHER lucrătorul și nici dep-urile opționale, astfel încât motorul se defectează în tăcere. `scripts/build/colocate-standalone.mjs` le reaplică pe ambele (worker esbuild + optional-dep closure în arborele autonom); rulează automat prin intermediul cârligului `postbuild` npm după fiecare build. Idempotent, eșuează-moale când dep-urile sunt absente.

**Verificați că este activ:** cu LLMLingua selectat, proza reală se micșorează de fapt (motorul oprește deschiderea eșuată), iar prima solicitare declanșează descărcarea modelului în `${DATA_DIR}/models/llmlingua`. Poarta sondează în mod intenționat doar `@atjsh/llmlingua-2` — ceilalți colegi sunt doar ESM și `require.resolve` aruncă asupra lor chiar și atunci când este prezent — astfel încât lucrătorul încă nu se deschide dacă vreun peer lipsește cu adevărat la momentul `import()`.

## Conducte stivuite

Modul stivuit rulează pașii conductei în ordine. Valoarea implicită este:

```txt
rtk -> caveman
```

Utilizați acest lucru pentru sesiunile de agent de codare în care un prompt combină ieșirea comenzii cu proza umană sau de asistent. RTK reduce mai întâi jurnalele de instrumente zgomotoase, apoi Caveman comprimă limbajul natural rămas.

Pașii pipeline sunt configurați cu `stackedPipeline` în setările de compresie sau prin combo-uri de compresie.

Atunci când ambele motoare reduc aceeași sarcină utilă eligibilă, economiile sunt compuse:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Filtru arbore de accesibilitate

Filtrul inteligent din arborele de accesibilitate MCP este un strat de compresie post-execuție care rulează pe MCP** rezultatele instrumentului** , nu pe solicitări sau context. Acesta vizează arborele de accesibilitate și sarcinile utile de instantanee ale browserului returnate de instrumente precum Playwright, utilizarea computerului și serverele MCP de automatizare a browserului.

### Ce face

1. **Eliminarea zgomotului** — elimină intrările generic/text goale (`- generic:`, `- text: ""`)
2. **Colapsul fraților** — când ≥ `collapseThreshold` (implicit 30) linii consecutive sunt repetări structurale, le restrânge în primele `collapseKeepHead` (implicit 10) linii + un rezumat al numărului + ultimele `collapseKeepTail` (implicit 5) linii
3. **Conservarea ref** Ancorele — `[ref=eXX]` cerute de Playwright/computer-use nu sunt niciodată atinse
4. **Trunchiere dură** — dacă textul după colaps depășește în continuare `maxTextChars` (implicit 50.000), trunchiază cu un indiciu de navigare, astfel încât agentul să poată continua să lucreze

### Locația motorului

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Configurare

Controlat de `compression.mcpAccessibility` în setările globale (migrarea 056). Configurație implicită:

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

Filtrul este aplicat numai sarcinilor utile rezultate de instrumente a căror `type` este `"text"` și a căror lungime depășește `minLengthToProcess`. Nu afectează comprimarea promptă sau sarcinile utile de solicitare.

### Economii așteptate

60–80% din rezultatele instrumentului de instantanee ale browserului, în funcție de complexitatea paginii. Algoritmul de colaps este O(n) în număr de linii și adaugă o latență neglijabilă.

### Acest filtru față de motoarele de compresie de mai sus

| Aspect               | Caveman / RTK / Stacked         | filtrul de accesibilitate MCP          |
| -------------------- | ------------------------------- | -------------------------------------- |
| Ţintă                | Solicitare solicitări / context | rezultatele instrumentului MCP         |
| Trigger              | Setarea modului de compresie    | `compression.mcpAccessibility.enabled` |
| Domeniul de aplicare | Toate mesajele SSE              | Numai rezultatele instrumentului       |
| Ref ancore           | N/A                             | Păstrată necondiționat                 |

---

## Combo de compresie

Combinările de compresie sunt denumite profiluri de compresie care pot fi atribuite combinărilor de rutare:

- `compression_combos`: stochează modul, pipeline, configurația RTK, configurația limbii și marcatorul implicit
- `compression_combo_assignments`: mapează un combo de compresie cu un combo de rutare
- integrarea în timp de execuție rezolvă un combo de compresie atribuit înainte de înlocuirea combo-ului generic
- analizele includ `compression_combo_id` și `engine`

Suprafața tabloului de bord: `Dashboard -> Context & Cache -> Compression Combos`.

## Cerințe preliminare / ghid operator (CCR și session-dedup)

CCR (`ccr`) și `session-dedup` înlocuiesc sau elid textul și lasă a** marker** din spatele. Această secțiune este referința operatorului pentru conectarea unui client, citirea celor doi markeri și preluarea sau diagnosticarea conținutului elidizat. Mecanica fiecărui motor este tratată mai sus; acesta este stratul „cum îl rulez”.

### Transporturi și puncte finale

Serverul MCP care expune instrumentele CCR poate fi accesat în trei moduri. Baza implicită URL este `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transport                                                | URL / comanda                           | Note                                                                                                                                                                     |
| -------------------------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| HTTP care poate fi transmis în flux (client, recomandat) | `http://localhost:20128/api/mcp/stream` | Punctul final cu care vorbesc clienții actuali MCP.                                                                                                                      |
| Legacy SSE singleton                                     | `http://localhost:20128/api/mcp/sse`    | Transport singleton mai vechi. Ea** se inchide** sesiuni care pot fi transmise în flux; utilizați clienții `streamable-http` împotriva `/api/mcp/stream`, nu a acestuia. |
| stdio                                                    | `omniroute --mcp`                       | Pentru IDE MCP config care generează procesul. Nu există niciun steag `--dev` ; `omniroute --mcp` este punctul de intrare stdio.                                         |

### Niveluri de stocare (ceea ce supraviețuiește unei reporniri)

CCR este a** pe două niveluri** magazin, nu numai în memorie:

- **Nivel fierbinte în memorie** — per-block cap 2 MiB, per-principal 16 MiB, global 64 MiB. Intrările sunt implicite la 24 h TTL (maximum 7 zile). Preluarea completă MCP din memorie este limitată la 256 KiB; orice mai mare este încă accesibil prin modurile ranged / grep.
- **Nivel SQLite durabil** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, activat în mod implicit) — susține nivelul în memorie, astfel încât un bloc să supraviețuiască evacuarii LRU, unei reporniri sau unei aterizări de recuperare pe o altă instanță. Rândul păstrează TTL ul blocului, astfel încât un bloc dincolo de TTL său dispare de la ambele niveluri.

Trei apărătoare păstrează nivelul durabil delimitat — un bloc rămâne doar pentru memorie atunci când:

1. blocul s-a terminat** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. timpul de rulare este un timp de rulare în cloud (fără disc local);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Deci „blocul a dispărut” nu este o poveste de repornire generală: un bloc sub-512 KB pe un timp de execuție local, non-cloud supraviețuiește unei reporniri prin nivelul durabil până când TTL său se epuizează. Consultați [Referința mediului](../reference/ENVIRONMENT.md) pentru variabilă.

### Cele două marcaje

| Marker                                | Sens                                                                                                                                                             | Ce ar trebui să facă modelul                                                                                                                                                                                 |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `[CCR retrieve hash=<24hex> chars=N]` | Un bloc mare a fost stocat la adresa de conținut.                                                                                                                | Sună `omniroute_ccr_retrieve` cu** 24-hex hash copiat text** pentru a recupera textul original.                                                                                                              |
| `[dedup:ref sha=…]`                   | Textul `session-dedup` elid deja trimis într-o tură anterioară a aceleiași sesiuni. Acesta este un** privire înapoi intenționată** , nu o pierdere sau o eroare. | Do** nu** apelați orice unealtă și faceți** nu** încercați să o „reconstituiți”. Prima apariție a textului este copia canonică; tura curentă nu este niciodată rescrisă, este dedusă într-o tură ulterioară. |

Analiza `[dedup:ref]` în urmă este o decizie deliberată a protocolului — nu există nicio reconstrucție pre-trimitere. Tratați-l ca „acest text exact a fost deja pe fir mai devreme în această sesiune”.

### Cerințe preliminare ale clientului

- **Cheie (stdio):** un apelant stdio nu poartă nicio identitate pe cerere, așa că se autentifică cu `OMNIROUTE_API_KEY` (setat în `env` al serverului MCP ). Fără el, apelantul este anonim, iar instrumentele care necesită un principal se pot degrada.
- **`tools[]` este condiția prealabilă a injecției.** Instrucțiunea CCR retrieve-protocol (#8033) este injectată** numai** când `tools[]` anunțat al cererii demonstrează că clientul poate ajunge efectiv `omniroute_ccr_retrieve`. Potrivirea este o potrivire de segment final delimitată de un separator (`__`, `.`, `/`, `:`) — niciodată un subșir simplu — așa că un nume cu spațiu de nume, cum ar fi `mcp__gateway__omniroute_ccr_retrieve` contează în continuare. Un `tools[]` absent sau care nu se potrivește înseamnă că instrucțiunea este _nu_ injectată, prin proiectare.
- **`codemode:false` (clienți OpenCode ).** OpenCode este implicit la Modul Cod, care face publicitate doar instrumentelor sale native pentru model și** nu** puneți instrumentele MCP pe lista nativă `tools[]`. Setați `codemode: false` pe intrarea serverului MCP, astfel încât instrumentele `omniroute_ccr_*` să fie promovate. Acesta este un** client** setare, nu una OmniRoute. Încă nu primește instrucțiunea CCR injectată: OpenCode denumește un instrument `<server>_<tool>`, astfel încât un server numit `omniroute` expune `omniroute_omniroute_ccr_retrieve`, iar `_` nu este unul dintre separatorii potriviți.
- **Directori.** Stocarea și preluarea sunt izolate pe principal autentificat (pe cheie API ). O cheie își vede numai propriile blocuri.

### Scopuri per instrument

Aplicarea domeniului de aplicare este întotdeauna activată pentru apelanții HTTP/SSE cu domeniu îngust. Instrumentele `omniroute_` CCR necesită:

| Instrument               | Domeniul de aplicare |
| ------------------------ | -------------------- |
| `omniroute_ccr_store`    | `write:compression`  |
| `omniroute_ccr_delete`   | `write:compression`  |
| `omniroute_ccr_retrieve` | `read:compression`   |
| `omniroute_ccr_inspect`  | `read:compression`   |
| `omniroute_ccr_list`     | `read:compression`   |
| `omniroute_ccr_stats`    | `read:compression`   |

Un domeniu lipsă returnează un** rezultatul erorii instrumentului MCP** (`isError: true`, nu un HTTP 403 — `403 LOCAL_ONLY` este autentificarea separată de gardă a rutei de loopback): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` O cheie minimă de la distanță poate deține `mcp:connect` (autorizează `/api/mcp/` -out doar local) plus domeniul de aplicare read/write specific de care are nevoie.

### Matricea clientului

| Client               | Transport                                      | Configurație de utilizat                                                                                                                                                                                                                                           | `tools[]` reclamă? (instrucțiunea → CCR injectată)                                                                                                                                                                                |
| -------------------- | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Codul Claude         | streamable-http                                | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                                  | Da — compatibil MCP; injectat.                                                                                                                                                                                                    |
| Cursor / Cline       | `stdio`** sau** `streamable-http`              | stdio: `omniroute --mcp` cu `OMNIROUTE_API_KEY` în `env`; sau o intrare MCP de la distanță care indică `http://localhost:20128/api/mcp/stream` (consultați [Ghidul de configurare → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Da — publicitate instrumentelor `omniroute_ccr_*`.                                                                                                                                                                                |
| OpenCode             | streamable-http                                | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plus `codemode: false`                                                                                                                                                                   | Instrumente promovate numai cu `codemode: false`; instrucțiunea nu este încă injectată, deoarece `omniroute_omniroute_ccr_retrieve` nu se potrivește (consultați [Cerințele preliminare ale clientului](#client-prerequisites) ). |
| Compatibil cu OpenAI | HTTP compatibil cu OpenAI (finalizări de chat) | client standard de finalizare a chat-ului față de punctul final compatibil OpenAI                                                                                                                                                                                  | **Nu** — unui apelant simplu compatibil cu OpenAI nu i se spune niciodată să sune instrumentul, iar instrucțiunea nu este injectată.                                                                                              |

### Limite de recuperare și paginare

Rezultatele textului instrumentului MCP sunt tăiate în jurul `mcpAccessibility.maxTextChars` ( `50000` implicit). O recuperare `full` a unui bloc este limitată la 256 KiB —** nu există o recuperare completă nelimitată** . Când `chars=N` unui bloc este mare, paginați-l în loc să trageți totul:

- Regula generală:**`chars > 40000` → folosește un `mode`** , niciodată un plin gol.
- `mode:"grep"` — regex `pattern` potriviți linie cu linie, până la 1.000 de linii de potrivire (`unique: true` drops repetă), cel mai ieftin pentru „găsiți singura linie de care am nevoie”.
- `mode:"lines"` — un interval de 1 linii indexate; are nevoie atât `start` cât și `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` linii.
- `mode:"stats"` — numărul de linii, caractere și octeți fără corp.

Utilizați `mode:"lines"` cu `start`/`end` pentru a parcurge un bloc lung în pagini, mai degrabă decât să solicitați întregul odată.

### Denumirea instrumentului

Instrumentul de recuperare se numește în prezent `omniroute_ccr_retrieve` (prefixul `omniroute_` este o soluție datată pentru coliziunile de nume între servere). Un nume de instrument cu sufix delimitat mai curat și o remediere pentru rezultatele MCP JSON trunchiate la mijlocul șirului sunt urmărite ca urmăriri în amonte; această pagină documentează numai comportamentul curent, expediat.

### Ciclul de viață al sesiunii

Sesiunile HTTP care pot fi transmise în flux sunt inactiv și serverul le recunoaște; fereastra inactivă este constanta `MCP_SESSION_IDLE_MS` (referită prin nume, nu o valoare codificată, deci această pagină nu se deplasează atunci când se schimbă). Simptomul unei sesiuni inactiv este un HTTP 404 cu `Unknown Mcp-Session-Id` — remediul este reconectarea sau repornirea sesiunii,** nu** pentru a roti o cheie, a schimba un domeniu sau a redenumi un instrument.

## API Suprafață

| Traseu                                 | Scop                                                                   |
| -------------------------------------- | ---------------------------------------------------------------------- |
| `/api/settings/compression`            | Setări globale de compresie (include configurația `mcpAccessibility` ) |
| `/api/compression/preview`             | Previzualizează orice mod de compresie                                 |
| `/api/compression/language-packs`      | Listați pachetele de limbi disponibile Caveman                         |
| `/api/context/caveman/config`          | Alias pentru setările Caveman                                          |
| `/api/context/rtk/config`              | RTK implicite și setări                                                |
| `/api/context/rtk/filters`             | catalog de filtre RTK                                                  |
| `/api/context/rtk/test`                | RTK preview/test punct final                                           |
| `/api/context/rtk/raw-output/[id]`     | Recuperare autentificată a ieșirii brute redactate                     |
| `/api/context/combos`                  | Combo de compresie CRUD                                                |
| `/api/context/combos/[id]/assignments` | Atribuire combo de rutare CRUD                                         |
| `/api/context/analytics`               | Alias de analiză a compresiei                                          |

Rutele de gestionare necesită autentificare de management sau verificări ale politicii cheii API.

## MCP Tools

Compresia expune cinci instrumente MCP :

| Instrument                          | Domeniul de aplicare | Scop                               |
| ----------------------------------- | -------------------- | ---------------------------------- |
| `omniroute_compression_status`      | `read:compression`   | Setări, analize, statistici cache  |
| `omniroute_compression_configure`   | `write:compression`  | Actualizați setările globale       |
| `omniroute_set_compression_engine`  | `write:compression`  | Setați modul și conducta opțională |
| `omniroute_list_compression_combos` | `read:compression`   | Lista combo de compresie           |
| `omniroute_compression_combo_stats` | `read:compression`   | Citiți analitice combo/engine      |

## Domeniu de aplicare și excluderi

**Înglobările nu sunt niciodată comprimate.** `open-sse/handlers/embeddings.ts` nu apelează niciodată niciun motor de compresie — corpurile request/response trec direct executorului neatinse. Acest lucru este structural astăzi (înglobările și completările de chat sunt manipulatori disjunși), nu o verificare în timpul execuției, dar înseamnă că problema de distorsiune vectorială în #8034 nu are suprafață de expunere în calea înglobărilor.

**filtrul de excludere Per-model/endpoint (#8034).** Pentru finalizarea chat-ului, un operator poate denumi ID-uri de model / ținte `provider/model` care nu trebuie să fie niciodată comprimate — o balustradă utilă dacă compresia este vreodată conectată mai aproape de o cale adiacentă înglobărilor și, în general, utilă pentru orice model al cărui prompt octet pentru octet contează (evaluări deterministe, prefixe sensibile la cache etc.).

- Câmp de setări: `exclusions?: string[]` în configurația globală de compresie (`GET`/`PUT /api/settings/compression`), a persistat prin spațiul de nume de compresie `key_value` existent (`src/lib/db/compression.ts`) — nici un tabel nou.
- Fila tablou de bord:** Tabloul de bord → Compresie → Excluderi** (`/dashboard/compression/exclusions`).
- Sintaxa modelului: `*` este singurul wildcard. Fiecare alt metacaracter regex dintr-un model este eliminat înainte de potrivire, astfel încât `gpt-5.6` se potrivește numai cu șirul literal, niciodată `gpt-5x6` (sigur pentru ReDoS, mărginit, fără cuantificatori imbricați). Modelele se potrivesc fără a ține seama de majuscule și minuscule atât cu id-ul modelului complet, cât și cu `provider/model` compozit — `gpt-5-6`, `openai/gpt-5-6` și `openai/*`, iar `*` singur exclude fiecare model.
- Potrivire: `isCompressionExcluded()` / `normalizeCompressionExclusions()` în `open-sse/services/compression/exclusions.ts`. `chatCore.ts` verifică ținta exclusă imediat după rezolvarea setărilor de compresie,** înainte ca orice motor să pornească** , și tratează o potrivire exact ca compresia fiind dezactivată la nivel global — corpul cererii este probabil identic pentru octeți. Omiterea este înregistrată prin `writeCompressionSkip(..., "excluded")` pentru vizibilitate analitică.
- Implicit ( lista empty/absent ): identic cu comportamentul pre-#8034 — nimic nu este exclus.

## Limitări cunoscute

- **LLMLingua-2 (SLM) necesită dep-uri opționale colocate.** Lucrătorul rulează într-o versiune de producție numai atunci când `@atjsh/llmlingua-2` + peers sunt colocați în `dist/node_modules` (a se vedea `scripts/build/colocateOptionals.mjs`, #4286). Fără ele, motorul se deschide (returnează textul original). Rezoluția lucrătorului nu mai depinde de `import.meta.url` (moare în pachetul autonom) — se ancorează pe runtime cwd / `argv[1]`.
- **Pachetele lingvistice Caveman `de` / `fr` / `ja` sunt parțiale.** Ei expediază reguli `context` + `filler` + `structural`, dar nu pachete `dedup` / `ultra`, deci intensitatea `ultra` nu este mai puternică decât `full` pentru acele limbi (ei folosesc doar propriile reguli — nu există nicio retragere silențioasă la regulile engleze `dedup`/`ultra`, care ar distruge textul străin). `en` / `es` / `id` / `pt-BR` sunt complete. Contribuțiile `dedup.json` + `ultra.json` pentru pachetele parțiale sunt binevenite.
- **Telemetria stivuită listează doar motoarele care s-au comprimat.** O etapă de conductă stivuită al cărei motor a funcționat, dar a produs economii de 0 %, returnează `stats:null` și, prin urmare, nu apare în `engineBreakdown` — care nu se poate distinge de un pas care a fost omis. Distingerea „a alergat, 0 %” de „sărit” ar necesita o modificare a modelului de defalcare și este amânată.

## Validare

Porțile focalizate pentru această zonă sunt:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
