# Compression Engines (Bosanski)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompresija je izgrađena oko ugovora motora. Režim može direktno pokrenuti jedan motor (`caveman` ili `rtk`) ili deterministički naslagani cjevovod koji izvršava više motora po redu.

## Načini rada

| Mode         | Put motora                                                                         | Predviđeni unos                                   |
| ------------ | ---------------------------------------------------------------------------------- | ------------------------------------------------- |
| `off`        | nijedan                                                                            | Tačno brzo očuvanje                               |
| `lite`       | Caveman lite pomoćnici                                                             | Uvijek uključeno čišćenje niskog rizika           |
| `standard`   | Caveman                                                                            | Brza kondenzacija na prirodnom jeziku             |
| `aggressive` | Caveman + history/tool sažeti                                                      | Duge sesije ćaskanja                              |
| `ultra`      | Caveman + pomoćnici za orezivanje                                                  | Oporavak s ograničenjem konteksta                 |
| `rtk`        | RTK                                                                                | Terminal, shell, build, test i git izlaz          |
| `omniglyph`  | OmniGlyph                                                                          | Kontekst kao slika na žici izvornog provajdera    |
| `stacked`    | Pipeline. Zadani zahtjev je `session-dedup -> lite`. `rtk -> caveman` je uključen. | Mješoviti trupci alata i proza, maksimalne uštede |

### OmniGlyph kompresijski profili

Mehanizam `omniglyph` (paket `omniglyph`, 1.4.0 +) prihvata imenovani semantički profil, postavljen globalno kroz `omniglyph.profile` u postavkama kompresije ili po koraku kroz konfiguraciju koraka naslaganog cjevovoda:

| Profil        | Granica                                                                                              |
| ------------- | ---------------------------------------------------------------------------------------------------- |
| `aggressive`  | Default. Politika objavljenih priznanica mjeri — sistem slika, dokumentaciju alata i gustu historiju |
| `balanced`    | Čuva izvorno stanje uživo, štiti zadnjih 8 okreta, urušava stariju zatvorenu povijest                |
| `coding-safe` | Održava autoritet, šeme alata i izlaz alata uživo, štiti zadnjih 12 okreta                           |
| `passthrough` | Rute bez transformacije; motor je preskočen                                                          |

Profil je a** plafon, ne pod** : `mergeCompressionProfileOptions` u paketu odbija da dozvoli pozivaocu da nadjača ponovno otvaranje trake sa gubicima profil zatvoren, tako da `preserveSystemPrompt: false` po koraku ne može ponovo omogućiti kompresiju sistema pod `coding-safe`.

Mjereno na ovoj bazi koda: `coding-safe` i `balanced` podižu `minCompressChars` do maksimuma i drže sistem, šeme alata i rezultate alata izvornim, tako da se sesija koja još nije akumulirala historiju zaustavlja na `below_min_chars` i motor ništa ne transformira. Zbog toga je default `aggressive`, a ne najsigurniji profil.

Paket rješava svoj vlastiti opseg modela i profil iz svoje konfiguracije okruženja. OmniRoute nikada ne delegira odluku: adapter pričvršćuje kapiju modela za najrestriktivniji opseg paketa, tako da postavke okruženja domaćina mogu samo suziti listu dozvoljenih, nikada je ne proširiti preko OmniRoute-ovih izmjerenih računa.

## Engine Registry

Registar živi u `open-sse/services/compression/engines/registry.ts`. Motori otkrivaju zajednički ugovor:

- `id`: stabilan id motora kao što je `caveman` ili `rtk`
- `apply(text, config)`: naslijeđena putanja izvršenja koju koriste naslagani cjevovodi
- `compress(input, config)`: primarna putanja izvršenja koja vraća tekst + stats
- `getConfigSchema()`: vraća oblik važeće konfiguracije sličan JSON šemi
- `validateConfig(config)`: vraća `{ valid, errors[] }`

Registracija koristi `registerCompressionEngine(engine)` (ili `registerEngine` za napredne slučajeve), koji poziva `assertValidEngine()` i `validateConfig(defaultConfig)` prije prihvatanja. Koristite `unregisterCompressionEngine(id)` da uklonite motor u toku rada.

