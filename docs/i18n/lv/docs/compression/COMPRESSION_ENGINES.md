# Compression Engines (Latviešu)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompresija ir balstīta uz dzinēja līgumiem. Režīms var tieši darbināt vienu dzinēju (`caveman` vai `rtk`) vai deterministisku stacked konveijeru, kas izpilda vairākus dzinējus secībā.

## Režīmi

| Režīms       | Dzinēja ceļš                                                                                         | Paredzētā ievade                                           |
| ------------ | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| `off`        | neviens                                                                                              | Precīza tūlītēja saglabāšana                               |
| `lite`       | Caveman Lite palīgi                                                                                  | Zema riska vienmēr notiekoša tīrīšana                      |
| `standard`   | Alu cilvēks                                                                                          | Dabiskās valodas tūlītēja kondensācija                     |
| `aggressive` | Caveman + history/tool apkopotāji                                                                    | Ilgas tērzēšanas sesijas                                   |
| `ultra`      | Caveman + atzarošanas palīgi                                                                         | Konteksta ierobežojuma atkopšana                           |
| `rtk`        | RTK                                                                                                  | Termināļa, apvalka, būvēšanas, pārbaudes un git izvade     |
| `omniglyph`  | OmniGlyph                                                                                            | Konteksts kā attēls vietējā nodrošinātāja vadā             |
| `stacked`    | Cauruļvads. Pieprasījuma noklusējuma vērtība ir `session-dedup -> lite`. `rtk -> caveman` ir izvēle. | Jaukti instrumentu žurnāli un proza, maksimāls ietaupījums |

### OmniGlyph kompresijas profili

`omniglyph` dzinējs (pakotne `omniglyph`, 1.4.0 +) pieņem nosauktu semantisko profilu, kas globāli iestatīts, izmantojot `omniglyph.profile` saspiešanas iestatījumos vai katrā solī, izmantojot stacked konveijera soļu konfigurāciju:

| Profils       | Robeža                                                                                                   |
| ------------- | -------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Noklusējums. Politika publicētajās kvītīs mērīja — attēlu sistēmu, rīku dokumentus un blīvu vēsturi      |
| `balanced`    | Saglabā reāllaika štata vietējo, aizsargā pēdējos 8 pagriezienus, sakļauj vecāku slēgto vēsturi          |
| `coding-safe` | Saglabā autoritāti, instrumentu shēmas un reāllaika instrumenta izvadi, aizsargā pēdējos 12 apgriezienus |
| `passthrough` | Maršruti bez pārveidošanas; dzinējs ir izlaists                                                          |

Profils ir a** griesti, nevis grīda** : `mergeCompressionProfileOptions` iepakojumā atsakās ļaut zvanītājam ignorēt joslu ar zudumiem, ja profils ir aizvērts, tāpēc `preserveSystemPrompt: false` pa solim nevar atkārtoti iespējot sistēmas saspiešanu zem `coding-safe`.

Mērot šajā kodu bāzē: `coding-safe` un `balanced` paaugstina `minCompressChars` līdz maksimumam un saglabā sistēmas, rīku shēmas un rīku rezultātus sākotnējos, tāpēc sesija, kurai vēl nav uzkrāta vēsture, apstājas pie `below_min_chars` un dzinējs neko nepārveido. Tāpēc noklusējuma profils ir `aggressive`, nevis drošākais profils.

Pakotne atrisina savu modeļa darbības jomu un profilu no vides konfigurācijas. OmniRoute nekad nedeleģē lēmumu: adapteris piesprauž modeļa vārtus pakotnes visierobežotākajai jomai, tāpēc resursdatora vides iestatījumi var tikai sašaurināt atļaušanas sarakstu, nekad to nepaplašināt, pārsniedzot OmniRoute izmērītos ieņēmumus.

## Dzinēju reģistrs

Reģistrs dzīvo `open-sse/services/compression/engines/registry.ts`. Dzinēji pakļauj kopīgu līgumu:

- `id`: stabils dzinēja ID, piemēram `caveman` vai `rtk`
- `apply(text, config)`: mantotais izpildes ceļš, ko izmanto stacked cauruļvadi
- `compress(input, config)`: primārais izpildes ceļš, kas atgriež tekstu + stats
- `getConfigSchema()`: atgriež derīgas konfigurācijas JSON shēmai līdzīgu formu
- `validateConfig(config)`: atgriež `{ valid, errors[] }`

Reģistrācijai tiek izmantots `registerCompressionEngine(engine)` (vai `registerEngine` progresīviem gadījumiem), kas pirms pieņemšanas izsauc `assertValidEngine()` un `validateConfig(defaultConfig)`. Izmantojiet `unregisterCompressionEngine(id)`, lai darbības laikā noņemtu dzinēju.

