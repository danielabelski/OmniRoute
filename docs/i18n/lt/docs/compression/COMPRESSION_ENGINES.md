# Compression Engines (Lietuvių)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompresija yra pagrįsta variklio sutartimis. Režimas gali tiesiogiai paleisti vieną variklį (`caveman` arba `rtk`) arba deterministinį sudėtinį dujotiekį, kuris eilės tvarka vykdo kelis variklius.

## Režimai

| Režimas      | Variklio kelias                                                                                          | Numatytas įvestis                                         |
| ------------ | -------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| `off`        | jokios                                                                                                   | Tikslus greitas konservavimas                             |
| `lite`       | Caveman Lite pagalbininkai                                                                               | Mažos rizikos nuolatinis valymas                          |
| `standard`   | Urvinis žmogus                                                                                           | Greitas kondensatas natūralia kalba                       |
| `aggressive` | Urvinio žmogaus + history/tool suvestinės                                                                | Ilgos pokalbių sesijos                                    |
| `ultra`      | Urvinio žmogaus + genėjimo pagalbininkai                                                                 | Konteksto apribojimo atkūrimas                            |
| `rtk`        | RTK                                                                                                      | Terminalas, apvalkalas, kūrimas, bandymas ir git išvestis |
| `omniglyph`  | OmniGlyph                                                                                                | Kontekstas kaip vaizdas vietiniame teikėjo laide          |
| `stacked`    | Dujotiekis. Numatytasis užklausos parametras yra `session-dedup -> lite`. `rtk -> caveman` pasirenkamas. | Mišrūs įrankių žurnalai ir proza, maksimaliai sutaupoma   |

### OmniGlyph suspaudimo profiliai

`omniglyph` variklis (paketas `omniglyph`, 1.4.0 +) priima įvardytą semantinį profilį, visame pasaulyje nustatytą per `omniglyph.profile` glaudinimo nustatymuose arba kiekvienam žingsniui per sudėtinio dujotiekio žingsnių konfigūraciją:

| Profilis      | Riba                                                                                                 |
| ------------- | ---------------------------------------------------------------------------------------------------- |
| `aggressive`  | Numatytoji. Paskelbtų kvitų politika matavo — vaizdų sistemą, įrankių dokumentus ir tankią istoriją  |
| `balanced`    | Išsaugo gyvą valstiją, saugo paskutinius 8 posūkius, sugriauna senesnę uždarą istoriją               |
| `coding-safe` | Išlaiko autoritetą, įrankių schemas ir tiesioginę įrankių išvestį, apsaugo paskutinius 12 apsisukimų |
| `passthrough` | Maršrutai be transformacijos; variklis praleidžiamas                                                 |

Profilis yra a** lubos, o ne grindys** : pakuotėje esantis `mergeCompressionProfileOptions` atsisako leisti skambinančiajam nepaisyti, kad būtų iš naujo atidaryta nuostolinga juosta, profilis uždarytas, todėl kiekvienam žingsniui `preserveSystemPrompt: false` negali iš naujo įjungti sistemos glaudinimo pagal `coding-safe`.

Matuojant pagal šią kodų bazę: `coding-safe` ir `balanced` padidina `minCompressChars` iki maksimumo ir išlaiko sistemos, įrankių schemų ir įrankių rezultatus natūralius, todėl seansas, kuris dar nesukaupė istorijos, sustoja ties `below_min_chars` ir variklis nieko nekeičia. Štai kodėl numatytasis yra `aggressive`, o ne saugiausias profilis.

Paketas išsprendžia savo modelio apimtį ir profilį pagal aplinkos konfigūraciją. OmniRoute niekada neperduoda sprendimo: adapteris prisega modelio vartus prie labiausiai ribojančios paketo apimties, todėl pagrindinio kompiuterio aplinkos parametrai gali tik susiaurinti leistinų sąrašą, niekada jo neišplėsti iki OmniRoute išmatuotų kvitų.

## Variklio registras

Registras gyvena `open-sse/services/compression/engines/registry.ts`. Varikliai sudaro bendrą sutartį:

- `id`: stabilus variklio ID, pvz. `caveman` arba `rtk`
- `apply(text, config)`: senas vykdymo kelias, naudojamas sukrautuose vamzdynuose
- `compress(input, config)`: pirminis vykdymo kelias, grąžinantis tekstą + statistika
- `getConfigSchema()`: grąžina į JSON schemą panašią galiojančios konfigūracijos formą
- `validateConfig(config)`: grąžina `{ valid, errors[] }`

Registruojantis naudojamas `registerCompressionEngine(engine)` (arba `registerEngine` išplėstiniams atvejams), kuris iškviečia `assertValidEngine()` ir `validateConfig(defaultConfig)` prieš priimant. Naudokite `unregisterCompressionEngine(id)`, kad pašalintumėte variklį veikimo metu.

