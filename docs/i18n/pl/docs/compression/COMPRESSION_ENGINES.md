# Compression Engines (Polski)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

Kompresja OmniRoute opiera się na kontraktach silnika. Tryb może bezpośrednio uruchamiać jeden silnik (`caveman` lub `rtk`) lub deterministyczny potok skumulowany, który uruchamia wiele silników w kolejności.

## Tryby

| Tryb         | Ścieżka silnika                                                                                    | Zamierzone wejście                                           |
| ------------ | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| `off`        | nic                                                                                                | Dokładna, szybka konserwacja                                 |
| `lite`       | Jaskiniowcy Lite pomocnicy                                                                         | Zawsze włączone czyszczenie o niskim ryzyku                  |
| `standard`   | Jaskiniowiec                                                                                       | Szybka kondensacja w języku naturalnym                       |
| `aggressive` | Podsumowania jaskiniowca + history/tool                                                            | Długie sesje rozmów                                          |
| `ultra`      | Jaskiniowiec + pomocnicy przy przycinaniu                                                          | Odzyskiwanie ograniczone kontekstem                          |
| `rtk`        | RTK                                                                                                | Terminal, powłoka, kompilacja, test i wyjście git            |
| `omniglyph`  | OmniGlyph                                                                                          | Kontekst jako obraz na natywnym kablu dostawcy               |
| `stacked`    | Rurociąg. Domyślnym żądaniem jest `session-dedup -> lite`. `rtk -> caveman` jest opcją opcjonalną. | Mieszane dzienniki narzędzi i proza, maksymalne oszczędności |

### profile kompresyjne OmniGlyph

Silnik `omniglyph` (pakiet `omniglyph`, 1.4.0 +) akceptuje nazwany profil semantyczny, ustawiany globalnie poprzez `omniglyph.profile` w ustawieniach kompresji lub krokowo poprzez konfigurację kroków stosu potoku:

| Profil        | Granica                                                                                                       |
| ------------- | ------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Domyślny. Polityka opublikowanych wpływów mierzona systemem obrazów —, dokumentacją narzędzi i gęstą historią |
| `balanced`    | Utrzymuje natywny stan aktywny, chroni ostatnie 8 tur, zwija starszą zamkniętą historię                       |
| `coding-safe` | Zachowuje uprawnienia, schematy narzędzi i dane wyjściowe narzędzia na żywo, chroni ostatnie 12 tur           |
| `passthrough` | Trasy bez przekształcania; silnik jest pomijany                                                               |

Profil to A** sufit, a nie podłoga** : `mergeCompressionProfileOptions` w pakiecie nie pozwala wywołującemu zastąpić ponownego otwarcia pasa stratnego, profil został zamknięty, więc `preserveSystemPrompt: false` na krok nie może ponownie włączyć kompresji systemu w ramach `coding-safe`.

Mierzone na podstawie tej bazy kodu: `coding-safe` i `balanced` podnoszą `minCompressChars` do maksimum i zachowują natywne systemy, schematy narzędzi i wyniki narzędzi, więc sesja, która nie zgromadziła jeszcze historii, zatrzymuje się w `below_min_chars`, a silnik niczego nie przekształca. Dlatego domyślnym profilem jest `aggressive`, a nie najbezpieczniejszy profil.

Pakiet rozpoznaje swój własny zakres modelu i profil na podstawie konfiguracji środowiska. OmniRoute nigdy nie deleguje decyzji: adapter przypina bramę modelu do najbardziej restrykcyjnego zakresu pakietu, więc ustawienia środowiska hosta mogą jedynie zawęzić listę dozwolonych, nigdy jej nie poszerzać poza zmierzone wpływy OmniRoute.

## Rejestr silnika

Rejestr znajduje się w `open-sse/services/compression/engines/registry.ts`. Silniki ujawniają wspólną umowę:

- `id`: stabilny identyfikator silnika, taki jak `caveman` lub `rtk`
- `apply(text, config)`: starsza ścieżka wykonania używana przez potoki skumulowane
- `compress(input, config)`: podstawowa ścieżka wykonania zwracająca tekst statystyk +
- `getConfigSchema()`: zwraca kształt prawidłowej konfiguracji podobny do schematu JSON
- `validateConfig(config)`: zwraca `{ valid, errors[] }`

Rejestracja wykorzystuje `registerCompressionEngine(engine)` (lub `registerEngine` w zaawansowanych przypadkach), które wywołuje `assertValidEngine()` i `validateConfig(defaultConfig)` przed zaakceptowaniem. Użyj `unregisterCompressionEngine(id)`, aby usunąć silnik w czasie wykonywania.

`strategySelector.ts` rejestruje wbudowane silniki przed uruchomieniem kompresji. Dzięki temu podgląd, kompresja w czasie wykonywania, tryb stosowy, testy i przyszłe silniki korzystają z tej samej ścieżki wykonania.

