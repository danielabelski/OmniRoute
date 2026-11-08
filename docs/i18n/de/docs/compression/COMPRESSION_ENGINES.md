# Compression Engines (Deutsch)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute Komprimierung basiert auf Engine-Verträgen. Ein Modus kann eine Engine direkt ausführen (`caveman` oder `rtk`) oder eine deterministische gestapelte Pipeline, die mehrere Engines der Reihe nach ausführt.

## Modi

| Modus        | Motorpfad                                                                                    | Beabsichtigte Eingabe                                         |
| ------------ | -------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| `off`        | keiner                                                                                       | Exakte zeitnahe Konservierung                                 |
| `lite`       | Caveman Lite-Helfer                                                                          | Risikoarme, ständig aktive Bereinigung                        |
| `standard`   | Höhlenmensch                                                                                 | Prompt-Verdichtung in natürlicher Sprache                     |
| `aggressive` | Caveman + history/tool Zusammenfassungen                                                     | Lange Chat-Sitzungen                                          |
| `ultra`      | Caveman + Beschneidungshelfer                                                                | Kontextlimitierte Wiederherstellung                           |
| `rtk`        | RTK                                                                                          | Terminal-, Shell-, Build-, Test- und Git-Ausgabe              |
| `omniglyph`  | OmniGlyph                                                                                    | Kontext als Bild auf der nativen Anbieterleitung              |
| `stacked`    | Pipeline. Der Anforderungsstandard ist `session-dedup -> lite`. `rtk -> caveman` ist Opt-In. | Gemischte Werkzeugprotokolle und Prosa, maximale Einsparungen |

### OmniGlyph Komprimierungsprofile

Die `omniglyph` Engine (Paket `omniglyph`, 1.4.0 +) akzeptiert ein benanntes semantisches Profil, das global über `omniglyph.profile` in den Komprimierungseinstellungen oder pro Schritt über die Schrittkonfiguration der gestapelten Pipeline festgelegt wird:

| Profil        | Grenze                                                                                                                |
| ------------- | --------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Standard. Die Richtlinie der veröffentlichten Belege maß — -Bildsystem, die Werkzeugdokumente und den dichten Verlauf |
| `balanced`    | Behält den Live-Status nativ bei, schützt die letzten 8 Runden und reduziert den älteren geschlossenen Verlauf        |
| `coding-safe` | Behält Autorität, Werkzeugschemata und Live-Werkzeugausgabe nativ bei und schützt die letzten 12 Runden               |
| `passthrough` | Routen ohne Umgestaltung; Der Motor wird übersprungen                                                                 |

Das Profil ist ein** Decke, kein Boden** : `mergeCompressionProfileOptions` im Paket weigert sich, einem Anrufer das Überschreiben einer verlustbehafteten Spur zu überschreiben, wenn das Profil geschlossen wurde, sodass ein pro-Schritt `preserveSystemPrompt: false` die Systemkomprimierung unter `coding-safe` nicht wieder aktivieren kann.

Gemessen an dieser Codebasis: `coding-safe` und `balanced` erhöhen `minCompressChars` auf sein Maximum und halten System, Tool-Schemata und Tool-Ergebnisse nativ, sodass eine Sitzung, die noch keinen Verlauf angesammelt hat, bei `below_min_chars` stoppt und die Engine nichts transformiert. Aus diesem Grund ist die Standardeinstellung `aggressive` und nicht das sicherste Profil.

Das Paket löst seinen eigenen Modellbereich und sein eigenes Profil aus seiner Umgebungskonfiguration auf. OmniRoute delegiert die Entscheidung niemals: Der Adapter fixiert das Modell-Gate an den restriktivsten Bereich des Pakets, sodass Host-Umgebungseinstellungen die Zulassungsliste nur einschränken und niemals über die gemessenen Belege von OmniRoute hinaus erweitern können.

## Motorregister

Das Register befindet sich in `open-sse/services/compression/engines/registry.ts`. Engines legen einen gemeinsamen Vertrag offen:

- `id`: stabile Engine-ID wie `caveman` oder `rtk`
- `apply(text, config)`: Legacy-Ausführungspfad, der von gestapelten Pipelines verwendet wird
- `compress(input, config)`: Primärer Ausführungspfad, der Text- + Statistiken zurückgibt
- `getConfigSchema()`: Gibt die JSON-Schema-ähnliche Form einer gültigen Konfiguration zurück
- `validateConfig(config)`: gibt `{ valid, errors[] }` zurück

Bei der Registrierung wird `registerCompressionEngine(engine)` (oder `registerEngine` für fortgeschrittene Fälle) verwendet, das vor der Annahme `assertValidEngine()` und `validateConfig(defaultConfig)` aufruft. Verwenden Sie `unregisterCompressionEngine(id)`, um eine Engine zur Laufzeit zu entfernen.

`strategySelector.ts` registriert die integrierten Engines, bevor die Komprimierung ausgeführt wird. Dadurch können Vorschau, Laufzeitkomprimierung, Stapelmodus, Tests und zukünftige Engines denselben Ausführungspfad verwenden.

