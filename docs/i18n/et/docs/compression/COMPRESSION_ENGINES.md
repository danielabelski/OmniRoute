# Compression Engines (Eesti)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompressioon on üles ehitatud mootorilepingutele. Režiim võib käitada otse ühte mootorit (`caveman` või `rtk`) või deterministlikku virnastatud konveieri, mis käivitab järjekorras mitu mootorit.

## Režiimid

| Režiim       | Mootori teekond                                                                        | Mõeldud sisend                                         |
| ------------ | -------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| `off`        | mitte ühtegi                                                                           | Täpne kiire säilitamine                                |
| `lite`       | Caveman lite abilised                                                                  | Madala riskitasemega alati puhastus                    |
| `standard`   | Koopamees                                                                              | Loomulikkeelne kiire kondensatsioon                    |
| `aggressive` | Caveman + history/tool kokkuvõtted                                                     | Pikad vestlusseansid                                   |
| `ultra`      | Caveman + pügamisabilised                                                              | Kontekstipiirangu taastamine                           |
| `rtk`        | RTK                                                                                    | Terminal, kest, ehitamine, testimine ja git väljund    |
| `omniglyph`  | OmniGlyph                                                                              | Kontekst pildina kohaliku teenusepakkuja juhtmes       |
| `stacked`    | Torujuhe. Taotluse vaikeseade on `session-dedup -> lite`. `rtk -> caveman` on lubatud. | Segatööriistade logid ja proosa, maksimaalne kokkuhoid |

### OmniGlyph surveprofiilid

`omniglyph` mootor (pakett `omniglyph`, 1.4.0 +) aktsepteerib nimega semantilist profiili, mis on määratud globaalselt tihendusseadetes `omniglyph.profile` kaudu või etapi kaupa virnastatud konveieri sammukonfiguratsiooni kaudu:

| Profiil       | Piir                                                                                                            |
| ------------- | --------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Vaikimisi. Avaldatud kviitungite poliitika mõõdeti — piltide süsteemi, tööriistade dokumente ja tihedat ajalugu |
| `balanced`    | Hoiab reaalajas olekut loomulikuna, kaitseb viimased 8 pööret, variseb vanema suletud ajaloo                    |
| `coding-safe` | Hoiab autoriteedi, tööriistaskeemide ja reaalajas tööriistaväljundi loomulikuna, kaitseb viimast 12 pööret      |
| `passthrough` | Marsruudid ilma ümberkujundamiseta; mootor jääb vahele                                                          |

Profiil on a** lagi, mitte põrand** : pakendis sisalduv `mergeCompressionProfileOptions` keeldub laskmast helistajal alistada kadudega rada uuesti avada, profiil on suletud, nii et sammupõhine `preserveSystemPrompt: false` ei saa `coding-safe` all süsteemi tihendamist uuesti lubada.

Sellel koodibaasil mõõdetuna: `coding-safe` ja `balanced` tõstavad `minCompressChars` maksimumini ja hoiavad süsteemi, tööriistaskeemid ja tööriista tulemused loomulikuna, nii et seanss, millel pole veel ajalugu kogutud, peatub `below_min_chars` juures ja mootor ei muuda midagi. Seetõttu on vaikimisi profiil `aggressive`, mitte kõige turvalisem profiil.

Pakett lahendab oma mudeli ulatuse ja profiili oma keskkonna konfiguratsioonist. OmniRoute ei delegeeri kunagi otsust: adapter kinnitab mudelivärava paketi kõige piiravama ulatusega, nii et hostikeskkonna sätted saavad ainult lubade loendit kitsendada, mitte kunagi laiendada seda OmniRoute mõõdetud laekumistest kaugemale.

## Mootori register

Register asub `open-sse/services/compression/engines/registry.ts`. Mootorid paljastavad jagatud lepingu:

- `id`: stabiilne mootori ID, näiteks `caveman` või `rtk`
- `apply(text, config)`: virnastatud torujuhtmete kasutatav pärandkäitetee
- `compress(input, config)`: esmane täitmistee, mis tagastab teksti + statistika
- `getConfigSchema()`: tagastab kehtiva konfiguratsiooni JSON-skeemitaolise kuju
- `validateConfig(config)`: tagastab `{ valid, errors[] }`

Registreerimisel kasutatakse `registerCompressionEngine(engine)` (või täpsemate juhtumite puhul `registerEngine` ), mis kutsub enne nõustumist välja `assertValidEngine()` ja `validateConfig(defaultConfig)`. Mootori tööajal eemaldamiseks kasutage `unregisterCompressionEngine(id)`.