`strategySelector.ts` registruoja įmontuotus variklius prieš pradedant suspaudimą. Tai leidžia peržiūrai, vykdymo laiko glaudinimui, sudėtiniam režimui, bandymams ir būsimiems varikliams naudoti tą patį vykdymo kelią.

### MCP aprašymo suspaudimas (susijęs)

Atskiras registras suglaudina MCP įrankio aprašo metaduomenis registro lygiu — žr. `open-sse/mcp-server/descriptionCompressor.ts` ir [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Jis pakartotinai naudoja „Caveman“ taisykles, bet naudoja įrankio metaduomenis, o ne prašo naudingų krovinių.

### Papildomi įmontuoti varikliai

Be „Caveman“, RTK ir LLMLingua-2, registre pateikiami keli specializuoti be nuostolių / struktūriniai varikliai (naudojami vamzdynuose, žaidimų aikštelėje ir bandymuose):

| Variklis      | Id              | Ką tai daro                                                                                                                                                                           |
| ------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR           | `ccr`           | Turinio suspaudimas ir gavimas (H4): pakeičia didelius gretimus teksto blokus į turinį adresuotomis nuorodomis, todėl repeated/large blokai siunčiami vieną kartą, o vėliau nurodomi. |
| aukštis       | `headroom`      | SmartCrusher (H3 + N5): vienarūšių JSON masyvo naudingųjų apkrovų lentelinis sutankinimas be nuostolių į stulpelinę `[N rows]` formą.                                                 |
| jonizatorius  | `ionizer`       | Head/middle/tail eilučių mėginių ėmimas labai dideliems vienarūšiams blokams, išsaugant elidinį vidurį kaip CCR turinį adresuotą nuorodą.                                             |
| session-dedup | `session-dedup` | Su turiniu susijęs kryžminio posūkio dubliavimo panaikinimas (įkvėptas „TokenMizer“): panaikina tekstą, jau matytą ankstesniuose tos pačios sesijos posūkiuose.                       |

**CCR atkūrimo protokolo instrukcija (#8033):** Kai pirmą kartą CCR užklausoje pakeičia ≥ 1 bloką, variklis pateikia vieną idempotentinį `system` pranešimą (pirmaujantis `[CCR protocol]` sentinel), mokydamas skambinantįjį žymeklį → įrankį susitarti: ką reiškia `[CCR retrieve hash=<24hex> chars=N]` žymeklis, kad maiša turi būti nukopijuota pažodžiui (visi 24 hex lock yra klaidingi simboliai) — nerasta“ praleidžia), o `[dedup:ref sha=...]` žymeklis reiškia „pažvelgti atgal į istoriją“, o ne „iškviesti įrankį“. Užrašas suleidžiamas** tik tada, kai skambinančiojo reklamuojamas `tools[]` įrodo, kad jis iš tikrųjų gali pasiekti `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — paprastas su OpenAI suderinamas skambintuvas be šio įrankio niekada negauna nurodymo paskambinti tam, ko jis negali pasiekti. Idempotencija užtikrinama nuskaitant sargybinio pranešimų istoriją prieš įvedant, todėl kelių posūkių užklausos (kurios atkuria ankstesnius pranešimus) nededa raštelio vieną kartą per ėjimą.

## Urvinis žmogus

Urvinio žmogaus režimas orientuotas į normalios prozos semantinį kondensavimą:

- išsaugo kodų blokus, URLs, JSON, kelius ir struktūrinius duomenis
- pašalina užpildą, apsidraudimą, pasikartojantį kontekstą ir daugžodžias jungiamąsias frazes
- palaiko kalbos žinią failų taisyklių paketus `open-sse/services/compression/rules/`
- išlieka pasiekiamas naudojant senus `standard`, `aggressive` ir `ultra` režimus

Prietaisų skydelio paviršius yra `Dashboard -> Context & Cache -> Caveman`.

Caveman prieš srovę praneša apie `~75%` mažiau išvesties žetonų, `65%` vidutinį išvesties sutaupymą `22-87%` diapazone ir `~46%` įvesties glaudinimo įrankį. OmniRoute naudoja „Caveman“ įvesties numerį, kai dokumentuoja sukauptas prompt/context santaupas; Urvinio žmogaus išvesties režimas išlieka atskira atsako elgesio funkcija.

## RTK

RTK režimas sutelktas į komandų ir įrankių išvestį:

- aptinka išvesties klases, tokias kaip `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testai, TypeScript/Vite/Webpack versijos, ESLint, npm audit/installs, Docker žurnalai, apvalkalas `find`/`grep`, dėklo pėdsakai ir bendrieji žurnalai
- Taiko 49 JSON filtrus iš `open-sse/services/compression/engines/rtk/filters/`
- palaiko RTK stiliaus deklaratyvųjį konvejerį: ANSI pašalinimas, keitimas, suderinimo išvesties trumpasis jungimas, strip/keep eilutės, eilutės sutrumpinimas, head/tail/max-line sutrumpinimas ir tuščias atsarginis
- palaiko patikimus projektų filtrus `.rtk/filters.json` ir pasaulinius filtrus `DATA_DIR/rtk/filters.json`
- pašalinamos ANSI sekos, progreso triukšmas, pasikartojančios eilutės ir nenaudinga generacija
- išsaugo veiksmingus gedimus, įspėjimus, santraukas, pakeistus failus ir uodegos kontekstą
- pasirinktinai gali išsaugoti redaguotą neapdorotą recovery/debugging išvestį per autentifikuotus valdymo maršrutus

Prietaisų skydelio paviršius yra `Dashboard -> Context & Cache -> RTK`.

Eksploatacinė informacija apie tinkintus filtrus, pasitikėjimą, patikrinimą ir neapdorotos išvesties atkūrimą veikia [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK prieš srovę praneša apie `60-90%` sutaupymus komandų išvesties glaudinimui. Jo README pavyzdyje parodyta 30 minučių Claude kodo sesija, pereinanti nuo `~118,000` žetonų iki `~23,900` arba `79.7%` išsaugoto.

## LLMLingua-2 (semantinis genėjimas)

LLMLingua-2 režimas veikia** semantinis žetonų genėjimas** apie prozą, naudojant mažą ONNX žetonų klasifikatorių, papildantį taisyklėmis pagrįstus Caveman ir RTK variklius:

- suspaudžia prozą tik nesisteminiuose pranešimuose; aptverti kodų blokai ir kitos išsaugotos konstrukcijos niekada nekeičiamos
- paleidžia `@atjsh/llmlingua-2` backend (ONNX per `@huggingface/transformers`) darbuotojo gijoje, todėl modelio išvada niekada neužblokuoja užklausos įvykio ciklo
- yra** galima sukrauti** (`stackPriority` 35): sukrautame konvejeryje jis veikia po struktūrinių variklių (CCR, session-dedup, headroom, Caveman), bet prieš `ultra`, nes semantinis genėjimas yra efektyviausias jau struktūriškai suglaudintam tekstui — pvz `rtk -> caveman -> llmlingua`
- **nesėkmingai atsidaro esant bet kokiai klaidai** (trūksta pasirenkamų deps, darbuotojo keitimo, modelio įkėlimo, išvados arba skirtojo laiko) → originalus tekstas grąžinamas nepakeistas, niekada nėra klaida

Variklio vieta: `open-sse/services/compression/engines/llmlingua/`. Prietaisų skydelio paviršius yra `Dashboard -> Context & Cache -> LLMLingua`.

### Modeliai

Numatytasis modelis yra**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, greitas ). Didesnis tikslumas** BERT bazė** modelis (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) pasiekiamas variklio konfigūracijos `model` lauke. `@huggingface/transformers` tingiai atsisiunčia pasirinktą modelį iš HuggingFace Hub į `${DATA_DIR}/models/llmlingua` pirmojo skambučio metu (`modelStore.ts`); `modelPath` konfigūracijos nepaisymas nukreipia jį į vietinę kopiją (diegimai neprisijungus / su oro tarpais).

### Pasirenkamos priklausomybės ir diegimas pagal pareikalavimą

Apkarpomas LLMLingua vykdymo laiko lygiavertis dėklas yra** neprivaloma** . Dvi pakuotės `optionalDependencies` deklaruojamos kaip `package.json` ir saugomos** išorės** pagal gamybos versiją (`scripts/build/prepublish.ts` jų nesujungia):

| Paketas              | Versija (smeigtukas) | Pastabos                                    |
| -------------------- | -------------------- | ------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`              | Įėjimo paketas; kitus skelbia bendraamžiais |
| `js-tiktoken`        | `^1.0.20`            | Tokenizatorius                              |

`@huggingface/transformers` prisegtas prie `^4.2.0` (bendrinamas su vietiniu įterpimo keliu ir taip pat atsekamas į atskirą rinkinį); `@atjsh/llmlingua-2@2.0.5` bendradarbiauja su `"^3.5.2 || ^4.0.0"`, todėl palaikomi ir Transformers.js v3, ir v4. Nuo 2.0.4 versijos `@atjsh/llmlingua-2` nebereikalauja `@tensorflow/tfjs`, todėl iš SLM krūvos buvo pašalintas didžiausias bendraautoris (TensorFlow.js). Tik du aukščiau pateikti paketai yra genėti SLM. Standartinis `npm install` (dev) pasirenkamą krūvą įdiegia automatiškai, nebent būtų praleistos pasirenkamos priklausomybės.

**Kodėl pagal pareikalavimą:** npm paskelbtas paketas, atskiras paketas ir Docker vaizdo siuntimas** be** šie deps išlikti liekni. Kai jų nėra, sugenda darbuotojo priklausomybės vartai ( `@atjsh/llmlingua-2` sprendimo zondas `worker.ts`) ir variklis** nesėkmingai atsidaro tyliai** — pasirinkus LLMLingua tampa ne-oper (tekstas grąžinamas nepakeistas, klaida neužregistruota). Norėdami suaktyvinti jį apkarpytoje aplinkoje, įdiekite pasirenkamą krūvą:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Pašalinus `@tensorflow/tfjs` (2.0.4 +), pašalinamas anksčiau dominavęs ~ 800 MB bendradarbis — likęs pėdsakas yra transformers.js + onnxruntime-node vykdymo laikas ir TinyBERT modelis (~ 57 MB), atsisiųstas pirmą kartą naudojant (ne per npm).

Pagal aplinką:

- **Kūrėjas / `npm install`** — įdiegiamas automatiškai, nebent išlaikėte `--omit=optional` (arba `--no-optional`). Nereikia jokių veiksmų.
- **Visuotinis npm (`npm i -g omniroute`) / atskiras** — paleiskite aukščiau esančią diegimo komandą įdiegtų paketų kataloge arba įdiekite iš naujo, nepraleisdami pasirenkamų deps.
- **Docker** — pridėkite diegimo komandą išvestiniame vaizdo sluoksnyje; paskelbtas vaizdas yra plonas pagal dizainą.
- **VPS (PM2)** — įdiekite į programos `node_modules`, tada paleiskite procesą iš naujo, kad darbuotojas iš naujo patikrintų vartus.
- **Atskiras „Raw Next“ (`npm run build` → `.build/next/standalone/server.js`)** — atskiri sekimo laivai NEITHER darbuotojo nei pasirenkami deps, todėl variklis tyliai atsidaro. `scripts/build/colocate-standalone.mjs` iš naujo pritaiko abu (darbuotojas įrengia + pasirenkamąjį-dep uždarymą į atskirą medį); jis veikia automatiškai per `postbuild` npm kabliuką po kiekvieno kūrimo. Idempotentas, atsparus nesėkmėms, kai nėra dep.

**Patikrinkite, ar jis aktyvus:** Pasirinkus LLMLingua, tikroji proza iš tikrųjų susitraukia (variklis nustoja atsidaryti), o pirmoji užklausa suaktyvina modelio atsisiuntimą į `${DATA_DIR}/models/llmlingua`. Vartai tyčia tikrina tik `@atjsh/llmlingua-2` — kiti bendraamžiai yra tik ESM ir `require.resolve` meta juos net tada, kai yra — todėl darbuotojas vis tiek atsidaro nesėkmingai, jei `import()` metu kurio nors bendraamžio tikrai trūksta.

## Sukrauti vamzdynai

Stacked režimu dujotiekio žingsniai vykdomi eilės tvarka. Numatytasis yra:

```txt
rtk -> caveman
```

Naudokite tai kodavimo agento seansams, kai eilutė sujungia komandų išvestį su žmogaus ar asistento proza. RTK pirmiausia sumažina triukšmingus įrankių žurnalus, tada Caveman suspaudžia likusią natūralią kalbą.

Dujotiekio žingsniai sukonfigūruojami naudojant `stackedPipeline` glaudinimo nustatymuose arba naudojant glaudinimo derinius.

Kai abu varikliai sumažina tą pačią tinkamą naudingąją apkrovą, sutaupoma:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP pritaikymo neįgaliesiems medžio filtras

MCP pritaikymo neįgaliesiems medžio išmanusis filtras yra glaudinimo sluoksnis po vykdymo, kuris veikia MCP** įrankio rezultatai** , ne pagal raginimus ar kontekstą. Tai taikoma išsamiam pritaikymo neįgaliesiems medžio ir naršyklės momentinių kopijų naudingosioms apkrovoms, kurias grąžina tokie įrankiai kaip Playwright, kompiuterio naudojimas ir naršyklės automatizavimo MCP serveriai.

### Ką tai daro

1. **Triukšmo šalinimas** — pašalina tuščius generic/text įrašus (`- generic:`, `- text: ""`)
2. **Brolių žlugimas** — kai ≥ `collapseThreshold` (numatytasis 30) iš eilės eilučių kartojasi, sutraukia jas į pirmąsias `collapseKeepHead` (numatytasis 10) eilutes + skaičiavimo suvestinė + paskutines `collapseKeepTail` (numatytosios 5) eilutes
3. **Ref išsaugojimas** — `[ref=eXX]` inkarai, kurių reikalauja Playwright/computer-use, niekada neliečiami
4. **Sunkus sutrumpinimas** — jei tekstas po sutraukimo vis tiek viršija `maxTextChars` (numatytasis 50 000), sutrumpinamas su naršymo užuomina, kad agentas galėtų tęsti darbą

### Variklio vieta

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfigūracija

Valdo `compression.mcpAccessibility` visuotiniuose nustatymuose (migracija 056). Numatytoji konfigūracija:

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

Filtras taikomas tik įrankio rezultatų naudingosioms apkrovoms, kurių `type` yra `"text"` ir kurių ilgis viršija `minLengthToProcess`. Tai neturi įtakos greitam suspaudimui ar užklausoms naudingoms apkrovoms.

### Tikimasi sutaupyti

60–80 % naršyklės momentinių nuotraukų įrankio rezultatų, atsižvelgiant į puslapio sudėtingumą. Sutraukimo algoritmas yra O(n) eilučių skaičiuje ir prideda nereikšmingą delsą.

### Šis filtras palyginti su aukščiau esančiais suspaudimo varikliais

| Aspektas       | Urvinis žmogus / RTK / Sukrautas | MCP prieinamumo filtras                |
| -------------- | -------------------------------- | -------------------------------------- |
| Tikslas        | Užklausos raginimai / kontekstas | MCP įrankio rezultatai                 |
| Trigeris       | Suspaudimo režimo nustatymas     | `compression.mcpAccessibility.enabled` |
| Taikymo sritis | Visi SSE pranešimai              | Tik įrankių rezultatai                 |
| Ref inkarai    | N/A                              | Saugomas besąlygiškai                  |

---

## Suspaudimo deriniai

Suspaudimo deriniai yra pavadinti glaudinimo profiliais, kuriuos galima priskirti maršruto deriniams:

- `compression_combos`: saugojimo režimas, vamzdynas, RTK konfigūracija, kalbos konfigūracija ir numatytasis žymeklis
- `compression_combo_assignments`: susieja glaudinimo derinį su maršruto parinkimo deriniu
- vykdymo laiko integracija išsprendžia priskirtą glaudinimo kombinaciją prieš nepaisant bendrojo derinio
- analitika apima `compression_combo_id` ir `engine`

Prietaisų skydelio paviršius: `Dashboard -> Context & Cache -> Compression Combos`.

## Būtinos sąlygos / operatoriaus vadovas (CCR & session-dedup)

CCR (`ccr`) ir `session-dedup` pakeiskite arba panaikinkite tekstą ir palikite a** žymeklis** už nugaros. Šis skyrius yra operatoriaus nuoroda, kaip prijungti klientą, nuskaityti du žymeklius ir nuskaityti arba diagnozuoti pašalintą turinį. Kiekvieno variklio mechanika aprašyta aukščiau; tai sluoksnis „kaip man tai paleisti“.

### Transportas ir galutiniai taškai

MCP serverį, kuris atskleidžia „ CCR įrankius, galima pasiekti trimis būdais. Numatytoji bazė URL yra `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transportas                              | URL / komanda                           | Pastabos                                                                                                                                         |
| ---------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Srautinė HTTP (klientas, rekomenduojama) | `http://localhost:20128/api/mcp/stream` | Galutinis taškas, su kuriuo kalba dabartiniai MCP klientai.                                                                                      |
| Senas SSE vienvietis                     | `http://localhost:20128/api/mcp/sse`    | Senesnis vienvietis transportas. Tai** užsidaro** transliuojamos sesijos; naudokite `streamable-http` klientus prieš `/api/mcp/stream`, o ne šį. |
| stdio                                    | `omniroute --mcp`                       | IDE MCP konfigūracijai, kuri sukelia procesą. Nėra `--dev` vėliavos; `omniroute --mcp` yra stdio įėjimo taškas.                                  |

### Saugyklos pakopos (kas išgyvena paleidus iš naujo)

CCR yra a** dviejų pakopų** parduotuvėje, ne tik atmintyje:

- **Karšta atminties pakopa** — bloko dangtelis 2 MiB, vienas pagrindinis 16 MiB, pasaulinis 64 MiB. Įrašai pagal numatytuosius nustatymus yra 24 h TTL (daugiausia 7 dienos). Visas MCP gavimas iš atminties yra apribotas iki 256 KiB; bet kas didesnis vis tiek pasiekiamas naudojant diapazono / grep režimus.
- **Patvari SQLite pakopa** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, įjungta pagal numatytuosius nustatymus) — palaiko atmintyje esančią pakopą, todėl blokas išgyvena LRU iškeldinimą, paleidimą iš naujo arba gavimo nukreipimą į kitą egzempliorių. Eilėje išlaikomas bloko TTL, todėl blokas, esantis už jo TTL dingsta iš abiejų pakopų.

Trys apsaugos apsaugo patvarią pakopą apribotą — blokas lieka tik atmintyje, kai:

1. blokas baigėsi** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. vykdymo laikas yra debesies vykdymo laikas (nėra vietinio disko);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Taigi „blokas dingo“ nėra visapusiška iš naujo paleidimo istorija: sub-512 KB blokas vietinėje, ne debesų vykdymo aplinkoje, išlaiko paleidimą iš naujo per patvarią pakopą, kol baigiasi jo TTL. Žr. [Aplinkos nuorodą](../reference/ENVIRONMENT.md) apie kintamąjį.

### Du žymekliai

| Žymeklis                              | Reikšmė                                                                                                                                                  | Ką turėtų daryti modelis                                                                                                                                                                                              |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Didelis blokas buvo saugomas pagal turinį.                                                                                                               | Paskambinkite `omniroute_ccr_retrieve` su** 24 šešioliktainė maiša nukopijuota pažodžiui** kad atgautumėte originalų tekstą.                                                                                          |
| `[dedup:ref sha=…]`                   | `session-dedup` elided tekstas jau išsiųstas ankstesniame tos pačios sesijos eigoje. Tai yra an** tyčinis žvilgsnis atgal** , o ne praradimas ar klaida. | Daryk** ne** paskambink bet kokiam įrankiui ir padaryk** ne** pabandyk tai „rekonstruoti“. Pirmasis teksto atvejis yra kanoninė kopija; dabartinis posūkis niekada neperrašomas, jis pašalinamas vėlesniame posūkyje. |

`[dedup:ref]` peržiūra yra apgalvotas protokolinis sprendimas, — nėra rekonstrukcijos prieš siuntimą. Laikykite tai kaip „šis tikslus tekstas jau buvo paskelbtas anksčiau šios sesijos metu“.

### Būtinos sąlygos klientui

- **Raktas (stdio):** stdio skambinantysis neturi užklausos tapatybės, todėl jis autentifikuojamas naudojant `OMNIROUTE_API_KEY` (nustatytas MCP serverio `env`). Be jo skambinantysis yra anoniminis, o įrankiai, kuriems reikia vadovo, gali susilpnėti.
- **`tools[]` yra išankstinė injekcijos sąlyga.** Įvedama CCR retrieve-protocol instrukcija (#8033).** tik** kai užklausos reklamuojamas `tools[]` įrodo, kad klientas iš tikrųjų gali pasiekti `omniroute_ccr_retrieve`. Atitiktis yra paskutinio segmento atitikmuo, apribotas skyrikliu (`__`, `.`, `/`, `:`) — niekada nėra tuščios poeilutės — todėl pavadinimas su vardų erdve, pvz. `mcp__gateway__omniroute_ccr_retrieve` vis tiek skaičiuojamas. Jei `tools[]` nėra arba jis neatitinka, tai reiškia, kad instrukcija _neįšvirkščiama pagal dizainą.
- **`codemode:false` (OpenCode klientai).** OpenCode numatytasis kodo režimas, kuris reklamuoja tik savo įrankius modeliui ir** ne** įtraukite MCP įrankius į vietinį `tools[]` sąrašą. Nustatykite `codemode: false` MCP serverio įraše, kad būtų reklamuojami `omniroute_ccr_*` įrankiai. Tai yra a** klientas** nustatymas, o ne OmniRoute. Jame dar nėra įvesta CCR instrukcijos: OpenCode įrankį pavadina `<server>_<tool>`, todėl serveris, vadinamas `omniroute` atskleidžia `omniroute_omniroute_ccr_retrieve`, o `_` nėra vienas iš suderintų separatorių.
- **Direktoriai.** Saugojimas ir gavimas yra atskirti pagal autentifikuotą pagrindinį (už API raktą). Raktas mato tik savo blokus.

### Taikymo sritis pagal įrankį

Apimties užtikrinimas visada įjungtas siauros apimties HTTP/SSE skambintojams. `omniroute_` CCR įrankiams reikia:

| Įrankis                  | Taikymo sritis      |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Trūksta apimtis grąžina an**MCP įrankio klaidos rezultatas** (`isError: true`, o ne HTTP 403 — `403 LOCAL_ONLY` yra atskiras atgalinio maršruto apsaugos autentifikavimas): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimaliame nuotolinio valdymo mygtuke gali būti `mcp:connect` (įgalioja `/api/mcp/` tik vietinį iškirpimą) ir specifinę read/write sritį, kurios jam reikia.

### Kliento matrica

| Klientas              | Transportas                                      | Konfigūracija naudoti                                                                                                                                                                                                                           | `tools[]` reklamavosi? (suleidžiama → CCR instrukcija)                                                                                                                              |
| --------------------- | ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kodas          | transliuojamas - http                            | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                               | Taip — MCP; suleisti.                                                                                                                                                               |
| Cursor / Cline        | `stdio`** arba** `streamable-http`               | stdio: `omniroute --mcp` su `OMNIROUTE_API_KEY` `env`; arba nuotolinis MCP įrašas, nukreiptas į `http://localhost:20128/api/mcp/stream` (žr. [sąrankos vadovą → MCP kliento konfigūracija](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Taip, — reklamuoja `omniroute_ccr_*` įrankius.                                                                                                                                      |
| OpenCode              | transliuojamas - http                            | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plius `codemode: false`                                                                                                                                               | Įrankiai reklamuojami tik su `codemode: false`; instrukcija vis tiek neįvesta, nes `omniroute_omniroute_ccr_retrieve` nesutampa (žr. [Kliento prielaidos](#client-prerequisites) ). |
| Suderinamas su OpenAI | Su OpenAI suderinamas HTTP (pokalbių užbaigimai) | standartinis pokalbių užbaigimo klientas su OpenAI suderinamu galutiniu tašku                                                                                                                                                                   | **Niekada** — paprastam su OpenAI suderinamam skambinančiajam niekada nesakoma skambinti į įrankį, o instrukcija neįvedama.                                                         |

### Paieškos ribos ir puslapių skaičius

MCP įrankio teksto rezultatai iškirpti aplink `mcpAccessibility.maxTextChars` (numatytasis `50000`). Bloko `full` gavimas yra 256 KiB —** nėra neapriboto pilno atkūrimo** . Kai bloko `chars=N` yra didelis, perbraukite jį, o ne traukite visą:

- Nykščio taisyklė:**`chars > 40000` → naudokite `mode`** , niekada plikas pilnas.
- `mode:"grep"` — regex `pattern` atitinka eilutę po eilutės, iki 1 000 atitinkančių eilučių (`unique: true` drops pasikartoja), pigiausia už „rasti vieną man reikalingą eilutę“.
- `mode:"lines"` — 1 indeksuotų linijų diapazonas; reikia ir `start`, ir `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` linijos.
- `mode:"stats"` — eilutės, simboliai ir baitai skaičiuojami be kūno.

Naudokite `mode:"lines"` su `start`/`end`, jei norite nueiti ilgą puslapių bloką, o ne prašyti viso iš karto.

### Įrankio įvardijimas

Šiuo metu gavimo įrankis pavadintas `omniroute_ccr_retrieve` (priešdėlis `omniroute_` yra pasenęs kelių serverių pavadinimų susidūrimų sprendimas). Švaresnis apribotos priesagos įrankio pavadinimas ir MCP JSON rezultatų sutrumpintos eilutės vidurio pataisa stebimi kaip tolesni veiksmai; šiame puslapyje dokumentuojama tik dabartinė siuntimo elgsena.

### Sesijos gyvavimo ciklas

Streamable-HTTP sesijos neveikia ir serveris jas naudoja; tuščiosios eigos langas yra `MCP_SESSION_IDLE_MS` konstanta (nurodyta pavadinimu, o ne užkoduota reikšmė, todėl šis puslapis nejuda, kai jis keičiasi). Nenaudojamo seanso požymis yra HTTP 404 su `Unknown Mcp-Session-Id` — Ištaisyti galima iš naujo prisijungti arba paleisti seansą iš naujo,** ne** norėdami pasukti raktą, pakeisti taikymo sritį arba pervardyti įrankį.

## API paviršius

| Maršrutas                              | Tikslas                                                                        |
| -------------------------------------- | ------------------------------------------------------------------------------ |
| `/api/settings/compression`            | Visuotiniai glaudinimo nustatymai (įskaitant `mcpAccessibility` konfigūraciją) |
| `/api/compression/preview`             | Peržiūrėkite bet kurį suspaudimo režimą                                        |
| `/api/compression/language-packs`      | Išvardykite galimus „Caveman“ kalbos paketus                                   |
| `/api/context/caveman/config`          | Urvinio žmogaus nustatymų slapyvardis                                          |
| `/api/context/rtk/config`              | RTK numatytieji nustatymai ir nustatymai                                       |
| `/api/context/rtk/filters`             | RTK filtrų katalogas                                                           |
| `/api/context/rtk/test`                | RTK preview/test galutinis taškas                                              |
| `/api/context/rtk/raw-output/[id]`     | Autentifikuotas redaguotas neapdorotos išvesties atkūrimas                     |
| `/api/context/combos`                  | Kompresijos kombinacija CRUD                                                   |
| `/api/context/combos/[id]/assignments` | Maršruto parinkimo derinio priskyrimas CRUD                                    |
| `/api/context/analytics`               | Suspaudimo analizės slapyvardis                                                |

Valdymo maršrutams reikalingas valdymo autentifikavimas arba API rakto politikos patikros.

## MCP įrankiai

Suspaudimas atskleidžia penkis MCP įrankius:

| Įrankis                             | Taikymo sritis      | Tikslas                                     |
| ----------------------------------- | ------------------- | ------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Nustatymai, analizė, talpyklos statistika   |
| `omniroute_compression_configure`   | `write:compression` | Atnaujinkite visuotinius nustatymus         |
| `omniroute_set_compression_engine`  | `write:compression` | Nustatykite režimą ir pasirenkamą dujotiekį |
| `omniroute_list_compression_combos` | `read:compression`  | Išvardykite glaudinimo derinius             |
| `omniroute_compression_combo_stats` | `read:compression`  | Skaitykite combo/engine analytics           |

## Taikymo sritis ir išimtys

**Įterpimai niekada nėra suspausti.** `open-sse/handlers/embeddings.ts` niekada nevadina jokio suspaudimo variklio — request/response kūnai perduodami tiesiai į vykdytoją nepaliesti. Šiandien tai yra struktūrinė (įterpimai ir pokalbių užbaigimai yra atskirtos tvarkyklės), o ne vykdymo laiko patikra, bet tai reiškia, kad #8034 vektorinio iškraipymo problema įterpimo kelyje neturi poveikio.

**Per-model/endpoint išskyrimo filtras (#8034).** Užbaigdamas pokalbį, operatorius gali pavadinti modelio ID / `provider/model` tikslus, kurių niekada negalima suspausti — apsauginis turėklas, naudingas, jei vėliau glaudinimas yra arčiau įterpimo kelio, ir paprastai naudingas bet kokiam modeliui, kurio tikslus baitas po baito eilutės yra svarbios (deterministiniai įvertinimai, talpyklos jautrūs priešdėliai ir kt.).

- Nustatymų laukas: `exclusions?: string[]` visuotinėje glaudinimo konfigūracijoje (`GET`/`PUT /api/settings/compression`), išliko per esamą `key_value` glaudinimo vardų sritį (`src/lib/db/compression.ts`) — naujos lentelės.
- Prietaisų skydelio skirtukas:** Prietaisų skydelis → Suspaudimas → Išimtys** (`/dashboard/compression/exclusions`).
- Šablono sintaksė: `*` yra vienintelis pakaitos simbolis. Kiekvienas kitas reguliariojo reiškinio metasimbolis šablone prieš derinimą pašalinamas, todėl `gpt-5.6` atitinka tik pažodinę eilutę, niekada netinka `gpt-5x6` (saugus ReDoS, ribotas, nėra įdėtųjų kvantiklių). Šablonai nejautrus didžiosioms ir mažosioms raidėms atitinka tiek pliko modelio ID, tiek `provider/model` sudėtinį — `gpt-5-6`, `openai/gpt-5-6` ir `openai/*`, o vien `*` neįtraukia visų modelių.
- Atitikimas: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` patikrina neįtrauktą taikinį iškart po to, kai išsprendžia glaudinimo nustatymus,** prieš paleidžiant bet kokį variklį** , ir atitiktį traktuoja lygiai taip, kaip glaudinimas yra visuotinai išjungtas — užklausos turinys yra įrodyta, kad baitas yra identiškas. Praleidimas įrašomas per `writeCompressionSkip(..., "excluded")`, kad būtų galima matyti analizę.
- Numatytasis (empty/absent sąrašas ): identiškas prieš #8034 elgsenai — nieko neišskiriama.

## Žinomi apribojimai

- **LLMLingua-2 (SLM) reikalauja kartu esančių pasirenkamų deps.** Darbuotojas veikia tik gamybinėje versijoje, kai `@atjsh/llmlingua-2` + bendraamžiai yra `dist/node_modules` (žr. `scripts/build/colocateOptionals.mjs`, #4286). Be jų variklis atsidaro (grąžina originalų tekstą). Darbuotojo skiriamoji geba nebepriklauso nuo `import.meta.url` (ji miršta atskirame pakete) — ji pritvirtinama prie vykdymo laiko cwd / `argv[1]`.
- **Caveman kalbos paketai `de` / `fr` / `ja` yra daliniai.** Jie siunčia `context` + `filler` + `structural` taisykles, bet ne `dedup` / `ultra` paketus, todėl toms kalboms `ultra` intensyvumas nėra stipresnis nei `full` (jie naudoja tik savo taisykles — nėra tylaus grįžimo prie anglų kalbos `dedup`/`ultra` užsienio teksto). `en` / `es` / `id` / `pt-BR` yra baigti. Laukiame `dedup.json` + `ultra.json` indėlių į dalines pakuotes.
- **Sukrautoje telemetrijoje pateikiami tik suspausti varikliai.** Sudėtinio vamzdyno žingsnis, kurio variklis veikė, bet sutaupė 0 %, grąžina `stats:null`, todėl `engineBreakdown` — neatsiranda taip, kad būtų galima atskirti nuo žingsnio, kuris buvo praleistas. Norint atskirti „paleista, 0 %“ nuo „praleista“, reikėtų pakeisti suskirstymo modelį ir tai atidedama.

## Patvirtinimas

Šios srities vartai yra šie:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