### MCP opis kompresja (powiązane)

Oddzielny rejestr kompresuje metadane opisu narzędzia MCP na poziomie rejestru — patrz `open-sse/mcp-server/descriptionCompressor.ts` i [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Wykorzystuje reguły jaskiniowca, ale działa na metadanych narzędzi, a nie na ładunkach żądań.

### Dodatkowe wbudowane silniki

Poza Caveman, RTK i LLMLingua-2 rejestr zawiera kilka wyspecjalizowanych silników bezstratnych/strukturalnych (używanych w ułożonych w stos rurociągach, na placu zabaw i w testach):

| Silnik               | Id              | Co to robi                                                                                                                                                                     |
| -------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CCR                  | `ccr`           | Content-Compress-Retrieve (H4): zastępuje duże, ciągłe bloki tekstu odniesieniami adresowanymi do treści, więc bloki repeated/large są wysyłane raz, a następnie przywoływane. |
| przestrzeń nad głową | `headroom`      | SmartCrusher (H3 + N5): bezstratne zagęszczenie tabelaryczne jednorodnych ładunków tablicy JSON do postaci kolumnowej `[N rows]`.                                              |
| jonizator            | `ionizer`       | próbkowanie wierszy Head/middle/tail dla bardzo dużych jednorodnych bloków, przechowując środek z pominięciem jako odniesienie do zawartości CCR.                              |
| deduplikacja sesji   | `session-dedup` | Deduplikacja między turami adresowana do treści (inspirowana TokenMizer): usuwa tekst widoczny już we wcześniejszych turach tej samej sesji.                                   |

**Instrukcja protokołu pobierania CCR (#8033):** za pierwszym razem, gdy CCR zastępuje w żądaniu 1 blok ≥, silnik dołącza na początku pojedynczy idempotentny komunikat `system` (na początku `[CCR protocol]` Sentinel) ucząc wywołującego znacznik → Tool Contract: co oznacza znacznik `[CCR retrieve hash=<24hex> chars=N]`, że skrót musi zostać skopiowany dosłownie (wszystkie 24 znaki szesnastkowe błędnie skopiowane skróty — są prawdopodobną przyczyną chybień „nie znaleziono bloku”) oraz że znacznik `[dedup:ref sha=...]` oznacza „spójrz wstecz na historię”, a nie „wywołaj narzędzie”. Notatka zostaje wstrzyknięta** tylko wtedy, gdy reklamowane `tools[]` dzwoniącego udowodni, że faktycznie może osiągnąć `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — zwykły program wywołujący zgodny z OpenAI bez tego narzędzia nigdy nie otrzyma instrukcji wywołania czegoś, do czego nie może dotrzeć. Idempotencja jest wymuszana poprzez skanowanie historii wiadomości dla wartownika przed wstrzyknięciem, więc żądania wieloturowe (które odtwarzają poprzednie wiadomości) nie kumulują notatki raz na turę.

## Jaskiniowiec

Tryb jaskiniowca skupia się na semantycznej kondensacji normalnej prozy:

- zachowuje bloki kodu, URLs, JSON, ścieżki i dane strukturalne
- usuwa wypełniacze, zabezpieczenia, powtarzający się kontekst i pełne sformułowania łączące
- obsługuje pakiety reguł plików uwzględniających język w `open-sse/services/compression/rules/`
- pozostaje dostępny w starszych trybach `standard`, `aggressive` i `ultra`

Powierzchnia deski rozdzielczej to `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream raportuje mniejszą liczbę tokenów wyjściowych `~75%`, średnie oszczędności wyjściowe `65%` w testach porównawczych z zakresem `22-87%` oraz narzędzie do kompresji danych wejściowych `~46%`. OmniRoute używa numeru wejściowego jaskiniowca podczas dokumentowania skumulowanych oszczędności prompt/context ; Tryb wyjściowy jaskiniowca pozostaje odrębną funkcją odpowiedzi i zachowania.

## RTK

Tryb RTK koncentruje się na wynikach poleceń i narzędzi:

- wykrywa klasy wyjściowe, takie jak `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, testy Cargo/Go, kompilacje TypeScript/Vite/Webpack, ESLint, npm audit/installs, dzienniki Docker, powłoka `find`/`grep`, ślady stosu i logi ogólne
- stosuje 49 filtrów JSON firmy `open-sse/services/compression/engines/rtk/filters/`
- obsługuje deklaratywny potok w stylu RTK: usuwanie ANSI, zamiana, zwarcie na wyjściu dopasowania, linie strip/keep, obcięcie per-line, obcięcie head/tail/max-line i powrót przy pustym
- obsługuje filtry projektów bramkowanych zaufaniem w `.rtk/filters.json` i filtry globalne w `DATA_DIR/rtk/filters.json`
- usuwa sekwencje ANSI, szum postępu, powtarzające się linie i nieprzydatny schemat
- zachowuje możliwe do podjęcia działania awarie, ostrzeżenia, podsumowania, zmienione pliki i kontekst końcowy
- może opcjonalnie zachować zredagowane surowe dane wyjściowe dla recovery/debugging poprzez uwierzytelnione ścieżki zarządzania

Powierzchnia deski rozdzielczej to `Dashboard -> Context & Cache -> RTK`.

Szczegóły operacyjne dotyczące niestandardowych filtrów, zaufania, weryfikacji i odzyskiwania nieprzetworzonych danych wyjściowych są dostępne w [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream raportuje oszczędności `60-90%` w zakresie kompresji danych wyjściowych poleceń. Jego przykład README pokazuje 30-minutową sesję kodu Claude przechodzącą z tokenów `~118,000` do `~23,900` lub zapisanego `79.7%`.

## LLMLingua-2 (przycinanie semantyczne)

działa tryb LLMLingua-2** przycinanie tokenów semantycznych** o prozie przy użyciu małego klasyfikatora tokenów ONNX, uzupełniającego oparte na regułach silniki Caveman i RTK :

- kompresuje prozę wyłącznie w komunikatach niesystemowych; chronione bloki kodu i inne zachowane konstrukcje nigdy nie są zmieniane
- uruchamia backend `@atjsh/llmlingua-2` (ONNX przez `@huggingface/transformers`) w wątku roboczym, więc wnioskowanie o modelu nigdy nie blokuje pętli zdarzeń żądania
- Jest** możliwość układania w stosy** (`stackPriority` 35): w potoku skumulowanym działa po silnikach strukturalnych (CCR, session-dedup, headroom, Caveman), ale przed `ultra`, ponieważ przycinanie semantyczne jest najskuteczniejsze w przypadku już skompresowanego strukturalnie tekstu — np. `rtk -> caveman -> llmlingua`
- **otwiera się w przypadku dowolnego błędu** (brak opcjonalnych punktów, odrodzenia pracowników, ładowania modelu, wnioskowania lub przekroczenia limitu czasu) → oryginalny tekst jest zwracany bez zmian, nigdy nie jest to błąd

Lokalizacja silnika: `open-sse/services/compression/engines/llmlingua/`. Powierzchnia deski rozdzielczej to `Dashboard -> Context & Cache -> LLMLingua`.

### Modele

Domyślny model to**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, szybko). Większa dokładność** Baza BERT** model (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) jest dostępny poprzez pole konfiguracji silnika `model`. `@huggingface/transformers` leniwie pobiera wybrany model z HuggingFace Hub do `${DATA_DIR}/models/llmlingua` przy pierwszym połączeniu (`modelStore.ts`); zastąpienie konfiguracji `modelPath` wskazuje zamiast tego kopię lokalną (instalacje offline / z przerwami powietrznymi).

### Opcjonalne zależności i instalacja na żądanie

Stos równorzędny środowiska wykonawczego LLMLingua który można wyczyścić, to** fakultatywny** . Dwa pakiety są zadeklarowane jako `optionalDependencies` w `package.json` i przechowywane** zewnętrzny** według wersji produkcyjnej (`scripts/build/prepublish.ts` nie łączy ich w pakiet):

| Pakiet               | Wersja (pin) | Notatki                                             |
| -------------------- | ------------ | --------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`      | Pakiet wejściowy; deklaruje innych jako rówieśników |
| `js-tiktoken`        | `^1.0.20`    | Tokenizator                                         |

`@huggingface/transformers` jest przypięty do `^4.2.0` (współdzielony z lokalną ścieżką osadzania, a także śledzony w samodzielnym pakiecie); `@atjsh/llmlingua-2@2.0.5` łączy się z nim za pomocą `"^3.5.2 || ^4.0.0"`, więc obsługiwane są zarówno Transformers.js v3, jak i v4. Od wersji 2.0.4 `@atjsh/llmlingua-2` nie wymaga już `@tensorflow/tfjs`, co usunęło największego pojedynczego współautora (TensorFlow.js) ze stosu SLM. Tylko dwa powyższe pakiety są możliwymi do czyszczenia peerami SLM. Standardowy `npm install` (dev) instaluje opcjonalny stos automatycznie, chyba że pominięto opcjonalne zależności.

**Dlaczego na żądanie:** pakiet npm-published, pakiet samodzielny i statek z obrazami Docker** bez** te głębokości, aby zachować szczupłą sylwetkę. Gdy są one nieobecne, bramka zależności procesu roboczego (sonda `@atjsh/llmlingua-2` w `worker.ts`) ulega awarii i silnik** otwiera się po cichu** — wybranie LLMLingua staje się niewykonaniem operacji (tekst zwrócony bez zmian, nie zarejestrowany żaden błąd). Aby aktywować go w oczyszczonym środowisku, zainstaluj opcjonalny stos:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Usunięcie `@tensorflow/tfjs` (2.0.4 +) eliminuje wcześniej dominującego współautora ~ 800 MB — pozostały ślad to środowiska wykonawcze transformers.js + onnxruntime-node plus model TinyBERT (~ 57 MB) pobrany przy pierwszym użyciu (nie przez npm).

Na środowisko:

- **Dev / `npm install`** — instaluje się automatycznie, chyba że przekazałeś `--omit=optional` (lub `--no-optional`). Żadne działanie nie jest potrzebne.
- **Globalny npm (`npm i -g omniroute`) / samodzielny** — uruchom powyższą komendę install w katalogu zainstalowanego pakietu lub zainstaluj ponownie bez pomijania opcjonalnych deps.
- **Docker** — dodaj polecenie install w pochodnej warstwie obrazu; opublikowany obraz jest z założenia smukły.
- **VPS (PM2)** — zainstaluj w `node_modules` aplikacji, a następnie uruchom ponownie proces, aby pracownik ponownie sprawdził bramę.
- **Raw Next samodzielny (`npm run build` → `.build/next/standalone/server.js`)** — samodzielnych statków śledzących NEITHER pracownika ani opcjonalnych oddziałów, więc silnik cicho wyłącza się po awarii. `scripts/build/colocate-standalone.mjs` ponownie stosuje oba (proces roboczy esbuild + opcjonalne zamknięcie do samodzielnego drzewa); działa automatycznie poprzez hak `postbuild` npm po każdej kompilacji. Idempotentny, miękki w przypadku braku depsów.

**Sprawdź, czy jest aktywny:** po wybraniu LLMLingua prawdziwa proza faktycznie się kurczy (silnik przestaje otwierać się w przypadku awarii), a pierwsze żądanie powoduje pobranie modelu do `${DATA_DIR}/models/llmlingua`. Brama celowo sonduje tylko `@atjsh/llmlingua-2` — pozostałe peery korzystają tylko z ESM i `require.resolve` rzuca na nich nawet wtedy, gdy jest obecny —, więc proces roboczy nadal otwiera się awaryjnie, jeśli w czasie `import()` rzeczywiście brakuje któregokolwiek z równorzędnych partnerów.

## Ułożone rurociągi

Tryb skumulowany uruchamia kroki potoku w kolejności. Wartość domyślna to:

```txt
rtk -> caveman
```

Użyj tej opcji w przypadku sesji agenta kodującego, w których zachęta łączy dane wyjściowe poleceń z prozą człowieka lub asystenta. RTK najpierw redukuje zaszumione dzienniki narzędzi, a następnie Caveman kompresuje pozostały język naturalny.

Kroki potoku są konfigurowane za pomocą `stackedPipeline` w ustawieniach kompresji lub poprzez kombinacje kompresji.

Gdy oba silniki zmniejszają tę samą kwalifikującą się ładowność, oszczędności się sumują:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Filtr drzewa dostępności

Inteligentny filtr drzewa dostępności MCP to warstwa kompresji po wykonaniu, która działa na MCP** wyniki narzędzia** , a nie w przypadku podpowiedzi lub kontekstu. Jego celem jest szczegółowe drzewo dostępności i migawki przeglądarki zwracane przez narzędzia takie jak Playwright, serwery MCP do obsługi komputera i automatyzacji przeglądarki.

### Co to robi

1. **Usuwanie szumów** — usuwa puste wpisy generic/text (`- generic:`, `- text: ""`)
2. **Upadek rodzeństwa** — gdy ≥ `collapseThreshold` (domyślnie 30) kolejne linie są powtórzeniami strukturalnymi, zwija je w pierwsze `collapseKeepHead` (domyślnie 10) linii + podsumowanie licznika + ostatnie `collapseKeepTail` (domyślnie 5) linii
3. **Zachowanie ref** — Kotwy `[ref=eXX]` wymagane przez Playwright/computer-use nigdy nie są dotykane
4. **Twarde obcięcie** — jeśli tekst po zwinięciu nadal przekracza `maxTextChars` (domyślnie 50 000), zostanie obcięty ze wskazówką nawigacyjną, aby agent mógł kontynuować pracę

### Lokalizacja silnika

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfiguracja

Kontrolowane przez `compression.mcpAccessibility` w ustawieniach globalnych (migracja 056). Domyślna konfiguracja:

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

Filtr jest stosowany tylko do ładunków wynikowych narzędzi, których `type` wynosi `"text"` i których długość przekracza `minLengthToProcess`. Nie ma to wpływu na szybką kompresję ani ładunki żądań.

### Oczekiwane oszczędności

60–80% wyników narzędzia migawki przeglądarki, w zależności od złożoności strony. Algorytm zwijania to O(n) w liczbie linii i dodaje znikome opóźnienie.

### Ten filtr w porównaniu z powyższymi silnikami kompresyjnymi

| Aspekt       | Jaskiniowiec / RTK / Ułożone   | filtr dostępności MCP                  |
| ------------ | ------------------------------ | -------------------------------------- |
| Cel          | Zapytaj o podpowiedzi/kontekst | wyniki narzędzia MCP                   |
| Spust        | Ustawienie trybu kompresji     | `compression.mcpAccessibility.enabled` |
| Zakres       | Wszystkie wiadomości SSE       | Tylko wyniki narzędzi                  |
| Ref. kotwice | N/A                            | Zachowane bezwarunkowo                 |

---

## Kombinacje kompresyjne

Kombinacje kompresji to tak zwane profile kompresji, które można przypisać do kombinacji routingu:

- `compression_combos`: tryb przechowywania, potok, konfiguracja RTK, konfiguracja języka i znacznik domyślny
- `compression_combo_assignments`: mapuje kombinację kompresji na kombinację routingu
- Integracja środowiska uruchomieniowego rozwiązuje przypisaną kombinację kompresji przed zastąpieniem kombinacji ogólnej
- narzędzia analityczne obejmują `compression_combo_id` i `engine`

Powierzchnia deski rozdzielczej: `Dashboard -> Context & Cache -> Compression Combos`.

## Wymagania wstępne / podręcznik operatora (CCR i session-dedup)

CCR (`ccr`) i `session-dedup` zastępują lub usuwają tekst i pozostawiają a** znacznik** za. Ta sekcja zawiera informacje dla operatora dotyczące okablowania klienta, odczytywania dwóch znaczników i pobierania lub diagnozowania pominiętej zawartości. Mechanika każdego silnika została opisana powyżej; to jest warstwa „jak to uruchomić”.

### Transporty i punkty końcowe

Do serwera MCP udostępniającego narzędzia CCR można dotrzeć na trzy sposoby. Domyślną bazą URL jest `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transport                            | URL / polecenie                         | Notatki                                                                                                                                                                      |
| ------------------------------------ | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Streamowalna HTTP (klient, zalecana) | `http://localhost:20128/api/mcp/stream` | Punkt końcowy, z którym rozmawiają bieżący klienci MCP.                                                                                                                      |
| Starszy singleton SSE                | `http://localhost:20128/api/mcp/sse`    | Starszy transport singletonowy. To** zamyka się** sesje nadające się do transmisji strumieniowej; używaj klientów `streamable-http` przeciwko `/api/mcp/stream`, a nie tego. |
| stdio                                | `omniroute --mcp`                       | Dla konfiguracji IDE MCP, która uruchamia proces. Nie ma flagi `--dev` ; `omniroute --mcp` jest punktem wejścia stdio.                                                       |

### Warstwy pamięci masowej (co przetrwa ponowne uruchomienie)

CCR jest** dwupoziomowy** przechowuj, a nie tylko w pamięci:

- **Gorąca warstwa w pamięci** — na blok 2 MiB, na głównego 16 MiB, globalnie 64 MiB. Wpisy są domyślnie ustawione na 24 godziny TTL (maksymalnie 7 dni). Pełne pobieranie MCP z pamięci jest ograniczone do 256 KiB; wszystko większe jest nadal osiągalne w trybach ranged/grep.
- **Trwała warstwa SQLite** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, domyślnie włączone) — tworzy kopię zapasową warstwy w pamięci, dzięki czemu blok przetrwa eksmisję LRU, ponowne uruchomienie lub lądowanie pobierania w innej instancji. Wiersz zachowuje TTL bloku, więc blok znajdujący się za jego TTL znika z obu poziomów.

Trzech strażników utrzymuje trwały, ograniczony poziom — blok pozostaje tylko w pamięci, gdy:

1. blok się skończył** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. środowisko wykonawcze jest środowiskiem wykonawczym w chmurze (bez dysku lokalnego);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Zatem „blok zniknął” nie jest ogólną historią ponownego uruchomienia: blok sub-512 KB w lokalnym środowisku wykonawczym innym niż chmura przetrwa ponowne uruchomienie za pośrednictwem trwałej warstwy, aż do wyczerpania się jego TTL. Zobacz [Informacje o środowisku](../reference/ENVIRONMENT.md) dla zmiennej.

### Dwa znaczniki

| Znacznik                              | Oznaczający                                                                                                                                    | Co modelka powinna zrobić                                                                                                                                                                                                     |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Zapisano duży blok z adresem treściowym.                                                                                                       | Zadzwoń do `omniroute_ccr_retrieve` za pomocą** Hash 24-szesnastkowy skopiowany dosłownie** aby odzyskać oryginalny tekst.                                                                                                    |
| `[dedup:ref sha=…]`                   | `session-dedup` usunął tekst wysłany już we wcześniejszej turze tej samej sesji. To jest** celowe spojrzenie wstecz** , a nie strata czy błąd. | Do** nie** zadzwoń do dowolnego narzędzia i zrób to** nie** spróbuj go „zrekonstruować”. Pierwszym wystąpieniem tekstu jest kopia kanoniczna; bieżąca tura nigdy nie jest przepisana, jest deduplikowana w późniejszej turze. |

Przeglądanie `[dedup:ref]` jest celową decyzją protokołu. — nie ma rekonstrukcji przed wysłaniem. Potraktuj to tak, jakby „ten dokładny tekst był już w sieci wcześniej w tej sesji”.

### Wymagania wstępne klienta

- **Klucz (stdio):** wywołujący stdio nie ma tożsamości na żądanie, więc uwierzytelnia się za pomocą `OMNIROUTE_API_KEY` (ustawionego w `env` serwera MCP ). Bez tego rozmówca jest anonimowy, a narzędzia wymagające zleceniodawcy mogą ulec degradacji.
- **`tools[]` jest warunkiem wstępnym wstrzyknięcia.** Wstrzykiwana jest instrukcja protokołu pobierania CCR (#8033).** tylko** kiedy reklamowany `tools[]` żądania udowodni, że klient faktycznie może dotrzeć `omniroute_ccr_retrieve`. Dopasowanie jest dopasowaniem końcowego segmentu ograniczonego separatorem (`__`, `.`, `/`, `:`) — nigdy nie jest gołym podłańcuchem —, więc nazwa z przestrzenią nazw, taka jak `mcp__gateway__omniroute_ccr_retrieve` nadal się liczy. Brak lub niepasujący `tools[]` oznacza, że instrukcja _nie_ jest wstrzykiwana zgodnie z projektem.
- **`codemode:false` (klienci OpenCode ).** OpenCode domyślnie korzysta z trybu kodu, który anonsuje modelowi tylko swoje natywne narzędzia** nie** umieść narzędzia MCP na natywnej liście `tools[]`. Ustaw `codemode: false` we wpisie serwera MCP, aby narzędzia `omniroute_ccr_*` były reklamowane. To jest** klient** ustawienie, a nie OmniRoute. Nie otrzymuje jeszcze wstrzykniętej instrukcji CCR : OpenCode nazywa narzędzie `<server>_<tool>`, więc serwer o nazwie `omniroute` udostępnia `omniroute_omniroute_ccr_retrieve`, a `_` nie jest jednym z dopasowanych separatorów.
- **Dyrektorzy.** Przechowywanie i pobieranie są izolowane dla każdego uwierzytelnionego podmiotu zabezpieczeń (na klucz API ). Klucz widzi tylko swoje własne bloki.

### Zakresy na narzędzie

Wymuszanie zakresu jest zawsze włączone dla obiektów wywołujących HTTP/SSE o wąskim zakresie. Narzędzia CCR `omniroute_` :

| Narzędzie                | Zakres              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Brakujący zakres zwraca an** Wynik błędu narzędzia MCP** (`isError: true`, a nie HTTP 403 — `403 LOCAL_ONLY` jest oddzielnym autoryzacją strażnika trasy pętli zwrotnej): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Minimalny klucz zdalny może przechowywać `mcp:connect` (autoryzuje wycięcie `/api/mcp/` tylko lokalnie) plus specyficzny zakres read/write którego potrzebuje.

### Matryca klienta

| Klient                | Transport                                      | Konfiguracja do użycia                                                                                                                                                                                                                           | `tools[]` reklamowane? (wstrzyknięto instrukcję → CCR )                                                                                                                                                         |
| --------------------- | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Kod Claude            | przesyłane strumieniowo-http                   | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                | Tak — Obsługa MCP; wstrzyknięty.                                                                                                                                                                                |
| Cursor / Cline        | `stdio`** Lub** `streamable-http`              | stdio: `omniroute --mcp` z `OMNIROUTE_API_KEY` w `env`; lub zdalny wpis MCP wskazujący na `http://localhost:20128/api/mcp/stream` (patrz [Podręcznik instalacji → MCP Konfiguracja klienta](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Tak — reklamuje narzędzia `omniroute_ccr_*`.                                                                                                                                                                    |
| OpenCode              | przesyłane strumieniowo-http                   | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream` plus `codemode: false`                                                                                                                                                  | Narzędzia reklamowane tylko z `codemode: false`; instrukcja nadal nie została wstrzyknięta, ponieważ `omniroute_omniroute_ccr_retrieve` nie pasuje (patrz [Wymagania wstępne klienta](#client-prerequisites) ). |
| Kompatybilny z OpenAI | HTTP kompatybilny z OpenAI (zakończenia czatu) | standardowy klient uzupełniania czatu z punktem końcowym zgodnym z OpenAI                                                                                                                                                                        | **Nigdy** — Zwykły program wywołujący zgodny z OpenAI nigdy nie otrzymuje polecenia wywołania narzędzia, a instrukcja nie jest wstrzykiwana.                                                                    |

### Limity pobierania i paginacja

Wyniki tekstowe narzędzia MCP są obcinane wokół `mcpAccessibility.maxTextChars` (domyślnie `50000`). `full` odzyskanie bloku jest ograniczone do 256 KiB —** nie ma nieograniczonego pełnego pobierania** . Kiedy `chars=N` bloku jest duże, stronicuj go zamiast ciągnąć całość:

- Praktyczna zasada:**`chars > 40000` → użyj `mode`** , nigdy do pełna.
- `mode:"grep"` — regex `pattern` dopasowuje linia po linii, do 1000 pasujących linii (`unique: true` upuszcza powtórzenia), najtańszy dla „znajdź jedną linię, której potrzebuję”.
- `mode:"lines"` — zakres linii o indeksie 1; potrzebuje zarówno `start` jak i `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` linie.
- `mode:"stats"` — liczy linię, znak i bajt bez treści.

Użyj `mode:"lines"` z `start`/`end`, aby przejść długi blok na stronach, zamiast żądać całości na raz.

### Nazewnictwo narzędzi

Narzędzie do pobierania nosi obecnie nazwę `omniroute_ccr_retrieve` (przedrostek `omniroute_` to przestarzałe rozwiązanie problemu kolizji nazw między serwerami). Czystsza nazwa narzędzia z ograniczonymi sufiksami i poprawka dla wyników MCP JSON obciętych w środkowym ciągu znaków są śledzone jako kontynuacje w górę; ta strona dokumentuje wyłącznie bieżące, dostarczane zachowanie.

### Cykl życia sesji

Sesje Streamable-HTTP są bezczynne i serwer je zbiera; oknem bezczynności jest stała `MCP_SESSION_IDLE_MS` (do której odwołuje się nazwa, a nie zakodowana na stałe wartość, więc ta strona nie zmienia się, gdy się zmienia). Objawem bezczynnej sesji jest HTTP 404 z `Unknown Mcp-Session-Id` — rozwiązaniem jest ponowne połączenie lub ponowne uruchomienie sesji,** nie** aby obrócić klucz, zmienić zakres lub zmienić nazwę narzędzia.

## API Powierzchnia

| Trasa                                  | Zamiar                                                                 |
| -------------------------------------- | ---------------------------------------------------------------------- |
| `/api/settings/compression`            | Globalne ustawienia kompresji (w tym konfiguracja `mcpAccessibility` ) |
| `/api/compression/preview`             | Podgląd dowolnego trybu kompresji                                      |
| `/api/compression/language-packs`      | Lista dostępnych pakietów językowych Caveman                           |
| `/api/context/caveman/config`          | Alias ustawień jaskiniowca                                             |
| `/api/context/rtk/config`              | Domyślne i ustawienia RTK                                              |
| `/api/context/rtk/filters`             | katalog filtrów RTK                                                    |
| `/api/context/rtk/test`                | RTK punkt końcowy preview/test                                         |
| `/api/context/rtk/raw-output/[id]`     | Uwierzytelnione, zredagowane odzyskiwanie danych wyjściowych           |
| `/api/context/combos`                  | Kombinacja kompresji CRUD                                              |
| `/api/context/combos/[id]/assignments` | Przypisanie kombinacji routingu CRUD                                   |
| `/api/context/analytics`               | Alias analizy kompresji                                                |

Trasy zarządzania wymagają uwierzytelniania zarządzania lub kontroli zasad klucza API.

## MCP Narzędzia

Kompresja udostępnia pięć narzędzi MCP :

| Narzędzie                           | Zakres              | Zamiar                                               |
| ----------------------------------- | ------------------- | ---------------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Ustawienia, analityka, statystyki pamięci podręcznej |
| `omniroute_compression_configure`   | `write:compression` | Zaktualizuj ustawienia globalne                      |
| `omniroute_set_compression_engine`  | `write:compression` | Ustaw tryb i opcjonalny potok                        |
| `omniroute_list_compression_combos` | `read:compression`  | Lista kombinacji kompresji                           |
| `omniroute_compression_combo_stats` | `read:compression`  | Przeczytaj statystyki combo/engine                   |

## Zakres i wyłączenia

**Osadzenia nigdy nie są kompresowane.** `open-sse/handlers/embeddings.ts` nigdy nie wywołuje żadnego silnika kompresji — ciała request/response przechodzą prosto do executora w nienaruszonym stanie. Dziś ma to charakter strukturalny (osadzanie i uzupełnianie czatów to rozłączne procedury obsługi), a nie kontrola w czasie wykonywania, ale oznacza to, że problem zniekształcenia wektora w #8034 nie ma powierzchni eksponowanej na ścieżce osadzania.

**filtr wykluczający Per-model/endpoint (#8034).** W przypadku uzupełniania czatu operator może nazwać identyfikatory modeli/obiekty `provider/model`, które nigdy nie mogą być kompresowane — poręcz przydatną, jeśli kompresja zostanie kiedykolwiek później podłączona bliżej ścieżki sąsiadującej z osadzeniem, i ogólnie przydatna dla każdego modelu, dla którego liczy się dokładny monit bajt po bajcie (deterministyczne wartości ewaluacyjne, prefiksy wrażliwe na pamięć podręczną itp.).

- Pole ustawień: `exclusions?: string[]` w globalnej konfiguracji kompresji (`GET`/`PUT /api/settings/compression`), utrwalone poprzez istniejącą przestrzeń nazw kompresji `key_value` (`src/lib/db/compression.ts`) — bez nowej tabeli.
- Zakładka Panel:** Deska rozdzielcza → Kompresja → Wyłączenia** (`/dashboard/compression/exclusions`).
- Składnia wzorca: `*` jest jedynym symbolem wieloznacznym. Przed dopasowaniem następuje ucieczka przed każdym innym metaznakiem wyrażenia regularnego we wzorcu, więc `gpt-5.6` dopasowuje tylko ciąg dosłowny, nigdy `gpt-5x6` (bezpieczny dla ReDoS, ograniczony, bez zagnieżdżonych kwantyfikatorów). Wzorce dopasowują się bez uwzględniania wielkości liter zarówno w przypadku samego identyfikatora modelu, jak i kompozytu `provider/model` — `gpt-5-6`, `openai/gpt-5-6` i `openai/*` wszystkie działają, a samo `*` wyklucza każdy model.
- Dopasowanie: `isCompressionExcluded()` / `normalizeCompressionExclusions()` w `open-sse/services/compression/exclusions.ts`. `chatCore.ts` sprawdza wykluczony cel zaraz po ustaleniu ustawień kompresji,** zanim jakikolwiek silnik uruchomi się** i traktuje dopasowanie dokładnie tak, jak globalnie wyłączona kompresja — treść żądania jest prawdopodobnie identyczna pod względem bajtów. Pominięcie jest rejestrowane przez `writeCompressionSkip(..., "excluded")` w celu zapewnienia widoczności analiz.
- Domyślnie (lista empty/absent ): identyczne z zachowaniem pre-#8034 — nic nie jest wykluczone.

## Znane ograniczenia

- **LLMLingua-2 (SLM) wymaga opcjonalnych depsów znajdujących się w pobliżu.** Proces roboczy działa tylko w wersji produkcyjnej, gdy elementy równorzędne `@atjsh/llmlingua-2` + są zlokalizowane w `dist/node_modules` (patrz `scripts/build/colocateOptionals.mjs`, #4286). Bez nich silnik ulegnie awarii (zwróci oryginalny tekst). Rozdzielczość procesu roboczego nie zależy już od `import.meta.url` (umiera w samodzielnym pakiecie) — który zakotwicza w środowisku wykonawczym cwd / `argv[1]`.
- **Pakiety językowe Caveman `de` / `fr` / `ja` są częściowe.** Dostarczają reguły `context` + `filler` + `structural`, ale bez pakietów `dedup` / `ultra`, więc intensywność `ultra` nie jest większa niż `full` dla tych języków (używają tylko własnych reguł — nie ma cichego powrotu do angielskich reguł `dedup`/`ultra`, które zniekształciłyby obcy tekst). `en` / `es` / `id` / `pt-BR` są gotowe. Wkład `dedup.json` + `ultra.json` dla pakietów częściowych jest mile widziany.
- **Skumulowana telemetria wyświetla tylko listę silników, które zostały skompresowane.** Krok potoku skumulowanego, którego silnik działał, ale wygenerował 0% oszczędności, zwraca `stats:null`, zatem nie pojawia się w `engineBreakdown` — w sposób nieodróżnialny od kroku, który został pominięty. Rozróżnienie „ubiegło, 0%” od „pominiętego” wymagałoby zmiany modelu podziału i zostało odroczone.

## Walidacja

Bramy skupiające się na tym obszarze to:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