`strategySelector.ts` registreerib sisseehitatud mootorid enne kompressiooni käivitamist. See võimaldab eelvaatel, käitusaja tihendamisel, virnastatud režiimil, testidel ja tulevastel mootoritel kasutada sama täitmisteed.

### MCP kirjelduse tihendamine (seotud)

Eraldi register tihendab MCP tööriista kirjelduse metaandmeid registritasemel — vt `open-sse/mcp-server/descriptionCompressor.ts` ja [MCP-SERVER.md](../frameworks/MCP-SERVER.md). See kasutab Cavemani reegleid uuesti, kuid töötab tööriista metaandmetel, mitte ei taotle kasulikke koormusi.

### Täiendavad sisseehitatud mootorid

Lisaks Cavemanile, RTK ja LLMLingua-2 tarnib register mitmeid spetsiaalseid kadudeta / struktuurseid mootoreid (mida kasutavad virnastatud torujuhtmed, mänguväljak ja testid):

| Mootor        | Id              | Mida see teeb                                                                                                                                                            |
| ------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): asendab suured külgnevad tekstiplokid sisuaadressiga viidetega, nii et repeated/large plokid saadetakse üks kord ja seejärel viidatakse. |
| pearuum       | `headroom`      | SmartCrusher (H3 + N5): homogeensete JSON-massiivi kasulike koormuste kadudeta tabelitihendamine veergukujuliseks `[N rows]` vormiks.                                    |
| ionisaator    | `ionizer`       | Head/middle/tail rea proovivõtt väga suurte homogeensete plokkide jaoks, salvestades elideeritud keskosa CCR sisu adresseeritud viitena.                                 |
| session-dedup | `session-dedup` | Sisuadresseeritud pöördeülene deduplikatsioon (TokenMizerist inspireeritud): eemaldab sama seansi varasemates pööretes juba nähtud teksti.                               |