`strategySelector.ts` reģistrē iebūvētos dzinējus pirms kompresijas darbības. Tas ļauj priekšskatījumam, izpildlaika saspiešanai, stacked režīmam, testiem un turpmākajiem dzinējiem izmantot to pašu izpildes ceļu.

### MCP apraksta saspiešana (saistīta)

Atsevišķs reģistrs saspiež MCP rīka apraksta metadatus reģistra līmenī — skatiet `open-sse/mcp-server/descriptionCompressor.ts` un [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Tas atkārtoti izmanto Caveman noteikumus, bet darbojas ar rīku metadatiem, nevis pieprasa lietderīgās slodzes.

### Papildu iebūvētie dzinēji

Papildus Caveman, RTK un LLMLingua-2 reģistrā tiek piegādāti vairāki specializēti bezzudumu/strukturālie dzinēji (ko izmanto salikti cauruļvadi, rotaļu laukums un testi):

| Dzinējs       | Id              | Ko tas dara                                                                                                                                                                                     |
| ------------- | --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): aizstāj lielus blakus esošos teksta blokus ar saturam adresētām atsaucēm, tāpēc repeated/large bloki tiek nosūtīti vienreiz un pēc tam tiek izmantoti atsauces. |
| galvas telpa  | `headroom`      | SmartCrusher (H3 + N5): homogēnu JSON masīva lietderīgo kravu bezzudumu tabulas blīvēšana kolonnveida `[N rows]` formā.                                                                         |
| jonizators    | `ionizer`       | Head/middle/tail rindu paraugu ņemšana ļoti lieliem viendabīgiem blokiem, saglabājot elidēto vidu kā CCR saturam adresētu atsauci.                                                              |
| session-dedup | `session-dedup` | Saturam adresēta pārrobežu kārtu dedublikācija (TokenMizer iedvesmota): izslēdz tekstu, kas jau ir redzams tās pašas sesijas iepriekšējos posmos.                                               |