### MCP -Beschreibungskomprimierung (verwandt)

Eine separate Registrierung komprimiert die Metadaten MCP Tools auf Registrierungsebene — siehe `open-sse/mcp-server/descriptionCompressor.ts` und [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Es verwendet Caveman-Regeln wieder, arbeitet jedoch mit Tool-Metadaten und nicht mit Anforderungsnutzdaten.

### Zusätzliche Einbaumotoren

Neben Caveman, RTK und LLMLingua-2 liefert die Registry mehrere spezialisierte verlustfreie/strukturelle Engines (die von gestapelten Pipelines, dem Spielplatz und Tests verwendet werden):

| Motor          | Ausweis         | Was es bewirkt                                                                                                                                                                                    |
| -------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR            | `ccr`           | Content-Compress-Retrieve (H4): Ersetzt große zusammenhängende Textblöcke durch inhaltsadressierte Referenzen, sodass repeated/large Blöcke einmal gesendet und anschließend referenziert werden. |
| Kopffreiheit   | `headroom`      | SmartCrusher (H3 + N5): verlustfreie tabellarische Komprimierung homogener JSON-Array-Nutzlasten in eine spaltenförmige `[N rows]` Form.                                                          |
| Ionisator      | `ionizer`       | Head/middle/tail -Zeilenabtastung für sehr große homogene Blöcke, wobei die eliminierte Mitte als inhaltsadressierte CCR -Referenz gespeichert wird.                                              |
| Sitzungs-dedup | `session-dedup` | Inhaltsadressierte Cross-Turn-Deduplizierung (TokenMizer-inspiriert): Eliminiert Text, der bereits in früheren Runden derselben Sitzung gesehen wurde.                                            |

**CCR Retrie-Protocol-Anweisung (#8033):** Wenn CCR zum ersten Mal ≥ 1 Block in einer Anfrage ersetzt, stellt die Engine eine einzelne, idempotente `system` -Nachricht voran (vorangestellt mit dem `[CCR protocol]` Sentinel), die dem Aufrufer die Markierung → Tool Contract“ beibringt: Was eine `[CCR retrieve hash=<24hex> chars=N]` Markierung bedeutet, dass der Hash wörtlich kopiert werden muss (alle 24 Hex-Zeichen, — falsch kopierte Hashes sind die wahrscheinliche Ursache für „Block nicht gefunden“-Fehler) und dass eine `[dedup:ref sha=...]` -Markierung „Schau zurück“ bedeutet Verlauf“, nicht „Werkzeug aufrufen“. Die Note wird eingespritzt** Nur wenn der vom Anrufer angekündigte `tools[]` beweist, dass er `omniroute_ccr_retrieve` tatsächlich erreichen kann** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — Ein einfacher OpenAI-kompatibler Aufrufer ohne dieses Tool erhält niemals eine Anweisung, etwas aufzurufen, das er nicht erreichen kann. Idempotenz wird erzwungen, indem der Nachrichtenverlauf vor dem Injizieren nach dem Sentinel durchsucht wird, sodass Multi-Turn-Anfragen (die frühere Nachrichten wiedergeben) die Notiz nicht einmal pro Runde stapeln.

## Höhlenmensch

Der Caveman-Modus konzentriert sich auf die semantische Verdichtung normaler Prosa:

- bewahrt Codeblöcke, URLs, JSON, Pfade und strukturierte Daten
- Entfernt Füllwörter, Absicherungen, wiederholten Kontext und ausführliche konnektive Formulierungen
- unterstützt sprachbasierte Dateiregelpakete in `open-sse/services/compression/rules/`
- bleibt über die alten Modi `standard`, `aggressive` und `ultra` verfügbar

Die Oberfläche des Armaturenbretts ist `Dashboard -> Context & Cache -> Caveman`.

Caveman Upstream meldet `~75%` weniger Ausgabetoken, `65%` durchschnittliche Ausgabeeinsparungen in Benchmarks mit einem `22-87%` Bereich und ein `~46%` -Eingabekomprimierungstool. OmniRoute verwendet die eingangsseitige Zahl von Caveman, wenn es gestapelte prompt/context Einsparungen dokumentiert; Der Caveman-Ausgabemodus bleibt eine separate Antwortverhaltensfunktion.

## RTK

RTK Modus konzentriert sich auf die Befehls- und Toolausgabe:

- Erkennt Ausgabeklassen wie `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go -Tests, TypeScript/Vite/Webpack Builds, ESLint, npm audit/installs, Docker Protokolle, Shell `find`/`grep`, Stack-Traces und generische Protokolle
- wendet 49 JSON -Filter von `open-sse/services/compression/engines/rtk/filters/` an
- unterstützt die deklarative Pipeline im RTK-Stil: ANSI -Stripping, Ersetzen, Match-Output-Kurzschluss, strip/keep Zeilen, zeilenweise Kürzung, head/tail/max-line -Kürzung und On-Empty-Fallback
- unterstützt vertrauenswürdige Projektfilter in `.rtk/filters.json` und globale Filter in `DATA_DIR/rtk/filters.json`
- Entfernt ANSI -Sequenzen, Fortschrittsgeräusche, wiederholte Zeilen und nicht hilfreiche Boilerplates
- Behält umsetzbare Fehler, Warnungen, Zusammenfassungen, geänderte Dateien und den Endkontext bei
- kann optional die geschwärzte Rohausgabe für recovery/debugging über authentifizierte Verwaltungsrouten beibehalten

Die Oberfläche des Armaturenbretts ist `Dashboard -> Context & Cache -> RTK`.

Betriebsdetails für benutzerdefinierte Filter, Vertrauen, Überprüfung und Wiederherstellung der Rohausgabe live in [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK Upstream meldet `60-90%` Einsparungen für die Befehlsausgabekomprimierung. Das README Beispiel zeigt eine 30-minütige Claude -Code-Sitzung, die von `~118,000` Tokens zu `~23,900` oder `79.7%` Speicherung führt.

## LLMLingua-2 (Semantische Beschneidung)

LLMLingua-2 Modus wird ausgeführt** Semantisches Token-Beschneiden** über Prosa unter Verwendung eines kleinen ONNX Token-Klassifikators, der die regelbasierten Caveman- und RTK Engines ergänzt:

- komprimiert Prosa nur in Nicht-Systemnachrichten; Umzäunte Codeblöcke und andere erhaltene Konstrukte werden niemals geändert
- führt das `@atjsh/llmlingua-2` Backend (ONNX über `@huggingface/transformers`) in einem Arbeitsthread aus, sodass die Modellinferenz niemals die Anforderungsereignisschleife blockiert
- Ist** stapelbar** (`stackPriority` 35): In einer gestapelten Pipeline wird es nach den Struktur-Engines (CCR, session-dedup, headroom, Caveman) aber vor `ultra` ausgeführt, da die semantische Bereinigung bei bereits strukturell komprimiertem Text — B. `rtk -> caveman -> llmlingua` am effektivsten ist
- **fail-opens wird bei jedem Fehler geöffnet** (fehlende optionale Deps, Worker-Spawn, Modellladung, Inferenz oder Zeitüberschreitung) → Der Originaltext wird unverändert zurückgegeben, niemals ein Fehler

Motorstandort: `open-sse/services/compression/engines/llmlingua/`. Die Dashboard-Oberfläche ist `Dashboard -> Context & Cache -> LLMLingua`.

### Modelle

Das Standardmodell ist**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, schnell). Eine höhere Genauigkeit** BERT-Basis** Das Modell (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) ist über das Engine-Konfigurationsfeld `model` verfügbar. `@huggingface/transformers` lädt das ausgewählte Modell beim ersten Aufruf träge vom HuggingFace Hub in `${DATA_DIR}/models/llmlingua` herunter (`modelStore.ts`); Eine `modelPath` -Konfigurationsüberschreibung verweist stattdessen auf eine lokale Kopie (Offline-/Air-Gapped-Installationen).

### Optionale Abhängigkeiten und On-Demand-Installation

Der beschneidbare LLMLingua -Laufzeit-Peer-Stack ist** optional** . Zwei Pakete werden in `package.json` als `optionalDependencies` deklariert und behalten** extern** durch den Produktions-Build (`scripts/build/prepublish.ts` bündelt sie nicht):

| Paket                | Version (Pin) | Notizen                                               |
| -------------------- | ------------- | ----------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`       | Eintrittspaket; erklärt die anderen zu Gleichaltrigen |
| `js-tiktoken`        | `^1.0.20`     | Tokenizer                                             |

`@huggingface/transformers` ist an `^4.2.0` angeheftet (gemeinsam mit dem lokalen Einbettungspfad geteilt und auch im eigenständigen Bundle nachverfolgt); `@atjsh/llmlingua-2@2.0.5` verbindet es mit `"^3.5.2 || ^4.0.0"`, daher werden sowohl Transformers.js v3 als auch v4 unterstützt. Seit 2.0.4 benötigt `@atjsh/llmlingua-2` kein `@tensorflow/tfjs` mehr, wodurch der größte einzelne Mitwirkende (TensorFlow.js) aus dem SLM Stapel entfernt wurde. Nur die beiden oben genannten Pakete sind beschneidbare SLM Peers. Ein Standard `npm install` (dev) installiert den optionalen Stack automatisch, sofern optionale Abhängigkeiten nicht weggelassen werden.

**Warum auf Abruf:** Das von npm veröffentlichte Paket, das eigenständige Bundle und das Docker Image werden ausgeliefert** ohne** Diese Deps, um schlank zu bleiben. Wenn sie fehlen, schlägt das Abhängigkeitsgatter des Workers (eine `@atjsh/llmlingua-2` Auflösungsprüfung in `worker.ts`) fehl und die Engine** fail-öffnet sich lautlos** — LLMLingua auswählt, wird zu einem No-Op (Text wird unverändert zurückgegeben, kein Fehler protokolliert). Um es in einer bereinigten Umgebung zu aktivieren, installieren Sie den optionalen Stack:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

Die `@tensorflow/tfjs` Entfernung (2.0.4 +) eliminiert den zuvor dominanten ~ 800 MB Mitwirkenden ZQE — Der verbleibende Platzbedarf besteht aus den Laufzeiten von transformers.js + OnnxRuntime-Node sowie dem TinyBERT Modell (~ 57 MB), das bei der ersten Verwendung heruntergeladen wurde (nicht über NPM).

Pro Umgebung:

- **Dev / `npm install`** — wird automatisch installiert, sofern Sie nicht `--omit=optional` (oder `--no-optional`) übergeben haben. Es sind keine Maßnahmen erforderlich.
- **Globales npm (`npm i -g omniroute`) / eigenständig** — Führen Sie den Installationsbefehl oben im installierten Paketverzeichnis aus oder installieren Sie ihn erneut, ohne optionale Deps wegzulassen.
- **Docker** — fügt den Installationsbefehl in einer abgeleiteten Image-Ebene hinzu; Das veröffentlichte Bild ist von Natur aus schlank.
- **VPS (PM2)** Installieren Sie — im `node_modules` der App und starten Sie dann den Prozess neu, damit der Worker das Gate erneut prüft.
- **Raw Next Standalone (`npm run build` → `.build/next/standalone/server.js`)** — Der eigenständige Trace versendet NEITHER weder den Worker noch die optionalen Deps, sodass die Engine stillschweigend bei Ausfall geöffnet wird. `scripts/build/colocate-standalone.mjs` wendet beide erneut an (Worker esbuild + optional-dep-Schließung in den eigenständigen Baum); Es wird nach jedem Build automatisch über den `postbuild` npm-Hook ausgeführt. Idempotent, ausfallsicher, wenn Deps fehlen.

**Überprüfen Sie, ob es aktiv ist:** Wenn LLMLingua ausgewählt ist, schrumpft Real Prosa tatsächlich (die Engine stoppt das Fail-Opening), und die erste Anfrage löst den Modell-Download in `${DATA_DIR}/models/llmlingua` aus. Das Gate testet absichtlich nur `@atjsh/llmlingua-2` — die anderen Peers sind nur ESM und `require.resolve` wirft auf sie, selbst wenn — vorhanden ist, sodass der Worker immer noch Fail-Opens durchführt, wenn zum `import()` Zeitpunkt wirklich ein Peer fehlt.

## Gestapelte Pipelines

Im gestapelten Modus werden die Pipelineschritte der Reihe nach ausgeführt. Der Standardwert ist:

```txt
rtk -> caveman
```

Verwenden Sie dies für Coding-Agent-Sitzungen, bei denen eine Eingabeaufforderung die Befehlsausgabe mit der Prosa eines Menschen oder eines Assistenten kombiniert. RTK reduziert zunächst verrauschte Tool-Protokolle, dann komprimiert Caveman die verbleibende natürliche Sprache.

Pipeline-Schritte werden mit `stackedPipeline` in den Komprimierungseinstellungen oder über Komprimierungskombinationen konfiguriert.

Wenn beide Motoren die gleiche zulässige Nutzlast reduzieren, ergeben sich folgende Einsparungen:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP Barrierefreiheitsbaumfilter

Der intelligente Filter MCP accessibility-tree“ ist eine Komprimierungsschicht nach der Ausführung, die auf MCP ausgeführt wird** Werkzeugergebnisse** , nicht auf Eingabeaufforderungen oder Kontext. Es zielt auf die ausführlichen Accessibility-Tree- und Browser-Snapshot-Payloads ab, die von Tools wie Playwright, Computer-Use- und Browser-Automation- MCP Servern zurückgegeben werden.

### Was es bewirkt

1. **Rauschunterdrückung** — entfernt leere generic/text Einträge (`- generic:`, `- text: ""`)
2. **Zusammenbruch der Geschwister** Wenn — ≥ `collapseThreshold` (Standard 30) aufeinanderfolgende Zeilen strukturelle Wiederholungen sind, werden sie in die ersten `collapseKeepHead` (Standard 10) Zeilen reduziert + eine Zählzusammenfassung + die letzten `collapseKeepTail` (Standard 5) Zeilen
3. **Referenzkonservierung** Die von Playwright/computer-use benötigten — `[ref=eXX]` -Anker werden niemals berührt
4. **Harte Kürzung** — wenn der Text nach dem Reduzieren immer noch `maxTextChars` (Standard 50.000) überschreitet, wird er mit einem Navigationshinweis abgeschnitten, damit der Agent weiterarbeiten kann

### Standort des Motors

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Konfiguration

Wird von `compression.mcpAccessibility` in den globalen Einstellungen gesteuert (Migration 056). Standardkonfiguration:

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

Der Filter wird nur auf Tool-Ergebnisnutzlasten angewendet, deren `type` `"text"` ist und deren Länge `minLengthToProcess` überschreitet. Es wirkt sich nicht auf die Prompt-Komprimierung oder Anforderungsnutzlasten aus.

### Erwartete Einsparungen

60–80 % der Ergebnisse des Browser-Snapshot-Tools, abhängig von der Komplexität der Seite. Der Kollaps-Algorithmus hat eine Zeilenanzahl von O(n) und fügt eine vernachlässigbare Latenz hinzu.

### Dieser Filter im Vergleich zu den oben genannten Kompressionsmotoren

| Aspekt    | Höhlenmensch / RTK / Gestapelt              | MCP Barrierefreiheitsfilter            |
| --------- | ------------------------------------------- | -------------------------------------- |
| Ziel      | Bitten Sie um Eingabeaufforderungen/Kontext | Ergebnisse MCP -Tools                  |
| Auslösen  | Einstellung des Komprimierungsmodus         | `compression.mcpAccessibility.enabled` |
| Umfang    | Alle SSE -Nachrichten                       | Nur Tool-Ergebnisse                    |
| Ref-Anker | N/A                                         | Bedingungslos erhalten                 |

---

## Komprimierungskombinationen

Komprimierungskombinationen sind benannte Komprimierungsprofile, die Routing-Kombinationen zugewiesen werden können:

- `compression_combos`: Speichert Modus, Pipeline, RTK -Konfiguration, Sprachkonfiguration und Standardmarkierung
- `compression_combo_assignments`: Ordnet eine Komprimierungskombination einer Routing-Kombination zu
- Die Laufzeitintegration löst eine zugewiesene Komprimierungskombination auf, bevor die generische Kombination überschreibt
- Zu den Analysen gehören `compression_combo_id` und `engine`

Armaturenbrettoberfläche: `Dashboard -> Context & Cache -> Compression Combos`.

## Voraussetzungen / Bedienerhandbuch (CCR & session-dedup)

CCR (`ccr`) und `session-dedup` ersetzen oder streichen Text und belassen a** Marker** hinter. Dieser Abschnitt ist die Bedienerreferenz für die Verkabelung eines Clients, das Lesen der beiden Markierungen und das Abrufen oder Diagnostizieren des eliminierten Inhalts. Die Mechanik jedes Motors wird oben behandelt; Dies ist die Ebene „Wie führe ich es aus?“.

### Transporte und Endpunkte

Der MCP -Server, der die CCR Tools verfügbar macht, kann auf drei Arten erreicht werden. Der Standard-Basis- URL ist `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transport                            | URL / Befehl                            | Notizen                                                                                                                                           |
| ------------------------------------ | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Streambares HTTP (Client, empfohlen) | `http://localhost:20128/api/mcp/stream` | Der Endpunkt, mit dem aktuelle MCP Clients kommunizieren.                                                                                         |
| Legacy- SSE -Singleton               | `http://localhost:20128/api/mcp/sse`    | Älterer Singleton-Transport. Es** schließt** streambare Sitzungen; Verwenden Sie `streamable-http` Clients gegen `/api/mcp/stream`, nicht diesen. |
| stdio                                | `omniroute --mcp`                       | Für IDE MCP -Konfiguration, die den Prozess erzeugt. Es gibt kein `--dev` -Flag; `omniroute --mcp` ist der stdio-Einstiegspunkt.                  |

### Speicherebenen (was einen Neustart überlebt)

CCR ist ein** zweistufig** speichern, nicht nur im Speicher:

- **Heiße In-Memory-Stufe** — pro Block, Obergrenze 2 MiB, pro Prinzipal 16 MiB, global 64 MiB. Einträge werden standardmäßig im 24-Stunden TTL (maximal 7 Tage) angezeigt. Der vollständige MCP Abruf aus dem Speicher ist auf 256 KiB begrenzt. Alles, was größer ist, ist weiterhin über die Ranged-/Grep-Modi erreichbar.
- **Strapazierfähige SQLite Stufe** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, standardmäßig aktiviert) — unterstützt die In-Memory-Ebene, sodass ein Block LRU Räumung, einen Neustart oder einen Abruf auf einer anderen Instanz übersteht. Die Zeile behält den TTL des Blocks bei, sodass ein Block nach seinem TTL aus beiden Ebenen entfernt wird.

Drei Wachen behalten die dauerhafte Stufe bei — ein Block bleibt nur im Gedächtnis, wenn:

1. die Sperre ist vorbei** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. die Laufzeit ist eine Cloud-Laufzeit (keine lokale Festplatte);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

„Der Block ist verschwunden“ ist also keine pauschale Neustartgeschichte: Ein sub-512 KB Block auf einer lokalen Nicht-Cloud-Laufzeit überlebt einen Neustart über die dauerhafte Ebene, bis sein TTL aufgebraucht ist. Siehe [Umgebungsreferenz](../reference/ENVIRONMENT.md) für die Variable.

### Die beiden Markierungen

| Marker                                | Bedeutung                                                                                                                                                                 | Was das Modell tun soll                                                                                                                                                                                                                                             |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Ein großer Block wurde inhaltsadressiert gespeichert.                                                                                                                     | Rufen Sie `omniroute_ccr_retrieve` mit dem an** 24-Hex-Hash wörtlich kopiert** um den Originaltext zurückzubekommen.                                                                                                                                                |
| `[dedup:ref sha=…]`                   | `session-dedup` hat Text gelöscht, der bereits in einer früheren Runde derselben Sitzung gesendet wurde. Dies ist ein** bewusster Rückblick** , kein Verlust oder Fehler. | Tun** nicht** Rufen Sie ein beliebiges Tool auf und tun Sie es** nicht** Versuchen Sie es zu „rekonstruieren“. Das erste Vorkommen des Textes ist die kanonische Kopie; Die aktuelle Runde wird nie neu geschrieben, sie wird in einer späteren Runde dedupliziert. |

Der `[dedup:ref]` -Rückblick ist eine bewusste Protokollentscheidung, — es gibt keine Rekonstruktion vor dem Senden. Behandeln Sie es so, als ob „dieser exakte Text bereits früher in dieser Sitzung auf dem Draht war.“

### Client-Voraussetzungen

- **Schlüssel (stdio):** Ein stdio-Aufrufer trägt keine Identität pro Anfrage und authentifiziert sich daher mit `OMNIROUTE_API_KEY` (festgelegt im `env` des MCP Servers). Ohne sie ist der Anrufer anonym und Tools, die einen Prinzipal erfordern, können beeinträchtigt werden.
- **`tools[]` ist die Injektionsvoraussetzung.** Die CCR Retrie-Protocol-Anweisung (#8033) wird eingefügt** nur** wenn der beworbene `tools[]` der Anfrage beweist, dass der Client `omniroute_ccr_retrieve` tatsächlich erreichen kann. Bei der Übereinstimmung handelt es sich um eine Übereinstimmung mit nachgestellten Segmenten, die durch ein Trennzeichen (`__`, `.`, `/`, `:`) begrenzt ist. — ist niemals eine bloße Teilzeichenfolge — sodass ein Namespace-Name wie `mcp__gateway__omniroute_ccr_retrieve` weiterhin zählt. Ein fehlender oder nicht übereinstimmender `tools[]` bedeutet, dass die Anweisung konstruktionsbedingt _nicht_ eingefügt wurde.
- **`codemode:false` (OpenCode Clients).** OpenCode verwendet standardmäßig den Codemodus, der dem Modell und nur seine nativen Tools ankündigt** nicht** Setzen Sie MCP Tools auf die native `tools[]` Liste. Legen Sie `codemode: false` für den MCP -Servereintrag fest, damit die `omniroute_ccr_*` Tools angekündigt werden. Das ist ein** Kunde** Einstellung, keine OmniRoute Einstellung. Die CCR Anweisung wird noch nicht eingefügt: OpenCode nennt ein Tool `<server>_<tool>`, sodass ein Server namens `omniroute` `omniroute_omniroute_ccr_retrieve` verfügbar macht und `_` nicht zu den übereinstimmenden Trennzeichen gehört.
- **Schulleiter.** Speicherung und Abruf erfolgen isoliert pro authentifiziertem Prinzipal (pro API -Schlüssel). Ein Schlüssel sieht nur seine eigenen Blöcke.

### Bereiche pro Werkzeug

Die Bereichserzwingung ist für HTTP/SSE -Aufrufer mit engem Bereich immer aktiviert. Die `omniroute_` CCR -Tools erfordern:

| Werkzeug                 | Umfang              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Ein fehlender Bereich gibt eine zurück**MCP Tool-Fehlerergebnis** (`isError: true`, kein HTTP 403 — `403 LOCAL_ONLY` ist die separate Loopback-Route-Guard-Authentifizierung): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Ein minimaler Remote-Schlüssel kann `mcp:connect` enthalten (autorisiert die nur lokale `/api/mcp/` -Ausgliederung) sowie den spezifischen read/write Bereich, den er benötigt.

### Kundenmatrix

| Kunde             | Transport                                 | Zu verwendende Konfiguration                                                                                                                                                                                                                               | `tools[]` beworben? (→ CCR Anweisung injiziert)                                                                                                                                                              |
| ----------------- | ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Claude -Code      | streambar-http                            | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                          | Ja — MCP-fähig; gespritzt.                                                                                                                                                                                   |
| Cursor / Cline    | `stdio`** oder** `streamable-http`        | stdio: `omniroute --mcp` mit `OMNIROUTE_API_KEY` in `env`; oder ein entfernter MCP Eintrag, der auf `http://localhost:20128/api/mcp/stream` zeigt (siehe [Setup-Anleitung → MCP Client-Konfiguration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Ja, — bewirbt die `omniroute_ccr_*` Tools.                                                                                                                                                                   |
| OpenCode          | streambar-http                            | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, plus `codemode: false`                                                                                                                                                           | Nur mit `codemode: false` beworbene Tools; Die Anweisung wird immer noch nicht eingefügt, da `omniroute_omniroute_ccr_retrieve` nicht übereinstimmt (siehe [Clientvoraussetzungen](#client-prerequisites) ). |
| OpenAI-kompatibel | OpenAI-kompatibles HTTP (Chat-Abschlüsse) | Standard-Chat-Completions-Client gegen den OpenAI-kompatiblen Endpunkt                                                                                                                                                                                     | **Niemals** — Ein einfacher OpenAI-kompatibler Aufrufer wird niemals angewiesen, das Tool aufzurufen, und die Anweisung wird nicht eingefügt.                                                                |

### Abrufgrenzen und Paginierung

Die Textergebnisse MCP Tools werden um `mcpAccessibility.maxTextChars` herum abgeschnitten (Standard: `50000`). Der `full` Abruf eines Blocks ist auf 256 KiB — begrenzt** Es gibt keinen unbegrenzten vollständigen Abruf** . Wenn das `chars=N` eines Blocks groß ist, blättern Sie es, anstatt das Ganze zu ziehen:

- Faustregel:**`chars > 40000` → verwende einen `mode`** , nie ganz voll.
- `mode:"grep"` — regex `pattern` zeilenweise abgeglichen, bis zu 1.000 passende Zeilen (`unique: true` löscht Wiederholungen), am günstigsten für „Finde die eine Zeile, die ich brauche.“
- `mode:"lines"` — ein 1-indizierter Zeilenbereich; benötigt sowohl `start` als auch `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` Zeilen.
- `mode:"stats"` — Zeilen-, Zeichen- und Byteanzahl ohne den Textkörper.

Verwenden Sie `mode:"lines"` mit `start`/`end`, um einen langen Block in Seiten zu durchlaufen, anstatt das Ganze auf einmal anzufordern.

### Werkzeugbenennung

Das Abruftool heißt derzeit `omniroute_ccr_retrieve` (das Präfix `omniroute_` ist eine veraltete Problemumgehung für serverübergreifende Namenskollisionen). Ein saubererer Toolname mit begrenztem Suffix und ein Fix für MCP JSON Ergebnisse, die in der Mitte der Zeichenfolge abgeschnitten sind, werden als Upstream-Follow-ups verfolgt; Diese Seite dokumentiert nur das aktuelle, ausgelieferte Verhalten.

### Sitzungslebenszyklus

Streamable-HTTP-Sitzungen ruhen im Leerlauf und der Server erntet sie; Das Leerlauffenster ist die `MCP_SESSION_IDLE_MS` Konstante (durch den Namen referenziert, kein fest codierter Wert, sodass diese Seite nicht driftet, wenn sie sich ändert). Das Symptom einer Idle-Reaped-Sitzung ist ein HTTP 404 mit `Unknown Mcp-Session-Id` — Die Abhilfe besteht darin, die Sitzung erneut zu verbinden oder neu zu starten.** nicht** um einen Schlüssel zu drehen, einen Bereich zu ändern oder ein Werkzeug umzubenennen.

## API Oberfläche

| Route                                  | Zweck                                                                                  |
| -------------------------------------- | -------------------------------------------------------------------------------------- |
| `/api/settings/compression`            | Globale Komprimierungseinstellungen (einschließlich `mcpAccessibility` -Konfiguration) |
| `/api/compression/preview`             | Vorschau aller Komprimierungsmodi                                                      |
| `/api/compression/language-packs`      | Liste der verfügbaren Caveman-Sprachpakete auf                                         |
| `/api/context/caveman/config`          | Alias für Caveman-Einstellungen                                                        |
| `/api/context/rtk/config`              | RTK Standards und -Einstellungen                                                       |
| `/api/context/rtk/filters`             | RTK -Filterkatalog                                                                     |
| `/api/context/rtk/test`                | RTK preview/test -Endpunkt                                                             |
| `/api/context/rtk/raw-output/[id]`     | Authentifizierte Wiederherstellung der geschwärzten Rohausgabe                         |
| `/api/context/combos`                  | Komprimierungskombination CRUD                                                         |
| `/api/context/combos/[id]/assignments` | Routing-Combo-Zuweisung CRUD                                                           |
| `/api/context/analytics`               | Alias für die Komprimierungsanalyse                                                    |

Verwaltungsrouten erfordern eine Verwaltungsauthentifizierung oder API-Schlüsselrichtlinienprüfungen.

## MCP Tools

Durch die Komprimierung werden fünf MCP Tools verfügbar gemacht:

| Werkzeug                            | Umfang              | Zweck                                      |
| ----------------------------------- | ------------------- | ------------------------------------------ |
| `omniroute_compression_status`      | `read:compression`  | Einstellungen, Analysen, Cache-Statistiken |
| `omniroute_compression_configure`   | `write:compression` | Globale Einstellungen aktualisieren        |
| `omniroute_set_compression_engine`  | `write:compression` | Modus und optionale Pipeline festlegen     |
| `omniroute_list_compression_combos` | `read:compression`  | Komprimierungskombinationen auflisten      |
| `omniroute_compression_combo_stats` | `read:compression`  | Lesen Sie combo/engine -Analysen           |

## Geltungsbereich und Ausschlüsse

**Einbettungen werden niemals komprimiert.** `open-sse/handlers/embeddings.ts` ruft niemals eine Komprimierungs-Engine — auf, die request/response -Körper werden unverändert direkt an den Executor übergeben. Dies ist heutzutage strukturell (Einbettungen und Chat-Vervollständigungen sind disjunkte Handler), keine Laufzeitprüfung, aber es bedeutet, dass das Problem der Vektorverzerrung in #8034 keine Expositionsoberfläche im Einbettungspfad hat.

**Per-model/endpoint Ausschlussfilter (#8034).** Für Chat-Vervollständigungen kann ein Operator Modell-IDs/ `provider/model` -Ziele benennen, die niemals komprimiert werden dürfen. ZQD — eine Leitplanke, die nützlich ist, wenn die Komprimierung später jemals näher an einen an Einbettungen angrenzenden Pfad angeschlossen wird, und im Allgemeinen nützlich für jedes Modell, dessen genaue Byte-für-Byte-Eingabe wichtig ist (deterministische Auswertungen, Cache-sensitive Präfixe usw.).

- Einstellungsfeld: `exclusions?: string[]` in der globalen Komprimierungskonfiguration (`GET`/`PUT /api/settings/compression`), beibehalten über den vorhandenen `key_value` -Komprimierungsnamespace (`src/lib/db/compression.ts`), — keine neue Tabelle.
- Registerkarte „Dashboard“:** Dashboard → -Komprimierung → -Ausschlüsse** (`/dashboard/compression/exclusions`).
- Mustersyntax: `*` ist der einzige Platzhalter. Jedes andere Regex-Metazeichen in einem Muster wird vor dem Abgleich maskiert, sodass `gpt-5.6` nur mit der Literalzeichenfolge übereinstimmt, niemals `gpt-5x6` (ReDoS-sicher, begrenzt, keine verschachtelten Quantoren). Muster stimmen ohne Berücksichtigung der Groß- und Kleinschreibung sowohl mit der nackten Modell-ID als auch mit der `provider/model` -Kombination — `gpt-5-6`, `openai/gpt-5-6` und `openai/*` überein, und `*` allein schließt jedes Modell aus.
- Übereinstimmung: `isCompressionExcluded()` / `normalizeCompressionExclusions()` in `open-sse/services/compression/exclusions.ts`. `chatCore.ts` überprüft das ausgeschlossene Ziel direkt nach der Auflösung der Komprimierungseinstellungen.** bevor irgendein Motor läuft** und behandelt eine Übereinstimmung genauso wie eine global deaktivierte Komprimierung — der Anforderungstext nachweislich byteidentisch ist. Der Sprung wird zur Analysetransparenz über `writeCompressionSkip(..., "excluded")` aufgezeichnet.
- Standard (empty/absent Liste): identisch mit dem Verhalten vor #8034 — nichts ist ausgeschlossen.

## Bekannte Einschränkungen

- **LLMLingua-2 (SLM) erfordert optionale Deps am selben Ort.** Der Worker wird nur in einem Produktions-Build ausgeführt, wenn sich `@atjsh/llmlingua-2` + Peers in `dist/node_modules` befinden (siehe `scripts/build/colocateOptionals.mjs`, #4286). Ohne sie wird die Engine fehlgeschlagen (gibt den Originaltext zurück). Die Worker-Auflösung hängt nicht mehr von `import.meta.url` ab (es stirbt im Standalone-Bundle) — verankert es auf der Laufzeit cwd / `argv[1]`.
- **Die Caveman-Sprachpakete `de` / `fr` / `ja` sind teilweise.** Sie versenden `context` + `filler` + `structural` -Regeln, aber keine `dedup` / `ultra` Pakete, daher ist `ultra` Intensität für diese Sprachen nicht stärker als `full` (sie verwenden nur ihre eigenen Regeln — es gibt keinen stillen Rückgriff auf die englischen `dedup`/`ultra` -Regeln, die fremden Text entstellen würden). `en` / `es` / `id` / `pt-BR` sind abgeschlossen. Beiträge von `dedup.json` + `ultra.json` für die Teilpakete sind willkommen.
- **Die gestapelte Telemetrie listet nur Engines auf, die komprimiert wurden.** Ein gestapelter Pipeline-Schritt, dessen Engine lief, aber 0 % Einsparungen erzeugte, gibt `stats:null` zurück und erscheint daher nicht in `engineBreakdown` — was von einem übersprungenen Schritt nicht zu unterscheiden ist. Die Unterscheidung zwischen „gelaufen, 0 %“ und „übersprungen“ würde eine Änderung des Aufschlüsselungsmodells erfordern und wird zurückgestellt.

## Validierung

Die fokussierten Tore für diesen Bereich sind:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