**CCR otsimisprotokolli juhis (#8033):** Kui CCR asendab esimest korda päringus ploki ≥ 1, lisab mootor ühe idempotentse `system` -teate (mis juhib `[CCR protocol]` valvurit), õpetades helistajale markerit → tööriista lepingut: mida tähendab `[CCR retrieve hash=<24hex> chars=N]` marker, et räsi tuleb sõna-sõnalt kopeerida (kõik 24 hexb-i põhjust ei leitud" jätab vahele) ja — `[dedup:ref sha=...]` marker tähendab "ajalukku tagasivaatamist", mitte "tööriista kutsumist". Märkus süstitakse** ainult siis, kui helistaja reklaamitud `tools[]` tõestab, et see võib tegelikult jõuda `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — tavaline OpenAI-ga ühilduv helistaja ilma selle tööriistata ei saa kunagi käsku helistada millelegi, mida ta kätte ei saa. Idempotentsust jõustatakse, kui enne süstimist skannitakse sõnumite ajalugu valvuri jaoks, nii et mitme pöörde päringud (mis taasesitavad varasemaid sõnumeid) ei virna märget üks kord pöörde kohta.

## Koopamees

Koopainimese režiim keskendub normaalse proosa semantilisele kondenseerumisele:

- säilitab koodiplokid, URLs, JSON, teed ja struktureeritud andmed
- eemaldab täiteaine, riskimaandamise, korduva konteksti ja paljusõnalise sidefraasi
- toetab keeleteadlikke failireeglite pakette `open-sse/services/compression/rules/`
- jääb kättesaadavaks pärandrežiimide `standard`, `aggressive` ja `ultra` kaudu

Armatuurlaua pind on `Dashboard -> Context & Cache -> Caveman`.

Caveman ülesvoolu teatab `~75%` vähem väljundmärke, `65%` keskmist väljundsäästu `22-87%` -vahemiku võrdlusalustes ja `~46%` sisendi tihendamise tööriista. OmniRoute kasutab virnastatud prompt/context säästude dokumenteerimisel Cavemani sisendi numbrit; Koopainimese väljundrežiim jääb eraldi reageerimiskäitumise funktsiooniks.

## RTK

RTK režiim keskendub käsu- ja tööriistaväljundile:

- tuvastab väljundklassid, nagu `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testid, TypeScript/Vite/Webpack järgud, ESLint, npm audit/installs, Docker logid, shell `find`/`grep`, virna jäljed ja üldised logid
- rakendab 49 JSON filtrit `open-sse/services/compression/engines/rtk/filters/` st
- toetab RTK-stiilis deklaratiivset konveieri: ANSI eemaldamine, asendamine, sobitamise väljundi lühis, strip/keep read, reapõhine kärpimine, head/tail/max-line kärpimine ja tühjaks jääv tagasiminek
- toetab usaldusvärseid projektifiltreid `.rtk/filters.json` ja globaalseid filtreid `DATA_DIR/rtk/filters.json` s
- eemaldab ANSI jadad, edenemismüra, korduvad read ja kasutu plaadi
- säilitab rakendatavad tõrked, hoiatused, kokkuvõtted, muudetud failid ja sabakonteksti
- võib valikuliselt säilitada redigeeritud töötlemata väljundi recovery/debugging jaoks autentitud haldusmarsruutide kaudu

Armatuurlaua pind on `Dashboard -> Context & Cache -> RTK`.

Kohandatud filtrite, usalduse, kontrollimise ja töötlemata väljundi taastamise tööandmed on saadaval [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream teatab `60-90%` säästudest käsu-väljundi tihendamiseks. Selle README näide näitab 30-minutilist Claude -koodi seanssi, mis kulgeb `~118,000` märkidelt `~23,900` või `79.7%` salvestatud.

## LLMLingua-2 (semantiline pügamine)

LLMLingua-2 režiim toimib** semantilise märgi pügamine** proosas, kasutades väikest ONNX märgiklassifikaatorit, mis täiendab reeglipõhiseid Cavemani ja RTK mootoreid:

- tihendab proosa ainult süsteemivälistes sõnumites; tarastatud koodiplokke ja muid säilinud konstruktsioone ei muudeta kunagi
- käivitab `@atjsh/llmlingua-2` taustaprogrammi (ONNX `@huggingface/transformers` kaudu ) töölõimes, nii et mudeli järeldus ei blokeeri kunagi päringu sündmuse tsüklit
- on** virnastatav** (`stackPriority` 35): virnastatud konveier töötab pärast struktuurimootoreid (CCR, session-dedup, headroom, Caveman), kuid enne `ultra`, kuna semantiline pügamine on kõige tõhusam juba struktuurselt tihendatud teksti puhul — nt `rtk -> caveman -> llmlingua`
- **tõrkeavaneb mis tahes vea korral** (puuduvad valikulised dep-id, töötaja kude, mudeli laadimine, järeldused või ajalõpp) → algtekst tagastatakse muutmata kujul, mitte kunagi viga

Mootori asukoht: `open-sse/services/compression/engines/llmlingua/`. Armatuurlaua pind on `Dashboard -> Context & Cache -> LLMLingua`.

### Mudelid

Vaikimisi mudel on**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, kiire). Suurem täpsus** BERT-baas** mudel (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) on saadaval mootori konfiguratsiooni `model` välja kaudu. `@huggingface/transformers` laadib valitud mudeli esimesel kõnel laisalt alla HuggingFace Hubist `${DATA_DIR}/models/llmlingua` -sse (`modelStore.ts`); `modelPath` konfiguratsiooni alistamine suunab selle hoopis kohalikule koopiale (võrguühenduseta / õhuvahega installid).

### Valikulised sõltuvused ja nõudmisel installimine

Kärbitav LLMLingua käitusaegne sarnaste rakenduste virn on** valikuline** . Kaks pakki deklareeritakse `optionalDependencies` - `package.json` ja neid hoitakse alles** välised** tootmisjärgu järgi (`scripts/build/prepublish.ts` ei koonda neid):

| pakett               | Versioon (pin) | Märkmed                                         |
| -------------------- | -------------- | ----------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`        | Sissepääsupakett; kuulutab teised eakaaslasteks |
| `js-tiktoken`        | `^1.0.20`      | Tokenisaator                                    |

`@huggingface/transformers` on kinnitatud `^4.2.0` -sse (jagatud kohaliku manustamisteega ja jälgitud ka eraldiseisvasse kogumisse); `@atjsh/llmlingua-2@2.0.5` sarnaneb sellel `"^3.5.2 || ^4.0.0"` ga, seega toetatakse nii Transformers.js v3 kui ka v4. Alates versioonist 2.0.4 ei nõua `@atjsh/llmlingua-2` enam `@tensorflow/tfjs`, mis eemaldas SLM pinust suurima üksiku kaastöölise (TensorFlow.js). Ainult kaks ülaltoodud paketti on kärbitavad SLM kaaslased. Tavaline `npm install` (dev) installib valikulise virna automaatselt, kui valikulisi sõltuvusi ei jäeta välja.

**Miks nõudmisel:** npm-i avaldatud pakett, eraldiseisev komplekt ja Docker pildisaadetis** ilma** need depid saledaks jääda. Kui nad puuduvad, siis töötaja sõltuvusvärav ( `@atjsh/llmlingua-2` lahenduse sond `worker.ts`) ebaõnnestub ja mootor** ebaõnnestub-avaneb vaikselt** — LLMLingua valimine muutub no-op (tekst tagastatakse muutmata kujul, viga ei logita). Selle aktiveerimiseks kärbitud keskkonnas installige valikuline virn:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` eemaldamine (2.0.4 +) kõrvaldab varem domineerinud ~ 800 MB kaasautori — järelejäänud jalajälg on transformers.js + onnxruntime-node käitusajad, pluss TinyBERT mudel (~ 57 MB), mis laaditi alla esmakordsel kasutamisel (mitte np kaudu).

Keskkonna kohta:

- **Arendaja / `npm install`** — installitakse automaatselt, välja arvatud juhul, kui olete läbinud `--omit=optional` (või `--no-optional`). Tegevust pole vaja.
- **Globaalne npm (`npm i -g omniroute`) / eraldiseisev** — käivitage installimiskäsk ülaltoodud installipaketi kataloogis või installige uuesti ilma valikulisi deps-i jätmata.
- **Docker** — lisab tuletatud pildikihile installikäskluse; avaldatud pilt on disainilt sale.
- **VPS (PM2)** — installige rakenduse `node_modules`, seejärel taaskäivitage protsess, et töötaja kontrolliks väravat uuesti.
- **Raw Next eraldiseisev (`npm run build` → `.build/next/standalone/server.js`)** — eraldiseisvad jälgimislaevad NEITHER töötaja ega valikulised deps, nii et mootor avaneb vaikselt rikke korral. `scripts/build/colocate-standalone.mjs` rakendab mõlemad uuesti (töötaja ehitab + valikulise sügavuse sulgemise eraldiseisvasse puusse); see töötab automaatselt pärast iga ehitamist `postbuild` npm konksu kaudu. Idempotentne, tõrkekindel, kui depsid puuduvad.

**Kontrollige, kas see on aktiivne:** kui LLMLingua on valitud, siis pärisproosa tegelikult kahaneb (mootor peatab tõrkeavamise) ja esimene päring käivitab mudeli allalaadimise `${DATA_DIR}/models/llmlingua`-sse. Värav uurib tahtlikult ainult `@atjsh/llmlingua-2` — teised partnerid on ainult ESM-iga ja `require.resolve` viskab neile peale isegi siis, kui — on olemas, nii et töötaja avab ikka tõrgeteta, kui mõni partner on `import()` ajal tõesti puudu.

## Virnastatud torujuhtmed

Virnastatud režiim käivitab konveieri etapid järjekorras. Vaikimisi on:

```txt
rtk -> caveman
```

Kasutage seda kodeerimisagendi seansside jaoks, kus viip ühendab käsuväljundi inimese või assistendi proosaga. RTK vähendab esmalt mürarikkaid tööriistalogisid, seejärel tihendab Caveman ülejäänud loomuliku keele.

Torujuhtme sammud konfigureeritakse tihendusseadetes või tihenduskombode kaudu `stackedPipeline`.

Kui mõlemad mootorid vähendavad sama kõlblikku kandevõimet, on kokkuhoid:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP juurdepääsetavuse puufilter

MCP juurdepääsetavuse puu nutikas filter on täitmisjärgne tihenduskiht, mis töötab MCP** tööriista tulemused** , mitte viipade või konteksti alusel. See sihib üksikasjalikku juurdepääsetavuse puud ja brauseri hetktõmmise kasulikku koormust, mille tagastavad sellised tööriistad nagu Playwright, arvutikasutus ja brauseri automatiseerimise MCP serverid.

### Mida see teeb

1. **Müra eemaldamine** — eemaldab tühjad generic/text kirjed (`- generic:`, `- text: ""`)
2. **Õdede-vendade kokkuvarisemine** — kui ≥ `collapseThreshold` (vaikimisi 30) järjestikused read on struktuursed kordused, ahendab need esimesteks `collapseKeepHead` (vaikimisi 10) ridadeks + loenduse kokkuvõte + viimased `collapseKeepTail` (vaikimisi 5) read
3. **Viite säilitamine** — `[ref=eXX]` ankruid, mida Playwright/computer-use nõuab, ei puudutata kunagi
4. **Kõva kärpimine** —, kui tekst pärast ahendamist ületab endiselt `maxTextChars` (vaikimisi 50 000), kärbitakse koos navigeerimisvihjega, et agent saaks tööd jätkata

### Mootori asukoht

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Seadistamine

Globaalsetes seadetes juhib `compression.mcpAccessibility` (migratsioon 056). Vaikekonfiguratsioon:

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

Filtrit rakendatakse ainult tööriista tulemusel kasulikele koormustele, mille `type` on `"text"` ja pikkus ületab `minLengthToProcess`. See ei mõjuta kiiret tihendamist ega taotle kasulikku koormust.

### Oodatud kokkuhoid

60–80% brauseri hetktõmmise tööriista tulemustest, olenevalt lehe keerukusest. Ahendamisalgoritm on ridade loenduses O(n) ja lisab tühise latentsuse.

### See filter vs ülaltoodud kompressioonmootorid

| Aspekt      | Koopamees / RTK / virnastatud  | MCP juurdepääsetavuse filter           |
| ----------- | ------------------------------ | -------------------------------------- |
| Sihtmärk    | Taotlege viipasid / kontekst   | MCP tööriista tulemused                |
| Päästik     | Kompressioonirežiimi seadistus | `compression.mcpAccessibility.enabled` |
| Ulatus      | Kõik SSE sõnumid               | Ainult tööriista tulemused             |
| Viiteankrud | N/A                            | Säilitatud tingimusteta                |

---

## Kompressioonikombinatsioonid

Tihenduskombod nimetatakse tihendusprofiilideks, mida saab määrata marsruutimiskombodele:

- `compression_combos`: salvestab režiimi, torujuhtme, RTK konfiguratsiooni, keele konfiguratsiooni ja vaikemarkeri
- `compression_combo_assignments`: vastendab tihenduskombo marsruutimise kombinatsiooniks
- käitusaegne integratsioon lahendab määratud tihenduskombo enne üldise kombinatsiooni alistamist
- analüütika hõlmab `compression_combo_id` ja `engine`

Armatuurlaua pind: `Dashboard -> Context & Cache -> Compression Combos`.

## Eeltingimused / operaatori juhend (CCR & session-dedup)

CCR (`ccr`) ja `session-dedup` asendavad või eemaldavad teksti ja jätavad a** marker** taga. See jaotis on operaatori viide kliendi juhtmestiku ühendamiseks, kahe markeri lugemiseks ja väljastatud sisu hankimiseks või diagnoosimiseks. Iga mootori mehaanikat käsitletakse eespool; see on "kuidas ma seda käivitan" kiht.

### Transpordid ja lõpp-punktid

MCP serverisse, mis paljastab CCR tööriistad, pääseb kolmel viisil. Vaikimisi URL baasväärtus on `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transport                              | URL / käsk                              | Märkmed                                                                                                                             |
| -------------------------------------- | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Voogesitatav HTTP (klient, soovitatav) | `http://localhost:20128/api/mcp/stream` | Lõpp-punkt, millega praegused MCP kliendid räägivad.                                                                                |
| Pärand SSE singleton                   | `http://localhost:20128/api/mcp/sse`    | Vanem üksiktransport. See** sulgub** voogedastavad seansid; kasutage `streamable-http` kliente `/api/mcp/stream` vastu, mitte seda. |
| stdio                                  | `omniroute --mcp`                       | Protsessi käivitava IDE MCP konfiguratsiooni jaoks. `--dev` lippu pole; `omniroute --mcp` on stdio sisenemispunkt.                  |

### Salvestustasemed (mis püsib taaskäivitamisel üle)

CCR on a** kahetasandiline** pood, mitte ainult mälus:

- **Kuum mälusisene tasand** — ploki kohta 2 MiB, peamise kohta 16 MiB, globaalne 64 MiB. Kirjed on vaikimisi 24 h TTL (maksimaalselt 7 päeva). Täieliku MCP mälust otsimise ülempiir on 256 KiB; kõik suuremad on endiselt kättesaadavad vahemiku / grep režiimide kaudu.
- **Vastupidav SQLite tasand** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, vaikimisi sisse lülitatud) — toetab mälus olevat taset, nii et plokk jääb ellu pärast LRU väljatõstmist, taaskäivitamist või laadimise maandumist teisele eksemplarile. Rida säilitab ploki TTL, nii et selle TTL möödunud plokk kaob mõlemast astmest.

