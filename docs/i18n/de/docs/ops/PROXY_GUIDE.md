# 🌐 OmniRoute Proxy Guide (Deutsch)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Umgehen Sie geografische Sperren, schützen Sie Ihre Identität und leiten Sie den AI Verkehr ohne Konfigurationsaufwand über jeden Proxy- — weiter.**

OmniRoute umfasst ein Proxy-Verwaltungssystem mit vollem Funktionsumfang, mit dem Sie den Datenverkehr des Upstream AI Anbieters über HTTP, HTTPS oder SOCKS5 Proxys weiterleiten können. Egal, ob Sie sich in einer gesperrten Region befinden, IP Rotation benötigen oder Stealth-Fingerprinting — wünschen, dieser Leitfaden deckt alles ab.

---

## Inhaltsverzeichnis

- [Warum Proxys verwenden?](#why-use-proxies)
- [Architekturübersicht](#architecture-overview)
- [4-Ebenen-Proxy-System](#4-level-proxy-system)
- [Proxy-Registrierung (CRUD)](#proxy-registry-crud)
- [1proxy Kostenloser Marktplatz](#1proxy-free-proxy-marketplace)
- [Proxy-Rotation](#proxy-rotation)
- [Anti-Erkennung und Stealth](#anti-detection--stealth)
- [Upstream-Proxy-Modi](#upstream-proxy-modes)
- [Armaturenbrett UI](#dashboard-ui)
- [API Referenz](#api-reference)
- [Umgebungsvariablen](#environment-variables)
- [Fehlerbehebung](#troubleshooting)

---

## Warum Proxys verwenden?

Viele AI -Anbieter beschränken den Zugriff nach geografischer Region. Entwickler in** Russland, China, Iran, Kuba, Türkei** , und in anderen Ländern treten Fehler auf wie:

```
unsupported_country_region_territory
```

Auch außerhalb gesperrter Regionen sind Proxys nützlich für:

| Anwendungsfall                   | Beschreibung                                                               |
| -------------------------------- | -------------------------------------------------------------------------- |
| **Geografische Umgehungsstraße** | Greifen Sie aus gesperrten Ländern OpenAI, Anthropic, Codex und Copilot zu |
| **IP -Rotation**                 | Verteilen Sie Anfragen auf mehrere IPs, um Ratenbegrenzungen zu vermeiden  |
| **Privatsphäre**                 | Verstecken Sie Ihre echte IP vor Upstream-Anbietern                        |
| **Einhaltung**                   | Leiten Sie den Datenverkehr durch bestimmte Gerichtsbarkeiten              |
| **Testen**                       | Simulieren Sie Anfragen aus verschiedenen Regionen                         |

---

## Architekturübersicht

```
┌───────────────────────────────────────────────────────────────┐
│                       OmniRoute Server                        │
│                                                               │
│  ┌─────────────┐    ┌──────────────┐    ┌──────────────────┐  │
│  │ Proxy       │    │ Proxy        │    │ Proxy            │  │
│  │ Registry    │───▶│ Dispatcher   │───▶│ Fetch (undici)   │  │
│  │ (SQLite)    │    │ (cached)     │    │                  │  │
│  └─────────────┘    └──────────────┘    └────────┬─────────┘  │
│         ▲                                        │            │
│         │                                        ▼            │
│  ┌──────┴──────┐                        ┌──────────────────┐  │
│  │ 1proxy Sync │                        │ Upstream         │  │
│  │ (free pool) │                        │ Provider API     │  │
│  └─────────────┘                        └──────────────────┘  │
└───────────────────────────────────────────────────────────────┘
```

### Schlüsselkomponenten

| Komponente              | Datei                                        | Rolle                                                     |
| ----------------------- | -------------------------------------------- | --------------------------------------------------------- |
| **Proxy-Registrierung** | `src/lib/db/proxies.ts`                      | CRUD für Proxy-Einträge, + -Bereichszuweisungen           |
| **Proxy-Dispatcher**    | `open-sse/utils/proxyDispatcher.ts`          | Erstellt `undici` ProxyAgent/SOCKS Dispatcher mit Caching |
| **Proxy-Abruf**         | `open-sse/utils/proxyFetch.ts`               | Umschließt `fetch()` mit Proxy-Dispatcher-Injection       |
| **Einstellungen Route** | `src/app/api/settings/proxy/route.ts`        | Legacy-Proxy-Konfiguration API (GET/PUT/DELETE)           |
| **Managementroute**     | `src/app/api/v1/management/proxies/route.ts` | Registrierung CRUD API (GET/POST/PATCH/DELETE)            |
| **1proxy DB**           | `src/lib/db/oneproxy.ts`                     | Kostenlose Proxy-Marktplatz-Persistenz                    |

---

## Standard-Proxy-Status für neue Konten

In** Einstellungen → Proxy → Globale Konfiguration** , verwenden** Aktivieren Sie den Proxy standardmäßig für neue Verbindungen** um den anfänglichen Proxy-Status neu hinzugefügter Anbieterkonten auszuwählen.

Die neue Einstellung steuert den anfänglichen Proxy-Status neu hinzugefügter Anbieterkonten. Es ändert weder bestehende Konten noch ersetzt es den globalen Proxy-Switch. Sein Anfangswert behält das vorherige Verhalten bei. Deaktivieren Sie es einmal, um zukünftige Konten mit standardmäßig deaktiviertem Proxy zu erstellen.

Die Präferenz wird als `defaultNewConnectionProxyEnabled` über die vorhandenen Einstellungen API gespeichert. Die Standardeinstellung ist `true`, wenn sie nie gespeichert wird. Das Speichern von `false` wird für nachfolgende neue Konten ohne Neustart wirksam. `POST /api/providers` akzeptiert einen optionalen strikten booleschen Wert `proxyEnabled`; Ein explizites `true` oder `false` hat Vorrang vor dem Erstellungsstandard. Wenn Sie ein doppeltes Konto oder OAuth Wiederverbindung weglassen, bleibt der gespeicherte Status dieses Kontos erhalten. Einzelne Konten können auch danach noch aktiviert oder deaktiviert werden.

Selektive Anbieterübertragungen verwenden die Standardeinstellungen der Zielinstallation für neue Konten und behalten die Zielrichtlinie bei, wenn vorhandene Konten ersetzt werden. Proxy-Schalter sind keine tragbaren Übertragungsfelder. Die vollständige Backup-Wiederherstellung und die historische JSON/SQL -Migration behalten ihre bestehende Wiederherstellungssemantik bei, einschließlich gespeicherter Kontowerte und Legacy-Schema-Standardeinstellungen. Durch eine vollständige Wiederherstellung der Einstellungen kann diese Einstellung ebenfalls wiederhergestellt werden.

Diese Einstellung weist keinen Proxy zu und stellt auch nicht fest, dass einer fehlerfrei ist oder verwendet wird. Das tatsächliche Routing hängt weiterhin vom globalen Proxy-Switch und der entsprechenden Proxy-Konfiguration ab. Synthetische Anbieter ohne dauerhaftes Konto, OAuth Verkehr vor der Kontoerstellung, environment/system Proxys und die Vernetzung externer Backends fallen nicht in den Geltungsbereich.

## 4-Ebenen-Proxy-System

OmniRoute unterstützt die Proxy-Konfiguration unter** vier unabhängige Bereiche** , gelöst in der Reihenfolge ihrer Priorität:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### So funktioniert die Auflösung

Wenn OmniRoute eine Anfrage an einen Upstream-Anbieter sendet, ruft es `resolveProxyForConnectionFromRegistry()` auf, das jede Ebene in der folgenden Reihenfolge überprüft:

1. **Kontoebene** — Ist dieser bestimmten Verbindung ID ein Proxy zugewiesen?
2. **Anbieterebene** — Ist diesem Anbieter ein Proxy zugeordnet (z. B. `openai`)?
3. **Globale Ebene** — Ist ein globaler Proxy konfiguriert?
4. **Kein Proxy** — Direkte Verbindung zum Anbieter.

Das erste Spiel gewinnt. Das bedeutet, dass Sie einen globalen Proxy als Fallback festlegen, ihn aber für bestimmte Anbieter oder Verbindungen außer Kraft setzen können.

### Was wird weitergeleitet?

| Verkehrstyp            | Proxy? | Notizen                                                    |
| ---------------------- | ------ | ---------------------------------------------------------- |
| Chat-Abschlüsse        | ✅     | Alle `/v1/chat/completions` Anfragen                       |
| Einbettungen           | ✅     | `/v1/embeddings`                                           |
| Bilderzeugung          | ✅     | `/v1/images/generations`                                   |
| Audio (TTS/STT)        | ✅     | `/v1/audio/*`                                              |
| OAuth Token-Austausch  | ✅     | Löst `unsupported_country_region_territory`                |
| Verbindungstests       | ✅     | Die Schaltfläche „Verbindung testen“ verwendet einen Proxy |
| Token-Aktualisierung   | ✅     | Hintergrund OAuth -Erneuerung                              |
| Modellsynchronisierung | ✅     | Auflistung und Entdeckung von Modellen                     |

---

## Proxy-Registrierung (CRUD)

Die Proxy-Registrierung ist eine SQLite Tabelle (`proxy_registry`), in der alle Ihre Proxys gespeichert sind. Jeder Proxy verfügt über:

| Feld       | Typ          | Beschreibung                                     |
| ---------- | ------------ | ------------------------------------------------ |
| `id`       | UUID         | Eindeutiger Bezeichner                           |
| `name`     | Zeichenfolge | Für Menschen lesbares Etikett                    |
| `type`     | Zeichenfolge | Protokoll: `http`, `https`, `socks5`             |
| `host`     | Zeichenfolge | Proxy-Hostname oder IP                           |
| `port`     | Ganze Zahl   | Portnummer                                       |
| `username` | Zeichenfolge | Auth-Benutzername (im Ruhezustand verschlüsselt) |
| `password` | Zeichenfolge | Auth-Passwort (im Ruhezustand verschlüsselt)     |
| `region`   | Zeichenfolge | Beschriftung der geografischen Region            |
| `notes`    | Zeichenfolge | Freitextnotizen                                  |
| `status`   | Zeichenfolge | `active` oder `inactive`                         |
| `source`   | Zeichenfolge | `manual` oder `oneproxy`                         |

### Erstellen eines Proxys

**Über das Dashboard:**

1. Gehe zu** Einstellungen → Proxy**
2. Klicken** Proxy hinzufügen**
3. Geben Sie Typ, Host, Port und optionale Authentifizierungsdaten ein
4. Speichern

**Über API:**

```bash
curl -X POST http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "name": "US Proxy",
    "type": "http",
    "host": "proxy.example.com",
    "port": 8080,
    "username": "user",
    "password": "pass",
    "region": "US"
  }'
```

### Aktualisieren eines Proxys

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Notiz:** Anmeldeinformationen bleiben erhalten, es sei denn, Sie senden ausdrücklich nicht leere Ersatzdaten. Durch das Senden leerer Zeichenfolgen für `username`/`password` bleiben die gespeicherten Werte erhalten.

### Einen Proxy löschen

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Proxys auflisten

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Zuweisen von Proxys zu Bereichen

```bash
# Assign to global scope
curl -X PUT http://localhost:20128/api/settings/proxy \
  -H "Content-Type: application/json" \
  -d '{"level": "global", "proxy": {"type":"http","host":"proxy.example.com","port":8080}}'

# Assign to a specific provider
curl -X PUT http://localhost:20128/api/settings/proxy \
  -H "Content-Type: application/json" \
  -d '{"level": "provider", "id": "openai", "proxy": {"type":"socks5","host":"socks.example.com","port":1080}}'

# Assign to a specific connection/key
curl -X PUT http://localhost:20128/api/settings/proxy \
  -H "Content-Type: application/json" \
  -d '{"level": "key", "id": "connection-uuid", "proxy": {"type":"http","host":"key-proxy.com","port":3128}}'
```

### Effektiven Proxy auflösen

Überprüfen Sie, welcher Proxy für eine bestimmte Verbindung verwendet wird:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Gibt den aufgelösten Proxy mit seiner Ebene (`account`, `provider` oder `global`) und Quelle zurück.

### Massenzuweisung

Weisen Sie einen Proxy mehreren Anbietern oder Verbindungen gleichzeitig zu:

```bash
curl -X POST http://localhost:20128/api/v1/management/proxies/bulk-assign \
  -H "Content-Type: application/json" \
  -d '{
    "scope": "provider",
    "scopeIds": ["openai", "anthropic", "codex"],
    "proxyId": "proxy-uuid"
  }'
```

### Import/Export

Proxys sind im enthalten**Backup/Restore** System. Wenn Sie Ihre OmniRoute Konfiguration exportieren:

1. Gehe zu** Dashboard → -Einstellungen → -Backup**
2. Klicken** Export** — -Proxy-Registrierung und Zuweisungen sind enthalten
3. Zum Wiederherstellen klicken Sie auf** Import** und laden Sie die Sicherungsdatei hoch

Die Proxy-Registrierung unterstützt ebenfalls** Upsert durch Host-+ Port** Wenn Sie — einen bereits vorhandenen Proxy importieren (gleicher Host und Port), wird dieser aktualisiert, anstatt ein Duplikat zu erstellen.

### Legacy-Migration

Wenn Sie Proxys in einer älteren Version (Vorregistrierung) konfiguriert haben, migriert OmniRoute diese automatisch:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Dies geschieht einmal beim ersten Start nach dem Upgrade. Verwenden Sie `migrateLegacyProxyConfigToRegistry({ force: true })`, um es erneut auszuführen.

---

## 1proxy Kostenloser Proxy-Marktplatz

> 🆕** Beitrag von [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Problem [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integriert sich mit dem** [1Proxy](https://1proxy-api.aitradepulse.com)** Community-Plattform, auf die man Zugriff gewähren kann** Hunderte von kostenlosen, validierten Proxys** aus aller Welt. Dies ist ideal für Benutzer, die keine eigene Proxy-Infrastruktur haben.

### Wie es funktioniert

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Synchronisieren** — OmniRoute ruft validierte Proxys vom 1proxy API
2. **Speichern** — -Proxys werden in derselben `proxy_registry` Tabelle wie `source = 'oneproxy'` gespeichert
3. **Filter** — Filtern Sie nach Protokoll, Land, Qualitätsfaktor
4. **Drehen** — Wählen Sie den besten Proxy mithilfe von Qualitäts-, Zufalls- oder Sequenzstrategien aus
5. **Automatischer Abbau** — Bei ausgefallenen Proxys wird der Qualitätsfaktor reduziert; unter dem Schwellenwert → als inaktiv markiert

### Proxys synchronisieren

**Über das Dashboard:**

1. Gehe zu** Einstellungen → 1proxy** Tab
2. Klicken** „Jetzt synchronisieren“**
3. Statistiken anzeigen: Proxys insgesamt, aktive Anzahl, durchschnittliche Qualität, Aufschlüsselung nach Ländern

**Über API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Proxys filtern

```bash
# Filter by protocol
curl "http://localhost:20128/api/settings/oneproxy?protocol=socks5"

# Filter by country
curl "http://localhost:20128/api/settings/oneproxy?countryCode=US"

# Filter by minimum quality score
curl "http://localhost:20128/api/settings/oneproxy?minQuality=80"

# Combine filters
curl "http://localhost:20128/api/settings/oneproxy?protocol=http&countryCode=DE&minQuality=70"
```

### Proxy-Qualitätswerte

Jeder 1proxy-Proxy wird mit Metadaten geliefert:

| Feld            | Beschreibung                                    |
| --------------- | ----------------------------------------------- |
| `qualityScore`  | 0-100 Bewertung von 1 Proxy-Validierung         |
| `latencyMs`     | Gemessene Netzwerklatenz                        |
| `anonymity`     | `transparent`, `anonymous` oder `elite`         |
| `googleAccess`  | Ob der Proxy auf Google -Dienste zugreifen kann |
| `countryCode`   | Zweibuchstabiger ISO -Ländercode                |
| `lastValidated` | Zeitstempel der letzten Validierung             |

Qualitätswerte werden dynamisch angepasst:

- **Fehlgeschlagene Anfragen** Reduzieren Sie die Punktzahl um 10 Punkte
- **Die Punktzahl sinkt auf ≤ 10** → Proxy ist `inactive` gekennzeichnet
- Inaktive Proxys sind von der Rotation ausgeschlossen

### Rotationsstrategien

```bash
# Rotate by quality (best proxy first) — default
curl -X POST http://localhost:20128/api/settings/oneproxy/rotate \
  -H "Content-Type: application/json" \
  -d '{"strategy": "quality"}'

# Random rotation
curl -X POST http://localhost:20128/api/settings/oneproxy/rotate \
  -d '{"strategy": "random"}'

# Sequential (least recently validated first)
curl -X POST http://localhost:20128/api/settings/oneproxy/rotate \
  -d '{"strategy": "sequential"}'
```

### Leistungsschalter

Der 1proxy sync verfügt über einen eingebauten Schutzschalter:

- Nach** 5 aufeinanderfolgende Synchronisierungsfehler** , weitere Synchronisierungsversuche werden blockiert
- Zurücksetzen mit: `resetOneproxyCircuitBreaker()` oder Neustart des Servers
- Der Synchronisierungsstatus ist unter `GET /api/settings/oneproxy?action=status` verfügbar

### 1proxy-Proxys löschen

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Anti-Erkennung und Stealth

OmniRoute leitet den Datenverkehr nicht nur über einen Proxy- — weiter, sondern lässt den Datenverkehr auch legitim aussehen:

### TLS Fingerabdruck-Spoofing

Verwendet `wreq-js`, um browserähnliche TLS Fingerabdrücke zu generieren und umgeht dabei Bot-Erkennungssysteme, die Nicht-Browser TLS Handshakes kennzeichnen.

### CLI Fingerabdruck-Matching

Der**CLI Fingerabdruck-Schalter** (`Settings → Security`) ordnet HTTP Header und JSON Body-Felder neu an, damit sie mit der genauen Signatur nativer CLI Binärdateien (Claude Code, Codex usw.) übereinstimmen. Das funktioniert** oben auf** der Proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Sie bekommen beides**IP Maskierung** Und** Authentizität verlangen** gleichzeitig.

### Proxy IP Preservation

Farbcodierte Abzeichen im Dashboard zeigen an, welche Proxy-Ebene aktiv ist:

| Abzeichen | Ebene      | Bedeutung                                                           |
| --------- | ---------- | ------------------------------------------------------------------- |
| 🟢        | Global     | Der gesamte Datenverkehr läuft über diesen Proxy                    |
| 🟡        | Anbieter   | Nur der Datenverkehr dieses Anbieters wird per Proxy weitergeleitet |
| 🔵        | Verbindung | Dieser spezielle key/account verwendet diesen Proxy                 |

Das Abzeichen zeigt zur Überprüfung auch den aufgelösten Proxy- IP an.

---

## Upstream-Proxy-Modi

Für Anbieter, die das CLIProxyAPI -Muster verwenden, unterstützt OmniRoute drei Upstream-Proxy-Modi:

| Modus         | Beschreibung                                                |
| ------------- | ----------------------------------------------------------- |
| `native`      | OmniRoute übernimmt das Proxy-Routing direkt (Standard)     |
| `cliproxyapi` | Delegiert an eine externe CLIProxyAPI Instanz               |
| `fallback`    | Versucht zuerst natives, greift dann auf CLIProxyAPI zurück |

Pro Anbieter konfigurieren:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Armaturenbrett UI

### Einstellungen → Proxy-Registerkarte

- **Globaler Proxy** Konfiguration (einmal für den gesamten Datenverkehr festgelegt)
- **Proxy pro Anbieter** überschreibt
- **Proxy pro Verbindung** Aufgaben
- **Verbindungstest** über konfigurierten Proxy
- **Farbcodierte Abzeichen** Zeigt den aktiven Proxy-Level an

### Einstellungen → 1proxy Tab

- **Jetzt synchronisieren** Klicken Sie auf die Schaltfläche, um kostenlose Proxys abzurufen
- **Statistikkarten** : Gesamt, Aktiv, Durchschnittliche Qualität, Letzte Synchronisierung
- **Filter** : Protokoll, Ländercode, Mindestqualität
- **Proxy-Tabelle** mit Host, Protokoll, Land, Qualitätsfaktor, Latenz, Anonymität, Google -Zugriff
- **Synchronisierungsstatus** Panel mit success/failure -Tracking und aufeinanderfolgender Fehlerzählung
- **Alles löschen** um alle 1proxy-Einträge zu entfernen

---

## API Referenz

### Proxy-Einstellungen API

| Verfahren | Endpunkt                                       | Beschreibung                                        |
| --------- | ---------------------------------------------- | --------------------------------------------------- |
| `GET`     | `/api/settings/proxy`                          | Holen Sie sich die vollständige Proxy-Konfiguration |
| `GET`     | `/api/settings/proxy?level=global`             | Holen Sie sich einen globalen Proxy                 |
| `GET`     | `/api/settings/proxy?level=provider&id=openai` | Holen Sie sich den Provider-Proxy                   |
| `GET`     | `/api/settings/proxy?resolve=connectionId`     | Effektiven Proxy auflösen                           |
| `PUT`     | `/api/settings/proxy`                          | Proxy-Konfiguration aktualisieren                   |
| `DELETE`  | `/api/settings/proxy?level=provider&id=openai` | Proxy auf Ebene entfernen                           |

### Proxy-Registrierung API

| Verfahren | Endpunkt                                          | Beschreibung                      |
| --------- | ------------------------------------------------- | --------------------------------- |
| `GET`     | `/api/v1/management/proxies`                      | Listen Sie alle Proxys auf        |
| `GET`     | `/api/v1/management/proxies?id=uuid`              | Holen Sie sich einen Proxy von ID |
| `GET`     | `/api/v1/management/proxies?id=uuid&where_used=1` | Erhalten Sie Proxy-Zuweisungen    |
| `POST`    | `/api/v1/management/proxies`                      | Proxy erstellen                   |
| `PATCH`   | `/api/v1/management/proxies`                      | Proxy aktualisieren               |
| `DELETE`  | `/api/v1/management/proxies?id=uuid`              | Proxy löschen                     |
| `DELETE`  | `/api/v1/management/proxies?id=uuid&force=1`      | Löschen erzwingen                 |
| `POST`    | `/api/v1/management/proxies/bulk-assign`          | Massenzuweisung                   |
| `GET`     | `/api/v1/management/proxies/assignments`          | Aufgaben auflisten                |
| `GET`     | `/api/v1/management/proxies/health`               | Proxy-Gesundheitsstatistiken      |

### Tunnel API

Informationen dazu, wie Sie Ihre OmniRoute Instanz dem öffentlichen Internet (Cloudflare/ngrok/Tailscale) zugänglich machen, anstatt ausgehende Daten über einen Proxy weiterzuleiten, finden Sie unter [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Der Tunnel REST API läuft unter `/api/tunnels/{cloudflared,ngrok,tailscale}/*` und ist orthogonal zur oben dokumentierten ausgehenden Proxy-Kette.

### 1proxy API

| Verfahren | Endpunkt                               | Beschreibung                                  |
| --------- | -------------------------------------- | --------------------------------------------- |
| `GET`     | `/api/settings/oneproxy`               | Listen Sie 1Proxy-Proxys auf                  |
| `GET`     | `/api/settings/oneproxy?action=stats`  | Statistiken + Synchronisierungsstatus abrufen |
| `GET`     | `/api/settings/oneproxy?action=status` | Nur den Synchronisierungsstatus abrufen       |
| `POST`    | `/api/settings/oneproxy`               | Synchronisierung auslösen                     |
| `POST`    | `/api/settings/oneproxy/rotate`        | Zum nächsten Proxy wechseln                   |
| `DELETE`  | `/api/settings/oneproxy?id=uuid`       | Löschen Sie eins                              |
| `DELETE`  | `/api/settings/oneproxy?clearAll=1`    | Alles löschen                                 |

### Upstream-Proxy API

| Verfahren | Endpunkt                          | Beschreibung                                    |
| --------- | --------------------------------- | ----------------------------------------------- |
| `GET`     | `/api/upstream-proxy/:providerId` | Holen Sie sich die Upstream-Proxy-Konfiguration |
| `PUT`     | `/api/upstream-proxy/:providerId` | Legen Sie den Upstream-Proxy-Modus fest         |
| `DELETE`  | `/api/upstream-proxy/:providerId` | Entfernen Sie die Upstream-Proxy-Konfiguration  |

---

## Umgebungsvariablen

| Variable              | Standard | Beschreibung                                                                    |
| --------------------- | -------- | ------------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`   | Aktivieren Sie SOCKS5 Proxy-Unterstützung (Standard- `true` in `.env.example`). |

---

## Fehlerbehebung

### „SOCKS5 -Proxy ist deaktiviert“

Legen Sie `ENABLE_SOCKS5_PROXY=true` in Ihrer `.env` Datei fest und starten Sie neu.

### Fehler „Socket hängen“ durch Proxy

Dies ist bei billigen Proxys normal, die ungenutzte Verbindungen abbrechen. OmniRoute erledigt dies bereits durch:

- Keep-Alive bei Proxy-Verbindungen deaktivieren (`keepAliveTimeout: 1`)
- Pipelining deaktivieren (`pipelining: 0`)
- Zwischenspeichern von Dispatchern, um wiederholte Handshakes zu vermeiden

Wenn das Problem weiterhin besteht, versuchen Sie es mit einem anderen Proxy oder verwenden Sie die 1-Proxy-Rotationsfunktion.

### „unsupported_country_region_territory“ während OAuth

Stellen Sie sicher, dass der Proxy konfiguriert ist** vor** Starten des OAuth Flusses. OmniRoute leitet OAuth -Token-Austausch über den konfigurierten Proxy. Legen Sie zunächst einen globalen Proxy oder Proxy auf Anbieterebene fest und stellen Sie dann eine Verbindung her.

### Proxy wird nicht verwendet

Überprüfen Sie die Auflösungsreihenfolge:

1. Überprüfen Sie dies mit `GET /api/settings/proxy?resolve=your-connection-id`
2. Überprüfen Sie, ob der Proxy `status` `active` ist (nicht `inactive`).
3. Stellen Sie sicher, dass der Proxy-Zuweisungsbereich mit Ihrer Verbindung übereinstimmt

### 1Proxy-Synchronisierung schlägt fehl

Überprüfen Sie den Synchronisierungsstatus:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Wenn `consecutiveFailures >= 5`, hat der Schutzschalter ausgelöst. Starten Sie den Server neu, um ihn zurückzusetzen, oder warten Sie auf den manuellen Reset.

---

## Datenbankschema

### `proxy_registry` Tabelle

```sql
CREATE TABLE proxy_registry (
  id TEXT PRIMARY KEY,
  name TEXT NOT NULL,
  type TEXT NOT NULL DEFAULT 'http',
  host TEXT NOT NULL,
  port INTEGER NOT NULL,
  username TEXT DEFAULT '',
  password TEXT DEFAULT '',
  region TEXT,
  notes TEXT,
  status TEXT DEFAULT 'active',
  source TEXT NOT NULL DEFAULT 'manual',    -- 'manual' or 'oneproxy'
  quality_score INTEGER,                     -- 0-100 (1proxy only)
  latency_ms INTEGER,                        -- milliseconds (1proxy only)
  anonymity TEXT,                            -- transparent/anonymous/elite
  google_access INTEGER DEFAULT 0,           -- can access Google? (1proxy)
  last_validated TEXT,                       -- ISO timestamp (1proxy)
  country_code TEXT,                         -- ISO 2-letter code (1proxy)
  created_at TEXT NOT NULL,
  updated_at TEXT NOT NULL
);
```

### `proxy_assignments` Tabelle

```sql
CREATE TABLE proxy_assignments (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  proxy_id TEXT NOT NULL REFERENCES proxy_registry(id),
  scope TEXT NOT NULL,        -- 'global', 'provider', 'account', 'combo'
  scope_id TEXT,              -- provider ID, connection ID, or combo ID
  created_at TEXT NOT NULL,
  updated_at TEXT NOT NULL,
  UNIQUE(scope, scope_id)
);
```

---

## Proxy-Zustandsprüfung (v3.8.16 +)

OmniRoute's** Proxy-Fast-Fail** Der Mechanismus (`src/lib/proxyHealth.ts`) erkennt tote Proxys in < 2s über eine schnelle TCP -Verbindungsprüfung** speichert das Ergebnis zwischen** um den Overhead pro Anfrage zu vermeiden.

### Wie es funktioniert

```
Request ──▶ ProxyHealthCache.get(url)
             │
             ├─ Cache hit + fresh?  ──▶ return cached status
             │
             └─ Cache miss / stale?  ──▶ TCP connect to host:port
                                          (timeout: FAST_FAIL_TIMEOUT_MS)
                                          ──▶ cache for HEALTH_CACHE_TTL_MS
                                          ──▶ return result
```

Ohne dies würde ein toter Proxy jede Anfrage für die gesamte `PROXY_TIMEOUT_MS` (Standard 30 Sekunden) blockieren, bevor sie fehlschlägt.

### Einstellbare Umgebungsvariablen

| Variable                     | Standard | Zweck                                                      |
| ---------------------------- | -------- | ---------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`   | TCP -Verbindungs-Timeout pro Integritätsprüfung            |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`  | Wie lange ein Gesundheitsergebnis zwischengespeichert wird |

**Empfohlene Werte:**

| Szenario                         | Fast-Fail-Timeout | Cache TTL | Argumentation                                                                        |
| -------------------------------- | ----------------- | --------- | ------------------------------------------------------------------------------------ |
| API -Gateway mit hohem Durchsatz | 1500 ms           | 60000 ms  | Aggressiver, ausfallsicherer, längerer Cache zur Reduzierung von Überprüfungen       |
| Geoverteilte Knoten              | 3000 ms           | 15000 ms  | Langsamere Netzwerke benötigen mehr Zeit; Kürzerer Cache für schnelles Failover      |
| Entwicklung / Tests              | 1000 ms           | 10000 ms  | Schnelle Iteration auf lokalen Proxys                                                |
| Stealth / Anti-Erkennung         | 2500 ms           | 45000 ms  | Vermeiden Sie schnelles Sondieren, das zu Geschwindigkeitsbegrenzungen führen könnte |

### Überprüfen des Proxy-Zustands

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Das `stale` Flag ist `true`, wenn der Cache-Eintrag `HEALTH_CACHE_TTL_MS` überschritten hat und die nächste Anfrage eine neue Prüfung auslöst.

### Standardeinstellungen pro Proxytyp

Die Gesundheitsprüfung verwendet sinnvolle Standardwerte basierend auf dem URL Schema:

| Schema                     | Standardport |
| -------------------------- | ------------ |
| `http://`                  | 8080         |
| `https://`                 | 443          |
| `socks5://` / `socks5h://` | 1080         |

Benutzerdefinierte Ports im URL (`http://host:9999`) haben immer Vorrang vor dem Standardschema.

---

## Proxy-Analyse und Beobachtbarkeit

OmniRoute verfolgt die Pro-Proxy-Nutzung, um Betreibern bei der Diagnose von Routing-Mustern, Latenzspitzen und wiederkehrenden Fehlern zu helfen.

### Was wird verfolgt?

Für jede Anfrage über einen konfigurierten Proxy zeichnet OmniRoute Folgendes auf:

| Metrisch     | Beschreibung                                                      |
| ------------ | ----------------------------------------------------------------- |
| `proxy_url`  | Vollständiger Proxy- URL (mit maskierten Authentifizierungsdaten) |
| `provider`   | Upstream-Anbieter ID (Openai, Anthropic usw.)                     |
| `latency_ms` | Gesamte Roundtrip-Zeit einschließlich Proxy-Handshake             |
| `connect_ms` | Nur TCP -Verbindungszeit                                          |
| `status`     | HTTP Statuscode vom Upstream                                      |
| `error`      | Fehlerklasse, wenn die Anfrage fehlgeschlagen ist                 |
| `timestamp`  | ISO 8601 UTC                                                      |

### Zugriff auf die Daten

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Der eigentliche Endpunkt ist `/api/usage/proxy-logs` (siehe `src/app/api/usage/proxy-logs/route.ts`). Dieser Endpunkt unterstützt:

- `GET /api/usage/proxy-logs` — ruft Proxy-Protokolle ab
- `DELETE /api/usage/proxy-logs` — löscht alle Proxy-Protokolle

Aggregierte Statistiken können bei Bedarf direkt aus der `proxy_logs` Tabelle über SQL abgefragt werden. Das Dashboard UI bietet möglicherweise aggregierte Ansichten.

### Gemeinsame Muster

**Erkennen Sie einen flatternden Proxy** (abwechselnd zwischen success/failure):

```sql
SELECT proxy_url,
       COUNT(*) AS total,
       SUM(CASE WHEN status >= 500 THEN 1 ELSE 0 END) AS errors,
       ROUND(100.0 * SUM(CASE WHEN status >= 500 THEN 1 ELSE 0 END) / COUNT(*), 1) AS error_pct
FROM proxy_logs
WHERE timestamp > datetime('now', '-1 hour')
GROUP BY proxy_url
HAVING error_pct > 5
ORDER BY error_pct DESC;
```

**Finden Sie langsame Proxys** (p95 Latenz > 2s):

```sql
WITH ranked AS (
  SELECT proxy_url, latency_ms,
         PERCENT_RANK() OVER (PARTITION BY proxy_url ORDER BY latency_ms) AS pct
  FROM proxy_logs
  WHERE timestamp > datetime('now', '-24 hour')
)
SELECT proxy_url, latency_ms
FROM ranked
WHERE pct >= 0.95
ORDER BY latency_ms DESC;
```

---

## Entscheidungsbaum für Rotationsstrategie

Wenn einem Bereich mehrere Proxys zugewiesen sind, verwendet OmniRoute einen** Rotationsstrategie** um auszuwählen, welches für jede Anfrage verwendet werden soll. Die Strategie wird auf Bereichsebene konfiguriert (global, pro Anbieter, pro Konto, pro Kombination).

### Verfügbare Strategien

| Strategie            | Wann zu verwenden                                | Abtausch                                                                  |
| -------------------- | ------------------------------------------------ | ------------------------------------------------------------------------- |
| `quality` (Standard) | Produktion mit Proxys unterschiedlicher Qualität | Bevorzugt hoch bewertete Proxys; kann niedrig bewertete aushungern lassen |
| `random`             | Lastverteilung, Privatsphäre                     | Gleichmäßige Verteilung; ignoriert Qualitätssignale                       |
| `sequential`         | Debugging, deterministisches Testen              | Durchläuft die Proxys der Reihe nach; leicht zum Nachdenken               |

### Entscheidungsbaum

```
                    Do you have quality scores for your proxies?
                    │
        ┌───────────┴───────────┐
        │                       │
       YES                     NO
        │                       │
   Are all proxies             │
   roughly equal                  │
   in quality?                   │
        │                       │
   ┌────┴────┐                  │
   │         │                  │
  YES       NO                Use
   │         │              `random`
   │         │              (even spread
   │         │              builds quality
   │         │              data over time)
   │         │
   │    Use `quality`
   │    (best for
   │    mixed quality)
   │
Use `random`
(spread load
evenly)
```

## Automatischer Fehlerausschluss für Ihre eigenen Proxys

Der 1proxy-Marktplatzpool stuft ausgefallene Proxys bereits automatisch herab (siehe [Proxy-Qualitätswerte](#proxy-quality-scores) ). Für Proxys** Du** Der zur Registrierung hinzugefügte Hintergrundintegritätsplaner (`src/lib/proxyHealth/scheduler.ts`) bietet das gleiche Verhalten „ein totes Mitglied automatisch aus der Kette ausschließen“, ohne etwas zu löschen:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Wie es in eine Multi-Proxy-Kette passt:

1. Der Scheduler prüft alle registrierten Proxys alle `PROXY_HEALTH_INTERVAL_MS` (Standard 10 Minuten; mindestens 1 Minute).
2. Nach `PROXY_AUTO_REMOVE_AFTER` fortlaufend** schlüssig** Bei Ausfällen (ein echter Verbindungsfehler — ein Timeout oder der eigene 5xx des Probe-Ziels zählt nie, siehe [Proxy-Zustandsprüfung](#proxy-health-checking-v3816) ), wird der `status` des Proxys auf `dead` gesetzt.
3. `dead` ist einer der Status, die der Alive-Status-Filter, der von pool/rotation Auflösung verwendet wird, ausschließt, sodass die Rotation eines Bereichs (Round-Robin / Random / Sticky / Latency — siehe [Entscheidungsbaum für Rotationsstrategie](#rotation-strategy-decision-tree) ) die Übergabe dieses Proxys an neue Anfragen sofort stoppt. Es sind keine anderen Proxys im Pool betroffen, und der gesamte Pool greift niemals stillschweigend auf eine direkte Verbindung zurück. Siehe — siehe den Fail-Closed-Guard des [4-Level-Proxy-Systems](#4-level-proxy-system).
4. Der Scheduler prüft weiterhin `dead` Proxys im gleichen Intervall. Bei der nächsten erfolgreichen Prüfung wird `status` wieder auf `active` umgestellt und die Rotation — wird erneut aktiviert, ohne dass ein erneutes manuelles Hinzufügen erforderlich ist.

Das ist Absicht** Opt-In und zerstörungsfrei** : Standardmäßig zählt und protokolliert der Scheduler nur Fehler (siehe Richtlinie C in `decision.ts`), und `PROXY_AUTO_DISABLE` löscht niemals eine Zeile — wofür das separate, aggressivere `PROXY_AUTO_REMOVE` Flag gedacht ist. Wenn beide auf `true` gesetzt sind, gewinnt `PROXY_AUTO_REMOVE` (ein Proxy, der gelöscht werden soll, hat zwischendurch keine Verwendung für eine Soft-Disable). Die vollständige Variablenliste finden Sie in der Referenz [zur Umgebungskonfiguration](../reference/ENVIRONMENT.md).

---

> 📖** Zugehörige Dokumentation:**
>
> - [Benutzerhandbuch](../guides/USER_GUIDE.md) — Allgemeine Einrichtung und Konfiguration – [API Referenz](../reference/API_REFERENCE.md) — Vollständige API Dokumentation – [Umgebungskonfiguration](../reference/ENVIRONMENT.md) — Alle Umgebungsvariablen