`strategySelector.ts` registruje ugrađene motore prije pokretanja kompresije. Ovo omogućava pregled, kompresiju vremena izvođenja, složeni način rada, testove i buduće mašine da koriste istu putanju izvršavanja.

### MCP kompresija opisa (povezano)

Zaseban registar komprimira metapodatke opisa MCP alata na nivou registra — vidi `open-sse/mcp-server/descriptionCompressor.ts` i [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Ponovo koristi Caveman pravila, ali radi na metapodacima alata, a ne na zahtjevima korisnih opterećenja.

### Dodatni ugrađeni motori

Osim Cavemana, RTK i LLMLingua-2, registar isporučuje nekoliko specijaliziranih mehanizama bez gubitaka / strukturalnih motora (koji se koriste za naslagane cjevovode, igralište i testove):

| Motor            | Id              | Šta radi                                                                                                                                                                                    |
| ---------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR              | `ccr`           | Content-Compress-Retrieve (H4): zamjenjuje velike susjedne blokove teksta referencama adresiranim na sadržaj, tako da se repeated/large blokovi šalju jednom i nakon toga se referenciraju. |
| prostor za glavu | `headroom`      | SmartCrusher (H3 + N5): tabelarno sažimanje homogenog JSON niza korisnih opterećenja bez gubitaka u stupasti `[N rows]` oblik.                                                              |
| jonizator        | `ionizer`       | Uzorkovanje Head/middle/tail reda za vrlo velike homogene blokove, pohranjujući elidiranu sredinu kao CCR referencu adresiranu na sadržaj.                                                  |
| session-dedup    | `session-dedup` | Unakrsna deduplikacija usmjerena na sadržaj (inspirirana TokenMizerom): izbacuje tekst koji je već viđen u ranijim okretima iste sesije.                                                    |

**CCR retrieve-protocol instruction (#8033):** the first time CCR replaces ≥1 block in a request, the engine prepends a single, idempotent `system` message (leading with the `[CCR protocol]` sentinel) teaching the caller the marker → tool contract: what a `[CCR retrieve hash=<24hex> chars=N]` marker means, that the hash must be copied verbatim (all 24 hex characters — mis-copied hashes are the likely cause of "block not found" misses), and that a `[dedup:ref sha=...]` marker means "look back in history", not "call the tool". The note is injected **only when the caller's advertised `tools[]` proves it can actually reach `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — a plain OpenAI-compatible caller without that tool never receives an instruction to call something it cannot reach. Idempotency is enforced by scanning the message history for the sentinel before injecting, so multi-turn requests (which replay prior messages) do not stack the note once per turn.

## Caveman

Način Caveman fokusira se na semantičku kondenzaciju normalne proze:

- čuva blokove koda, URLs, JSON, staze i strukturirane podatke
- uklanja dopunu, hedžing, ponovljeni kontekst i opširno vezivno fraziranje
- podržava pakete pravila datoteka svjesni jezika u `open-sse/services/compression/rules/`
- ostaje dostupan kroz stare `standard`, `aggressive` i `ultra` načine

Površina instrument table je `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream prijavljuje `~75%` manje izlaznih tokena, `65%` prosječne uštede izlaza u mjerilima sa `22-87%` opsegom i `~46%` alat za kompresiju ulaza. OmniRoute koristi broj na ulaznoj strani Cavemana kada dokumentuje naslagane prompt/context uštede; Režim izlaza Caveman ostaje zasebna karakteristika ponašanja.

## RTK

RTK način rada fokusira se na izlaz komandi i alata:

- detektuje izlazne klase kao što su `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go testovi, TypeScript/Vite/Webpack builds, ESLint, npm audit/installs, Docker logovi, shell `find`/`grep`, tragovi steka i generički zapisi
- primjenjuje 49 JSON filtera iz `open-sse/services/compression/engines/rtk/filters/`
- podržava deklarativni cevovod u RTK stilu: ANSI skidanje, zamjena, kratki spoj s podudaranjem izlaza, strip/keep linije, skraćivanje po liniji, head/tail/max-line skraćivanje i povratak na prazno
- podržava filtre projekta u `.rtk/filters.json` i globalne filtere u `DATA_DIR/rtk/filters.json`
- uklanja ANSI sekvence, šum napretka, ponavljane linije i beskorisni šablon
- čuva kvarove, upozorenja, sažetke, promijenjene datoteke i rep kontekst
- može opciono zadržati redigovani neobrađeni izlaz za recovery/debugging kroz autentificirane rute upravljanja

Površina instrument table je `Dashboard -> Context & Cache -> RTK`.

Operativni detalji za prilagođene filtere, povjerenje, verifikaciju i oporavak sirovog izlaza žive u [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream prijavljuje `60-90%` uštede za kompresiju komandnog izlaza. Njegov README primjer pokazuje 30-minutnu sesiju Claude koda koja ide od `~118,000` tokena do `~23,900`, ili `79.7%` sačuvanog.

## LLMLingua-2 (semantičko obrezivanje)

LLMLingua-2 način rada** semantičko odsecanje tokena** o prozi koristeći mali klasifikator ONNX tokena, koji dopunjuje Caveman i RTK motore zasnovane na pravilima:

- komprimuje prozu samo u nesistemske poruke; ograđeni blokovi koda i drugi sačuvani konstrukti se nikada ne mijenjaju
- pokreće `@atjsh/llmlingua-2` backend (ONNX preko `@huggingface/transformers`) u radnoj niti, tako da zaključivanje modela nikada ne blokira petlju događaja zahtjeva
- je** stackable** (`stackPriority` 35): u naslaganom cevovodu radi nakon strukturnih motora (CCR, session-dedup, headroom, Caveman ) ali prije `ultra`, budući da je semantičko skraćivanje najefikasnije na već strukturno komprimiranom tekstu — npr. `rtk -> caveman -> llmlingua`
- **neuspješno otvaranje na bilo kojoj grešci** (nedostaju opcionalni deps, worker spawn, model load, inference, or timeout) → originalni tekst se vraća nepromijenjen, nikada greška

Lokacija motora: `open-sse/services/compression/engines/llmlingua/`. Površina instrument table je `Dashboard -> Context & Cache -> LLMLingua`.

### Modeli

Zadani model je**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, brzo). Veća tačnost** BERT-baza** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) je dostupan preko polja za konfiguraciju motora `model`. `@huggingface/transformers` lijeno preuzima odabrani model iz HuggingFace Huba u `${DATA_DIR}/models/llmlingua` pri prvom pozivu (`modelStore.ts`); umjesto toga `modelPath` konfiguracija ga usmjerava na lokalnu kopiju (offline / air-gapped instalacije).

### Opcione zavisnosti i instalacija na zahtjev

LLMLingua runtime peer stack koji se može smanjiti je** opciono** . Dva paketa su deklarirana kao `optionalDependencies` u `package.json` i čuvaju se** vanjski** prema proizvodnoj verziji (`scripts/build/prepublish.ts` ih ne povezuje):

| Paket                | Verzija (pin) | Bilješke                                     |
| -------------------- | ------------- | -------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`       | Entry package; ostale deklarira kao vršnjake |
| `js-tiktoken`        | `^1.0.20`     | Tokenizer                                    |

`@huggingface/transformers` je zakačen na `^4.2.0` (dijeli se s lokalnom putanjom za ugrađivanje i također se prati u samostalni paket); `@atjsh/llmlingua-2@2.0.5` peer na njemu sa `"^3.5.2 || ^4.0.0"`, tako da su i Transformers.js v3 i v4 podržani. Od 2.0.4, `@atjsh/llmlingua-2` više ne zahtijeva `@tensorflow/tfjs`, što je uklonilo najvećeg pojedinačnog saradnika (TensorFlow.js) iz SLM steka. Samo dva gore navedena paketa su SLM peer koji se može orezati. Standardni `npm install` (dev) automatski instalira opcioni stek osim ako su opcione zavisnosti izostavljene.

**Zašto na zahtjev:** npm-objavljeni paket, samostalni paket i Docker image ship** bez** ovi deps da ostanu vitki. Kada su odsutni, radnička kapija zavisnosti ( `@atjsh/llmlingua-2` sonda za rješavanje u `worker.ts`) ne radi i motor** bez greške otvara se tiho** — odabirom LLMLingua postaje ne-op (tekst se vraća nepromijenjen, greška nije zabilježena). Da biste ga aktivirali u smanjenom okruženju, instalirajte opcionalni stog:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Uklanjanje `@tensorflow/tfjs` (2.0.4 +) eliminira prethodno dominantni ~ 800 MB doprinosnik — preostali otisak je transformers.js + onnxruntime-node runtimes, plus TinyBERT model (~ 57 MB) preuzet pri prvoj upotrebi (ne preko npm).

Po okruženju:

- **Dev / `npm install`** — se instalira automatski osim ako niste položili `--omit=optional` (ili `--no-optional`). Nije potrebna akcija.
- **Globalni npm (`npm i -g omniroute`) / samostalan** — pokrenite gornju naredbu za instalaciju unutar instaliranog direktorija paketa ili ponovo instalirajte bez izostavljanja opcionih deps-ova.
- **Docker** — dodajte naredbu za instalaciju u sloj izvedene slike; objavljena slika je tanka po dizajnu.
- **VPS (PM2)** — instalirajte u `node_modules` aplikacije, a zatim ponovo pokrenite proces kako bi radnik ponovo ispitao kapiju.
- **Raw Next samostalno (`npm run build` → `.build/next/standalone/server.js`)** — samostalno praćenje šalje NEITHER radnika niti opcione deps, tako da se motor tiho otvara. `scripts/build/colocate-standalone.mjs` ponovo primjenjuje oba (radnik esbuild + opciono-dep zatvaranje u samostalno stablo); pokreće se automatski preko `postbuild` npm kuke nakon svake gradnje. Idempotentan, mekan kada deps nema.

**Provjerite da li je aktivan:** sa odabranim LLMLingua, prava proza se zapravo smanjuje (motor prestaje da se otvara pri kvaru), a prvi zahtjev pokreće preuzimanje modela u `${DATA_DIR}/models/llmlingua`. Kapija namjerno ispituje samo `@atjsh/llmlingua-2` — ostali ravnopravni vršnjaci su samo za ESM i `require.resolve` ih baca čak i kada je prisutan — tako da se radnik i dalje ne otvara ako bilo koji ravnopravni partner stvarno nedostaje u `import()` vrijeme.

## Stacked Pipelines

Stacked mod pokreće korake cjevovoda po redu. Zadana postavka je:

```txt
rtk -> caveman
```

Koristite ovo za sesije agenta za kodiranje gdje prompt kombinuje izlaz komande sa prozom za ljude ili pomoćnike. RTK prvo smanjuje bučne zapise alata, a zatim Caveman komprimira preostali prirodni jezik.

Koraci cjevovoda se konfiguriraju pomoću `stackedPipeline` u postavkama kompresije ili kroz kombinacije kompresije.

Kada oba motora smanje istu prihvatljivu nosivost, ušteda je:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Filter stabla pristupačnosti

Pametni filter MCP stabla pristupačnosti je sloj kompresije nakon izvršenja koji radi na MCP** rezultati alata** , ne na upite ili kontekst. Cilja na opširno stablo pristupačnosti i korisne snimke pregledača koje vraćaju alati kao što su Playwright, korištenje računara i MCP serveri za automatizaciju pretraživača.

### Šta radi

1. **Skidanje buke** — uklanja prazne generic/text unose (`- generic:`, `- text: ""`)
2. **Brat i sestra kolaps** — kada su ≥ `collapseThreshold` (podrazumevano 30) uzastopne linije strukturna ponavljanja, sažima ih u prve `collapseKeepHead` (podrazumevano 10) linije + rezime brojanja + poslednjih `collapseKeepTail` (zadano 5) linija
3. **Ref očuvanje** — `[ref=eXX]` sidra koja zahtijeva Playwright/computer-use se nikada ne dodiruju
4. **Hard truncation** — ako tekst nakon kolapsa i dalje premašuje `maxTextChars` (zadano 50.000), skraćuje se navigacijskim nagovještajem kako bi agent mogao nastaviti s radom

### Lokacija motora

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfiguracija

Kontrolira `compression.mcpAccessibility` u globalnim postavkama (migracija 056). Zadana konfiguracija:

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

Filter se primjenjuje samo na korisna opterećenja rezultata alata čiji je `type` `"text"` i čija dužina prelazi `minLengthToProcess`. To ne utječe na promptnu kompresiju ili zahtjeve korisnog opterećenja.

### Očekivana ušteda

60–80% na rezultate alata za brze snimke pretraživača, u zavisnosti od složenosti stranice. Algoritam kolapsa je O(n) u broju redova i dodaje zanemarljivo kašnjenje.

### Ovaj filter naspram gornjih kompresijskih motora

| Aspekt    | Caveman / RTK / Stacked    | MCP filter pristupačnosti              |
| --------- | -------------------------- | -------------------------------------- |
| Target    | Zahtjevi / kontekst        | rezultati MCP                          |
| Trigger   | Postavka načina kompresije | `compression.mcpAccessibility.enabled` |
| Obim      | Sve SSE poruke             | Samo rezultati alata                   |
| Ref sidra | N/A                        | Bezuslovno očuvano                     |

---

## Compression Combos

Kombinacije kompresije nazivaju se profili kompresije koji se mogu dodijeliti kombinacijama usmjeravanja:

- `compression_combos`: pohranjuje način rada, cjevovod, RTK konfiguraciju, konfiguraciju jezika i zadani marker
- `compression_combo_assignments`: mapira kombinaciju kompresije u kombinaciju usmjeravanja
- runtime integracija rješava dodijeljenu kombinaciju kompresije prije nego što generička kombinacija nadjača
- analitika uključuje `compression_combo_id` i `engine`

Površina instrument table: `Dashboard -> Context & Cache -> Compression Combos`.

## Preduvjeti / vodič za operatera (CCR & session-dedup)

CCR (`ccr`) i `session-dedup` zamjenjuju ili brišu tekst i ostavljaju a** marker** iza. Ovaj odjeljak je referenca za operatera za povezivanje klijenta, čitanje dva markera i dohvaćanje ili dijagnosticiranje izbrisanog sadržaja. Mehanika svakog motora je pokrivena gore; ovo je sloj "kako da ga pokrenem".

### Transport i krajnje tačke

Do MCP servera koji izlaže CCR alate može se doći na tri načina. Zadana baza URL je `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transport                                             | URL / komanda                           | Bilješke                                                                                                                                 |
| ----------------------------------------------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| HTTP koji se može prenositi (klijent, preporučuje se) | `http://localhost:20128/api/mcp/stream` | Krajnja tačka sa kojom trenutno razgovaraju MCP klijenti.                                                                                |
| Naslijeđeni SSE singleton                             | `http://localhost:20128/api/mcp/sse`    | Stariji singleton transport. To** zatvara** streamable sessions; koristite `streamable-http` klijente protiv `/api/mcp/stream`, ne ovog. |
| stdio                                                 | `omniroute --mcp`                       | Za konfiguraciju IDE MCP koja pokreće proces. Ne postoji `--dev` zastava; `omniroute --mcp` je stdio ulazna tačka.                       |

### Nivoi pohrane (ono što preživi nakon ponovnog pokretanja)

CCR je a** dvoslojni** trgovina, ne samo u memoriji:

- **Vrući nivo u memoriji** — kapa po bloku 2 MiB, po principalu 16 MiB, globalno 64 MiB. Unosi su podrazumevani na 24 h TTL (maksimalno 7 dana). Potpuno MCP preuzimanje iz memorije ograničeno je na 256 KiB; sve veće je i dalje dostupno kroz rangirane / grep modove.
- **Izdržljiv SQLite nivo** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, uključeno po defaultu) — podržava nivo u memoriji tako da blok preživi LRU izbacivanje, ponovno pokretanje ili preuzimanje na drugoj instanci. Red zadržava TTL bloka, tako da blok iza njegovog TTL nestaje sa oba nivoa.

