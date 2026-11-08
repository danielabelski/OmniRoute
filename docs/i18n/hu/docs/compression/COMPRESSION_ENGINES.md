# Compression Engines (Magyar)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompresszió a motorszerződések köré épül. Egy mód futtathat egy motort közvetlenül (`caveman` vagy `rtk`), vagy egy determinisztikus halmozott folyamatot, amely több motort is végrehajt egymás után.

## Módok

| Mód          | A motor útja                                                                                                  | Szánt bemenet                                          |
| ------------ | ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| `off`        | egyik sem                                                                                                     | Pontos azonnali megőrzés                               |
| `lite`       | Caveman lite segítők                                                                                          | Alacsony kockázatú állandó tisztítás                   |
| `standard`   | Barlanglakó ősember                                                                                           | Természetes nyelvű azonnali páralecsapódás             |
| `aggressive` | Caveman + history/tool összefoglalók                                                                          | Hosszú csevegés                                        |
| `ultra`      | Caveman + metsző segítők                                                                                      | Kontextus-korlát helyreállítás                         |
| `rtk`        | RTK                                                                                                           | Terminál, shell, build, teszt és git kimenet           |
| `omniglyph`  | OmniGlyph                                                                                                     | Context-as-image a natív szolgáltató vezetékén         |
| `stacked`    | Csővezeték. A kérés alapértelmezett értéke `session-dedup -> lite`. `rtk -> caveman` feliratkozási lehetőség. | Vegyes szerszámnaplók és próza, maximális megtakarítás |

### OmniGlyph kompressziós profilok

A `omniglyph` motor (csomag `omniglyph`, 1.4.0 +) egy elnevezett szemantikai profilt fogad el, globálisan beállítva `omniglyph.profile` keresztül a tömörítési beállításokban, vagy lépésenként a halmozott folyamat lépéskonfigjában:

| Profil        | Határ                                                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------------------------ |
| `aggressive`  | Alapértelmezett. A politika a közzétett bevételek — képrendszert, eszközdokumentumokat és sűrű előzményeket mértek |
| `balanced`    | Megtartja az élő állapotot natívan, megvédi az utolsó 8 fordulatot, összeomolja a régebbi zárt történelmet         |
| `coding-safe` | Megőrzi a jogosultságot, a szerszámsémákat és az élő szerszám kimenetet natívan, védi az utolsó 12 fordulatot      |
| `passthrough` | Útvonalak átalakítás nélkül; a motor kimarad                                                                       |

A profil a** mennyezet, nem padló** : a csomagban található `mergeCompressionProfileOptions` nem engedi, hogy a hívó felülbírálja a veszteséges sáv újbóli megnyitását a profil zárva, így a lépésenkénti `preserveSystemPrompt: false` nem engedélyezheti újra a rendszertömörítést `coding-safe` alatt.

Ezen a kódbázison mérve: `coding-safe` és `balanced` a maximumra emeli `minCompressChars`, és natívan tartja a rendszert, az eszközsémákat és az eszközeredményeket, így a munkamenet, amely még nem halmozott fel történelmet, megáll `below_min_chars` nél, és a motor semmit sem alakít át. Ezért az alapértelmezett `aggressive` nem pedig a legbiztonságosabb profil.

A csomag feloldja saját modell hatókörét és profilját a környezet konfigurációjából. OmniRoute soha nem ruházza át a döntést: az adapter a modellkaput a csomag legkorlátozóbb hatóköréhez rögzíti, így a gazdagép környezet beállításai csak szűkíthetik az engedélyezési listát, soha nem tágíthatják ki OmniRoute mért bevételeinél túl.

## Motornyilvántartás

A rendszerleíró adatbázis `open-sse/services/compression/engines/registry.ts` ban található. A motorok közös szerződést kötnek:

- `id`: stabil motorazonosító, például `caveman` vagy `rtk`
- `apply(text, config)`: a halmozott folyamatok által használt örökölt végrehajtási útvonal
- `compress(input, config)`: elsődleges végrehajtási útvonal, amely szöveget ad vissza + stats
- `getConfigSchema()`: az érvényes konfiguráció JSON-sémaszerű alakját adja vissza
- `validateConfig(config)`: `{ valid, errors[] }` adja vissza

A regisztráció `registerCompressionEngine(engine)` (vagy haladó esetekben `registerEngine` ) használja, amely meghívja `assertValidEngine()` és `validateConfig(defaultConfig)` az elfogadás előtt. `unregisterCompressionEngine(id)` segítségével távolítsa el a motort futás közben.

