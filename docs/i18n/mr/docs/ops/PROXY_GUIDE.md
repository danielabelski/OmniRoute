# 🌐 OmniRoute Proxy Guide (मराठी)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **भौगोलिक ब्लॉकला बायपास करा, तुमच्या ओळखीचे रक्षण करा आणि शून्य कॉन्फिगरेशन जटिलतेसह कोणत्याही प्रॉक्सी — द्वारे AI रहदारीला मार्ग द्या.**

OmniRoute मध्ये एक पूर्ण-वैशिष्ट्यीकृत प्रॉक्सी व्यवस्थापन प्रणाली समाविष्ट आहे जी तुम्हाला HTTP, HTTPS, किंवा SOCKS5 प्रॉक्सी द्वारे अपस्ट्रीम AI प्रदाता रहदारी मार्गी लावू देते. तुम्ही ब्लॉक केलेल्या प्रदेशात असलात, IP रोटेशनची गरज आहे किंवा तुम्हाला स्टेल्थ फिंगरप्रिंटिंग — हवे आहे, हे मार्गदर्शक सर्वकाही कव्हर करते.

---

## सामग्री सारणी

- [प्रॉक्सी का वापरायचे?](#why-use-proxies)
- [आर्किटेक्चर विहंगावलोकन](#architecture-overview)
- [4-स्तरीय प्रॉक्सी सिस्टम](#4-level-proxy-system)
- [प्रॉक्सी रजिस्ट्री (CRUD)](#proxy-registry-crud)
- [1प्रॉक्सी फ्री मार्केटप्लेस](#1proxy-free-proxy-marketplace)
- [प्रॉक्सी रोटेशन](#proxy-rotation)
- [अँटी-डिटेक्शन आणि स्टिल्थ](#anti-detection--stealth)
- [अपस्ट्रीम प्रॉक्सी मोड](#upstream-proxy-modes)
- [डॅशबोर्ड UI](#dashboard-ui)
- [API संदर्भ](#api-reference)
- [पर्यावरण परिवर्तने](#environment-variables)
- [समस्यानिवारण](#troubleshooting)

---

## प्रॉक्सी का वापरायचे?

अनेक AI प्रदाते भौगोलिक प्रदेशानुसार प्रवेश प्रतिबंधित करतात. मध्ये विकासक** रशिया, चीन, इराण, क्युबा, तुर्की** , आणि इतर देशांमध्ये त्रुटी आढळतात जसे:

```
unsupported_country_region_territory
```

बाहेरील अवरोधित प्रदेशांमध्येही, प्रॉक्सी यासाठी उपयुक्त आहेत:

| केस वापरा          | वर्णन                                                                       |
| ------------------ | --------------------------------------------------------------------------- |
| **भौगोलिक बायपास** | ब्लॉक केलेल्या देशांमधून OpenAI, Anthropic, Codex, Copilot मध्ये प्रवेश करा |
| **IP रोटेशन**      | दर मर्यादा टाळण्यासाठी एकाधिक IPs मध्ये विनंत्या वितरित करा                 |
| **गोपनीयता**       | अपस्ट्रीम प्रदात्यांकडून तुमचा वास्तविक IP लपवा                             |
| **अनुपालन**        | विशिष्ट अधिकारक्षेत्रातून रहदारी मार्गी लावा                                |
| **चाचणी**          | विविध क्षेत्रांतील विनंत्यांचे अनुकरण करा                                   |

---

## आर्किटेक्चर विहंगावलोकन

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

### मुख्य घटक

| घटक                     | फाईल                                         | भूमिका                                                |
| ----------------------- | -------------------------------------------- | ----------------------------------------------------- |
| **प्रॉक्सी रेजिस्ट्री** | `src/lib/db/proxies.ts`                      | प्रॉक्सी एंट्रीसाठीCRUD + स्कोप असाइनमेंट             |
| **प्रॉक्सी डिस्पॅचर**   | `open-sse/utils/proxyDispatcher.ts`          | कॅशिंगसह `undici` ProxyAgent/SOCKS डिस्पॅचर तयार करते |
| **प्रॉक्सी आणणे**       | `open-sse/utils/proxyFetch.ts`               | प्रॉक्सी डिस्पॅचर इंजेक्शनसह `fetch()` गुंडाळते       |
| **सेटिंग्ज मार्ग**      | `src/app/api/settings/proxy/route.ts`        | लेगसी प्रॉक्सी कॉन्फिगरेशन API (GET/PUT/DELETE)       |
| **व्यवस्थापन मार्ग**    | `src/app/api/v1/management/proxies/route.ts` | नोंदणी CRUD API (GET/POST/PATCH/DELETE)               |
| **1 प्रॉक्सी DB**       | `src/lib/db/oneproxy.ts`                     | मोफत प्रॉक्सी मार्केटप्लेस चिकाटी                     |

---

## नवीन खात्यांसाठी डीफॉल्ट प्रॉक्सी स्थिती

मध्ये** सेटिंग्ज → प्रॉक्सी → ग्लोबल कॉन्फिगरेशन** , वापरा** नवीन कनेक्शनसाठी डीफॉल्टनुसार प्रॉक्सी सक्षम करा** नव्याने जोडलेल्या प्रदाता खात्यांची प्रारंभिक प्रॉक्सी स्थिती निवडण्यासाठी.

नवीन सेटिंग नवीन जोडलेल्या प्रदाता खात्यांची प्रारंभिक प्रॉक्सी स्थिती नियंत्रित करते. हे विद्यमान खाती बदलत नाही किंवा जागतिक प्रॉक्सी स्विच बदलत नाही. त्याचे प्रारंभिक मूल्य मागील वर्तन संरक्षित करते. डीफॉल्टनुसार अक्षम केलेल्या प्रॉक्सीसह भविष्यातील खाती तयार करण्यासाठी ते एकदा बंद करा.

प्राधान्य विद्यमान सेटिंग्ज API द्वारे `defaultNewConnectionProxyEnabled` म्हणून संग्रहित केले जाते. कधीही सेव्ह न केल्यावर ते `true` वर डीफॉल्ट होते. `false` जतन करणे नंतरच्या नवीन खात्यांसाठी रीस्टार्ट न करता प्रभावी होते. `POST /api/providers` वैकल्पिक कठोर बुलियन `proxyEnabled` स्वीकारते; एक स्पष्ट `true` किंवा `false` निर्मिती डीफॉल्ट वर प्राधान्य घेते. डुप्लिकेट खात्यावरील वगळणे किंवा OAuth रीकनेक्ट त्या खात्याची संचयित स्थिती राखून ठेवते. वैयक्तिक खाती त्यानंतरही सक्षम किंवा अक्षम केली जाऊ शकतात.

निवडक प्रदाता हस्तांतरण नवीन खात्यांसाठी गंतव्य स्थापनेचे डीफॉल्ट वापरतात आणि विद्यमान खाती बदलताना गंतव्य धोरण जतन करतात. प्रॉक्सी टॉगल पोर्टेबल ट्रान्सफर फील्ड नाहीत. संपूर्ण बॅकअप पुनर्संचयित करणे आणि ऐतिहासिक JSON/SQL स्थलांतर त्यांचे विद्यमान पुनर्संचयित शब्दार्थ राखून ठेवतात, जतन केलेली खाते मूल्ये आणि लेगसी स्कीमा डीफॉल्टसह; पूर्ण सेटिंग्ज पुनर्संचयित करणे हे प्राधान्य पुनर्संचयित देखील करू शकते.

हे प्राधान्य प्रॉक्सी नियुक्त करत नाही किंवा एखादी व्यक्ती निरोगी किंवा वापरात आहे हे स्थापित करत नाही. वास्तविक राउटिंग अजूनही ग्लोबल प्रॉक्सी स्विच आणि लागू प्रॉक्सी कॉन्फिगरेशनवर अवलंबून आहे. सक्तीचे खाते नसलेले सिंथेटिक प्रदाते, खाते तयार करण्यापूर्वी OAuth रहदारी, environment/system प्रॉक्सी आणि बाह्य बॅकएंडचे नेटवर्किंग त्याच्या कार्यक्षेत्राबाहेर आहेत.

## 4-स्तरीय प्रॉक्सी सिस्टम

OmniRoute येथे प्रॉक्सी कॉन्फिगरेशनचे समर्थन करते** चार स्वतंत्र स्कोप** , प्राधान्य क्रमाने निराकरण केले:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### रिझोल्यूशन कसे कार्य करते

जेव्हा OmniRoute अपस्ट्रीम प्रदात्याला विनंती पाठवते, तेव्हा ते `resolveProxyForConnectionFromRegistry()` ला कॉल करते जे प्रत्येक स्तर क्रमाने तपासते:

1. **खाते-स्तर** — या विशिष्ट कनेक्शन ID ला प्रॉक्सी नियुक्त केली आहे का?
2. **प्रदाता-स्तर** — या प्रदात्याला प्रॉक्सी नियुक्त केली आहे (उदा. `openai`)?
3. **जागतिक स्तरावर** — जागतिक प्रॉक्सी कॉन्फिगर केलेली आहे का?
4. **प्रॉक्सी नाही** — प्रदात्याशी थेट कनेक्शन.

पहिला सामना जिंकतो. याचा अर्थ तुम्ही फॉलबॅक म्हणून जागतिक प्रॉक्सी सेट करू शकता परंतु विशिष्ट प्रदाते किंवा कनेक्शनसाठी ते अधिलिखित करू शकता.

### काय प्रॉक्सी मिळते

| रहदारीचा प्रकार     | प्रॉक्सीड? | नोट्स                                         |
| ------------------- | ---------- | --------------------------------------------- |
| गप्पा पूर्ण झाल्या  | ✅         | सर्व `/v1/chat/completions` विनंत्या          |
| एम्बेडिंग           | ✅         | `/v1/embeddings`                              |
| प्रतिमा निर्मिती    | ✅         | `/v1/images/generations`                      |
| ऑडिओ (TTS/STT)      | ✅         | `/v1/audio/*`                                 |
| OAuth टोकन एक्सचेंज | ✅         | `unsupported_country_region_territory` सोडवते |
| कनेक्शन चाचण्या     | ✅         | "टेस्ट कनेक्शन" बटण प्रॉक्सी वापरते           |
| टोकन रिफ्रेश        | ✅         | पार्श्वभूमी OAuth नूतनीकरण                    |
| मॉडेल समक्रमण       | ✅         | मॉडेल सूची आणि शोध                            |

---

## प्रॉक्सी रजिस्ट्री (CRUD)

प्रॉक्सी रेजिस्ट्री एक SQLite टेबल (`proxy_registry`) आहे जी तुमच्या सर्व प्रॉक्सी संग्रहित करते. प्रत्येक प्रॉक्सीमध्ये आहे:

| फील्ड      | प्रकार   | वर्णन                                            |
| ---------- | -------- | ------------------------------------------------ |
| `id`       | UUID     | अद्वितीय ओळखकर्ता                                |
| `name`     | स्ट्रिंग | मानवी-वाचनीय लेबल                                |
| `type`     | स्ट्रिंग | प्रोटोकॉल: `http`, `https`, `socks5`             |
| `host`     | स्ट्रिंग | प्रॉक्सी होस्टनाव किंवा IP                       |
| `port`     | पूर्णांक | पोर्ट नंबर                                       |
| `username` | स्ट्रिंग | प्रमाणीकरण वापरकर्तानाव (उर्वरित ठिकाणी कूटबद्ध) |
| `password` | स्ट्रिंग | प्रमाणीकरण संकेतशब्द (उर्वरित ठिकाणी कूटबद्ध)    |
| `region`   | स्ट्रिंग | भौगोलिक प्रदेश लेबल                              |
| `notes`    | स्ट्रिंग | मुक्त-मजकूर नोट्स                                |
| `status`   | स्ट्रिंग | `active` किंवा `inactive`                        |
| `source`   | स्ट्रिंग | `manual` किंवा `oneproxy`                        |

### प्रॉक्सी तयार करणे

**डॅशबोर्ड द्वारे:**

1. वर जा** सेटिंग्ज → प्रॉक्सी**
2. क्लिक करा** प्रॉक्सी जोडा**
3. प्रकार, होस्ट, पोर्ट आणि पर्यायी प्रमाणीकरण क्रेडेन्शियल भरा
4. जतन करा

**API द्वारे:**

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

### प्रॉक्सी अपडेट करत आहे

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **टीप:** तुम्ही स्पष्टपणे नॉन-रिक्त बदली पाठवल्याशिवाय क्रेडेन्शियल जतन केले जातात. `username`/`password` साठी रिकाम्या स्ट्रिंग पाठवल्याने संग्रहित मूल्ये कायम राहतील.

### प्रॉक्सी हटवत आहे

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### सूची प्रॉक्सी

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### कार्यक्षेत्रासाठी प्रॉक्सी नियुक्त करणे

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

### प्रभावी प्रॉक्सी निराकरण

दिलेल्या कनेक्शनसाठी कोणती प्रॉक्सी वापरली जाईल ते तपासा:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

निराकरण केलेले प्रॉक्सी त्याच्या स्तरासह (`account`, `provider`, किंवा `global`) आणि स्त्रोतासह परत करते.

### मोठ्या प्रमाणात असाइनमेंट

एकाच वेळी एकाधिक प्रदाते किंवा कनेक्शनला एक प्रॉक्सी नियुक्त करा:

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

मध्ये प्रॉक्सी समाविष्ट आहेत**Backup/Restore** प्रणाली जेव्हा तुम्ही तुमचे OmniRoute कॉन्फिगरेशन एक्सपोर्ट करता:

1. वर जा** डॅशबोर्ड → सेटिंग्ज → बॅकअप**
2. क्लिक करा** निर्यात करा** — प्रॉक्सी नोंदणी आणि असाइनमेंट समाविष्ट आहेत
3. पुनर्संचयित करण्यासाठी, क्लिक करा** आयात करा** आणि बॅकअप फाइल अपलोड करा

प्रॉक्सी नोंदणी देखील समर्थन करते** यजमान + पोर्ट द्वारे upsert** — जर तुम्ही आधीपासून अस्तित्वात असलेली प्रॉक्सी आयात केली (समान होस्ट आणि पोर्ट), ते डुप्लिकेट तयार करण्याऐवजी अपडेट होते.

### वारसा स्थलांतर

तुम्ही जुन्या आवृत्तीमध्ये (पूर्व-नोंदणी) प्रॉक्सी कॉन्फिगर केल्यास, OmniRoute त्यांना आपोआप स्थलांतरित करते:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

हे अपग्रेड नंतर पहिल्या स्टार्टअपवर एकदा होते. पुन्हा चालवण्यासाठी `migrateLegacyProxyConfigToRegistry({ force: true })` वापरा.

---

## 1प्रॉक्सी फ्री प्रॉक्सी मार्केटप्लेस

> 🆕** [@oyi77](https://github.com/oyi77) द्वारे योगदान दिले** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (अंक [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute सह समाकलित होते** [1 प्रॉक्सी](https://1proxy-api.aitradepulse.com)** प्रवेश प्रदान करण्यासाठी समुदाय मंच** शेकडो विनामूल्य, प्रमाणित प्रॉक्सी** जगभरातून. ज्या वापरकर्त्यांची स्वतःची प्रॉक्सी इन्फ्रास्ट्रक्चर नाही त्यांच्यासाठी हे योग्य आहे.

### हे कसे कार्य करते

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **सिंक** — OmniRoute 1proxy API वरून प्रमाणित प्रॉक्सी आणते
2. **स्टोअर** — प्रॉक्सी `source = 'oneproxy'` सह समान `proxy_registry` टेबलमध्ये जतन केले जातात
3. **फिल्टर करा** — प्रोटोकॉल, देश, गुणवत्ता स्कोअरनुसार फिल्टर करा
4. **फिरवा** — गुणवत्ता, यादृच्छिक किंवा अनुक्रमिक धोरणे वापरून सर्वोत्तम प्रॉक्सी निवडा
5. **ऑटो-डिग्रेड** — अयशस्वी प्रॉक्सी त्यांच्या गुणवत्तेचा स्कोअर कमी करतात; खाली थ्रेशोल्ड → निष्क्रिय म्हणून चिन्हांकित केले आहे

### प्रॉक्सी सिंक करत आहे

**डॅशबोर्ड द्वारे:**

1. वर जा** सेटिंग्ज → 1proxy** टॅब
2. क्लिक करा** "आता समक्रमित करा"**
3. आकडेवारी पहा: एकूण प्रॉक्सी, सक्रिय संख्या, सरासरी गुणवत्ता, देशानुसार ब्रेकडाउन

**API द्वारे:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### फिल्टरिंग प्रॉक्सी

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

### प्रॉक्सी गुणवत्ता स्कोअर

प्रत्येक 1 प्रॉक्सी प्रॉक्सी मेटाडेटासह येते:

| फील्ड           | वर्णन                                         |
| --------------- | --------------------------------------------- |
| `qualityScore`  | 1प्रॉक्सी प्रमाणीकरण पासून 0-100 रेटिंग       |
| `latencyMs`     | नेटवर्क लेटन्सी मोजली                         |
| `anonymity`     | `transparent`, `anonymous`, किंवा `elite`     |
| `googleAccess`  | प्रॉक्सी Google सेवांमध्ये प्रवेश करू शकते का |
| `countryCode`   | दोन-अक्षरी ISO देश कोड                        |
| `lastValidated` | अंतिम प्रमाणीकरणाचा टाइमस्टॅम्प               |

गुणवत्ता स्कोअर डायनॅमिकरित्या समायोजित केले जातात:

- **अयशस्वी विनंत्या** 10 गुणांनी गुण कमी करा
- **स्कोअर ≤ 10 वर घसरला** → प्रॉक्सी `inactive` चिन्हांकित आहे
- निष्क्रिय प्रॉक्सी रोटेशनमधून वगळल्या जातात

### रोटेशन स्ट्रॅटेजीज

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

### सर्किट ब्रेकर

1प्रॉक्सी सिंकमध्ये अंगभूत सर्किट ब्रेकर आहे:

- नंतर** 5 सलग सिंक अयशस्वी** , पुढील समक्रमण प्रयत्न अवरोधित केले आहेत
- यासह रीसेट करा: `resetOneproxyCircuitBreaker()` किंवा सर्व्हर रीस्टार्ट करा
- `GET /api/settings/oneproxy?action=status` वर सिंक स्थिती उपलब्ध आहे

### 1 प्रॉक्सी प्रॉक्सी साफ करत आहे

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## अँटी-डिटेक्शन आणि स्टिल्थ

OmniRoute केवळ प्रॉक्सी — द्वारे रहदारीला मार्ग देत नाही त्यामुळे रहदारी कायदेशीर दिसते:

### TLS फिंगरप्रिंट स्पूफिंग

ब्राउझर सारखे TLS फिंगरप्रिंट व्युत्पन्न करण्यासाठी `wreq-js` वापरते, बॉट डिटेक्शन सिस्टमला बायपास करून जे ब्राउझर नसलेल्या TLS हँडशेकला ध्वजांकित करते.

### CLI फिंगरप्रिंट मॅचिंग

द**CLI फिंगरप्रिंट टॉगल** (`Settings → Security`) नेटिव्ह CLI बायनरी (Claude कोड, Codex, इ.) च्या अचूक स्वाक्षरीशी जुळण्यासाठी HTTP शीर्षलेख आणि JSON बॉडी फील्डची पुनर्रचना करते. हे कार्य करते** च्या वर** प्रॉक्सी:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

तुम्हाला दोन्ही मिळतील**IP मास्किंग** आणि** सत्यतेची विनंती करा** एकाच वेळी

### प्रॉक्सी IP संरक्षण

डॅशबोर्डमधील कलर-कोड केलेले बॅज कोणते प्रॉक्सी स्तर सक्रिय आहे हे दर्शवतात:

| बॅज | पातळी   | अर्थ                                      |
| --- | ------- | ----------------------------------------- |
| 🟢  | जागतिक  | सर्व रहदारी या प्रॉक्सीमधून जाते          |
| 🟡  | प्रदाता | फक्त या प्रदात्याची रहदारी प्रॉक्सी आहे   |
| 🔵  | जोडणी   | हे विशिष्ट key/account ही प्रॉक्सी वापरते |

बॅज पडताळणीसाठी सोडवलेला प्रॉक्सी IP देखील दाखवतो.

---

## अपस्ट्रीम प्रॉक्सी मोड

CLIProxyAPI पॅटर्न वापरणाऱ्या प्रदात्यांसाठी, OmniRoute तीन अपस्ट्रीम प्रॉक्सी मोडला समर्थन देते:

| मोड           | वर्णन                                            |
| ------------- | ------------------------------------------------ |
| `native`      | OmniRoute थेट प्रॉक्सी राउटिंग हाताळते (डीफॉल्ट) |
| `cliproxyapi` | बाह्य CLIProxyAPI उदाहरणासाठी प्रतिनिधी          |
| `fallback`    | प्रथम मूळ प्रयत्न करतो, CLIProxyAPI वर येतो      |

प्रति-प्रदाता कॉन्फिगर करा:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## डॅशबोर्ड UI

### सेटिंग्ज → प्रॉक्सी टॅब

- **ग्लोबल प्रॉक्सी** कॉन्फिगरेशन (सर्व रहदारीसाठी एकदा सेट करा)
- **प्रति-प्रदाता प्रॉक्सी** अधिलिखित करते
- **प्रति-कनेक्शन प्रॉक्सी** असाइनमेंट
- **कनेक्शन चाचणी** कॉन्फिगर केलेल्या प्रॉक्सीद्वारे
- **रंग-कोडित बॅज** सक्रिय प्रॉक्सी पातळी दर्शवित आहे

### सेटिंग्ज → 1प्रॉक्सी टॅब

- **आता सिंक करा** विनामूल्य प्रॉक्सी आणण्यासाठी बटण
- **आकडेवारी कार्ड** : एकूण, सक्रिय, सरासरी गुणवत्ता, अंतिम समक्रमण
- **फिल्टर** : प्रोटोकॉल, देश कोड, किमान गुणवत्ता
- **प्रॉक्सी टेबल** यजमान, प्रोटोकॉल, देश, गुणवत्ता स्कोअर, विलंबता, निनावीपणा, Google प्रवेशासह
- **सिंक स्थिती** success/failure ट्रॅकिंग आणि सलग अपयशी संख्या असलेले पॅनेल
- **सर्व साफ करा** सर्व 1 प्रॉक्सी नोंदी काढण्यासाठी

---

## API संदर्भ

### प्रॉक्सी सेटिंग्ज API

| पद्धत    | अंत्यबिंदू                                     | वर्णन                            |
| -------- | ---------------------------------------------- | -------------------------------- |
| `GET`    | `/api/settings/proxy`                          | पूर्ण प्रॉक्सी कॉन्फिगरेशन मिळवा |
| `GET`    | `/api/settings/proxy?level=global`             | जागतिक प्रॉक्सी मिळवा            |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | प्रदाता प्रॉक्सी मिळवा           |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | प्रभावी प्रॉक्सी सोडवा           |
| `PUT`    | `/api/settings/proxy`                          | प्रॉक्सी कॉन्फिगरेशन अपडेट करा   |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | स्तरावर प्रॉक्सी काढा            |

### प्रॉक्सी रेजिस्ट्री API

| पद्धत    | अंत्यबिंदू                                        | वर्णन                       |
| -------- | ------------------------------------------------- | --------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | सर्व प्रॉक्सींची यादी करा   |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID द्वारे प्रॉक्सी मिळवा    |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | प्रॉक्सी असाइनमेंट मिळवा    |
| `POST`   | `/api/v1/management/proxies`                      | प्रॉक्सी तयार करा           |
| `PATCH`  | `/api/v1/management/proxies`                      | प्रॉक्सी अपडेट करा          |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | प्रॉक्सी हटवा               |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | सक्तीने हटवा                |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | मोठ्या प्रमाणात नियुक्त करा |
| `GET`    | `/api/v1/management/proxies/assignments`          | असाइनमेंटची यादी करा        |
| `GET`    | `/api/v1/management/proxies/health`               | प्रॉक्सी आरोग्य आकडेवारी    |

### बोगदे API

प्रॉक्सीद्वारे आउटबाउंड राउटिंग करण्याऐवजी सार्वजनिक इंटरनेट (Cloudflare/ngrok/Tailscale) वर तुमचे OmniRoute उदाहरण उघड करण्यासाठी, [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) पहा. बोगदा REST API `/api/tunnels/{cloudflared,ngrok,tailscale}/*` अंतर्गत राहतो आणि वर दस्तऐवजीकरण केलेल्या आउटबाउंड प्रॉक्सी चेनसाठी ऑर्थोगोनल आहे.

### 1 प्रॉक्सी API

| पद्धत    | अंत्यबिंदू                             | वर्णन                            |
| -------- | -------------------------------------- | -------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | 1 प्रॉक्सी प्रॉक्सी सूचीबद्ध करा |
| `GET`    | `/api/settings/oneproxy?action=stats`  | आकडेवारी + समक्रमण स्थिती मिळवा  |
| `GET`    | `/api/settings/oneproxy?action=status` | फक्त सिंक स्थिती मिळवा           |
| `POST`   | `/api/settings/oneproxy`               | ट्रिगर सिंक                      |
| `POST`   | `/api/settings/oneproxy/rotate`        | पुढील प्रॉक्सीवर फिरवा           |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | एक हटवा                          |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | सर्व साफ करा                     |

### अपस्ट्रीम प्रॉक्सी API

| पद्धत    | अंत्यबिंदू                        | वर्णन                                |
| -------- | --------------------------------- | ------------------------------------ |
| `GET`    | `/api/upstream-proxy/:providerId` | अपस्ट्रीम प्रॉक्सी कॉन्फिगरेशन मिळवा |
| `PUT`    | `/api/upstream-proxy/:providerId` | अपस्ट्रीम प्रॉक्सी मोड सेट करा       |
| `DELETE` | `/api/upstream-proxy/:providerId` | अपस्ट्रीम प्रॉक्सी कॉन्फिगरेशन काढा  |

---

## पर्यावरण परिवर्तने

| चल                    | डीफॉल्ट | वर्णन                                                                    |
| --------------------- | ------- | ------------------------------------------------------------------------ |
| `ENABLE_SOCKS5_PROXY` | `true`  | SOCKS5 प्रॉक्सी समर्थन सक्षम करा ( `.env.example` मध्ये डीफॉल्ट `true` ) |

---

## समस्यानिवारण

### "SOCKS5 प्रॉक्सी अक्षम आहे"

तुमच्या `.env` फाइलमध्ये `ENABLE_SOCKS5_PROXY=true` सेट करा आणि रीस्टार्ट करा.

### प्रॉक्सीद्वारे "सॉकेट हँग अप" त्रुटी

निष्क्रिय कनेक्शन सोडणाऱ्या स्वस्त प्रॉक्सीसह हे सामान्य आहे. OmniRoute हे आधीच हाताळते:

- प्रॉक्सी कनेक्शन (`keepAliveTimeout: 1`) वर जिवंत ठेवा अक्षम करणे
- पाइपलाइनिंग अक्षम करणे (`pipelining: 0`)
- वारंवार हस्तांदोलन टाळण्यासाठी डिस्पॅचर कॅश करणे

ते कायम राहिल्यास, भिन्न प्रॉक्सी वापरून पहा किंवा 1प्रॉक्सी रोटेशन वैशिष्ट्य वापरा.

### OAuth दरम्यान "unsupported_country_region_territory"

प्रॉक्सी कॉन्फिगर केल्याची खात्री करा** आधी** OAuth प्रवाह सुरू करत आहे. OmniRoute कॉन्फिगर केलेल्या प्रॉक्सीद्वारे OAuth टोकन एक्सचेंजला रूट करते. प्रथम जागतिक किंवा प्रदाता-स्तरीय प्रॉक्सी सेट करा, नंतर कनेक्ट करा.

### प्रॉक्सी वापरली जात नाही

रिझोल्यूशन ऑर्डर तपासा:

1. `GET /api/settings/proxy?resolve=your-connection-id` सह सत्यापित करा
2. प्रॉक्सी `status` `active` आहे का ते तपासा ( `inactive` नाही)
3. प्रॉक्सी असाइनमेंट स्कोप तुमच्या कनेक्शनशी जुळत असल्याची खात्री करा

### 1प्रॉक्सी सिंक अयशस्वी

समक्रमण स्थिती तपासा:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

`consecutiveFailures >= 5` असल्यास, सर्किट ब्रेकर ट्रिप झाला आहे. रीसेट करण्यासाठी सर्व्हर रीस्टार्ट करा किंवा मॅन्युअल रीसेटची प्रतीक्षा करा.

---

## डेटाबेस स्कीमा

### `proxy_registry` टेबल

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

### `proxy_assignments` टेबल

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

## प्रॉक्सी आरोग्य तपासणी (v3.8.16 +)

OmniRoute चे** प्रॉक्सी जलद-अयशस्वी** मेकॅनिझम (`src/lib/proxyHealth.ts`) झटकन TCP कनेक्शन तपासणीद्वारे < 2s मध्ये मृत प्रॉक्सी शोधते, नंतर** परिणाम कॅश करतो** प्रति-विनंती ओव्हरहेड टाळण्यासाठी.

### हे कसे कार्य करते

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

याशिवाय, मृत प्रॉक्सी अयशस्वी होण्यापूर्वी पूर्ण `PROXY_TIMEOUT_MS` (डिफॉल्ट 30s) साठी प्रत्येक विनंती अवरोधित करेल.

### ट्यून करण्यायोग्य पर्यावरण व्हेरिएबल्स

| चल                           | डीफॉल्ट | उद्देश                                  |
| ---------------------------- | ------- | --------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | प्रति आरोग्य तपासणीTCP कनेक्शन कालबाह्य |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | आरोग्य परिणाम किती काळ कॅश केला जातो    |

**शिफारस केलेली मूल्ये:**

| परिस्थिती               | जलद-अयशस्वी कालबाह्य | कॅशे TTL | तर्क                                                      |
| ----------------------- | -------------------- | -------- | --------------------------------------------------------- |
| उच्च-थ्रूपुट API गेटवे  | 1500ms               | 60000ms  | चेक कमी करण्यासाठी आक्रमक फेल-फास्ट, लांब कॅशे            |
| भौगोलिक-वितरित नोड्स    | 3000ms               | 15000ms  | धीमे नेटवर्कला अधिक वेळ लागतो; जलद फेलओव्हरसाठी लहान कॅशे |
| देव / चाचणी             | 1000ms               | 10000ms  | स्थानिक प्रॉक्सी वर द्रुत पुनरावृत्ती                     |
| स्टेल्थ / अँटी-डिटेक्शन | 2500ms               | 45000ms  | जलद तपासणी टाळा ज्यामुळे दर मर्यादा ट्रिगर होऊ शकतात      |

### प्रॉक्सी आरोग्य तपासणी

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

जेव्हा कॅशे एंट्रीने `HEALTH_CACHE_TTL_MS` ओलांडली असेल तेव्हा `stale` ध्वज `true` असेल आणि पुढील विनंती नवीन तपासणी ट्रिगर करेल.

### प्रति-प्रॉक्सी प्रकार डीफॉल्ट

आरोग्य तपासणी URL योजनेच्या आधारे योग्य दोष वापरते:

| योजना                      | डीफॉल्ट पोर्ट |
| -------------------------- | ------------- |
| `http://`                  | 8080          |
| `https://`                 | 443           |
| `socks5://` / `socks5h://` | 1080          |

URL (`http://host:9999`) मधील कस्टम पोर्ट नेहमी स्कीम डीफॉल्टपेक्षा प्राधान्य घेतात.

---

## प्रॉक्सी विश्लेषण आणि निरीक्षणक्षमता

OmniRoute ऑपरेटरना राउटिंग पॅटर्न, लेटन्सी स्पाइक्स आणि आवर्ती अपयशांचे निदान करण्यात मदत करण्यासाठी प्रति-प्रॉक्सी वापराचा मागोवा घेते.

### काय ट्रॅक केले आहे

कॉन्फिगर केलेल्या प्रॉक्सीद्वारे प्रत्येक विनंतीसाठी, OmniRoute रेकॉर्ड करते:

| मेट्रिक      | वर्णन                                                         |
| ------------ | ------------------------------------------------------------- |
| `proxy_url`  | पूर्ण प्रॉक्सी URL (मास्क केलेल्या प्रमाणीकरण क्रेडेन्शियलसह) |
| `provider`   | अपस्ट्रीम प्रदाता ID (openai, anthropic, इ.)                  |
| `latency_ms` | प्रॉक्सी हँडशेकसह एकूण राउंड-ट्रिप वेळ                        |
| `connect_ms` | TCP फक्त कनेक्ट वेळ                                           |
| `status`     | अपस्ट्रीम वरून HTTP स्थिती कोड                                |
| `error`      | विनंती अयशस्वी झाल्यास त्रुटी वर्ग                            |
| `timestamp`  | ISO 8601 UTC                                                  |

### डेटामध्ये प्रवेश करणे

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

वास्तविक अंतबिंदू `/api/usage/proxy-logs` आहे ( `src/app/api/usage/proxy-logs/route.ts` पहा). हा एंडपॉइंट समर्थन देतो:

- `GET /api/usage/proxy-logs` — प्रॉक्सी लॉग पुनर्प्राप्त करा
- `DELETE /api/usage/proxy-logs` — सर्व प्रॉक्सी लॉग साफ करा

आवश्यक असल्यास एकूण आकडेवारी थेट `proxy_logs` टेबलवरून SQL द्वारे विचारली जाऊ शकते. डॅशबोर्ड UI एकूण दृश्ये देऊ शकतो.

### सामान्य नमुने

**फडफडणारी प्रॉक्सी शोधा** ( success/failure मधील पर्यायी):

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

**हळू प्रॉक्सी शोधा** (p95 लेटन्सी > 2s):

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

## रोटेशन स्ट्रॅटेजी डिसिजन ट्री

जेव्हा एका कार्यक्षेत्रासाठी एकाधिक प्रॉक्सी नियुक्त केल्या जातात, तेव्हा OmniRoute a वापरते** रोटेशन धोरण** प्रत्येक विनंतीसाठी कोणता वापरायचा ते निवडण्यासाठी. स्कोप स्तरावर धोरण कॉन्फिगर केले आहे (जागतिक, प्रति-प्रदाता, प्रति-खाते, प्रति-कॉम्बो).

### उपलब्ध धोरणे

| रणनीती              | कधी वापरायचे                          | व्यापार बंद                                                            |
| ------------------- | ------------------------------------- | ---------------------------------------------------------------------- |
| `quality` (डिफॉल्ट) | मिश्र-गुणवत्तेच्या प्रॉक्सीसह उत्पादन | उच्च-रेट केलेल्या प्रॉक्सींना अनुकूल; कमी दर्जाचे लोक उपाशी राहू शकतात |
| `random`            | लोड वितरण, गोपनीयता                   | अगदी वितरण; गुणवत्ता सिग्नलकडे दुर्लक्ष करते                           |
| `sequential`        | डीबगिंग, निर्धारक चाचणी               | क्रमाने प्रॉक्सीद्वारे चक्र; तर्क करणे सोपे                            |

### निर्णय वृक्ष

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

## तुमच्या स्वतःच्या प्रॉक्सींसाठी स्वयंचलित अपयश वगळणे

1प्रॉक्सी मार्केटप्लेस पूल आधीच अयशस्वी प्रॉक्सी स्वतःहून-डिग्रेड करतो ( [प्रॉक्सी गुणवत्ता स्कोअर](#proxy-quality-scores) पहा). प्रॉक्सी साठी** आपण** रेजिस्ट्रीमध्ये जोडलेले, बॅकग्राउंड हेल्थ शेड्युलर (`src/lib/proxyHealth/scheduler.ts`) काहीही न हटवता "डेड सदस्याला आपोआप साखळीतून वगळा" असेच वर्तन प्रदान करते:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

ते मल्टी-प्रॉक्सी साखळीत कसे बसते:

1. शेड्युलर प्रत्येक नोंदणीकृत प्रॉक्सी प्रत्येक `PROXY_HEALTH_INTERVAL_MS` (डिफॉल्ट 10 मिनिट; किमान 1 मिनिट) तपासतो.
2. सलग `PROXY_AUTO_REMOVE_AFTER` नंतर** निर्णायक** अयशस्वी (वास्तविक कनेक्शन अयशस्वी — कालबाह्य किंवा प्रोबचे स्वतःचे 5xx कधीही मोजले जात नाही, [प्रॉक्सी हेल्थ चेकिंग](#proxy-health-checking-v3816) पहा), प्रॉक्सीचे `status` `dead` वर सेट केले आहे.
3. `dead` हे pool/rotation रिझोल्यूशनद्वारे वापरलेले अलाइव्ह-स्टेटस फिल्टर वगळण्यात आलेले एक स्टेटस आहे, त्यामुळे स्कोपचे रोटेशन (राऊंड-रॉबिन/रँडम/स्टिकी/लेटन्सी — पहा [रोटेशन स्ट्रॅटेजी डिसिजन ट्री](#rotation-strategy-decision-tree) ) नवीन विनंत्यांकडे प्रॉक्सी देणे लगेच थांबवते. पूलमधील इतर कोणत्याही प्रॉक्सी प्रभावित होत नाहीत आणि संपूर्ण पूल कधीही शांतपणे थेट कनेक्शनवर परत येत नाही — [4-स्तरीय प्रॉक्सी सिस्टम](#4-level-proxy-system) फेल-क्लोज्ड गार्ड पहा.
4. शेड्युलर त्याच अंतराने `dead` प्रॉक्सी तपासत राहतो. पुढील यशस्वी प्रोब `status` परत `active` वर फ्लिप करते आणि ते — रोटेशनमध्ये पुन्हा प्रवेश करते, मॅन्युअल री-ऍड आवश्यक नसते.

हे मुद्दाम केले आहे** निवड आणि विना-विध्वंसक** : डीफॉल्टनुसार शेड्युलर केवळ अपयशांची गणना करतो आणि लॉग नोंदवतो ( `decision.ts` मध्ये धोरण C पहा), आणि `PROXY_AUTO_DISABLE` कधीही — पंक्ती हटवत नाही ज्यासाठी वेगळा, अधिक आक्रमक `PROXY_AUTO_REMOVE` ध्वज आहे. दोन्ही `true` वर सेट केले असल्यास, `PROXY_AUTO_REMOVE` जिंकतो (हटवल्या जाणाऱ्या प्रॉक्सीचा मधल्या सॉफ्ट-डिसेबलसाठी काही उपयोग नाही). संपूर्ण व्हेरिएबल सूचीसाठी [पर्यावरण कॉन्फिग](../reference/ENVIRONMENT.md) संदर्भ पहा.

---

> 📖** संबंधित कागदपत्रे:**
>
> - [वापरकर्ता मार्गदर्शक](../guides/USER_GUIDE.md) — सामान्य सेटअप आणि कॉन्फिगरेशन - [API संदर्भ](../reference/API_REFERENCE.md) — पूर्ण API दस्तऐवजीकरण - [पर्यावरण कॉन्फिग](../reference/ENVIRONMENT.md) — सर्व पर्यावरण चल