Kolm kaitset hoiavad vastupidavat tasandit piiratud — a plokk jääb ainult mäluks, kui:

1. blokk on läbi** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. käitusaeg on pilve käitusaeg (kohalikku ketast pole);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Nii et "plokk kadus" ei ole üldine taaskäivitamise lugu: sub-512 KB plokk kohalikul, mittepilvepõhisel käituskeskkonnal püsib taaskäivituse läbi vastupidava tasandi, kuni selle TTL saab otsa. Muutuja kohta vaadake [Keskkonna viidet](../reference/ENVIRONMENT.md).

### Kaks markerit

| Marker                                | Tähendus                                                                                                                                     | Mida peaks modell tegema                                                                                                                                                                                                         |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Suur plokk salvestati sisuaadressiga.                                                                                                        | Helistage `omniroute_ccr_retrieve` -le** 24-hex hash kopeeritud sõna-sõnalt** et algtekst tagasi saada.                                                                                                                          |
| `[dedup:ref sha=…]`                   | `session-dedup` elided tekst, mis on juba saadetud sama seansi varasemas pöördes. See on an** tahtlik tagasivaade** , mitte kaotus või viga. | Tee** mitte** helistage mis tahes tööriistale ja tehke** mitte** proovige seda "rekonstrueerida". Teksti esimene esinemine on kanooniline koopia; praegust pööret ei kirjutata kunagi ümber, see eemaldatakse hilisemal pöördel. |