`strategySelector.ts` a sűrítés megkezdése előtt regisztrálja a beépített motorokat. Ez lehetővé teszi, hogy az előnézet, a futásidejű tömörítés, a halmozott mód, a tesztek és a jövőbeli motorok ugyanazt a végrehajtási útvonalat használják.

### MCP leírás tömörítése (kapcsolódó)

Egy külön beállításjegyzék tömöríti MCP eszközleíró metaadatokat — rendszerleíró adatbázis szintjén, lásd `open-sse/mcp-server/descriptionCompressor.ts` és [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Újra felhasználja a Caveman-szabályokat, de az eszközök metaadatai alapján működik, nem pedig a hasznos terheket kéri.

### További beépített motorok

A Caveman, RTK és LLMLingua-2 mellett a nyilvántartó több speciális veszteségmentes / szerkezeti motort szállít (halmozott csővezetékekhez, játszótérhez és tesztekhez):

| Motor         | Id              | Mit csinál                                                                                                                                                                       |
| ------------- | --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): a nagy összefüggő szövegblokkokat tartalom-címzett hivatkozásokra cseréli, így repeated/large blokkokat egyszer küldi el, majd hivatkozik rájuk. |
| fejtér        | `headroom`      | SmartCrusher (H3 + N5): homogén JSON-tömb hasznos terhek veszteségmentes táblázatos tömörítése oszlopos `[N rows]` formába.                                                      |
| ionizáló      | `ionizer`       | Head/middle/tail sor mintavételezés nagyon nagy homogén blokkokhoz, az elided közepét CCR tartalom-címzett referenciaként tárolva.                                               |
| session-dedup | `session-dedup` | Tartalomközpontú körök közötti deduplikáció (TokenMizer által inspirált): kiküszöböli a munkamenet korábbi fordulóiban már látott szöveget.                                      |

