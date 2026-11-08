# 🌐 OmniRoute Proxy Guide (اردو)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **جغرافیائی بلاکس کو نظرانداز کریں، اپنی شناخت کی حفاظت کریں، اور صفر کنفیگریشن پیچیدگی کے ساتھ کسی بھی پراکسی — کے ذریعے AI ٹریفک کو روٹ کریں۔**

OmniRoute میں ایک مکمل خصوصیات والا پراکسی مینجمنٹ سسٹم شامل ہے جو آپ کو HTTP، HTTPS، یا SOCKS5 پراکسیز کے ذریعے اپ اسٹریم AI فراہم کنندہ ٹریفک کو روٹ کرنے دیتا ہے۔ چاہے آپ مسدود علاقے میں ہوں، IP گردش کی ضرورت ہو، یا اسٹیلتھ فنگر پرنٹ — چاہتے ہوں یہ گائیڈ ہر چیز کا احاطہ کرتی ہے۔

---

## مندرجات کا جدول

- [پراکسی کیوں استعمال کریں؟](#why-use-proxies)
- [فن تعمیر کا جائزہ](#architecture-overview)
- [4 لیول پراکسی سسٹم](#4-level-proxy-system)
- [پراکسی رجسٹری (CRUD)](#proxy-registry-crud)
- [1 پراکسی فری مارکیٹ پلیس](#1proxy-free-proxy-marketplace)
- [پراکسی گردش](#proxy-rotation)
- [اینٹی ڈیٹیکشن اور اسٹیلتھ](#anti-detection--stealth)
- [اپ اسٹریم پراکسی موڈز](#upstream-proxy-modes)
- [ڈیش بورڈ UI](#dashboard-ui)
- [API حوالہ](#api-reference)
- [ماحولیاتی متغیرات](#environment-variables)
- [خرابی کا سراغ لگانا](#troubleshooting)

---

## پراکسی کیوں استعمال کریں؟

بہت سے AI فراہم کرنے والے جغرافیائی علاقے کے لحاظ سے رسائی کو محدود کرتے ہیں۔ میں ڈویلپرز** روس، چین، ایران، کیوبا، ترکی** ، اور دیگر ممالک کو غلطیوں کا سامنا کرنا پڑتا ہے جیسے:

```
unsupported_country_region_territory
```

یہاں تک کہ بلاک شدہ علاقوں سے باہر، پراکسی اس کے لیے مفید ہیں:

| کیس استعمال کریں۔      | تفصیل                                                                |
| ---------------------- | -------------------------------------------------------------------- |
| **جغرافیائی بائی پاس** | مسدود ممالک سے OpenAI، Anthropic، Codex، Copilot تک رسائی حاصل کریں  |
| **IP گردش**            | شرح کو محدود کرنے سے بچنے کے لیے متعدد IPs میں درخواستیں تقسیم کریں۔ |
| **رازداری**            | اپ اسٹریم فراہم کنندگان سے اپنا اصلی IP چھپائیں۔                     |
| **تعمیل**              | مخصوص دائرہ اختیار کے ذریعے ٹریفک کو روٹ کریں۔                       |
| **ٹیسٹنگ**             | مختلف علاقوں سے درخواستوں کی تقلید کریں۔                             |

---

## فن تعمیر کا جائزہ

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

### کلیدی اجزاء

| جزو                  | فائل                                         | کردار                                                     |
| -------------------- | -------------------------------------------- | --------------------------------------------------------- |
| **پراکسی رجسٹری**    | `src/lib/db/proxies.ts`                      | پراکسی اندراجات کے لیے CRUD + اسکوپ اسائنمنٹس             |
| **پراکسی ڈسپیچر**    | `open-sse/utils/proxyDispatcher.ts`          | کیشنگ کے ساتھ `undici` ProxyAgent/SOCKS ڈسپیچرز بناتا ہے۔ |
| **پراکسی بازیافت**   | `open-sse/utils/proxyFetch.ts`               | `fetch()` پراکسی ڈسپیچر انجیکشن سے لپیٹتا ہے۔             |
| **ترتیبات کا راستہ** | `src/app/api/settings/proxy/route.ts`        | لیگیسی پراکسی تشکیل API (GET/PUT/DELETE)                  |
| **انتظامی راستہ**    | `src/app/api/v1/management/proxies/route.ts` | رجسٹری CRUD API (GET/POST/PATCH/DELETE)                   |
| **1 proxy DB**       | `src/lib/db/oneproxy.ts`                     | مفت پراکسی مارکیٹ پلیس استقامت                            |

---

## نئے اکاؤنٹس کے لیے ڈیفالٹ پراکسی حالت

میں** ترتیبات → پراکسی → گلوبل کنفیگریشن** ، استعمال کریں۔** نئے کنکشنز کے لیے بطور ڈیفالٹ پراکسی کو فعال کریں۔** نئے شامل کردہ فراہم کنندہ اکاؤنٹس کی ابتدائی پراکسی حالت کا انتخاب کرنے کے لیے۔

نئی ترتیب نئے شامل کردہ فراہم کنندہ اکاؤنٹس کی ابتدائی پراکسی حالت کو کنٹرول کرتی ہے۔ یہ موجودہ اکاؤنٹس کو تبدیل نہیں کرتا ہے یا عالمی پراکسی سوئچ کو تبدیل نہیں کرتا ہے۔ اس کی ابتدائی قدر پچھلے رویے کو محفوظ رکھتی ہے۔ بطور ڈیفالٹ غیر فعال پراکسی کے ساتھ مستقبل کے اکاؤنٹس بنانے کے لیے اسے ایک بار بند کریں۔

ترجیح موجودہ سیٹنگز API کے ذریعے `defaultNewConnectionProxyEnabled` کے بطور محفوظ کی جاتی ہے۔ جب کبھی محفوظ نہیں ہوتا ہے تو یہ `true` پر ڈیفالٹ ہوتا ہے۔ `false` محفوظ کرنا بعد کے نئے اکاؤنٹس کے لیے دوبارہ شروع کیے بغیر اثر انداز ہوتا ہے۔ `POST /api/providers` اختیاری سخت بولین `proxyEnabled` قبول کرتا ہے۔ ایک واضح `true` یا `false` تخلیق کے ڈیفالٹ پر فوقیت رکھتا ہے۔ ڈپلیکیٹ اکاؤنٹ یا OAuth دوبارہ جڑنا اس اکاؤنٹ کی ذخیرہ شدہ حالت کو محفوظ رکھتا ہے۔ انفرادی اکاؤنٹس کو بعد میں بھی فعال یا غیر فعال کیا جا سکتا ہے۔

منتخب فراہم کنندہ کی منتقلی نئے اکاؤنٹس کے لیے منزل کی تنصیب کا ڈیفالٹ استعمال کرتی ہے اور موجودہ اکاؤنٹس کو تبدیل کرتے وقت منزل کی پالیسی کو محفوظ رکھتی ہے۔ پراکسی ٹوگلز پورٹیبل ٹرانسفر فیلڈز نہیں ہیں۔ مکمل بیک اپ بحالی اور تاریخی JSON/SQL منتقلی ان کے موجودہ بحالی کے الفاظ کو برقرار رکھتی ہے، بشمول محفوظ کردہ اکاؤنٹ کی اقدار اور میراثی اسکیما ڈیفالٹس؛ مکمل ترتیبات کی بحالی اس ترجیح کو بھی بحال کر سکتی ہے۔

یہ ترجیح کسی پراکسی کو تفویض نہیں کرتی ہے یا یہ ثابت نہیں کرتی ہے کہ وہ صحت مند ہے یا استعمال میں ہے۔ اصل روٹنگ اب بھی عالمی پراکسی سوئچ اور قابل اطلاق پراکسی کنفیگریشن پر منحصر ہے۔ مستقل اکاؤنٹ کے بغیر مصنوعی فراہم کنندگان، اکاؤنٹ بنانے سے پہلے OAuth ٹریفک، environment/system پراکسی، اور بیرونی بیک اینڈز نیٹ ورکنگ اس کے دائرہ کار سے باہر ہیں۔

## 4 لیول پراکسی سسٹم

OmniRoute پراکسی کنفیگریشن کو سپورٹ کرتا ہے۔** چار آزاد دائرہ کار** ترجیحی ترتیب میں حل کیا گیا:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### ریزولوشن کیسے کام کرتا ہے۔

جب OmniRoute اپ اسٹریم فراہم کنندہ کو درخواست بھیجتا ہے، تو یہ `resolveProxyForConnectionFromRegistry()` کال کرتا ہے جو ہر سطح کو ترتیب سے چیک کرتا ہے:

1. **اکاؤنٹ کی سطح** — کیا اس مخصوص کنکشن ID کو کوئی پراکسی تفویض کی گئی ہے؟
2. **فراہم کنندہ کی سطح** — کیا اس فراہم کنندہ کو کوئی پراکسی تفویض کی گئی ہے (مثال کے طور پر، `openai`)؟
3. **عالمی سطح پر** — کیا کوئی عالمی پراکسی ترتیب دی گئی ہے؟
4. **کوئی پراکسی نہیں۔** — فراہم کنندہ سے براہ راست رابطہ۔

پہلا میچ جیت جاتا ہے۔ اس کا مطلب ہے کہ آپ عالمی پراکسی کو فال بیک کے طور پر سیٹ کر سکتے ہیں لیکن اسے مخصوص فراہم کنندگان یا کنکشنز کے لیے اوور رائیڈ کر سکتے ہیں۔

### کیا پراکسی ہو جاتا ہے

| ٹریفک کی قسم          | پراکسیڈ؟ | نوٹس                                               |
| --------------------- | -------- | -------------------------------------------------- |
| چیٹ کی تکمیل          | ✅       | تمام `/v1/chat/completions` درخواستیں۔             |
| ایمبیڈنگز             | ✅       | `/v1/embeddings`                                   |
| تصویر کی نسل          | ✅       | `/v1/images/generations`                           |
| آڈیو (TTS/STT)        | ✅       | `/v1/audio/*`                                      |
| OAuth ٹوکن کا تبادلہ  | ✅       | `unsupported_country_region_territory` حل کرتا ہے۔ |
| کنکشن ٹیسٹ            | ✅       | "ٹیسٹ کنکشن" بٹن پراکسی کا استعمال کرتا ہے۔        |
| ٹوکن ریفریش           | ✅       | پس منظر OAuth تجدید                                |
| ماڈل کی مطابقت پذیری۔ | ✅       | ماڈل کی فہرست اور دریافت                           |

---

## پراکسی رجسٹری (CRUD)

پراکسی رجسٹری ایک SQLite ٹیبل (`proxy_registry`) ہے جو آپ کے تمام پراکسیز کو محفوظ کرتی ہے۔ ہر پراکسی ہے:

| میدان      | قسم  | تفصیل                               |
| ---------- | ---- | ----------------------------------- |
| `id`       | UUID | منفرد شناخت کنندہ                   |
| `name`     | تار  | انسانی پڑھنے کے قابل لیبل           |
| `type`     | تار  | پروٹوکول: `http`، `https`، `socks5` |
| `host`     | تار  | پراکسی میزبان نام یا IP             |
| `port`     | عدد  | پورٹ نمبر                           |
| `username` | تار  | مستند صارف نام (باقی میں خفیہ کردہ) |
| `password` | تار  | تصدیقی پاس ورڈ (باقی میں خفیہ کردہ) |
| `region`   | تار  | جغرافیائی علاقہ لیبل                |
| `notes`    | تار  | مفت ٹیکسٹ نوٹ                       |
| `status`   | تار  | `active` یا `inactive`              |
| `source`   | تار  | `manual` یا `oneproxy`              |

### ایک پراکسی بنانا

**ڈیش بورڈ کے ذریعے:**

1. پر جائیں۔** → پراکسی کی ترتیبات**
2. کلک کریں۔** پراکسی شامل کریں۔**
3. قسم، میزبان، پورٹ، اور اختیاری توثیق کی اسناد کو پُر کریں۔
4. محفوظ کریں۔

**API کے ذریعے:**

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

### پراکسی کو اپ ڈیٹ کرنا

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **نوٹ:** اسناد اس وقت تک محفوظ رہتی ہیں جب تک کہ آپ واضح طور پر غیر خالی تبدیلیاں نہ بھیجیں۔ `username`/`password` کے لیے خالی تار بھیجنے سے ذخیرہ شدہ قدریں برقرار رہیں گی۔

### پراکسی کو حذف کرنا

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### فہرست سازی پراکسی

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### پراکسیوں کو دائرہ کار میں تفویض کرنا

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

### مؤثر پراکسی کو حل کرنا

چیک کریں کہ دیے گئے کنکشن کے لیے کون سی پراکسی استعمال کی جائے گی:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

حل شدہ پراکسی کو اس کی سطح (`account`, `provider`, یا `global`) اور ماخذ کے ساتھ لوٹاتا ہے۔

### بلک اسائنمنٹ

ایک ہی وقت میں متعدد فراہم کنندگان یا کنکشنز کو ایک پراکسی تفویض کریں:

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

پراکسی شامل ہیں۔**Backup/Restore** نظام جب آپ اپنی OmniRoute کنفیگریشن برآمد کرتے ہیں:

1. پر جائیں۔** ڈیش بورڈ → سیٹنگز → بیک اپ**
2. کلک کریں۔** برآمد کریں۔** — پراکسی رجسٹری اور اسائنمنٹس شامل ہیں۔
3. بحال کرنے کے لیے، کلک کریں۔** درآمد کریں۔** اور بیک اپ فائل اپ لوڈ کریں۔

پراکسی رجسٹری بھی سپورٹ کرتی ہے۔** میزبان + پورٹ کی طرف سے upsert** — اگر آپ ایک پراکسی درآمد کرتے ہیں جو پہلے سے موجود ہے (ایک ہی میزبان اور پورٹ) تو یہ ڈپلیکیٹ بنانے کے بجائے اپ ڈیٹ ہوجاتا ہے۔

### میراثی ہجرت

اگر آپ نے پرانے ورژن (پری رجسٹری) میں پراکسی کو ترتیب دیا ہے، تو OmniRoute خود بخود انہیں منتقل کر دیتا ہے:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

یہ اپ گریڈ کے بعد پہلے سٹارٹ اپ پر ایک بار ہوتا ہے۔ دوبارہ چلانے کے لیے `migrateLegacyProxyConfigToRegistry({ force: true })` استعمال کریں۔

---

## 1 پراکسی فری پراکسی مارکیٹ پلیس

> 🆕** تعاون کردہ بذریعہ [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (مسئلہ [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute کے ساتھ ضم ہوتا ہے۔** [1 پراکسی](https://1proxy-api.aitradepulse.com)** تک رسائی فراہم کرنے کے لیے کمیونٹی پلیٹ فارم** سینکڑوں مفت، توثیق شدہ پراکسیز** دنیا بھر سے یہ ان صارفین کے لیے بہترین ہے جن کا اپنا پراکسی انفراسٹرکچر نہیں ہے۔

### یہ کیسے کام کرتا ہے۔

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **مطابقت پذیری** — OmniRoute 1proxy API سے توثیق شدہ پراکسیز لاتا ہے
2. **اسٹور** — پراکسیز کو اسی `proxy_registry` ٹیبل میں `source = 'oneproxy'` کے ساتھ محفوظ کیا جاتا ہے۔
3. **فلٹر** — پروٹوکول، ملک، کوالٹی سکور کے لحاظ سے فلٹر کریں۔
4. **گھمائیں۔** — معیار، بے ترتیب، یا ترتیب وار حکمت عملیوں کا استعمال کرتے ہوئے بہترین پراکسی کا انتخاب کریں
5. **آٹو ڈیگریڈ** — ناکام پراکسی اپنے کوالٹی سکور کو کم کر دیتی ہیں۔ نیچے کی حد → غیر فعال نشان زد ہے۔

### پراکسیز کی مطابقت پذیری

**ڈیش بورڈ کے ذریعے:**

1. پر جائیں۔** → 1proxy کی ترتیبات** ٹیب
2. کلک کریں۔** "اب مطابقت پذیری کریں"**
3. اعدادوشمار دیکھیں: کل پراکسی، فعال شمار، اوسط معیار، ملک کے لحاظ سے ٹوٹ پھوٹ

**API کے ذریعے:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### پراکسیوں کو فلٹر کرنا

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

### پراکسی کوالٹی اسکورز

ہر 1 پراکسی پراکسی میٹا ڈیٹا کے ساتھ آتی ہے:

| میدان           | تفصیل                                             |
| --------------- | ------------------------------------------------- |
| `qualityScore`  | 1 پراکسی کی توثیق سے 0-100 درجہ بندی              |
| `latencyMs`     | نیٹ ورک کی تاخیر کی پیمائش کی گئی۔                |
| `anonymity`     | `transparent`، `anonymous`، یا `elite`            |
| `googleAccess`  | آیا پراکسی Google سروسز تک رسائی حاصل کر سکتی ہے۔ |
| `countryCode`   | دو حرفی ISO کنٹری کوڈ                             |
| `lastValidated` | آخری توثیق کا ٹائم اسٹیمپ                         |

معیار کے اسکور متحرک طور پر ایڈجسٹ کیے جاتے ہیں:

- **ناکام درخواستیں۔** اسکور کو 10 پوائنٹس سے کم کریں۔
- **اسکور ≤ 10 تک گر گیا۔** → پراکسی کو `inactive` نشان زد کیا گیا ہے۔
- غیر فعال پراکسیوں کو گردش سے خارج کر دیا گیا ہے۔

### گردش کی حکمت عملی

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

### سرکٹ بریکر

1proxy sync میں ایک بلٹ ان سرکٹ بریکر ہے:

- کے بعد** 5 لگاتار مطابقت پذیری کی ناکامیاں** ، مزید مطابقت پذیری کی کوششیں مسدود ہیں۔
- کے ساتھ ری سیٹ کریں: `resetOneproxyCircuitBreaker()` یا سرور کو دوبارہ شروع کریں۔
- مطابقت پذیری کی حیثیت `GET /api/settings/oneproxy?action=status` پر دستیاب ہے۔

### 1 پراکسی پراکسیوں کو صاف کرنا

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## اینٹی ڈیٹیکشن اور اسٹیلتھ

OmniRoute ٹریفک کو صرف ایک پراکسی — کے ذریعے روٹ نہیں کرتا ہے یہ ٹریفک کو جائز بناتا ہے:

### TLS فنگر پرنٹ سپوفنگ

`wreq-js` کا استعمال براؤزر جیسے TLS فنگر پرنٹس بنانے کے لیے کرتا ہے، بوٹ ڈیٹیکشن سسٹم کو نظرانداز کرتے ہوئے جو غیر براؤزر TLS ہینڈ شیکس کو جھنڈا لگاتے ہیں۔

### CLI فنگر پرنٹ میچنگ

دی**CLI فنگر پرنٹ ٹوگل** (`Settings → Security`) HTTP ہیڈر اور JSON باڈی فیلڈز کو مقامی CLI بائنریز (Claude کوڈ، Codex، وغیرہ) کے درست دستخط سے ملنے کے لیے دوبارہ ترتیب دیتا ہے۔ یہ کام کرتا ہے۔** کے اوپر** پراکسی:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

آپ دونوں کو حاصل کریں۔**IP ماسکنگ** اور** صداقت کی درخواست کریں** بیک وقت

### پراکسی IP تحفظ

ڈیش بورڈ میں کلر کوڈ والے بیجز دکھاتے ہیں کہ کون سی پراکسی لیول فعال ہے:

| بیج | سطح             | مطلب                                               |
| --- | --------------- | -------------------------------------------------- |
| 🟢  | عالمی           | تمام ٹریفک اس پراکسی سے گزرتی ہے۔                  |
| 🟡  | فراہم کرنے والا | صرف اس فراہم کنندہ کی ٹریفک پراکسی ہے۔             |
| 🔵  | کنکشن           | یہ مخصوص key/account اس پراکسی کو استعمال کرتا ہے۔ |

بیج تصدیق کے لیے حل شدہ پراکسی IP بھی دکھاتا ہے۔

---

## اپ اسٹریم پراکسی موڈز

فراہم کنندگان کے لیے جو CLIProxyAPI پیٹرن استعمال کرتے ہیں، OmniRoute تین اپ اسٹریم پراکسی طریقوں کو سپورٹ کرتا ہے:

| موڈ           | تفصیل                                                              |
| ------------- | ------------------------------------------------------------------ |
| `native`      | OmniRoute پراکسی روٹنگ کو براہ راست ہینڈل کرتا ہے (پہلے سے طے شدہ) |
| `cliproxyapi` | بیرونی CLIProxyAPI کے نمائندے                                      |
| `fallback`    | پہلے مقامی کی کوشش کرتا ہے، CLIProxyAPI پر واپس آتا ہے۔            |

فی فراہم کنندہ کو ترتیب دیں:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## ڈیش بورڈ UI

### ترتیبات → پراکسی ٹیب

- **عالمی پراکسی** ترتیب (تمام ٹریفک کے لیے ایک بار مقرر)
- **فی فراہم کنندہ پراکسی** اوور رائیڈ کرتا ہے۔
- **فی کنکشن پراکسی** اسائنمنٹس
- **کنکشن ٹیسٹ** تشکیل شدہ پراکسی کے ذریعے
- **رنگین کوڈ والے بیجز** فعال پراکسی لیول دکھا رہا ہے۔

### ترتیبات → 1proxy Tab

- **ابھی مطابقت پذیری کریں۔** مفت پراکسیز لانے کے لیے بٹن
- **اعدادوشمار کے کارڈز** : کل، فعال، اوسط معیار، آخری مطابقت پذیری۔
- **فلٹرز** : پروٹوکول، کنٹری کوڈ، کم سے کم معیار
- **پراکسی ٹیبل** میزبان، پروٹوکول، ملک، کوالٹی سکور، تاخیر، نام ظاہر نہ کرنے، Google رسائی کے ساتھ
- **مطابقت پذیری کی حیثیت** success/failure ٹریکنگ اور لگاتار ناکامی کی گنتی کے ساتھ پینل
- **تمام صاف کریں۔** تمام 1 پراکسی اندراجات کو ہٹانے کے لیے

---

## API حوالہ

### پراکسی API

| طریقہ    | اختتامی نقطہ                                   | تفصیل                         |
| -------- | ---------------------------------------------- | ----------------------------- |
| `GET`    | `/api/settings/proxy`                          | مکمل پراکسی تشکیل حاصل کریں۔  |
| `GET`    | `/api/settings/proxy?level=global`             | عالمی پراکسی حاصل کریں۔       |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | فراہم کنندہ پراکسی حاصل کریں۔ |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | مؤثر پراکسی کو حل کریں۔       |
| `PUT`    | `/api/settings/proxy`                          | پراکسی ترتیب کو اپ ڈیٹ کریں۔  |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | سطح پر پراکسی کو ہٹا دیں۔     |

### پراکسی رجسٹری API

| طریقہ    | اختتامی نقطہ                                      | تفصیل                         |
| -------- | ------------------------------------------------- | ----------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | تمام پراکسیوں کی فہرست بنائیں |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID کے ذریعے پراکسی حاصل کریں۔ |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | پراکسی اسائنمنٹس حاصل کریں۔   |
| `POST`   | `/api/v1/management/proxies`                      | پراکسی بنائیں                 |
| `PATCH`  | `/api/v1/management/proxies`                      | پراکسی کو اپ ڈیٹ کریں۔        |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | پراکسی کو حذف کریں۔           |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | زبردستی حذف کریں۔             |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | بلک تفویض                     |
| `GET`    | `/api/v1/management/proxies/assignments`          | اسائنمنٹس کی فہرست بنائیں     |
| `GET`    | `/api/v1/management/proxies/health`               | پراکسی صحت کے اعدادوشمار      |

### سرنگوں API

اپنے OmniRoute مثال کو پراکسی کے ذریعے آؤٹ باؤنڈ روٹ کرنے کے بجائے پبلک انٹرنیٹ (Cloudflare/ngrok/Tailscale) پر ظاہر کرنے کے لیے، [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) دیکھیں۔ سرنگ REST API `/api/tunnels/{cloudflared,ngrok,tailscale}/*` کے تحت رہتی ہے اور اوپر دستاویزی آؤٹ باؤنڈ پراکسی چین کے لیے آرتھوگونل ہے۔

### 1 proxy API

| طریقہ    | اختتامی نقطہ                           | تفصیل                                         |
| -------- | -------------------------------------- | --------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | 1 پراکسی پراکسیوں کی فہرست بنائیں             |
| `GET`    | `/api/settings/oneproxy?action=stats`  | اعدادوشمار + مطابقت پذیری کی حیثیت حاصل کریں۔ |
| `GET`    | `/api/settings/oneproxy?action=status` | صرف مطابقت پذیری کی حیثیت حاصل کریں۔          |
| `POST`   | `/api/settings/oneproxy`               | ٹرگر مطابقت پذیری                             |
| `POST`   | `/api/settings/oneproxy/rotate`        | اگلی پراکسی پر گھمائیں۔                       |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | ایک کو حذف کریں۔                              |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | سب صاف کریں۔                                  |

### Upstream Proxy API

| طریقہ    | اختتامی نقطہ                      | تفصیل                                 |
| -------- | --------------------------------- | ------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | اپ اسٹریم پراکسی کنفیگریشن حاصل کریں۔ |
| `PUT`    | `/api/upstream-proxy/:providerId` | اپ اسٹریم پراکسی موڈ سیٹ کریں۔        |
| `DELETE` | `/api/upstream-proxy/:providerId` | اپ اسٹریم پراکسی ترتیب کو ہٹا دیں۔    |

---

## ماحولیاتی متغیرات

| متغیر                 | طے شدہ | تفصیل                                                                 |
| --------------------- | ------ | --------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true` | SOCKS5 پراکسی سپورٹ کو فعال کریں ( `.env.example` میں ڈیفالٹ `true` ) |

---

## خرابی کا سراغ لگانا

### "SOCKS5 پراکسی غیر فعال ہے"

اپنی `.env` فائل میں `ENABLE_SOCKS5_PROXY=true` سیٹ کریں اور دوبارہ شروع کریں۔

### پراکسی کے ذریعے "ساکٹ ہینگ اپ" کی غلطیاں

سستے پراکسیوں کے ساتھ یہ معمول ہے جو بیکار کنکشن چھوڑ دیتے ہیں۔ OmniRoute پہلے ہی اس کو سنبھالتا ہے:

- پراکسی کنکشنز پر زندہ رکھنے کو غیر فعال کرنا (`keepAliveTimeout: 1`)
- پائپ لائننگ کو غیر فعال کرنا (`pipelining: 0`)
- بار بار مصافحہ سے بچنے کے لیے بھیجنے والوں کو کیش کرنا

اگر یہ برقرار رہتا ہے تو، ایک مختلف پراکسی آزمائیں یا 1proxy روٹیشن فیچر استعمال کریں۔

### OAuth کے دوران "غیر تعاون یافتہ_ملک_علاقہ_علاقہ"

یقینی بنائیں کہ پراکسی ترتیب دی گئی ہے۔** پہلے** OAuth بہاؤ شروع کرنا۔ OmniRoute کنفیگرڈ پراکسی کے ذریعے OAuth ٹوکن ایکسچینج کو روٹس کرتا ہے۔ پہلے عالمی یا فراہم کنندہ کی سطح کی پراکسی سیٹ کریں، پھر جڑیں۔

### پراکسی استعمال نہیں ہو رہی

ریزولوشن آرڈر چیک کریں:

1. `GET /api/settings/proxy?resolve=your-connection-id` سے تصدیق کریں۔
2. چیک کریں کہ آیا پراکسی `status` `active` ہے ( `inactive` نہیں)
3. یقینی بنائیں کہ پراکسی تفویض کا دائرہ آپ کے کنکشن سے ملتا ہے۔

### 1 پراکسی مطابقت پذیری ناکام ہو رہی ہے۔

مطابقت پذیری کی حیثیت کو چیک کریں:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

اگر `consecutiveFailures >= 5`، سرکٹ بریکر ٹرپ ہو گیا ہے۔ ری سیٹ کرنے کے لیے سرور کو دوبارہ شروع کریں، یا دستی ری سیٹ کا انتظار کریں۔

---

## ڈیٹا بیس اسکیما

### `proxy_registry` ٹیبل

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

### `proxy_assignments` ٹیبل

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

## پراکسی ہیلتھ چیکنگ (v3.8.16 +)

OmniRoute's** پراکسی فاسٹ فیل** میکانزم (`src/lib/proxyHealth.ts`) ایک فوری TCP کنکشن چیک کے ذریعے < 2s میں مردہ پراکسیوں کا پتہ لگاتا ہے، پھر** نتیجہ کیش کرتا ہے۔** فی درخواست اوور ہیڈ سے بچنے کے لیے۔

### یہ کیسے کام کرتا ہے۔

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

اس کے بغیر، ایک مردہ پراکسی ناکام ہونے سے پہلے مکمل `PROXY_TIMEOUT_MS` (پہلے سے طے شدہ 30s) کی ہر درخواست کو روک دے گی۔

### ٹیون ایبل ماحولیاتی متغیرات

| متغیر                        | طے شدہ  | مقصد                              |
| ---------------------------- | ------- | --------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | TCP کنکشن ٹائم آؤٹ فی ہیلتھ چیک   |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | صحت کا نتیجہ کب تک محفوظ ہوتا ہے۔ |

**تجویز کردہ اقدار:**

| منظر نامہ               | فاسٹ فیل ٹائم آؤٹ | کیشے TTL | استدلال                                                                 |
| ----------------------- | ----------------- | -------- | ----------------------------------------------------------------------- |
| ہائی تھرو پٹ API گیٹ وے | 1500ms            | 60000ms  | چیک کو کم کرنے کے لیے جارحانہ فیل-تیز، طویل کیش                         |
| جیو سے تقسیم شدہ نوڈس   | 3000ms            | 15000ms  | سست نیٹ ورکس کو زیادہ وقت درکار ہوتا ہے۔ تیز فیل اوور کے لیے چھوٹا کیشے |
| دیو/ٹیسٹنگ              | 1000ms            | 10000ms  | مقامی پراکسیوں پر فوری تکرار                                            |
| اسٹیلتھ / اینٹی ڈیٹیکشن | 2500ms            | 45000ms  | تیز رفتار تحقیقات سے گریز کریں جو شرح کی حدود کو متحرک کر سکتا ہے۔      |

### پراکسی ہیلتھ کا معائنہ کرنا

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

`stale` جھنڈا `true` ہوتا ہے جب کیشے کا اندراج `HEALTH_CACHE_TTL_MS` سے تجاوز کر جاتا ہے اور اگلی درخواست ایک نئے چیک کو متحرک کرے گی۔

### فی پراکسی قسم ڈیفالٹس

صحت کی جانچ URL اسکیم کی بنیاد پر سمجھدار ڈیفالٹس کا استعمال کرتی ہے:

| سکیم                       | ڈیفالٹ پورٹ |
| -------------------------- | ----------- |
| `http://`                  | 8080        |
| `https://`                 | 443         |
| `socks5://` / `socks5h://` | 1080        |

URL (`http://host:9999`) میں حسب ضرورت بندرگاہوں کو ہمیشہ اسکیم ڈیفالٹ پر فوقیت حاصل ہوتی ہے۔

---

## پراکسی تجزیات اور مشاہدہ

OmniRoute آپریٹرز کو روٹنگ پیٹرن، لیٹنسی اسپائکس، اور بار بار آنے والی ناکامیوں کی تشخیص میں مدد کرنے کے لیے فی پراکسی استعمال کو ٹریک کرتا ہے۔

### کیا ٹریک کیا گیا ہے

ترتیب شدہ پراکسی کے ذریعے ہر درخواست کے لیے، OmniRoute ریکارڈ کرتا ہے:

| میٹرک        | تفصیل                                                |
| ------------ | ---------------------------------------------------- |
| `proxy_url`  | مکمل پراکسی URL (تصویر کی اسناد کے ساتھ نقاب پوش)    |
| `provider`   | اپ اسٹریم فراہم کنندہ ID (اوپنائی، اینتھروپک، وغیرہ) |
| `latency_ms` | پراکسی ہینڈ شیک سمیت راؤنڈ ٹرپ کا کل وقت             |
| `connect_ms` | TCP صرف کنیکٹ ٹائم                                   |
| `status`     | اپ اسٹریم سے HTTP اسٹیٹس کوڈ                         |
| `error`      | اگر درخواست ناکام ہوگئی تو غلطی کی کلاس              |
| `timestamp`  | ISO 8601 UTC                                         |

### ڈیٹا تک رسائی

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

اصل نقطہ `/api/usage/proxy-logs` ہے ( `src/app/api/usage/proxy-logs/route.ts` دیکھیں)۔ یہ اختتامی نقطہ سپورٹ کرتا ہے:

- `GET /api/usage/proxy-logs` — پراکسی لاگز کو بازیافت کریں۔
- `DELETE /api/usage/proxy-logs` — تمام پراکسی لاگز کو صاف کریں۔

اگر ضرورت ہو تو مجموعی اعدادوشمار براہ راست `proxy_logs` ٹیبل سے SQL کے ذریعے پوچھے جا سکتے ہیں۔ ڈیش بورڈ UI مجموعی آراء پیش کر سکتا ہے۔

### عام پیٹرن

**فلاپنگ پراکسی کا پتہ لگائیں۔** ( success/failure کے درمیان متبادل):

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

**سست پراکسی تلاش کریں۔** (p95 لیٹنسی > 2s):

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

## گردش کی حکمت عملی فیصلہ درخت

جب ایک دائرہ کار میں متعدد پراکسیز تفویض کی جاتی ہیں، OmniRoute استعمال کرتا ہے۔** گردش کی حکمت عملی** ہر درخواست کے لیے کون سا استعمال کرنا ہے۔ حکمت عملی دائرہ کار کی سطح پر ترتیب دی گئی ہے (عالمی، فی فراہم کنندہ، فی اکاؤنٹ، فی کامبو)۔

### دستیاب حکمت عملی

| حکمت عملی                  | کب استعمال کرنا ہے۔                     | تجارت بند                                                                    |
| -------------------------- | --------------------------------------- | ---------------------------------------------------------------------------- |
| `quality` (پہلے سے طے شدہ) | مخلوط معیار کے پراکسیوں کے ساتھ پیداوار | اعلی درجہ کی پراکسیوں کی حمایت کرتا ہے؛ کم درجہ بندی والے بھوکے رہ سکتے ہیں۔ |
| `random`                   | لوڈ کی تقسیم، رازداری                   | یہاں تک کہ تقسیم؛ معیار کے اشاروں کو نظر انداز کرتا ہے۔                      |
| `sequential`               | ڈیبگنگ، ڈیٹرمنسٹک ٹیسٹنگ                | ترتیب میں پراکسی کے ذریعے سائیکل؛ کے بارے میں استدلال کرنا آسان ہے           |

### فیصلہ کن درخت

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

## آپ کی اپنی پراکسیوں کے لیے خودکار ناکامی کا اخراج

1 پراکسی مارکیٹ پلیس پول پہلے ہی ناکام پراکسیوں کو خود سے خود بخود ڈی گریڈ کرتا ہے ( [پراکسی کوالٹی اسکورز](#proxy-quality-scores) دیکھیں)۔ پراکسیوں کے لیے** آپ** رجسٹری میں شامل کیا گیا، بیک گراؤنڈ ہیلتھ شیڈولر (`src/lib/proxyHealth/scheduler.ts`) کچھ بھی حذف کیے بغیر، وہی "ایک مردہ رکن کو خود بخود زنجیر سے خارج کریں" رویہ فراہم کرتا ہے:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

یہ ملٹی پراکسی چین میں کیسے فٹ بیٹھتا ہے:

1. شیڈولر ہر رجسٹرڈ پراکسی ہر `PROXY_HEALTH_INTERVAL_MS` (پہلے سے طے شدہ 10 منٹ؛ کم از کم 1 منٹ) کی تحقیقات کرتا ہے۔
2. `PROXY_AUTO_REMOVE_AFTER` کے بعد لگاتار** حتمی** ناکامیاں (ایک حقیقی کنکشن کی ناکامی — ٹائم آؤٹ یا تحقیقاتی ہدف کا اپنا 5xx کبھی شمار نہیں ہوتا، [پراکسی ہیلتھ چیکنگ](#proxy-health-checking-v3816) دیکھیں)، پراکسی کا `status` `dead` پر سیٹ ہے۔
3. `dead` ان اسٹیٹسز میں سے ایک ہے جو pool/rotation ریزولوشن کے ذریعے استعمال ہونے والا زندہ اسٹیٹس فلٹر خارج کرتا ہے، اس لیے اسکوپ کی گردش (راؤنڈ رابن/رینڈم/اسٹکی/لیٹنسی — دیکھیں [Rotation Strategy Decision Tree](#rotation-strategy-decision-tree) ) فوری طور پر اس پراکسی کو نئی درخواستوں کے حوالے کرنا بند کر دیتی ہے۔ پول میں کوئی اور پراکسی متاثر نہیں ہوتی ہے، اور پورا پول کبھی بھی خاموشی سے براہ راست کنکشن پر نہیں آتا — [4-Level Proxy System](#4-level-proxy-system) fail-closed guard دیکھیں۔
4. شیڈولر اسی وقفہ پر `dead` پراکسیوں کی جانچ کرتا رہتا ہے۔ اگلی کامیاب تحقیقات `status` واپس `active` پر پلٹ دیتی ہے اور یہ گردش — میں دوبارہ داخل ہوتی ہے کوئی دستی دوبارہ شامل کرنے کی ضرورت نہیں ہے۔

یہ جان بوجھ کر ہے۔** آپٹ ان اور غیر تباہ کن** : ڈیفالٹ کے طور پر شیڈولر صرف ناکامیوں کو شمار کرتا ہے اور لاگ ان کرتا ہے ( `decision.ts` میں پالیسی C دیکھیں)، اور `PROXY_AUTO_DISABLE` کبھی بھی قطار — حذف نہیں کرتا ہے جس کے لیے الگ، زیادہ جارحانہ `PROXY_AUTO_REMOVE` پرچم ہے۔ اگر دونوں کو `true` پر سیٹ کیا جاتا ہے تو `PROXY_AUTO_REMOVE` جیت جاتا ہے (ایک پراکسی جو حذف ہونے والی ہے اس کے درمیان نرم غیر فعال کرنے کا کوئی فائدہ نہیں ہے)۔ مکمل متغیر فہرست کے لیے [Environment Config](../reference/ENVIRONMENT.md) حوالہ دیکھیں۔

---

> 📖** متعلقہ دستاویزات:**
>
> - [یوزر گائیڈ](../guides/USER_GUIDE.md) — جنرل سیٹ اپ اور کنفیگریشن - [API حوالہ](../reference/API_REFERENCE.md) — مکمل API دستاویزات - [Environment Config](../reference/ENVIRONMENT.md) — تمام ماحولیاتی متغیرات