`[dedup:ref]` tagasivaade on tahtlik protokolliline otsus. — puudub saatmiseelne rekonstrueerimine. Käsitlege seda kui "see täpne tekst oli juba varem sellel seansil väljas".

### Kliendi eeldused

- **Võti (stdio):** stdio-helistajal puudub päringupõhine identiteet, mistõttu see autentib `OMNIROUTE_API_KEY` (seatud MCP serveri `env`). Ilma selleta on helistaja anonüümne ja käsundiandjat vajavad tööriistad võivad halveneda.
- **`tools[]` on süstimise eeltingimus.** Sisestatakse CCR retrieve-protocol käsk (#8033).** ainult** kui päringu reklaamitud `tools[]` tõestab, et klient võib tegelikult jõuda `omniroute_ccr_retrieve`. Vaste on lõpuosa vaste, mida piirab eraldaja (`__`, `.`, `/`, `:`) — ei ole kunagi tühi alamstring — nii et nimeruumiga nimi, näiteks `mcp__gateway__omniroute_ccr_retrieve` läheb arvesse. Puuduv või mittevastav `tools[]` tähendab, et käsku _ei_ sisestata.
- **`codemode:false` (OpenCode kliendid).** OpenCode kasutab vaikimisi koodirežiimi, mis reklaamib mudelile ja mudelile ainult oma tööriistu** ei tee seda** pane MCP tööriistad algsesse `tools[]` loendisse. Määrake MCP serveri sisestuses `codemode: false`, et `omniroute_ccr_*` tööriistu reklaamitaks. See on a** klient** seade, mitte OmniRoute. Sellele ei sisestata veel käsku CCR : OpenCode nimetab tööriista `<server>_<tool>`, nii et server nimega `omniroute` paljastab `omniroute_omniroute_ccr_retrieve` ja `_` ei ole üks sobitatud eraldajatest.
- **Direktorid.** Salvestus ja otsimine on isoleeritud autentitud printsiparaadi ( API võtme kohta). Võti näeb ainult oma plokke.

### Kasutusalad tööriista kohta

Piiravuse jõustamine on kitsa ulatusega HTTP/SSE helistajate jaoks alati sisse lülitatud. `omniroute_` CCR tööriistad nõuavad:

| Tööriist                 | Ulatus              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Puuduv ulatus tagastab an**MCP tööriista vea tulemus** (`isError: true`, mitte HTTP 403 — `403 LOCAL_ONLY` on eraldi loopback marsruudivalve autentimine): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimaalne kaugvõti võib sisaldada `mcp:connect` (volitab `/api/mcp/` -i ainult lokaalset väljalõike) pluss spetsiifilise read/write ulatuse, mida see vajab.

### Kliendimaatriks

| Klient            | Transport                                     | Konfiguratsioon kasutamiseks                                                                                                                                                                                                                     | `tools[]` reklaamitud? (→ CCR juhis sisestatud)                                                                                                                                            |
| ----------------- | --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Claude kood       | striimitav-http                               | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                | Jah — MCP-võimeline; süstitud.                                                                                                                                                             |
| Cursor / Cline    | `stdio`** või** `streamable-http`             | stdio: `omniroute --mcp` koos `OMNIROUTE_API_KEY` ga `env`; või kaug- MCP -sisend, mis osutab `http://localhost:20128/api/mcp/stream` (vt [häälestusjuhendit → MCP kliendi konfiguratsioon](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Jah — reklaamib `omniroute_ccr_*` tööriistu.                                                                                                                                               |
| OpenCode          | striimitav-http                               | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` pluss `codemode: false`                                                                                                                                                 | Tööriistad, mida reklaamitakse ainult `codemode: false` ga; käsku ikka ei sisestata, sest `omniroute_omniroute_ccr_retrieve` ei sobi (vt [Kliendi eeltingimused](#client-prerequisites) ). |
| OpenAI-ga ühilduv | OpenAI-ga ühilduv HTTP (vestluse lõpetamised) | standardse vestluse lõpetamise klient OpenAI-ga ühilduva lõpp-punkti vastu                                                                                                                                                                       | **Mitte kunagi** — tavalisel OpenAI-ga ühilduval helistajal ei öelda kunagi tööriistale helistamiseks ja juhiseid ei sisestata.                                                            |

### Otsimise piirangud ja lehekülgede arv

MCP tööriista tekstitulemused lõigatakse ümber `mcpAccessibility.maxTextChars` (vaikimisi `50000`). Ploki `full` allalaadimise piiriks on 256 KiB —** piiramatut täielikku allalaadimist pole** . Kui ploki `chars=N` on suur, lehitsege see, mitte ei tõmba kogu asja:

- Rusikareegel:**`chars > 40000` → kasutage `mode`** , mitte kunagi paljast täis.
- `mode:"grep"` — regex `pattern` sobitatud ridade kaupa, kuni 1000 sobivat rida (`unique: true` drops kordub), odavaim "leia üks vajalik rida".
- `mode:"lines"` — 1-indeksiga joonvahemik; vajab nii `start` kui ka `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` read.
- `mode:"stats"` — rida, tähemärki ja baite loetakse ilma kehata.

Kasutage `mode:"lines"` koos `start`/`end`, et lehekülgede kaupa läbida, mitte kogu asja korraga nõuda.

### Tööriistade nimetamine

Tootmistööriist kannab praegu nime `omniroute_ccr_retrieve` (eesliide `omniroute_` on dateeritud lahendus serveriüleste nimede kokkupõrgetele). Tööriista puhtamat piiritletud järelliidet ja parandust MCP JSON tulemuste kärbitud keskmist stringi jälgitakse ülesvoolu järelmeetmetena; sellel lehel dokumenteeritakse ainult praegune tarnitud käitumine.

### Seansi elutsükkel

Voogesitatavad HTTP-seansid on tühikäigul ja server võtab need ära; jõudeaken on `MCP_SESSION_IDLE_MS` konstant (viidatud nime järgi, mitte kõvakoodiga väärtus, nii et see leht ei triivi, kui see muutub). Tühiseansi sümptomiks on HTTP 404 koos `Unknown Mcp-Session-Id` — Abinõu on seansi taasühendamine või taaskäivitamine,** mitte** klahvi pööramiseks, ulatuse muutmiseks või tööriista ümbernimetamiseks.

## API pind

| Marsruut                               | Eesmärk                                                                      |
| -------------------------------------- | ---------------------------------------------------------------------------- |
| `/api/settings/compression`            | Globaalsed tihendamise seaded (sisaldab `mcpAccessibility` konfiguratsiooni) |
| `/api/compression/preview`             | Vaadake mis tahes tihendusrežiimi eelvaadet                                  |
| `/api/compression/language-packs`      | Loetlege saadaolevad Cavemani keelepaketid                                   |
| `/api/context/caveman/config`          | Caveman seadete alias                                                        |
| `/api/context/rtk/config`              | RTK vaikesätted ja sätted                                                    |
| `/api/context/rtk/filters`             | RTK filtrite kataloog                                                        |
| `/api/context/rtk/test`                | RTK preview/test lõpp-punkt                                                  |
| `/api/context/rtk/raw-output/[id]`     | Autentitud redigeeritud töötlemata väljundi taastamine                       |
| `/api/context/combos`                  | Kompressioon CRUD                                                            |
| `/api/context/combos/[id]/assignments` | Marsruutimise kombinatsiooni määramine CRUD                                  |
| `/api/context/analytics`               | Tihendusanalüütika varjunimi                                                 |

Haldusmarsruudid nõuavad halduse autentimist või API-võtme poliitikakontrolle.

## MCP tööriistad

Kompressioon paljastab viis MCP tööriista:

| Tööriist                            | Ulatus              | Eesmärk                                  |
| ----------------------------------- | ------------------- | ---------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Seaded, analüüs, vahemälu statistika     |
| `omniroute_compression_configure`   | `write:compression` | Värskendage globaalseid seadeid          |
| `omniroute_set_compression_engine`  | `write:compression` | Seadistage režiim ja valikuline torujuhe |
| `omniroute_list_compression_combos` | `read:compression`  | Loetlege tihenduskombod                  |
| `omniroute_compression_combo_stats` | `read:compression`  | Lugege combo/engine analüüsi             |

## Ulatus ja välistused

**Manustusi ei tihendata kunagi.** `open-sse/handlers/embeddings.ts` ei nimeta kunagi ühtegi kompressioonimootorit — request/response kehad lähevad puutumatult otse täideviijale. See on tänapäeval struktuurne (manustused ja vestluse lõpetamised on lahtised töötlejad), mitte käitusaegne kontroll, kuid see tähendab, et #8034 -s ei ole vektorimoonutuste probleemil manustamisteel kokkupuutepinda.

**Per-model/endpoint välistusfilter (#8034).** Vestluse lõpuleviimisel saab operaator nimetada mudeli ID-d / `provider/model` -sihtmärgid, mida ei tohi kunagi tihendada — kaitsepiire, mis on kasulik, kui tihendamine on hiljem manustega külgnevale teele lähemale, ja üldiselt kasulik iga mudeli puhul, mille täpne bait-bait-viipa on oluline (deterministlikud väärtused, vahemälutundlikud eesliited jne).

- Seadete väli: `exclusions?: string[]` globaalsel tihendamise konfiguratsioonil (`GET`/`PUT /api/settings/compression`), püsis olemasoleva `key_value` tihendamise nimeruumi kaudu (`src/lib/db/compression.ts`) — uut tabelit pole.
- Armatuurlaua vahekaart:** Armatuurlaud → Compression → välistused** (`/dashboard/compression/exclusions`).
- Mustri süntaks: `*` on ainus metamärk. Mustri iga teine regex-metamärk on enne sobitamist välditud, nii et `gpt-5.6` sobib ainult sõnasõnalise stringiga, mitte kunagi `gpt-5x6` (ReDoS-ohutu, piiratud, pesastatud kvantoreid pole). Mustrid ühtivad tõstutundlikult nii tühja mudeli ID kui ka `provider/model` liitkoodiga — `gpt-5-6`, `openai/gpt-5-6` ja `openai/*` kõik töötavad ning `*` üksi välistab kõik mudelid.
- Sobivus: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` kontrollib välistatud sihtmärki kohe pärast tihendusseadete lahendamist,** enne kui mõni mootor tööle hakkab** , ja kohtleb vastet täpselt nii, nagu pakkimine oleks globaalselt keelatud — päringu keha on tõestatavalt baidide identne. Vahelejätmine salvestatakse `writeCompressionSkip(..., "excluded")` kaudu analüütika nähtavuse tagamiseks.
- Vaikimisi (empty/absent loend): identne #8034 eelse käitumisega — miski pole välistatud.

## Teadaolevad piirangud

- **LLMLingua-2 (SLM) nõuab ühise asukohaga valikulisi deps-e.** Töötaja töötab tootmisjärgus ainult siis, kui `@atjsh/llmlingua-2` + partnerid asuvad `dist/node_modules` (vt `scripts/build/colocateOptionals.mjs`, #4286). Ilma nendeta mootor tõrkeavaneb (tagastab originaalteksti). Töötaja eraldusvõime ei sõltu enam `import.meta.url` (see sureb eraldiseisvas komplektis) — see ankurdub käitusajal cwd / `argv[1]`.
- **Cavemani keelepaketid `de` / `fr` / `ja` on osalised.** Nad saadavad `context` + `filler` + `structural` reegleid, kuid `dedup` / `ultra` pakette pole, nii et `ultra` intensiivsus ei ole nende keelte puhul suurem kui `full` (nad kasutavad ainult oma reegleid — ingliskeelsetele `dedup`/`ultra` võõrtekstidele ei ole vaikset tagasiminekut). `en` / `es` / `id` / `pt-BR` on valmis. Osapakkide `dedup.json` + `ultra.json` on teretulnud.
- **Virnastatud telemeetria loetleb ainult tihendatud mootorid.** Virnastatud torujuhtme samm, mille mootor töötas, kuid andis 0% säästu, tagastab `stats:null` ja seega ei kuvata `engineBreakdown` — eristamatuna vahelejäetud etapist. "Jooks, 0 %" eristamiseks "vahele jäetud" nõuaks jaotusmudeli muutmist ja see lükatakse edasi.

## Valideerimine

Selle piirkonna fookusväravad on järgmised:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