**CCR retrieve-protocol utasítás (#8033):** Amikor először CCR lecseréli ≥ 1 blokkot egy kérésben, a motor egyetlen, idempotens `system` üzenetet fűz (a `[CCR protocol]` őrzővel vezet), amely megtanítja a hívónak a jelölőt → tool kontraktus: mit jelent a `[CCR retrieve hash=<24hex> chars=N]` marker, hogy a hash-t szó szerint kell másolni (mind a 24 hexa zárolás oka valószínűleg nem található" hiányzik), és a — `[dedup:ref sha=...]` azt jelenti, hogy "nézz vissza a történelembe", nem pedig "hívd a szerszámot". A jegyzet be van fecskendezve** csak akkor, ha a hívó által hirdetett `tools[]` bizonyítja, hogy valóban elérheti `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — egy egyszerű OpenAI-kompatibilis hívó az eszköz nélkül soha nem kap utasítást arra, hogy olyat hívjon meg, amit nem tud elérni. Az idempotenciát úgy kényszerítik ki, hogy a beadás előtt átvizsgálják az üzenetelőzményeket az őrszem után, így a többfordulós kérések (amelyek a korábbi üzeneteket játsszák le) nem halmozzák fel körönként egyszer a jegyzetet.

## Barlanglakó ősember

A Caveman mód a normál próza szemantikai sűrítésére összpontosít:

- megőrzi a kódblokkokat, URLs, JSON, útvonalakat és strukturált adatokat
- eltávolítja a kitöltést, a fedezetet, az ismétlődő kontextust és a bőbeszédű összekötő kifejezéseket
- támogatja a nyelvtudatos fájlszabálycsomagokat a `open-sse/services/compression/rules/`
- elérhető marad a régi `standard`, `aggressive` és `ultra` módokon keresztül

A műszerfal felülete `Dashboard -> Context & Cache -> Caveman`.

A Caveman upstream `~75%` kevesebb kimeneti tokenről, `65%` átlagos kimeneti megtakarításról számol be a `22-87%` tartománnyal rendelkező benchmarkokban és egy `~46%` bemenet-tömörítő eszközről. OmniRoute a Caveman bemeneti oldali számát használja a halmozott prompt/context megtakarítások dokumentálásakor; A Caveman kimeneti mód külön válasz-viselkedési funkció marad.

## RTK

RTK mód a parancs- és eszközkimenetre összpontosít:

- olyan kimeneti osztályokat észlel, mint `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go tesztek, TypeScript/Vite/Webpack buildek, ESLint, npm audit/installs, Docker naplók, shell `find`/`grep`, veremnyomok és általános naplók
- 49 JSON szűrőt alkalmaz `open-sse/services/compression/engines/rtk/filters/` től
- támogatja az RTK-stílusú deklaratív folyamatot: ANSI lehúzás, csere, egyeztető kimenet rövidzárlat, strip/keep sorok, soronkénti csonkítás, head/tail/max-line csonkítás és on-empty tartalék
- Támogatja a bizalmi projektszűrőket `.rtk/filters.json` ban és a globális szűrőket `DATA_DIR/rtk/filters.json` ben
- ANSI szekvenciák, folyamatzaj, ismétlődő sorok és nem hasznos kazánok kivágása
- megőrzi a végrehajtható hibákat, a figyelmeztetéseket, az összefoglalókat, a módosított fájlokat és a kontextust
- opcionálisan megőrizheti a redaktált nyers kimenetet recovery/debugging számára hitelesített felügyeleti útvonalakon keresztül

A műszerfal felülete `Dashboard -> Context & Cache -> RTK`.

Az egyéni szűrők, a bizalom, az ellenőrzés és a nyers kimenet helyreállításának működési részletei [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md) ban.

RTK upstream `60-90%` megtakarításokat jelent a parancs-kimeneti tömörítéshez. A README példája egy 30 perces Claude kód munkamenetet mutat be, amely `~118,000` tokentől `~23,900`-ig vagy `79.7%` elmentettig megy.

## LLMLingua-2 (szemantikus metszés)

LLMLingua-2 mód teljesít** szemantikus jelzőmetszés** prózában egy kis ONNX token osztályozóval, amely kiegészíti a szabályalapú Caveman és RTK motorokat:

- csak a nem rendszerüzenetekben tömöríti a prózát; a bekerített kódblokkok és más megőrzött konstrukciók soha nem változnak
- a `@atjsh/llmlingua-2` háttérprogramot (ONNX via `@huggingface/transformers`) egy worker szálban futtatja, így a modellkövetkeztetés soha nem blokkolja a kérés eseményhurkot
- van** egymásra rakható** (`stackPriority` 35): halmozott csővezetékben a szerkezeti motorok (CCR, session-dedup, headroom, Caveman) után fut, de `ultra` előtt, mivel a szemantikai metszés a már szerkezetileg tömörített szövegeknél a leghatékonyabb — pl `rtk -> caveman -> llmlingua`
- **hiba esetén megnyílik** (hiányzik az opcionális deps, a worker spawn, a modell betöltése, a következtetés vagy az időtúllépés) → az eredeti szöveg változatlan formában kerül visszaadásra, soha nem hiba

Motor helye: `open-sse/services/compression/engines/llmlingua/`. A műszerfal felülete `Dashboard -> Context & Cache -> LLMLingua`.

### Modellek

Az alapértelmezett modell a**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, gyors). Nagyobb pontosságú** BERT-bázis** modell (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) a motorkonfiguráció `model` mezőn keresztül érhető el. `@huggingface/transformers` lustán letölti a kiválasztott modellt a HuggingFace Hubból `${DATA_DIR}/models/llmlingua` -ba az első híváskor (`modelStore.ts`); a `modelPath` konfiguráció felülírása inkább egy helyi másolatra irányítja (offline / légrés telepítések).

### Opcionális függőségek és igény szerinti telepítés

A kivágható LLMLingua futásidejű peer verem az** választható** . Két csomagot `optionalDependencies` nek nyilvánítanak `package.json` ben, és megőrzik** külső** a termelési build alapján (`scripts/build/prepublish.ts` nem köti össze őket):

| Csomag               | Verzió (pin) | Megjegyzések                                        |
| -------------------- | ------------ | --------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`      | Belépőcsomag; a többieket egyenrangúnak nyilvánítja |
| `js-tiktoken`        | `^1.0.20`    | Tokenizátor                                         |

`@huggingface/transformers` rögzítve van `^4.2.0` -ben (megosztva a helyi beágyazási útvonallal, és az önálló kötegbe is be van nyomva); `@atjsh/llmlingua-2@2.0.5` `"^3.5.2 || ^4.0.0"`-vel párosul, így Transformers.js v3 és v4 is támogatott. A 2.0.4 óta `@atjsh/llmlingua-2` már nincs szüksége `@tensorflow/tfjs`, ami eltávolította a legnagyobb egyetlen közreműködőt (TensorFlow.js) a SLM veremből. Csak a fenti két csomag metszhető SLM társ. A szabványos `npm install` (dev) automatikusan telepíti az opcionális veremet, hacsak nem hagyja ki az opcionális függőségeket.

**Miért igény szerint:** az npm által kiadott csomag, az önálló csomag és a Docker képszállító** nélkül** ezek a depek, hogy karcsúak maradjanak. Ha nincsenek jelen, a dolgozó függőségi kapuja (a `@atjsh/llmlingua-2` feloldó szonda `worker.ts` ben) meghibásodik, és a motor** hangtalanul megnyílik** — LLMLingua kiválasztása no-op lesz (a szöveg változatlan formában jelenik meg, nincs hibanaplózás). A levágott környezetben történő aktiváláshoz telepítse az opcionális köteget:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

A `@tensorflow/tfjs` eltávolítás (2.0.4 +) kiküszöböli a korábban domináns ~ 800 MB közreműködőt — a fennmaradó lábnyom a transformers.js + onnxruntime-node runtimes, plusz a TinyBERT modell (~ 57 MB) az első használatkor letöltött (nem npm-n keresztül).

Környezetenként:

- **Fejlesztő / `npm install`** — automatikusan települ, hacsak nem teljesítette `--omit=optional` (vagy `--no-optional`). Nincs szükség intézkedésre.
- **Globális npm (`npm i -g omniroute`) / önálló** — futtassa a fenti install parancsot a telepített csomagok könyvtárában, vagy telepítse újra az opcionális deps kihagyása nélkül.
- **Docker** — hozzáadja az install parancsot egy származtatott képréteghez; a közzétett kép kialakítása vékony.
- **VPS (PM2)** — telepítse az alkalmazás `node_modules` fájljába, majd indítsa újra a folyamatot, hogy a dolgozó újra megvizsgálja a kaput.
- **Raw Next önálló (`npm run build` → `.build/next/standalone/server.js`)** — az önálló nyomkövető hajók NEITHER a dolgozót és az opcionális mélyedéseket, így a motor hangtalanul meghibásodik. `scripts/build/colocate-standalone.mjs` újra alkalmazza mindkettőt (a dolgozó + opcionális mélységi bezárását építi be az önálló fába); minden összeállítás után automatikusan fut a `postbuild` npm hook-on keresztül. Idempotens, hibamentes, ha a depek hiányoznak.

**Ellenőrizze, hogy aktív-e:** LLMLingua kiválasztása esetén a valódi próza valójában összezsugorodik (a motor leállítja a hibanyitást), és az első kérés elindítja a modell letöltését `${DATA_DIR}/models/llmlingua` be. A kapu szándékosan csak `@atjsh/llmlingua-2` — vizsgálja, a többi peer csak ESM-et használ, és `require.resolve` akkor is dob rájuk, ha — jelen van, így a dolgozó továbbra is megszakad, ha valamelyik társ valóban hiányzik a `import()` időpontban.

## Halmozott csővezetékek

A halmozott mód a folyamat lépéseit sorrendben futtatja. Az alapértelmezett érték:

```txt
rtk -> caveman
```

Használja ezt a kódoló ügynök munkamenetekhez, ahol a prompt kombinálja a parancskimenetet az emberi vagy asszisztens prózával. RTK először csökkenti a zajos eszköznaplókat, majd a Caveman tömöríti a megmaradt természetes nyelvet.

A folyamat lépései `stackedPipeline` val konfigurálhatók a tömörítési beállításokban vagy a tömörítési kombinációkon keresztül.

Ha mindkét motor ugyanazt a hasznos terhet csökkenti, a megtakarítás:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP akadálymentesítési faszűrő

A MCP akadálymentesítési fa intelligens szűrője egy végrehajtás utáni tömörítési réteg, amely MCP n fut.** eszköz eredményeit** , nem felszólításokra vagy kontextusra. Megcélozza a részletes akadálymentesítési fát és a böngésző pillanatképeit, amelyeket olyan eszközök adnak vissza, mint Playwright, a számítógép-használat és a böngésző-automatizálási MCP szerverek.

### Mit csinál

1. **Zajcsillapítás** — eltávolítja az üres generic/text bejegyzéseket (`- generic:`, `- text: ""`)
2. **Testvér összeomlás** — ha ≥ `collapseThreshold` (alapértelmezett 30) egymást követő sorok szerkezeti ismétlődések, összecsukja őket az első `collapseKeepHead` (alapértelmezett 10) sorokba + a számlálás összegzése + az utolsó `collapseKeepTail` (alapértelmezett 5) sorok
3. **Ref megőrzés** `[ref=eXX]` Playwright/computer-use által igényelt — horgonyokhoz soha nem szabad hozzáérni
4. **Kemény csonkítás** — ha az összecsukás után a szöveg továbbra is meghaladja `maxTextChars` (alapértelmezett 50 000), akkor a navigációs utalással csonkolja, hogy az ügynök folytathassa a munkát

### A motor helye

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfiguráció

`compression.mcpAccessibility` vezérli a globális beállításokban (migráció 056). Alapértelmezett konfiguráció:

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

A szűrő csak azokra a szerszámeredmény hasznos terhekre vonatkozik, amelyek `type` értéke `"text"`, és hossza meghaladja `minLengthToProcess`. Nincs hatással az azonnali tömörítésre vagy a hasznos terhelésekre.

### Várható megtakarítás

60–80%-a a böngésző pillanatfelvételi eszközének eredményeinek, az oldal bonyolultságától függően. Az összecsukási algoritmus O(n) a sorszámban, és elhanyagolható késleltetést ad hozzá.

### Ez a szűrő a fenti kompressziós motorokhoz képest

| Vonatkozás    | Caveman / RTK / Halmozott   | MCP akadálymentesítési szűrő           |
| ------------- | --------------------------- | -------------------------------------- |
| Cél           | Kérési promptok / kontextus | MCP eszköz eredményei                  |
| Kioldó        | Tömörítési mód beállítása   | `compression.mcpAccessibility.enabled` |
| Hatály        | Minden SSE üzenet           | Csak az eszköz eredményei              |
| Ref horgonyok | N/A                         | Feltétel nélkül megőrizve              |

---

## Tömörítési kombók

A tömörítési kombók neve tömörítési profilok, amelyek az útválasztási kombókhoz rendelhetők:

- `compression_combos`: tárolási mód, csővezeték, RTK konfiguráció, nyelvi konfiguráció és alapértelmezett jelölő
- `compression_combo_assignments`: a tömörítési kombót leképezi egy útválasztási kombóra
- A futásidejű integráció feloldja a hozzárendelt tömörítési kombinációt, mielőtt az általános kombinációt felülbírálná
- az elemzések közé tartozik `compression_combo_id` és `engine`

Műszerfal felülete: `Dashboard -> Context & Cache -> Compression Combos`.

## Előfeltételek / kezelői útmutató (CCR & session-dedup)

CCR (`ccr`) és `session-dedup` lecseréli vagy megszünteti a szöveget, és hagyja a a** jelző** mögött. Ez a szakasz a kezelői referencia a kliens bekötéséhez, a két jelölő leolvasásához és az elidézett tartalom lekéréséhez vagy diagnosztizálásához. Az egyes motorok mechanikáját fentebb tárgyaltuk; ez a "hogyan futtassam" réteg.

### Szállítások és végpontok

A CCR eszközöket megjelenítő MCP szervert háromféleképpen lehet elérni. Az alapértelmezett URL alapérték a `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Szállítás                            | URL / parancs                           | Megjegyzések                                                                                                                                    |
| ------------------------------------ | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Streamálható HTTP (kliens, ajánlott) | `http://localhost:20128/api/mcp/stream` | A végpont, amellyel a jelenlegi MCP ügyfelek beszélnek.                                                                                         |
| Legacy SSE singleton                 | `http://localhost:20128/api/mcp/sse`    | Régebbi egyszemélyes szállítás. Azt** bezár** streamelhető munkamenetek; `streamable-http` klienseket használj `/api/mcp/stream` ellen, ne ezt. |
| stdio                                | `omniroute --mcp`                       | IDE MCP konfigurációhoz, amely elindítja a folyamatot. Nincs `--dev` zászló; `omniroute --mcp` az stdio belépési pontja.                        |

### Tárolási szintek (ami túléli az újraindítást)

CCR egy** kétszintű** bolt, nem csak a memóriában:

- **Forró memóriaszint** — blokkonkénti sapka 2 MiB, főként 16 MiB, globális 64 MiB. A bejegyzések alapértelmezett értéke 24 órás TTL (maximum 7 nap). A memóriából való teljes MCP lehívás korlátja 256 KiB; minden nagyobb még mindig elérhető a ranged / grep módokon keresztül.
- **Tartós SQLite szint** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, alapértelmezés szerint be van kapcsolva) — támogatja a memórián belüli réteget, így a blokk túléli LRU kilakoltatást, újraindítást vagy egy másik példányon történő visszakeresést. A sor megtartja a blokk TTL, így a TTL előtti blokk mindkét szintről eltűnik.

