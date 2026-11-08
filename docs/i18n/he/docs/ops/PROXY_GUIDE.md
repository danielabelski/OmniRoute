# 🌐 OmniRoute Proxy Guide (עברית)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **עוקף חסימות גיאוגרפיות, הגן על הזהות שלך ונתב תעבורת AI דרך כל פרוקסי — עם אפס מורכבות תצורה.**

OmniRoute כולל מערכת ניהול פרוקסי מלאת תכונות המאפשרת לך לנתב תעבורת ספקי AI במעלה הזרם דרך פרוקסי HTTP, HTTPS או SOCKS5. בין אם אתה באזור חסום, צריך סיבוב IP, או רוצה טביעת אצבע חמקנית — המדריך הזה מכסה הכל.

---

## תוֹכֶן הָעִניָנִים

- [למה להשתמש בפרוקסי?](#why-use-proxies)
- [סקירה כללית של אדריכלות](#architecture-overview)
- [מערכת פרוקסי 4 רמות](#4-level-proxy-system)
- [רישום פרוקסי (CRUD)](#proxy-registry-crud)
- [1proxy Free Marketplace](#1proxy-free-proxy-marketplace)
- [סיבוב פרוקסי](#proxy-rotation)
- [נגד גילוי והתגנבות](#anti-detection--stealth)
- [מצבי פרוקסי במעלה הזרם](#upstream-proxy-modes)
- [לוח המחוונים UI](#dashboard-ui)
- [API](#api-reference)
- [משתני סביבה](#environment-variables)
- [פתרון בעיות](#troubleshooting)

---

## למה להשתמש בפרוקסי?

ספקי AI רבים מגבילים את הגישה לפי אזור גיאוגרפי. מפתחים ב** רוסיה, סין, איראן, קובה, טורקיה** , ומדינות אחרות נתקלות בשגיאות כמו:

```
unsupported_country_region_territory
```

אפילו מחוץ לאזורים חסומים, פרוקסי שימושיים עבור:

| Use Case          | תֵאוּר                                                 |
| ----------------- | ------------------------------------------------------ |
| **עוקף גיאוגרפי** | גש ל- OpenAI, Anthropic, Codex, Copilot ממדינות חסומות |
| **סיבוב IP**      | הפזר בקשות על פני מספר IPs כדי להימנע מהגבלת שיעור     |
| **פְּרָטִיוּת**   | הסתר IP האמיתי שלך מספקים במעלה הזרם                   |
| **הַתאָמָה**      | נתב תנועה דרך תחומי שיפוט ספציפיים                     |
| **בּוֹחֵן**       | הדמיית בקשות מאזורים שונים                             |

---

## סקירה כללית של אדריכלות

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

### רכיבי מפתח

| רְכִיב           | קוֹבֶץ                                       | תַפְקִיד                                       |
| ---------------- | -------------------------------------------- | ---------------------------------------------- |
| **רישום פרוקסי** | `src/lib/db/proxies.ts`                      | CRUD עבור ערכי פרוקסי הקצאות היקף +            |
| **שולח פרוקסי**  | `open-sse/utils/proxyDispatcher.ts`          | יוצר שולחני `undici` ProxyAgent/SOCKS עם מטמון |
| **אחזור פרוקסי** | `open-sse/utils/proxyFetch.ts`               | עוטף `fetch()` עם הזרקת שרת proxy              |
| **הגדרות מסלול** | `src/app/api/settings/proxy/route.ts`        | תצורת proxy מדור קודם API (GET/PUT/DELETE)     |
| **מסלול ניהול**  | `src/app/api/v1/management/proxies/route.ts` | רישום CRUD API (GET/POST/PATCH/DELETE)         |
| **1 פרוקסי DB**  | `src/lib/db/oneproxy.ts`                     | התמדה חופשית בשוק פרוקסי                       |

---

## מצב ברירת המחדל של proxy עבור חשבונות חדשים

ב** הגדרות → Proxy → תצורה גלובלית** , להשתמש** אפשר פרוקסי כברירת מחדל עבור חיבורים חדשים** כדי לבחור את מצב ה-proxy הראשוני של חשבונות ספקים חדשים שנוספו.

ההגדרה החדשה שולטת במצב ה-proxy הראשוני של חשבונות ספקים חדשים שנוספו. זה לא משנה חשבונות קיימים או מחליף את מתג ה-proxy הגלובלי. הערך ההתחלתי שלו שומר על ההתנהגות הקודמת. כבה אותו פעם אחת כדי ליצור חשבונות עתידיים עם פרוקסי מושבת כברירת מחדל.

ההעדפה מאוחסנת כ- `defaultNewConnectionProxyEnabled` דרך ההגדרות הקיימות API. ברירת המחדל היא `true` כאשר מעולם לא נשמר. שמירת `false` נכנסת לתוקף עבור חשבונות חדשים הבאים ללא הפעלה מחדש. `POST /api/providers` מקבל `proxyEnabled` בוליאני קפדני אופציונלי; `true` או `false` מפורש עדיפות על ברירת המחדל של היצירה. השמטה בחשבון כפול או חיבור מחדש OAuth משמרת את המצב השמור של חשבון זה. עדיין ניתן להפעיל או להשבית חשבונות בודדים לאחר מכן.

העברות ספקים סלקטיביות משתמשות בברירת המחדל של התקנת היעד עבור חשבונות חדשים ומשמרות את מדיניות היעד בעת החלפת חשבונות קיימים. מתגי Proxy אינם שדות העברה ניידים. שחזור גיבוי מלא והגירה היסטורית JSON/SQL שומרים על סמנטיקת השחזור הקיימת שלהם, כולל ערכי חשבון שמורים וברירות מחדל של סכימה מדור קודם; שחזור הגדרות מלא יכול גם לשחזר העדפה זו.

העדפה זו אינה מקצה פרוקסי או קובעת שהוא בריא או בשימוש. הניתוב בפועל עדיין תלוי במתג ה-proxy הגלובלי ובתצורת ה-proxy הרלוונטית. ספקים סינתטיים ללא חשבון מתמשך, תעבורת OAuth לפני יצירת החשבון, פרוקסי environment/system ורשתות של backends חיצוניים נמצאים מחוץ להיקפו.

## מערכת פרוקסי 4 רמות

OmniRoute תומך בתצורת פרוקסי ב** ארבעה היקפים עצמאיים** , נפתר בסדר עדיפות:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### איך הרזולוציה עובדת

כאשר OmniRoute שולח בקשה לספק במעלה הזרם, הוא קורא `resolveProxyForConnectionFromRegistry()` שבודק כל רמה לפי הסדר:

1. **ברמת החשבון** — האם יש פרוקסי מוקצה לחיבור הספציפי הזה ID?
2. **ברמת הספק** — האם יש פרוקסי שהוקצה לספק זה (למשל, `openai`)?
3. **ברמה עולמית** — האם מוגדר פרוקסי גלובלי?
4. **אין פרוקסי** — חיבור ישיר לספק.

המשחק הראשון מנצח. משמעות הדבר היא שאתה יכול להגדיר פרוקסי גלובלי כחלופה אך לעקוף אותו עבור ספקים או חיבורים ספציפיים.

### מה מקבל פרוקסי

| סוג תנועה            | פרוקסי? | הערות                                       |
| -------------------- | ------- | ------------------------------------------- |
| השלמות של צ'אט       | ✅      | כל בקשות `/v1/chat/completions`             |
| הטבעות               | ✅      | `/v1/embeddings`                            |
| יצירת תמונות         | ✅      | `/v1/images/generations`                    |
| אודיו (TTS/STT)      | ✅      | `/v1/audio/*`                               |
| החלפת אסימונים OAuth | ✅      | פותר `unsupported_country_region_territory` |
| בדיקות חיבור         | ✅      | כפתור "בדוק חיבור" משתמש בפרוקסי            |
| רענון אסימון         | ✅      | רקע חידוש OAuth                             |
| סנכרון דגם           | ✅      | רישום דגמים וגילוי                          |

---

## רישום פרוקסי (CRUD)

רישום ה-proxy הוא טבלת SQLite (`proxy_registry`) המאחסנת את כל ה-proxies שלך. לכל פרוקסי יש:

| שָׂדֶה     | סוּג           | תֵאוּר                              |
| ---------- | -------------- | ----------------------------------- |
| `id`       | UUID           | מזהה ייחודי                         |
| `name`     | חוּט           | תווית קריא לאדם                     |
| `type`     | חוּט           | פרוטוקול: `http`, `https`, `socks5` |
| `host`     | חוּט           | שם מארח פרוקסי או IP                |
| `port`     | מִספָּר שָׁלֵם | מספר יציאה                          |
| `username` | חוּט           | שם משתמש אישור (מוצפן במצב מנוחה)   |
| `password` | חוּט           | סיסמת אימות (מוצפנת במצב מנוחה)     |
| `region`   | חוּט           | תווית אזור גיאוגרפי                 |
| `notes`    | חוּט           | הערות בטקסט חופשי                   |
| `status`   | חוּט           | `active` או `inactive`              |
| `source`   | חוּט           | `manual` או `oneproxy`              |

### יצירת פרוקסי

**דרך לוח המחוונים:**

1. עבור אל** הגדרות → Proxy**
2. נְקִישָׁה** הוסף פרוקסי**
3. מלא את הסוג, המארח, היציאה ואישורי האימות האופציונליים
4. לְהַצִיל

**דרך API:**

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

### עדכון פרוקסי

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **פֶּתֶק:** האישורים נשמרים אלא אם כן אתה שולח במפורש תחליפים שאינם ריקים. שליחת מחרוזות ריקות עבור `username`/`password` תשמור על הערכים המאוחסנים.

### מחיקת פרוקסי

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### פרוקסי רישום

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### הקצאת פרוקסי להיקפים

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

### פתרון פרוקסי יעיל

בדוק באיזה פרוקסי ישמש עבור חיבור נתון:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

מחזיר את ה-proxy שנפתר עם הרמה שלו (`account`, `provider` או `global`) והמקור שלו.

### הקצאת כמות גדולה

הקצה פרוקסי אחד למספר ספקים או חיבורים בו-זמנית:

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

פרוקסי כלולים ב-**Backup/Restore** מַעֲרֶכֶת. כאשר אתה מייצא את תצורת OmniRoute שלך:

1. עבור אל** לוח המחוונים → הגדרות → גיבוי**
2. נְקִישָׁה** יְצוּא** הרישום והמשימות — פרוקסי כלולים
3. כדי לשחזר, לחץ** יְבוּא** ולהעלות את קובץ הגיבוי

גם רישום ה-proxy תומך** להעלות על ידי מארח יציאת +** — אם אתה מייבא פרוקסי שכבר קיים (אותו מארח ויציאה), הוא מתעדכן במקום ליצור כפיל.

### הגירה מדור קודם

אם הגדרתם פרוקסי בגרסה ישנה יותר (טרום רישום), OmniRoute מעבירה אותם אוטומטית:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

זה קורה פעם אחת באתחול הראשון לאחר השדרוג. השתמש `migrateLegacyProxyConfigToRegistry({ force: true })` כדי להפעיל מחדש.

---

## 1proxy Free Proxy Marketplace

> 🆕** תרם על ידי [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (גיליון [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute משתלב עם** [1 פרוקסי](https://1proxy-api.aitradepulse.com)** פלטפורמה קהילתית לספק גישה אליה** מאות פרוקסי חינם ומאומתים** מרחבי העולם. זה מושלם עבור משתמשים שאין להם תשתית פרוקסי משלהם.

### איך זה עובד

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **סנכרון** — OmniRoute מביא פרוקסי מאומתים מה-1proxy API
2. **חנות** — Proxies נשמרים באותה טבלת `proxy_registry` עם `source = 'oneproxy'`
3. **לְסַנֵן** — סנן לפי פרוטוקול, מדינה, ציון איכות
4. **לְסוֹבֵב** — בחר את ה-proxy הטוב ביותר באמצעות אסטרטגיות איכות, אקראיות או רציפות
5. **השפלה אוטומטית** — פרוקסי שנכשלו מקבלים את ציון האיכות שלהם מופחת; מתחת לסף → מסומן כלא פעיל

### סנכרון פרוקסי

**דרך לוח המחוונים:**

1. עבור אל** הגדרות → 1proxy** לשונית
2. נְקִישָׁה** "סנכרן עכשיו"**
3. הצג נתונים סטטיסטיים: סך כל פרוקסי, ספירה פעילה, איכות ממוצעת, פירוט לפי מדינה

**דרך API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### סינון פרוקסי

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

### ציוני איכות של פרוקסי

כל פרוקסי 1proxy מגיע עם מטא נתונים:

| שָׂדֶה          | תֵאוּר                                |
| --------------- | ------------------------------------- |
| `qualityScore`  | דירוג 0-100 מאימות פרוקסי 1           |
| `latencyMs`     | זמן אחזור רשת נמדד                    |
| `anonymity`     | `transparent`, `anonymous` או `elite` |
| `googleAccess`  | האם ה-proxy יכול לגשת לשירותי Google  |
| `countryCode`   | קוד מדינה בן שתי אותיות ISO           |
| `lastValidated` | חותמת זמן של האימות האחרון            |

ציוני האיכות מותאמים באופן דינמי:

- **בקשות שנכשלו** להפחית את הניקוד ב-10 נקודות
- **הציון יורד ל- ≤ 10** → proxy מסומן `inactive`
- פרוקסי לא פעילים אינם נכללים בסיבוב

### אסטרטגיות סיבוב

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

### מפסק חשמל

לסינכרון 1proxy יש מפסק מובנה:

- לְאַחַר** 5 כשלי סנכרון רצופים** , ניסיונות סנכרון נוספים חסומים
- אפס עם: `resetOneproxyCircuitBreaker()` או הפעל מחדש את השרת
- סטטוס סנכרון זמין ב- `GET /api/settings/oneproxy?action=status`

### ניקוי פרוקסי 1proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## נגד גילוי והתגנבות

OmniRoute לא רק מנתב תעבורה דרך פרוקסי — אלא גורם לתנועה להיראות לגיטימית:

### זיוף טביעות אצבע TLS

משתמש `wreq-js` כדי ליצור טביעות אצבע מסוג TLS דמויות דפדפן, תוך עקיפת מערכות זיהוי בוטים המסמנות לחיצות ידיים TLS שאינן דפדפן.

### CLI התאמת טביעות אצבע

ה**CLI החלפת טביעת אצבע** (`Settings → Security`) מסדר מחדש את הכותרות HTTP ושדות הגוף JSON כדי להתאים את החתימה המדויקת של קבצי CLI מקוריים (Claude Code, Codex וכו'). זה עובד** עַל גַבֵּי** ה-proxy:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

אתה מקבל את שניהם** מיסוך IP** ו** לבקש אותנטיות** בּוֹ זְמַנִית.

### פרוקסי IP שימור

תגים מקודדים בצבע בלוח המחוונים מראים איזו רמת פרוקסי פעילה:

| תָג | רָמָה      | מַשְׁמָעוּת                               |
| --- | ---------- | ----------------------------------------- |
| 🟢  | גלוֹבָּלִי | כל התעבורה עוברת דרך פרוקסי זה            |
| 🟡  | ספק        | רק התעבורה של ספק זה עוברת פרוקסי         |
| 🔵  | קֶשֶׁר     | key/account הספציפי הזה משתמש בפרוקסי הזה |

התג מציג גם את ה-proxy IP שנפתר לאימות.

---

## מצבי פרוקסי במעלה הזרם

עבור ספקים המשתמשים בדפוס CLIProxyAPI, OmniRoute תומך בשלושה מצבי פרוקסי במעלה הזרם:

| מצב           | תֵאוּר                                           |
| ------------- | ------------------------------------------------ |
| `native`      | OmniRoute מטפל בניתוב פרוקסי ישירות (ברירת מחדל) |
| `cliproxyapi` | נציגים למופע CLIProxyAPI חיצוני                  |
| `fallback`    | מנסה יליד ראשון, נופל בחזרה ל- CLIProxyAPI       |

הגדר לכל ספק:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## לוח המחוונים UI

### הגדרות → Proxy Tab

- **פרוקסי גלובלי** תצורה (הגדר פעם אחת עבור כל התעבורה)
- **פרוקסי לכל ספק** עוקף
- **פרוקסי לכל חיבור** משימות
- **בדיקת חיבור** דרך פרוקסי מוגדר
- **תגים מקודדים בצבע** מציג רמת פרוקסי פעילה

### הגדרות → 1proxy Tab

- **סנכרן עכשיו** לחצן כדי להביא פרוקסי בחינם
- **כרטיסי סטטיסטיקה** : סה"כ, פעיל, איכות ממוצעת, סנכרון אחרון
- **מסננים** : פרוטוקול, קוד מדינה, איכות מינימלית
- **טבלת פרוקסי** עם מארח, פרוטוקול, מדינה, ציון איכות, חביון, אנונימיות, גישת Google
- **סטטוס סנכרון** פאנל עם מעקב success/failure וספירת כשלים רצופה
- **נקה הכל** כדי להסיר את כל ערכי 1proxy

---

## API

### הגדרות פרוקסי API

| שִׁיטָה  | נקודת קצה                                      | תֵאוּר                |
| -------- | ---------------------------------------------- | --------------------- |
| `GET`    | `/api/settings/proxy`                          | קבל תצורת proxy מלאה  |
| `GET`    | `/api/settings/proxy?level=global`             | קבל פרוקסי גלובלי     |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | קבל פרוקסי של ספק     |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | פתרון פרוקסי יעיל     |
| `PUT`    | `/api/settings/proxy`                          | עדכן את תצורת ה-proxy |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | הסר פרוקסי ברמה       |

### רישום proxy API

| שִׁיטָה  | נקודת קצה                                         | תֵאוּר                  |
| -------- | ------------------------------------------------- | ----------------------- |
| `GET`    | `/api/v1/management/proxies`                      | רשום את כל פרוקסי       |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | קבל פרוקסי על ידי ID    |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | קבל הקצאות פרוקסי       |
| `POST`   | `/api/v1/management/proxies`                      | צור פרוקסי              |
| `PATCH`  | `/api/v1/management/proxies`                      | עדכן פרוקסי             |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | מחק פרוקסי              |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | כפה מחיקה               |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | הקצאה בכמות גדולה       |
| `GET`    | `/api/v1/management/proxies/assignments`          | רשימת מטלות             |
| `GET`    | `/api/v1/management/proxies/health`               | סטטיסטיקת בריאות פרוקסי |

### מנהרות API

לחשיפת מופע OmniRoute שלך לאינטרנט הציבורי (Cloudflare/ngrok/Tailscale) במקום ניתוב יוצא דרך פרוקסי, ראה [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). המנהרה REST API חיה תחת `/api/tunnels/{cloudflared,ngrok,tailscale}/*` והיא אורתוגונלית לשרשרת ה-proxy היוצאת שתועדה לעיל.

### 1 פרוקסי API

| שִׁיטָה  | נקודת קצה                              | תֵאוּר                          |
| -------- | -------------------------------------- | ------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | רשום 1 פרוקסי פרוקסי            |
| `GET`    | `/api/settings/oneproxy?action=stats`  | קבל סטטיסטיקה של סטטוס סנכרון + |
| `GET`    | `/api/settings/oneproxy?action=status` | קבל סטטוס סנכרון בלבד           |
| `POST`   | `/api/settings/oneproxy`               | הפעל סנכרון                     |
| `POST`   | `/api/settings/oneproxy/rotate`        | סובב ל-proxy הבא                |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | מחק אחד                         |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | נקה הכל                         |

### Upstream Proxy API

| שִׁיטָה  | נקודת קצה                         | תֵאוּר                          |
| -------- | --------------------------------- | ------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | קבל תצורת פרוקסי במעלה הזרם     |
| `PUT`    | `/api/upstream-proxy/:providerId` | הגדר מצב פרוקסי במעלה הזרם      |
| `DELETE` | `/api/upstream-proxy/:providerId` | הסר את תצורת ה-proxy במעלה הזרם |

---

## משתני סביבה

| מִשְׁתַנֶה            | בְּרִירַת מֶחדָל | תֵאוּר                                                          |
| --------------------- | ---------------- | --------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`           | אפשר תמיכה ב-proxy SOCKS5 (ברירת מחדל `true` ב- `.env.example`) |

---

## פתרון בעיות

### "פרוקסי SOCKS5 מושבת"

הגדר `ENABLE_SOCKS5_PROXY=true` בקובץ `.env` שלך והפעל מחדש.

### שגיאות "ניתוק שקע" דרך פרוקסי

זה נורמלי עם פרוקסי זולים שמפילים חיבורים סרק. OmniRoute כבר מטפל בזה על ידי:

- השבתת Keep-alive בחיבורי פרוקסי (`keepAliveTimeout: 1`)
- השבתת צנרת (`pipelining: 0`)
- שמירה במטמון לשולחים כדי למנוע לחיצות ידיים חוזרות

אם זה נמשך, נסה פרוקסי אחר או השתמש בתכונת סיבוב 1proxy.

### "unsupported_country_region_territory" במהלך OAuth

ודא שהפרוקסי מוגדר** לִפנֵי** התחלת זרימת OAuth. OmniRoute מנתב את החלפת האסימונים OAuth דרך ה-proxy המוגדר. תחילה הגדר פרוקסי גלובלי או ברמת הספק ולאחר מכן התחבר.

### פרוקסי לא בשימוש

בדוק את סדר הרזולוציה:

1. אמת עם `GET /api/settings/proxy?resolve=your-connection-id`
2. בדוק אם ה-proxy `status` הוא `active` (לא `inactive`)
3. ודא שהיקף הקצאת ה-proxy תואם את החיבור שלך

### סנכרון 1 פרוקסי נכשל

בדוק את מצב הסנכרון:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

אם `consecutiveFailures >= 5`, המפסק נפל. הפעל מחדש את השרת כדי לאפס, או המתן לאיפוס ידני.

---

## סכמת מסד נתונים

### שולחן `proxy_registry`

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

### שולחן `proxy_assignments`

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

## בדיקת תקינות פרוקסי (v3.8.16 +)

של OmniRoute** פרוקסי מהיר-נכשל** מנגנון (`src/lib/proxyHealth.ts`) מזהה פרוקסי מתים ב- < 2s באמצעות בדיקת חיבור TCP מהירה, ואז** מאחסנת את התוצאה** כדי למנוע תקורה לפי בקשה.

### איך זה עובד

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

בלי זה, פרוקסי מת יחסום כל בקשה ל- `PROXY_TIMEOUT_MS` המלא (ברירת המחדל של 30s) לפני כשל.

### משתני סביבה ניתנים לכוונון

| מִשְׁתַנֶה                   | בְּרִירַת מֶחדָל | מַטָרָה                             |
| ---------------------------- | ---------------- | ----------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`           | פסק זמן לחיבור TCP לכל בדיקת תקינות |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`          | כמה זמן תוצאת בריאות נשמרת במטמון   |

**ערכים מומלצים:**

| תַרחִישׁ               | פסק זמן מהיר של כשל | מטמון TTL | הַנמָקָה                                                         |
| ---------------------- | ------------------- | --------- | ---------------------------------------------------------------- |
| שער API בתפוקה גבוהה   | 1500 אלפיות השנייה  | 60000ms   | מטמון ארוך יותר, מהיר כישלון אגרסיבי לצמצום בדיקות               |
| צמתים בחלוקה גיאוגרפית | 3000ms              | 15000ms   | רשתות איטיות יותר זקוקות ליותר זמן; מטמון קצר יותר עבור כשל מהיר |
| מפתח / בדיקה           | 1000 אלפיות השנייה  | 10000ms   | איטרציה מהירה על פרוקסי מקומיים                                  |
| התגנבות / אנטי גילוי   | 2500ms              | 45000ms   | הימנע מחיטוט מהיר שעלול להפעיל מגבלות קצב                        |

### בדיקת בריאות פרוקסי

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

דגל `stale` הוא `true` כאשר ערך המטמון חרג מ- `HEALTH_CACHE_TTL_MS` והבקשה הבאה תפעיל בדיקה חדשה.

### ברירת מחדל לפי סוג פרוקסי

בדיקת הבריאות משתמשת בברירות מחדל הגיוניות המבוססות על סכימת URL :

| תָכְנִית                   | יציאת ברירת מחדל |
| -------------------------- | ---------------- |
| `http://`                  | 8080             |
| `https://`                 | 443              |
| `socks5://` / `socks5h://` | 1080             |

יציאות מותאמות אישית ב- URL (`http://host:9999`) תמיד מקבלות עדיפות על ברירת המחדל של הסכימה.

---

## ניתוח פרוקסי ותצפית

OmniRoute עוקב אחר שימוש לכל פרוקסי כדי לעזור למפעילים לאבחן דפוסי ניתוב, עליות חביון וכשלים חוזרים.

### מה מעקב

עבור כל בקשה דרך פרוקסי מוגדר, OmniRoute רושם:

| מֶטרִי       | תֵאוּר                                   |
| ------------ | ---------------------------------------- |
| `proxy_url`  | Proxy מלא URL (עם אישורי אישור מוסווים)  |
| `provider`   | ספק במעלה הזרם ID (אופנאי, אנתרופי וכו') |
| `latency_ms` | זמן סה"כ הלוך ושוב כולל לחיצת יד פרוקסי  |
| `connect_ms` | זמן חיבור TCP בלבד                       |
| `status`     | קוד סטטוס HTTP ממעלה הזרם                |
| `error`      | מחלקת שגיאה אם הבקשה נכשלה               |
| `timestamp`  | ISO 8601 UTC                             |

### גישה לנתונים

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

נקודת הקצה האמיתית היא `/api/usage/proxy-logs` (ראה `src/app/api/usage/proxy-logs/route.ts`). נקודת קצה זו תומכת ב:

- `GET /api/usage/proxy-logs` — אחזר יומני פרוקסי
- `DELETE /api/usage/proxy-logs` — נקה את כל יומני ה-proxy

ניתן לשאול נתונים סטטיסטיים מצטברים ישירות מטבלת `proxy_logs` דרך SQL במידת הצורך. לוח המחוונים UI עשוי להציע תצוגות מצטברות.

### דפוסים נפוצים

**זיהוי פרוקסי מתנופף** (מתחלף בין success/failure):

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

**מצא פרוקסי איטיים** (חביון p95 > 2s):

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

## עץ החלטות אסטרטגיית סיבוב

כאשר מספר פרוקסי מוקצים ל-scope, OmniRoute משתמש ב-a** אסטרטגיית סיבוב** כדי לבחור באיזה מהם להשתמש עבור כל בקשה. האסטרטגיה מוגדרת ברמת ההיקף (גלובל, לכל ספק, לכל חשבון, לכל שילוב).

### אסטרטגיות זמינות

| אִסטרָטֶגִיָה          | מתי להשתמש                     | פשרה                                                      |
| ---------------------- | ------------------------------ | --------------------------------------------------------- |
| `quality` (ברירת מחדל) | ייצור עם פרוקסי באיכות מעורבת  | מעדיף פרוקסי בדירוג גבוה; עלול להרעיב אנשים עם דירוג נמוך |
| `random`               | חלוקת עומסים, פרטיות           | הפצה שווה; מתעלם מאותות איכות                             |
| `sequential`           | איתור באגים, בדיקה דטרמיניסטית | עובר מחזורי פרוקסי לפי הסדר; קל לנמק                      |

### עץ החלטות

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

## אי הכללת כשלים אוטומטית עבור פרוקסי משלך

מאגר 1proxy marketplace כבר משפיל אוטומטית פרוקסי שנכשלו בעצמו (ראה [ציוני איכות פרוקסי](#proxy-quality-scores) ). עבור פרוקסי** אַתָה** נוסף לרישום, מתזמן בריאות הרקע (`src/lib/proxyHealth/scheduler.ts`) מספק את אותה התנהגות "הסר חבר מת מהשרשרת באופן אוטומטי", מבלי למחוק דבר:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

איך זה משתלב בשרשרת מרובת פרוקסי:

1. המתזמן בודק כל פרוקסי רשום בכל `PROXY_HEALTH_INTERVAL_MS` (ברירת מחדל 10 דקות; מינימום 1 דקה).
2. אחרי `PROXY_AUTO_REMOVE_AFTER` רצוף** מַכרִיעַ** כשלים (כשל אמיתי בחיבור — פסק זמן או 5xx של יעד הבדיקה עצמו לעולם לא נחשב, ראה [בדיקת תקינות Proxy](#proxy-health-checking-v3816) ), `status` של ה-proxy מוגדר ל- `dead`.
3. `dead` הוא אחד מהסטטוסים שמסנן הסטטוס החי בשימוש על ידי רזולוציית pool/rotation אינו כולל, כך שסיבוב של scope (סיבובי / אקראי / דביק / חביון — ראה [עץ החלטות אסטרטגיית סיבוב](#rotation-strategy-decision-tree) ) מפסיק מיד להעביר את ה-proxy לבקשות חדשות. שום פרוקסי אחר בבריכה לא מושפע, והבריכה כולה לעולם לא נופלת בשקט בחזרה לחיבור ישיר — לראות את ה [-4-Level Proxy System](#4-level-proxy-system) כשל סגור השמירה.
4. המתזמן ממשיך לבחון פרוקסי `dead` באותו מרווח. הבדיקה המוצלחת הבאה הופכת `status` בחזרה ל- `active` והוא נכנס מחדש לסיבוב — ללא צורך בהוספה ידנית מחדש.

זה בכוונה** opt-in ולא הרסני** : כברירת מחדל, המתזמן סופר ומתעד רק כשלים (ראה מדיניות C ב- `decision.ts`), ו- `PROXY_AUTO_DISABLE` אף פעם לא מוחק שורה — שעבורו מיועד דגל `PROXY_AUTO_REMOVE` הנפרד והאגרסיבי יותר. אם שניהם מוגדרים ל- `true`, `PROXY_AUTO_REMOVE` מנצח (לפרוקסי שעומד להימחק אין שימוש ב-soft-disable ביניהם). עיין בהפניה [לתצורת הסביבה](../reference/ENVIRONMENT.md) עבור רשימת המשתנים המלאה.

---

> 📖** תיעוד קשור:**
>
> - [מדריך למשתמש](../guides/USER_GUIDE.md) — הגדרה ותצורה כללית - [API הפניה](../reference/API_REFERENCE.md) — תיעוד API מלא - [תצורת סביבה](../reference/ENVIRONMENT.md) — כל משתני הסביבה
