# Compression Engines (Suomi)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute kompressio rakentuu moottorisopimusten ympärille. Tila voi käyttää yhtä moottoria suoraan (`caveman` tai `rtk`) tai determinististä pinottua liukuhihnaa, joka suorittaa useita moottoreita järjestyksessä.

## Tilat

| tila         | Moottorin polku                                                                             | Tarkoitettu syöttö                                       |
| ------------ | ------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| `off`        | ei yhtään                                                                                   | Tarkka nopea säilytys                                    |
| `lite`       | Caveman lite -apulaiset                                                                     | Pieniriskinen aina päällä oleva siivous                  |
| `standard`   | Luolaihminen                                                                                | Luonnonkielinen nopea kondensaatio                       |
| `aggressive` | Caveman + history/tool yhteenvedot                                                          | Pitkät chat-istunnot                                     |
| `ultra`      | Caveman + -leikkausapulaiset                                                                | Kontekstirajoituksen palautus                            |
| `rtk`        | RTK                                                                                         | Pääte, shell, build, testata ja git-tulostus             |
| `omniglyph`  | OmniGlyph                                                                                   | Konteksti kuvana alkuperäisen palveluntarjoajan johdolla |
| `stacked`    | Putkilinja. Pyynnön oletusarvo on `session-dedup -> lite`. `rtk -> caveman` on valinnainen. | Sekalaisia työkalulokeja ja proosaa, maksimi säästö      |

### OmniGlyph puristusprofiilit

`omniglyph` -moottori (paketti `omniglyph`, 1.4.0 +) hyväksyy nimetyn semanttisen profiilin, joka on asetettu globaalisti pakkausasetuksissa `omniglyph.profile` kautta tai vaiheittain pinotun liukuhihnan vaihekonfiguraatiossa:

| Profiili      | Raja                                                                                                                    |
| ------------- | ----------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Oletus. Politiikassa julkaistut kuitit mittasivat — -kuvajärjestelmää, työkaludokumentteja ja tiheää historiaa          |
| `balanced`    | Pitää live-tilan natiivina, suojaa viimeiset 8 kierrosta, romuttaa vanhemman suljetun historian                         |
| `coding-safe` | Säilyttää auktoriteetin, työkalukaaviot ja reaaliaikaisen työkalutulosteen alkuperäisinä, suojaa viimeiset 12 kierrosta |
| `passthrough` | Reitit ilman muuntamista; moottori jää väliin                                                                           |

Profiili on a** katto, ei lattia** : pakkauksessa oleva `mergeCompressionProfileOptions` kieltäytyy sallimasta soittajan ohitusta avata uudelleen häviöllisen kaistan profiili suljettu, joten vaihekohtainen `preserveSystemPrompt: false` ei voi ottaa järjestelmän pakkausta uudelleen käyttöön `coding-safe` ssä.

Tällä koodikannassa mitattuna: `coding-safe` ja `balanced` nostavat `minCompressChars` maksimissaan ja pitävät järjestelmän, työkalukaaviot ja työkalutulokset alkuperäisinä, joten istunto, jolle ei ole vielä kertynyt historiaa, pysähtyy `below_min_chars` hen eikä moottori muuta mitään. Tästä syystä oletus on `aggressive` turvallisimman profiilin sijaan.

Paketti ratkaisee oman mallialueensa ja profiilinsa ympäristökokoonpanostaan. OmniRoute ei koskaan delegoi päätöstä: sovitin kiinnittää malliportin paketin kaikkein rajoittavimpaan alueeseen, joten isäntäympäristön asetukset voivat vain kaventaa sallittujen luetteloa, eivätkä koskaan laajentaa sitä OmniRoute:n mitattujen kuittien ohi.

## Moottorin rekisteri

Rekisteri sijaitsee `open-sse/services/compression/engines/registry.ts`. Moottorit paljastavat yhteisen sopimuksen:

- `id`: vakaa moottorin tunnus, kuten `caveman` tai `rtk`
- `apply(text, config)`: pinottujen putkien käyttämä vanha suorituspolku
- `compress(input, config)`: ensisijainen suorituspolku, joka palauttaa tekstin + -tilastot
- `getConfigSchema()`: palauttaa kelvollisen konfiguraation JSON-skeeman kaltaisen muodon
- `validateConfig(config)`: palauttaa `{ valid, errors[] }`

Rekisteröinnissa käytetään `registerCompressionEngine(engine)` (tai `registerEngine` edistyneissä tapauksissa), joka kutsuu `assertValidEngine()` ja `validateConfig(defaultConfig)` ennen hyväksymistä. Käytä `unregisterCompressionEngine(id)` moottorin poistamiseen käytön aikana.

