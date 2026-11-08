# Compression Engines (Hrvatski)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompresija je izgrađena oko ugovora motora. Način može pokrenuti jedan motor izravno (`caveman` ili `rtk`) ili deterministički naslagani cjevovod koji izvršava više motora redom.

## Načini rada

| Način rada   | Put motora                                                                       | Predviđeni unos                                      |
| ------------ | -------------------------------------------------------------------------------- | ---------------------------------------------------- |
| `off`        | nikakav                                                                          | Točno brzo očuvanje                                  |
| `lite`       | Caveman lite pomoćnici                                                           | Čišćenje s niskim rizikom koje je uvijek uključeno   |
| `standard`   | Pećinski čovjek                                                                  | Brza kondenzacija prirodnog jezika                   |
| `aggressive` | Caveman + history/tool sažetci                                                   | Duge sesije razgovora                                |
| `ultra`      | Caveman + pomoćnici u rezidbi                                                    | Oporavak ograničenja konteksta                       |
| `rtk`        | RTK                                                                              | Terminal, shell, build, test i git izlaz             |
| `omniglyph`  | OmniGlyph                                                                        | Kontekst kao slika na žici izvornog davatelja usluga |
| `stacked`    | Cjevovod. Zadani zahtjev je `session-dedup -> lite`. `rtk -> caveman` je opt-in. | Mješoviti zapisi alata i proza, maksimalne uštede    |

### OmniGlyph profili kompresije

`omniglyph` motor (paket `omniglyph`, 1.4.0 +) prihvaća imenovani semantički profil, postavljen globalno kroz `omniglyph.profile` u postavkama kompresije ili po koraku kroz konfiguraciju koraka naslaganog cjevovoda:

| Profil        | Granica                                                                                        |
| ------------- | ---------------------------------------------------------------------------------------------- |
| `aggressive`  | Zadano. Politika objavljenih računa mjeri — sustav slika, dokumentaciju alata i gustu povijest |
| `balanced`    | Održava izvorno stanje uživo, štiti zadnjih 8 poteza, urušava stariju zatvorenu povijest       |
| `coding-safe` | Održava autoritet, sheme alata i izlaz alata uživo, štiti zadnjih 12 okretaja                  |
| `passthrough` | Rute bez transformacije; motor je preskočen                                                    |

Profil je a** strop, a ne pod** : `mergeCompressionProfileOptions` u paketu odbija dopustiti pozivatelju da premosti ponovno otvaranje trake s gubicima profil zatvoren, tako da `preserveSystemPrompt: false` po koraku ne može ponovno omogućiti kompresiju sustava pod `coding-safe`.

Mjereno na ovoj bazi kodova: `coding-safe` i `balanced` podižu `minCompressChars` do svog maksimuma i zadržavaju izvorne sustav, sheme alata i rezultate alata, tako da sesija koja još nije akumulirala povijest zaustavlja na `below_min_chars` i motor ne transformira ništa. Zato je zadana vrijednost `aggressive`, a ne najsigurniji profil.

Paket rješava vlastiti opseg modela i profil iz svoje konfiguracije okruženja. OmniRoute nikada ne delegira odluku: adapter pričvršćuje vrata modela na najrestriktivniji opseg paketa, tako da postavke okruženja glavnog računala mogu samo suziti popis dopuštenih, nikad ga proširiti izvan OmniRoute-ovih izmjerenih primitaka.

## Registar motora

Registar živi u `open-sse/services/compression/engines/registry.ts`. Motori izlažu zajednički ugovor:

- `id`: ID stabilnog motora kao što je `caveman` ili `rtk`
- `apply(text, config)`: naslijeđeni put izvršenja koji koriste naslagani cjevovodi
- `compress(input, config)`: primarni put izvršavanja koji vraća tekst + statistike
- `getConfigSchema()`: vraća oblik valjane konfiguracije sličan JSON-shemi
- `validateConfig(config)`: vraća `{ valid, errors[] }`

Registracija koristi `registerCompressionEngine(engine)` (ili `registerEngine` za napredne slučajeve), koji poziva `assertValidEngine()` i `validateConfig(defaultConfig)` prije prihvaćanja. Koristite `unregisterCompressionEngine(id)` za uklanjanje motora tijekom izvođenja.

`strategySelector.ts` registrira ugrađene motore prije pokretanja kompresije. To omogućuje pregled, kompresiju vremena izvođenja, složeni način rada, testove i buduće motore koji koriste isti put izvršenja.

