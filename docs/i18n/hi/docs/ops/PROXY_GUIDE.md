# 🌐 OmniRoute Proxy Guide (हिन्दी)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **भौगोलिक ब्लॉकों को बायपास करें, अपनी पहचान की रक्षा करें, और शून्य कॉन्फ़िगरेशन जटिलता के साथ किसी भी प्रॉक्सी — के माध्यम से AI ट्रैफ़िक को रूट करें।**

OmniRoute में एक पूर्ण विशेषताओं वाली प्रॉक्सी प्रबंधन प्रणाली शामिल है जो आपको HTTP, HTTPS, या SOCKS5 प्रॉक्सी के माध्यम से अपस्ट्रीम AI प्रदाता ट्रैफ़िक को रूट करने देती है। चाहे आप अवरुद्ध क्षेत्र में हों, IP रोटेशन की आवश्यकता हो, या गुप्त फ़िंगरप्रिंटिंग — चाहते हों, यह मार्गदर्शिका सब कुछ कवर करती है।

---

## विषयसूची

- [प्रॉक्सी का उपयोग क्यों करें?](#why-use-proxies)
- [वास्तुकला सिंहावलोकन](#architecture-overview)
- [4-स्तरीय प्रॉक्सी सिस्टम](#4-level-proxy-system)
- [प्रॉक्सी रजिस्ट्री (CRUD)](#proxy-registry-crud)
- [1प्रॉक्सी मुक्त बाज़ार](#1proxy-free-proxy-marketplace)
- [प्रॉक्सी रोटेशन](#proxy-rotation)
- [एंटी-डिटेक्शन और चुपके](#anti-detection--stealth)
- [अपस्ट्रीम प्रॉक्सी मोड](#upstream-proxy-modes)
- [डैशबोर्ड UI](#dashboard-ui)
- [API संदर्भ](#api-reference)
- [पर्यावरण चर](#environment-variables)
- [समस्या निवारण](#troubleshooting)

---

## प्रॉक्सी का उपयोग क्यों करें?

कई AI प्रदाता भौगोलिक क्षेत्र के आधार पर पहुंच प्रतिबंधित करते हैं। डेवलपर्स में** रूस, चीन, ईरान, क्यूबा, तुर्की** , और अन्य देशों को निम्न जैसी त्रुटियों का सामना करना पड़ता है:

```
unsupported_country_region_territory
```

अवरुद्ध क्षेत्रों के बाहर भी, प्रॉक्सी इनके लिए उपयोगी हैं:

| उदाहरण             | विवरण                                                               |
| ------------------ | ------------------------------------------------------------------- |
| **भौगोलिक बाईपास** | अवरुद्ध देशों से OpenAI, Anthropic, Codex, Copilot तक पहुंचें       |
| **IP रोटेशन**      | दर सीमित करने से बचने के लिए अनुरोधों को एकाधिक IPs में वितरित करें |
| **गोपनीयता**       | अपस्ट्रीम प्रदाताओं से अपना वास्तविक IP छिपाएँ                      |
| **अनुपालन**        | विशिष्ट न्यायक्षेत्रों के माध्यम से यातायात को रूट करें             |
| **परीक्षण**        | विभिन्न क्षेत्रों से अनुरोधों का अनुकरण करें                        |

---

## वास्तुकला सिंहावलोकन

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

### ज़रूरी भाग

| अवयव                   | फ़ाइल                                        | भूमिका                                                    |
| ---------------------- | -------------------------------------------- | --------------------------------------------------------- |
| **प्रॉक्सी रजिस्ट्री** | `src/lib/db/proxies.ts`                      | प्रॉक्सी प्रविष्टियों + स्कोप असाइनमेंट के लिए CRUD       |
| **प्रॉक्सी डिस्पैचर**  | `open-sse/utils/proxyDispatcher.ts`          | कैशिंग के साथ `undici` ProxyAgent/SOCKS डिस्पैचर बनाता है |
| **प्रॉक्सी फ़ेच**      | `open-sse/utils/proxyFetch.ts`               | प्रॉक्सी डिस्पैचर इंजेक्शन के साथ `fetch()` लपेटता है     |
| **सेटिंग्स रूट**       | `src/app/api/settings/proxy/route.ts`        | लीगेसी प्रॉक्सी कॉन्फ़िगरेशन API (GET/PUT/DELETE)         |
| **प्रबंधन मार्ग**      | `src/app/api/v1/management/proxies/route.ts` | रजिस्ट्री CRUD API (GET/POST/PATCH/DELETE)                |
| **1प्रॉक्सी DB**       | `src/lib/db/oneproxy.ts`                     | मुफ़्त प्रॉक्सी बाज़ार की दृढ़ता                          |

---

## नए खातों के लिए डिफ़ॉल्ट प्रॉक्सी स्थिति

में** सेटिंग्स → प्रॉक्सी → वैश्विक कॉन्फ़िगरेशन** , उपयोग** नए कनेक्शन के लिए डिफ़ॉल्ट रूप से प्रॉक्सी सक्षम करें** नए जोड़े गए प्रदाता खातों की प्रारंभिक प्रॉक्सी स्थिति चुनने के लिए।

नई सेटिंग नए जोड़े गए प्रदाता खातों की प्रारंभिक प्रॉक्सी स्थिति को नियंत्रित करती है। यह मौजूदा खातों को नहीं बदलता है या वैश्विक प्रॉक्सी स्विच को प्रतिस्थापित नहीं करता है। इसका प्रारंभिक मूल्य पिछले व्यवहार को बरकरार रखता है। डिफ़ॉल्ट रूप से अक्षम प्रॉक्सी के साथ भविष्य के खाते बनाने के लिए इसे एक बार बंद करें।

प्राथमिकता को मौजूदा सेटिंग्स API के माध्यम से `defaultNewConnectionProxyEnabled` के रूप में संग्रहीत किया जाता है। कभी भी सहेजा न जाने पर यह `true` पर डिफॉल्ट हो जाता है। `false` को सहेजना बाद के नए खातों के लिए बिना पुनरारंभ किए प्रभावी होता है। `POST /api/providers` एक वैकल्पिक सख्त बूलियन `proxyEnabled` स्वीकार करता है; एक स्पष्ट `true` या `false` निर्माण डिफ़ॉल्ट पर प्राथमिकता दी जाती है। डुप्लिकेट खाते पर चूक या OAuth पुनः कनेक्ट उस खाते की संग्रहीत स्थिति को सुरक्षित रखता है। व्यक्तिगत खातों को बाद में भी सक्षम या अक्षम किया जा सकता है।

चयनात्मक प्रदाता स्थानांतरण नए खातों के लिए गंतव्य स्थापना के डिफ़ॉल्ट का उपयोग करते हैं और मौजूदा खातों को प्रतिस्थापित करते समय गंतव्य नीति को संरक्षित करते हैं। प्रॉक्सी टॉगल पोर्टेबल ट्रांसफर फ़ील्ड नहीं हैं। पूर्ण बैकअप पुनर्स्थापना और ऐतिहासिक JSON/SQL माइग्रेशन अपने मौजूदा पुनर्स्थापना शब्दार्थ को बनाए रखता है, जिसमें सहेजे गए खाता मान और विरासत स्कीमा डिफ़ॉल्ट शामिल हैं; एक पूर्ण सेटिंग्स पुनर्स्थापना भी इस प्राथमिकता को पुनर्स्थापित कर सकती है।

यह प्राथमिकता किसी प्रॉक्सी को निर्दिष्ट नहीं करती है या यह स्थापित नहीं करती है कि कोई स्वस्थ है या उपयोग में है। वास्तविक रूटिंग अभी भी वैश्विक प्रॉक्सी स्विच और लागू प्रॉक्सी कॉन्फ़िगरेशन पर निर्भर करती है। बिना स्थायी खाते के सिंथेटिक प्रदाता, खाता निर्माण से पहले OAuth ट्रैफ़िक, environment/system प्रॉक्सी और बाहरी बैकएंड की नेटवर्किंग इसके दायरे से बाहर हैं।

## 4-स्तरीय प्रॉक्सी सिस्टम

OmniRoute प्रॉक्सी कॉन्फ़िगरेशन का समर्थन करता है** चार स्वतंत्र दायरे** , प्राथमिकता क्रम में हल किया गया:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### संकल्प कैसे काम करता है

जब OmniRoute एक अपस्ट्रीम प्रदाता को अनुरोध भेजता है, तो यह `resolveProxyForConnectionFromRegistry()` कॉल करता है जो क्रम में प्रत्येक स्तर की जाँच करता है:

1. **खाता-स्तरीय** — क्या इस विशिष्ट कनेक्शन ID को कोई प्रॉक्सी सौंपी गई है?
2. **प्रदाता स्तरीय** — क्या इस प्रदाता को कोई प्रॉक्सी सौंपी गई है (जैसे, `openai`)?
3. **वैश्विक स्तर की** — क्या कोई वैश्विक प्रॉक्सी कॉन्फ़िगर किया गया है?
4. **कोई प्रॉक्सी नहीं** — प्रदाता से सीधा कनेक्शन।

पहला मैच जीतता है. इसका मतलब है कि आप वैश्विक प्रॉक्सी को फ़ॉलबैक के रूप में सेट कर सकते हैं लेकिन विशिष्ट प्रदाताओं या कनेक्शनों के लिए इसे ओवरराइड कर सकते हैं।

### क्या प्रॉक्सी हो जाता है

| यातायात प्रकार      | प्रॉक्सी? | टिप्पणियाँ                                           |
| ------------------- | --------- | ---------------------------------------------------- |
| चैट पूर्णता         | ✅        | सभी `/v1/chat/completions` अनुरोध                    |
| एंबेडिंग            | ✅        | `/v1/embeddings`                                     |
| छवि निर्माण         | ✅        | `/v1/images/generations`                             |
| ऑडियो (TTS/STT)     | ✅        | `/v1/audio/*`                                        |
| OAuth टोकन एक्सचेंज | ✅        | `unsupported_country_region_territory` को हल करता है |
| कनेक्शन परीक्षण     | ✅        | "टेस्ट कनेक्शन" बटन प्रॉक्सी का उपयोग करता है        |
| टोकन ताज़ा करें     | ✅        | पृष्ठभूमि OAuth नवीनीकरण                             |
| मॉडल सिंक           | ✅        | मॉडल सूचीकरण और खोज                                  |

---

## प्रॉक्सी रजिस्ट्री (CRUD)

प्रॉक्सी रजिस्ट्री एक SQLite तालिका (`proxy_registry`) है जो आपके सभी प्रॉक्सी को संग्रहीत करती है। प्रत्येक प्रॉक्सी में है:

| मैदान      | प्रकार   | विवरण                                             |
| ---------- | -------- | ------------------------------------------------- |
| `id`       | UUID     | विशिष्ट पहचानकर्ता                                |
| `name`     | डोरी     | मानव-पठनीय लेबल                                   |
| `type`     | डोरी     | प्रोटोकॉल: `http`, `https`, `socks5`              |
| `host`     | डोरी     | प्रॉक्सी होस्टनाम या IP                           |
| `port`     | पूर्णांक | पोर्ट नंबर                                        |
| `username` | डोरी     | प्रामाणिक उपयोक्तानाम (बाकी समय में एन्क्रिप्टेड) |
| `password` | डोरी     | प्रामाणिक पासवर्ड (बाकी स्थिति में एन्क्रिप्टेड)  |
| `region`   | डोरी     | भौगोलिक क्षेत्र लेबल                              |
| `notes`    | डोरी     | मुफ़्त-पाठ नोट्स                                  |
| `status`   | डोरी     | `active` या `inactive`                            |
| `source`   | डोरी     | `manual` या `oneproxy`                            |

### एक प्रॉक्सी बनाना

**डैशबोर्ड के माध्यम से:**

1. जाओ** सेटिंग्स → प्रॉक्सी**
2. क्लिक** प्रॉक्सी जोड़ें**
3. प्रकार, होस्ट, पोर्ट और वैकल्पिक प्रमाणीकरण क्रेडेंशियल भरें
4. बचाना

**API के माध्यम से:**

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

### एक प्रॉक्सी अद्यतन कर रहा है

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **टिप्पणी:** जब तक आप स्पष्ट रूप से गैर-रिक्त प्रतिस्थापन नहीं भेजते तब तक क्रेडेंशियल संरक्षित रहते हैं। `username`/`password` के लिए खाली स्ट्रिंग भेजने से संग्रहीत मान बने रहेंगे।

### एक प्रॉक्सी हटाना

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### प्रॉक्सी सूचीबद्ध करना

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### कार्यक्षेत्रों को प्रॉक्सी निर्दिष्ट करना

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

### प्रभावी प्रॉक्सी का समाधान

जांचें कि किसी दिए गए कनेक्शन के लिए कौन सी प्रॉक्सी का उपयोग किया जाएगा:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

हल की गई प्रॉक्सी को उसके स्तर (`account`, `provider`, या `global`) और स्रोत के साथ लौटाता है।

### थोक असाइनमेंट

एक ही समय में कई प्रदाताओं या कनेक्शनों को एक प्रॉक्सी असाइन करें:

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

प्रॉक्सी शामिल हैं**Backup/Restore** प्रणाली। जब आप अपना OmniRoute कॉन्फ़िगरेशन निर्यात करते हैं:

1. जाओ** डैशबोर्ड → सेटिंग्स → बैकअप**
2. क्लिक** निर्यात** — प्रॉक्सी रजिस्ट्री और असाइनमेंट शामिल हैं
3. पुनर्स्थापित करने के लिए, क्लिक करें** आयात** और बैकअप फ़ाइल अपलोड करें

प्रॉक्सी रजिस्ट्री भी सपोर्ट करती है** होस्ट + पोर्ट द्वारा upsert** — यदि आप एक प्रॉक्सी आयात करते हैं जो पहले से मौजूद है (समान होस्ट और पोर्ट), तो यह डुप्लिकेट बनाने के बजाय अपडेट हो जाता है।

### विरासत प्रवासन

यदि आपने प्रॉक्सी को पुराने संस्करण (प्री-रजिस्ट्री) में कॉन्फ़िगर किया है, तो OmniRoute स्वचालित रूप से उन्हें माइग्रेट करता है:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

अपग्रेड के बाद पहली बार स्टार्टअप पर ऐसा एक बार होता है। पुनः चलाने के लिए `migrateLegacyProxyConfigToRegistry({ force: true })` उपयोग करें।

---

## 1प्रॉक्सी फ्री प्रॉक्सी मार्केटप्लेस

> 🆕** [@oyi77](https://github.com/oyi77) द्वारा योगदान दिया गया** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (मुद्दा [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute के साथ एकीकृत होता है** [1प्रॉक्सी](https://1proxy-api.aitradepulse.com)** पहुंच प्रदान करने के लिए सामुदायिक मंच** सैकड़ों निःशुल्क, मान्य प्रॉक्सी** दुनिया भर से. यह उन उपयोगकर्ताओं के लिए बिल्कुल सही है जिनके पास अपना प्रॉक्सी इंफ्रास्ट्रक्चर नहीं है।

### यह काम किस प्रकार करता है

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **साथ-साथ करना** — OmniRoute 1proxy API से मान्य प्रॉक्सी प्राप्त करता है
2. **इकट्ठा करना** — प्रॉक्सी को `source = 'oneproxy'` के साथ उसी `proxy_registry` तालिका में सहेजा जाता है
3. **फ़िल्टर** — प्रोटोकॉल, देश, गुणवत्ता स्कोर द्वारा फ़िल्टर करें
4. **घुमाएँ** — गुणवत्ता, यादृच्छिक, या अनुक्रमिक रणनीतियों का उपयोग करके सर्वोत्तम प्रॉक्सी चुनें
5. **स्वतः ख़राब होना** — विफल प्रॉक्सी का गुणवत्ता स्कोर कम हो जाता है; सीमा से नीचे → निष्क्रिय के रूप में चिह्नित किया गया है

### प्रॉक्सी सिंक करना

**डैशबोर्ड के माध्यम से:**

1. जाओ** सेटिंग्स → 1प्रॉक्सी** टैब
2. क्लिक** "अभी सिंक करें"**
3. आँकड़े देखें: कुल प्रॉक्सी, सक्रिय संख्या, औसत गुणवत्ता, देश-दर-देश विश्लेषण

**API के माध्यम से:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### फ़िल्टरिंग प्रॉक्सी

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

### प्रॉक्सी गुणवत्ता स्कोर

प्रत्येक 1प्रॉक्सी प्रॉक्सी मेटाडेटा के साथ आती है:

| मैदान           | विवरण                                        |
| --------------- | -------------------------------------------- |
| `qualityScore`  | 1प्रॉक्सी सत्यापन से 0-100 रेटिंग            |
| `latencyMs`     | मापी गई नेटवर्क विलंबता                      |
| `anonymity`     | `transparent`, `anonymous`, या `elite`       |
| `googleAccess`  | क्या प्रॉक्सी Google सेवाओं तक पहुंच सकता है |
| `countryCode`   | दो अक्षर वाला ISO देश कोड                    |
| `lastValidated` | अंतिम सत्यापन का टाइमस्टैम्प                 |

गुणवत्ता स्कोर गतिशील रूप से समायोजित किए जाते हैं:

- **विफल अनुरोध** स्कोर को 10 अंक कम करें
- **स्कोर घटकर ≤ 10 हो गया** → प्रॉक्सी को `inactive` चिह्नित किया गया है
- निष्क्रिय प्रॉक्सी को रोटेशन से बाहर रखा गया है

### रोटेशन रणनीतियाँ

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

### परिपथ वियोजक

1प्रॉक्सी सिंक में एक अंतर्निहित सर्किट ब्रेकर है:

- बाद** लगातार 5 सिंक विफलताएँ** , आगे समन्वयन प्रयास अवरुद्ध हैं
- इसके साथ रीसेट करें: `resetOneproxyCircuitBreaker()` या सर्वर को पुनरारंभ करें
- सिंक स्थिति `GET /api/settings/oneproxy?action=status` पर उपलब्ध है

### 1प्रॉक्सी प्रॉक्सी को साफ़ करना

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## एंटी-डिटेक्शन और चुपके

OmniRoute केवल प्रॉक्सी — के माध्यम से ट्रैफ़िक को रूट नहीं करता है, यह ट्रैफ़िक को वैध बनाता है:

### TLS फ़िंगरप्रिंट स्पूफिंग

गैर-ब्राउज़र TLS हैंडशेक को चिह्नित करने वाले बॉट डिटेक्शन सिस्टम को दरकिनार करते हुए, ब्राउज़र-जैसे TLS फ़िंगरप्रिंट उत्पन्न करने के लिए `wreq-js` उपयोग करता है।

### CLI फ़िंगरप्रिंट मिलान

**CLI फ़िंगरप्रिंट टॉगल** (`Settings → Security`) मूल CLI बायनेरिज़ (Claude कोड, Codex, आदि) के सटीक हस्ताक्षर से मेल खाने के लिए HTTP हेडर और JSON बॉडी फ़ील्ड को पुन: व्यवस्थित करता है। यह सही है** के शीर्ष पर** प्रॉक्सी:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

आपको दोनों मिलते हैं**IP मास्किंग** और** प्रामाणिकता का अनुरोध करें** इसके साथ ही।

### प्रॉक्सी IP संरक्षण

डैशबोर्ड में रंग-कोडित बैज दिखाते हैं कि कौन सा प्रॉक्सी स्तर सक्रिय है:

| बिल्ला | स्तर    | अर्थ                                                |
| ------ | ------- | --------------------------------------------------- |
| 🟢     | वैश्विक | सारा ट्रैफिक इस प्रॉक्सी से होकर गुजरता है          |
| 🟡     | प्रदाता | केवल इस प्रदाता का ट्रैफ़िक प्रॉक्सी है             |
| 🔵     | संबंध   | यह विशिष्ट key/account इस प्रॉक्सी का उपयोग करता है |

बैज सत्यापन के लिए हल की गई प्रॉक्सी IP भी दिखाता है।

---

## अपस्ट्रीम प्रॉक्सी मोड

उन प्रदाताओं के लिए जो CLIProxyAPI पैटर्न का उपयोग करते हैं, OmniRoute तीन अपस्ट्रीम प्रॉक्सी मोड का समर्थन करता है:

| तरीका         | विवरण                                                           |
| ------------- | --------------------------------------------------------------- |
| `native`      | OmniRoute सीधे प्रॉक्सी रूटिंग को संभालता है (डिफ़ॉल्ट)         |
| `cliproxyapi` | बाहरी CLIProxyAPI उदाहरण के लिए प्रतिनिधि                       |
| `fallback`    | पहले मूल निवासी की कोशिश करता है, CLIProxyAPI पर वापस आ जाता है |

प्रति-प्रदाता कॉन्फ़िगर करें:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## डैशबोर्ड UI

### सेटिंग्स → प्रॉक्सी टैब

- **वैश्विक प्रॉक्सी** कॉन्फ़िगरेशन (सभी ट्रैफ़िक के लिए एक बार सेट करें)
- **प्रति-प्रदाता प्रॉक्सी** ओवरराइड
- **प्रति-कनेक्शन प्रॉक्सी** कार्य
- **कनेक्शन परीक्षण** कॉन्फ़िगर प्रॉक्सी के माध्यम से
- **रंग-कोडित बैज** सक्रिय प्रॉक्सी स्तर दिखा रहा है

### सेटिंग्स → 1प्रॉक्सी टैब

- **अभी सिंक करें** निःशुल्क प्रॉक्सी लाने के लिए बटन
- **आँकड़े कार्ड** : कुल, सक्रिय, औसत गुणवत्ता, अंतिम सिंक
- **फिल्टर** : प्रोटोकॉल, देश कोड, न्यूनतम गुणवत्ता
- **प्रॉक्सी टेबल** होस्ट, प्रोटोकॉल, देश, गुणवत्ता स्कोर, विलंबता, गुमनामी, Google पहुंच के साथ
- **सिंक स्थिति** success/failure ट्रैकिंग और लगातार विफलता गणना वाला पैनल
- **सभी साफ करें** सभी 1प्रॉक्सी प्रविष्टियों को हटाने के लिए

---

## API संदर्भ

### प्रॉक्सी सेटिंग्स API

| तरीका    | endpoint                                       | विवरण                                    |
| -------- | ---------------------------------------------- | ---------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | पूर्ण प्रॉक्सी कॉन्फ़िगरेशन प्राप्त करें |
| `GET`    | `/api/settings/proxy?level=global`             | वैश्विक प्रॉक्सी प्राप्त करें            |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | प्रदाता प्रॉक्सी प्राप्त करें            |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | प्रभावी प्रॉक्सी का समाधान करें          |
| `PUT`    | `/api/settings/proxy`                          | प्रॉक्सी कॉन्फ़िगरेशन अपडेट करें         |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | स्तर पर प्रॉक्सी हटाएँ                   |

### प्रॉक्सी रजिस्ट्री API

| तरीका    | endpoint                                          | विवरण                           |
| -------- | ------------------------------------------------- | ------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | सभी प्रॉक्सी की सूची बनाएं      |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID द्वारा प्रॉक्सी प्राप्त करें |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | प्रॉक्सी असाइनमेंट प्राप्त करें |
| `POST`   | `/api/v1/management/proxies`                      | प्रॉक्सी बनाएं                  |
| `PATCH`  | `/api/v1/management/proxies`                      | प्रॉक्सी अपडेट करें             |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | प्रॉक्सी हटाएँ                  |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | बलपूर्वक हटाना                  |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | थोक में असाइन करें              |
| `GET`    | `/api/v1/management/proxies/assignments`          | असाइनमेंट की सूची बनाएं         |
| `GET`    | `/api/v1/management/proxies/health`               | प्रॉक्सी स्वास्थ्य आँकड़े       |

### सुरंगें API

अपने OmniRoute उदाहरण को प्रॉक्सी के माध्यम से आउटबाउंड रूट करने के बजाय सार्वजनिक इंटरनेट (Cloudflare/ngrok/Tailscale) पर उजागर करने के लिए, [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) देखें। सुरंग REST API `/api/tunnels/{cloudflared,ngrok,tailscale}/*` के अंतर्गत रहती है और ऊपर प्रलेखित आउटबाउंड प्रॉक्सी श्रृंखला के लिए ऑर्थोगोनल है।

### 1प्रॉक्सी API

| तरीका    | endpoint                               | विवरण                             |
| -------- | -------------------------------------- | --------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | सूची 1प्रॉक्सी प्रॉक्सी           |
| `GET`    | `/api/settings/oneproxy?action=stats`  | आँकड़े + सिंक स्थिति प्राप्त करें |
| `GET`    | `/api/settings/oneproxy?action=status` | केवल समन्वयन स्थिति प्राप्त करें  |
| `POST`   | `/api/settings/oneproxy`               | ट्रिगर सिंक                       |
| `POST`   | `/api/settings/oneproxy/rotate`        | अगले प्रॉक्सी पर घुमाएँ           |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | एक हटाओ                           |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | सभी साफ करें                      |

### अपस्ट्रीम प्रॉक्सी API

| तरीका    | endpoint                          | विवरण                                        |
| -------- | --------------------------------- | -------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | अपस्ट्रीम प्रॉक्सी कॉन्फ़िगरेशन प्राप्त करें |
| `PUT`    | `/api/upstream-proxy/:providerId` | अपस्ट्रीम प्रॉक्सी मोड सेट करें              |
| `DELETE` | `/api/upstream-proxy/:providerId` | अपस्ट्रीम प्रॉक्सी कॉन्फ़िगरेशन हटाएँ        |

---

## पर्यावरण चर

| चर                    | गलती करना | विवरण                                                                    |
| --------------------- | --------- | ------------------------------------------------------------------------ |
| `ENABLE_SOCKS5_PROXY` | `true`    | SOCKS5 प्रॉक्सी समर्थन सक्षम करें ( `.env.example` में डिफ़ॉल्ट `true` ) |

---

## समस्या निवारण

### "SOCKS5 प्रॉक्सी अक्षम है"

अपनी `.env` फ़ाइल में `ENABLE_SOCKS5_PROXY=true` सेट करें और पुनरारंभ करें।

### प्रॉक्सी के माध्यम से "सॉकेट हैंग अप" त्रुटियाँ

सस्ते प्रॉक्सी के साथ यह सामान्य है जो निष्क्रिय कनेक्शन को हटा देता है। OmniRoute पहले से ही इसे संभालता है:

- प्रॉक्सी कनेक्शन पर जीवित रखें को अक्षम करना (`keepAliveTimeout: 1`)
- पाइपलाइनिंग अक्षम करना (`pipelining: 0`)
- बार-बार हाथ मिलाने से बचने के लिए कैशिंग डिस्पैचर

यदि यह बनी रहती है, तो एक अलग प्रॉक्सी आज़माएँ या 1प्रॉक्सी रोटेशन सुविधा का उपयोग करें।

### OAuth के दौरान "असमर्थित_देश_क्षेत्र_क्षेत्र"।

सुनिश्चित करें कि प्रॉक्सी कॉन्फ़िगर है** पहले** OAuth प्रवाह शुरू करना। OmniRoute कॉन्फ़िगर प्रॉक्सी के माध्यम से OAuth टोकन एक्सचेंज को रूट करता है। पहले वैश्विक या प्रदाता-स्तरीय प्रॉक्सी सेट करें, फिर कनेक्ट करें।

### प्रॉक्सी का उपयोग नहीं किया जा रहा है

समाधान आदेश की जाँच करें:

1. `GET /api/settings/proxy?resolve=your-connection-id` से सत्यापित करें
2. जांचें कि क्या प्रॉक्सी `status` `active` है ( `inactive` नहीं)
3. सुनिश्चित करें कि प्रॉक्सी असाइनमेंट का दायरा आपके कनेक्शन से मेल खाता हो

### 1प्रॉक्सी सिंक विफल हो रहा है

सिंक स्थिति जांचें:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

यदि `consecutiveFailures >= 5`, तो सर्किट ब्रेकर ट्रिप हो गया है। रीसेट करने के लिए सर्वर को पुनरारंभ करें, या मैन्युअल रीसेट की प्रतीक्षा करें।

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

## प्रॉक्सी स्वास्थ्य जाँच (v3.8.16 +)

OmniRoute'एस** प्रॉक्सी फास्ट-फेल** तंत्र (`src/lib/proxyHealth.ts`) एक त्वरित TCP कनेक्शन जांच के माध्यम से < 2s में मृत प्रॉक्सी का पता लगाता है, फिर** परिणाम को कैश करता है** प्रति-अनुरोध ओवरहेड से बचने के लिए।

### यह काम किस प्रकार करता है

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

इसके बिना, एक मृत प्रॉक्सी विफल होने से पहले पूर्ण `PROXY_TIMEOUT_MS` (डिफ़ॉल्ट 30s) के लिए प्रत्येक अनुरोध को अवरुद्ध कर देगी।

### ट्यून करने योग्य पर्यावरण चर

| चर                           | गलती करना | उद्देश्य                                     |
| ---------------------------- | --------- | -------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`    | स्वास्थ्य जांच के अनुसार TCP कनेक्शन टाइमआउट |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`   | स्वास्थ्य परिणाम कितने समय तक कैश्ड रहता है  |

**अनुशंसित मान:**

| परिदृश्य                      | तेजी से विफल समयबाह्य | कैश TTL | तर्क                                                                       |
| ----------------------------- | --------------------- | ------- | -------------------------------------------------------------------------- |
| उच्च-थ्रूपुट API प्रवेश द्वार | 1500ms                | 60000ms | आक्रामक विफलता-तेज़, जांच को कम करने के लिए लंबा कैश                       |
| भू-वितरित नोड्स               | 3000ms                | 15000ms | धीमे नेटवर्क को अधिक समय की आवश्यकता होती है; तेज़ फ़ेलओवर के लिए छोटा कैश |
| देव/परीक्षण                   | 1000ms                | 10000ms | स्थानीय प्रॉक्सी पर त्वरित पुनरावृत्ति                                     |
| गुप्त/विरोधी पहचान            | 2500ms                | 45000ms | तेजी से जांच करने से बचें जो दर सीमा को ट्रिगर कर सकता है                  |

### प्रॉक्सी स्वास्थ्य का निरीक्षण

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

जब कैश प्रविष्टि `HEALTH_CACHE_TTL_MS` से अधिक हो जाती है तो `stale` ध्वज `true` होता है और अगला अनुरोध एक नई जांच को ट्रिगर करेगा।

### प्रति-प्रॉक्सी प्रकार डिफ़ॉल्ट

स्वास्थ्य जांच URL योजना के आधार पर समझदार डिफ़ॉल्ट का उपयोग करती है:

| योजना                      | डिफ़ॉल्ट पोर्ट |
| -------------------------- | -------------- |
| `http://`                  | 8080           |
| `https://`                 | 443            |
| `socks5://` / `socks5h://` | 1080           |

URL (`http://host:9999`) में कस्टम पोर्ट हमेशा स्कीम डिफ़ॉल्ट पर प्राथमिकता लेते हैं।

---

## प्रॉक्सी एनालिटिक्स और अवलोकनशीलता

OmniRoute ऑपरेटरों को रूटिंग पैटर्न, विलंबता स्पाइक्स और आवर्ती विफलताओं का निदान करने में मदद करने के लिए प्रति-प्रॉक्सी उपयोग को ट्रैक करता है।

### क्या ट्रैक किया गया है

कॉन्फ़िगर प्रॉक्सी के माध्यम से प्रत्येक अनुरोध के लिए, OmniRoute रिकॉर्ड:

| मीट्रिक      | विवरण                                              |
| ------------ | -------------------------------------------------- |
| `proxy_url`  | पूर्ण प्रॉक्सी URL (प्रमाणीकरण क्रेडेंशियल छिपाकर) |
| `provider`   | अपस्ट्रीम प्रदाता ID (ओपनाई, एंथ्रोपिक, आदि)       |
| `latency_ms` | प्रॉक्सी हैंडशेक सहित कुल राउंड-ट्रिप का समय       |
| `connect_ms` | TCP केवल कनेक्ट समय                                |
| `status`     | अपस्ट्रीम सेHTTP स्थिति कोड                        |
| `error`      | यदि अनुरोध विफल हुआ तो त्रुटि वर्ग                 |
| `timestamp`  | ISO 8601 UTC                                       |

### डेटा तक पहुँचना

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

वास्तविक समापन बिंदु `/api/usage/proxy-logs` है (देखें `src/app/api/usage/proxy-logs/route.ts`)। यह समापन बिंदु समर्थन करता है:

- `GET /api/usage/proxy-logs` — प्रॉक्सी लॉग पुनर्प्राप्त करें
- `DELETE /api/usage/proxy-logs` — सभी प्रॉक्सी लॉग साफ़ करें

यदि आवश्यक हो तो समग्र आँकड़े सीधे `proxy_logs` तालिका से SQL के माध्यम से पूछे जा सकते हैं। डैशबोर्ड UI समग्र दृश्य प्रस्तुत कर सकता है।

### सामान्य पैटर्न

**फ़्लैपिंग प्रॉक्सी का पता लगाएं** ( success/failure के बीच वैकल्पिक):

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

**धीमी प्रॉक्सी खोजें** (p95 विलंबता > 2s):

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

## रोटेशन रणनीति निर्णय वृक्ष

जब एकाधिक प्रॉक्सी को एक दायरे में सौंपा जाता है, तो OmniRoute एक का उपयोग करता है** रोटेशन रणनीति** यह चुनना कि प्रत्येक अनुरोध के लिए किसका उपयोग करना है। रणनीति को स्कोप स्तर (वैश्विक, प्रति-प्रदाता, प्रति-खाता, प्रति-कॉम्बो) पर कॉन्फ़िगर किया गया है।

### उपलब्ध रणनीतियाँ

| रणनीति               | कब उपयोग करें                                 | अदला - बदली                                                            |
| -------------------- | --------------------------------------------- | ---------------------------------------------------------------------- |
| `quality` (डिफ़ॉल्ट) | मिश्रित गुणवत्ता वाले प्रॉक्सी के साथ उत्पादन | उच्च-रेटेड प्रॉक्सी का समर्थन करता है; कम रेटिंग वाले भूखे रह सकते हैं |
| `random`             | लोड वितरण, गोपनीयता                           | समान वितरण; गुणवत्ता संकेतों पर ध्यान नहीं देता                        |
| `sequential`         | डिबगिंग, नियतात्मक परीक्षण                    | क्रम में प्रॉक्सी के माध्यम से चक्र; इसके बारे में तर्क करना आसान है   |

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

## आपकी अपनी प्रॉक्सी के लिए स्वचालित विफलता बहिष्करण

1प्रॉक्सी मार्केटप्लेस पूल पहले से ही विफल प्रॉक्सी को अपने आप ही ऑटो-डिग्रेड कर देता है ( [प्रॉक्सी क्वालिटी स्कोर](#proxy-quality-scores) देखें)। प्रॉक्सी के लिए** आप** रजिस्ट्री में जोड़ा गया, पृष्ठभूमि स्वास्थ्य अनुसूचक (`src/lib/proxyHealth/scheduler.ts`) कुछ भी हटाए बिना, समान "श्रृंखला से एक मृत सदस्य को स्वचालित रूप से बाहर निकालें" व्यवहार प्रदान करता है:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

यह मल्टी-प्रॉक्सी श्रृंखला में कैसे फिट बैठता है:

1. शेड्यूलर प्रत्येक पंजीकृत प्रॉक्सी की हर `PROXY_HEALTH_INTERVAL_MS` (डिफ़ॉल्ट 10 मिनट; न्यूनतम 1 मिनट) जांच करता है।
2. `PROXY_AUTO_REMOVE_AFTER` के बाद लगातार** निर्णयात्मक** विफलताएं (एक वास्तविक कनेक्शन विफलता — एक टाइमआउट या जांच लक्ष्य का अपना 5xx कभी भी गिना नहीं जाता है, [प्रॉक्सी स्वास्थ्य जांच](#proxy-health-checking-v3816) देखें), प्रॉक्सी का `status` `dead` पर सेट है।
3. `dead` उन स्थितियों में से एक है जिसे pool/rotation रिज़ॉल्यूशन द्वारा उपयोग किए जाने वाले जीवित-स्थिति फ़िल्टर में शामिल नहीं किया गया है, इसलिए एक स्कोप का रोटेशन (राउंड-रॉबिन / यादृच्छिक / चिपचिपा / विलंबता — देखें [रोटेशन रणनीति निर्णय वृक्ष](#rotation-strategy-decision-tree) ) तुरंत उस प्रॉक्सी को नए अनुरोधों को सौंपना बंद कर देता है। पूल में कोई भी अन्य प्रॉक्सी प्रभावित नहीं होती है, और पूरा पूल कभी भी चुपचाप सीधे कनेक्शन पर वापस नहीं आता है — [4-लेवल प्रॉक्सी सिस्टम](#4-level-proxy-system) फेल-क्लोज्ड गार्ड देखें।
4. शेड्यूलर समान अंतराल पर `dead` प्रॉक्सी की जांच करता रहता है। अगली सफल जांच `status` वापस `active` पर फ़्लिप कर देती है और यह रोटेशन — में फिर से प्रवेश कर जाती है, किसी मैन्युअल पुनः जोड़ने की आवश्यकता नहीं होती है।

ये जानबूझकर किया गया है** ऑप्ट-इन और गैर-विनाशकारी** : डिफ़ॉल्ट रूप से शेड्यूलर केवल विफलताओं को गिनता है और लॉग करता है ( `decision.ts` में नीति C देखें), और `PROXY_AUTO_DISABLE` कभी भी — पंक्ति को नहीं हटाता है, यही अलग, अधिक आक्रामक `PROXY_AUTO_REMOVE` ध्वज है। यदि दोनों को `true` पर सेट किया जाता है, `PROXY_AUTO_REMOVE` जीतता है (एक प्रॉक्सी जिसे हटाया जाना है, उसके बीच में सॉफ्ट-डिसेबल का कोई उपयोग नहीं है)। संपूर्ण चर सूची के लिए [पर्यावरण कॉन्फ़िगरेशन](../reference/ENVIRONMENT.md) संदर्भ देखें।

---

> 📖** संबंधित दस्तावेज़:**
>
> - [उपयोगकर्ता गाइड](../guides/USER_GUIDE.md) — सामान्य सेटअप और कॉन्फ़िगरेशन - [API संदर्भ](../reference/API_REFERENCE.md) — पूर्ण API दस्तावेज़ीकरण - [पर्यावरण कॉन्फ़िगरेशन](../reference/ENVIRONMENT.md) — सभी पर्यावरण चर