Tri štitnika drže izdržljivi nivo ograničenim — blok ostaje samo u memoriji kada:

1. blok je gotov** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. vrijeme izvođenja je vrijeme izvođenja u oblaku (bez lokalnog diska);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Dakle, "blok je nestao" nije potpuna priča o ponovnom pokretanju: sub-512 KB blok na lokalnom, ne-cloud runtime-u preživljava ponovno pokretanje preko trajnog nivoa sve dok njegov TTL ne ponestane. Pogledajte [Referenca za okruženje](../reference/ENVIRONMENT.md) za varijablu.

### Dva markera

| Marker                                | Značenje                                                                                                                                       | Šta model treba da uradi                                                                                                                                                                                     |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `[CCR retrieve hash=<24hex> chars=N]` | Veliki blok je pohranjen sa adresom sadržaja.                                                                                                  | Pozovi `omniroute_ccr_retrieve` sa** 24-hex heš kopiran doslovno** da vratite originalni tekst.                                                                                                              |
| `[dedup:ref sha=…]`                   | `session-dedup` je uklonjen tekst koji je već poslan u ranijem dijelu iste sesije. Ovo je an** namjerno osvrtanje** , a ne gubitak ili greška. | Uradi** ne** pozovite bilo koji alat i uradite** ne** pokušajte da ga "rekonstruišete". Prvo pojavljivanje teksta je kanonska kopija; trenutni red se nikada ne prepisuje, već se dedupira u kasnijem krugu. |