`strategySelector.ts` rekisteröi sisäänrakennetut moottorit ennen puristusajoa. Näin esikatselu, ajonaikainen pakkaus, pinottu tila, testit ja tulevat moottorit voivat käyttää samaa suorituspolkua.

### MCP -kuvauksen pakkaus (liittyy)

Erillinen rekisteri pakkaa MCP -työkalun kuvausmetatiedot rekisteritasolla — katso `open-sse/mcp-server/descriptionCompressor.ts` ja [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Se käyttää uudelleen Caveman-sääntöjä, mutta toimii työkalun metatiedoilla, ei pyydä hyötykuormia.

### Sisäänrakennetut lisämoottorit

Cavemanin, RTK ja LLMLingua-2:n lisäksi rekisteri toimittaa useita erikoistuneita häviöttömiä / rakenteellisia moottoreita (käytetään pinottuissa putkissa, leikkikentällä ja testeissä):

| Moottori      | Id              | Mitä se tekee                                                                                                                                                                           |
| ------------- | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): korvaa suuret vierekkäiset tekstilohkot sisältöosoitteellisilla viittauksilla, joten repeated/large -lohkot lähetetään kerran ja viitataan sen jälkeen. |
| päätilaa      | `headroom`      | SmartCrusher (H3 + N5): homogeenisten JSON-matriisin hyötykuormien häviötön taulukkopakkaus pylväsmäiseen `[N rows]` muotoon.                                                           |
| ionisaattori  | `ionizer`       | Head/middle/tail -rivien näytteenotto erittäin suurille homogeenisille lohkoille, tallentamalla elided keskikohdan CCR -sisältökohdistukseksi.                                          |
| session-dedup | `session-dedup` | Sisältökohtainen käännösten päällekkäisyyden poistaminen (TokenMizer-vaikutteinen): eliminoi tekstin, joka on jo nähty saman istunnon aikaisemmissa käännöksissä.                       |

