# 🌐 OmniRoute Proxy Guide (Українська)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Обходьте географічні блокування, захищайте свою особу та направляйте трафік AI через будь-який проксі-сервер — без складності налаштування.**

OmniRoute містить повнофункціональну систему керування проксі-серверами, яка дозволяє маршрутизувати вихідний трафік постачальника AI через проксі-сервери HTTP, HTTPS або SOCKS5. Незалежно від того, чи перебуваєте ви в заблокованому регіоні, потребуєте ротації IP або бажаєте сховати відбитки пальців — цей посібник охоплює все.

---

## Зміст

- [Навіщо використовувати проксі?](#why-use-proxies)
- [Огляд архітектури](#architecture-overview)
- [4-рівнева система проксі](#4-level-proxy-system)
- [Реєстр проксі (CRUD)](#proxy-registry-crud)
- [1proxy Free Marketplace](#1proxy-free-proxy-marketplace)
- [Ротація проксі](#proxy-rotation)
- [Антивиявлення та стелс](#anti-detection--stealth)
- [Режими висхідного проксі](#upstream-proxy-modes)
- [Приладова панель UI](#dashboard-ui)
- [Довідник API](#api-reference)
- [Змінні середовища](#environment-variables)
- [Усунення несправностей](#troubleshooting)

---

## Навіщо використовувати проксі?

Багато провайдерів AI обмежують доступ за географічним регіоном. Розробники в** Росія, Китай, Іран, Куба, Туреччина** та інші країни стикаються з такими помилками:

```
unsupported_country_region_territory
```

Навіть за межами заблокованих регіонів проксі корисні для:

| Випадок використання   | опис                                                                  |
| ---------------------- | --------------------------------------------------------------------- |
| **Географічний обхід** | Доступ до OpenAI, Anthropic, Codex, Copilot із заблокованих країн     |
| **обертання IP**       | Розподіліть запити між кількома IPs, щоб уникнути обмеження швидкості |
| **Конфіденційність**   | Приховайте свій справжній IP від провайдерів, що працюють вище        |
| **Відповідність**      | Маршрут руху через певні юрисдикції                                   |
| **Тестування**         | Імітація запитів з різних регіонів                                    |

---

## Огляд архітектури

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

### Ключові компоненти

| компонент                 | Файл                                         | Роль                                                       |
| ------------------------- | -------------------------------------------- | ---------------------------------------------------------- |
| **Реєстр проксі**         | `src/lib/db/proxies.ts`                      | CRUD для записів проксі + призначення області              |
| **Проксі-диспетчер**      | `open-sse/utils/proxyDispatcher.ts`          | Створює диспетчери `undici` ProxyAgent/SOCKS із кешуванням |
| **Проксі Fetch**          | `open-sse/utils/proxyFetch.ts`               | Обертає `fetch()` за допомогою проксі-диспетчера           |
| **Налаштування маршруту** | `src/app/api/settings/proxy/route.ts`        | Застаріла конфігурація проксі API (GET/PUT/DELETE)         |
| **Маршрут управління**    | `src/app/api/v1/management/proxies/route.ts` | Реєстр CRUD API (GET/POST/PATCH/DELETE)                    |
| **1 проксі DB**           | `src/lib/db/oneproxy.ts`                     | Постійність ринку безкоштовних проксі-серверів             |

---

## Стандартний стан проксі для нових облікових записів

в** Налаштування → Проксі → Глобальна конфігурація** , використання** Увімкнути проксі за замовчуванням для нових підключень** щоб вибрати початковий стан проксі для щойно доданих облікових записів постачальників.

Нове налаштування контролює початковий стан проксі-сервера щойно доданих облікових записів постачальників. Він не змінює існуючі облікові записи та не замінює глобальний перемикач проксі. Його початкове значення зберігає попередню поведінку. Вимкніть його один раз, щоб у майбутньому створювати облікові записи з вимкненим проксі-сервером за замовчуванням.

Параметри зберігаються як `defaultNewConnectionProxyEnabled` через наявні налаштування API. За замовчуванням встановлено `true` якщо ніколи не зберігається. Збереження `false` набуває чинності для наступних нових облікових записів без перезапуску. `POST /api/providers` приймає необов'язковий суворий логічний `proxyEnabled`; явний `true` або `false` має пріоритет над значенням за замовчуванням створення. Пропуск повторного облікового запису або повторне підключення OAuth зберігає збережений стан цього облікового запису. Окремі облікові записи можна буде ввімкнути або вимкнути пізніше.

Вибіркові передачі постачальників використовують параметри цільової інсталяції за замовчуванням для нових облікових записів і зберігають цільову політику під час заміни існуючих облікових записів. Перемикачі проксі не є переносними полями передачі. Повне відновлення резервної копії та історична міграція JSON/SQL зберігають свою існуючу семантику відновлення, включаючи збережені значення облікового запису та стандартні налаштування застарілої схеми; повне відновлення налаштувань також може відновити це налаштування.

Це налаштування не призначає проксі-сервер і не встановлює, що він справний чи використовується. Фактична маршрутизація все ще залежить від глобального перемикача проксі та відповідної конфігурації проксі. Синтетичні постачальники без постійного облікового запису, трафік OAuth до створення облікового запису, проксі-сервери environment/system і зовнішні серверні мережі не входять до його сфери.

## 4-рівнева система проксі

OmniRoute підтримує налаштування проксі на** чотири незалежні області** , вирішено в першочерговому порядку:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Як працює дозвіл

Коли OmniRoute надсилає запит постачальнику вищестоящого потоку, він викликає `resolveProxyForConnectionFromRegistry()`, який перевіряє кожен рівень по порядку:

1. **Рівень облікового запису** — Чи є проксі, призначений для цього конкретного підключення ID?
2. **Рівень провайдера** — Чи є проксі, призначений цьому провайдеру (наприклад, `openai`)?
3. **Глобальний рівень** — Чи налаштовано глобальний проксі?
4. **Немає проксі** — Пряме підключення до провайдера.

Перший матч виграє. Це означає, що ви можете встановити глобальний проксі як запасний, але замінити його для певних постачальників або з’єднань.

### Що отримує проксі

| Тип трафіку          | Проксі-сервер? | Примітки                                            |
| -------------------- | -------------- | --------------------------------------------------- |
| Завершення чату      | ✅             | Усі запити `/v1/chat/completions`                   |
| Вбудовування         | ✅             | `/v1/embeddings`                                    |
| Генерація зображення | ✅             | `/v1/images/generations`                            |
| Аудіо (TTS/STT)      | ✅             | `/v1/audio/*`                                       |
| біржа токенів OAuth  | ✅             | Розв’язує `unsupported_country_region_territory`    |
| Тести підключення    | ✅             | Кнопка «Перевірити підключення» використовує проксі |
| Оновлення маркера    | ✅             | Фонове оновлення OAuth                              |
| Синхронізація моделі | ✅             | Перелік моделей і відкриття                         |

---

## Реєстр проксі (CRUD)

Реєстр проксі — це таблиця SQLite (`proxy_registry`), у якій зберігаються всі ваші проксі. Кожен проксі має:

| Поле       | Тип        | опис                                                          |
| ---------- | ---------- | ------------------------------------------------------------- |
| `id`       | UUID       | Унікальний ідентифікатор                                      |
| `name`     | Рядок      | Зрозуміла етикетка                                            |
| `type`     | Рядок      | Протокол: `http`, `https`, `socks5`                           |
| `host`     | Рядок      | Ім'я хоста проксі або IP                                      |
| `port`     | Ціле число | Номер порту                                                   |
| `username` | Рядок      | Ім'я користувача авторизації (зашифроване в стані споживання) |
| `password` | Рядок      | Пароль авторизації (зашифрований у стані спокою)              |
| `region`   | Рядок      | Мітка географічного регіону                                   |
| `notes`    | Рядок      | Нотатки з довільним текстом                                   |
| `status`   | Рядок      | `active` або `inactive`                                       |
| `source`   | Рядок      | `manual` або `oneproxy`                                       |

### Створення проксі

**Через інформаційну панель:**

1. Перейти до** Налаштування проксі →**
2. Натисніть** Додати проксі**
3. Заповніть тип, хост, порт і додаткові облікові дані авторизації
4. зберегти

**Через API:**

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

### Оновлення проксі

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Примітка:** Облікові дані зберігаються, якщо ви явно не надішлете непорожні заміни. Надсилання порожніх рядків для `username`/`password` збереже збережені значення.

### Видалення проксі

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Лістинг проксі

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Призначення проксі для областей

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

### Вирішення ефективного проксі

Перевірте, який проксі використовуватиметься для даного з’єднання:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Повертає дозволений проксі-сервер із його рівнем (`account`, `provider` або `global`) і джерелом.

### Масове призначення

Призначте один проксі кільком провайдерам або підключенням одночасно:

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

Проксі включені в**Backup/Restore** система. Під час експорту конфігурації OmniRoute :

1. Перейти до** Інформаційна панель → Налаштування → Резервне копіювання**
2. Натисніть** Експорт** реєстр проксі — та призначення включені
3. Щоб відновити, натисніть** Імпорт** і завантажте файл резервної копії

Реєстр проксі також підтримує** upsert портом + хоста** — якщо ви імпортуєте проксі, який уже існує (той самий хост і порт), він оновлюється замість створення дубліката.

### Міграція у спадок

Якщо ви налаштували проксі-сервери в старішій версії (перед реєстрацією), OmniRoute автоматично їх перенесе:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Це відбувається один раз під час першого запуску після оновлення. Використовуйте `migrateLegacyProxyConfigToRegistry({ force: true })` для повторного запуску.

---

## 1proxy Free Proxy Marketplace

> 🆕** Надав [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (проблема [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute інтегрується з** [1 проксі](https://1proxy-api.aitradepulse.com)** платформа спільноти, до якої можна надати доступ** сотні безкоштовних перевірених проксі-серверів** з усього світу. Це ідеально підходить для користувачів, які не мають власної інфраструктури проксі.

### Як це працює

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Синхронізувати** — OmniRoute отримує перевірені проксі з 1proxy API
2. **Магазин** Проксі — зберігаються в одній таблиці `proxy_registry` із `source = 'oneproxy'`
3. **фільтр** — Фільтрувати за протоколом, країною, показником якості
4. **Обертати** — Виберіть найкращий проксі-сервер за допомогою якісних, випадкових або послідовних стратегій
5. **Автоматична деградація** — Показник якості невдалих проксі-серверів знижується; нижче порогу → позначено як неактивне

### Синхронізація проксі

**Через інформаційну панель:**

1. Перейти до** Налаштування → 1proxy** вкладка
2. Натисніть** "Синхронізувати зараз"**
3. Перегляд статистики: загальна кількість проксі-серверів, активна кількість, середня якість, розподіл за країнами

**Через API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Фільтрація проксі

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

### Проксі-показники якості

Кожен проксі-сервер 1proxy постачається з метаданими:

| Поле            | опис                                           |
| --------------- | ---------------------------------------------- |
| `qualityScore`  | Рейтинг 0-100 з перевірки 1проксі              |
| `latencyMs`     | Виміряна затримка мережі                       |
| `anonymity`     | `transparent`, `anonymous` або `elite`         |
| `googleAccess`  | Чи може проксі отримати доступ до служб Google |
| `countryCode`   | Двобуквений код країни ISO                     |
| `lastValidated` | Мітка часу останньої перевірки                 |

Показники якості динамічно коригуються:

- **Невдалі запити** знизити оцінку на 10 балів
- **Оцінка знижується до ≤ 10** Проксі → позначено `inactive`
- Неактивні проксі виключаються з ротації

### Стратегії ротації

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

### Автоматичний вимикач

1proxy sync має вбудований автоматичний вимикач:

- після** 5 послідовних помилок синхронізації** , подальші спроби синхронізації блокуються
- Скинути за допомогою: `resetOneproxyCircuitBreaker()` або перезапустити сервер
- Статус синхронізації доступний на `GET /api/settings/oneproxy?action=status`

### Очищення проксі 1proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Антивиявлення та стелс

OmniRoute не просто направляє трафік через проксі — він робить трафік легітимним:

### Підробка відбитків пальців TLS

Використовує `wreq-js` для створення відбитків пальців TLS, подібних до браузера, в обхід систем виявлення ботів, які позначають небраузерні рукостискання TLS.

### Зіставлення відбитків пальців CLI

The** Перемикач відбитків пальців CLI** (`Settings → Security`) змінює порядок заголовків HTTP і полів тіла JSON, щоб точно відповідати сигнатурі рідних двійкових файлів CLI (код Claude, Codex тощо). Це працює** на вершині** проксі:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Ви отримуєте обидва**IP маскування** і** запит автентичності** одночасно.

### Збереження проксі IP

Кольорові значки на інформаційній панелі показують, який рівень проксі активний:

| Бейдж | Рівень      | Значення                                           |
| ----- | ----------- | -------------------------------------------------- |
| 🟢    | Глобальний  | Через цей проксі йде весь трафік                   |
| 🟡    | Провайдер   | Тільки трафік цього провайдера проксі              |
| 🔵    | Підключення | Цей конкретний key/account використовує цей проксі |

Значок також показує дозволений проксі-сервер IP для перевірки.

---

## Режими висхідного проксі

Для провайдерів, які використовують шаблон CLIProxyAPI, OmniRoute підтримує три режими висхідного проксі:

| Режим         | опис                                                                     |
| ------------- | ------------------------------------------------------------------------ |
| `native`      | OmniRoute безпосередньо обробляє маршрутизацію проксі (за замовчуванням) |
| `cliproxyapi` | Делегує зовнішній екземпляр CLIProxyAPI                                  |
| `fallback`    | Спершу пробує рідну систему, потім повертається до CLIProxyAPI           |

Налаштувати для кожного постачальника:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Приладова панель UI

### Налаштування вкладки проксі →

- **Глобальний проксі** конфігурація (встановлюється один раз для всього трафіку)
- **Проксі-сервер для кожного постачальника** перевизначає
- **Проксі для кожного з'єднання** завдання
- **Тест підключення** через налаштований проксі
- **Кольорові значки** показ активного рівня проксі

### Налаштування вкладки → 1proxy

- **Синхронізувати зараз** кнопку для отримання безкоштовних проксі
- **Картки статистики** : Загальна, Активна, Середня якість, Остання синхронізація
- **Фільтри** : протокол, код країни, мінімальна якість
- **Таблиця проксі** з хостом, протоколом, країною, показником якості, затримкою, анонімністю, доступом Google
- **Статус синхронізації** панель із відстеженням success/failure та кількістю послідовних відмов
- **Очистити все** щоб видалити всі записи 1proxy

---

## Довідник API

### Налаштування проксі API

| метод    | Кінцева точка                                  | опис                               |
| -------- | ---------------------------------------------- | ---------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Отримати повну конфігурацію проксі |
| `GET`    | `/api/settings/proxy?level=global`             | Отримати глобальний проксі         |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Отримати проксі провайдера         |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Вирішити ефективний проксі         |
| `PUT`    | `/api/settings/proxy`                          | Оновіть конфігурацію проксі        |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Видалити проксі на рівні           |

### Реєстр проксі API

| метод    | Кінцева точка                                     | опис                         |
| -------- | ------------------------------------------------- | ---------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Перерахувати всі проксі      |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Отримати проксі через ID     |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Отримайте призначення проксі |
| `POST`   | `/api/v1/management/proxies`                      | Створити проксі              |
| `PATCH`  | `/api/v1/management/proxies`                      | Оновити проксі               |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Видалити проксі              |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Примусове видалення          |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Масове призначення           |
| `GET`    | `/api/v1/management/proxies/assignments`          | Список завдань               |
| `GET`    | `/api/v1/management/proxies/health`               | Проксі-статистика здоров'я   |

### Тунелі API

Щоб отримати доступ до загальнодоступного Інтернету ( OmniRoute ) замість маршрутизації через проксі-сервер, див Cloudflare/ngrok/Tailscale[TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). Тунель REST API знаходиться під `/api/tunnels/{cloudflared,ngrok,tailscale}/*` і є ортогональним вихідному проксі-ланцюжку, задокументованому вище.

### 1 проксі API

| метод    | Кінцева точка                          | опис                                      |
| -------- | -------------------------------------- | ----------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Список 1 проксі-проксі                    |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Отримати статистику стану синхронізації + |
| `GET`    | `/api/settings/oneproxy?action=status` | Отримати лише статус синхронізації        |
| `POST`   | `/api/settings/oneproxy`               | Тригер синхронізації                      |
| `POST`   | `/api/settings/oneproxy/rotate`        | Перейти до наступного проксі              |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Видалити одну                             |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Очистити все                              |

### Вихідний проксі API

| метод    | Кінцева точка                     | опис                                         |
| -------- | --------------------------------- | -------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Отримати вихідну конфігурацію проксі-сервера |
| `PUT`    | `/api/upstream-proxy/:providerId` | Налаштуйте режим проксі-сервера              |
| `DELETE` | `/api/upstream-proxy/:providerId` | Видаліть конфігурацію проксі-сервера         |

---

## Змінні середовища

| змінна                | За замовчуванням | опис                                                                         |
| --------------------- | ---------------- | ---------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`           | Увімкнути підтримку проксі SOCKS5 (за замовчуванням `true` у `.env.example`) |

---

## Усунення несправностей

### "проксі SOCKS5 вимкнено"

Встановіть `ENABLE_SOCKS5_PROXY=true` у файлі `.env` і перезапустіть.

### помилки "сокет зависання" через проксі

Це нормально для дешевих проксі-серверів, які розривають неактивні з’єднання. OmniRoute вже обробляє це:

- Вимкнення підтримки активності на проксі-з’єднаннях (`keepAliveTimeout: 1`)
- Вимкнення конвеєрної обробки (`pipelining: 0`)
- Кешування диспетчерів, щоб уникнути повторних рукостискань

Якщо це не зникне, спробуйте інший проксі або скористайтеся функцією ротації 1proxy.

### "unsupported_country_region_territory" під час OAuth

Переконайтеся, що проксі налаштовано** раніше** запуск потоку OAuth. OmniRoute направляє обмін маркерами OAuth через налаштований проксі. Спочатку встановіть глобальний або проксі-сервер на рівні постачальника, а потім підключіться.

### Проксі не використовується

Перевірте порядок вирішення:

1. Перевірити за допомогою `GET /api/settings/proxy?resolve=your-connection-id`
2. Перевірте, чи проксі `status` є `active` (а не `inactive`)
3. Переконайтеся, що область призначення проксі-сервера відповідає вашому з’єднанню

### Помилка синхронізації 1 проксі

Перевірте стан синхронізації:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Якщо `consecutiveFailures >= 5`, спрацював автоматичний вимикач. Перезапустіть сервер, щоб скинути налаштування, або зачекайте ручного скидання.

---

## Схема бази даних

### Таблиця `proxy_registry`

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

### Таблиця `proxy_assignments`

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

## Перевірка справності проксі (v3.8.16 +)

OmniRoute** швидкий збій проксі** механізм (`src/lib/proxyHealth.ts`) виявляє мертві проксі-сервери в < 2s за допомогою швидкої перевірки з’єднання TCP, а потім** кешує результат** щоб уникнути накладних витрат на запит.

### Як це працює

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

Без цього непрацюючий проксі-сервер блокував би всі запити на повний `PROXY_TIMEOUT_MS` (за замовчуванням 30 с) перед тим, як вийти з ладу.

### Настроювані змінні середовища

| змінна                       | За замовчуванням | призначення                                           |
| ---------------------------- | ---------------- | ----------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`           | тайм-аут підключення TCP для перевірки працездатності |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`          | Як довго кешується результат здоров’я                 |

**Рекомендовані значення:**

| Сценарій                              | Тайм-аут швидкої помилки | Кешувати TTL | Міркування                                                                                    |
| ------------------------------------- | ------------------------ | ------------ | --------------------------------------------------------------------------------------------- |
| Шлюз API високої пропускної здатності | 1500 мс                  | 60000 мс     | Агресивний безвідмовний, довший кеш для зменшення перевірок                                   |
| Георозподілені вузли                  | 3000 мс                  | 15000 мс     | Повільніші мережі потребують більше часу; коротший кеш для швидкого відновлення після відмови |
| Розробка / тестування                 | 1000 мс                  | 10000 мс     | Швидка ітерація на локальних проксі                                                           |
| Стелс / антивиявлення                 | 2500 мс                  | 45000 мс     | Уникайте швидкого зондування, яке може викликати обмеження швидкості                          |

### Перевірка здоров'я проксі

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

Прапор `stale` має значення `true`, коли запис кешу перевищує `HEALTH_CACHE_TTL_MS`, і наступний запит ініціює нову перевірку.

### Тип проксі за замовчуванням

Перевірка працездатності використовує розумні значення за замовчуванням на основі схеми URL :

| Схема                      | Порт за замовчуванням |
| -------------------------- | --------------------- |
| `http://`                  | 8080                  |
| `https://`                 | 443                   |
| `socks5://` / `socks5h://` | 1080                  |

Користувальницькі порти в URL (`http://host:9999`) завжди мають пріоритет над типовою схемою.

---

## Проксі-аналітика та спостереження

OmniRoute відстежує використання кожного проксі-сервера, щоб допомогти операторам діагностувати шаблони маршрутизації, стрибки затримки та повторювані збої.

### Що відстежується

Для кожного запиту через налаштований проксі OmniRoute записує:

| Метрика      | опис                                                                      |
| ------------ | ------------------------------------------------------------------------- |
| `proxy_url`  | Повний проксі-сервер URL (із замаскованими обліковими даними авторизації) |
| `provider`   | Вихідний провайдер ID (openai, anthropic тощо)                            |
| `latency_ms` | Загальний час проходження туди й назад, включаючи рукостискання проксі    |
| `connect_ms` | лише час підключення TCP                                                  |
| `status`     | код статусу HTTP з висхідного каналу                                      |
| `error`      | Клас помилки, якщо запит не виконано                                      |
| `timestamp`  | ISO 8601 UTC                                                              |

### Доступ до даних

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

Справжньою кінцевою точкою є `/api/usage/proxy-logs` (див. `src/app/api/usage/proxy-logs/route.ts`). Ця кінцева точка підтримує:

- `GET /api/usage/proxy-logs` — отримати журнали проксі
- `DELETE /api/usage/proxy-logs` — очистити всі журнали проксі

За потреби сукупну статистику можна запитувати безпосередньо з таблиці `proxy_logs` через SQL. Інформаційна панель UI може пропонувати зведені перегляди.

### Загальні шаблони

**Виявлення махового проксі** (чергує success/failure):

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

**Знайдіть повільні проксі** (затримка p95 > 2 с):

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

## Дерево рішень стратегії ротації

Якщо для однієї області призначено кілька проксі-серверів, OmniRoute використовує a** стратегія ротації** щоб вибрати, який використовувати для кожного запиту. Стратегія налаштовується на рівні масштабу (глобальний, для кожного постачальника, для кожного облікового запису, для кожного комбо).

### Доступні стратегії

| Стратегія                    | Коли використовувати                         | Компроміс                                                                                           |
| ---------------------------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| `quality` (за замовчуванням) | Виробництво з проксі-серверами різної якості | Віддає перевагу проксі-серверам з високим рейтингом; можуть голодувати тих, хто має низький рейтинг |
| `random`                     | Розподіл навантаження, конфіденційність      | Рівномірний розподіл; ігнорує сигнали якості                                                        |
| `sequential`                 | Налагодження, детерміноване тестування       | Циклічний цикл через проксі-сервери по порядку; легко міркувати                                     |

### Дерево рішень

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

## Автоматичне виключення збоїв для ваших власних проксі

Пул ринкового майданчика 1proxy вже самостійно автоматично знижує несправні проксі (див. [Показники якості проксі](#proxy-quality-scores) ). Для довірених осіб** ти** доданий до реєстру, фоновий планувальник працездатності (`src/lib/proxyHealth/scheduler.ts`) забезпечує таку саму поведінку «автоматично виключити мертвого учасника з ланцюга», не видаляючи нічого:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Як це вписується в багатопроксі-ланцюг:

1. Планувальник перевіряє кожен зареєстрований проксі кожну `PROXY_HEALTH_INTERVAL_MS` (за замовчуванням 10 хвилин; мінімум 1 хвилина).
2. Після `PROXY_AUTO_REMOVE_AFTER` поспіль** остаточний** збої (справжня помилка з’єднання — таймаут або власний 5xx цільового зонда ніколи не зараховується, див. [Перевірка працездатності проксі](#proxy-health-checking-v3816) ), `status` проксі встановлено на `dead`.
3. `dead` є одним із статусів, які виключає фільтр статусу живого, який використовується роздільною здатністю pool/rotation, тому ротація області (циклічна / випадкова / липка / затримка — див. [Дерево рішень стратегії ротації](#rotation-strategy-decision-tree) ) негайно припиняє передавати цей проксі новим запитам. Ніякі інші проксі-сервери в пулі не зачіпаються, і весь пул ніколи мовчки не повертається до прямого з’єднання — дивіться [4-рівневу систему захисту проксі-серверів](#4-level-proxy-system) від збоїв.
4. Планувальник продовжує перевірку проксі `dead` з однаковим інтервалом. Наступний успішний зонд повертає `status` назад до `active`, і він знову входить до обертання — повторне додавання вручну не потрібне.

Це свідомо** вибірковий і неруйнівний** : за замовчуванням планувальник лише підраховує та реєструє помилки (див. політику C у `decision.ts`), а `PROXY_AUTO_DISABLE` ніколи не видаляє рядок —, для чого призначений окремий, більш агресивний прапор `PROXY_AUTO_REMOVE`. Якщо для обох встановлено значення `true`, виграє `PROXY_AUTO_REMOVE` (проксі-сервер, який збирається видалити, не потребує м’якого вимкнення між ними). Повний список змінних див. у довіднику [Environment Config](../reference/ENVIRONMENT.md).

---

> 📖** Пов'язана документація:**
>
> - [Посібник користувача](../guides/USER_GUIDE.md) — Загальне налаштування та конфігурація - [API Reference](../reference/API_REFERENCE.md) — Повна документація API - [Environment Config](../reference/ENVIRONMENT.md) — Усі змінні середовища
