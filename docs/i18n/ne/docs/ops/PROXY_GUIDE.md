# 🌐 OmniRoute Proxy Guide (नेपाली)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **भौगोलिक ब्लकहरू बाइपास गर्नुहोस्, तपाईंको पहिचान सुरक्षित गर्नुहोस्, र शून्य कन्फिगरेसन जटिलताको साथ कुनै पनि प्रोक्सी — मार्फत AI ट्राफिक मार्ग गर्नुहोस्।**

OmniRoute एक पूर्ण-विशेष प्रोक्सी प्रबन्धन प्रणाली समावेश छ जसले तपाईंलाई HTTP, HTTPS, वा SOCKS5 प्रोक्सीहरू मार्फत अपस्ट्रीम AI प्रदायक ट्राफिकलाई रूट गर्न दिन्छ। चाहे तपाईं अवरुद्ध क्षेत्रमा हुनुहुन्छ, IP रोटेशन चाहिन्छ, वा स्टेल्थ फिंगरप्रिन्टिङ — चाहनुहुन्छ यो गाइडले सबै कुरा समेट्छ।

---

## सामग्रीको तालिका

- [प्रोक्सीहरू किन प्रयोग गर्ने?](#why-use-proxies)
- [वास्तुकला अवलोकन](#architecture-overview)
- [4-स्तर प्रोक्सी प्रणाली](#4-level-proxy-system)
- [प्रोक्सी रजिस्ट्री (CRUD)](#proxy-registry-crud)
- [१ प्रोक्सी फ्री मार्केटप्लेस](#1proxy-free-proxy-marketplace)
- [प्रोक्सी रोटेशन](#proxy-rotation)
- [एन्टी-डिटेक्शन र स्टिल्थ](#anti-detection--stealth)
- [अपस्ट्रीम प्रोक्सी मोडहरू](#upstream-proxy-modes)
- [ड्यासबोर्ड UI](#dashboard-ui)
- [API सन्दर्भ](#api-reference)
- [वातावरण चर](#environment-variables)
- [समस्या निवारण](#troubleshooting)

---

## प्रोक्सीहरू किन प्रयोग गर्ने?

धेरै AI प्रदायकहरूले भौगोलिक क्षेत्रद्वारा पहुँच प्रतिबन्धित गर्छन्। मा विकासकर्ताहरू** रुस, चीन, इरान, क्युबा, टर्की** , र अन्य देशहरूले त्रुटिहरू सामना गर्छन् जस्तै:

```
unsupported_country_region_territory
```

बाहिरका अवरुद्ध क्षेत्रहरूमा पनि, प्रोक्सीहरू यसका लागि उपयोगी छन्:

| केस प्रयोग गर्नुहोस् | विवरण                                                               |
| -------------------- | ------------------------------------------------------------------- |
| **भौगोलिक बाइपास**   | अवरुद्ध देशहरूबाट OpenAI, Anthropic, Codex, Copilot पहुँच गर्नुहोस् |
| **IP रोटेशन**        | दर सीमित हुनबाट जोगिन धेरै IPs मा अनुरोधहरू वितरण गर्नुहोस्         |
| **गोपनीयता**         | अपस्ट्रीम प्रदायकहरूबाट तपाईंको वास्तविक IP लुकाउनुहोस्             |
| **अनुपालन**          | विशिष्ट क्षेत्राधिकार मार्फत ट्राफिक मार्ग                          |
| **परीक्षण**          | विभिन्न क्षेत्रहरूबाट अनुरोधहरू अनुकरण गर्नुहोस्                    |

---

## वास्तुकला अवलोकन

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

### प्रमुख अवयवहरू

| कम्पोनेन्ट              | फाइल                                         | भूमिका                                                              |
| ----------------------- | -------------------------------------------- | ------------------------------------------------------------------- |
| **प्रोक्सी रजिस्ट्री**  | `src/lib/db/proxies.ts`                      | प्रोक्सी प्रविष्टिहरूको लागिCRUD + स्कोप असाइनमेन्टहरू              |
| **प्रोक्सी डिस्प्याचर** | `open-sse/utils/proxyDispatcher.ts`          | क्यासिङको साथ `undici` ProxyAgent/SOCKS डिस्प्याचरहरू सिर्जना गर्दछ |
| **प्रोक्सी फेच**        | `open-sse/utils/proxyFetch.ts`               | `fetch()` लाई प्रोक्सी डिस्प्याचर इन्जेक्सनले लपेट्छ                |
| **सेटिङ मार्ग**         | `src/app/api/settings/proxy/route.ts`        | लिगेसी प्रोक्सी कन्फिगरेसन API (GET/PUT/DELETE)                     |
| **व्यवस्थापन मार्ग**    | `src/app/api/v1/management/proxies/route.ts` | रजिस्ट्री CRUD API (GET/POST/PATCH/DELETE)                          |
| **1 proxy DB**          | `src/lib/db/oneproxy.ts`                     | नि: शुल्क प्रोक्सी मार्केटप्लेस दृढता                               |

---

## नयाँ खाताहरूको लागि पूर्वनिर्धारित प्रोक्सी अवस्था

मा** सेटिङहरू → प्रोक्सी → ग्लोबल कन्फिगरेसन** , प्रयोग गर्नुहोस्** नयाँ जडानहरूको लागि पूर्वनिर्धारित रूपमा प्रोक्सी सक्षम गर्नुहोस्** नयाँ थपिएका प्रदायक खाताहरूको प्रारम्भिक प्रोक्सी अवस्था छनोट गर्न।

नयाँ सेटिङले नयाँ थपिएका प्रदायक खाताहरूको प्रारम्भिक प्रोक्सी अवस्था नियन्त्रण गर्छ। यसले अवस्थित खाताहरू परिवर्तन गर्दैन वा ग्लोबल प्रोक्सी स्विचलाई प्रतिस्थापन गर्दैन। यसको प्रारम्भिक मूल्यले अघिल्लो व्यवहारलाई सुरक्षित गर्दछ। पूर्वनिर्धारित रूपमा असक्षम पारिएको प्रोक्सीको साथ भविष्यका खाताहरू सिर्जना गर्न यसलाई एक पटक बन्द गर्नुहोस्।

प्राथमिकता `defaultNewConnectionProxyEnabled` को रूपमा अवस्थित सेटिङहरू API मार्फत भण्डारण गरिएको छ। यो `true` मा पूर्वनिर्धारित हुन्छ जब कहिल्यै बचत हुँदैन। `false` बचत गर्दा पुन: सुरु नगरी पछिल्ला नयाँ खाताहरूको लागि प्रभाव पार्छ। `POST /api/providers` वैकल्पिक सख्त बुलियन `proxyEnabled` स्वीकार गर्दछ; एक स्पष्ट `true` वा `false` सिर्जना पूर्वनिर्धारितमा प्राथमिकता लिन्छ। डुप्लिकेट खाता वा OAuth पुन: जडानमा छुटकाराले त्यो खाताको भण्डारण अवस्था सुरक्षित गर्दछ। व्यक्तिगत खाताहरू अझै पनि सक्षम वा पछि अक्षम गर्न सकिन्छ।

छनौट प्रदायक स्थानान्तरणहरूले नयाँ खाताहरूको लागि गन्तव्य स्थापनाको पूर्वनिर्धारित प्रयोग गर्दछ र अवस्थित खाताहरू प्रतिस्थापन गर्दा गन्तव्य नीति सुरक्षित गर्दछ। प्रोक्सी टगलहरू पोर्टेबल स्थानान्तरण क्षेत्रहरू होइनन्। पूर्ण जगेडा पुनर्स्थापना र ऐतिहासिक JSON/SQL माइग्रेसनले सुरक्षित खाता मानहरू र लिगेसी स्किमा पूर्वनिर्धारितहरू सहित तिनीहरूको अवस्थित पुनर्स्थापना अर्थशास्त्रलाई कायम राख्छ; पूर्ण सेटिङहरू पुनर्स्थापनाले पनि यो प्राथमिकतालाई पुनर्स्थापित गर्न सक्छ।

यो प्राथमिकताले प्रोक्सी नियुक्त गर्दैन वा स्थापित गर्दैन कि एक स्वस्थ वा प्रयोगमा छ। वास्तविक राउटिङ अझै पनि ग्लोबल प्रोक्सी स्विच र लागू प्रोक्सी कन्फिगरेसनमा निर्भर गर्दछ। स्थिर खाता बिना सिंथेटिक प्रदायकहरू, खाता सिर्जना गर्नु अघि OAuth ट्राफिक, environment/system प्रोक्सीहरू, र बाह्य ब्याकएन्ड्स नेटवर्किङ यसको दायरा बाहिर छन्।

## 4-स्तर प्रोक्सी प्रणाली

OmniRoute मा प्रोक्सी कन्फिगरेसन समर्थन गर्दछ** चार स्वतन्त्र दायरा** , प्राथमिकता क्रम मा समाधान:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### कसरी संकल्प काम गर्दछ

जब OmniRoute ले अपस्ट्रीम प्रदायकलाई अनुरोध पठाउँछ, यसले `resolveProxyForConnectionFromRegistry()` कल गर्छ जसले प्रत्येक स्तरलाई क्रमबद्ध रूपमा जाँच गर्दछ:

1. **खाता स्तर** — यो विशिष्ट जडान ID मा कुनै प्रोक्सी तोकिएको छ?
2. **प्रदायक-स्तर** — के त्यहाँ यो प्रदायक (जस्तै, `openai`) लाई कुनै प्रोक्सी तोकिएको छ?
3. **विश्वव्यापी स्तर** — त्यहाँ विश्वव्यापी प्रोक्सी कन्फिगर गरिएको छ?
4. **कुनै प्रोक्सी छैन** — प्रदायकसँग प्रत्यक्ष जडान।

पहिलो खेल जित्छ। यसको मतलब तपाईले विश्वव्यापी प्रोक्सीलाई फलब्याकको रूपमा सेट गर्न सक्नुहुन्छ तर विशिष्ट प्रदायक वा जडानहरूको लागि यसलाई ओभरराइड गर्न सक्नुहुन्छ।

### के प्रोक्सी हुन्छ

| ट्राफिक प्रकार    | प्रोक्सी? | नोटहरू                                          |
| ----------------- | --------- | ----------------------------------------------- |
| च्याट पूरा        | ✅        | सबै `/v1/chat/completions` अनुरोधहरू            |
| इम्बेडिङहरू       | ✅        | `/v1/embeddings`                                |
| छवि उत्पादन       | ✅        | `/v1/images/generations`                        |
| अडियो (TTS/STT)   | ✅        | `/v1/audio/*`                                   |
| OAuth टोकन विनिमय | ✅        | `unsupported_country_region_territory` हल गर्दछ |
| जडान परीक्षणहरू   | ✅        | "परीक्षण जडान" बटन प्रोक्सी प्रयोग गर्दछ        |
| टोकन रिफ्रेस      | ✅        | पृष्ठभूमि OAuth नवीकरण                          |
| मोडेल सिंक        | ✅        | मोडेल सूची र खोज                                |

---

## प्रोक्सी रजिस्ट्री (CRUD)

प्रोक्सी रजिस्ट्री एक SQLite तालिका (`proxy_registry`) हो जसले तपाइँका सबै प्रोक्सीहरू भण्डार गर्दछ। प्रत्येक प्रोक्सी छ:

| क्षेत्र    | टाइप गर्नुहोस् | विवरण                                                  |
| ---------- | -------------- | ------------------------------------------------------ |
| `id`       | UUID           | अद्वितीय पहिचानकर्ता                                   |
| `name`     | स्ट्रिङ        | मानव-पठनीय लेबल                                        |
| `type`     | स्ट्रिङ        | प्रोटोकल: `http`, `https`, `socks5`                    |
| `host`     | स्ट्रिङ        | प्रोक्सी होस्टनाम वा IP                                |
| `port`     | पूर्णांक       | पोर्ट नम्बर                                            |
| `username` | स्ट्रिङ        | प्रमाणिकरण प्रयोगकर्ता नाम (बाँकीमा इन्क्रिप्ट गरिएको) |
| `password` | स्ट्रिङ        | प्रमाणीकरण पासवर्ड (बाकीमा इन्क्रिप्ट गरिएको)          |
| `region`   | स्ट्रिङ        | भौगोलिक क्षेत्र लेबल                                   |
| `notes`    | स्ट्रिङ        | फ्री-टेक्स्ट नोटहरू                                    |
| `status`   | स्ट्रिङ        | `active` वा `inactive`                                 |
| `source`   | स्ट्रिङ        | `manual` वा `oneproxy`                                 |

### प्रोक्सी सिर्जना गर्दै

**ड्यासबोर्ड मार्फत:**

1. मा जानुहोस्** सेटिङहरू → प्रोक्सी**
2. क्लिक गर्नुहोस्** प्रोक्सी थप्नुहोस्**
3. प्रकार, होस्ट, पोर्ट, र वैकल्पिक प्रमाणीकरण प्रमाणहरू भर्नुहोस्
4. बचत गर्नुहोस्

**API मार्फत:**

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

### प्रोक्सी अद्यावधिक गर्दै

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **नोट:** तपाईंले स्पष्ट रूपमा गैर-खाली प्रतिस्थापनहरू पठाउनुभएन भने प्रमाणपत्रहरू सुरक्षित हुन्छन्। `username`/`password` को लागि खाली स्ट्रिङहरू पठाउँदा भण्डार गरिएको मानहरू राखिनेछ।

### प्रोक्सी मेटाउँदै

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### सूचीकरण प्रोक्सीहरू

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### स्कोपहरूमा प्रोक्सीहरू असाइन गर्दै

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

### प्रभावकारी प्रोक्सी समाधान गर्दै

दिइएको जडानको लागि कुन प्रोक्सी प्रयोग गरिनेछ भनेर जाँच गर्नुहोस्:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

यसको स्तर (`account`, `provider`, वा `global`) र स्रोतको साथ समाधान गरिएको प्रोक्सी फर्काउँछ।

### बल्क असाइनमेन्ट

एकै पटकमा धेरै प्रदायक वा जडानहरूलाई एउटा प्रोक्सी तोक्नुहोस्:

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

प्रोक्सीहरू समावेश छन्**Backup/Restore** प्रणाली। जब तपाइँ तपाइँको OmniRoute कन्फिगरेसन निर्यात गर्नुहुन्छ:

1. मा जानुहोस्** ड्यासबोर्ड → सेटिङहरू → ब्याकअप**
2. क्लिक गर्नुहोस्** निर्यात गर्नुहोस्** — प्रोक्सी रजिस्ट्री र असाइनमेन्टहरू समावेश छन्
3. पुनर्स्थापना गर्न, क्लिक गर्नुहोस्** आयात गर्नुहोस्** र ब्याकअप फाइल अपलोड गर्नुहोस्

प्रोक्सी रजिस्ट्री पनि समर्थन गर्दछ** होस्ट + पोर्ट द्वारा upsert** — यदि तपाइँ पहिले नै अवस्थित प्रोक्सी आयात गर्नुहुन्छ (एउटै होस्ट र पोर्ट), यो नक्कल सिर्जना गर्नुको सट्टा अद्यावधिक हुन्छ।

### लिगेसी माइग्रेसन

यदि तपाईंले पुरानो संस्करण (पूर्व-रेजिस्ट्री) मा प्रोक्सीहरू कन्फिगर गर्नुभयो भने, OmniRoute तिनीहरूलाई स्वतः माइग्रेट गर्छ:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

यो अपग्रेड पछि पहिलो स्टार्टअपमा एक पटक हुन्छ। पुन: चलाउन `migrateLegacyProxyConfigToRegistry({ force: true })` प्रयोग गर्नुहोस्।

---

## १ प्रोक्सी फ्री प्रोक्सी मार्केटप्लेस

> 🆕** [@oyi77](https://github.com/oyi77) द्वारा योगदान गरिएको तस्वीर** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (अंक [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute सँग एकीकृत हुन्छ** [१ प्रोक्सी](https://1proxy-api.aitradepulse.com)** पहुँच प्रदान गर्न सामुदायिक प्लेटफर्म** सयौं नि:शुल्क, मान्य प्रोक्सीहरू** संसारभरबाट। यो प्रयोगकर्ताहरूको लागि उपयुक्त छ जसको आफ्नै प्रोक्सी पूर्वाधार छैन।

### यो कसरी काम गर्दछ

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **सिंक** — OmniRoute 1proxy API बाट मान्य प्रोक्सीहरू ल्याउँछ
2. **स्टोर** — प्रोक्सीहरू `source = 'oneproxy'` सँग एउटै `proxy_registry` तालिकामा बचत गरिएका छन्
3. **फिल्टर गर्नुहोस्** प्रोटोकल, देश, गुणस्तर स्कोर द्वारा — फिल्टर
4. **घुमाउनुहोस्** — गुणस्तर, अनियमित, वा क्रमिक रणनीतिहरू प्रयोग गरेर उत्तम प्रोक्सी छान्नुहोस्
5. **स्वतः घटाउनुहोस्** — असफल प्रोक्सीहरूले तिनीहरूको गुणस्तर स्कोर घटाउँछन्; तलको थ्रेसहोल्ड → निष्क्रिय चिन्ह लगाइयो

### प्रोक्सीहरू सिङ्क गर्दै

**ड्यासबोर्ड मार्फत:**

1. मा जानुहोस्** सेटिङहरू → 1proxy** ट्याब
2. क्लिक गर्नुहोस्** "अब सिङ्क गर्नुहोस्"**
3. तथ्याङ्कहरू हेर्नुहोस्: कुल प्रोक्सीहरू, सक्रिय गणना, औसत गुणस्तर, देश अनुसार

**API मार्फत:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### प्रोक्सीहरू फिल्टर गर्दै

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

### प्रोक्सी गुणस्तर स्कोर

प्रत्येक 1 प्रोक्सी प्रोक्सी मेटाडेटा संग आउँछ:

| क्षेत्र         | विवरण                                     |
| --------------- | ----------------------------------------- |
| `qualityScore`  | १ प्रोक्सी प्रमाणीकरणबाट ०-१०० मूल्याङ्कन |
| `latencyMs`     | नेटवर्क विलम्बता मापन                     |
| `anonymity`     | `transparent`, `anonymous`, वा `elite`    |
| `googleAccess`  | प्रोक्सीले Google सेवाहरू पहुँच गर्न सक्छ |
| `countryCode`   | दुई-अक्षर ISO देश कोड                     |
| `lastValidated` | पछिल्लो प्रमाणीकरणको टाइमस्ट्याम्प        |

गुणस्तर स्कोरहरू गतिशील रूपमा समायोजित हुन्छन्:

- **असफल अनुरोधहरू** 10 अंकले स्कोर घटाउनुहोस्
- **स्कोर ≤ 10 मा घट्यो** → प्रोक्सी `inactive` चिन्ह लगाइएको छ
- निष्क्रिय प्रोक्सीहरू रोटेशनबाट बहिष्कृत छन्

### घुमाउने रणनीतिहरू

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

1 प्रोक्सी सिंकमा निर्मित सर्किट ब्रेकर छ:

- पछि** 5 लगातार सिंक विफलता** , थप सिंक प्रयासहरू अवरुद्ध छन्
- रिसेट गर्नुहोस्: `resetOneproxyCircuitBreaker()` वा सर्भर पुन: सुरु गर्नुहोस्
- सिंक स्थिति `GET /api/settings/oneproxy?action=status` मा उपलब्ध छ

### १ प्रोक्सी प्रोक्सीहरू खाली गर्दै

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## एन्टी-डिटेक्शन र स्टिल्थ

OmniRoute ट्राफिकलाई प्रोक्सी — मार्फत मात्र रुट गर्दैन यसले ट्राफिकलाई वैध देखिन्छ:

### TLS फिंगरप्रिन्ट स्पूफिंग

ब्राउजर-जस्तै TLS फिंगरप्रिन्टहरू उत्पन्न गर्न `wreq-js` प्रयोग गर्दछ, बट पत्ता लगाउने प्रणालीहरू बाइपास गर्दै जसले ब्राउजर TLS ह्यान्डशेकहरूलाई फ्ल्याग गर्दछ।

### CLI फिंगरप्रिन्ट मिलान

द**CLI फिंगरप्रिन्ट टगल** (`Settings → Security`) ले HTTP हेडरहरू र JSON बडी फिल्डहरूलाई नेटिभ CLI बाइनरीहरू (Claude कोड, Codex, इत्यादि) को सही हस्ताक्षर मिलाउन पुन: क्रमबद्ध गर्दछ। यो काम गर्छ** माथि** प्रोक्सी:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

तपाईले दुबै पाउनुहुन्छ**IP मास्किङ** र** प्रमाणिकता अनुरोध** एकै साथ।

### प्रोक्सी IP संरक्षण

ड्यासबोर्डमा रङ-कोडित ब्याजहरूले कुन प्रोक्सी स्तर सक्रिय छ देखाउँछन्:

| ब्याज | स्तर        | अर्थ                                            |
| ----- | ----------- | ----------------------------------------------- |
| 🟢    | विश्वव्यापी | सबै ट्राफिक यो प्रोक्सी मार्फत जान्छ            |
| 🟡    | प्रदायक     | यो प्रदायकको ट्राफिक मात्र प्रोक्सी गरिएको छ    |
| 🔵    | जडान        | यो विशिष्ट key/account यो प्रोक्सी प्रयोग गर्दछ |

ब्याजले प्रमाणीकरणको लागि समाधान गरिएको प्रोक्सी IP पनि देखाउँछ।

---

## अपस्ट्रीम प्रोक्सी मोडहरू

CLIProxyAPI ढाँचा प्रयोग गर्ने प्रदायकहरूका लागि, OmniRoute तीनवटा अपस्ट्रिम प्रोक्सी मोडहरूलाई समर्थन गर्दछ:

| मोड           | विवरण                                                         |
| ------------- | ------------------------------------------------------------- |
| `native`      | OmniRoute प्रोक्सी राउटिङ सिधै ह्यान्डल गर्छ (पूर्वनिर्धारित) |
| `cliproxyapi` | बाह्य CLIProxyAPI उदाहरणका लागि प्रतिनिधिहरू                  |
| `fallback`    | पहिले नेटिभ कोसिस गर्छ, CLIProxyAPI मा फर्किन्छ               |

प्रति-प्रदायक कन्फिगर गर्नुहोस्:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## ड्यासबोर्ड UI

### सेटिङहरू → प्रोक्सी ट्याब

- **ग्लोबल प्रोक्सी** कन्फिगरेसन (सबै ट्राफिकको लागि एक पटक सेट गर्नुहोस्)
- **प्रति-प्रदायक प्रोक्सी** ओभरराइड गर्दछ
- **प्रति-जडान प्रोक्सी** असाइनमेन्टहरू
- **जडान परीक्षण** कन्फिगर गरिएको प्रोक्सी मार्फत
- **रंग-कोडित ब्याजहरू** सक्रिय प्रोक्सी स्तर देखाउँदै

### सेटिङहरू → 1 proxy ट्याब

- **अहिले सिङ्क गर्नुहोस्** नि: शुल्क प्रोक्सीहरू ल्याउन बटन
- **तथ्याङ्क कार्डहरू** : कुल, सक्रिय, औसत गुणस्तर, अन्तिम सिङ्क
- **फिल्टरहरू** : प्रोटोकल, देश कोड, न्यूनतम गुणस्तर
- **प्रोक्सी तालिका** होस्ट, प्रोटोकल, देश, गुणस्तर स्कोर, विलम्बता, अज्ञातता, Google पहुँच संग
- **सिंक स्थिति** success/failure ट्र्याकिङ र लगातार असफलता गणना भएको प्यानल
- **सबै खाली गर्नुहोस्** सबै 1 प्रोक्सी प्रविष्टिहरू हटाउन

---

## API सन्दर्भ

### प्रोक्सी सेटिङहरू API

| विधि     | अन्तिम बिन्दु                                  | विवरण                                       |
| -------- | ---------------------------------------------- | ------------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | पूर्ण प्रोक्सी कन्फिगरेसन प्राप्त गर्नुहोस् |
| `GET`    | `/api/settings/proxy?level=global`             | विश्वव्यापी प्रोक्सी प्राप्त गर्नुहोस्      |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | प्रदायक प्रोक्सी प्राप्त गर्नुहोस्          |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | प्रभावकारी प्रोक्सी समाधान गर्नुहोस्        |
| `PUT`    | `/api/settings/proxy`                          | प्रोक्सी कन्फिगरेसन अपडेट गर्नुहोस्         |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | स्तरमा प्रोक्सी हटाउनुहोस्                  |

### प्रोक्सी रजिस्ट्री API

| विधि     | अन्तिम बिन्दु                                     | विवरण                                 |
| -------- | ------------------------------------------------- | ------------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | सबै प्रोक्सीहरू सूचीबद्ध गर्नुहोस्    |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID द्वारा प्रोक्सी प्राप्त गर्नुहोस्  |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | प्रोक्सी असाइनमेन्ट प्राप्त गर्नुहोस् |
| `POST`   | `/api/v1/management/proxies`                      | प्रोक्सी सिर्जना गर्नुहोस्            |
| `PATCH`  | `/api/v1/management/proxies`                      | प्रोक्सी अपडेट गर्नुहोस्              |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | प्रोक्सी मेटाउनुहोस्                  |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | जबरजस्ती मेटाउनुहोस्                  |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | बल्क तोक्ने                           |
| `GET`    | `/api/v1/management/proxies/assignments`          | असाइनमेन्टहरू सूचीबद्ध गर्नुहोस्      |
| `GET`    | `/api/v1/management/proxies/health`               | प्रोक्सी स्वास्थ्य तथ्याङ्क           |

### सुरुङहरू API

प्रोक्सी मार्फत आउटबाउन्ड रुट गर्नुको सट्टा सार्वजनिक इन्टरनेट (Cloudflare/ngrok/Tailscale) मा तपाइँको OmniRoute उदाहरण उजागर गर्न, [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) हेर्नुहोस्। सुरुङ REST API `/api/tunnels/{cloudflared,ngrok,tailscale}/*` अन्तर्गत रहन्छ र माथि उल्लेखित आउटबाउन्ड प्रोक्सी चेनमा अर्थोगोनल छ।

### 1 proxy API

| विधि     | अन्तिम बिन्दु                          | विवरण                                     |
| -------- | -------------------------------------- | ----------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | 1 प्रोक्सी प्रोक्सीहरू सूचीबद्ध गर्नुहोस् |
| `GET`    | `/api/settings/oneproxy?action=stats`  | तथ्याङ्क + सिंक स्थिति प्राप्त गर्नुहोस्  |
| `GET`    | `/api/settings/oneproxy?action=status` | सिंक स्थिति मात्र प्राप्त गर्नुहोस्       |
| `POST`   | `/api/settings/oneproxy`               | ट्रिगर सिंक                               |
| `POST`   | `/api/settings/oneproxy/rotate`        | अर्को प्रोक्सीमा घुमाउनुहोस्              |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | एउटा मेट्नुहोस्                           |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | सबै खाली गर्नुहोस्                        |

### अपस्ट्रीम प्रोक्सी API

| विधि     | अन्तिम बिन्दु                     | विवरण                                           |
| -------- | --------------------------------- | ----------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | अपस्ट्रीम प्रोक्सी कन्फिगरेसन प्राप्त गर्नुहोस् |
| `PUT`    | `/api/upstream-proxy/:providerId` | अपस्ट्रीम प्रोक्सी मोड सेट गर्नुहोस्            |
| `DELETE` | `/api/upstream-proxy/:providerId` | अपस्ट्रीम प्रोक्सी कन्फिगरेसन हटाउनुहोस्        |

---

## वातावरण चर

| चर                    | पूर्वनिर्धारित | विवरण                                                                              |
| --------------------- | -------------- | ---------------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`         | SOCKS5 प्रोक्सी समर्थन सक्षम गर्नुहोस् ( `.env.example` मा पूर्वनिर्धारित `true` ) |

---

## समस्या निवारण

### "SOCKS5 प्रोक्सी असक्षम छ"

तपाईंको `.env` फाइलमा `ENABLE_SOCKS5_PROXY=true` सेट गर्नुहोस् र पुन: सुरु गर्नुहोस्।

### प्रोक्सी मार्फत "सकेट ह्याङ्ग अप" त्रुटिहरू

यो सस्तो प्रोक्सीहरूसँग सामान्य छ जसले निष्क्रिय जडानहरू छोड्छ। OmniRoute ले यसलाई पहिले नै ह्यान्डल गर्छ:

- प्रोक्सी जडानहरूमा जीवित राख्न असक्षम गर्दै (`keepAliveTimeout: 1`)
- पाइपलाइन असक्षम गर्दै (`pipelining: 0`)
- बारम्बार हात मिलाउनबाट बच्न डिस्प्याचरहरूलाई क्यास गर्दै

यदि यो जारी रह्यो भने, फरक प्रोक्सी प्रयास गर्नुहोस् वा 1 प्रोक्सी रोटेशन सुविधा प्रयोग गर्नुहोस्।

### OAuth को समयमा "unsupported_country_region_territory"

सुनिश्चित गर्नुहोस् कि प्रोक्सी कन्फिगर गरिएको छ** अघि** OAuth प्रवाह सुरु गर्दै। OmniRoute रुटहरू OAuth टोकन एक्सचेन्ज कन्फिगर गरिएको प्रोक्सी मार्फत। पहिले ग्लोबल वा प्रदायक-स्तर प्रोक्सी सेट गर्नुहोस्, त्यसपछि जडान गर्नुहोस्।

### प्रोक्सी प्रयोग भइरहेको छैन

रिजोल्युसन अर्डर जाँच गर्नुहोस्:

1. `GET /api/settings/proxy?resolve=your-connection-id` सँग प्रमाणित गर्नुहोस्
2. proxy `status` `active` ( `inactive` होइन) हो कि छैन जाँच गर्नुहोस्
3. सुनिश्चित गर्नुहोस् कि प्रोक्सी असाइनमेन्ट स्कोप तपाईको जडानसँग मेल खान्छ

### 1 प्रोक्सी सिंक असफल

सिंक स्थिति जाँच गर्नुहोस्:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

यदि `consecutiveFailures >= 5`, सर्किट ब्रेकर ट्रिप भएको छ। रिसेट गर्न सर्भर रिस्टार्ट गर्नुहोस्, वा म्यानुअल रिसेटको लागि पर्खनुहोस्।

---

## डाटाबेस स्कीमा

### `proxy_registry` तालिका

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

### `proxy_assignments` तालिका

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

## प्रोक्सी स्वास्थ्य जाँच (v3.8.16 +)

OmniRoute's** प्रोक्सी छिटो असफल** मेकानिजम (`src/lib/proxyHealth.ts`) ले द्रुत TCP जडान जाँच मार्फत < 2s मा मृत प्रोक्सीहरू पत्ता लगाउँदछ, त्यसपछि** परिणाम क्यास गर्दछ** प्रति-अनुरोध ओभरहेडबाट बच्न।

### यो कसरी काम गर्दछ

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

यो बिना, एक मृत प्रोक्सी असफल हुनु अघि पूर्ण `PROXY_TIMEOUT_MS` (पूर्वनिर्धारित 30s) को लागी प्रत्येक अनुरोध ब्लक गर्नेछ।

### ट्युनेबल वातावरण चर

| चर                           | पूर्वनिर्धारित | उद्देश्य                                       |
| ---------------------------- | -------------- | ---------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`         | स्वास्थ्य जाँच प्रतिTCP जडान टाइमआउट           |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`        | स्वास्थ्य परिणाम कति लामो समय सम्म क्यास हुन्छ |

**सिफारिस गरिएका मानहरू:**

| परिदृश्य                   | फास्ट-फेल टाइमआउट | क्यास TTL | तर्क                                                             |
| -------------------------- | ----------------- | --------- | ---------------------------------------------------------------- |
| उच्च-थ्रुपुट API गेटवे     | 1500ms            | 60000ms   | आक्रामक असफल-छिटो, चेक कम गर्न लामो क्यास                        |
| भू-वितरित नोडहरू           | 3000ms            | 15000ms   | ढिलो नेटवर्कहरूलाई थप समय चाहिन्छ; छिटो फेलओभरको लागि छोटो क्यास |
| देव / परीक्षण              | 1000ms            | 10000ms   | स्थानीय प्रोक्सीहरूमा द्रुत पुनरावृत्ति                          |
| चोरी / विरोधी पत्ता लगाउने | 2500ms            | 45000ms   | दर सीमा ट्रिगर गर्न सक्ने द्रुत जाँचबाट बच्नुहोस्                |

### प्रोक्सी स्वास्थ्य निरीक्षण

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

क्यास प्रविष्टिले `HEALTH_CACHE_TTL_MS` नाघेको बेला `stale` झण्डा `true` हुन्छ र अर्को अनुरोधले नयाँ जाँच ट्रिगर गर्नेछ।

### प्रति-प्रोक्सी प्रकार पूर्वनिर्धारित

स्वास्थ्य जाँचले URL योजनामा आधारित समझदार पूर्वनिर्धारितहरू प्रयोग गर्दछ:

| योजना                      | पूर्वनिर्धारित पोर्ट |
| -------------------------- | -------------------- |
| `http://`                  | 8080                 |
| `https://`                 | 443                  |
| `socks5://` / `socks5h://` | 1080                 |

URL (`http://host:9999`) मा अनुकूलन पोर्टहरू योजना पूर्वनिर्धारितमा सधैं प्राथमिकता लिन्छन्।

---

## प्रोक्सी एनालिटिक्स र अवलोकन योग्यता

OmniRoute अपरेटरहरूलाई राउटिंग ढाँचा, विलम्बता स्पाइक्स, र पुनरावर्ती विफलताहरू निदान गर्न मद्दत गर्न प्रति-प्रोक्सी प्रयोग ट्र्याक गर्दछ।

### के ट्र्याक गरिएको छ

कन्फिगर गरिएको प्रोक्सी मार्फत प्रत्येक अनुरोधको लागि, OmniRoute रेकर्डहरू:

| मेट्रिक      | विवरण                                                      |
| ------------ | ---------------------------------------------------------- |
| `proxy_url`  | पूर्ण प्रोक्सी URL (प्रमाणीकरण प्रमाणहरू मास्क गरिएको साथ) |
| `provider`   | अपस्ट्रीम प्रदायक ID (openai, anthropic, आदि)              |
| `latency_ms` | प्रोक्सी ह्यान्डशेक सहित कुल राउन्ड-ट्रिप समय              |
| `connect_ms` | TCP जडान समय मात्र                                         |
| `status`     | अपस्ट्रीमबाट HTTP स्थिति कोड                               |
| `error`      | अनुरोध असफल भएमा त्रुटि वर्ग                               |
| `timestamp`  | ISO 8601 UTC                                               |

### डाटा पहुँच गर्दै

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

वास्तविक अन्तिम बिन्दु `/api/usage/proxy-logs` हो ( `src/app/api/usage/proxy-logs/route.ts` हेर्नुहोस्)। यो अन्त्य बिन्दु समर्थन गर्दछ:

- `GET /api/usage/proxy-logs` — प्रोक्सी लगहरू पुन: प्राप्त गर्नुहोस्
- `DELETE /api/usage/proxy-logs` — सबै प्रोक्सी लगहरू खाली गर्नुहोस्

समग्र तथ्याङ्कहरू आवश्यक भएमा SQL मार्फत `proxy_logs` तालिकाबाट सीधै सोध्न सकिन्छ। ड्यासबोर्ड UI समग्र दृश्यहरू प्रस्ताव गर्न सक्छ।

### साझा ढाँचाहरू

**फ्ल्यापिङ प्रोक्सी पत्ता लगाउनुहोस्** ( success/failure बीचको विकल्प):

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

**ढिलो प्रोक्सीहरू फेला पार्नुहोस्** (p95 विलम्बता > 2s):

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

## रोटेशन रणनीति निर्णय रूख

जब धेरै प्रोक्सीहरू स्कोपमा तोकिएका हुन्छन्, OmniRoute a प्रयोग गर्दछ** घुमाउने रणनीति** प्रत्येक अनुरोधको लागि कुन प्रयोग गर्ने छनोट गर्न। रणनीति स्कोप स्तरमा कन्फिगर गरिएको छ (वैश्विक, प्रति-प्रदायक, प्रति-खाता, प्रति-कम्बो)।

### उपलब्ध रणनीतिहरू

| रणनीति                     | कहिले प्रयोग गर्ने                        | व्यापार बन्द                                                               |
| -------------------------- | ----------------------------------------- | -------------------------------------------------------------------------- |
| `quality` (पूर्वनिर्धारित) | मिश्रित-गुणस्तर प्रोक्सीहरूको साथ उत्पादन | उच्च-मूल्याङ्कन प्रोक्सीहरूको पक्षमा; कम मूल्याङ्कन भएकाहरूलाई भोकाउन सक्छ |
| `random`                   | लोड वितरण, गोपनीयता                       | समान वितरण; गुणस्तर संकेतहरू बेवास्ता गर्दछ                                |
| `sequential`               | डिबगिङ, नियतात्मक परीक्षण                 | क्रमबद्ध रूपमा प्रोक्सीहरू मार्फत चक्रहरू; तर्क गर्न सजिलो                 |

### निर्णय रूख

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

## तपाईंको आफ्नै प्रोक्सीहरूको लागि स्वचालित विफलता बहिष्कार

1proxy मार्केटप्लेस पूलले पहिले नै असफल प्रोक्सीहरूलाई आफ्नै रूपमा स्वतः-डिग्रेड गर्छ ( [प्रोक्सी गुणस्तर स्कोर](#proxy-quality-scores) हेर्नुहोस्)। प्रोक्सीहरूको लागि** तिमी** रजिस्ट्रीमा थपिएको, पृष्ठभूमि स्वास्थ्य अनुसूचक (`src/lib/proxyHealth/scheduler.ts`) ले उही "चेनबाट मृत सदस्यलाई स्वचालित रूपमा बहिष्कार गर्नुहोस्" व्यवहार प्रदान गर्दछ, केहि पनि नमेटाईकन:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

यो कसरी बहु-प्रोक्सी श्रृंखलामा फिट हुन्छ:

1. अनुसूचकले प्रत्येक दर्ता प्रोक्सी प्रत्येक `PROXY_HEALTH_INTERVAL_MS` (पूर्वनिर्धारित 10 मिनेट; न्यूनतम 1 मिनेट) जाँच गर्दछ।
2. `PROXY_AUTO_REMOVE_AFTER` पछि लगातार** निर्णायक** विफलताहरू (एक वास्तविक जडान विफलता — एक टाइमआउट वा प्रोब लक्ष्यको आफ्नै 5xx कहिल्यै गणना गर्दैन, [प्रोक्सी स्वास्थ्य जाँच](#proxy-health-checking-v3816) हेर्नुहोस्), प्रोक्सीको `status` `dead` मा सेट गरिएको छ।
3. `dead` pool/rotation रिजोल्युसनद्वारा प्रयोग गरिएको लाइभ-स्टेटस फिल्टरले समावेश नगर्ने अवस्थाहरू मध्ये एक हो, त्यसैले स्कोपको रोटेशन (राउण्ड-रोबिन / अनियमित / स्टिकी / लेटन्सी — [रोटेशन रणनीति निर्णय ट्री](#rotation-strategy-decision-tree) हेर्नुहोस्) ले तुरुन्तै नयाँ अनुरोधहरूलाई प्रोक्सी हस्तान्तरण गर्न रोक्छ। पूलमा कुनै पनि अन्य प्रोक्सीहरू प्रभावित छैनन्, र पूरै पोखरी कहिल्यै चुपचाप सीधा जडानमा फर्किने छैन — [4-स्तर प्रोक्सी प्रणाली](#4-level-proxy-system) असफल-बन्द गार्ड हेर्नुहोस्।
4. The scheduler keeps probing `dead` proxies on the same interval. The next successful probe flips `status` back to `active` and it re-enters rotation — no manual re-add required.

यो जानाजानी हो** अप्ट-इन र गैर-विनाशकारी** : पूर्वनिर्धारित रूपमा अनुसूचकले असफलताहरू मात्र गणना र लग गर्दछ (हेर्नुहोस् नीति C `decision.ts` मा), र `PROXY_AUTO_DISABLE` पङ्क्ति — मेटाउँदैन जुन अलग, बढी आक्रामक `PROXY_AUTO_REMOVE` झण्डाको लागि हो। यदि दुबै `true` मा सेट गरिएको छ भने, `PROXY_AUTO_REMOVE` जित्छ (मेटिने बारे प्रोक्सी बीचमा सफ्ट-असक्षमको लागि कुनै उपयोग छैन)। पूर्ण चर सूचीको लागि [वातावरण कन्फिग](../reference/ENVIRONMENT.md) सन्दर्भ हेर्नुहोस्।

---

> 📖** सम्बन्धित कागजात:**
>
> - [प्रयोगकर्ता गाइड](../guides/USER_GUIDE.md) — सामान्य सेटअप र कन्फिगरेसन - [API सन्दर्भ](../reference/API_REFERENCE.md) — पूर्ण API कागजात - [वातावरण कन्फिग](../reference/ENVIRONMENT.md) — सबै वातावरण चरहरू