**CCR izguves protokola instrukcija (#8033):** Pirmo reizi, kad CCR pieprasījumā aizstāj ≥ 1 bloku, dzinējs pievieno vienu idempotentu `system` ziņojumu (sākot ar `[CCR protocol]` sentinel), mācot zvanītājam marķiera → rīka līgumu: ko nozīmē `[CCR retrieve hash=<24hex> chars=N]` marķieris, ka jaucējkods ir jākopē burtiski (visi 24 hex bloķēšanas rakstzīmes, iespējams, ir — rakstzīmes. nav atrasts" nepalaiž garām), un ka `[dedup:ref sha=...]` marķieris nozīmē "atskatīties vēsturē", nevis "izsaukt rīku". Piezīme tiek injicēta** tikai tad, kad zvanītāja reklamētais `tools[]` pierāda, ka tas faktiski var sasniegt `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — vienkāršs ar OpenAI saderīgs zvanītājs bez šī rīka nekad nesaņem norādījumu izsaukt kaut ko tādu, ko tas nevar sasniegt. Idempotence tiek nodrošināta, pirms injicēšanas pārbaudot ziņojumu vēsturi, lai atrastu uzraugu, tāpēc vairāku gājienu pieprasījumi (kas atkārto iepriekšējos ziņojumus) nesaliek piezīmi vienu reizi gājienā.

## Alu cilvēks

Alu cilvēka režīms koncentrējas uz parastās prozas semantisko kondensāciju:

- saglabā kodu blokus, URLs, JSON, ceļus un strukturētos datus
- noņem aizpildījumu, riska ierobežošanu, atkārtotu kontekstu un daudznozīmīgu savienojošo frāzi
- atbalsta valodu zinošas failu noteikumu pakotnes `open-sse/services/compression/rules/`
- joprojām ir pieejams, izmantojot mantotos `standard`, `aggressive` un `ultra` režīmus

Informācijas paneļa virsma ir `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream ziņo par `~75%` mazāk izvades marķieru, `65%` vidējo izvades ietaupījumu etalonos ar `22-87%` diapazonu un `~46%` ievades saspiešanas rīku. OmniRoute izmanto Caveman ievades puses numuru, dokumentējot stacked prompt/context ietaupījumus; Alu cilvēka izvades režīms joprojām ir atsevišķa reakcijas uzvedības funkcija.

## RTK

RTK režīms koncentrējas uz komandu un rīku izvadi:

- nosaka izvades klases, piemēram, `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testus, TypeScript/Vite/Webpack būvējumus, ESLint, npm audit/installs, Docker žurnālus, apvalku `find`/`grep`, steka trases un vispārīgos žurnālus.
- izmanto 49 JSON filtrus no `open-sse/services/compression/engines/rtk/filters/`
- atbalsta RTK stila deklaratīvo konveijeru: ANSI noņemšana, nomaiņa, saskaņošanas izvades īssavienojums, strip/keep līnijas, katras līnijas saīsināšana, head/tail/max-line saīsināšana un tukša atkāpšanās.
- atbalsta uzticamības projektu filtrus `.rtk/filters.json` un globālos filtrus `DATA_DIR/rtk/filters.json`
- svītro ANSI sekvences, progresa troksni, atkārtotas līnijas un nederīgu pamatplāksni
- saglabā darbības kļūmes, brīdinājumus, kopsavilkumus, mainītos failus un astes kontekstu
- var pēc izvēles saglabāt rediģēto neapstrādāto izvadi recovery/debugging, izmantojot autentificētus pārvaldības maršrutus

Informācijas paneļa virsma ir `Dashboard -> Context & Cache -> RTK`.

Darbības informācija par pielāgotajiem filtriem, uzticamību, pārbaudi un neapstrādātas izvades atkopšanu tiešsaistē [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream ziņo par `60-90%` ietaupījumiem komandu izvades saspiešanai. Tā README piemērā ir parādīta 30 minūšu Claude koda sesija, kas pāriet no `~118,000` marķieriem uz `~23,900` vai `79.7%` saglabātu.

## LLMLingua-2 (semantiskā atzarošana)

LLMLingua-2 režīms darbojas** semantiskā marķiera apgriešana** par prozu, izmantojot nelielu ONNX marķieru klasifikatoru, kas papildina uz noteikumiem balstītos Caveman un RTK dzinējus:

- saspiež prozu tikai nesistēmas ziņojumos; iežogotie kodu bloki un citas saglabātās konstrukcijas nekad netiek mainītas
- palaiž `@atjsh/llmlingua-2` aizmugursistēmu (ONNX caur `@huggingface/transformers`) darbinieka pavedienā, tāpēc modeļa secinājumi nekad nebloķē pieprasījuma notikuma cilpu
- ir** sakraujami** (`stackPriority` 35): stacked konveijerā tas darbojas pēc strukturālajiem dzinējiem (CCR, session-dedup, headroom, Caveman), bet pirms `ultra`, jo semantiskā atzarošana ir visefektīvākā jau strukturāli saspiestam tekstam — piemēram, `rtk -> caveman -> llmlingua`
- **kļūmju atvēršana jebkuras kļūdas gadījumā** (trūkst izvēles deps, darbinieka nāves, modeļa ielādes, secinājumi vai taimauta) → oriģinālais teksts tiek atgriezts nemainīts, nekad nav kļūda

Dzinēja atrašanās vieta: `open-sse/services/compression/engines/llmlingua/`. Informācijas paneļa virsma ir `Dashboard -> Context & Cache -> LLMLingua`.

### Modeļi

Noklusējuma modelis ir**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, ātrs). Augstāka precizitāte** BERT bāze** modelis (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) ir pieejams, izmantojot motora konfigurācijas `model` lauku. `@huggingface/transformers` laiski lejupielādē atlasīto modeli no HuggingFace Hub uz `${DATA_DIR}/models/llmlingua` pirmajā zvanā (`modelStore.ts`); `modelPath` konfigurācijas ignorēšana norāda uz lokālo kopiju (bezsaistes / instalēšanas ar gaisa pārtraukumu).

### Izvēles atkarības un instalēšana pēc pieprasījuma

Atzarojamā LLMLingua izpildlaika vienādranga steks ir** pēc izvēles** . Divi iepakojumi tiek deklarēti kā `optionalDependencies` `package.json` un tiek glabāti** ārējā** pēc ražošanas būvējuma (`scripts/build/prepublish.ts` tos neapvieno):

| Iepakojums           | Versija (pin) | Piezīmes                                         |
| -------------------- | ------------- | ------------------------------------------------ |
| `@atjsh/llmlingua-2` | `2.0.5`       | Ieejas pakete; pasludina pārējos par vienaudžiem |
| `js-tiktoken`        | `^1.0.20`     | Tokenizators                                     |

`@huggingface/transformers` ir piesprausts pie `^4.2.0` (kopīgots ar vietējo iegulšanas ceļu un arī izsekots atsevišķajā komplektā); `@atjsh/llmlingua-2@2.0.5` sadarbojas ar `"^3.5.2 || ^4.0.0"`, tāpēc tiek atbalstīti gan Transformers.js v3, gan v4. Kopš versijas 2.0.4 `@atjsh/llmlingua-2` vairs neprasa `@tensorflow/tfjs`, kas no SLM steka noņēma lielāko vienu līdzautoru (TensorFlow.js). Tikai divas iepriekš minētās pakotnes ir atzarojamas SLM līdzīgas paketes. Standarta `npm install` (dev) automātiski instalē izvēles steku, ja vien netiek izlaistas izvēles atkarības.

**Kāpēc pēc pieprasījuma:** npm publicētā pakotne, savrupais komplekts un Docker attēla sūtījums** bez** šie deps, lai paliktu slaidi. Ja to nav, darbinieka atkarības vārti ( `@atjsh/llmlingua-2` atrisināšanas zonde `worker.ts`) nedarbojas un dzinējs** klusi atveras** — atlasot LLMLingua kļūst par no-op (teksts tiek atgriezts nemainīgs, kļūda nav reģistrēta). Lai to aktivizētu apgrieztā vidē, instalējiet izvēles kaudzīti:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` noņemšana (2.0.4 +) novērš iepriekš dominējošo ~ 800 MB veicinātāju — atlikušais nospiedums ir transformers.js + onnxruntime-node izpildlaiki, kā arī TinyBERT modelis (~ 57 MB), kas lejupielādēts pirmajā lietošanas reizē (nevis caur npm).

Videi:

- **Izstrādātājs / `npm install`** — tiek instalēts automātiski, ja vien neesat nokārtojis `--omit=optional` (vai `--no-optional`). Nav nepieciešama nekāda darbība.
- **Globālais npm (`npm i -g omniroute`) / savrups** — palaidiet instalēšanas komandu iepriekš instalētās pakotnes direktorijā vai pārinstalējiet, neizlaižot papildu deps.
- **Docker** — pievienot instalēšanas komandu atvasinātajā attēla slānī; publicētais attēls ir slaids pēc dizaina.
- **VPS (PM2)** — instalējiet lietotnes `node_modules`, pēc tam restartējiet procesu, lai darbinieks atkārtoti pārbaudītu vārtus.
- **Raw Next savrups (`npm run build` → `.build/next/standalone/server.js`)** — atsevišķie izsekošanas kuģi NEITHER strādnieku vai izvēles deps, lai dzinējs klusi atvērsies. `scripts/build/colocate-standalone.mjs` atkārtoti piemēro abus (darbinieks esbuild + neobligātu-dep slēgšanu savrupajā kokā); tas darbojas automātiski, izmantojot `postbuild` npm āķi pēc katras būves. Idempotents, izturīgs, ja dep nav.

**Pārbaudiet, vai tas ir aktīvs:** ja ir atlasīts LLMLingua, reālā proza faktiski sarūk (dzinējs aptur kļūmes atvēršanu), un pirmais pieprasījums aktivizē modeļa lejupielādi `${DATA_DIR}/models/llmlingua`. Vārti apzināti pārbauda tikai `@atjsh/llmlingua-2` — citi līdzīgie ir tikai ESM, un `require.resolve` met uz tiem pat tad, ja ir — tāpēc darbinieks joprojām tiek atvērts, ja `import()` laikā patiešām trūkst kāda līdzinieka.

## Sakrauti cauruļvadi

Stacked režīmā konveijera darbības tiek veiktas secībā. Noklusējums ir:

```txt
rtk -> caveman
```

Izmantojiet to kodēšanas aģenta sesijām, kurās uzvedne apvieno komandu izvadi ar cilvēka vai asistenta prozu. RTK vispirms samazina trokšņainos rīku žurnālus, pēc tam Caveman saspiež atlikušo dabisko valodu.

Cauruļvada soļi tiek konfigurēti ar `stackedPipeline` saspiešanas iestatījumos vai izmantojot saspiešanas kombinācijas.

Kad abi dzinēji samazina to pašu piemēroto kravnesību, ietaupījums:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP pieejamības koka filtrs

MCP pieejamības koka viedais filtrs ir pēcizpildes saspiešanas slānis, kas darbojas MCP** rīku rezultāti** , nevis pēc uzvednēm vai konteksta. Tas ir paredzēts detalizētām pieejamības koka un pārlūkprogrammas momentuzņēmumu lietderīgajām slodzēm, ko atgriež tādi rīki kā Playwright, datora lietošana un pārlūkprogrammas automatizācijas MCP serveri.

### Ko tas dara

1. **Trokšņa noņemšana** — noņem tukšus generic/text ierakstus (`- generic:`, `- text: ""`)
2. **Brāļa sabrukums** — ja ≥ `collapseThreshold` (noklusējuma 30) secīgās rindas ir strukturāli atkārtojumi, sakļauj tās pirmajās `collapseKeepHead` (noklusējuma 10) rindās + skaitīšanas kopsavilkums + pēdējās `collapseKeepTail` (noklusējuma 5) rindas
3. **Atsauces saglabāšana** — `[ref=eXX]` enkuri, kas nepieciešami Playwright/computer-use nekad netiek aiztikti
4. **Stingra saīsināšana** — ja teksts pēc sakukšanas joprojām pārsniedz `maxTextChars` (noklusējuma 50 000), tiek saīsināts ar navigācijas mājienu, lai aģents varētu turpināt darbu

### Dzinēja atrašanās vieta

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfigurācija

Globālos iestatījumos (migrācijas 056) kontrolē `compression.mcpAccessibility`. Noklusējuma konfigurācija:

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

Filtrs tiek lietots tikai instrumenta rezultātu kravām, kuru `type` ir `"text"` un kuru garums pārsniedz `minLengthToProcess`. Tas neietekmē tūlītēju saspiešanu vai lietderīgās slodzes pieprasījumu.

### Paredzamie ietaupījumi

60–80% no pārlūkprogrammas momentuzņēmuma rīka rezultātiem atkarībā no lapas sarežģītības. Sakļūšanas algoritms ir O(n) līniju skaitā un pievieno nenozīmīgu latentumu.

### Šis filtrs salīdzinājumā ar iepriekš minētajiem kompresijas dzinējiem

| Aspekts       | Alu cilvēks / RTK / Stacked    | MCP pieejamības filtrs                 |
| ------------- | ------------------------------ | -------------------------------------- |
| Mērķis        | Pieprasīt uzvednes / konteksts | MCP rīku rezultāti                     |
| Sprūda        | Kompresijas režīma iestatīšana | `compression.mcpAccessibility.enabled` |
| Darbības joma | Visas SSE ziņas                | Tikai rīku rezultāti                   |
| Ref enkuri    | N/A                            | Saglabāts bez nosacījumiem             |

---

## Kompresijas kombinācijas

Kompresijas kombinācijas tiek nosauktas par saspiešanas profiliem, ko var piešķirt maršrutēšanas kombinācijām:

- `compression_combos`: saglabājas režīms, cauruļvads, RTK konfigurācija, valodas konfigurācija un noklusējuma marķieris
- `compression_combo_assignments`: kartē saspiešanas kombināciju ar maršrutēšanas kombināciju
- izpildlaika integrācija atrisina piešķirto saspiešanas kombināciju pirms vispārīgās kombinācijas ignorēšanas
- analītika ietver `compression_combo_id` un `engine`

Informācijas paneļa virsma: `Dashboard -> Context & Cache -> Compression Combos`.

## Priekšnosacījumi / operatora rokasgrāmata (CCR & session-dedup)

CCR (`ccr`) un `session-dedup` aizstāj vai atceļ tekstu un atstāj a** marķieris** aiz muguras. Šī sadaļa ir operatora atsauce, lai savienotu klientu, nolasītu divus marķierus un izgūtu vai diagnosticētu izdalītā satura. Katra dzinēja mehānika ir apskatīta iepriekš; šis ir slānis "kā to palaist".

### Transports un galapunkti

MCP serveri, kas atklāj CCR rīkus, var sasniegt trīs veidos. Noklusējuma bāze URL ir `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transports                            | URL / komanda                           | Piezīmes                                                                                                                                       |
| ------------------------------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Straumējama HTTP (klients, ieteicams) | `http://localhost:20128/api/mcp/stream` | Galapunkts, ar kuru sarunājas pašreizējie MCP klienti.                                                                                         |
| Mantotais SSE viengabals              | `http://localhost:20128/api/mcp/sse`    | Vecāks vienvietīgs transports. Tas** aizveras** straumējamas sesijas; izmantojiet `streamable-http` klientus pret `/api/mcp/stream`, nevis šo. |
| stdio                                 | `omniroute --mcp`                       | IDE MCP konfigurācijai, kas rada procesu. Nav `--dev` karoga; `omniroute --mcp` ir stdio ievades punkts.                                       |

### Krātuves līmeņi (kas izdzīvo pēc restartēšanas)

CCR ir a** divpakāpju** veikals, nevis tikai atmiņā:

- **Karsts atmiņas līmenis** — bloka vāciņš 2 MiB, vienam galvenajam 16 MiB, globālais 64 MiB. Ieraksti pēc noklusējuma ir 24 h TTL (maksimums 7 dienas). Pilna MCP izguve no atmiņas ir ierobežota līdz 256 KiB; viss lielāks joprojām ir sasniedzams, izmantojot diapazona / grep režīmus.
- **Izturīgs SQLite līmenis** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, ieslēgts pēc noklusējuma) — atbalsta atmiņas līmeni, lai bloks izturētu LRU izlikšanu, restartēšanu vai izguves nosēšanos citā instancē. Rinda saglabā bloka TTL, tāpēc bloks, kas pārsniedz tā TTL ir pazudis no abiem līmeņiem.