Három védőburkolat tartja a tartós réteget behatárolva — egy blokk csak a memóriában marad, ha:

1. vége a blokknak** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. a futási környezet felhő futási környezet (nincs helyi lemez);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Tehát az „eltűnt blokk” nem egy általános újraindítási történet: a sub-512 KB blokk egy helyi, nem felhőalapú futási környezetben túléli az újraindítást a tartós rétegen keresztül, amíg TTL ki nem fogy. Lásd [a környezeti hivatkozást](../reference/ENVIRONMENT.md) a változóhoz.

### A két jelző

| Jelző                                 | Jelentése                                                                                                                                                                | Mit kell tennie a modellnek                                                                                                                                                                                   |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Egy nagy blokkot tartalom-címzetten tároltak.                                                                                                                            | Hívja `omniroute_ccr_retrieve` a** 24 hexadecimális hash szó szerint másolva** hogy visszakapja az eredeti szöveget.                                                                                          |
| `[dedup:ref sha=…]`                   | `session-dedup` elided szöveg, amelyet már elküldtek ugyanannak a munkamenetnek egy korábbi fordulójában. Ez egy** szándékos visszatekintés** , nem veszteség vagy hiba. | Tedd** nem** hívjon bármilyen eszközt és tegye** nem** próbálja meg "rekonstruálni". A szöveg első előfordulása a kanonikus másolat; az aktuális kört soha nem írják át, hanem egy későbbi körben dedupálják. |

