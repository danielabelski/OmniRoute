# 🌐 OmniRoute Proxy Guide (Polski)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Omiń blokady geograficzne, chroń swoją tożsamość i kieruj ruch AI przez dowolny serwer proxy — przy zerowej złożoności konfiguracji.**

OmniRoute zawiera w pełni funkcjonalny system zarządzania proxy, który umożliwia kierowanie ruchu nadrzędnego dostawcy AI przez serwery proxy HTTP, HTTPS lub SOCKS5. Niezależnie od tego, czy jesteś w zablokowanym regionie, potrzebujesz rotacji IP, czy też chcesz ukrywać odciski palców — ten przewodnik opisuje wszystko.

---

## Spis treści

- [Dlaczego warto korzystać z serwerów proxy?](#why-use-proxies)
- [Przegląd architektury](#architecture-overview)
- [4-poziomowy system proxy](#4-level-proxy-system)
- [Rejestr proxy (CRUD)](#proxy-registry-crud)
- [Bezpłatny rynek 1proxy](#1proxy-free-proxy-marketplace)
- [Rotacja proxy](#proxy-rotation)
- [Ochrona przed wykrywaniem i ukrywanie się](#anti-detection--stealth)
- [Tryby proxy nadrzędnego](#upstream-proxy-modes)
- [Deska rozdzielcza UI](#dashboard-ui)
- [API Odniesienie](#api-reference)
- [Zmienne środowiskowe](#environment-variables)
- [Rozwiązywanie problemów](#troubleshooting)

---

## Dlaczego warto korzystać z serwerów proxy?

Wielu dostawców AI ogranicza dostęp według regionu geograficznego. Deweloperzy w** Rosja, Chiny, Iran, Kuba, Turcja** , a inne kraje napotykają błędy takie jak:

```
unsupported_country_region_territory
```

Nawet poza zablokowanymi regionami serwery proxy są przydatne w przypadku:

| Przypadek użycia           | Opis                                                                       |
| -------------------------- | -------------------------------------------------------------------------- |
| **Obwodnica geograficzna** | Uzyskaj dostęp do OpenAI, Anthropic, Codex, Copilot z zablokowanych krajów |
| **obrót IP**               | Rozdzielaj żądania na wiele IPs, aby uniknąć ograniczania szybkości        |
| **Prywatność**             | Ukryj swoje prawdziwe IP przed dostawcami wyższego szczebla                |
| **Zgodność**               | Kieruj ruch przez określone jurysdykcje                                    |
| **Testowanie**             | Symuluj żądania z różnych regionów                                         |

---

## Przegląd architektury

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

### Kluczowe komponenty

| Część                       | Plik                                         | Rola                                                         |
| --------------------------- | -------------------------------------------- | ------------------------------------------------------------ |
| **Rejestr proxy**           | `src/lib/db/proxies.ts`                      | CRUD dla wpisów proxy, przypisania zakresów +                |
| **Pełnomocnik dyspozytora** | `open-sse/utils/proxyDispatcher.ts`          | Tworzy dyspozytorów `undici` ProxyAgent/SOCKS z buforowaniem |
| **Pobieranie proxy**        | `open-sse/utils/proxyFetch.ts`               | Zawija `fetch()` za pomocą wtrysku dyspozytora proxy         |
| **Ustawienia Trasa**        | `src/app/api/settings/proxy/route.ts`        | Starsza konfiguracja proxy API (GET/PUT/DELETE)              |
| **Ścieżka zarządzania**     | `src/app/api/v1/management/proxies/route.ts` | Rejestr CRUD API (GET/POST/PATCH/DELETE)                     |
| **1 DB**                    | `src/lib/db/oneproxy.ts`                     | Bezpłatna trwałość rynku proxy                               |

---

## Domyślny stan proxy dla nowych kont

W** Ustawienia → Proxy → Konfiguracja globalna** , używać** Włącz domyślnie serwer proxy dla nowych połączeń** aby wybrać początkowy stan proxy dla nowo dodanych kont dostawców.

Nowe ustawienie kontroluje początkowy stan serwera proxy nowo dodanych kont dostawców. Nie zmienia istniejących kont ani nie zastępuje globalnego przełącznika proxy. Jego wartość początkowa zachowuje poprzednie zachowanie. Wyłącz tę opcję raz, aby tworzyć przyszłe konta z domyślnie wyłączonym serwerem proxy.

Preferencje są przechowywane jako `defaultNewConnectionProxyEnabled` w istniejących ustawieniach API. Domyślnie jest to `true` jeśli nigdy nie jest zapisywany. Zapisanie `false` obowiązuje dla kolejnych nowych kont bez ponownego uruchamiania. `POST /api/providers` akceptuje opcjonalną, ścisłą wartość logiczną `proxyEnabled`; jawne `true` lub `false` ma pierwszeństwo przed domyślnym ustawieniem tworzenia. Pominięcie zduplikowanego konta lub ponowne połączenie OAuth zachowuje przechowywany stan tego konta. Konta indywidualne można później nadal włączać i wyłączać.

Selektywne transfery dostawców korzystają z ustawień domyślnych instalacji docelowej dla nowych kont i zachowują zasady docelowe podczas zastępowania istniejących kont. Przełączniki proxy nie są przenośnymi polami transferu. Pełne przywracanie kopii zapasowych i migracja historii JSON/SQL zachowują istniejącą semantykę przywracania, w tym zapisane wartości konta i domyślne ustawienia schematu starszego typu; pełne przywrócenie ustawień może również przywrócić tę preferencję.

Ta preferencja nie przypisuje serwera proxy ani nie ustala, czy jest on sprawny lub używany. Rzeczywisty routing nadal zależy od globalnego przełącznika proxy i odpowiedniej konfiguracji proxy. Dostawcy syntetyczni bez trwałego konta, ruch OAuth przed utworzeniem konta, serwery proxy environment/system i sieci zewnętrznych backendów są poza jego zakresem.

## 4-poziomowy system proxy

OmniRoute obsługuje konfigurację proxy pod adresem** cztery niezależne zakresy** , rozstrzygnięte w kolejności priorytetów:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Jak działa rozdzielczość

Kiedy OmniRoute wysyła żądanie do dostawcy wyższego szczebla, wywołuje `resolveProxyForConnectionFromRegistry()`, który sprawdza każdy poziom w kolejności:

1. **Poziom konta** — Czy do tego konkretnego połączenia ID przypisano serwer proxy?
2. **Poziom dostawcy** — Czy do tego dostawcy jest przypisany serwer proxy (np. `openai`)?
3. **Poziom globalny** — Czy skonfigurowano globalny serwer proxy?
4. **Brak serwera proxy** — Bezpośrednie połączenie z dostawcą.

Pierwszy mecz wygrywa. Oznacza to, że możesz ustawić globalny serwer proxy jako rezerwowy, ale zastąpić go dla określonych dostawców lub połączeń.

### Co jest przesyłane przez serwer proxy

| Typ ruchu             | Przesłane przez serwer proxy? | Notatki                                               |
| --------------------- | ----------------------------- | ----------------------------------------------------- |
| Zakończenia czatu     | ✅                            | Wszystkie prośby `/v1/chat/completions`               |
| Osadzenia             | ✅                            | `/v1/embeddings`                                      |
| Generowanie obrazu    | ✅                            | `/v1/images/generations`                              |
| Dźwięk (TTS/STT)      | ✅                            | `/v1/audio/*`                                         |
| wymiana tokenów OAuth | ✅                            | Rozwiązuje `unsupported_country_region_territory`     |
| Testy połączenia      | ✅                            | Przycisk „Testuj połączenie” korzysta z serwera proxy |
| Odświeżenie tokena    | ✅                            | Odnowa OAuth w tle                                    |
| Synchronizacja modelu | ✅                            | Lista modeli i ich odkrycie                           |

---

## Rejestr proxy (CRUD)

Rejestr proxy to tabela SQLite (`proxy_registry`), w której przechowywane są wszystkie Twoje proxy. Każdy serwer proxy posiada:

| Pole       | Typ              | Opis                                                             |
| ---------- | ---------------- | ---------------------------------------------------------------- |
| `id`       | UUID             | Unikalny identyfikator                                           |
| `name`     | Smyczkowy        | Etykieta czytelna dla człowieka                                  |
| `type`     | Smyczkowy        | Protokół: `http`, `https`, `socks5`                              |
| `host`     | Smyczkowy        | Nazwa hosta proxy lub IP                                         |
| `port`     | Liczba całkowita | Numer portu                                                      |
| `username` | Smyczkowy        | Autoryzowana nazwa użytkownika (zaszyfrowana w stanie spoczynku) |
| `password` | Smyczkowy        | Hasło uwierzytelniające (zaszyfrowane w stanie spoczynku)        |
| `region`   | Smyczkowy        | Etykieta regionu geograficznego                                  |
| `notes`    | Smyczkowy        | Notatki tekstowe                                                 |
| `status`   | Smyczkowy        | `active` lub `inactive`                                          |
| `source`   | Smyczkowy        | `manual` lub `oneproxy`                                          |

### Tworzenie proxy

**Za pośrednictwem panelu:**

1. Idź do** Ustawienia → Proxy**
2. Trzask** Dodaj serwer proxy**
3. Wpisz typ, host, port i opcjonalne poświadczenia uwierzytelniania
4. Ratować

**Przez API:**

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

### Aktualizowanie serwera proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Notatka:** Poświadczenia zostaną zachowane, chyba że wyraźnie wyślesz niepuste zamienniki. Wysyłanie pustych ciągów znaków dla `username`/`password` spowoduje zachowanie zapisanych wartości.

### Usuwanie serwera proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Lista serwerów proxy

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Przypisywanie proxy do zakresów

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

### Rozwiązywanie problemu skutecznego serwera proxy

Sprawdź, który serwer proxy będzie używany dla danego połączenia:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Zwraca rozwiązany serwer proxy z jego poziomem (`account`, `provider` lub `global`) i źródłem.

### Przypisanie zbiorcze

Przypisz jedno proxy do wielu dostawców lub połączeń jednocześnie:

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

Serwery proxy są zawarte w**Backup/Restore** system. Kiedy eksportujesz konfigurację OmniRoute :

1. Idź do** Pulpit nawigacyjny → Ustawienia → Kopia zapasowa**
2. Trzask** Eksport** Rejestr proxy — i przypisania są uwzględnione
3. Aby przywrócić, kliknij** Import** i prześlij plik kopii zapasowej

Rejestr proxy również obsługuje** upsert przez port + hosta** — jeśli zaimportujesz serwer proxy, który już istnieje (ten sam host i port), zostanie on zaktualizowany, zamiast tworzyć duplikat.

### Migracja starszego typu

Jeśli skonfigurowałeś proxy w starszej wersji (rejestracja wstępna), OmniRoute automatycznie je migruje:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Dzieje się tak raz przy pierwszym uruchomieniu po aktualizacji. Użyj `migrateLegacyProxyConfigToRegistry({ force: true })`, aby uruchomić ponownie.

---

## 1proxy Bezpłatny rynek proxy

> 🆕** Dodane przez [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Problem [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integruje się z** [1 serwer proxy](https://1proxy-api.aitradepulse.com)** platforma społecznościowa, do której można uzyskać dostęp** setki bezpłatnych, zweryfikowanych serwerów proxy** z całego świata. Jest to idealne rozwiązanie dla użytkowników, którzy nie mają własnej infrastruktury proxy.

### Jak to działa

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Synchronizuj** — OmniRoute pobiera sprawdzone proxy z 1proxy API
2. **Sklep** — Proxy są zapisywane w tej samej tabeli `proxy_registry` co `source = 'oneproxy'`
3. **Filtr** — Filtruj według protokołu, kraju i wyniku jakości
4. **Obracać** — Wybierz najlepszy serwer proxy, korzystając ze strategii jakościowej, losowej lub sekwencyjnej
5. **Autodegradacja** — Nieudane serwery proxy mają obniżony wynik jakości; poniżej progu → oznaczony jako nieaktywny

### Synchronizowanie serwerów proxy

**Za pośrednictwem panelu:**

1. Idź do** Ustawienia → 1proxy** patka
2. Trzask** „Synchronizuj teraz”**
3. Zobacz statystyki: łączna liczba serwerów proxy, liczba aktywnych, średnia jakość, podział według krajów

**Przez API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtrowanie serwerów proxy

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

### Wyniki jakości proxy

Każdy serwer proxy 1proxy zawiera metadane:

| Pole            | Opis                                                          |
| --------------- | ------------------------------------------------------------- |
| `qualityScore`  | Ocena 0-100 z walidacji 1proxy                                |
| `latencyMs`     | Zmierzone opóźnienie sieci                                    |
| `anonymity`     | `transparent`, `anonymous` lub `elite`                        |
| `googleAccess`  | Określa, czy serwer proxy może uzyskać dostęp do usług Google |
| `countryCode`   | Dwuliterowy kod kraju ISO                                     |
| `lastValidated` | Znacznik czasu ostatniej walidacji                            |

Wyniki jakości są dostosowywane dynamicznie:

- **Nieudane żądania** obniżyć wynik o 10 punktów
- **Wynik spada do ≤ 10** serwer proxy → jest oznaczony jako `inactive`
- Nieaktywne proxy są wyłączone z rotacji

### Strategie rotacyjne

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

### Wyłącznik automatyczny

Synchronizacja 1proxy ma wbudowany wyłącznik automatyczny:

- Po** 5 kolejnych błędów synchronizacji** , dalsze próby synchronizacji zostaną zablokowane
- Zresetuj za pomocą: `resetOneproxyCircuitBreaker()` lub zrestartuj serwer
- Stan synchronizacji jest dostępny na `GET /api/settings/oneproxy?action=status`

### Czyszczenie 1proxy proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Ochrona przed wykrywaniem i ukrywanie się

OmniRoute nie tylko kieruje ruchem przez serwer proxy — ale sprawia, że ruch wygląda na legalny:

### TLS Fałszowanie odcisków palców

Używa `wreq-js` do generowania odcisków palców TLS podobnych do przeglądarki, omijając systemy wykrywania botów, które flagują uściski dłoni TLS inne niż przeglądarka.

### CLI Dopasowanie odcisków palców

The**CLI Przełącznik odcisku palca** (`Settings → Security`) zmienia kolejność nagłówków HTTP i pól treści JSON, aby dopasować je do dokładnego podpisu natywnych plików binarnych CLI (kod Claude, Codex itp.). To działa** na górze** pełnomocnik:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Dostajesz oba** maskowanie IP** I** poproś o autentyczność** jednocześnie.

### Pełnomocnik IP Konserwacja

Oznaczone kolorami plakietki na pulpicie nawigacyjnym pokazują, który poziom proxy jest aktywny:

| Odznaka | Poziom     | Oznaczający                                                 |
| ------- | ---------- | ----------------------------------------------------------- |
| 🟢      | Światowy   | Cały ruch przechodzi przez ten serwer proxy                 |
| 🟡      | Dostawca   | Tylko ruch tego dostawcy jest przesyłany przez serwer proxy |
| 🔵      | Połączenie | Ta konkretna key/account używa tego proxy                   |

Odznaka pokazuje również rozwiązany serwer proxy IP w celu weryfikacji.

---

## Tryby proxy nadrzędnego

W przypadku dostawców korzystających ze wzorca CLIProxyAPI OmniRoute obsługuje trzy tryby proxy nadrzędnego:

| Tryb          | Opis                                                       |
| ------------- | ---------------------------------------------------------- |
| `native`      | OmniRoute obsługuje bezpośrednio routing proxy (domyślnie) |
| `cliproxyapi` | Delegaty do zewnętrznej instancji CLIProxyAPI              |
| `fallback`    | Najpierw próbuje natywnie, potem wraca do CLIProxyAPI      |

Skonfiguruj dla każdego dostawcy:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Deska rozdzielcza UI

### Ustawienia → Zakładka proxy

- **Globalny serwer proxy** konfiguracja (ustawiona raz dla całego ruchu)
- **Serwer proxy dla każdego dostawcy** zastępuje
- **Serwer proxy na połączenie** zadania
- **Test połączenia** poprzez skonfigurowany serwer proxy
- **Odznaki oznaczone kolorami** pokazujący aktywny poziom proxy

### Ustawienia → 1proxy Tab

- **Synchronizuj teraz** przycisk umożliwiający pobranie bezpłatnych serwerów proxy
- **Karty statystyk** : Łącznie, Aktywne, Średnia jakość, Ostatnia synchronizacja
- **Filtry** : Protokół, kod kraju, jakość minimalna
- **Tabela proxy** z hostem, protokołem, krajem, wynikiem jakości, opóźnieniem, anonimowością, dostępem Google
- **Stan synchronizacji** panel ze śledzeniem success/failure i liczbą kolejnych awarii
- **Wyczyść wszystko** aby usunąć wszystkie wpisy 1proxy

---

## API Odniesienie

### Ustawienia proxy API

| Metoda   | Punkt końcowy                                  | Opis                             |
| -------- | ---------------------------------------------- | -------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Uzyskaj pełną konfigurację proxy |
| `GET`    | `/api/settings/proxy?level=global`             | Uzyskaj globalny serwer proxy    |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Uzyskaj serwer proxy dostawcy    |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Rozwiąż skuteczny serwer proxy   |
| `PUT`    | `/api/settings/proxy`                          | Zaktualizuj konfigurację proxy   |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Usuń serwer proxy na poziomie    |

### Rejestr proxy API

| Metoda   | Punkt końcowy                                     | Opis                            |
| -------- | ------------------------------------------------- | ------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Lista wszystkich serwerów proxy |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Uzyskaj proxy przez ID          |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Uzyskaj przypisania proxy       |
| `POST`   | `/api/v1/management/proxies`                      | Utwórz serwer proxy             |
| `PATCH`  | `/api/v1/management/proxies`                      | Zaktualizuj serwer proxy        |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Usuń proxy                      |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Wymuś usunięcie                 |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Przypisz zbiorczo               |
| `GET`    | `/api/v1/management/proxies/assignments`          | Lista zadań                     |
| `GET`    | `/api/v1/management/proxies/health`               | Statystyki stanu serwera proxy  |

### Tunele API

Informacje na temat udostępniania instancji OmniRoute publicznemu internetowi (Cloudflare/ngrok/Tailscale) zamiast kierowania ruchu wychodzącego przez serwer proxy można znaleźć w artykule [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Tunel REST API znajduje się pod `/api/tunnels/{cloudflared,ngrok,tailscale}/*` i jest prostopadły do udokumentowanego powyżej wychodzącego łańcucha proxy.

### 1 API

| Metoda   | Punkt końcowy                          | Opis                              |
| -------- | -------------------------------------- | --------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Lista 1 serwerów proxy            |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Uzyskaj status synchronizacji +   |
| `GET`    | `/api/settings/oneproxy?action=status` | Uzyskaj tylko stan synchronizacji |
| `POST`   | `/api/settings/oneproxy`               | Synchronizacja wyzwalacza         |
| `POST`   | `/api/settings/oneproxy/rotate`        | Obróć do następnego proxy         |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Usuń jeden                        |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Wyczyść wszystko                  |

### Upstream Proxy API

| Metoda   | Punkt końcowy                     | Opis                                           |
| -------- | --------------------------------- | ---------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Pobierz konfigurację serwera proxy nadrzędnego |
| `PUT`    | `/api/upstream-proxy/:providerId` | Ustaw tryb proxy nadrzędnego                   |
| `DELETE` | `/api/upstream-proxy/:providerId` | Usuń konfigurację serwera proxy nadrzędnego    |

---

## Zmienne środowiskowe

| Zmienny               | Domyślny | Opis                                                           |
| --------------------- | -------- | -------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`   | Włącz obsługę proxy SOCKS5 (domyślnie `true` w `.env.example`) |

---

## Rozwiązywanie problemów

### „SOCKS5 proxy jest wyłączone”

Ustaw `ENABLE_SOCKS5_PROXY=true` w pliku `.env` i uruchom ponownie.

### Błędy „rozłączenia gniazda” za pośrednictwem serwera proxy

Jest to normalne w przypadku tanich serwerów proxy, które zrywają bezczynne połączenia. OmniRoute już sobie z tym radzi:

- Wyłączanie utrzymywania aktywności w połączeniach proxy (`keepAliveTimeout: 1`)
- Wyłączanie potokowania (`pipelining: 0`)
- Buforowanie dyspozytorów, aby uniknąć powtarzających się uścisków dłoni

Jeśli problem będzie się powtarzał, wypróbuj inny serwer proxy lub użyj funkcji rotacji 1proxy.

### „unsupported_country_region_territory” podczas OAuth

Upewnij się, że serwer proxy jest skonfigurowany** zanim** rozpoczęcie przepływu OAuth. OmniRoute kieruje wymianę tokenów OAuth przez skonfigurowany serwer proxy. Najpierw ustaw serwer proxy globalny lub na poziomie dostawcy, a następnie połącz się.

### Serwer proxy nie jest używany

Sprawdź kolejność rozstrzygania:

1. Sprawdź za pomocą `GET /api/settings/proxy?resolve=your-connection-id`
2. Sprawdź, czy proxy `status` to `active` (nie `inactive`)
3. Upewnij się, że zakres przypisania proxy jest zgodny z Twoim połączeniem

### 1 synchronizacja proxy nie powiodła się

Sprawdź stan synchronizacji:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Jeśli `consecutiveFailures >= 5`, zadziałał wyłącznik automatyczny. Uruchom ponownie serwer, aby zresetować, lub poczekaj na reset ręczny.

---

## Schemat bazy danych

### `proxy_registry` Tabela

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

### `proxy_assignments` Tabela

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

## Sprawdzanie stanu serwera proxy (wersja 3.8.16 +)

OmniRoute** proxy, szybka awaria** mechanizm (`src/lib/proxyHealth.ts`) wykrywa martwe proxy w < 2s poprzez szybkie sprawdzenie połączenia TCP, a następnie** buforuje wynik** aby uniknąć narzutu na żądanie.

### Jak to działa

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

Bez tego martwy serwer proxy blokowałby każde żądanie pełnego `PROXY_TIMEOUT_MS` (domyślnie 30 s), zanim zakończy się niepowodzeniem.

### Przestrajalne zmienne środowiskowe

| Zmienny                      | Domyślny | Zamiar                                                           |
| ---------------------------- | -------- | ---------------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`   | Przekroczono limit czasu połączenia TCP na kontrolę stanu        |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`  | Jak długo wynik kondycji jest przechowywany w pamięci podręcznej |

**Zalecane wartości:**

| Scenariusz                       | Limit czasu szybkiej awarii | Pamięć podręczna TTL | Rozumowanie                                                                                              |
| -------------------------------- | --------------------------- | -------------------- | -------------------------------------------------------------------------------------------------------- |
| Brama API o dużej przepustowości | 1500 ms                     | 60000 ms             | Agresywna, szybka i dłuższa pamięć podręczna w celu ograniczenia kontroli                                |
| Węzły rozproszone geograficznie  | 3000 ms                     | 15000 ms             | Wolniejsze sieci potrzebują więcej czasu; krótsza pamięć podręczna dla szybkiego przełączania awaryjnego |
| Dev/testowanie                   | 1000 ms                     | 10000 ms             | Szybka iteracja na lokalnych serwerach proxy                                                             |
| Stealth/anty-wykrywanie          | 2500 ms                     | 45000ms              | Unikaj szybkiego sondowania, które mogłoby spowodować uruchomienie limitów szybkości                     |

### Sprawdzanie stanu serwera proxy

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Flaga `stale` to `true` gdy wpis w pamięci podręcznej przekroczył wartość `HEALTH_CACHE_TTL_MS`, a następne żądanie spowoduje ponowne sprawdzenie.

### Domyślne ustawienia typu dla serwera proxy

Kontrola stanu używa rozsądnych ustawień domyślnych w oparciu o schemat URL :

| Schemat                    | Domyślny port |
| -------------------------- | ------------- |
| `http://`                  | 8080          |
| `https://`                 | 443           |
| `socks5://` / `socks5h://` | 1080          |

Porty niestandardowe w URL (`http://host:9999`) zawsze mają pierwszeństwo przed domyślnym schematem.

---

## Analityka proxy i obserwowalność

OmniRoute śledzi wykorzystanie poszczególnych serwerów proxy, aby pomóc operatorom diagnozować wzorce routingu, skoki opóźnień i powtarzające się awarie.

### Co jest śledzone

Dla każdego żądania za pośrednictwem skonfigurowanego serwera proxy OmniRoute rejestruje:

| Metryczny    | Opis                                                               |
| ------------ | ------------------------------------------------------------------ |
| `proxy_url`  | Pełne proxy URL (z zamaskowanymi danymi autoryzacyjnymi)           |
| `provider`   | Dostawca usług wyższego szczebla ID (openai, antropiczny itp.)     |
| `latency_ms` | Całkowity czas podróży w obie strony, łącznie z uzgadnianiem proxy |
| `connect_ms` | TCP tylko czas połączenia                                          |
| `status`     | kod stanu HTTP od źródła                                           |
| `error`      | Klasa błędu, jeśli żądanie nie powiodło się                        |
| `timestamp`  | ISO 8601 UTC                                                       |

### Dostęp do danych

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Prawdziwym punktem końcowym jest `/api/usage/proxy-logs` (patrz `src/app/api/usage/proxy-logs/route.ts`). Ten punkt końcowy obsługuje:

- `GET /api/usage/proxy-logs` — pobierz logi proxy
- `DELETE /api/usage/proxy-logs` — wyczyść wszystkie logi proxy

W razie potrzeby zbiorcze statystyki można przeglądać bezpośrednio z tabeli `proxy_logs` za pośrednictwem SQL. Pulpit nawigacyjny UI może oferować widoki zbiorcze.

### Typowe wzory

**Wykryj trzepoczący serwer proxy** (na zmianę success/failure):

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

**Znajdź wolne proxy** (opóźnienie p95 > 2s):

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

## Drzewo decyzyjne strategii rotacji

Kiedy do zakresu przypisanych jest wiele serwerów proxy, OmniRoute używa a** strategia rotacji** aby wybrać, którego użyć dla każdego żądania. Strategię konfiguruje się na poziomie zakresu (globalny, na dostawcę, na konto, na kombinację).

### Dostępne strategie

| Strategia             | Kiedy używać                             | Kompromis                                                           |
| --------------------- | ---------------------------------------- | ------------------------------------------------------------------- |
| `quality` (domyślnie) | Produkcja z proxy o mieszanej jakości    | Preferuje wysoko oceniane proxy; mogą głodować te o niskich ocenach |
| `random`              | Rozkład obciążenia, prywatność           | Równa dystrybucja; ignoruje sygnały jakości                         |
| `sequential`          | Debugowanie, testowanie deterministyczne | Przełącza kolejno serwery proxy; łatwo to uzasadnić                 |

### Drzewo decyzyjne

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

## Automatyczne wykluczanie awarii dla własnych serwerów proxy

Pula 1proxy marketplace już sama automatycznie degraduje uszkodzone serwery proxy (zobacz [Wyniki Jakości serwerów proxy](#proxy-quality-scores) ). Dla proxy** Ty** dodany do rejestru harmonogram kondycji tła (`src/lib/proxyHealth/scheduler.ts`) zapewnia to samo zachowanie „automatycznie wykluczaj martwego członka z łańcucha”, bez usuwania czegokolwiek:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Jak to pasuje do łańcucha z wieloma serwerami proxy:

1. Program planujący sonduje każdy zarejestrowany serwer proxy co każde `PROXY_HEALTH_INTERVAL_MS` (domyślnie 10 minut; minimalnie 1 minuta).
2. Po `PROXY_AUTO_REMOVE_AFTER` kolejnych** rozstrzygający** awarie (rzeczywisty błąd połączenia — przekroczenie limitu czasu lub własne 5xx celu sondy nigdy się nie liczy, zobacz [Sprawdzanie stanu serwera proxy](#proxy-health-checking-v3816) ), `status` serwera proxy jest ustawione na `dead`.
3. `dead` to jeden ze statusów, który wyklucza filtr stanu aktywności używany przez rozdzielczość pool/rotation, więc rotacja zakresu (działanie okrężne / losowe / lepkie / opóźnienie — patrz [Drzewo decyzyjne strategii rotacji](#rotation-strategy-decision-tree) ) natychmiast przestaje przekazywać ten serwer proxy nowym żądaniom. Nie ma to wpływu na żadne inne serwery proxy w puli, a cała pula nigdy po cichu nie powraca do bezpośredniego połączenia. — patrz [4-poziomowy system proxy](#4-level-proxy-system) zapewniający zabezpieczenie przed awarią.
4. Program planujący sprawdza serwery proxy `dead` w tych samych odstępach czasu. Następna udana sonda odwraca `status` z powrotem do `active` i ponownie wchodzi w rotację — nie jest wymagane ręczne ponowne dodawanie.

To jest celowe** dobrowolne i nieniszczące** : domyślnie program planujący zlicza i rejestruje tylko awarie (zobacz politykę C w `decision.ts`), a `PROXY_AUTO_DISABLE` nigdy nie usuwa wiersza —, do czego służy osobna, bardziej agresywna flaga `PROXY_AUTO_REMOVE`. Jeśli oba są ustawione na `true`, wygrywa `PROXY_AUTO_REMOVE` (proxy, które ma zostać usunięte, nie ma zastosowania do miękkiego wyłączania pomiędzy). Pełną listę zmiennych znajdziesz w dokumentacji [konfiguracji środowiska](../reference/ENVIRONMENT.md).

---

> 📖** Powiązana dokumentacja:**
>
> - [Podręcznik użytkownika](../guides/USER_GUIDE.md) — Ogólna konfiguracja i konfiguracja - [API Odniesienie](../reference/API_REFERENCE.md) — Pełna dokumentacja API - [Konfiguracja środowiska](../reference/ENVIRONMENT.md) — Wszystkie zmienne środowiskowe