Trīs aizsargi notur izturīgu līmeņu robežu — bloks paliek tikai atmiņā, ja:

1. bloks ir beidzies** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. izpildlaiks ir mākoņa izpildlaiks (nav lokālā diska);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Tātad "bloks pazuda" nav vispārējs restartēšanas stāsts: sub-512 KB bloks lokālā, ne mākoņa izpildlaikā iztur restartēšanu, izmantojot izturīgo līmeni, līdz izbeidzas tā TTL. Skatiet mainīgo [vides atsauci](../reference/ENVIRONMENT.md).

### Divi marķieri

| Marķieris                             | Nozīme                                                                                                                                             | Kas modelim jādara                                                                                                                                                                                                    |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Liels bloks tika saglabāts saturam adresēti.                                                                                                       | Zvaniet `omniroute_ccr_retrieve` ar** 24 heksadecimālais jauktais nokopēts burtiski** lai atgūtu sākotnējo tekstu.                                                                                                    |
| `[dedup:ref sha=…]`                   | `session-dedup` elided teksts, kas jau nosūtīts tās pašas sesijas iepriekšējā pagriezienā. Tas ir an** tīšs atskats** , nevis zaudējumi vai kļūda. | Dariet** nē** piezvani uz jebkuru rīku un dari** nē** mēģināt to "rekonstruēt". Pirmā teksta sastopamība ir kanoniskā kopija; pašreizējais pagrieziens nekad netiek pārrakstīts, tas tiek noņemts vēlākā pagriezienā. |