A `[dedup:ref]` visszatekintés szándékos protokoll döntés — nincs küldés előtti rekonstrukció. Tekintse úgy, hogy "ez a pontos szöveg már korábban is megjelent ebben a munkamenetben".

### Ügyfél előfeltételei

- **Kulcs (stdio):** az stdio hívó nem hordoz kérésenkénti identitást, ezért `OMNIROUTE_API_KEY` hitelesít (a MCP szerver `env` van beállítva). Enélkül a hívó névtelen, és az igazgatót igénylő eszközök leromolhatnak.
- **`tools[]` a befecskendezés előfeltétele.** A CCR retrieve-protocol utasítás (#8033) be van fecskendezve** csak** amikor a kérés hirdetett `tools[]` bizonyítja, hogy az ügyfél valóban elérheti `omniroute_ccr_retrieve`. Az egyezés egy zárószegmenses egyezés, amelyet elválasztó (`__`, `.`, `/`, `:`) határol. — soha nem csupasz — részkarakterlánc, így a névteres név, például `mcp__gateway__omniroute_ccr_retrieve` továbbra is számít. A hiányzó vagy nem egyező `tools[]` azt jelenti, hogy az utasítás _nincs_ befecskendezve.
- **`codemode:false` (OpenCode ügyfelek).** OpenCode alapértelmezett kódmódja, amely csak a natív eszközeit hirdeti a modellnek és** nem** tegye MCP eszközöket a natív `tools[]` listára. Állítsa be `codemode: false` a MCP szerverbejegyzésben, hogy a `omniroute_ccr_*` eszközök megjelenjenek. Ez a** ügyfél** beállítás, nem egy OmniRoute. Még nem kapja meg a CCR utasítást: OpenCode egy eszközt `<server>_<tool>` néven nevez el, így a `omniroute` nevű szerver felfedi `omniroute_omniroute_ccr_retrieve`, és `_` nem tartozik az illesztett elválasztók közé.
- **igazgatók.** A tárolás és a visszakeresés hitelesített főként ( API kulcsonként) elkülönítve történik. Egy kulcs csak a saját blokkjait látja.

### Hatókör szerszámonként

A hatókör érvényesítése mindig be van kapcsolva a szűk hatókörű HTTP/SSE hívóknál. A `omniroute_` CCR eszközök a következőket igénylik:

| Eszköz                   | Hatály              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

A hiányzó hatókör egy**MCP szerszámhiba eredménye** (`isError: true`, nem egy HTTP 403 — a `403 LOCAL_ONLY` a külön visszacsatolásos útvonalőrző hitelesítés): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Egy minimális távoli kulcsban tárolható `mcp:connect` (engedélyezi a `/api/mcp/` csak helyi kivágást), valamint a szükséges read/write hatókör.

### Kliens mátrix

| Ügyfél              | Szállítás                                      | Konfig a használathoz                                                                                                                                                                                                                                     | `tools[]` hirdetett? (→ CCR utasítás beadva)                                                                                                                                               |
| ------------------- | ---------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Claude kód          | streamelhető-http                              | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                         | Igen — MCP-képes; befecskendezve.                                                                                                                                                          |
| Cursor / Cline      | `stdio`** vagy** `streamable-http`             | stdio: `omniroute --mcp` `OMNIROUTE_API_KEY` a `env`; vagy egy távoli MCP -bejegyzés, amely `http://localhost:20128/api/mcp/stream` re mutat (lásd: [Telepítési útmutató → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Igen — reklámozza a `omniroute_ccr_*` eszközöket.                                                                                                                                          |
| OpenCode            | streamelhető-http                              | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plusz `codemode: false`                                                                                                                                                         | Csak `codemode: false` hirdetett eszközök; az utasítás még mindig nincs beadva, mert `omniroute_omniroute_ccr_retrieve` nem egyezik (lásd [Kliens előfeltételek](#client-prerequisites) ). |
| OpenAI kompatibilis | OpenAI-kompatibilis HTTP (csevegés befejezése) | szabványos csevegés-kiegészítő kliens az OpenAI-kompatibilis végponttal szemben                                                                                                                                                                           | **Soha** — egy sima OpenAI-kompatibilis hívónak soha nem mondják, hogy hívja az eszközt, és az utasítást sem adják be.                                                                     |

### Visszakeresési korlátok és oldalszámozás

MCP eszköz szöveges eredményei `mcpAccessibility.maxTextChars` körül vannak vágva (alapértelmezett `50000`). Egy blokk `full` lekérésének felső határa 256 KiB —** nincs korlátlan teljes visszakeresés** . Ha egy blokk `chars=N` nagy, lapozd át ahelyett, hogy az egészet kihúznád:

- Ökölszabály:**`chars > 40000` → használj `mode`** , soha egy csupasz tele.
- `mode:"grep"` — regex `pattern` soronként egyeztetve, legfeljebb 1000 egyező sor (`unique: true` drops ismétlődik), a legolcsóbb a "találja meg azt a sort, amelyre szükségem van".
- `mode:"lines"` — egy 1 indexű vonaltartomány; `start` és `end` is kell.
- `mode:"head"` / `mode:"tail"` — first/last `n` sorok.
- `mode:"stats"` — sorok, karakterek és bájtok a törzs nélkül számítanak.

Használja `mode:"lines"` `start`/`end` -vel, hogy hosszú blokkot haladjon végig az oldalakon, ahelyett, hogy egyszerre kérné le az egészet.

### Eszköz elnevezés

A visszakereső eszköz neve jelenleg `omniroute_ccr_retrieve` (a `omniroute_` előtag a kiszolgálók közötti névütközések dátumozott megoldása). Egy tisztább korlátos utótagú eszköznév és egy javítás MCP JSON eredmények csonkolt középső karakterláncához a rendszer felfelé irányuló követésként követi nyomon; ez az oldal csak az aktuális, szállított viselkedést dokumentálja.

### A munkamenet életciklusa

A streamelhető HTTP-munkamenetek tétlenül működnek, és a szerver lekéri őket; az üresjárati ablak a `MCP_SESSION_IDLE_MS` konstans (névvel hivatkozva, nem kódolt értékkel, így ez az oldal nem sodródik, ha változik). A tétlenül learatott munkamenet tünete egy HTTP 404 `Unknown Mcp-Session-Id` — -vel, a megoldás a munkamenet újracsatlakozása vagy újraindítása,** nem** kulcs forgatásához, hatókör módosításához vagy eszköz átnevezéséhez.

## API felület

| Útvonal                                | Cél                                                                             |
| -------------------------------------- | ------------------------------------------------------------------------------- |
| `/api/settings/compression`            | Globális tömörítési beállítások (beleértve `mcpAccessibility` konfigurációt is) |
| `/api/compression/preview`             | Tekintse meg a tömörítési módokat                                               |
| `/api/compression/language-packs`      | Sorolja fel az elérhető Caveman nyelvi csomagokat                               |
| `/api/context/caveman/config`          | Caveman beállítások álnév                                                       |
| `/api/context/rtk/config`              | RTK alapértékei és beállításai                                                  |
| `/api/context/rtk/filters`             | RTK szűrőkatalógus                                                              |
| `/api/context/rtk/test`                | RTK preview/test végpont                                                        |
| `/api/context/rtk/raw-output/[id]`     | Hitelesített, szerkesztett nyers kimenet helyreállítása                         |
| `/api/context/combos`                  | Kompressziós kombó CRUD                                                         |
| `/api/context/combos/[id]/assignments` | Útválasztás-kombó hozzárendelés CRUD                                            |
| `/api/context/analytics`               | Tömörítési elemzési álnév                                                       |

A felügyeleti útvonalak kezelési hitelesítést vagy API-kulcs házirend-ellenőrzéseket igényelnek.

## MCP Tools

A tömörítés öt MCP eszközt tesz elérhetővé:

| Eszköz                              | Hatály              | Cél                                              |
| ----------------------------------- | ------------------- | ------------------------------------------------ |
| `omniroute_compression_status`      | `read:compression`  | Beállítások, elemzések, gyorsítótár statisztikák |
| `omniroute_compression_configure`   | `write:compression` | Frissítse a globális beállításokat               |
| `omniroute_set_compression_engine`  | `write:compression` | Állítsa be a módot és az opcionális csővezetéket |
| `omniroute_list_compression_combos` | `read:compression`  | Tömörítési kombinációk listázása                 |
| `omniroute_compression_combo_stats` | `read:compression`  | Olvassa el combo/engine analytics-t              |

## Hatály és kizárások

**A beágyazások soha nem tömöríthetők.** `open-sse/handlers/embeddings.ts` soha nem nevez semmilyen kompressziós motort — a request/response testek érintetlenül jutnak át közvetlenül a végrehajtóhoz. Ez ma strukturális (a beágyazások és a chat-befejezések diszjunkt kezelők), nem futásidejű ellenőrzés, de azt jelenti, hogy a #8034 vektortorzítási aggálya nem rendelkezik expozíciós felülettel a beágyazási útvonalon.

**Per-model/endpoint kizáró szűrő (#8034).** A csevegés befejezéséhez az operátor megnevezheti a modellazonosítókat / `provider/model` célokat, amelyeket soha nem szabad tömöríteni, — egy védőkorlát, amely akkor hasznos, ha a tömörítést később a beágyazásokkal szomszédos útvonalhoz kötik közelebb, és általában hasznos minden olyan modellnél, amelynek pontos bájtról bájtra promptja számít (determinisztikus kiértékelések, gyorsítótár-érzékeny előtagok stb.).

- Beállítások mező: `exclusions?: string[]` a globális tömörítési konfiguráción (`GET`/`PUT /api/settings/compression`), megmaradt a meglévő `key_value` tömörítési névtéren (`src/lib/db/compression.ts`) — nincs új tábla.
- Irányítópult lap:** Irányítópult → Tömörítés → Kizárások** (`/dashboard/compression/exclusions`).
- Minta szintaxis: `*` az egyetlen helyettesítő karakter. A mintában minden más reguláris kifejezés metakarakterét a rendszer kihagyja az egyeztetés előtt, így `gpt-5.6` csak a literális karakterláncra egyezik, `gpt-5x6` soha (ReDoS-biztos, korlátos, nincsenek beágyazott kvantorok). A minták kis- és nagybetűktől eltérően illeszkednek mind a csupasz modellazonosítóhoz, mind a `provider/model` összetett — `gpt-5-6`, `openai/gpt-5-6` és `openai/*` függvényhez, és `*` önmagában kizár minden modellt.
- Illesztés: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` közvetlenül a tömörítési beállítások feloldása után ellenőrzi a kizárt célt,** mielőtt bármelyik motor beindulna** , és az egyezést pontosan úgy kezeli, mint a tömörítést, ha globálisan le van tiltva, — a kérés törzse bizonyíthatóan bájt-azonos. A kihagyást `writeCompressionSkip(..., "excluded")` keresztül rögzíti az analitikai láthatóság érdekében.
- Alapértelmezett (empty/absent lista): megegyezik a #8034 előtti viselkedéssel — sincs kizárva.

## Ismert korlátozások

- **LLMLingua-2 (SLM) megköveteli a közös helyen található opcionális dep-eket.** A dolgozó csak akkor fut termelési buildben, ha `@atjsh/llmlingua-2` + társak `dist/node_modules` -ben találhatók (lásd `scripts/build/colocateOptionals.mjs`, #4286). Ezek nélkül a motor hibamegnyílik (visszaadja az eredeti szöveget). A dolgozók felbontása már nem függ `import.meta.url` tól (az önálló kötegben meghal) — a futásidejű cwd / `argv[1]` hoz rögzíti.
- **`de` / `fr` / `ja` Caveman nyelvi csomagok részlegesek.** Szállítanak `context` + `filler` + `structural` szabályokat, de nem `dedup` / `ultra` csomagokat, így `ultra` intenzitása nem erősebb, mint `full` ezeknél a nyelveknél (csak a saját szabályaikat használják —, nincs csendes visszaesés az angol `dedup`/`ultra` idegen szöveghez). `en` / `es` / `id` / `pt-BR` kész. Várjuk `dedup.json` + `ultra.json` hozzájárulását a részcsomagokhoz.
- **A halmozott telemetria csak a tömörített motorokat jeleníti meg.** Egy halmozott csővezeték-lépés, amelynek motorja járt, de 0 %-os megtakarítást produkált, `stats:null` ad vissza, és így nem jelenik meg `engineBreakdown` — ben, megkülönböztethetetlenül egy kihagyott lépéstől. A „futott, 0 %” és a „kihagyott” megkülönböztetése a bontási modell megváltoztatását igényelné, és elhalasztható.

## Érvényesítés

Ennek a területnek a fókuszált kapui a következők:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