### MCP kompresija opisa (povezano)

Odvojeni registar sažima metapodatke opisa MCP alata na razini registra — pogledajte `open-sse/mcp-server/descriptionCompressor.ts` i [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Ponovno koristi pravila Cavemana, ali radi na metapodacima alata, a ne na zahtjevima.

### Dodatni ugrađeni motori

Osim Cavemana, RTK i LLMLingua-2, registar isporučuje nekoliko specijaliziranih bez gubitaka / strukturnih motora (koje koriste naslagani cjevovodi, igralište i testovi):

| Motor            | Id              | Što radi                                                                                                                                                                                         |
| ---------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CCR              | `ccr`           | Content-Compress-Retrieve (H4): zamjenjuje velike kontinuirane tekstualne blokove referencama adresiranim na sadržaj, tako da se repeated/large blokovi šalju jednom i referenciraju nakon toga. |
| prostor za glavu | `headroom`      | SmartCrusher (H3 + N5): tablično sažimanje bez gubitaka korisnih opterećenja homogenog JSON polja u stupčasti `[N rows]` oblik.                                                                  |
| ionizator        | `ionizer`       | Head/middle/tail uzorkovanje redaka za vrlo velike homogene blokove, pohranjivanje elidirane sredine kao CCR reference adresirane na sadržaj.                                                    |
| sesija-dedup     | `session-dedup` | Deduplikacija unakrsnog zaokreta usmjerena na sadržaj (nadahnuto TokenMizerom): uklanja tekst koji je već viđen u ranijim zaokretima iste sesije.                                                |

**CCR instrukcija protokola dohvaćanja (#8033):** prvi put kada CCR zamijeni ≥ 1 blok u zahtjevu, motor ispred jedne, idempotentne `system` poruke (na čelu sa `[CCR protocol]` sentinelom) poučava pozivatelja markeru ugovor → alata: što `[CCR retrieve hash=<24hex> chars=N]` marker znači, da se hash mora kopirati doslovce (sva 24 heksadecimalna znaka — krivo kopirani hashovi su vjerojatni uzrok promašaja "blok nije pronađen"), i da oznaka `[dedup:ref sha=...]` znači "pogledaj u prošlost", a ne "pozovi alat". Bilješka je ubrizgana** samo kada oglašeni `tools[]` pozivatelja dokaže da zapravo može doseći `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` u `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — običan OpenAI-kompatibilan pozivatelj bez tog alata nikada ne prima instrukcije da pozove nešto što ne može dosegnuti. Idempotencija se provodi skeniranjem povijesti poruka za stražara prije ubacivanja, tako da višestruki zahtjevi (koji ponavljaju prethodne poruke) ne slažu bilješku jednom po potezu.

## Pećinski čovjek

Način Caveman fokusiran je na semantičku kondenzaciju normalne proze:

- čuva blokove koda, URLs, JSON, staze i strukturirane podatke
- uklanja dopunu, zaštitu, ponovljeni kontekst i opširno vezivno fraziranje
- podržava pakete pravila za datoteke s obzirom na jezik u `open-sse/services/compression/rules/`
- ostaje dostupan putem naslijeđenih načina rada `standard`, `aggressive` i `ultra`

Površina armaturne ploče je `Dashboard -> Context & Cache -> Caveman`.

Caveman uzvodno izvještava `~75%` manje izlaznih tokena, `65%` prosječnim uštedama izlaza u referentnim vrijednostima sa `22-87%` rasponom i `~46%` alatom za kompresiju unosa. OmniRoute koristi Caveman broj ulazne strane kada dokumentira naslagane prompt/context uštede; Način izlaza Caveman ostaje zasebna značajka ponašanja odgovora.

## RTK

RTK način rada fokusiran je na izlaz naredbi i alata:

- otkriva izlazne klase kao što su `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testovi, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker zapisnici, shell `find`/`grep`, tragovi steka i generički zapisnici
- primjenjuje 49 JSON filtera iz `open-sse/services/compression/engines/rtk/filters/`
- podržava deklarativni cjevovod u stilu RTK-a: skidanje ANSI, zamjena, kratki spoj podudaranja izlaza, strip/keep linije, skraćivanje po retku, skraćivanje head/tail/max-line i povrat na prazno
- podržava projektne filtre zaštićene povjerenjem u `.rtk/filters.json` i globalne filtre u `DATA_DIR/rtk/filters.json`
- uklanja ANSI sekvence, šum napretka, ponovljene retke i beskorisnu šablonu
- čuva djelotvorne pogreške, upozorenja, sažetke, promijenjene datoteke i zadnji kontekst
- može izborno zadržati redigirani neobrađeni izlaz za recovery/debugging kroz provjerene rute upravljanja

Površina armaturne ploče je `Dashboard -> Context & Cache -> RTK`.

Operativni detalji za prilagođene filtre, pouzdanost, provjeru i oporavak neobrađenog izlaza uživo u [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK uzvodno izvještava o uštedama `60-90%` za kompresiju naredbenog izlaza. Njegov README primjer prikazuje 30-minutnu sesiju Claude koda koja ide od `~118,000` tokena do `~23,900` ili `79.7%` saved.

## LLMLingua-2 (semantičko obrezivanje)

LLMLingua-2 način rada** semantički leksem podrezivanje** na prozi koristeći mali ONNX klasifikator tokena, nadopunjujući Caveman i RTK motore temeljene na pravilima:

- sažima prozu samo u nesustavnim porukama; ograđeni kodni blokovi i drugi sačuvani konstrukti nikad se ne mijenjaju
- pokreće `@atjsh/llmlingua-2` pozadinu (ONNX preko `@huggingface/transformers`) u radnoj niti, tako da zaključivanje modela nikada ne blokira petlju događaja zahtjeva
- je** koji se može složiti** (`stackPriority` 35): u naslaganom cjevovodu pokreće se nakon strukturnih motora (CCR, session-dedup, headroom, Caveman ), ali prije `ultra`, budući da je semantičko obrezivanje najučinkovitije na već strukturalno komprimiranom tekstu — npr. `rtk -> caveman -> llmlingua`
- **fail-otvara se pri bilo kojoj pogrešci** (nedostaju izborni deps, worker spawn, model load, inference ili timeout) → originalni tekst se vraća nepromijenjen, nikada greška

Položaj motora: `open-sse/services/compression/engines/llmlingua/`. Površina armaturne ploče je `Dashboard -> Context & Cache -> LLMLingua`.

### Modeli

Zadani model je**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, brzo). Veća točnost** BERT-baza** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) dostupan je preko polja konfiguracije motora `model`. `@huggingface/transformers` lijeno preuzima odabrani model iz HuggingFace Huba u `${DATA_DIR}/models/llmlingua` pri prvom pozivu (`modelStore.ts`); nadjačavanje `modelPath` konfiguracije usmjerava ga na lokalnu kopiju umjesto toga (izvanmrežne / zračne instalacije).

### Izborne ovisnosti i instalacija na zahtjev

LLMLingua runtime peer stack koji se može rezati je** neobavezan** . Dva paketa su deklarirana kao `optionalDependencies` u `package.json` i zadržana** vanjski** prema proizvodnoj izradi (`scripts/build/prepublish.ts` ih ne spaja):

| Paket                | Verzija (pin) | Bilješke                                   |
| -------------------- | ------------- | ------------------------------------------ |
| `@atjsh/llmlingua-2` | `2.0.5`       | Ulazni paket; ostale proglašava vršnjacima |
| `js-tiktoken`        | `^1.0.20`     | Tokenizator                                |

`@huggingface/transformers` je prikvačen na `^4.2.0` (dijeli se s lokalnom stazom ugrađivanja i također se prati u samostalni paket); `@atjsh/llmlingua-2@2.0.5` je jednak njemu sa `"^3.5.2 || ^4.0.0"`, tako da su podržani i Transformers.js v3 i v4. Od 2.0.4, `@atjsh/llmlingua-2` više ne zahtijeva `@tensorflow/tfjs`, koji je uklonio najvećeg pojedinačnog doprinositelja (TensorFlow.js) sa SLM stoga. Samo dva gornja paketa su ravnopravni SLM koji se mogu rezati. Standardni `npm install` (dev) automatski instalira dodatni stog osim ako su izostavljene neobavezne ovisnosti.

**Zašto na zahtjev:** paket koji je objavio npm, samostalni paket i otprema Docker slike** bez** ove deps ostati vitak. Kada su odsutni, radnička vrata ovisnosti (proba za rješavanje `@atjsh/llmlingua-2` u `worker.ts`) otkazuju i motor** fail-otvara tiho** — odabir LLMLingua postaje no-op (tekst se vraća nepromijenjen, greška nije zabilježena). Da biste ga aktivirali u smanjenom okruženju, instalirajte dodatni skup:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Uklanjanje `@tensorflow/tfjs` (2.0.4 +) eliminira prethodno dominantnog ~ 800 MB doprinositelja — preostali otisak je transformers.js + onnxruntime-node runtimes, plus TinyBERT model (~ 57 MB) preuzet pri prvoj upotrebi (ne putem npm-a).

Po okruženju:

- **Dev / `npm install`** — instaliran automatski osim ako ste prošli `--omit=optional` (ili `--no-optional`). Nikakva radnja nije potrebna.
- **Globalni npm (`npm i -g omniroute`) / samostalan** — pokrenite gornju instalacijsku naredbu unutar direktorija instaliranog paketa ili ponovno instalirajte bez izostavljanja opcijskih deps.
- **Docker** — dodajte instalacijsku naredbu u izvedeni sloj slike; objavljena slika isporučuje se tanka po dizajnu.
- **VPS (PM2)** — instalirajte u `node_modules` aplikacije, zatim ponovno pokrenite proces kako bi radnik ponovno ispitao vrata.
- **Raw Next samostalno (`npm run build` → `.build/next/standalone/server.js`)** — samostalni trace brodovi NEITHER radnik niti opcijski deps, tako da se motor tiho otvara. `scripts/build/colocate-standalone.mjs` ponovno primjenjuje oboje (worker esbuild + optional-dep closure u samostalno stablo); pokreće se automatski preko `postbuild` npm kuke nakon svake izgradnje. Idempotentan, fail-soft kada su deps odsutni.

**Provjerite je li aktivan:** s odabranim LLMLingua, stvarna proza se zapravo smanjuje (motor prestaje s otvaranjem), a prvi zahtjev pokreće preuzimanje modela u `${DATA_DIR}/models/llmlingua`. Vrata namjerno ispituju samo `@atjsh/llmlingua-2` — ostali peeri su samo ESM i `require.resolve` im baca čak i kada je prisutan —, tako da se radnik i dalje neuspješno otvara ako bilo koji peer stvarno nedostaje u `import()` vremenu.

## Složeni cjevovodi

Složeni način rada izvodi korake cjevovoda redom. Zadano je:

```txt
rtk -> caveman
```

Upotrijebite ovo za sesije agenta za kodiranje gdje prompt kombinira izlaz naredbe s prozom ljudi ili pomoćnika. RTK prvo smanjuje bučne zapise alata, a zatim Caveman sažima preostali prirodni jezik.

Koraci cjevovoda konfiguriraju se pomoću `stackedPipeline` u postavkama kompresije ili kroz kombinacije kompresije.

Kada oba motora smanje isti prihvatljivi nosivost, ušteda se spaja:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP filtar stabla pristupačnosti

Pametni filtar stabla pristupačnosti MCP sloj je kompresije nakon izvršenja koji radi na MCP** rezultati alata** , a ne na upite ili kontekst. Usmjeren je na opširno stablo pristupačnosti i korisničke snimke preglednika koje vraćaju alati kao što su Playwright, MCP poslužitelji za korištenje računala i automatizaciju preglednika.

### Što radi

1. **Skidanje buke** — uklanja prazne generic/text unose (`- generic:`, `- text: ""`)
2. **Kolaps brata i sestre** — kada ≥ `collapseThreshold` (zadano 30) uzastopnih redaka strukturno ponavlja, sažima ih u prve `collapseKeepHead` (zadano 10) retke + sažetak broja + zadnjih `collapseKeepTail` (zadano 5) redaka
3. **Ref očuvanje** — `[ref=eXX]` sidra koja zahtijeva Playwright/computer-use nikada se ne dodiruju
4. **Tvrdo skraćivanje** — ako tekst nakon sažimanja i dalje premašuje `maxTextChars` (zadano 50 000), skraćuje se navigacijskim savjetom tako da agent može nastaviti s radom

### Položaj motora

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfiguracija

Upravlja `compression.mcpAccessibility` u globalnim postavkama (migracija 056). Zadana konfiguracija:

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

Filtar se primjenjuje samo na rezultate alata čiji je `type` `"text"` i čija duljina premašuje `minLengthToProcess`. Ne utječe na brzu kompresiju ili korisni teret zahtjeva.

### Očekivana ušteda

60–80% na rezultate alata za pregled preglednika, ovisno o složenosti stranice. Algoritam sažimanja je O(n) u broju redaka i dodaje zanemarivu latenciju.

### Ovaj filter u odnosu na gornje kompresijske motore

| Aspekt    | Pećinski čovjek / RTK / naslagani | MCP filtar pristupačnosti              |
| --------- | --------------------------------- | -------------------------------------- |
| Cilj      | Zatražite upite / kontekst        | rezultati MCP                          |
| Okidač    | Postavka načina kompresije        | `compression.mcpAccessibility.enabled` |
| Opseg     | Sve SSE poruke                    | Samo rezultati alata                   |
| Ref sidra | N/A                               | Bezuvjetno očuvana                     |

---

## Kompresijske kombinacije

Kombinacije kompresije nazivaju se profili kompresije koji se mogu dodijeliti kombinacijama usmjeravanja:

- `compression_combos`: pohranjuje način rada, cjevovod, RTK konfiguraciju, jezičnu konfiguraciju i zadani marker
- `compression_combo_assignments`: preslikava kombinaciju kompresije u kombinaciju usmjeravanja
- integracija vremena izvođenja rješava dodijeljenu kombinaciju kompresije prije nadjačavanja generičke kombinacije
- analitika uključuje `compression_combo_id` i `engine`

Površina armaturne ploče: `Dashboard -> Context & Cache -> Compression Combos`.

## Preduvjeti / vodič za operatera (CCR & session-dedup)

CCR (`ccr`) i `session-dedup` zamjenjuju ili brišu tekst i ostavljaju a** marker** iza. Ovaj odjeljak je referenca operatera za spajanje klijenta, čitanje dva markera i dohvaćanje ili dijagnosticiranje izbrisanog sadržaja. Mehanika svakog motora opisana je gore; ovo je sloj "kako to pokrenuti".

### Prijevozi i krajnje točke

Do MCP poslužitelja koji izlaže CCR alate može se doći na tri načina. Zadana baza URL je `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Prijevoz                               | URL / naredba                           | Bilješke                                                                                                                              |
| -------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Streamable HTTP (klijent, preporučeno) | `http://localhost:20128/api/mcp/stream` | Krajnja točka s kojom trenutačni MCP klijenti razgovaraju.                                                                            |
| Legacy SSE singleton                   | `http://localhost:20128/api/mcp/sse`    | Stariji singleton prijevoz. To** zatvara** streamable sesije; koristite `streamable-http` klijente protiv `/api/mcp/stream`, ne ovaj. |
| stdio                                  | `omniroute --mcp`                       | Za IDE MCP konfiguraciju koja pokreće proces. Ne postoji `--dev` zastavica; `omniroute --mcp` je stdio ulazna točka.                  |

### Razine pohrane (ono što preživi ponovno pokretanje)

CCR je a** dvoslojni** pohrana, ne samo u memoriji:

- **Vruća razina u memoriji** — po bloku cap 2 MiB, po principalu 16 MiB, globalno 64 MiB. Unosi su zadani na 24 sata TTL (maksimalno 7 dana). Potpuno MCP dohvaćanje iz memorije ograničeno je na 256 KiB; sve što je veće i dalje je dostupno kroz ranged/grep modove.
- **Izdržljiva SQLite razina** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, uključeno prema zadanim postavkama) — podupire sloj u memoriji tako da blok preživi LRU izbacivanje, ponovno pokretanje ili povratno slijetanje na drugu instancu. Red zadržava TTL bloka, tako da blok nakon svog TTL nestaje s obje razine.

Tri čuvara drže izdržljivu razinu ograničenu — blok ostaje samo memorija kada:

1. blok je gotov** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. runtime je runtime u oblaku (bez lokalnog diska);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Dakle, "blok je nestao" nije sveobuhvatna priča o ponovnom pokretanju: blok sub-512 KB u lokalnom vremenu izvođenja koje nije u oblaku preživljava ponovno pokretanje putem trajnog sloja dok se njegov TTL ne potroši. Pogledajte [referencu okruženja](../reference/ENVIRONMENT.md) za varijablu.

### Dva markera

| Marker                                | Značenje                                                                                                                              | Što model treba učiniti                                                                                                                                                                                      |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `[CCR retrieve hash=<24hex> chars=N]` | Veliki blok je pohranjen sa sadržajnom adresom.                                                                                       | Nazovite `omniroute_ccr_retrieve` s** 24-hex hash kopirano doslovno** da biste dobili izvorni tekst natrag.                                                                                                  |
| `[dedup:ref sha=…]`                   | `session-dedup` elidirani tekst već poslan u ranijem krugu iste sesije. Ovo je** namjerni pogled unatrag** , a ne gubitak ili greška. | učiniti** ne** nazovite bilo koji alat i učinite** ne** pokušati ga "rekonstruirati". Prvo pojavljivanje teksta je kanonski prijepis; trenutni potez se nikada ne prepisuje, dedupira se na kasnijem potezu. |

`[dedup:ref]` pregled unatrag je namjerna protokolarna odluka — nema rekonstrukcije prije slanja. Tretirajte to kao "točno ovaj tekst je već bio emitiran ranije u ovoj sesiji."

### Preduvjeti klijenta

- **Ključ (stdio):** stdio pozivatelj ne nosi identitet po zahtjevu, pa se autentificira sa `OMNIROUTE_API_KEY` (postavljenim u `env` poslužitelja MCP ). Bez njega pozivatelj je anoniman i alati koji zahtijevaju principala mogu se pogoršati.
- **`tools[]` je preduvjet za ubrizgavanje.** Umetnuta je instrukcija protokola za dohvaćanje CCR (#8033).** samo** kada oglašeni `tools[]` zahtjeva dokaže da klijent zapravo može doseći `omniroute_ccr_retrieve`. Podudaranje je podudaranje zadnjeg segmenta omeđeno separatorom (`__`, `.`, `/`, `:`) — nikad goli podniz — tako da se ime u prostoru imena kao što je `mcp__gateway__omniroute_ccr_retrieve` i dalje računa. Odsutan ili nepodudarni `tools[]` znači da instrukcija _nije_ ubačena, prema dizajnu.
- **`codemode:false` (OpenCode klijenti).** OpenCode prema zadanim postavkama koristi Code Mode, koji oglašava samo svoje izvorne alate modelu i** ne radi** stavite MCP alate na izvorni `tools[]` popis. Postavite `codemode: false` na unos MCP poslužitelja tako da se reklamiraju `omniroute_ccr_*` alati. Ovo je a** klijent** postavka, a ne OmniRoute. Još se ne ubacuje CCR instrukcija: OpenCode imenuje alat `<server>_<tool>`, tako da poslužitelj koji se zove `omniroute` izlaže `omniroute_omniroute_ccr_retrieve`, a `_` nije jedan od odgovarajućih separatora.
- **ravnatelji.** Pohranjivanje i dohvaćanje su izolirani po autenticiranom principalu (po API ključu). Ključ vidi samo svoje blokove.

### Opseg po alatu

Provedba opsega uvijek je uključena za HTTP/SSE pozivatelje uskog opsega. Alati `omniroute_` CCR zahtijevaju:

| Alat                     | Opseg               |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Opseg koji nedostaje vraća an**MCP rezultat pogreške alata** (`isError: true`, ne HTTP 403 — `403 LOCAL_ONLY` je zasebna autentifikacija čuvara rute povratne petlje): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimalni daljinski ključ može držati `mcp:connect` (ovlašćuje `/api/mcp/` samo lokalno izdvajanje) plus specifični read/write opseg koji mu je potreban.

### Matrica klijenata

| Klijent             | Prijevoz                                        | Konfiguracija za korištenje                                                                                                                                                                                                                                   | `tools[]` reklamirao? (umetnuta instrukcija → CCR )                                                                                                                                               |
| ------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude kod          | streamable-http                                 | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                             | Da — MCP-sposoban; ubrizgan.                                                                                                                                                                      |
| Cursor / Cline      | `stdio`** ili** `streamable-http`               | stdio: `omniroute --mcp` sa `OMNIROUTE_API_KEY` u `env`; ili udaljeni MCP unos koji pokazuje na `http://localhost:20128/api/mcp/stream` (pogledajte [Vodič za postavljanje → MCP konfiguracije klijenta](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Da — reklamira `omniroute_ccr_*` alate.                                                                                                                                                           |
| OpenCode            | streamable-http                                 | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plus `codemode: false`                                                                                                                                                              | Alati reklamirani samo sa `codemode: false`; instrukcija još uvijek nije ubrizgana jer `omniroute_omniroute_ccr_retrieve` ne odgovara (pogledajte [Preduvjete klijenta](#client-prerequisites) ). |
| OpenAI-kompatibilan | HTTP kompatibilan s OpenAI-jem (završeci chata) | standardni klijent za završetak chata protiv OpenAI-kompatibilne krajnje točke                                                                                                                                                                                | **Nikada** — jednostavnom OpenAI-kompatibilnom pozivatelju nikada se ne kaže da pozove alat, a instrukcija se ne ubacuje.                                                                         |

### Ograničenja dohvaćanja i označavanje stranica

rezultati teksta alata MCP su ošišani oko `mcpAccessibility.maxTextChars` (zadano `50000`). `full` dohvat bloka ograničen je na 256 KiB —** ne postoji neograničeno potpuno dohvaćanje** . Kada je `chars=N` bloka velik, prelistajte ga umjesto da povlačite cijelu stvar:

- Osnovno pravilo:**`chars > 40000` → koristi `mode`** , nikad goli pun.
- `mode:"grep"` — regex `pattern` podudara red po red, do 1000 odgovarajućih redaka (`unique: true` ispušta ponavljanja), najjeftinije za "pronađi jedan redak koji mi treba."
- `mode:"lines"` — raspon linija s indeksom 1; treba i `start` i `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` linije.
- `mode:"stats"` — broj linija, znakova i bajtova bez tijela.

Upotrijebite `mode:"lines"` sa `start`/`end` da hodate po dugačkom bloku stranica umjesto da tražite cijelu stvar odjednom.

### Imenovanje alata

Alat za dohvaćanje trenutačno se zove `omniroute_ccr_retrieve` (prefiks `omniroute_` zastarjelo je rješenje za sukobe imena između poslužitelja). Čišći naziv alata s ograničenim sufiksom i popravak za MCP JSON rezultate skraćeni srednji niz prate se kao uzvodni nastavak; ova stranica dokumentira samo trenutno, isporučeno ponašanje.

### Životni ciklus sesije

Streamable-HTTP sesije su u stanju mirovanja i poslužitelj ih žanje; prozor mirovanja je `MCP_SESSION_IDLE_MS` konstanta (referencirana imenom, a ne čvrsto kodiranom vrijednošću, tako da se ova stranica ne pomiče kada se mijenja). Simptom idle-reaped sesije je HTTP 404 sa `Unknown Mcp-Session-Id` — lijek je ponovno povezivanje ili ponovno pokretanje sesije,** ne** za rotiranje ključa, promjenu opsega ili preimenovanje alata.

## API Površina

| Ruta                                   | Svrha                                                                     |
| -------------------------------------- | ------------------------------------------------------------------------- |
| `/api/settings/compression`            | Globalne postavke kompresije (uključuje `mcpAccessibility` konfiguraciju) |
| `/api/compression/preview`             | Pregledajte bilo koji način kompresije                                    |
| `/api/compression/language-packs`      | Popis dostupnih jezičnih paketa Caveman                                   |
| `/api/context/caveman/config`          | Alias postavki Cavemana                                                   |
| `/api/context/rtk/config`              | RTK zadane postavke i postavke                                            |
| `/api/context/rtk/filters`             | RTK filter katalog                                                        |
| `/api/context/rtk/test`                | RTK preview/test krajnja točka                                            |
| `/api/context/rtk/raw-output/[id]`     | Oporavak autentificiranog redigiranog sirovog izlaza                      |
| `/api/context/combos`                  | Kombinacija kompresije CRUD                                               |
| `/api/context/combos/[id]/assignments` | Routing-combo dodjela CRUD                                                |
| `/api/context/analytics`               | Alias analitike kompresije                                                |

Rute upravljanja zahtijevaju provjeru autentičnosti upravljanja ili provjere pravila API ključa.

## MCP

Kompresija izlaže pet MCP alata:

| Alat                                | Opseg               | Svrha                                        |
| ----------------------------------- | ------------------- | -------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Postavke, analitika, statistika predmemorije |
| `omniroute_compression_configure`   | `write:compression` | Ažurirajte globalne postavke                 |
| `omniroute_set_compression_engine`  | `write:compression` | Postavite način rada i dodatni cjevovod      |
| `omniroute_list_compression_combos` | `read:compression`  | Navedite kombinacije kompresije              |
| `omniroute_compression_combo_stats` | `read:compression`  | Pročitajte combo/engine analitiku            |

## Opseg i izuzeci

**Ugradnje se nikada ne komprimiraju.** `open-sse/handlers/embeddings.ts` nikada ne poziva nijedan kompresijski motor — request/response tijela prolaze ravno do izvršitelja netaknuta. To je danas strukturno (ugrađivanja i dovršavanja chata su nepovezani rukovatelji), a ne provjera vremena izvođenja, ali znači da problem vektorske distorzije u #8034 nema površinu izloženosti na putu ugrađivanja.

**Per-model/endpoint filtar za isključivanje (#8034).** Za dovršetke chata, operater može imenovati ID-ove modela / ciljeve `provider/model` koji se nikada ne smiju komprimirati — zaštitnu ogradu koja je korisna ako se kompresija ikada kasnije spoji bliže stazi koja je susjedna ugrađivanju i općenito je korisna za bilo koji model čiji je točan upit bajt za bajt važan (determinističke procjene, prefiksi osjetljivi na predmemoriju, itd.).

- Polje postavki: `exclusions?: string[]` na konfiguraciji globalne kompresije (`GET`/`PUT /api/settings/compression`), postojano putem postojećeg prostora imena kompresije `key_value` (`src/lib/db/compression.ts`) — nema nove tablice.
- Kartica nadzorne ploče:** Nadzorna ploča → Kompresija → Izuzeci** (`/dashboard/compression/exclusions`).
- Sintaksa uzorka: `*` je jedini zamjenski znak. Svaki drugi metakarakter regularnog izraza u uzorku se izbjegava prije podudaranja, tako da `gpt-5.6` odgovara samo literalnom nizu, nikada `gpt-5x6` (ReDoS-siguran, ograničen, bez ugniježđenih kvantifikatora). Uzorci se usklađuju bez obzira na velika i mala slova s ID-om golog modela i složenim `provider/model` — `gpt-5-6`, `openai/gpt-5-6` i `openai/*`, svi rade, a sam `*` isključuje svaki model.
- Podudaranje: `isCompressionExcluded()` / `normalizeCompressionExclusions()` u `open-sse/services/compression/exclusions.ts`. `chatCore.ts` provjerava izuzeti cilj odmah nakon rješavanja postavki kompresije,** prije nego bilo koji motor radi** , i tretira podudaranje točno kao da je kompresija globalno onemogućena — tijelo zahtjeva je dokazano identično u bajtu. Preskakanje se bilježi putem `writeCompressionSkip(..., "excluded")` radi vidljivosti analitike.
- Zadano (empty/absent popis): identično ponašanju prije #8034 — ništa nije isključeno.

## Poznata ograničenja

- **LLMLingua-2 (SLM) zahtijeva opcijske deps.** Radnik radi samo u proizvodnoj verziji kada su ravnopravni `@atjsh/llmlingua-2` + ko-locirani u `dist/node_modules` (pogledajte `scripts/build/colocateOptionals.mjs`, #4286). Bez njih motor se otvara (vraća izvorni tekst). Radna rezolucija više ne ovisi o `import.meta.url` (umire u samostalnom paketu) — ona se usidri na vrijeme izvođenja cwd / `argv[1]`.
- **Jezični paketi Caveman `de` / `fr` / `ja` su djelomični.** Šalju `context` + `filler` + `structural` pravila, ali ne i `dedup` / `ultra` pakete, tako da `ultra` intenzitet nije jači od `full` za te jezike (oni koriste samo vlastita pravila — nema tihog vraćanja na engleska `dedup`/`ultra` pravila, koja bi kvarila strani tekst). `en` / `es` / `id` / `pt-BR` su dovršeni. Doprinosi `dedup.json` + `ultra.json` za djelomične pakete su dobrodošli.
- **Složena telemetrija navodi samo motore koji su komprimirani.** Korak naslaganog cjevovoda čiji je motor radio, ali je proizveo 0 % uštede vraća `stats:null` i stoga se ne pojavljuje u `engineBreakdown` — nerazlučivo od koraka koji je preskočen. Razlikovanje "izvršeno, 0 %" od "preskočeno" zahtijevalo bi promjenu modela kvara i odgađa se.

## Validacija

Fokusirana vrata za ovo područje su:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