`[dedup:ref]` look-back je namjerna odluka protokola — nema rekonstrukcije prije slanja. Tretirajte to kao da je "ovaj tačan tekst već bio na žici ranije u ovoj sesiji."

### Preduslovi za klijente

- **Ključ (stdio):** stdio pozivalac ne nosi identitet po zahtevu, tako da se autentifikuje sa `OMNIROUTE_API_KEY` (podešen u `env` serveru MCP ). Bez toga pozivatelj je anoniman i alati koji zahtijevaju principal mogu degradirati.
- **`tools[]` je preduslov za injekciju.** Ubrizgava se CCR instrukcija protokola preuzimanja (#8033).** samo** kada oglašeni `tools[]` zahtjeva dokaže da klijent zaista može doći do `omniroute_ccr_retrieve`. Podudaranje je podudaranje zadnjeg segmenta ograničeno separatorom (`__`, `.`, `/`, `:`) — nikada nije goli podniz — tako da se ime u prostoru između imena kao što je `mcp__gateway__omniroute_ccr_retrieve` i dalje računa. Odsutan ili nepodudaran `tools[]` znači da se instrukcija _nije_ ubrizgava po dizajnu.
- **`codemode:false` (OpenCode klijenti).** OpenCode podrazumevano je na Code Mode, koji oglašava samo svoje izvorne alate modelu i** ne** stavite MCP alate na izvornu `tools[]` listu. Postavite `codemode: false` na unos MCP servera tako da se `omniroute_ccr_*` alati oglašavaju. Ovo je a** klijent** postavka, a ne OmniRoute. Još ne dobija CCR instrukciju ubrizganu: OpenCode imenuje alat `<server>_<tool>`, tako da server nazvan `omniroute` izlaže `omniroute_omniroute_ccr_retrieve`, a `_` nije jedan od podudarnih separatora.
- **Direktori.** Skladištenje i dohvaćanje su izolirani prema ovlaštenom principalu (po API ključu). Ključ vidi samo svoje blokove.

### Opseg po alatu

Sprovođenje opsega je uvijek uključeno za HTTP/SSE pozivaoce uskog opsega. `omniroute_` CCR alati zahtijevaju:

| Alat                     | Obim                |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Opseg koji nedostaje vraća an** rezultat greške alata MCP** (`isError: true`, a ne HTTP 403 — `403 LOCAL_ONLY` je odvojena petlja za zaštitu rute auth): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimalni daljinski ključ može držati `mcp:connect` (ovlašćuje `/api/mcp/` lokalno izdvajanje) plus specifičan read/write opseg koji mu je potreban.

### Klijentska matrica

| Klijent             | Transport                                        | Konfiguracija za korištenje                                                                                                                                                                                                                                 | `tools[]` reklamirao? (→ CCR instrukcija ubrizgana)                                                                                                                                                          |
| ------------------- | ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Claude Code         | streamable-http                                  | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                           | Da — MCP-sposoban; ubrizgan.                                                                                                                                                                                 |
| Cursor / Cline      | `stdio`** ili** `streamable-http`                | stdio: `omniroute --mcp` sa `OMNIROUTE_API_KEY` u `env`; ili udaljeni MCP ulaz koji pokazuje na `http://localhost:20128/api/mcp/stream` (pogledajte [Vodič za postavljanje → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Da — reklamira `omniroute_ccr_*` alate.                                                                                                                                                                      |
| OpenCode            | streamable-http                                  | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plus `codemode: false`                                                                                                                                                            | Alati koji se oglašavaju samo sa `codemode: false`; instrukcija još uvijek nije ubrizgana, jer se `omniroute_omniroute_ccr_retrieve` ne podudara (pogledajte [Preduslovi klijenta](#client-prerequisites) ). |
| OpenAI-kompatibilan | HTTP kompatibilan s OpenAI (završetak razgovora) | standardni klijent za dovršavanje razgovora u odnosu na krajnju tačku kompatibilnu s OpenAI                                                                                                                                                                 | **Nikad** — običnom OpenAI-kompatibilnom pozivaocu nikada nije rečeno da pozove alat, a instrukcija se ne ubrizgava.                                                                                         |

### Ograničenja preuzimanja i paginacija

Rezultati teksta alata MCP su isečeni oko `mcpAccessibility.maxTextChars` (podrazumevano `50000`). `full` preuzimanje bloka je ograničeno na 256 KiB —** nema neograničenog potpunog preuzimanja** . Kada je `chars=N` bloka velik, prelistajte ga umjesto da povlačite cijelu stvar:

- pravilo:**`chars > 40000` → koristite `mode`** , nikad puna.
- `mode:"grep"` — regex `pattern` uparen red po red, do 1000 podudarnih linija (`unique: true` ispušta ponavljanja), najjeftinije za "pronađi jedan red koji mi treba."
- `mode:"lines"` — 1-indeksirani raspon linija; treba i `start` i `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` linije.
- `mode:"stats"` — broj redova, karaktera i bajtova bez tijela.

Koristite `mode:"lines"` sa `start`/`end` da hodate po dugačkom bloku stranica umjesto da tražite cijelu stvar odjednom.

### Imenovanje alata

Alat za dohvaćanje se trenutno zove `omniroute_ccr_retrieve` (prefiks `omniroute_` je zaobilazno rješenje za međuserverske kolizije imena). Čišće ime alata sa ograničenim sufiksom i popravka za MCP JSON rezultate skraćene u sredini niza prate se kao uzvodno praćenje; ova stranica dokumentira samo trenutno, isporučeno ponašanje.

### Životni ciklus sesije

Streamable-HTTP sesije ne rade i server ih koristi; prozor mirovanja je `MCP_SESSION_IDLE_MS` konstanta (navedena imenom, a ne tvrdokodiranom vrijednošću, tako da se ova stranica ne pomjera kada se promijeni). Simptom neaktivne sesije je HTTP 404 sa `Unknown Mcp-Session-Id` — a lijek je ponovno povezivanje ili ponovno pokretanje sesije,** ne** za rotiranje ključa, promjenu opsega ili preimenovanje alata.

## API Surface

| Ruta                                   | Svrha                                                                     |
| -------------------------------------- | ------------------------------------------------------------------------- |
| `/api/settings/compression`            | Globalne postavke kompresije (uključuje `mcpAccessibility` konfiguraciju) |
| `/api/compression/preview`             | Pregledajte bilo koji način kompresije                                    |
| `/api/compression/language-packs`      | Navedite dostupne jezičke pakete Caveman                                  |
| `/api/context/caveman/config`          | Alias postavki Caveman                                                    |
| `/api/context/rtk/config`              | RTK zadane postavke i postavke                                            |
| `/api/context/rtk/filters`             | RTK filter katalog                                                        |
| `/api/context/rtk/test`                | RTK preview/test krajnja tačka                                            |
| `/api/context/rtk/raw-output/[id]`     | Ovjereno redigovano obnavljanje sirovog izlaza                            |
| `/api/context/combos`                  | Compression combo CRUD                                                    |
| `/api/context/combos/[id]/assignments` | Routing-combo dodjela CRUD                                                |
| `/api/context/analytics`               | Alias analitike kompresije                                                |

Rute upravljanja zahtijevaju autentifikaciju upravljanja ili provjere politike API ključeva.

## MCP Tools

Kompresija otkriva pet MCP alata:

| Alat                                | Obim                | Svrha                                    |
| ----------------------------------- | ------------------- | ---------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Postavke, analitika, keš statistika      |
| `omniroute_compression_configure`   | `write:compression` | Ažurirajte globalne postavke             |
| `omniroute_set_compression_engine`  | `write:compression` | Postavite način rada i opcijski cjevovod |
| `omniroute_list_compression_combos` | `read:compression`  | Popis kombo kompresije                   |
| `omniroute_compression_combo_stats` | `read:compression`  | Pročitajte combo/engine analytics        |

## Opseg i isključenja

**Ugrađivanje nikada nije komprimirano.** `open-sse/handlers/embeddings.ts` nikada ne poziva nikakav kompresijski mehanizam — request/response tijela prolaze ravno do izvršioca netaknuta. Ovo je danas strukturalno (ugrađivanje i dovršetak razgovora su disjunktni rukovaoci), a ne provjera vremena izvođenja, ali znači da problem vektorske distorzije u #8034 nema površinu ekspozicije na putu ugrađivanja.

**Per-model/endpoint filter za isključenje (#8034).** Za završetak razgovora, operater može imenovati ID-ove modela / `provider/model` ciljeve koji se nikada ne smiju komprimirati — zaštitni ograda korisnim ako se kompresija ikada kasnije poveže bliže stazi koja je susjedna ugrađivanjima, i općenito korisna za bilo koji model čiji je tačan bajt za bajt prompt važan (determinističke procjene, prefiks osjetljiv na keš itd.).

- Polje postavki: `exclusions?: string[]` na globalnoj konfiguraciji kompresije (`GET`/`PUT /api/settings/compression`), postojano preko postojećeg prostora `key_value` kompresije (`src/lib/db/compression.ts`) — nema nove tablice.
- Kartica kontrolne table:** Kontrolna tabla → Kompresija → Izuzeci** (`/dashboard/compression/exclusions`).
- Sintaksa uzorka: `*` je jedini zamjenski znak. Svaki drugi metaznak regularnog izraza u obrascu se izbjegava prije podudaranja, tako da `gpt-5.6` odgovara samo literalnom nizu, nikad `gpt-5x6` (ReDoS-siguran, ograničen, bez ugniježđenih kvantifikatora). Uzorci se poklapaju neosjetljivo na velika i mala slova i sa golim modelom id-om i `provider/model` kompozitnim — `gpt-5-6`, `openai/gpt-5-6` i `openai/*` svi rade, a `*` sam isključuje svaki model.
- Podudaranje: `isCompressionExcluded()` / `normalizeCompressionExclusions()` u `open-sse/services/compression/exclusions.ts`. `chatCore.ts` provjerava isključeni cilj odmah nakon rješavanja postavki kompresije,** pre nego što se motor pokrene** , i tretira podudaranje točno kao da je kompresija globalno onemogućena — tijelo zahtjeva je dokazivo identično bajtovima. Preskakanje se snima putem `writeCompressionSkip(..., "excluded")` radi vidljivosti analitike.
- Default (empty/absent lista): identično pre-#8034 ponašanju — ništa nije isključeno.

## Poznata ograničenja

- **LLMLingua-2 (SLM) zahtijeva ko-locirane opcione deps.** Radnik se pokreće samo u produkcijskoj verziji kada su `@atjsh/llmlingua-2` + peer-ovi ko-locirani u `dist/node_modules` (pogledajte `scripts/build/colocateOptionals.mjs`, #4286). Bez njih se motor ne otvara (vraća originalni tekst). Radnička rezolucija više ne ovisi o `import.meta.url` (umire u samostalnom paketu) — se sidri na vrijeme izvođenja cwd / `argv[1]`.
- **Jezički paketi Caveman `de` / `fr` / `ja` su djelomični.** Oni isporučuju `context` + `filler` + `structural` pravila, ali ne `dedup` / `ultra` pakete, tako da intenzitet `ultra` nije jači od `full` za te jezike (koriste samo svoja vlastita pravila — nema tihog vraćanja na engleska pravila `dedup`/`ultra`, koja bi pokvarila strani tekst). `en` / `es` / `id` / `pt-BR` su završeni. Doprinosi `dedup.json` + `ultra.json` za djelimične pakete su dobrodošli.
- **Naslagana telemetrija navodi samo motore koji su komprimirani.** Korak naslaganog cjevovoda čiji je motor radio, ali je proizveo 0% uštede vraća `stats:null` i tako se ne pojavljuje u `engineBreakdown` — nerazlučivo od koraka koji je preskočen. Razlikovanje "pokrenuto, 0 %" od "preskočenog" zahtijevalo bi promjenu modela kvara i odgađa se.

## Validacija

Fokusirane kapije za ovo područje su:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