**CCR retrieve-protocol -ohje (#8033):** Ensimmäistä kertaa CCR korvaa pyynnön ≥ 1 -lohkon, moottori lisää yhden idempotentin `system` -sanoman (jossa on `[CCR protocol]` sentinel), joka opettaa soittajalle merkin → työkalun sopimus: mitä `[CCR retrieve hash=<24hex> chars=N]` -merkki tarkoittaa, että hash on kopioitava sanatarkasti (kaikki 24 hex-merkkiä ovat todennäköisiä — -merkkiä) ei löydy" puuttuu), ja että `[dedup:ref sha=...]` -merkki tarkoittaa "katsoa taaksepäin historiassa", ei "soita työkalulle". Setti ruiskutetaan** vain kun soittajan mainostama `tools[]` osoittaa, että se voi todella saavuttaa `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — tavallinen OpenAI-yhteensopiva soittaja ilman tätä työkalua ei saa koskaan käskyä soittaa johonkin, jota se ei voi tavoittaa. Idempotenssi vahvistetaan skannaamalla vartijan viestihistoria ennen pistämistä, joten usean kierroksen pyynnöt (jotka toistavat aiempia viestejä) eivät pinoa nuottia kerran vuorossa.

## Luolaihminen

Caveman-tila keskittyy normaalin proosan semanttiseen tiivistymiseen:

- säilyttää koodilohkot, URLs, JSON, polut ja strukturoidut tiedot
- poistaa täyteaineen, suojauksen, toistuvan kontekstin ja monisanaisen yhdistävän ilmaisun
- tukee kielitietoisia tiedostosääntöpaketteja `open-sse/services/compression/rules/`:ssa
- on edelleen käytettävissä vanhojen `standard`, `aggressive` ja `ultra` -tilojen kautta

Kojelaudan pinta on `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream raportoi `~75%` vähemmän lähtötunnisteita, `65%` keskimääräisiä tuotossäästöjä `22-87%` -alueen vertailuarvoissa ja `~46%` -syötteen pakkaustyökalun. OmniRoute käyttää Caveman-syötepuolen numeroa dokumentoidessaan pinottuja prompt/context säästöjä; Luolamiesten ulostulotila on edelleen erillinen vaste-käyttäytymisominaisuus.

## RTK

RTK -tila keskittyy komentojen ja työkalujen ulostuloon:

- havaitsee tulosluokat, kuten `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go -testit, TypeScript/Vite/Webpack koontiversiot, ESLint, npm audit/installs, Docker -lokit, komentotulkki `find`/`grep`, pinojäljet ja yleiset lokit
- käyttää 49 JSON -suodatinta `open-sse/services/compression/engines/rtk/filters/`:ltä
- tukee RTK-tyylistä deklaratiivista liukuhihnaa: ANSI kuoppaus, korvaaminen, sovitusulostulon oikosulku, strip/keep rivit, rivikohtainen katkaisu, head/tail/max-line lyhennys ja tyhjennyksen palautus.
- tukee `.rtk/filters.json` ssa luotettavia projektisuodattimia ja `DATA_DIR/rtk/filters.json`:n globaaleja suodattimia
- poistaa ANSI sekvenssejä, edistymiskohinaa, toistuvia rivejä ja hyödytöntä kattilalevyä
- säilyttää toimintakelpoiset viat, varoitukset, yhteenvedot, muuttuneet tiedostot ja loppukontekstit
- voi valinnaisesti säilyttää redigoidun raakatulosteen recovery/debugging todennettujen hallintareittien kautta

Kojelaudan pinta on `Dashboard -> Context & Cache -> RTK`.

Mukautettujen suodattimien, luottamuksen, varmistuksen ja raakatulosteen palautuksen toiminnalliset tiedot näkyvät [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream raportoi `60-90%` säästöjä komento-lähtöpakkauksessa. Sen README esimerkki näyttää 30 minuutin Claude -koodiistunnon, joka siirtyy `~118,000` tunnisteista `~23,900` tai `79.7%` tallennettuun tilaan.

## LLMLingua-2 (semanttinen karsiminen)

LLMLingua-2 -tila toimii** semanttinen merkkien karsiminen** proosaa käyttäen pientä ONNX -merkkiluokittajaa, joka täydentää sääntöpohjaisia Caveman- ja RTK -moottoreita:

- pakkaa proosaa vain ei-järjestelmäviesteissä; aidattuja koodilohkoja ja muita säilytettyjä rakenteita ei koskaan muuteta
- suorittaa `@atjsh/llmlingua-2` taustaohjelman (ONNX kautta `@huggingface/transformers`) työsäikeessä, joten mallin päättely ei koskaan estä pyyntötapahtumasilmukkaa
- on** pinottava** (`stackPriority` 35): pinotussa liukuhihnassa se kulkee rakennemoottoreiden (CCR, session-dedup, headroom, Caveman) jälkeen, mutta ennen `ultra`, koska semanttinen karsiminen on tehokkainta jo rakenteellisesti pakatuissa tekstissä — esim. `rtk -> caveman -> llmlingua`
- **vika-avautuu mistä tahansa virheestä** (puuttuu valinnainen deps, worker spawn, mallin lataus, päättely tai aikakatkaisu) → alkuperäinen teksti palautetaan muuttumattomana, ei koskaan virhettä

Moottorin sijainti: `open-sse/services/compression/engines/llmlingua/`. Kojelaudan pinta on `Dashboard -> Context & Cache -> LLMLingua`.

### Mallit

Oletusmalli on**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, nopea). Korkeampi tarkkuus** BERT-tukikohta** malli (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) on saatavilla moottorin konfigurointi `model` -kentän kautta. `@huggingface/transformers` lataa valitun mallin laiskasti HuggingFace Hubista `${DATA_DIR}/models/llmlingua` :hen ensimmäisessä kutsussa (`modelStore.ts`); `modelPath` -asetusten ohitus osoittaa sen sijaan paikalliseen kopioon (offline-asennukset / ilmaväliset asennukset).

### Valinnaiset riippuvuudet ja tilausasennukset

Karsittava LLMLingua runtime peer-pino on** valinnainen** . Kaksi pakkausta ilmoitetaan `optionalDependencies` nä `package.json` ssä ja säilytetään** ulkoinen** tuotantokoon mukaan (`scripts/build/prepublish.ts` ei niputa niitä):

| Paketti              | Versio (pin) | Huomautuksia                                   |
| -------------------- | ------------ | ---------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`      | Sisäänpääsy paketti; julistaa muut vertaisiksi |
| `js-tiktoken`        | `^1.0.20`    | Tokenizer                                      |

`@huggingface/transformers` on kiinnitetty `^4.2.0` hen (jaettu paikallisen upotuspolun kanssa ja jäljitetty myös itsenäiseen nippuun); `@atjsh/llmlingua-2@2.0.5` vertailee sitä `"^3.5.2 || ^4.0.0"` kanssa, joten sekä Transformers.js v3 että v4 ovat tuettuja. Vuodesta 2.0.4 lähtien `@atjsh/llmlingua-2` ei enää vaadi `@tensorflow/tfjs`, mikä poisti suurimman yksittäisen tekijän (TensorFlow.js) SLM pinosta. Vain kaksi yllä olevaa pakettia ovat karsittavia SLM vertaisia. Tavallinen `npm install` (dev) asentaa valinnaisen pinon automaattisesti, ellei valinnaisia riippuvuuksia jätetä pois.

**Miksi on-demand:** npm:n julkaisema paketti, erillinen paketti ja Docker kuvatoimitus** ilman** nämä deps pysyä hoikkana. Kun he ovat poissa, työntekijän riippuvuusportti ( `@atjsh/llmlingua-2` -selvitysanturi `worker.ts`:ssä) epäonnistuu ja moottori** epäonnistuu-avautuu hiljaa** — LLMLingua valinnasta tulee no-op (teksti palautetaan muuttumattomana, virhettä ei kirjata). Aktivoidaksesi sen karsitussa ympäristössä, asenna valinnainen pino:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` poisto (2.0.4 +) eliminoi aiemmin hallitsevan ~ 800 MB -avustajan — jäljellä oleva jalanjälki on transformers.js + onnxruntime-node runtimes sekä TinyBERT malli (~ 57 MB), joka on ladattu ensimmäisellä käyttökerralla (ei np:n kautta).

Ympäristöä kohden:

- **Kehittäjä / `npm install`** — asennetaan automaattisesti, ellet läpäissyt `--omit=optional` (tai `--no-optional`). Toimia ei tarvita.
- **Globaali npm (`npm i -g omniroute`) / erillinen** — suorita yllä oleva asennuskomento asennetun paketin hakemistossa tai asenna uudelleen jättämättä pois valinnaisia depsiä.
- **Docker** — lisää asennuskomento johdettuun kuvakerrokseen; julkaistu kuva on suunnittelultaan ohut.
- **VPS (PM2)** — asentaa sovelluksen `node_modules` hen ja käynnistä sitten prosessi uudelleen, jotta työntekijä tutkii portin uudelleen.
- **Raw Next erillinen (`npm run build` → `.build/next/standalone/server.js`)** — erilliset jäljitysalukset NEITHER työntekijää tai valinnaisia depsiä, joten moottori avautuu hiljaa. `scripts/build/colocate-standalone.mjs` ottaa molemmat uudelleen käyttöön (työntekijä rakentaa + valinnaisen dep-sulkemisen itsenäiseen puuhun); se toimii automaattisesti `postbuild` npm -koukun kautta jokaisen rakentamisen jälkeen. Idempotentti, vikasietoinen, kun depsit puuttuvat.

**Varmista, että se on aktiivinen:** kun LLMLingua on valittuna, todellinen proosa itse asiassa kutistuu (moottori lakkaa avautumasta), ja ensimmäinen pyyntö käynnistää mallin latauksen `${DATA_DIR}/models/llmlingua` hen. Portti tutkii tarkoituksella vain `@atjsh/llmlingua-2` — muut vertaiset ovat vain ESM:iä ja `require.resolve` heittää niitä jopa silloin, kun — on läsnä, joten työntekijä silti avautuu, jos joku vertaishenkilö todella puuttuu `import()` ajalla.

## Pinotut putkistot

Pinottu tila suorittaa liukuhihnavaiheet järjestyksessä. Oletus on:

```txt
rtk -> caveman
```

Käytä tätä koodausagenttiistunnoissa, joissa kehote yhdistää komentotulosteen ihmisen tai avustajan prosen kanssa. RTK vähentää ensin meluisia työkalulokeja, sitten Caveman pakkaa jäljellä olevan luonnollisen kielen.

Putkilinjan vaiheet määritetään `stackedPipeline` pakkausasetuksissa tai pakkauskombojen avulla.

Kun molemmat moottorit vähentävät samaa hyväksyttävää hyötykuormaa, säästöyhdiste:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP esteettömyyspuusuodatin

Älykäs MCP Accessibility-tree -suodatin on suorituksen jälkeinen pakkaustaso, joka toimii MCP ssä** työkalun tulokset** , ei kehotteiden tai kontekstin perusteella. Se kohdistaa monisanaisiin saavutettavuuspuun ja selaimen tilannevedoshyötykuormiin, jotka palauttavat työkalut, kuten Playwright, tietokoneen käyttö ja selainautomaatio MCP palvelimet.

### Mitä se tekee

1. **Melunpoisto** — poistaa tyhjät generic/text merkinnät (`- generic:`, `- text: ""`)
2. **Sisarusten romahtaminen** — kun ≥ `collapseThreshold` (oletus 30) peräkkäiset rivit ovat rakenteellisia toistoja, tiivistää ne ensimmäisiksi `collapseKeepHead` (oletus 10) riveiksi + laskennan yhteenveto + viimeiset `collapseKeepTail` (oletus 5) rivit
3. **Viitteen säilyttäminen** — `[ref=eXX]` Playwright/computer-use vaatimiin ankkureihin ei koskaan kosketa
4. **Kova katkaisu** — jos teksti tiivistyksen jälkeen ylittää edelleen `maxTextChars` (oletusarvo 50 000), katkaistaan navigointivihjeellä, jotta agentti voi jatkaa työskentelyä

### Moottorin sijainti

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Kokoonpano

`compression.mcpAccessibility` hallitsee globaaleissa asetuksissa (migration 056). Oletusasetus:

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

Suodatinta käytetään vain työkalun tuloksena oleviin hyötykuormiin, joiden `type` on `"text"` ja joiden pituus on suurempi kuin `minLengthToProcess`. Se ei vaikuta nopeaan pakkaukseen tai pyyntöhyötykuormiin.

### Odotetut säästöt

60–80 % selaimen tilannekuvatyökalun tuloksista sivun monimutkaisuudesta riippuen. Tiivistysalgoritmi on O(n) rivimäärässä ja lisää merkityksetöntä latenssia.

### Tämä suodatin vs. yllä olevat kompressiomoottorit

| Aspekti        | Luolamies / RTK / Pinottu   | MCP esteettömyyssuodatin               |
| -------------- | --------------------------- | -------------------------------------- |
| Kohde          | Pyyntökehotteet / konteksti | MCP työkalun tulokset                  |
| Laukaista      | Pakkaustilan asetus         | `compression.mcpAccessibility.enabled` |
| Laajuus        | Kaikki SSE viestit          | Vain työkalutulokset                   |
| Viite ankkurit | N/A                         | Säilytetty ehdoitta                    |

---

## Kompressioyhdistelmät

Pakkausyhdistelmät ovat nimettyjä pakkausprofiileja, jotka voidaan määrittää reitityskomboihin:

- `compression_combos`: tallentaa tila, liukuhihna, RTK konfiguraatio, kieliasetus ja oletusmerkki
- `compression_combo_assignments`: kartoittaa pakkausyhdistelmän reititysyhdistelmäksi
- ajonaikainen integraatio ratkaisee määritetyn pakkausyhdistelmän ennen yleisen yhdistelmän ohituksia
- analytiikkaan kuuluvat `compression_combo_id` ja `engine`

Kojelaudan pinta: `Dashboard -> Context & Cache -> Compression Combos`.

## Edellytykset / käyttäjäopas (CCR & session-dedup)

CCR (`ccr`) ja `session-dedup` korvaavat tai poistavat tekstin ja jättävät a** merkki** takana. Tämä osio on käyttäjille tarkoitettu ohje asiakkaan kytkemiseen, kahden merkin lukemiseen ja poistetun sisällön hakemiseen tai diagnosointiin. Jokaisen moottorin mekaniikka on käsitelty edellä; tämä on "miten annan sen" -taso.

### Kuljetukset ja päätepisteet

MCP palvelimeen, joka paljastaa CCR työkalut, pääsee kolmella tavalla. Oletusperusarvo URL on `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Kuljetus                                  | URL / komento                           | Huomautuksia                                                                                                                                      |
| ----------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Striimattava HTTP (asiakas, suositeltava) | `http://localhost:20128/api/mcp/stream` | Päätepiste, jonka kanssa nykyiset MCP asiakkaat puhuvat.                                                                                          |
| Vanha SSE singleton                       | `http://localhost:20128/api/mcp/sse`    | Vanhempi singleton kuljetus. Se** sulkeutuu** suoratoistettavat istunnot; käytä `streamable-http` asiakkaita `/api/mcp/stream` vastaan, älä tätä. |
| stdio                                     | `omniroute --mcp`                       | IDE MCP -konfiguraatiolle, joka synnyttää prosessin. `--dev` lippua ei ole; `omniroute --mcp` on stdio-sisääntulopiste.                           |

### Tallennustasot (mikä kestää uudelleenkäynnistyksen)

CCR on a** kaksitasoinen** myymälä, ei vain muistissa:

- **Kuuma muistitaso** — lohkokohtainen korkki 2 MiB, pääasiallinen 16 MiB, globaali 64 MiB. Merkintöjen oletusarvo on 24 h TTL (enintään 7 päivää). Täydellinen MCP haku muistista on rajoitettu arvoon 256 KiB; kaikki suurempi on edelleen tavoitettavissa ranged / grep -tilojen kautta.
- **Kestävä SQLite -taso** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, oletuksena päällä) — tukee muistitasoa, jotta lohko selviytyy LRU -häätöstä, uudelleenkäynnistyksestä tai palautuksesta toiseen ilmentymään. Rivi säilyttää lohkon TTL, joten sen TTL ohi oleva lohko on poissa molemmista tasoista.