`[dedup:ref]` atskats ir apzināts protokola lēmums, — nav rekonstrukcijas pirms nosūtīšanas. Uztveriet to kā "šis precīzs teksts jau bija pieejams iepriekš šajā sesijā".

### Klienta priekšnoteikumi

- **Atslēga (stdio):** stdio zvanītājam nav pieprasījuma identitātes, tāpēc tas tiek autentificēts ar `OMNIROUTE_API_KEY` (iestatīts MCP servera `env`). Bez tā zvanītājs ir anonīms, un rīki, kuriem nepieciešams galvenais, var pasliktināties.
- **`tools[]` ir injekcijas priekšnosacījums.** Tiek ievadīta CCR izguves protokola instrukcija (#8033).** tikai** kad pieprasījuma reklamētais `tools[]` pierāda, ka klients patiešām var sasniegt `omniroute_ccr_retrieve`. Atbilstība ir beigu segmenta atbilstība, ko ierobežo atdalītājs (`__`, `.`, `/`, `:`) — nekad nav tukša apakšvirkne — tāpēc nosaukums ar nosaukumiem, piemēram, `mcp__gateway__omniroute_ccr_retrieve` joprojām tiek ņemts vērā. Trūkstošs vai neatbilstošs `tools[]` nozīmē, ka instrukcija pēc konstrukcijas _nav_ ievadīta.
- **`codemode:false` (OpenCode klienti).** OpenCode noklusējuma iestatījums ir koda režīms, kas modelim reklamē tikai savus vietējos rīkus** nav** ievietojiet MCP rīkus vietējā `tools[]` sarakstā. Iestatiet `codemode: false` MCP servera ierakstā, lai tiktu reklamēti `omniroute_ccr_*` rīki. Šis ir a** klients** iestatījums, nevis OmniRoute. Tas vēl nesaņem CCR instrukciju: OpenCode nosauc rīku `<server>_<tool>`, tāpēc serveris ar nosaukumu `omniroute` atklāj `omniroute_omniroute_ccr_retrieve`, un `_` nav viens no saskaņotajiem atdalītājiem.
- **Direktori.** Uzglabāšana un izguve ir izolēti katram autentificētam principālam (katrai API atslēgai). Atslēga redz tikai savus blokus.

### Darbības apjoms katram instrumentam

Tvēruma izpilde vienmēr ir ieslēgta šauras darbības jomas HTTP/SSE zvanītājiem. `omniroute_` CCR rīkiem ir nepieciešams:

| Rīks                     | Darbības joma       |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Trūkstošais tvērums atgriež an**MCP instrumenta kļūdas rezultāts** (`isError: true`, nevis HTTP 403 — `403 LOCAL_ONLY` ir atsevišķa cilpas maršruta apsardzes autentifikācija): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimālā tālvadības atslēgā var būt `mcp:connect` (autorizē `/api/mcp/` lokālo izņemšanu) un tam nepieciešamo īpašo read/write tvērumu.

### Klientu matrica

| Klients            | Transports                                      | Lietošanas konfigurācija                                                                                                                                                                                                                                  | `tools[]` reklamēja? (injicēta → CCR instrukcija)                                                                                                                                             |
| ------------------ | ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kods        | straumējams-http                                | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                         | Jā — MCP spējīgs; injicēts.                                                                                                                                                                   |
| Cursor / Cline     | `stdio`** vai** `streamable-http`               | stdio: `omniroute --mcp` ar `OMNIROUTE_API_KEY` `env`; vai attālā MCP ievade, kas norāda uz `http://localhost:20128/api/mcp/stream` (skatiet [iestatīšanas rokasgrāmatu → MCP klienta konfigurācija](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Jā — reklamē `omniroute_ccr_*` rīkus.                                                                                                                                                         |
| OpenCode           | straumējams-http                                | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plus `codemode: false`                                                                                                                                                          | Rīki, kas reklamēti tikai ar `codemode: false`; instrukcija joprojām nav ievadīta, jo `omniroute_omniroute_ccr_retrieve` nesakrīt (skat. [Klienta priekšnosacījumi](#client-prerequisites) ). |
| Saderīgs ar OpenAI | Ar OpenAI saderīga HTTP (tērzēšanas pabeigšana) | standarta tērzēšanas pabeigšanas klients ar OpenAI saderīgu galapunktu                                                                                                                                                                                    | **Nekad** — vienkāršam ar OpenAI saderīgam zvanītājam nekad netiek likts izsaukt rīku, un instrukcija netiek ievadīta.                                                                        |

### Izguves ierobežojumi un lappušu skaits

MCP rīka teksta rezultāti tiek apgriezti ap `mcpAccessibility.maxTextChars` (noklusējuma `50000`). Bloka `full` izguves ierobežojums ir 256 KiB —** nav neierobežotas pilnas izgūšanas** . Ja bloka `chars=N` ir liels, lapējiet to, nevis velciet visu:

- Īkšķis:**`chars > 40000` → izmantojiet `mode`** , nekad kails pilns.
- `mode:"grep"` — regex `pattern` saskaņota rindiņa pa rindiņai, līdz 1000 atbilstošām rindiņām (`unique: true` drops atkārtojas), lētākais “atrast vienu man vajadzīgo rindiņu”.
- `mode:"lines"` — 1 indeksēta līniju diapazons; ir nepieciešams gan `start`, gan `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` līnijas.
- `mode:"stats"` — rindas, rakstzīmes un baiti tiek skaitīti bez pamatteksta.

Izmantojiet `mode:"lines"` ar `start`/`end`, lai izietu garu bloku lapās, nevis pieprasītu visu uzreiz.

### Instrumentu nosaukšana

Izgūšanas rīks pašlaik ir nosaukts `omniroute_ccr_retrieve` ( `omniroute_` prefikss ir datēts risinājums starpserveru nosaukumu sadursmēm). Tīrāks ierobežota sufiksa rīka nosaukums un labojums MCP JSON rezultātiem, kas ir saīsināti vidējā virknē, tiek izsekoti kā augšupējie turpinājumi; šī lapa dokumentē tikai pašreizējo, nosūtīto darbību.

### Sesijas dzīves cikls

Straumējamās HTTP sesijas ir dīkstāves, un serveris tās iegūst; dīkstāves logs ir `MCP_SESSION_IDLE_MS` konstante (nosaukta pēc nosaukuma, nevis cietā koda vērtība, tāpēc šī lapa nepārvietojas, kad tā mainās). Dīkstāves sesijas simptoms ir HTTP 404 ar `Unknown Mcp-Session-Id` — kā novērst sesijas atkārtotu pievienošanu vai restartēšanu,** nē** lai pagrieztu atslēgu, mainītu darbības jomu vai pārdēvētu rīku.

## API virsma

| Maršruts                               | Mērķis                                                              |
| -------------------------------------- | ------------------------------------------------------------------- |
| `/api/settings/compression`            | Globālie saspiešanas iestatījumi (ietver `mcpAccessibility` config) |
| `/api/compression/preview`             | Priekšskatiet jebkuru saspiešanas režīmu                            |
| `/api/compression/language-packs`      | Norādiet pieejamās Caveman valodu pakotnes                          |
| `/api/context/caveman/config`          | Alu cilvēka iestatījumu aizstājvārds                                |
| `/api/context/rtk/config`              | RTK noklusējuma iestatījumi un iestatījumi                          |
| `/api/context/rtk/filters`             | RTK filtru katalogs                                                 |
| `/api/context/rtk/test`                | RTK preview/test galapunkts                                         |
| `/api/context/rtk/raw-output/[id]`     | Autentificēta rediģēta neapstrādātas izvades atkopšana              |
| `/api/context/combos`                  | Kompresijas kombinācija CRUD                                        |
| `/api/context/combos/[id]/assignments` | Maršrutēšanas kombinācijas uzdevums CRUD                            |
| `/api/context/analytics`               | Kompresijas analīzes aizstājvārds                                   |

Pārvaldības maršrutiem ir nepieciešama pārvaldības autentifikācija vai API atslēgas politikas pārbaudes.

## MCP rīki

Saspiešana atklāj piecus MCP rīkus:

| Rīks                                | Darbības joma       | Mērķis                                      |
| ----------------------------------- | ------------------- | ------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Iestatījumi, analīze, kešatmiņas statistika |
| `omniroute_compression_configure`   | `write:compression` | Atjauniniet globālos iestatījumus           |
| `omniroute_set_compression_engine`  | `write:compression` | Iestatīt režīmu un papildu cauruļvadu       |
| `omniroute_list_compression_combos` | `read:compression`  | Saraksta saspiešanas kombinācijas           |
| `omniroute_compression_combo_stats` | `read:compression`  | Lasiet combo/engine analytics               |

## Darbības joma un izņēmumi

**Iegulumi nekad netiek saspiesti.** `open-sse/handlers/embeddings.ts` nekad nesauc nevienu kompresijas dzinēju — request/response korpusi neskarti nododas tieši izpildītājam. Mūsdienās tas ir strukturāls (iegulšanas un tērzēšanas pabeigšanas ir nesadalīti apstrādātāji), nevis izpildlaika pārbaude, taču tas nozīmē, ka vektoru kropļojuma problēmai #8034 iegulšanas ceļā nav ekspozīcijas virsmas.

**Per-model/endpoint izslēgšanas filtrs (#8034).** Tērzēšanas pabeigšanai operators var nosaukt modeļu ID/ `provider/model` mērķus, kurus nekad nedrīkst saspiest — aizsargmargas, kas ir noderīgas, ja saspiešana vēlāk tiek pietuvināta iegulšanai blakus esošajam ceļam, un parasti ir noderīga jebkuram modelim, kura precīza uzvedne par baitu ir svarīga (deterministiski evali, kešatmiņas jutīgi prefiksi utt.).

- Iestatījumu lauks: `exclusions?: string[]` globālajā saspiešanas konfigurācijā (`GET`/`PUT /api/settings/compression`), saglabājās, izmantojot esošo `key_value` saspiešanas nosaukumvietu (`src/lib/db/compression.ts`) — nav jaunas tabulas.
- Informācijas paneļa cilne:** Informācijas panelis → Kompresijas → izņēmumi** (`/dashboard/compression/exclusions`).
- Raksta sintakse: `*` ir vienīgā aizstājējzīme. Visas otrās regulārās izteiksmes metarakstzīmes modelī pirms atbilstības noteikšanas tiek izspiestas, tāpēc `gpt-5.6` atbilst tikai burtiskajai virknei, nekad `gpt-5x6` (ReDoS drošs, ierobežots, bez ligzdotiem kvantoriem). Raksti nejutīgi atbilst gan tukšajam modeļa ID, gan `provider/model` saliktajam — `gpt-5-6`, `openai/gpt-5-6` un `openai/*`, un tikai `*` izslēdz visus modeļus.
- Atbilstība: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` pārbauda izslēgto mērķi tūlīt pēc saspiešanas iestatījumu atrisināšanas,** pirms darbojas kāds dzinējs** , un apstrādā atbilstību tieši tā, kā saspiešana ir globāli atspējota — pieprasījuma pamatteksts, iespējams, ir identisks baitam. Izlaišana tiek reģistrēta, izmantojot `writeCompressionSkip(..., "excluded")` lai nodrošinātu analītikas redzamību.
- Noklusējums (empty/absent saraksts): identiska pirms-#8034 uzvedībai — nekas nav izslēgts.

## Zināmi ierobežojumi

- **LLMLingua-2 (SLM) ir nepieciešamas blakus esošās izvēles deps.** Darbinieks darbojas tikai ražošanas būvējumā, kad `@atjsh/llmlingua-2` + līdzinieki atrodas `dist/node_modules` (sk. `scripts/build/colocateOptionals.mjs`, #4286). Bez tiem dzinējs tiek atvērts (atgriež sākotnējo tekstu). Darbinieka izšķirtspēja vairs nav atkarīga no `import.meta.url` (tas nomirst savrupajā komplektā) — tas tiek noenkurots izpildlaikā cwd/ `argv[1]`.
- **Alu cilvēku valodu pakotnes `de` / `fr` / `ja` ir daļējas.** Viņi nosūta `context` + `filler` + `structural` noteikumus, bet ne `dedup` / `ultra` pakotnes, tāpēc `ultra` intensitāte nav spēcīgāka par `full` šīm valodām (tās izmanto tikai savus noteikumus — nav klusas atkāpšanās uz angļu valodas `dedup`/`ultra` ārzemju tekstu). `en` / `es` / `id` / `pt-BR` ir pabeigti. Tiek gaidīti `dedup.json` + `ultra.json` ieguldījumi daļējiem iepakojumiem.
- **Stacked telemetrija parāda tikai saspiestos dzinējus.** Stack-pipeline solis, kura dzinējs darbojās, bet radīja 0 % ietaupījumu, atgriež `stats:null` un tāpēc neparādās `engineBreakdown` — neatšķirams no soļa, kas tika izlaists. Lai atšķirtu "izskrējis, 0 %" no "izlaists", būtu jāmaina sadalījuma modelis, un tas tiek atliktas.

## Validācija

Koncentrētie vārti šai zonai ir:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
