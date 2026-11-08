# 🌐 OmniRoute Proxy Guide (العربية)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **تجاوز الكتل الجغرافية، وحماية هويتك، وتوجيه حركة مرور AI عبر أي وكيل — بدون أي تعقيد في التكوين.**

يتضمن OmniRoute نظام إدارة وكيل كامل المواصفات يتيح لك توجيه حركة مرور موفر AI من خلال وكلاء HTTP أو HTTPS أو SOCKS5. سواء كنت في منطقة محظورة، أو تحتاج إلى تدوير IP ، أو تريد الحصول على بصمات أصابع خفية — فإن هذا الدليل يغطي كل شيء.

---

## جدول المحتويات

- [لماذا استخدام الوكلاء؟](#why-use-proxies)
- [نظرة عامة على الهندسة المعمارية](#architecture-overview)
- [نظام الوكيل ذو 4 مستويات](#4-level-proxy-system)
- [سجل الوكيل (CRUD)](#proxy-registry-crud)
- [1بروكسي السوق الحرة](#1proxy-free-proxy-marketplace)
- [دوران الوكيل](#proxy-rotation)
- [مكافحة الكشف والتخفي](#anti-detection--stealth)
- [أوضاع الوكيل المنبع](#upstream-proxy-modes)
- [لوحة القيادة UI](#dashboard-ui)
- [مرجع API](#api-reference)
- [متغيرات البيئة](#environment-variables)
- [استكشاف الأخطاء وإصلاحها](#troubleshooting)

---

## لماذا استخدام الوكلاء؟

يقوم العديد من موفري AI بتقييد الوصول حسب المنطقة الجغرافية. المطورين في** روسيا، الصين، إيران، كوبا، تركيا** ، وتواجه البلدان الأخرى أخطاء مثل:

```
unsupported_country_region_territory
```

حتى خارج المناطق المحظورة، يكون الوكلاء مفيدًا لما يلي:

| حالة الاستخدام       | وصف                                                                     |
| -------------------- | ----------------------------------------------------------------------- |
| **التجاوز الجغرافي** | قم بالوصول إلى OpenAI و Anthropic و Codex و Copilot من البلدان المحظورة |
| **دوران IP**         | توزيع الطلبات عبر IPs المتعددة لتجنب تحديد المعدل                       |
| **خصوصية**           | إخفاء IP الحقيقي الخاص بك من مقدمي الخدمات الأولية                      |
| **امتثال**           | توجيه حركة المرور عبر ولايات قضائية محددة                               |
| **اختبار**           | محاكاة الطلبات من مناطق مختلفة                                          |

---

## نظرة عامة على الهندسة المعمارية

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

### المكونات الرئيسية

| عنصر               | ملف                                          | دور                                                      |
| ------------------ | -------------------------------------------- | -------------------------------------------------------- |
| **سجل الوكيل**     | `src/lib/db/proxies.ts`                      | CRUD لإدخالات الوكيل لتعيينات نطاق +                     |
| **مرسل الوكيل**    | `open-sse/utils/proxyDispatcher.ts`          | إنشاء مرسلات `undici` ProxyAgent/SOCKS مع التخزين المؤقت |
| **جلب الوكيل**     | `open-sse/utils/proxyFetch.ts`               | يلتف `fetch()` مع حقن المرسل الوكيل                      |
| **مسار الإعدادات** | `src/app/api/settings/proxy/route.ts`        | تكوين الوكيل القديم API (GET/PUT/DELETE)                 |
| **طريق الإدارة**   | `src/app/api/v1/management/proxies/route.ts` | التسجيل CRUD API (GET/POST/PATCH/DELETE)                 |
| **1proxy DB**      | `src/lib/db/oneproxy.ts`                     | استمرار سوق الوكيل المجاني                               |

---

## حالة الوكيل الافتراضية للحسابات الجديدة

في** إعدادات → Proxy → التكوين العام** ، يستخدم** تمكين الوكيل بشكل افتراضي للاتصالات الجديدة** لاختيار حالة الوكيل الأولية لحسابات الموفر المضافة حديثًا.

يتحكم الإعداد الجديد في حالة الوكيل الأولية لحسابات الموفر المضافة حديثًا. ولا يغير الحسابات الموجودة أو يستبدل مفتاح الوكيل العالمي. تحافظ قيمته الأولية على السلوك السابق. قم بإيقاف تشغيله مرة واحدة لإنشاء حسابات مستقبلية مع تعطيل الوكيل افتراضيًا.

يتم تخزين التفضيل كـ `defaultNewConnectionProxyEnabled` من خلال الإعدادات الموجودة API. يتم تعيينه افتراضيًا على `true` عند عدم حفظه مطلقًا. يسري حفظ `false` على الحسابات الجديدة اللاحقة دون إعادة التشغيل. يقبل `POST /api/providers` `proxyEnabled` منطقيًا صارمًا اختياريًا؛ يكون لـ `true` أو `false` الصريحة الأسبقية على الإعداد الافتراضي للإنشاء. يؤدي الإغفال في الحساب المكرر أو إعادة الاتصال OAuth إلى الحفاظ على الحالة المخزنة لذلك الحساب. لا يزال من الممكن تمكين الحسابات الفردية أو تعطيلها بعد ذلك.

تستخدم عمليات نقل الموفر الانتقائية الإعداد الافتراضي لتثبيت الوجهة للحسابات الجديدة وتحافظ على سياسة الوجهة عند استبدال الحسابات الحالية. تبديلات الوكيل ليست حقول نقل محمولة. تحتفظ استعادة النسخ الاحتياطي الكاملة وترحيل JSON/SQL التاريخي بدلالات الاستعادة الحالية، بما في ذلك قيم الحساب المحفوظة والإعدادات الافتراضية للمخطط القديم؛ يمكن لاستعادة الإعدادات الكاملة أيضًا استعادة هذا التفضيل.

لا يؤدي هذا التفضيل إلى تعيين وكيل أو إثبات أنه سليم أو قيد الاستخدام. لا يزال التوجيه الفعلي يعتمد على محول الوكيل العام وتكوين الوكيل القابل للتطبيق. إن موفري الخدمة الاصطناعية الذين لا يملكون حسابًا مستمرًا، وحركة مرور OAuth قبل إنشاء الحساب، ووكلاء environment/system ، والشبكات الخلفية الخارجية، هم خارج نطاقه.

## نظام الوكيل ذو 4 مستويات

OmniRoute يدعم تكوين الوكيل في** أربعة نطاقات مستقلة** ، تم حلها حسب ترتيب الأولوية:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### كيف يعمل القرار

عندما يرسل OmniRoute طلبًا إلى موفر الخدمة الأولية، فإنه يستدعي `resolveProxyForConnectionFromRegistry()` الذي يتحقق من كل مستوى بالترتيب:

1. **على مستوى الحساب** — هل هناك وكيل مخصص لهذا الاتصال المحدد ID؟
2. **على مستوى المزود** — هل هناك وكيل مخصص لهذا المزود (على سبيل المثال، `openai`)؟
3. **على المستوى العالمي** — هل تم تكوين وكيل عالمي؟
4. **لا وكيل** — اتصال مباشر بالمزود.

المباراة الأولى تفوز. هذا يعني أنه يمكنك تعيين وكيل عالمي كبديل ولكن يمكنك تجاوزه لموفرين أو اتصالات محددة.

### ما يحصل على وكيل

| نوع حركة المرور    | وكيل؟ | ملحوظات                                    |
| ------------------ | ----- | ------------------------------------------ |
| استكمالات الدردشة  | ✅    | جميع طلبات `/v1/chat/completions`          |
| التضمين            | ✅    | `/v1/embeddings`                           |
| توليد الصورة       | ✅    | `/v1/images/generations`                   |
| الصوت (TTS/STT)    | ✅    | `/v1/audio/*`                              |
| تبادل رمز OAuth    | ✅    | يحل `unsupported_country_region_territory` |
| اختبارات الاتصال   | ✅    | يستخدم زر "اختبار الاتصال" الوكيل          |
| تحديث الرمز المميز | ✅    | تجديد OAuth الخلفية                        |
| مزامنة النموذج     | ✅    | قائمة النماذج واكتشافها                    |

---

## سجل الوكيل (CRUD)

سجل الوكيل هو جدول SQLite (`proxy_registry`) الذي يخزن جميع الوكلاء الخاصين بك. كل وكيل لديه:

| مجال       | يكتب     | وصف                                       |
| ---------- | -------- | ----------------------------------------- |
| `id`       | UUID     | معرف فريد                                 |
| `name`     | خيط      | تسمية يمكن قراءتها من قبل الإنسان         |
| `type`     | خيط      | البروتوكول: `http`، `https`، `socks5`     |
| `host`     | خيط      | اسم المضيف الوكيل أو IP                   |
| `port`     | عدد صحيح | رقم المنفذ                                |
| `username` | خيط      | اسم مستخدم المصادقة (مشفر أثناء الراحة)   |
| `password` | خيط      | كلمة مرور المصادقة (مشفرة في حالة الراحة) |
| `region`   | خيط      | تسمية المنطقة الجغرافية                   |
| `notes`    | خيط      | ملاحظات النص الحر                         |
| `status`   | خيط      | `active` أو `inactive`                    |
| `source`   | خيط      | `manual` أو `oneproxy`                    |

### إنشاء وكيل

**عبر لوحة التحكم:**

1. اذهب الى** إعدادات → الوكيل**
2. انقر** إضافة وكيل**
3. املأ بيانات اعتماد النوع والمضيف والمنفذ والمصادقة الاختيارية
4. يحفظ

**عبر API:**

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

### تحديث الوكيل

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **ملحوظة:** يتم الاحتفاظ ببيانات الاعتماد ما لم تقم بإرسال بدائل غير فارغة بشكل صريح. سيؤدي إرسال سلاسل فارغة لـ `username`/`password` إلى الاحتفاظ بالقيم المخزنة.

### حذف وكيل

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### وكلاء القائمة

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### تعيين الوكلاء للنطاقات

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

### حل الوكيل الفعال

تحقق من الوكيل الذي سيتم استخدامه لاتصال معين:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

إرجاع الوكيل الذي تم حله مع مستواه (`account` أو `provider` أو `global`) ومصدره.

### مهمة بالجملة

قم بتعيين وكيل واحد لموفرين أو اتصالات متعددة في وقت واحد:

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

يتم تضمين الوكلاء في**Backup/Restore** نظام. عند تصدير تكوين OmniRoute الخاص بك:

1. اذهب الى** لوحة التحكم إعدادات → النسخ الاحتياطي →**
2. انقر** يصدّر** يتم تضمين تسجيل الوكيل — والتخصيصات
3. للاستعادة، انقر فوق** يستورد** وتحميل ملف النسخ الاحتياطي

كما يدعم تسجيل الوكيل** upsert بواسطة ميناء + المضيف** — إذا قمت باستيراد وكيل موجود بالفعل (نفس المضيف والمنفذ)، فسيتم تحديثه بدلاً من إنشاء نسخة مكررة.

### الهجرة التراثية

إذا قمت بتكوين الوكلاء في إصدار أقدم (التسجيل المسبق)، فسيقوم OmniRoute بترحيلهم تلقائيًا:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

يحدث هذا مرة واحدة عند بدء التشغيل الأول بعد الترقية. استخدم `migrateLegacyProxyConfigToRegistry({ force: true })` لإعادة التشغيل.

---

## 1proxy سوق الوكيل المجاني

> 🆕** مساهمة من [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (الإصدار [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute يتكامل مع** [1proxy](https://1proxy-api.aitradepulse.com)** منصة المجتمع لتوفير الوصول إلى** مئات من الوكلاء المجانيين المعتمدين** من جميع أنحاء العالم. يعد هذا مثاليًا للمستخدمين الذين ليس لديهم بنية تحتية للوكيل خاصة بهم.

### كيف يعمل

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **مزامنة** يقوم — OmniRoute بجلب الوكلاء الذين تم التحقق من صحتهم من 1proxy API
2. **محل** يتم حفظ وكلاء — في نفس جدول `proxy_registry` مع `source = 'oneproxy'`
3. **فلتر** — تصفية حسب البروتوكول، البلد، ونقاط الجودة
4. **تناوب** — اختر أفضل وكيل باستخدام استراتيجيات الجودة أو العشوائية أو التسلسلية
5. **التحلل التلقائي** — الوكلاء الفاشلون يحصلون على نقاط جودة منخفضة؛ تحت عتبة → تم وضع علامة غير نشط

### مزامنة الوكلاء

**عبر لوحة التحكم:**

1. اذهب الى** إعدادات → 1proxy** فاتورة غير مدفوعة
2. انقر** "المزامنة الآن"**
3. عرض الإحصائيات: إجمالي الوكلاء، العدد النشط، متوسط الجودة، التوزيع حسب البلد

**عبر API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### تصفية الوكلاء

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

### نقاط جودة الوكيل

يأتي كل وكيل 1proxy مزودًا ببيانات تعريفية:

| مجال            | وصف                                              |
| --------------- | ------------------------------------------------ |
| `qualityScore`  | تصنيف 0-100 من التحقق من صحة 1proxy              |
| `latencyMs`     | قياس زمن استجابة الشبكة                          |
| `anonymity`     | `transparent` أو `anonymous` أو `elite`          |
| `googleAccess`  | ما إذا كان بإمكان الوكيل الوصول إلى خدمات Google |
| `countryCode`   | رمز البلد ISO المكون من حرفين                    |
| `lastValidated` | الطابع الزمني لآخر التحقق من الصحة               |

يتم تعديل نقاط الجودة ديناميكيًا:

- **الطلبات الفاشلة** خفض النتيجة بمقدار 10 نقاط
- **تنخفض النتيجة إلى ≤ 10** تم وضع علامة على وكيل → `inactive`
- يتم استبعاد الوكلاء غير النشطين من التناوب

### استراتيجيات التناوب

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

### قواطع دوائر

تحتوي مزامنة 1proxy على قاطع دائرة مدمج:

- بعد** 5 حالات فشل مزامنة متتالية** ، يتم حظر محاولات المزامنة الأخرى
- إعادة التعيين باستخدام: `resetOneproxyCircuitBreaker()` أو إعادة تشغيل الخادم
- حالة المزامنة متاحة في `GET /api/settings/oneproxy?action=status`

### مسح وكلاء 1proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## مكافحة الكشف والتخفي

لا يقوم OmniRoute بتوجيه حركة المرور عبر الوكيل — فحسب، بل يجعل حركة المرور تبدو مشروعة:

### TLS انتحال بصمات الأصابع

يستخدم `wreq-js` لإنشاء بصمات TLS تشبه المتصفح، متجاوزًا أنظمة اكتشاف الروبوتات التي تشير إلى مصافحات TLS غير المستعرضة.

### CLI مطابقة بصمات الأصابع

ال** تبديل بصمة CLI** (`Settings → Security`) يعيد ترتيب رؤوس HTTP وحقول نص JSON لتتوافق تمامًا مع التوقيع الدقيق لثنائيات CLI الأصلية (Claude Code، Codex، وما إلى ذلك). هذا يعمل** على رأس** الوكيل:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

يمكنك الحصول على حد سواء** اخفاء IP** و** طلب الأصالة** معًا.

### حفظ الوكيل IP

تُظهر الشارات المرمزة بالألوان في لوحة المعلومات مستوى الوكيل النشط:

| شارة | مستوى | معنى                                     |
| ---- | ----- | ---------------------------------------- |
| 🟢   | عالمي | كل حركة المرور تمر عبر هذا الوكيل        |
| 🟡   | مزود  | يتم إنشاء وكيل لحركة مرور هذا الموفر فقط |
| 🔵   | اتصال | يستخدم هذا key/account المحدد هذا الوكيل |

تُظهر الشارة أيضًا الوكيل IP الذي تم حله للتحقق.

---

## أوضاع الوكيل المنبع

بالنسبة للموفرين الذين يستخدمون نمط CLIProxyAPI ، يدعم OmniRoute ثلاثة أوضاع للوكيل الرئيسي:

| وضع           | وصف                                           |
| ------------- | --------------------------------------------- |
| `native`      | OmniRoute يعالج توجيه الوكيل مباشرة (افتراضي) |
| `cliproxyapi` | المندوبون إلى مثيل CLIProxyAPI خارجي          |
| `fallback`    | يحاول الأصلي أولا، ويعود إلى CLIProxyAPI      |

التكوين لكل موفر:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## لوحة القيادة UI

### إعدادات علامة تبويب الوكيل →

- **الوكيل العالمي** التكوين (يتم ضبطه مرة واحدة لجميع حركة المرور)
- **الوكيل لكل مزود** يتجاوز
- **الوكيل لكل اتصال** المهام
- **اختبار الاتصال** من خلال الوكيل الذي تم تكوينه
- **شارات مرمزة بالألوان** إظهار مستوى الوكيل النشط

### إعدادات → 1proxy Tab

- **مزامنة الآن** زر لجلب الوكلاء المجانيين
- **بطاقات الإحصائيات** : الإجمالي، النشط، متوسط الجودة، آخر مزامنة
- **المرشحات** : البروتوكول، رمز البلد، الحد الأدنى للجودة
- **جدول الوكيل** مع المضيف، والبروتوكول، والبلد، ونقاط الجودة، والكمون، وعدم الكشف عن هويته، والوصول إلى Google
- **حالة المزامنة** لوحة مع تتبع success/failure وعدد الفشل المتتالي
- **مسح الكل** لإزالة كافة إدخالات 1proxy

---

## مرجع API

### إعدادات الوكيل API

| طريقة    | نقطة النهاية                                   | وصف                          |
| -------- | ---------------------------------------------- | ---------------------------- |
| `GET`    | `/api/settings/proxy`                          | احصل على تكوين الوكيل الكامل |
| `GET`    | `/api/settings/proxy?level=global`             | احصل على الوكيل العالمي      |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | احصل على وكيل الموفر         |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | حل الوكيل الفعال             |
| `PUT`    | `/api/settings/proxy`                          | تحديث تكوين الوكيل           |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | إزالة الوكيل على المستوى     |

### سجل الوكيل API

| طريقة    | نقطة النهاية                                      | وصف                         |
| -------- | ------------------------------------------------- | --------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | قائمة كافة الوكلاء          |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | الحصول على الوكيل بواسطة ID |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | الحصول على مهام الوكيل      |
| `POST`   | `/api/v1/management/proxies`                      | إنشاء وكيل                  |
| `PATCH`  | `/api/v1/management/proxies`                      | تحديث الوكيل                |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | حذف الوكيل                  |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | فرض الحذف                   |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | تعيين بالجملة               |
| `GET`    | `/api/v1/management/proxies/assignments`          | قائمة المهام                |
| `GET`    | `/api/v1/management/proxies/health`               | إحصائيات صحة الوكيل         |

### أنفاق API

لعرض مثيل OmniRoute الخاص بك إلى الإنترنت العام (Cloudflare/ngrok/Tailscale) بدلاً من التوجيه للخارج عبر وكيل، راجع [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). يعيش النفق REST API ضمن `/api/tunnels/{cloudflared,ngrok,tailscale}/*` وهو متعامد مع سلسلة الوكيل الصادرة الموثقة أعلاه.

### 1proxy API

| طريقة    | نقطة النهاية                           | وصف                                 |
| -------- | -------------------------------------- | ----------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | قائمة 1proxy الوكلاء                |
| `GET`    | `/api/settings/oneproxy?action=stats`  | الحصول على احصائيات + حالة المزامنة |
| `GET`    | `/api/settings/oneproxy?action=status` | الحصول على حالة المزامنة فقط        |
| `POST`   | `/api/settings/oneproxy`               | مزامنة الزناد                       |
| `POST`   | `/api/settings/oneproxy/rotate`        | قم بالتدوير إلى الوكيل التالي       |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | احذف واحدة                          |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | مسح الكل                            |

### وكيل المنبع API

| طريقة    | نقطة النهاية                      | وصف                           |
| -------- | --------------------------------- | ----------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | احصل على تكوين الوكيل المنبع  |
| `PUT`    | `/api/upstream-proxy/:providerId` | قم بتعيين وضع الوكيل الأولي   |
| `DELETE` | `/api/upstream-proxy/:providerId` | قم بإزالة تكوين الوكيل الأولي |

---

## متغيرات البيئة

| عامل                  | تقصير  | وصف                                                         |
| --------------------- | ------ | ----------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true` | تمكين دعم وكيل SOCKS5 ( `true` الافتراضي في `.env.example`) |

---

## استكشاف الأخطاء وإصلاحها

### "تم تعطيل وكيل SOCKS5 "

قم بتعيين `ENABLE_SOCKS5_PROXY=true` في ملف `.env` الخاص بك وأعد التشغيل.

### أخطاء "مأخذ قطع الاتصال" من خلال الوكيل

يعد هذا أمرًا طبيعيًا مع الوكلاء الرخيصين الذين يقومون بإسقاط الاتصالات الخاملة. تتعامل OmniRoute مع هذا بالفعل من خلال:

- تعطيل استمرارية اتصالات الوكيل (`keepAliveTimeout: 1`)
- تعطيل خطوط الأنابيب (`pipelining: 0`)
- التخزين المؤقت للمرسلين لتجنب المصافحة المتكررة

إذا استمرت المشكلة، فجرّب وكيلاً مختلفًا أو استخدم ميزة التدوير 1proxy.

### "unsupported_country_region_territory" أثناء OAuth

تأكد من تكوين الوكيل** قبل** بدء تدفق OAuth. يقوم OmniRoute بتوجيه تبادل الرمز المميز OAuth من خلال الوكيل الذي تم تكوينه. قم بتعيين وكيل عالمي أو على مستوى الموفر أولاً، ثم قم بالاتصال.

### الوكيل غير مستخدم

التحقق من ترتيب القرار:

1. التحقق مع `GET /api/settings/proxy?resolve=your-connection-id`
2. تحقق مما إذا كان الوكيل `status` هو `active` (وليس `inactive`)
3. تأكد من أن نطاق تعيين الوكيل يطابق اتصالك

### فشل مزامنة الوكيل 1

التحقق من حالة المزامنة:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

إذا `consecutiveFailures >= 5`، فقد تعثر قاطع الدائرة. أعد تشغيل الخادم لإعادة التعيين، أو انتظر إعادة التعيين اليدوي.

---

## مخطط قاعدة البيانات

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

## فحص صحة الوكيل (v3.8.16 +)

OmniRoute** وكيل سريع الفشل** تكتشف الآلية (`src/lib/proxyHealth.ts`) الوكلاء الميتين في < 2s عبر فحص سريع لاتصال TCP ، ثم** يخزن النتيجة** لتجنب النفقات العامة لكل طلب.

### كيف يعمل

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

بدون ذلك، سيمنع الوكيل الميت كل طلب للحصول على `PROXY_TIMEOUT_MS` الكامل (30 ثانية افتراضيًا) قبل الفشل.

### متغيرات البيئة القابلة للضبط

| عامل                         | تقصير   | غاية                                        |
| ---------------------------- | ------- | ------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | مهلة اتصال TCP لكل فحص صحي                  |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | كم من الوقت يتم تخزين النتيجة الصحية مؤقتًا |

**القيم الموصى بها:**

| سيناريو                   | مهلة الفشل السريع | ذاكرة التخزين المؤقت TTL | المنطق                                                                           |
| ------------------------- | ----------------- | ------------------------ | -------------------------------------------------------------------------------- |
| بوابة API عالية الإنتاجية | 1500 مللي ثانية   | 60000 مللي ثانية         | ذاكرة تخزين مؤقت قوية وسريعة الفشل وأطول لتقليل عمليات التحقق                    |
| العقد الموزعة جغرافيا     | 3000 مللي ثانية   | 15000 مللي ثانية         | تحتاج الشبكات الأبطأ إلى مزيد من الوقت؛ ذاكرة تخزين مؤقت أقصر لتجاوز الفشل بسرعة |
| تطوير / اختبار            | 1000 مللي ثانية   | 10000 مللي ثانية         | التكرار السريع على الوكلاء المحليين                                              |
| التخفي / مكافحة الكشف     | 2500 مللي ثانية   | 45000 مللي ثانية         | تجنب الفحص السريع الذي قد يؤدي إلى فرض حدود على المعدل                           |

### فحص صحة الوكيل

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

تكون علامة `stale` هي `true` عندما يتجاوز إدخال ذاكرة التخزين المؤقت `HEALTH_CACHE_TTL_MS` وسيؤدي الطلب التالي إلى إجراء فحص جديد.

### الإعدادات الافتراضية لكل نوع وكيل

يستخدم فحص الصحة إعدادات افتراضية معقولة بناءً على مخطط URL :

| مخطط                       | المنفذ الافتراضي |
| -------------------------- | ---------------- |
| `http://`                  | 8080             |
| `https://`                 | 443              |
| `socks5://` / `socks5h://` | 1080             |

المنافذ المخصصة في URL (`http://host:9999`) لها دائمًا الأسبقية على الإعداد الافتراضي للنظام.

---

## تحليلات الوكيل وإمكانية الملاحظة

يقوم OmniRoute بتتبع استخدام كل وكيل لمساعدة المشغلين على تشخيص أنماط التوجيه، وارتفاع زمن الاستجابة، والفشل المتكرر.

### ما تم تعقبه

لكل طلب من خلال وكيل تم تكوينه، يسجل OmniRoute :

| متري         | وصف                                                           |
| ------------ | ------------------------------------------------------------- |
| `proxy_url`  | URL الوكيل الكامل (مع إخفاء بيانات اعتماد المصادقة)           |
| `provider`   | مزود المنبع ID (openai، الأنثروبي، إلخ.)                      |
| `latency_ms` | إجمالي وقت الرحلة ذهابًا وإيابًا بما في ذلك المصافحة بالوكالة |
| `connect_ms` | TCP وقت الاتصال فقط                                           |
| `status`     | رمز الحالة HTTP من المنبع                                     |
| `error`      | فئة الخطأ في حالة فشل الطلب                                   |
| `timestamp`  | ISO 8601 UTC                                                  |

### الوصول إلى البيانات

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

نقطة النهاية الحقيقية هي `/api/usage/proxy-logs` (انظر `src/app/api/usage/proxy-logs/route.ts`). تدعم نقطة النهاية هذه:

- `GET /api/usage/proxy-logs` — استرداد سجلات الوكيل
- `DELETE /api/usage/proxy-logs` — مسح كافة سجلات الوكيل

يمكن الاستعلام عن الإحصائيات المجمعة مباشرة من جدول `proxy_logs` عبر SQL إذا لزم الأمر. قد تقدم لوحة المعلومات UI طرق عرض مجمعة.

### الأنماط الشائعة

**كشف وكيل ترفرف** (يتناوب بين success/failure):

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

**ابحث عن الوكلاء البطيئين** (p95 الكمون > 2s):

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

## شجرة قرارات استراتيجية التناوب

عندما يتم تعيين عدة وكلاء لنطاق ما، يستخدم OmniRoute ملف** استراتيجية التناوب** لاختيار أي واحد لاستخدامه لكل طلب. يتم تكوين الإستراتيجية على مستوى النطاق (عالمي، لكل موفر، لكل حساب، لكل مجموعة).

### الاستراتيجيات المتاحة

| استراتيجية          | متى تستخدم                           | التنازل عن ميزة ممن أجل الحصول على أخرى                           |
| ------------------- | ------------------------------------ | ----------------------------------------------------------------- |
| `quality` (افتراضي) | الإنتاج باستخدام وكلاء مختلطي الجودة | يفضل الوكلاء ذوي التصنيف العالي؛ قد تجويع تلك ذات التصنيف المنخفض |
| `random`            | توزيع التحميل والخصوصية              | التوزيع المتساوي؛ يتجاهل إشارات الجودة                            |
| `sequential`        | تصحيح الأخطاء والاختبار الحتمي       | التنقل عبر الوكلاء بالترتيب؛ من السهل التفكير                     |

### شجرة القرار

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

## استبعاد الفشل التلقائي للوكلاء الخاصين بك

يقوم مجمع سوق 1proxy بالفعل بتخفيض الوكلاء الفاشلين تلقائيًا من تلقاء نفسه (راجع [نقاط جودة الوكيل](#proxy-quality-scores) ). للوكلاء** أنت** عند إضافته إلى السجل، يوفر برنامج جدولة صحة الخلفية (`src/lib/proxyHealth/scheduler.ts`) نفس سلوك "استبعاد عضو ميت من السلسلة تلقائيًا"، دون حذف أي شيء:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

كيف تتناسب مع سلسلة متعددة الوكيل:

1. يقوم المجدول بالتحقق من كل وكيل مسجل كل `PROXY_HEALTH_INTERVAL_MS` (الافتراضي 10 دقائق؛ الحد الأدنى 1 دقيقة).
2. بعد `PROXY_AUTO_REMOVE_AFTER` متتالية** قاطعة** حالات الفشل (فشل الاتصال الحقيقي — انتهاء المهلة أو 5xx الخاص بالهدف المسبار لا يتم احتسابه أبدًا، راجع [فحص صحة الوكيل](#proxy-health-checking-v3816) )، تم تعيين `status` الخاص بالوكيل على `dead`.
3. `dead` هي إحدى الحالات التي يستثنيها مرشح الحالة الحية المستخدم بواسطة دقة pool/rotation ، لذا فإن دوران النطاق (دائري روبن / عشوائي / ثابت / زمن الوصول — راجع [شجرة قرارات إستراتيجية التدوير](#rotation-strategy-decision-tree) ) يتوقف فورًا عن تسليم هذا الوكيل للطلبات الجديدة. لا يتأثر أي وكلاء آخرين في التجمع، ولا يعود المجمع بأكمله بصمت إلى الاتصال المباشر ( — راجع [نظام الحماية من الفشل في نظام الوكيل رباعي المستويات](#4-level-proxy-system).
4. يستمر المجدول في فحص وكلاء `dead` في نفس الفترة الزمنية. يقوم المسبار الناجح التالي بقلب `status` مرة أخرى إلى `active` ويدخل مرة أخرى في الدوران — ولا يلزم إعادة الإضافة اليدوية.

هذا عمدا** التقيد وغير المدمرة** : افتراضيًا، يقوم المجدول بحساب وتسجيل حالات الفشل فقط (راجع السياسة C في `decision.ts`)، ولا يحذف `PROXY_AUTO_DISABLE` أبدًا صف — الذي هو الغرض من علامة `PROXY_AUTO_REMOVE` المنفصلة والأكثر عدوانية. إذا تم تعيين كليهما على `true`، `PROXY_AUTO_REMOVE` يفوز (الوكيل الذي على وشك الحذف ليس له أي فائدة للتعطيل البسيط بينهما). راجع مرجع [تكوين البيئة](../reference/ENVIRONMENT.md) للحصول على قائمة المتغيرات الكاملة.

---

> 📖** الوثائق ذات الصلة:**
>
> - [دليل المستخدم](../guides/USER_GUIDE.md) — الإعداد والتكوين العام - [API المرجع](../reference/API_REFERENCE.md) — وثائق API الكاملة - [تكوين البيئة](../reference/ENVIRONMENT.md) — جميع متغيرات البيئة