Kolme suojusta pitävät kestävän tason rajallisena — a lohko pysyy vain muistissa, kun:

1. lohko on ohi** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. suoritusaika on pilvikäyttöaika (ei paikallista levyä);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Joten "lohko katosi" ei ole pelkkä uudelleenkäynnistystarina: sub-512 KB -lohko paikallisessa, ei-pilvikäyttöympäristössä selviää uudelleenkäynnistyksestä kestävän tason kautta, kunnes sen TTL loppuu. Katso muuttujan [ympäristöviite](../reference/ENVIRONMENT.md).

### Kaksi merkkiä

| Merkki                                | Merkitys                                                                                                                                                           | Mitä mallin pitäisi tehdä                                                                                                                                                                                                    |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Suuri lohko tallennettiin sisältöosoitteeseen.                                                                                                                     | Soita `omniroute_ccr_retrieve`** 24 hex hash kopioitu sanatarkasti** saadaksesi alkuperäisen tekstin takaisin.                                                                                                               |
| `[dedup:ref sha=…]`                   | `session-dedup` elided teksti, joka on jo lähetetty saman istunnon aikaisemmassa vuorossa. Tämä on an** tahallinen katsominen taaksepäin** , ei menetys tai virhe. | Tehdä** ei** soita mihin tahansa työkaluun ja tee** ei** yritä "rekonstruoida" se. Tekstin ensimmäinen esiintyminen on kanoninen kopio; nykyistä vuoroa ei koskaan kirjoiteta uudelleen, se poistetaan myöhemmässä vuorossa. |

