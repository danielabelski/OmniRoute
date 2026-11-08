# 🌐 OmniRoute Proxy Guide (فارسی)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **بلوک های جغرافیایی را دور بزنید، از هویت خود محافظت کنید و ترافیک AI را از طریق هر پروکسی — با پیچیدگی پیکربندی صفر هدایت کنید.**

OmniRoute شامل یک سیستم مدیریت پراکسی با امکانات کامل است که به شما امکان میدهد ترافیک ارائهدهنده AI بالادست را از طریق پراکسیهای HTTP، HTTPS یا SOCKS5 هدایت کنید. چه در یک منطقه مسدود شده باشید، چه نیاز به چرخش IP داشته باشید، یا بخواهید اثرانگشت مخفیانه — را داشته باشید، این راهنما همه چیز را پوشش می دهد.

---

## فهرست مطالب

- [چرا از پروکسی ها استفاده کنیم؟](#why-use-proxies)
- [نمای کلی معماری](#architecture-overview)
- [سیستم پروکسی 4 سطحی](#4-level-proxy-system)
- [رجیستری پروکسی (CRUD)](#proxy-registry-crud)
- [1پروکسی بازار آزاد](#1proxy-free-proxy-marketplace)
- [چرخش پروکسی](#proxy-rotation)
- [ضد تشخیص و پنهان کاری](#anti-detection--stealth)
- [حالت های پروکسی بالادست](#upstream-proxy-modes)
- [داشبورد UI](#dashboard-ui)
- [مرجع API](#api-reference)
- [متغیرهای محیطی](#environment-variables)
- [عیب یابی](#troubleshooting)

---

## چرا از پروکسی ها استفاده کنیم؟

بسیاری از ارائه دهندگان AI دسترسی را بر اساس منطقه جغرافیایی محدود می کنند. توسعه دهندگان در** روسیه، چین، ایران، کوبا، ترکیه** ، و کشورهای دیگر با خطاهایی مانند:

```
unsupported_country_region_territory
```

حتی در خارج از مناطق مسدود شده، پراکسی ها برای موارد زیر مفید هستند:

| استفاده از مورد       | توضیحات                                                                   |
| --------------------- | ------------------------------------------------------------------------- |
| **کنارگذر جغرافیایی** | از کشورهای مسدود شده OpenAI، Anthropic، Codex، Copilot دسترسی داشته باشید |
| **چرخش IP**           | برای جلوگیری از محدودیت نرخ، درخواست ها را در چند IPs توزیع کنید          |
| **حریم خصوصی**        | IP واقعی خود را از ارائه دهندگان بالادست پنهان کنید                       |
| **انطباق**            | ترافیک را از طریق حوزه های قضایی خاص هدایت کنید                           |
| **تست کردن**          | شبیه سازی درخواست ها از مناطق مختلف                                       |

---

## نمای کلی معماری

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

### اجزای کلیدی

| جزء                    | فایل                                         | نقش                                                                     |
| ---------------------- | -------------------------------------------- | ----------------------------------------------------------------------- |
| **رجیستری پروکسی**     | `src/lib/db/proxies.ts`                      | CRUD برای ورودی های پروکسی اختصاصات دامنه +                             |
| **توزیع کننده پروکسی** | `open-sse/utils/proxyDispatcher.ts`          | توزیع کننده های `undici` ProxyAgent/SOCKS را با ذخیره سازی ایجاد می کند |
| **واکشی پروکسی**       | `open-sse/utils/proxyFetch.ts`               | `fetch()` با تزریق پراکسی دیسپاچر پیچیده می کند                         |
| **مسیر تنظیمات**       | `src/app/api/settings/proxy/route.ts`        | پیکربندی پروکسی قدیمی API (GET/PUT/DELETE)                              |
| **مسیر مدیریت**        | `src/app/api/v1/management/proxies/route.ts` | رجیستری CRUD API (GET/POST/PATCH/DELETE)                                |
| **1پروکسی DB**         | `src/lib/db/oneproxy.ts`                     | تداوم بازار پروکسی رایگان                                               |

---

## حالت پروکسی پیشفرض برای حسابهای جدید

در** تنظیمات → Proxy → پیکربندی جهانی** ، استفاده کنید** پروکسی را به طور پیش فرض برای اتصالات جدید فعال کنید** برای انتخاب وضعیت پراکسی اولیه حساب های ارائه دهنده جدید اضافه شده.

تنظیم جدید وضعیت پروکسی اولیه حساب های ارائه دهنده جدید اضافه شده را کنترل می کند. این حساب های موجود را تغییر نمی دهد یا سوئیچ پروکسی جهانی را جایگزین نمی کند. مقدار اولیه آن رفتار قبلی را حفظ می کند. برای ایجاد حسابهای آینده با غیرفعال بودن پروکسی، یک بار آن را خاموش کنید.

اولویت به عنوان `defaultNewConnectionProxyEnabled` از طریق تنظیمات موجود API ذخیره می شود. زمانی که هرگز ذخیره نشود روی `true` پیشفرض میشود. ذخیره `false` برای حساب های جدید بعدی بدون راه اندازی مجدد اعمال می شود. `POST /api/providers` یک `proxyEnabled` بولی سخت اختیاری را می پذیرد. یک `true` یا `false` صریح بر پیشفرض ایجاد اولویت دارد. حذف یک حساب تکراری یا اتصال مجدد OAuth وضعیت ذخیره شده آن حساب را حفظ می کند. حسابهای فردی همچنان میتوانند بعد از آن فعال یا غیرفعال شوند.

انتقالهای ارائهدهنده انتخابی از پیشفرض نصب مقصد برای حسابهای جدید استفاده میکند و خطمشی مقصد را هنگام جایگزینی حسابهای موجود حفظ میکند. کلیدهای پراکسی فیلدهای انتقال قابل حمل نیستند. بازیابی کامل پشتیبان و مهاجرت تاریخی JSON/SQL ، معنای بازیابی موجود خود را حفظ میکنند، از جمله مقادیر ذخیرهشده حساب و پیشفرضهای طرح قدیمی. بازیابی تنظیمات کامل نیز می تواند این اولویت را بازیابی کند.

این اولویت یک پروکسی اختصاص نمیدهد یا ثابت نمیکند که یکی سالم است یا در حال استفاده است. مسیریابی واقعی همچنان به سوئیچ پراکسی جهانی و پیکربندی پراکسی قابل اجرا بستگی دارد. ارائه دهندگان مصنوعی بدون حساب ثابت، ترافیک OAuth قبل از ایجاد حساب، پراکسیهای environment/system و شبکههای پشتیبان خارجی خارج از محدوده آن هستند.

## سیستم پروکسی 4 سطحی

OmniRoute از پیکربندی پروکسی پشتیبانی می کند** چهار حوزه مستقل** ، به ترتیب اولویت حل شد:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### وضوح چگونه کار می کند

هنگامی که OmniRoute درخواستی را به یک ارائه دهنده بالادستی ارسال می کند، `resolveProxyForConnectionFromRegistry()` را فراخوانی می کند که هر سطح را به ترتیب بررسی می کند:

1. **در سطح حساب** — آیا پروکسی به این اتصال خاص ID اختصاص داده شده است؟
2. **در سطح ارائه دهنده** — آیا پروکسی به این ارائه دهنده اختصاص داده شده است (مثلا `openai`)؟
3. **در سطح جهانی** — آیا یک پروکسی جهانی پیکربندی شده است؟
4. **بدون پروکسی** — اتصال مستقیم به ارائه دهنده.

اولین مسابقه برنده می شود. این بدان معناست که میتوانید یک پروکسی سراسری را بهعنوان یک جایگزین تنظیم کنید، اما آن را برای ارائهدهندگان یا اتصالات خاص لغو کنید.

### چه چیزی پروکسی می شود

| نوع ترافیک       | پروکسی؟ | یادداشت ها                                          |
| ---------------- | ------- | --------------------------------------------------- |
| تکمیل چت         | ✅      | تمام درخواست های `/v1/chat/completions`             |
| جاسازی ها        | ✅      | `/v1/embeddings`                                    |
| تولید تصویر      | ✅      | `/v1/images/generations`                            |
| صوتی (TTS/STT)   | ✅      | `/v1/audio/*`                                       |
| تبادل توکن OAuth | ✅      | `unsupported_country_region_territory` را حل می کند |
| تست های اتصال    | ✅      | دکمه "تست اتصال" از پروکسی استفاده می کند           |
| نوسازی رمز       | ✅      | تجدید پس زمینه OAuth                                |
| همگام سازی مدل   | ✅      | فهرست و کشف مدل                                     |

---

## رجیستری پروکسی (CRUD)

رجیستری پروکسی یک جدول SQLite (`proxy_registry`) است که همه پراکسی های شما را ذخیره می کند. هر پروکسی دارای:

| میدان      | تایپ کنید | توضیحات                                         |
| ---------- | --------- | ----------------------------------------------- |
| `id`       | UUID      | شناسه منحصر به فرد                              |
| `name`     | رشته      | برچسب قابل خواندن برای انسان                    |
| `type`     | رشته      | پروتکل: `http`، `https`، `socks5`               |
| `host`     | رشته      | نام میزبان پروکسی یا IP                         |
| `port`     | عدد صحیح  | شماره پورت                                      |
| `username` | رشته      | تأیید نام کاربری (رمزگذاری شده در حالت استراحت) |
| `password` | رشته      | رمز عبور تأیید (رمزگذاری شده در حالت استراحت)   |
| `region`   | رشته      | برچسب منطقه جغرافیایی                           |
| `notes`    | رشته      | یادداشت های متن آزاد                            |
| `status`   | رشته      | `active` یا `inactive`                          |
| `source`   | رشته      | `manual` یا `oneproxy`                          |

### ایجاد یک پروکسی

**از طریق داشبورد:**

1. رفتن به** تنظیمات پروکسی →**
2. کلیک کنید** پروکسی را اضافه کنید**
3. نوع، میزبان، پورت و اعتبارنامه اختیاری را پر کنید
4. ذخیره کنید

**از طریق API:**

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

### به روز رسانی یک پروکسی

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **توجه:** اعتبارنامه ها حفظ می شوند مگر اینکه به صراحت جایگزین های غیر خالی ارسال کنید. ارسال رشته های خالی برای `username`/`password` مقادیر ذخیره شده را حفظ می کند.

### حذف یک پروکسی

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### پراکسی های فهرست شده

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### اختصاص پروکسی به Scopes

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

### حل و فصل پراکسی موثر

بررسی کنید که کدام پروکسی برای یک اتصال مشخص استفاده می شود:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

پراکسی حل شده را با سطح (`account`، `provider`، یا `global`) و منبع آن برمیگرداند.

### واگذاری انبوه

یک پروکسی را به چندین ارائه دهنده یا اتصال به طور همزمان اختصاص دهید:

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

پروکسی ها در**Backup/Restore** سیستم هنگامی که پیکربندی OmniRoute خود را صادر می کنید:

1. رفتن به** تنظیمات داشبورد → پشتیبان گیری →**
2. کلیک کنید** صادرات** رجیستری پروکسی — و تکالیف گنجانده شده است
3. برای بازیابی، کلیک کنید** واردات** و فایل پشتیبان را آپلود کنید

رجیستری پروکسی نیز پشتیبانی می کند** upsert توسط پورت + میزبان** — اگر یک پروکسی را وارد کنید که از قبل وجود دارد (همان میزبان و پورت)، به جای ایجاد یک تکراری، به روز می شود.

### مهاجرت میراث

اگر پروکسیها را در نسخه قدیمیتر (پیشرجیستری) پیکربندی کردهاید، OmniRoute بهطور خودکار آنها را منتقل میکند:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

این یک بار در اولین راه اندازی پس از ارتقا اتفاق می افتد. `migrateLegacyProxyConfigToRegistry({ force: true })` برای اجرای مجدد استفاده کنید.

---

## 1پروکسی بازار پراکسی رایگان

> 🆕** ارائه شده توسط [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (مسئله [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute با ادغام می شود** [1 پروکسی](https://1proxy-api.aitradepulse.com)** پلت فرم جامعه برای ارائه دسترسی به** صدها پروکسی رایگان و معتبر** از سراسر جهان این برای کاربرانی که زیرساخت پروکسی خود را ندارند عالی است.

### چگونه کار می کند

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **همگام سازی** — OmniRoute پراکسی های تایید شده را از 1proxy API واکشی می کند
2. **فروشگاه** پروکسی های — در همان جدول `proxy_registry` با `source = 'oneproxy'` ذخیره می شوند
3. **فیلتر کنید** — فیلتر بر اساس پروتکل، کشور، امتیاز کیفیت
4. **چرخش** — بهترین پروکسی را با استفاده از استراتژی های با کیفیت، تصادفی یا متوالی انتخاب کنید
5. **تخریب خودکار** پروکسی های ناموفق — نمره کیفیت خود را کاهش می دهند. زیر آستانه → غیرفعال علامت گذاری شد

### همگام سازی پراکسی ها

**از طریق داشبورد:**

1. رفتن به** تنظیمات → 1proxy** برگه
2. کلیک کنید** "اکنون همگام سازی"**
3. مشاهده آمار: کل پراکسی ها، تعداد فعال، کیفیت متوسط، تفکیک کشوری

**از طریق API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### فیلتر کردن پروکسی ها

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

### نمرات کیفیت پروکسی

هر پروکسی 1پروکسی همراه با ابرداده است:

| میدان           | توضیحات                                                            |
| --------------- | ------------------------------------------------------------------ |
| `qualityScore`  | امتیاز 0-100 از اعتبار سنجی 1پراکسی                                |
| `latencyMs`     | تأخیر شبکه اندازه گیری شده                                         |
| `anonymity`     | `transparent`، `anonymous`، یا `elite`                             |
| `googleAccess`  | اینکه آیا پروکسی می تواند به خدمات Google دسترسی داشته باشد یا خیر |
| `countryCode`   | کد کشور دو حرفی ISO                                                |
| `lastValidated` | مهر زمانی آخرین اعتبارسنجی                                         |

امتیازهای کیفیت به صورت پویا تنظیم می شوند:

- **درخواست های ناموفق** امتیاز را 10 امتیاز کاهش دهید
- **امتیاز به ≤ 10 کاهش می یابد** پروکسی → با علامت `inactive` مشخص شده است
- پراکسی های غیرفعال از چرخش حذف می شوند

### استراتژی های چرخش

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

### مدار شکن

1proxy sync دارای یک مدار شکن داخلی است:

- بعد از** 5 شکست متوالی همگام سازی** ، تلاش های بیشتر برای همگام سازی مسدود شده است
- بازنشانی با: `resetOneproxyCircuitBreaker()` یا راه اندازی مجدد سرور
- وضعیت همگام سازی در `GET /api/settings/oneproxy?action=status` در دسترس است

### پاک کردن 1 پروکسی

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## ضد تشخیص و پنهان کاری

OmniRoute فقط ترافیک را از طریق یک پروکسی — هدایت نمی کند، بلکه باعث می شود ترافیک قانونی به نظر برسد:

### جعل اثر انگشت TLS

`wreq-js` برای ایجاد اثرانگشت TLS مانند مرورگر استفاده میکند و سیستمهای تشخیص ربات را که دست دادن TLS غیر مرورگر را علامتگذاری میکنند، دور میزند.

### تطبیق اثر انگشت CLI

را** تعویض اثر انگشت CLI** (`Settings → Security`) سرصفحههای HTTP و فیلدهای بدنه JSON را برای مطابقت با امضای دقیق باینریهای اصلی CLI (کد Claude ، Codex و غیره) دوباره ترتیب میدهد. این کار می کند** در بالای** پروکسی:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

شما هر دو را دریافت می کنید** ماسک زدن IP** و** درخواست اصالت** به طور همزمان

### حفظ پروکسی IP

نشانهای رنگی در داشبورد نشان میدهند که کدام سطح پراکسی فعال است:

| نشان | سطح         | معنی                                             |
| ---- | ----------- | ------------------------------------------------ |
| 🟢   | جهانی       | تمام ترافیک از طریق این پروکسی انجام می شود      |
| 🟡   | ارائه دهنده | فقط ترافیک این ارائه دهنده پروکسی است            |
| 🔵   | اتصال       | این key/account خاص از این پروکسی استفاده می کند |

نشان همچنین پروکسی حل شده IP برای تأیید نشان می دهد.

---

## حالت های پروکسی بالادست

برای ارائه دهندگانی که از الگوی CLIProxyAPI استفاده می کنند، OmniRoute از سه حالت پروکسی بالادستی پشتیبانی می کند:

| حالت          | توضیحات                                                      |
| ------------- | ------------------------------------------------------------ |
| `native`      | OmniRoute مستقیماً مسیریابی پروکسی را کنترل می کند (پیش فرض) |
| `cliproxyapi` | نمایندگان به یک نمونه CLIProxyAPI خارجی                      |
| `fallback`    | ابتدا بومی را امتحان می کند، به CLIProxyAPI برمی گردد        |

پیکربندی هر ارائه دهنده:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## داشبورد UI

### تنظیمات تب پروکسی →

- **پروکسی جهانی** پیکربندی (تنظیم یک بار برای تمام ترافیک)
- **پروکسی هر ارائه دهنده** لغو می کند
- **پروکسی هر اتصال** تکالیف
- **تست اتصال** از طریق پروکسی پیکربندی شده
- **نشان های رنگی** نمایش سطح پراکسی فعال

### تنظیمات → 1proxy

- **اکنون همگام سازی کنید** دکمه برای واکشی پراکسی های رایگان
- **کارت های آمار** : مجموع، فعال، کیفیت متوسط، آخرین همگام سازی
- **فیلترها** : پروتکل، کد کشور، حداقل کیفیت
- **جدول پروکسی** با میزبان، پروتکل، کشور، امتیاز کیفیت، تأخیر، ناشناس بودن، دسترسی Google
- **وضعیت همگام سازی** پانل با ردیابی success/failure و تعداد خرابی های متوالی
- **پاک کردن همه** برای حذف همه 1 ورودی های پراکسی

---

## مرجع API

### تنظیمات پروکسی API

| روش      | نقطه پایانی                                    | توضیحات                             |
| -------- | ---------------------------------------------- | ----------------------------------- |
| `GET`    | `/api/settings/proxy`                          | پیکربندی کامل پروکسی را دریافت کنید |
| `GET`    | `/api/settings/proxy?level=global`             | دریافت پروکسی جهانی                 |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | دریافت پروکسی ارائه دهنده           |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | پروکسی موثر را حل کنید              |
| `PUT`    | `/api/settings/proxy`                          | پیکربندی پروکسی را به روز کنید      |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | حذف پروکسی در سطح                   |

### پروکسی رجیستری API

| روش      | نقطه پایانی                                       | توضیحات               |
| -------- | ------------------------------------------------- | --------------------- |
| `GET`    | `/api/v1/management/proxies`                      | لیست تمام پراکسی ها   |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | دریافت پروکسی توسط ID |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | دریافت تکالیف پروکسی  |
| `POST`   | `/api/v1/management/proxies`                      | ایجاد پروکسی          |
| `PATCH`  | `/api/v1/management/proxies`                      | به روز رسانی پروکسی   |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | حذف پروکسی            |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | حذف اجباری            |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | تخصیص انبوه           |
| `GET`    | `/api/v1/management/proxies/assignments`          | لیست تکالیف           |
| `GET`    | `/api/v1/management/proxies/health`               | آمار سلامت پروکسی     |

### تونل های API

برای نمایش نمونه OmniRoute خود در اینترنت عمومی (Cloudflare/ngrok/Tailscale) به جای مسیریابی خروجی از طریق یک پروکسی، به [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) مراجعه کنید. تونل REST API در زیر `/api/tunnels/{cloudflared,ngrok,tailscale}/*` زندگی می کند و متعامد به زنجیره پراکسی خروجی مستند شده در بالا است.

### 1پروکسی API

| روش      | نقطه پایانی                            | توضیحات                                |
| -------- | -------------------------------------- | -------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | 1 پراکسی را فهرست کنید                 |
| `GET`    | `/api/settings/oneproxy?action=stats`  | وضعیت همگام سازی آمار + را دریافت کنید |
| `GET`    | `/api/settings/oneproxy?action=status` | فقط وضعیت همگامسازی را دریافت کنید     |
| `POST`   | `/api/settings/oneproxy`               | همگام سازی ماشه                        |
| `POST`   | `/api/settings/oneproxy/rotate`        | چرخش به پراکسی بعدی                    |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | یکی را حذف کنید                        |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | پاک کردن همه                           |

### پروکسی بالادست API

| روش      | نقطه پایانی                       | توضیحات                                |
| -------- | --------------------------------- | -------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | پیکربندی پروکسی بالادست را دریافت کنید |
| `PUT`    | `/api/upstream-proxy/:providerId` | حالت پروکسی بالادست را تنظیم کنید      |
| `DELETE` | `/api/upstream-proxy/:providerId` | پیکربندی پروکسی بالادست را حذف کنید    |

---

## متغیرهای محیطی

| متغیر                 | پیش فرض | توضیحات                                                               |
| --------------------- | ------- | --------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`  | فعال کردن پشتیبانی از پروکسی SOCKS5 (پیشفرض `true` در `.env.example`) |

---

## عیب یابی

### "پراکسی SOCKS5 غیرفعال است"

`ENABLE_SOCKS5_PROXY=true` در فایل `.env` خود تنظیم کرده و مجددا راه اندازی کنید.

### خطاهای "سوکت قطع کردن" از طریق پروکسی

این با پراکسی های ارزان قیمتی که اتصالات بیکار را رها می کنند طبیعی است. OmniRoute قبلاً این کار را توسط:

- غیرفعال کردن نگه داشتن زنده در اتصالات پراکسی (`keepAliveTimeout: 1`)
- غیرفعال کردن خط لوله (`pipelining: 0`)
- ذخیره سازی دیسپچرها برای جلوگیری از دست دادن های مکرر

اگر ادامه داشت، پروکسی دیگری را امتحان کنید یا از ویژگی چرخش 1پروکسی استفاده کنید.

### "unsupported_country_region_territory" در طول OAuth

مطمئن شوید که پروکسی پیکربندی شده است** قبل از** شروع جریان OAuth. OmniRoute تبادل توکن OAuth را از طریق پروکسی پیکربندی شده هدایت می کند. ابتدا یک پروکسی سراسری یا در سطح ارائه دهنده تنظیم کنید، سپس متصل شوید.

### پروکسی استفاده نمی شود

ترتیب رزولوشن را بررسی کنید:

1. با `GET /api/settings/proxy?resolve=your-connection-id` تأیید کنید
2. بررسی کنید که آیا پروکسی `status` `active` است (نه `inactive`)
3. اطمینان حاصل کنید که محدوده تخصیص پروکسی با اتصال شما مطابقت دارد

### 1همگام سازی پراکسی انجام نشد

وضعیت همگام سازی را بررسی کنید:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

اگر `consecutiveFailures >= 5`، قطع کننده مدار قطع شده است. سرور را برای بازنشانی راه اندازی مجدد کنید یا منتظر تنظیم مجدد دستی باشید.

---

## طرحواره پایگاه داده

### جدول `proxy_registry`

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

### جدول `proxy_assignments`

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

## بررسی سلامت پروکسی (نسخه 3.8.16 +)

OmniRoute** پراکسی سریع شکست** مکانیزم (`src/lib/proxyHealth.ts`) پراکسی های مرده را در < 2s از طریق بررسی سریع اتصال TCP شناسایی می کند، سپس** نتیجه را ذخیره می کند** برای جلوگیری از سربار هر درخواست

### چگونه کار می کند

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

بدون این، یک پروکسی مرده هر درخواست برای `PROXY_TIMEOUT_MS` کامل (30s پیش فرض) را قبل از شکست مسدود می کند.

### متغیرهای محیطی قابل تنظیم

| متغیر                        | پیش فرض | هدف                                               |
| ---------------------------- | ------- | ------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | توقف زمان اتصال TCP در هر بررسی سلامت             |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | چه مدت یک نتیجه سلامت در حافظه پنهان ذخیره می شود |

**مقادیر توصیه شده:**

| سناریو                          | مهلت زمانی شکست سریع | کش TTL          | استدلال                                                                       |
| ------------------------------- | -------------------- | --------------- | ----------------------------------------------------------------------------- |
| دروازه API با توان عملیاتی بالا | 1500 میلیثانیه       | 60000 میلیثانیه | حافظه نهان تهاجمی سریع و طولانی تر برای کاهش چک ها                            |
| گره های جغرافیایی توزیع شده     | 3000 میلیثانیه       | 15000 میلیثانیه | شبکه های کندتر به زمان بیشتری نیاز دارند. حافظه پنهان کوتاه تر برای شکست سریع |
| توسعه دهنده / آزمایش            | 1000 میلیثانیه       | 10000 میلیثانیه | تکرار سریع در پراکسی های محلی                                                 |
| مخفی کاری / ضد تشخیص            | 2500 میلیثانیه       | 45000 میلیثانیه | از کاوش سریع که میتواند باعث ایجاد محدودیتهای نرخ شود، خودداری کنید           |

### بازرسی سلامت پروکسی

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

هنگامی که ورودی حافظه پنهان `HEALTH_CACHE_TTL_MS` بیشتر باشد، پرچم `stale` `true` است و درخواست بعدی یک بررسی جدید را آغاز می کند.

### پیش فرض های نوع هر پروکسی

بررسی سلامت از پیش فرض های معقولی بر اساس طرح URL استفاده می کند:

| طرح                        | پورت پیش فرض |
| -------------------------- | ------------ |
| `http://`                  | 8080         |
| `https://`                 | 443          |
| `socks5://` / `socks5h://` | 1080         |

پورت های سفارشی در URL (`http://host:9999`) همیشه بر پیش فرض طرح اولویت دارند.

---

## تجزیه و تحلیل پروکسی و قابلیت مشاهده

OmniRoute استفاده به ازای هر پروکسی را ردیابی می کند تا به اپراتورها در تشخیص الگوهای مسیریابی، افزایش تاخیر و خرابی های مکرر کمک کند.

### آنچه ردیابی می شود

برای هر درخواست از طریق یک پروکسی پیکربندی شده، OmniRoute ثبت می کند:

| متریک        | توضیحات                                            |
| ------------ | -------------------------------------------------- |
| `proxy_url`  | پروکسی کامل URL (با اعتبارنامه های نقاب دار)       |
| `provider`   | ارائه دهنده بالادست ID (openai، anthropic، و غیره) |
| `latency_ms` | کل زمان رفت و برگشت شامل دست دادن پروکسی           |
| `connect_ms` | فقط زمان اتصال TCP                                 |
| `status`     | کد وضعیت HTTP از بالادست                           |
| `error`      | کلاس خطا در صورت عدم موفقیت درخواست                |
| `timestamp`  | ISO 8601 UTC                                       |

### دسترسی به داده ها

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

نقطه پایان واقعی `/api/usage/proxy-logs` است (به `src/app/api/usage/proxy-logs/route.ts` مراجعه کنید). این نقطه پایانی پشتیبانی می کند:

- `GET /api/usage/proxy-logs` — لاگ های پروکسی را بازیابی کنید
- `DELETE /api/usage/proxy-logs` — تمام لاگ های پروکسی را پاک کنید

در صورت نیاز میتوان آمار کل را مستقیماً از جدول `proxy_logs` از طریق SQL جستجو کرد. داشبورد UI ممکن است نماهای جمعی ارائه دهد.

### الگوهای رایج

**یک پروکسی در حال حرکت را شناسایی کنید** (متناوب بین success/failure):

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

**پراکسی های کند را پیدا کنید** (تاخیر p95 > 2s):

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

## درخت تصمیم گیری استراتژی چرخش

هنگامی که چندین پراکسی به یک scope اختصاص داده می شود، OmniRoute از a استفاده می کند** استراتژی چرخش** انتخاب کنید که برای هر درخواست از کدام یک استفاده کنید. استراتژی در سطح دامنه (جهانی، هر ارائه دهنده، هر حساب، هر ترکیبی) پیکربندی شده است.

### استراتژی های موجود

| استراتژی           | زمان استفاده                    | معامله کردن                                                                           |
| ------------------ | ------------------------------- | ------------------------------------------------------------------------------------- |
| `quality` (پیشفرض) | تولید با پروکسی با کیفیت ترکیبی | از پروکسی های با رتبه بالا حمایت می کند. ممکن است افراد دارای رتبه پایین گرسنگی بکشند |
| `random`           | توزیع بار، حریم خصوصی           | توزیع یکنواخت؛ سیگنال های کیفیت را نادیده می گیرد                                     |
| `sequential`       | اشکال زدایی، آزمایش قطعی        | چرخه از طریق پراکسی به ترتیب. آسان برای استدلال                                       |

### درخت تصمیم

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

## حذف خودکار شکست برای پراکسی های خودتان

استخر 1proxy marketplace در حال حاضر به تنهایی پراکسی های ناموفق را به طور خودکار تنزل می دهد ( [نمرات کیفیت پروکسی را](#proxy-quality-scores) ببینید). برای پروکسی ها** شما** برنامهریز سلامت پسزمینه (`src/lib/proxyHealth/scheduler.ts`) که به رجیستری اضافه شده است، همان رفتار «حذف یک عضو مرده از زنجیره بهطور خودکار» را بدون حذف چیزی ارائه میکند:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

نحوه قرار گرفتن آن در یک زنجیره چند پروکسی:

1. زمانبند هر پروکسی ثبتشده را هر `PROXY_HEALTH_INTERVAL_MS` بررسی میکند (پیشفرض 10 دقیقه؛ حداقل 1 دقیقه).
2. پس از `PROXY_AUTO_REMOVE_AFTER` متوالی** قطعی** خرابی ها (یک شکست واقعی اتصال — یک مهلت زمانی یا 5xx خود هدف کاوشگر هرگز حساب نمی شود، به [بررسی سلامت پروکسی](#proxy-health-checking-v3816) مراجعه کنید)، `status` پروکسی روی `dead` تنظیم شده است.
3. `dead` یکی از وضعیتهایی است که فیلتر وضعیت زنده استفاده شده توسط وضوح pool/rotation آن را مستثنی میکند، بنابراین چرخش یک محدوده (تصادفی / تصادفی / چسبنده / تأخیر — به [درخت تصمیمگیری استراتژی چرخش](#rotation-strategy-decision-tree) مراجعه کنید) بلافاصله تحویل آن پراکسی به درخواستهای جدید را متوقف میکند. هیچ پراکسی دیگری در استخر تحت تأثیر قرار نمیگیرد، و [کل](#4-level-proxy-system) استخر — بیصدا به یک اتصال مستقیم باز نمیگردد.
4. زمانبند به بررسی پراکسیهای `dead` در همان بازه زمانی ادامه میدهد. کاوشگر موفق بعدی `status` به `active` برمی گرداند و دوباره وارد چرخش — می شود بدون نیاز به اضافه کردن مجدد دستی.

این به عمد است** انتخابی و غیر مخرب** : بهطور پیشفرض زمانبند فقط شکستها را میشمارد و ثبت میکند (به خطمشی C در `decision.ts` مراجعه کنید)، و `PROXY_AUTO_DISABLE` هرگز یک ردیف — را حذف نمیکند که پرچم جداگانه و تهاجمیتر `PROXY_AUTO_REMOVE` برای آن است. اگر هر دو روی `true` تنظیم شده باشند، `PROXY_AUTO_REMOVE` برنده میشود (پراکسی که قرار است حذف شود، برای غیرفعال کردن نرمافزار در بین آن کاربرد ندارد). برای لیست کامل متغیرها به مرجع [تنظیمات محیطی](../reference/ENVIRONMENT.md) مراجعه کنید.

---

> 📖** مستندات مرتبط:**
>
> - [راهنمای کاربر](../guides/USER_GUIDE.md) — تنظیم و پیکربندی کلی - [API مرجع](../reference/API_REFERENCE.md) — مستندات API کامل - [تنظیمات محیطی](../reference/ENVIRONMENT.md) — همه متغیرهای محیط
