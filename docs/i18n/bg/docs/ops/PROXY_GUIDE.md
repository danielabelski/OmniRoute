# 🌐 OmniRoute Proxy Guide (Български)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Заобикаляйте географски блокове, защитавайте самоличността си и маршрутизирайте AI трафик през всеки прокси — с нулева сложност на конфигурацията.**

OmniRoute включва пълнофункционална система за управление на прокси сървъри, която ви позволява да насочвате трафика на доставчика AI нагоре през HTTP, HTTPS или SOCKS5 прокси сървъри. Независимо дали сте в блокиран регион, имате нужда от IP ротация или искате стелт пръстови отпечатъци — това ръководство обхваща всичко.

---

## Съдържание

- [Защо да използвате проксита?](#why-use-proxies)
- [Преглед на архитектурата](#architecture-overview)
- [Прокси система на 4 нива](#4-level-proxy-system)
- [Прокси регистър (CRUD)](#proxy-registry-crud)
- [1прокси безплатен пазар](#1proxy-free-proxy-marketplace)
- [Прокси ротация](#proxy-rotation)
- [Анти-откриване и стелт](#anti-detection--stealth)
- [Прокси режими нагоре по веригата](#upstream-proxy-modes)
- [Табло UI](#dashboard-ui)
- [справка API](#api-reference)
- [Променливи на средата](#environment-variables)
- [Отстраняване на неизправности](#troubleshooting)

---

## Защо да използвате проксита?

Много доставчици AI ограничават достъпа по географски регион. Разработчици в** Русия, Китай, Иран, Куба, Турция** и други държави срещат грешки като:

```
unsupported_country_region_territory
```

Дори извън блокираните региони, прокситата са полезни за:

| Случай на употреба    | Описание                                                                             |
| --------------------- | ------------------------------------------------------------------------------------ |
| **Географски байпас** | Достъп до OpenAI, Anthropic, Codex, Copilot от блокирани държави                     |
| **IP ротация**        | Разпределете заявките между множество IPs, за да избегнете ограничаване на скоростта |
| **Поверителност**     | Скрийте истинския си IP от доставчиците нагоре по веригата                           |
| **Съответствие**      | Маршрутизирайте трафика през определени юрисдикции                                   |
| **Тестване**          | Симулирайте заявки от различни региони                                               |

---

## Преглед на архитектурата

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

### Ключови компоненти

| Компонент                 | Файл                                         | Роля                                                   |
| ------------------------- | -------------------------------------------- | ------------------------------------------------------ |
| **Прокси регистър**       | `src/lib/db/proxies.ts`                      | CRUD за прокси записи + присвоявания на обхват         |
| **Прокси диспечер**       | `open-sse/utils/proxyDispatcher.ts`          | Създава `undici` ProxyAgent/SOCKS диспечери с кеширане |
| **Извличане на прокси**   | `open-sse/utils/proxyFetch.ts`               | Обвива `fetch()` с инжектиране на прокси диспечер      |
| **Настройки Маршрут**     | `src/app/api/settings/proxy/route.ts`        | Наследена прокси конфигурация API (GET/PUT/DELETE)     |
| **Маршрут за управление** | `src/app/api/v1/management/proxies/route.ts` | Регистър CRUD API (GET/POST/PATCH/DELETE)              |
| **1 прокси DB**           | `src/lib/db/oneproxy.ts`                     | Устойчивост на безплатния прокси пазар                 |

---

## Състояние на прокси сървъра по подразбиране за нови акаунти

в** Настройки → Прокси → Глобална конфигурация** , използвайте** Активирайте прокси по подразбиране за нови връзки** за да изберете първоначалното състояние на прокси на новодобавените акаунти на доставчик.

Новата настройка контролира първоначалното състояние на прокси на новодобавените акаунти на доставчик. Той не променя съществуващите акаунти или замества глобалния превключвател на прокси. Първоначалната му стойност запазва предишното поведение. Изключете го веднъж, за да създадете бъдещи акаунти с деактивиран прокси сървър по подразбиране.

Предпочитанието се съхранява като `defaultNewConnectionProxyEnabled` чрез съществуващите настройки API. По подразбиране е `true`, когато никога не се запазва. Запазването `false` влиза в сила за следващите нови акаунти без рестартиране. `POST /api/providers` приема незадължителен строг булев `proxyEnabled`; изричен `true` или `false` има предимство пред настройката по подразбиране за създаване. Пропускането на дублиращ се акаунт или повторното свързване OAuth запазва съхраненото състояние на този акаунт. Индивидуалните акаунти все още могат да бъдат активирани или деактивирани след това.

Избирателните прехвърляния на доставчик използват по подразбиране дестинационната инсталация за нови акаунти и запазват политиката за дестинация при подмяна на съществуващи акаунти. Прокси превключвателите не са преносими полета за прехвърляне. Пълното възстановяване на резервно копие и историческата миграция JSON/SQL запазват съществуващата си семантика за възстановяване, включително запазени стойности на акаунта и настройки по подразбиране на наследената схема; пълното възстановяване на настройките също може да възстанови това предпочитание.

Това предпочитание не присвоява прокси, нито установява, че е изправно или се използва. Действителното маршрутизиране все още зависи от глобалния прокси превключвател и приложимата прокси конфигурация. Синтетичните доставчици без постоянен акаунт, OAuth трафик преди създаване на акаунт, environment/system прокси сървъри и мрежово свързване на външни бекендове са извън неговия обхват.

## Прокси система на 4 нива

OmniRoute поддържа прокси конфигурация на** четири независими обхвата** , решени по приоритет:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Как работи разделителната способност

Когато OmniRoute изпрати заявка до доставчик нагоре по веригата, той извиква `resolveProxyForConnectionFromRegistry()`, който проверява всяко ниво по ред:

1. **На ниво акаунт** — Има ли прокси, назначено за тази конкретна връзка ID?
2. **Ниво на доставчик** — Има ли прокси, назначено за този доставчик (напр. `openai`)?
3. **Глобално ниво** — Има ли конфигуриран глобален прокси?
4. **Няма прокси** — Директна връзка с доставчика.

Първият мач печели. Това означава, че можете да зададете глобален прокси като резервен, но да го замените за конкретни доставчици или връзки.

### Какво се проксира

| Тип трафик                | Проксиран? | Бележки                                       |
| ------------------------- | ---------- | --------------------------------------------- |
| Чат завършвания           | ✅         | Всички `/v1/chat/completions` заявки          |
| Вграждания                | ✅         | `/v1/embeddings`                              |
| Генериране на изображения | ✅         | `/v1/images/generations`                      |
| Аудио (TTS/STT)           | ✅         | `/v1/audio/*`                                 |
| обмен на токени OAuth     | ✅         | Решава `unsupported_country_region_territory` |
| Тестове за връзка         | ✅         | Бутонът "Тест на връзката" използва прокси    |
| Опресняване на токена     | ✅         | Фоново подновяване OAuth                      |
| Синхронизиране на модела  | ✅         | Изброяване и откриване на модели              |

---

## Прокси регистър (CRUD)

Прокси регистърът е SQLite таблица (`proxy_registry`), която съхранява всички ваши проксита. Всеки прокси има:

| Поле       | Тип        | Описание                                                 |
| ---------- | ---------- | -------------------------------------------------------- |
| `id`       | UUID       | Уникален идентификатор                                   |
| `name`     | низ        | Четим от човека етикет                                   |
| `type`     | низ        | Протокол: `http`, `https`, `socks5`                      |
| `host`     | низ        | Прокси име на хост или IP                                |
| `port`     | Цяло число | Номер на порт                                            |
| `username` | низ        | Потребителско име за удостоверяване (криптирано в покой) |
| `password` | низ        | Парола за удостоверяване (криптирана в покой)            |
| `region`   | низ        | Етикет за географски регион                              |
| `notes`    | низ        | Бележки със свободен текст                               |
| `status`   | низ        | `active` или `inactive`                                  |
| `source`   | низ        | `manual` или `oneproxy`                                  |

### Създаване на прокси

**Чрез таблото за управление:**

1. Отидете на** Настройки → прокси**
2. Кликнете** Добавете прокси**
3. Попълнете типа, хоста, порта и опционалните идентификационни данни за удостоверяване
4. Запазване

**Чрез API:**

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

### Актуализиране на прокси

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Забележка:** Идентификационните данни се запазват, освен ако изрично не изпратите непразни замени. Изпращането на празни низове за `username`/`password` ще запази съхранените стойности.

### Изтриване на прокси

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Обявяване на проксита

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Присвояване на проксита към обхвати

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

### Разрешаване на ефективен прокси

Проверете кой прокси ще се използва за дадена връзка:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Връща разрешеното прокси с неговото ниво (`account`, `provider` или `global`) и източник.

### Групово възлагане

Задайте едно прокси към множество доставчици или връзки едновременно:

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

Прокситата са включени в**Backup/Restore** система. Когато експортирате вашата OmniRoute конфигурация:

1. Отидете на** Табло за управление → Настройки → Архивиране**
2. Кликнете** Експортиране** — прокси регистър и задания са включени
3. За да възстановите, щракнете** Импортиране** и качете архивния файл

Прокси регистърът също поддържа** upsert от хост + порт** — ако импортирате прокси, което вече съществува (същия хост и порт), той се актуализира, вместо да създава дубликат.

### Наследена миграция

Ако сте конфигурирали проксита в по-стара версия (предварителен регистър), OmniRoute автоматично ги мигрира:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Това се случва веднъж при първото стартиране след надграждане. Използвайте `migrateLegacyProxyConfigToRegistry({ force: true })` за повторно изпълнение.

---

## 1proxy Безплатен прокси пазар

> 🆕** Допринесе от [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Проблем [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute се интегрира с** [1 прокси](https://1proxy-api.aitradepulse.com)** платформа на общността, до която да осигурите достъп** стотици безплатни, валидирани проксита** от цял свят. Това е идеално за потребители, които нямат собствена прокси инфраструктура.

### Как работи

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Синхр** — OmniRoute извлича валидирани проксита от 1proxy API
2. **Магазин** — Прокситата се записват в същата `proxy_registry` таблица със `source = 'oneproxy'`
3. **Филтър** — Филтриране по протокол, държава, качествен рейтинг
4. **Завъртете** — Изберете най-доброто прокси, като използвате качествени, произволни или последователни стратегии
5. **Автоматично разграждане** — Неуспешните проксита получават намален резултат за качество; под прага → маркиран като неактивен

### Синхронизиране на проксита

**Чрез таблото за управление:**

1. Отидете на** Настройки → 1прокси** раздел
2. Кликнете** „Синхронизиране сега“**
3. Преглед на статистика: общо проксита, активен брой, средно качество, разбивка по държави

**Чрез API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Филтриране на проксита

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

### Прокси качествени оценки

Всеки прокси 1proxy идва с метаданни:

| Поле            | Описание                                  |
| --------------- | ----------------------------------------- |
| `qualityScore`  | 0-100 рейтинг от 1прокси валидиране       |
| `latencyMs`     | Измерено забавяне на мрежата              |
| `anonymity`     | `transparent`, `anonymous` или `elite`    |
| `googleAccess`  | Дали проксито има достъп до Google услуги |
| `countryCode`   | Двубуквен ISO код на държавата            |
| `lastValidated` | Времево клеймо на последното валидиране   |

Резултатите за качество се коригират динамично:

- **Неуспешни заявки** намали резултата с 10 точки
- **Резултатът пада до ≤ 10** → проксито е отбелязано като `inactive`
- Неактивните прокси сървъри се изключват от ротация

### Стратегии за ротация

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

### Прекъсвач

1proxy sync има вграден прекъсвач:

- след** 5 последователни грешки при синхронизиране** , по-нататъшните опити за синхронизиране са блокирани
- Нулирайте с: `resetOneproxyCircuitBreaker()` или рестартирайте сървъра
- Състоянието на синхронизиране е налично в `GET /api/settings/oneproxy?action=status`

### Изчистване на 1proxy проксита

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Анти-откриване и стелт

OmniRoute не просто насочва трафика през прокси — а прави трафика да изглежда легитимен:

### TLS Подправяне на пръстови отпечатъци

Използва `wreq-js` за генериране на TLS пръстови отпечатъци, подобни на браузъра, заобикаляйки системите за откриване на ботове, които маркират TLS ръкостискания без браузър.

### CLI съпоставяне на пръстови отпечатъци

The**CLI Превключване на пръстови отпечатъци** (`Settings → Security`) пренарежда HTTP заглавките и полетата на тялото JSON, за да съответстват на точния подпис на естествените двоични файлове CLI (Claude код, Codex и т.н.). Това работи** на върха на** проксито:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Получавате и двете**IP маскиране** и** поискайте автентичност** едновременно.

### Запазване на прокси IP

Цветно кодирани значки в таблото за управление показват кое прокси ниво е активно:

| Значка | Ниво      | Значение                                         |
| ------ | --------- | ------------------------------------------------ |
| 🟢     | Глобален  | Целият трафик минава през този прокси            |
| 🟡     | Доставчик | Само трафикът на този доставчик е прокси         |
| 🔵     | Връзка    | Този специфичен key/account използва този прокси |

Значката също така показва разрешения прокси IP за проверка.

---

## Прокси режими нагоре по веригата

За доставчици, които използват модела CLIProxyAPI, OmniRoute поддържа три режима на прокси нагоре:

| Режим         | Описание                                                               |
| ------------- | ---------------------------------------------------------------------- |
| `native`      | OmniRoute обработва директно прокси маршрутизирането (по подразбиране) |
| `cliproxyapi` | Делегира към външен CLIProxyAPI екземпляр                              |
| `fallback`    | Първо опитва родния, връща се към CLIProxyAPI                          |

Конфигуриране на доставчик:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Табло UI

### Настройки → Прокси раздел

- **Глобален прокси** конфигурация (зададена веднъж за целия трафик)
- **Прокси за всеки доставчик** отменя
- **Прокси за всяка връзка** задачи
- **Тест за свързване** чрез конфигуриран прокси
- **Цветно кодирани значки** показва активно ниво на прокси

### Настройки → 1прокси раздел

- **Синхронизиране сега** бутон за извличане на безплатни проксита
- **Карти със статистика** : Общо, Активно, Средно качество, Последна синхронизация
- **Филтри** : Протокол, Код на държавата, Минимално качество
- **Прокси таблица** с хост, протокол, държава, качествен рейтинг, латентност, анонимност, Google достъп
- **Състояние на синхронизиране** панел с success/failure проследяване и последователен брой грешки
- **Изчистване на всички** за да премахнете всички 1прокси записи

---

## справка API

### Настройки на прокси API

| Метод    | Крайна точка                                   | Описание                                          |
| -------- | ---------------------------------------------- | ------------------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Вземете пълна конфигурация на прокси сървъра      |
| `GET`    | `/api/settings/proxy?level=global`             | Вземете глобален прокси                           |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Вземете прокси на доставчика                      |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Разрешете ефективен прокси                        |
| `PUT`    | `/api/settings/proxy`                          | Актуализиране на конфигурацията на прокси сървъра |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Премахване на прокси на ниво                      |

### Прокси регистър API

| Метод    | Крайна точка                                      | Описание                        |
| -------- | ------------------------------------------------- | ------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Избройте всички пълномощници    |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Вземете прокси чрез ID          |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Получаване на прокси назначения |
| `POST`   | `/api/v1/management/proxies`                      | Създайте прокси                 |
| `PATCH`  | `/api/v1/management/proxies`                      | Актуализиране на прокси         |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Изтриване на прокси             |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Принудително изтриване          |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Групово присвояване             |
| `GET`    | `/api/v1/management/proxies/assignments`          | Списък със задачи               |
| `GET`    | `/api/v1/management/proxies/health`               | Прокси здравни статистики       |

### Тунели API

За излагане на вашия OmniRoute екземпляр на публичния интернет (Cloudflare/ngrok/Tailscale) вместо изходящ маршрут през прокси, вижте [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Тунелът REST API живее под `/api/tunnels/{cloudflared,ngrok,tailscale}/*` и е ортогонален на изходящата прокси верига, документирана по-горе.

### 1 прокси API

| Метод    | Крайна точка                           | Описание                                                  |
| -------- | -------------------------------------- | --------------------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Избройте 1 прокси проксита                                |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Получаване на статистика за състояние на синхронизиране + |
| `GET`    | `/api/settings/oneproxy?action=status` | Получаване само на състояние на синхронизиране            |
| `POST`   | `/api/settings/oneproxy`               | Синхронизиране на задействане                             |
| `POST`   | `/api/settings/oneproxy/rotate`        | Завъртете към следващия прокси                            |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Изтрийте едно                                             |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Изчисти всички                                            |

### Прокси API нагоре

| Метод    | Крайна точка                      | Описание                                           |
| -------- | --------------------------------- | -------------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Вземете конфигурация на прокси сървъра нагоре      |
| `PUT`    | `/api/upstream-proxy/:providerId` | Задайте режим на прокси сървър нагоре              |
| `DELETE` | `/api/upstream-proxy/:providerId` | Премахнете конфигурацията на прокси сървъра нагоре |

---

## Променливи на средата

| Променлива            | По подразбиране | Описание                                                                           |
| --------------------- | --------------- | ---------------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`          | Активирайте поддръжката на SOCKS5 прокси (по подразбиране `true` в `.env.example`) |

---

## Отстраняване на неизправности

### "SOCKS5 проксито е деактивирано"

Задайте `ENABLE_SOCKS5_PROXY=true` във вашия `.env` файл и рестартирайте.

### грешки "socket hang up" чрез прокси

Това е нормално при евтини проксита, които прекъсват неактивните връзки. OmniRoute вече обработва това чрез:

- Деактивиране на поддържането на активност при прокси връзки (`keepAliveTimeout: 1`)
- Деактивиране на конвейера (`pipelining: 0`)
- Кеширане на диспечери, за да се избегнат повтарящи се ръкостискания

Ако продължава, опитайте с различен прокси или използвайте функцията за ротация на 1прокси.

### "unsupported_country_region_territory" по време OAuth

Уверете се, че проксито е конфигурирано** преди** стартиране на OAuth потока. OmniRoute маршрутизира обмена OAuth токени през конфигурирания прокси. Първо задайте глобален или прокси на ниво доставчик, след което се свържете.

### Проксито не се използва

Проверете реда на разрешаване:

1. Потвърдете с `GET /api/settings/proxy?resolve=your-connection-id`
2. Проверете дали проксито `status` е `active` (не `inactive`)
3. Уверете се, че обхватът на присвояване на прокси сървър съответства на вашата връзка

### 1 прокси синхронизирането е неуспешно

Проверете състоянието на синхронизиране:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Ако `consecutiveFailures >= 5`, прекъсвачът се е задействал. Рестартирайте сървъра, за да нулирате, или изчакайте ръчно нулиране.

---

## Схема на база данни

### Таблица `proxy_registry`

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

### Таблица `proxy_assignments`

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

## Проверка на изправността на прокси (v3.8.16 +)

OmniRoute** прокси бърз отказ** механизъм (`src/lib/proxyHealth.ts`) открива мъртви проксита в < 2s чрез бърза проверка на TCP връзката, след което** кешира резултата** за да избегнете допълнителни разходи за всяка заявка.

### Как работи

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

Без това мъртъв прокси ще блокира всяка заявка за пълната `PROXY_TIMEOUT_MS` (по подразбиране 30s), преди да се провали.

### Регулируеми променливи на средата

| Променлива                   | По подразбиране | Цел                                             |
| ---------------------------- | --------------- | ----------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`          | изчакване на TCP връзка за проверка на здравето |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`         | Колко време се кешира здравен резултат          |

**Препоръчителни стойности:**

| Сценарий                                   | Време за изчакване при бърз отказ | Кеш TTL | Разсъждение                                                                      |
| ------------------------------------------ | --------------------------------- | ------- | -------------------------------------------------------------------------------- |
| API шлюз с висока пропускателна способност | 1500ms                            | 60000ms | Агресивен отказоустойчив, по-дълъг кеш за намаляване на проверките               |
| Георазпределени възли                      | 3000ms                            | 15000ms | По-бавните мрежи се нуждаят от повече време; по-кратък кеш за бързо преодоляване |
| Dev / тестване                             | 1000ms                            | 10000ms | Бърза итерация на локални проксита                                               |
| Стелт / анти-откриване                     | 2500ms                            | 45000ms | Избягвайте бързото сондиране, което може да предизвика ограничения на скоростта  |

### Проверка на прокси здравето

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Флагът `stale` е `true`, когато записът в кеша е надвишил `HEALTH_CACHE_TTL_MS` и следващата заявка ще задейства нова проверка.

### Настройки по подразбиране за тип прокси

Проверката на здравето използва разумни настройки по подразбиране въз основа на схемата URL :

| Схема                      | Порт по подразбиране |
| -------------------------- | -------------------- |
| `http://`                  | 8080                 |
| `https://`                 | 443                  |
| `socks5://` / `socks5h://` | 1080                 |

Персонализираните портове в URL (`http://host:9999`) винаги имат предимство пред схемата по подразбиране.

---

## Прокси анализ и наблюдаемост

OmniRoute проследява използването на прокси сървър, за да помогне на операторите да диагностицират модели на маршрутизиране, пикове на латентност и повтарящи се грешки.

### Какво се проследява

За всяка заявка през конфигуриран прокси OmniRoute записва:

| Метрика      | Описание                                                                |
| ------------ | ----------------------------------------------------------------------- |
| `proxy_url`  | Пълен прокси URL (с маскирани идентификационни данни за удостоверяване) |
| `provider`   | Доставчик нагоре по веригата ID (openai, anthropic и т.н.)              |
| `latency_ms` | Общо време за отиване и връщане, включително ръкостискане на прокси     |
| `connect_ms` | TCP само време за свързване                                             |
| `status`     | HTTP код на състоянието от нагоре                                       |
| `error`      | Клас на грешка, ако заявката е неуспешна                                |
| `timestamp`  | ISO 8601 UTC                                                            |

### Достъп до данните

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Истинската крайна точка е `/api/usage/proxy-logs` (вижте `src/app/api/usage/proxy-logs/route.ts`). Тази крайна точка поддържа:

- `GET /api/usage/proxy-logs` — извлича прокси регистрационни файлове
- `DELETE /api/usage/proxy-logs` — изчистване на всички прокси регистрационни файлове

Обобщената статистика може да бъде поискана директно от таблицата `proxy_logs` чрез SQL, ако е необходимо. Таблото за управление UI може да предлага обобщени изгледи.

### Често срещани модели

**Откриване на плъзгащ се прокси** (редува се между success/failure):

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

**Намерете бавни проксита** (p95 латентност > 2s):

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

## Дърво на решения за ротационна стратегия

Когато няколко прокси сървъра са присвоени на обхват, OmniRoute използва a** ротационна стратегия** за да изберете кой да използвате за всяка заявка. Стратегията се конфигурира на ниво обхват (глобално, на доставчик, на акаунт, на комбинация).

### Налични стратегии

| Стратегия                   | Кога да използвате                           | Компромис                                                                       |
| --------------------------- | -------------------------------------------- | ------------------------------------------------------------------------------- |
| `quality` (по подразбиране) | Производство с проксита със смесено качество | Предпочита пълномощници с висок рейтинг; могат да гладуват тези с нисък рейтинг |
| `random`                    | Разпределение на товара, поверителност       | Равномерно разпределение; игнорира качествени сигнали                           |
| `sequential`                | Дебъгване, детерминистично тестване          | Цикли през проксита в ред; лесно за разсъждение                                 |

### Дърво на решенията

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

## Автоматично изключване на грешки за вашите собствени проксита

Пазарният пул 1proxy вече автоматично влошава неуспешните проксита самостоятелно (вижте [Качествени резултати на прокси](#proxy-quality-scores) ). За пълномощници** вие** добавен към регистъра, планировчикът на изправност на заден план (`src/lib/proxyHealth/scheduler.ts`) предоставя същото поведение „автоматично изключване на мъртъв член от веригата“, без да изтрива нищо:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Как се вписва във верига с множество прокси сървъри:

1. Планировчикът проверява всеки регистриран прокси на всеки `PROXY_HEALTH_INTERVAL_MS` (по подразбиране 10 минути; минимум 1 минута).
2. След `PROXY_AUTO_REMOVE_AFTER` последователно** убедителен** грешки (реална грешка на връзката — изчакване или собственият 5xx на целта на сондата никога не се отчита, вижте [Проверка на изправността на прокси](#proxy-health-checking-v3816) ), `status` на проксито е настроен на `dead`.
3. `dead` е едно от състоянията, които филтърът за активен статус, използван от резолюцията pool/rotation изключва, така че ротацията на обхвата (кръгла / произволна / лепкава / латентност — вижте [Дървото на решенията на стратегията за ротация](#rotation-strategy-decision-tree) ) незабавно спира предаването на този прокси на нови заявки. Никакви други прокси сървъри в пула не са засегнати и целият пул никога не се връща безшумно към директна връзка — вижте [4-нивовата защита на затворената при отказ прокси система](#4-level-proxy-system).
4. Планировчикът продължава да проучва `dead` проксита на същия интервал. Следващата успешна сонда обръща `status` обратно към `active` и той отново влиза в ротация — не е необходимо ръчно повторно добавяне.

Това е умишлено** включване и неразрушителен** : по подразбиране планировчикът само брои и регистрира грешки (вижте политика C в `decision.ts`), а `PROXY_AUTO_DISABLE` никога не изтрива ред — за което служи отделният, по-агресивен `PROXY_AUTO_REMOVE` флаг. Ако и двете са настроени на `true`, `PROXY_AUTO_REMOVE` печели (прокси, което предстои да бъде изтрито, няма полза от меко дезактивиране между тях). Вижте препратката към [Environment Config](../reference/ENVIRONMENT.md) за пълния списък с променливи.

---

> 📖** Свързана документация:**
>
> - [Ръководство за потребителя](../guides/USER_GUIDE.md) — Обща настройка и конфигурация - [API Справочник](../reference/API_REFERENCE.md) — Пълна API документация - [Конфигуриране на среда](../reference/ENVIRONMENT.md) — Всички променливи на средата