`[dedup:ref]` -katselu on tahallinen protokollapäätös. — ei ole olemassa lähetystä edeltävää rekonstruktiota. Käsittele sitä niin, että "tämä teksti oli jo aiemmin tässä istunnossa".

### Asiakkaan edellytykset

- **Avain (stdio):** stdio-soittajalla ei ole pyyntökohtaista identiteettiä, joten se todennetaan `OMNIROUTE_API_KEY` (asetettu MCP -palvelimen `env` ssä). Ilman sitä soittaja on anonyymi ja työkalut, jotka vaativat päämiehen, voivat heiketä.
- **`tools[]` on ruiskutuksen ennakkoehto.** CCR retrieve-protocol -käsky (#8033) injektoidaan** vain** kun pyynnön mainostettu `tools[]` osoittaa, että asiakas voi todella saavuttaa `omniroute_ccr_retrieve`. Osuma on erottimella (`__`, `.`, `/`, `:`) rajattu loppuosuus, — ei koskaan paljaalla osamerkkijonolla — joten nimiavaroitu nimi, kuten `mcp__gateway__omniroute_ccr_retrieve` lasketaan silti. Puuttuva tai ei-vastaava `tools[]` tarkoittaa, että käskyä _ei_ syötetä suunnittelun mukaan.
- **`codemode:false` (OpenCode asiakkaat).** OpenCode on oletuksena Code Mode, joka mainostaa vain alkuperäisiä työkalujaan mallille ja** ei** laita MCP työkalut alkuperäiseen `tools[]` luetteloon. Aseta `codemode: false` MCP -palvelinmerkintään, jotta `omniroute_ccr_*` työkaluja mainostetaan. Tämä on a** asiakas** asetus, ei OmniRoute. Se ei saa vielä CCR -käskyä: OpenCode nimeää työkalun `<server>_<tool>`, joten palvelin nimeltä `omniroute` paljastaa `omniroute_omniroute_ccr_retrieve`, eikä `_` ole yksi sovitetuista erottimista.
- **Rehtorit.** Tallennus ja haku eristetään todennettua pääkäyttäjää kohti (per API -avainta). Avain näkee vain omat lohkonsa.

### Laajuudet työkalua kohden

Soveltamisalan valvonta on aina käytössä kapea-alaisille HTTP/SSE soittajille. `omniroute_` CCR -työkalut vaativat:

| Työkalu                  | Laajuus             |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Puuttuva laajuus palauttaa an**MCP työkaluvirheen tulos** (`isError: true`, ei HTTP 403 — `403 LOCAL_ONLY` on erillinen loopback-reitinvartijan todennus): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Pienin kaukosäätimen avaimessa voi olla `mcp:connect` (valtuuttaa `/api/mcp/` paikallisen carve-out-toiminnon) sekä sen tarvitseman erityisen read/write alueen.

### Asiakasmatriisi

| Asiakas             | Kuljetus                                       | Konfigurointi käytettäväksi                                                                                                                                                                                                               | `tools[]` mainostettu? (→ CCR -ohje syötetty)                                                                                                                                              |
| ------------------- | ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Claude koodi        | suoratoisto-http                               | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                         | Kyllä — MCP-yhteensopiva; pistetään.                                                                                                                                                       |
| Cursor / Cline      | `stdio`** tai** `streamable-http`              | stdio: `omniroute --mcp` ja `OMNIROUTE_API_KEY` `env`:ssä; tai MCP -etäsyöttö, joka osoittaa `http://localhost:20128/api/mcp/stream` (katso [asennusopas → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Kyllä, — mainostaa `omniroute_ccr_*` -työkaluja.                                                                                                                                           |
| OpenCode            | suoratoisto-http                               | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` plus `codemode: false`                                                                                                                                           | Vain `codemode: false` mainostetut työkalut; ohjetta ei edelleenkään syötetä, koska `omniroute_omniroute_ccr_retrieve` ei täsmää (katso [Asiakkaan edellytykset](#client-prerequisites) ). |
| OpenAI-yhteensopiva | OpenAI-yhteensopiva HTTP (chatin täydennykset) | tavallinen keskustelun täydennysasiakas OpenAI-yhteensopivaa päätepistettä vastaan                                                                                                                                                        | **Ei koskaan** — tavallista OpenAI-yhteensopivaa soittajaa ei koskaan käsketty soittamaan työkaluun, eikä ohjetta anneta.                                                                  |

### Hakurajoitukset ja sivutus

MCP -työkalun tekstitulokset leikataan `mcpAccessibility.maxTextChars` ympärille (oletus `50000`). Lohkon `full` -palautuksen yläraja on 256 KiB —** ei ole rajatonta täyttä hakua** . Kun lohkon `chars=N` on suuri, sivua se sen sijaan, että vedät koko jutun:

- Nyrkkisääntö:**`chars > 40000` → käytä `mode`** , ei koskaan paljain täynnä.
- `mode:"grep"` — regex `pattern` sovitettu rivi riviltä, jopa 1 000 vastaavaa riviä (`unique: true` drops toistaa), edullisin "etsi yksi tarvitsemani rivi".
- `mode:"lines"` — 1-indeksoitu rivialue; tarvitsee sekä `start` että `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` rivit.
- `mode:"stats"` — rivit, merkit ja tavut laskevat ilman runkoa.

Käytä `mode:"lines"` komentoa `start`/`end` kävelläksesi pitkän lohkon sivuilla sen sijaan, että pyytäisit koko asiaa kerralla.

### Työkalun nimeäminen

Hakutyökalun nimi on tällä hetkellä `omniroute_ccr_retrieve` ( `omniroute_` -etuliite on päivätty palvelinten välisten nimien törmäysten kiertotapa). Selvempi rajoitetun päätetyökalun nimi ja korjaus MCP JSON -tuloksille katkaistu merkkijono puolivälissä seurataan alkupään seurantatoimia; tämä sivu dokumentoi vain nykyisen toimituksen.

### Istunnon elinkaari

Streamable-HTTP-istunnot ovat tyhjäkäynnillä ja palvelin kerää ne; tyhjäkäynti-ikkuna on `MCP_SESSION_IDLE_MS` vakio (viitataan nimellä, ei kovakoodattu arvo, joten tämä sivu ei ajaudu, kun se muuttuu). Käyttämättömän istunnon oire on HTTP 404 ja `Unknown Mcp-Session-Id` — Korjaustoimenpide on muodostaa yhteys uudelleen tai käynnistää istunto uudelleen,** ei** kiertää avainta, muuttaa laajuutta tai nimetä työkalu uudelleen.

## API pinta

| Reitti                                 | Tarkoitus                                                          |
| -------------------------------------- | ------------------------------------------------------------------ |
| `/api/settings/compression`            | Yleiset pakkausasetukset (mukaan lukien `mcpAccessibility` config) |
| `/api/compression/preview`             | Esikatsele mitä tahansa pakkaustilaa                               |
| `/api/compression/language-packs`      | Listaa saatavilla olevat Caveman-kielipaketit                      |
| `/api/context/caveman/config`          | Caveman-asetusten alias                                            |
| `/api/context/rtk/config`              | RTK oletukset ja asetukset                                         |
| `/api/context/rtk/filters`             | RTK suodatinluettelo                                               |
| `/api/context/rtk/test`                | RTK preview/test päätepiste                                        |
| `/api/context/rtk/raw-output/[id]`     | Todennettu redaktoitu raakatulosteen palautus                      |
| `/api/context/combos`                  | Kompressioyhdistelmä CRUD                                          |
| `/api/context/combos/[id]/assignments` | Reititys-yhdistelmätehtävä CRUD                                    |
| `/api/context/analytics`               | Pakkausanalytiikan alias                                           |

Hallintareitit edellyttävät hallinnan todennusta tai API-avaimen käytäntötarkistuksia.

## MCP työkalut

Pakkaus paljastaa viisi MCP työkalua:

| Työkalu                             | Laajuus             | Tarkoitus                                  |
| ----------------------------------- | ------------------- | ------------------------------------------ |
| `omniroute_compression_status`      | `read:compression`  | Asetukset, analytiikka, välimuistitilastot |
| `omniroute_compression_configure`   | `write:compression` | Päivitä yleiset asetukset                  |
| `omniroute_set_compression_engine`  | `write:compression` | Aseta tila ja valinnainen liukuhihna       |
| `omniroute_list_compression_combos` | `read:compression`  | Listaa pakkausyhdistelmät                  |
| `omniroute_compression_combo_stats` | `read:compression`  | Lue combo/engine analytics                 |

## Laajuus ja poissulkemiset

**Upotuksia ei koskaan pakata.** `open-sse/handlers/embeddings.ts` ei koskaan kutsu mitään kompressiomoottoria — request/response -kappaleet siirtyvät suoraan toimeenpanijalle koskemattomina. Tämä on nykyään rakenteellista (upotukset ja keskustelun loppuunsaattaminen ovat erillisiä käsittelijöitä), ei suorituksenaikainen tarkistus, mutta se tarkoittaa, että #8034 :n vektorivääristymäongelmalla ei ole näkyvyyttä upotuspolussa.

**Per-model/endpoint poissulkemissuodatin (#8034).** Keskustelun loppuun saattamista varten operaattori voi nimetä mallitunnukset / `provider/model` -kohteet, joita ei saa koskaan pakata — suojakaiteen, joka on hyödyllinen, jos pakkaus kytketään myöhemmin lähemmäksi upotusten viereistä polkua, ja yleensä hyödyllinen kaikissa malleissa, joiden täsmällisillä tavukohtaisilla kehotteilla on merkitystä (deterministiset evalit, välimuistille herkät etuliitteet jne.).

- Asetuskenttä: `exclusions?: string[]` yleisessä pakkauskokoonpanossa (`GET`/`PUT /api/settings/compression`), säilyi olemassa olevan `key_value` -pakkauksen nimiavaruuden kautta (`src/lib/db/compression.ts`) — ei uutta taulukkoa.
- Kojelauta-välilehti:** Dashboard → Compression → Poissulkemiset** (`/dashboard/compression/exclusions`).
- Kuvion syntaksi: `*` on ainoa jokerimerkki. Mallin jokainen toinen regex-metamerkki on pakotettu ennen täsmäämistä, joten `gpt-5.6` vastaa vain kirjaimellista merkkijonoa, ei koskaan `gpt-5x6` (ReDoS-turvallinen, rajoitettu, ei sisäkkäisiä kvantisoijia). Mallit täsmäävät kirjainkoolla epäherkästi sekä paljaan mallin id:n että `provider/model` -yhdistelmän — `gpt-5-6`, `openai/gpt-5-6` ja `openai/*` kanssa kaikki toimivat, ja `*` yksin sulkee pois kaikki mallit.
- Vastaavuus: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` tarkistaa poissuljetun kohteen heti pakkausasetusten ratkaisemisen jälkeen,** ennen kuin mikään moottori käy** , ja käsittelee osuman täsmälleen samalla tavalla kuin pakkaus on maailmanlaajuisesti pois käytöstä — pyynnön runko on todistettavasti tavuidenttinen. Ohitus tallennetaan `writeCompressionSkip(..., "excluded")` kautta analytiikan näkyvyyttä varten.
- Oletus (empty/absent lista): identtinen #8034 -käyttäytymisen kanssa. — mitään ei ole poissuljettu.

## Tunnetut rajoitukset

- **LLMLingua-2 (SLM) vaatii samassa paikassa sijaitsevia valinnaisia depsiä.** Työntekijä toimii tuotantoversiossa vain, kun `@atjsh/llmlingua-2` + -vertaiset ovat samassa paikassa `dist/node_modules` ssä (katso `scripts/build/colocateOptionals.mjs`, #4286). Ilman niitä moottorin vika-avautuu (palauttaa alkuperäisen tekstin). Työntekijän resoluutio ei enää riipu `import.meta.url` (se kuolee itsenäiseen nippuun) — se kiinnittyy ajonaikaiseen cwd / `argv[1]`.
- **Caveman-kielipaketit `de` / `fr` / `ja` ovat osittaisia.** He lähettävät `context` + `filler` + `structural` -säännöt, mutta ei `dedup` / `ultra` paketteja, joten `ultra` intensiteetti ei ole vahvempi kuin `full` näillä kielillä (he käyttävät vain omia sääntöjään — ei ole hiljaista palautusta englanninkielisiin `dedup`/`ultra` -sääntöihin, jotka muuttaisivat vieraita tekstiä). `en` / `es` / `id` / `pt-BR` ovat valmiit. `dedup.json` + `ultra.json` n osittaispakkaukset ovat tervetulleita.
- **Pinottu telemetria näyttää vain pakatut moottorit.** Pinotun putkilinjan vaihe, jonka moottori käy, mutta tuotti 0 % säästöjä, palauttaa `stats:null`, joten se ei näy `engineBreakdown` ssä — erotettavissa vaiheesta, joka ohitettiin. "Ajoi, 0 %" erottaminen "ohitetusta" vaatisi erittelymallin muutoksen, ja sitä lykätään.

## Validointi

Tämän alueen keskitetyt portit ovat:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
