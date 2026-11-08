# 🌐 OmniRoute Proxy Guide (বাংলা)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **ভৌগলিক ব্লকগুলিকে বাইপাস করুন, আপনার পরিচয় রক্ষা করুন এবং শূন্য কনফিগারেশন জটিলতার সাথে যেকোনো প্রক্সি — এর মাধ্যমে AI ট্র্যাফিককে রুট করুন৷**

OmniRoute একটি সম্পূর্ণ বৈশিষ্ট্যযুক্ত প্রক্সি ম্যানেজমেন্ট সিস্টেম রয়েছে যা আপনাকে HTTP, HTTPS বা SOCKS5 প্রক্সির মাধ্যমে আপস্ট্রিম AI প্রদানকারীর ট্র্যাফিককে রুট করতে দেয়। আপনি একটি অবরুদ্ধ অঞ্চলে থাকুন না কেন, IP ঘূর্ণন প্রয়োজন, বা স্টিলথ ফিঙ্গারপ্রিন্টিং — চান এই নির্দেশিকা সবকিছু কভার করে৷

---

## সূচিপত্র

- [কেন প্রক্সি ব্যবহার করবেন?](#why-use-proxies)
- [আর্কিটেকচার ওভারভিউ](#architecture-overview)
- [4-স্তরের প্রক্সি সিস্টেম](#4-level-proxy-system)
- [প্রক্সি রেজিস্ট্রি (CRUD)](#proxy-registry-crud)
- [1 প্রক্সি ফ্রি মার্কেটপ্লেস](#1proxy-free-proxy-marketplace)
- [প্রক্সি ঘূর্ণন](#proxy-rotation)
- [অ্যান্টি-ডিটেকশন এবং স্টিলথ](#anti-detection--stealth)
- [আপস্ট্রিম প্রক্সি মোড](#upstream-proxy-modes)
- [ড্যাশবোর্ড UI](#dashboard-ui)
- [API রেফারেন্স](#api-reference)
- [এনভায়রনমেন্ট ভেরিয়েবল](#environment-variables)
- [সমস্যা সমাধান](#troubleshooting)

---

## কেন প্রক্সি ব্যবহার করবেন?

অনেক AI প্রদানকারী ভৌগলিক অঞ্চল দ্বারা অ্যাক্সেস সীমাবদ্ধ করে। বিকাশকারীরা** রাশিয়া, চীন, ইরান, কিউবা, তুরস্ক** , এবং অন্যান্য দেশগুলি যেমন ত্রুটির সম্মুখীন হয়:

```
unsupported_country_region_territory
```

এমনকি বাইরের অবরুদ্ধ অঞ্চলে, প্রক্সিগুলি এর জন্য দরকারী:

| কেস ব্যবহার করুন  | বর্ণনা                                                                |
| ----------------- | --------------------------------------------------------------------- |
| **ভৌগলিক বাইপাস** | অবরুদ্ধ দেশগুলি থেকে OpenAI, Anthropic, Codex, Copilot অ্যাক্সেস করুন |
| **IP ঘূর্ণন**     | হার সীমাবদ্ধতা এড়াতে একাধিক IPs জুড়ে অনুরোধগুলি বিতরণ করুন          |
| **গোপনীয়তা**     | আপস্ট্রিম প্রদানকারীদের থেকে আপনার আসল IP লুকান                       |
| **সম্মতি**        | নির্দিষ্ট এখতিয়ারের মাধ্যমে ট্র্যাফিক রুট করুন                       |
| **টেস্টিং**       | বিভিন্ন অঞ্চল থেকে অনুরোধ অনুকরণ                                      |

---

## আর্কিটেকচার ওভারভিউ

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

### মূল উপাদান

| কম্পোনেন্ট             | ফাইল                                         | ভূমিকা                                                   |
| ---------------------- | -------------------------------------------- | -------------------------------------------------------- |
| **প্রক্সি রেজিস্ট্রি** | `src/lib/db/proxies.ts`                      | প্রক্সি এন্ট্রির জন্য CRUD + স্কোপ অ্যাসাইনমেন্ট         |
| **প্রক্সি প্রেরণকারী** | `open-sse/utils/proxyDispatcher.ts`          | ক্যাশিং সহ `undici` ProxyAgent/SOCKS প্রেরণকারী তৈরি করে |
| **প্রক্সি আনা**        | `open-sse/utils/proxyFetch.ts`               | প্রক্সি ডিসপ্যাচার ইনজেকশন দিয়ে `fetch()` মোড়ানো       |
| **সেটিংস রুট**         | `src/app/api/settings/proxy/route.ts`        | লিগ্যাসি প্রক্সি কনফিগারেশন API (GET/PUT/DELETE)         |
| **ম্যানেজমেন্ট রুট**   | `src/app/api/v1/management/proxies/route.ts` | রেজিস্ট্রি CRUD API (GET/POST/PATCH/DELETE)              |
| **1 প্রক্সি DB**       | `src/lib/db/oneproxy.ts`                     | বিনামূল্যে প্রক্সি মার্কেটপ্লেস অধ্যবসায়                |

---

## নতুন অ্যাকাউন্টের জন্য ডিফল্ট প্রক্সি অবস্থা

ইন** সেটিংস → প্রক্সি → গ্লোবাল কনফিগারেশন** , ব্যবহার করুন** নতুন সংযোগের জন্য ডিফল্টরূপে প্রক্সি সক্ষম করুন৷** নতুন যোগ করা প্রদানকারী অ্যাকাউন্টের প্রাথমিক প্রক্সি অবস্থা বেছে নিতে।

নতুন সেটিং নতুন যোগ করা প্রদানকারী অ্যাকাউন্টের প্রাথমিক প্রক্সি অবস্থা নিয়ন্ত্রণ করে। এটি বিদ্যমান অ্যাকাউন্ট পরিবর্তন করে না বা গ্লোবাল প্রক্সি সুইচ প্রতিস্থাপন করে না। এর প্রাথমিক মান পূর্ববর্তী আচরণ সংরক্ষণ করে। ডিফল্টরূপে অক্ষম প্রক্সি সহ ভবিষ্যতের অ্যাকাউন্ট তৈরি করতে একবার এটি বন্ধ করুন৷

পছন্দটি বিদ্যমান সেটিংস API মাধ্যমে `defaultNewConnectionProxyEnabled` হিসাবে সংরক্ষণ করা হয়। এটি `true` তে ডিফল্ট হয় যখন সংরক্ষণ করা হয় না। রিস্টার্ট ছাড়াই পরবর্তী নতুন অ্যাকাউন্টগুলির জন্য `false` সংরক্ষণ করা কার্যকর হয়৷ `POST /api/providers` একটি ঐচ্ছিক কঠোর বুলিয়ান `proxyEnabled` গ্রহণ করে; একটি স্পষ্ট `true` বা `false` ক্রিয়েশন ডিফল্টের উপর প্রাধান্য পায়। একটি ডুপ্লিকেট অ্যাকাউন্ট বা OAuth পুনরায় সংযোগে বাদ দেওয়া সেই অ্যাকাউন্টের সংরক্ষিত অবস্থা সংরক্ষণ করে। ব্যক্তিগত অ্যাকাউন্টগুলি তারপরেও সক্ষম বা অক্ষম করা যেতে পারে।

নির্বাচনী প্রদানকারী স্থানান্তরগুলি নতুন অ্যাকাউন্টগুলির জন্য গন্তব্য ইনস্টলেশনের ডিফল্ট ব্যবহার করে এবং বিদ্যমান অ্যাকাউন্টগুলি প্রতিস্থাপন করার সময় গন্তব্য নীতি সংরক্ষণ করে। প্রক্সি টগলগুলি বহনযোগ্য স্থানান্তর ক্ষেত্র নয়৷ সম্পূর্ণ ব্যাকআপ পুনরুদ্ধার এবং ঐতিহাসিক JSON/SQL মাইগ্রেশন তাদের বিদ্যমান পুনরুদ্ধার শব্দার্থকে ধরে রাখে, সংরক্ষিত অ্যাকাউন্ট মান এবং লিগ্যাসি স্কিমা ডিফল্ট সহ; একটি সম্পূর্ণ সেটিংস পুনরুদ্ধারও এই পছন্দটি পুনরুদ্ধার করতে পারে।

এই পছন্দটি একটি প্রক্সি বরাদ্দ করে না বা প্রতিষ্ঠিত করে না যে একটি সুস্থ বা ব্যবহার করা হচ্ছে। প্রকৃত রাউটিং এখনও বিশ্বব্যাপী প্রক্সি সুইচ এবং প্রযোজ্য প্রক্সি কনফিগারেশনের উপর নির্ভর করে। ক্রমাগত অ্যাকাউন্ট ছাড়াই সিন্থেটিক প্রদানকারী, অ্যাকাউন্ট তৈরির আগে OAuth ট্রাফিক, environment/system প্রক্সি, এবং বহিরাগত ব্যাকএন্ডের নেটওয়ার্কিং এর সুযোগের বাইরে।

## 4-স্তরের প্রক্সি সিস্টেম

OmniRoute এ প্রক্সি কনফিগারেশন সমর্থন করে** চারটি স্বাধীন সুযোগ** , অগ্রাধিকার ক্রমে সমাধান করা হয়েছে:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### কিভাবে রেজোলিউশন কাজ করে

যখন OmniRoute একটি আপস্ট্রিম প্রদানকারীকে একটি অনুরোধ পাঠায়, তখন এটি `resolveProxyForConnectionFromRegistry()` কল করে যা প্রতিটি স্তরকে ক্রমানুসারে পরীক্ষা করে:

1. **অ্যাকাউন্ট-স্তর** — এই নির্দিষ্ট সংযোগ ID এ কি কোনো প্রক্সি বরাদ্দ করা আছে?
2. **প্রদানকারীর স্তর** — এই প্রদানকারীকে কি কোন প্রক্সি বরাদ্দ করা হয়েছে (যেমন, `openai`)?
3. **বিশ্ব-স্তরের** — একটি বিশ্বব্যাপী প্রক্সি কনফিগার করা আছে?
4. **কোনো প্রক্সি নেই** — প্রদানকারীর সাথে সরাসরি সংযোগ।

প্রথম ম্যাচে জয়। এর মানে হল আপনি একটি গ্লোবাল প্রক্সি একটি ফলব্যাক হিসাবে সেট করতে পারেন তবে নির্দিষ্ট প্রদানকারী বা সংযোগগুলির জন্য এটিকে ওভাররাইড করতে পারেন৷

### কি প্রক্সি পায়

| ট্রাফিকের ধরন       | প্রক্সিড? | নোট                                               |
| ------------------- | --------- | ------------------------------------------------- |
| চ্যাট সমাপ্তি       | ✅        | সমস্ত `/v1/chat/completions` অনুরোধ               |
| এমবেডিং             | ✅        | `/v1/embeddings`                                  |
| ইমেজ প্রজন্ম        | ✅        | `/v1/images/generations`                          |
| অডিও (TTS/STT)      | ✅        | `/v1/audio/*`                                     |
| OAuth টোকেন বিনিময় | ✅        | `unsupported_country_region_territory` সমাধান করে |
| সংযোগ পরীক্ষা       | ✅        | "পরীক্ষা সংযোগ" বোতাম প্রক্সি ব্যবহার করে         |
| টোকেন রিফ্রেশ       | ✅        | পটভূমি OAuth পুনর্নবীকরণ                          |
| মডেল সিঙ্ক          | ✅        | মডেল তালিকা এবং আবিষ্কার                          |

---

## প্রক্সি রেজিস্ট্রি (CRUD)

প্রক্সি রেজিস্ট্রি হল একটি SQLite টেবিল (`proxy_registry`) যা আপনার সমস্ত প্রক্সি সংরক্ষণ করে। প্রতিটি প্রক্সি আছে:

| মাঠ        | টাইপ        | বর্ণনা                                               |
| ---------- | ----------- | ---------------------------------------------------- |
| `id`       | UUID        | অনন্য শনাক্তকারী                                     |
| `name`     | স্ট্রিং     | মানব-পাঠযোগ্য লেবেল                                  |
| `type`     | স্ট্রিং     | প্রোটোকল: `http`, `https`, `socks5`                  |
| `host`     | স্ট্রিং     | প্রক্সি হোস্টনাম বা IP                               |
| `port`     | পূর্ণসংখ্যা | পোর্ট নম্বর                                          |
| `username` | স্ট্রিং     | প্রমাণীকরণ ব্যবহারকারীর নাম (বিশ্রামে এনক্রিপ্ট করা) |
| `password` | স্ট্রিং     | প্রমাণীকরণ পাসওয়ার্ড (বিশ্রামে এনক্রিপ্ট করা)       |
| `region`   | স্ট্রিং     | ভৌগলিক অঞ্চল লেবেল                                   |
| `notes`    | স্ট্রিং     | ফ্রি-টেক্সট নোট                                      |
| `status`   | স্ট্রিং     | `active` বা `inactive`                               |
| `source`   | স্ট্রিং     | `manual` বা `oneproxy`                               |

### একটি প্রক্সি তৈরি করা হচ্ছে

**ড্যাশবোর্ডের মাধ্যমে:**

1. যান** সেটিংস → প্রক্সি**
2. ক্লিক করুন** প্রক্সি যোগ করুন**
3. ধরন, হোস্ট, পোর্ট এবং ঐচ্ছিক প্রমাণীকরণ শংসাপত্রগুলি পূরণ করুন৷
4. সংরক্ষণ করুন

**API এর মাধ্যমে:**

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

### একটি প্রক্সি আপডেট করা হচ্ছে

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **দ্রষ্টব্য:** শংসাপত্রগুলি সংরক্ষিত হয় যদি না আপনি স্পষ্টভাবে অ-খালি প্রতিস্থাপন না পাঠান। `username`/`password` এর জন্য খালি স্ট্রিং পাঠানোর ফলে সঞ্চিত মান বজায় থাকবে।

### একটি প্রক্সি মুছে ফেলা হচ্ছে

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### তালিকা প্রক্সি

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### স্কোপে প্রক্সি বরাদ্দ করা

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

### কার্যকরী প্রক্সি সমাধান করা

প্রদত্ত সংযোগের জন্য কোন প্রক্সি ব্যবহার করা হবে তা পরীক্ষা করুন:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

এর স্তর (`account`, `provider`, বা `global`) এবং উত্স সহ সমাধানকৃত প্রক্সি ফেরত দেয়৷

### বাল্ক অ্যাসাইনমেন্ট

একযোগে একাধিক প্রদানকারী বা সংযোগে একটি প্রক্সি বরাদ্দ করুন:

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

প্রক্সি অন্তর্ভুক্ত করা হয়**Backup/Restore** সিস্টেম আপনি যখন আপনার OmniRoute কনফিগারেশন রপ্তানি করেন:

1. যান** ড্যাশবোর্ড → সেটিংস → ব্যাকআপ**
2. ক্লিক করুন** রপ্তানি** — প্রক্সি রেজিস্ট্রি এবং অ্যাসাইনমেন্ট অন্তর্ভুক্ত করা হয়েছে
3. পুনরুদ্ধার করতে, ক্লিক করুন** আমদানি** এবং ব্যাকআপ ফাইল আপলোড করুন

প্রক্সি রেজিস্ট্রিও সমর্থন করে** হোস্ট + পোর্ট দ্বারা upsert** — যদি আপনি একটি প্রক্সি আমদানি করেন যা ইতিমধ্যেই বিদ্যমান (একই হোস্ট এবং পোর্ট), এটি একটি সদৃশ তৈরি করার পরিবর্তে আপডেট হয়।

### উত্তরাধিকার মাইগ্রেশন

আপনি যদি একটি পুরানো সংস্করণে (প্রি-রেজিস্ট্রি) প্রক্সি কনফিগার করেন, OmniRoute স্বয়ংক্রিয়ভাবে সেগুলি স্থানান্তরিত করে:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

আপগ্রেড করার পরে প্রথম স্টার্টআপে একবার এটি ঘটে। পুনরায় চালানোর জন্য `migrateLegacyProxyConfigToRegistry({ force: true })` ব্যবহার করুন।

---

## 1প্রক্সি ফ্রি প্রক্সি মার্কেটপ্লেস

> 🆕** [@oyi77](https://github.com/oyi77) দ্বারা অবদান** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (ইস্যু [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute এর সাথে একীভূত হয়** [1 প্রক্সি](https://1proxy-api.aitradepulse.com)** কমিউনিটি প্ল্যাটফর্ম অ্যাক্সেস প্রদান করতে** শত শত বিনামূল্যে, বৈধ প্রক্সি** সারা বিশ্ব থেকে এটি এমন ব্যবহারকারীদের জন্য উপযুক্ত যাদের নিজস্ব প্রক্সি অবকাঠামো নেই৷

### কিভাবে এটা কাজ করে

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **সিঙ্ক** — OmniRoute 1proxy API থেকে বৈধ প্রক্সি আনে
2. **দোকান** — প্রক্সিগুলি `source = 'oneproxy'` সাথে একই `proxy_registry` টেবিলে সংরক্ষিত হয়
3. **ফিল্টার** প্রোটোকল, দেশ, মানের স্কোর দ্বারা — ফিল্টার
4. **ঘোরান** — গুণমান, এলোমেলো, বা অনুক্রমিক কৌশল ব্যবহার করে সেরা প্রক্সি বেছে নিন
5. **অটো-ডিগ্রেড** — ব্যর্থ প্রক্সিরা তাদের মানের স্কোর হ্রাস পায়; থ্রেশহোল্ডের নীচে → নিষ্ক্রিয় হিসাবে চিহ্নিত৷

### প্রক্সি সিঙ্ক করা হচ্ছে

**ড্যাশবোর্ডের মাধ্যমে:**

1. যান** সেটিংস → 1proxy** ট্যাব
2. ক্লিক করুন** "এখনই সিঙ্ক করুন"**
3. পরিসংখ্যান দেখুন: মোট প্রক্সি, সক্রিয় গণনা, গড় গুণমান, দেশ অনুসারে ভাঙ্গন

**API এর মাধ্যমে:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### ফিল্টারিং প্রক্সি

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

### প্রক্সি কোয়ালিটি স্কোর

প্রতিটি 1 প্রক্সি প্রক্সি মেটাডেটা সহ আসে:

| মাঠ             | বর্ণনা                                               |
| --------------- | ---------------------------------------------------- |
| `qualityScore`  | 1প্রক্সি বৈধতা থেকে 0-100 রেটিং                      |
| `latencyMs`     | পরিমাপ করা নেটওয়ার্ক লেটেন্সি                       |
| `anonymity`     | `transparent`, `anonymous`, বা `elite`               |
| `googleAccess`  | প্রক্সি Google পরিষেবাগুলি অ্যাক্সেস করতে পারে কিনা৷ |
| `countryCode`   | দুই-অক্ষরের ISO কান্ট্রি কোড                         |
| `lastValidated` | শেষ বৈধতার টাইমস্ট্যাম্প                             |

গুণমানের স্কোর গতিশীলভাবে সমন্বয় করা হয়:

- **ব্যর্থ অনুরোধ** 10 পয়েন্ট দ্বারা স্কোর কমাতে
- **স্কোর ≤ 10 এ নেমে গেছে** → প্রক্সি `inactive` চিহ্নিত করা হয়েছে
- নিষ্ক্রিয় প্রক্সি ঘূর্ণন থেকে বাদ দেওয়া হয়

### ঘূর্ণন কৌশল

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

### সার্কিট ব্রেকার

1প্রক্সি সিঙ্কে একটি অন্তর্নির্মিত সার্কিট ব্রেকার রয়েছে:

- পরে** 5 টানা সিঙ্ক ব্যর্থতা** , আরও সিঙ্ক প্রচেষ্টা ব্লক করা হয়েছে
- এর সাথে রিসেট করুন: `resetOneproxyCircuitBreaker()` বা সার্ভার পুনরায় চালু করুন
- সিঙ্ক স্ট্যাটাস `GET /api/settings/oneproxy?action=status` এ উপলব্ধ

### 1 প্রক্সি প্রক্সি সাফ করা হচ্ছে

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## অ্যান্টি-ডিটেকশন এবং স্টিলথ

OmniRoute শুধুমাত্র একটি প্রক্সি — এর মাধ্যমে ট্রাফিককে রুট করে না এটি ট্র্যাফিককে বৈধ দেখায়:

### TLS ফিঙ্গারপ্রিন্ট স্পুফিং

ব্রাউজার-এর মতো TLS ফিঙ্গারপ্রিন্ট তৈরি করতে `wreq-js` ব্যবহার করে, বট সনাক্তকরণ সিস্টেমগুলিকে বাইপাস করে যা ব্রাউজার নয় TLS হ্যান্ডশেকগুলিকে পতাকাঙ্কিত করে৷

### CLI ফিঙ্গারপ্রিন্ট ম্যাচিং

দ**CLI ফিঙ্গারপ্রিন্ট টগল** (`Settings → Security`) HTTP হেডার এবং JSON বডি ক্ষেত্রগুলিকে নেটিভ CLI বাইনারিগুলির সঠিক স্বাক্ষরের সাথে মেলে (Claude কোড, Codex, ইত্যাদি)। এই কাজ করে** উপরে** প্রক্সি:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

আপনি উভয় পাবেন**IP মাস্কিং** এবং** সত্যতা অনুরোধ** একই সাথে

### প্রক্সি IP সংরক্ষণ

ড্যাশবোর্ডে রঙ-কোডযুক্ত ব্যাজগুলি দেখায় কোন প্রক্সি স্তর সক্রিয়:

| ব্যাজ | স্তর       | অর্থ                                             |
| ----- | ---------- | ------------------------------------------------ |
| 🟢    | গ্লোবাল    | সমস্ত ট্রাফিক এই প্রক্সি দিয়ে যায়              |
| 🟡    | প্রদানকারী | শুধুমাত্র এই প্রদানকারীর ট্রাফিক প্রক্সি করা হয় |
| 🔵    | সংযোগ      | এই নির্দিষ্ট key/account এই প্রক্সি ব্যবহার করে  |

ব্যাজটি যাচাইয়ের জন্য সমাধান করা প্রক্সি IP ও দেখায়।

---

## আপস্ট্রিম প্রক্সি মোড

প্রদানকারীদের জন্য যারা CLIProxyAPI প্যাটার্ন ব্যবহার করে, OmniRoute তিনটি আপস্ট্রিম প্রক্সি মোড সমর্থন করে:

| মোড           | বর্ণনা                                                |
| ------------- | ----------------------------------------------------- |
| `native`      | OmniRoute সরাসরি প্রক্সি রাউটিং পরিচালনা করে (ডিফল্ট) |
| `cliproxyapi` | একটি বহিরাগত CLIProxyAPI উদাহরণে প্রতিনিধি            |
| `fallback`    | প্রথমে নেটিভ চেষ্টা করে, CLIProxyAPI তে ফিরে আসে      |

প্রতি-প্রদানকারী কনফিগার করুন:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## ড্যাশবোর্ড UI

### সেটিংস → প্রক্সি ট্যাব

- **গ্লোবাল প্রক্সি** কনফিগারেশন (সমস্ত ট্রাফিকের জন্য একবার সেট করুন)
- **প্রতি-প্রদানকারী প্রক্সি** ওভাররাইড করে
- **প্রতি-সংযোগ প্রক্সি** অ্যাসাইনমেন্ট
- **সংযোগ পরীক্ষা** কনফিগার করা প্রক্সির মাধ্যমে
- **রঙ-কোডেড ব্যাজ** সক্রিয় প্রক্সি স্তর দেখাচ্ছে

### সেটিংস → 1proxy ট্যাব

- **এখন সিঙ্ক করুন** বিনামূল্যে প্রক্সি আনার বোতাম
- **পরিসংখ্যান কার্ড** : মোট, সক্রিয়, গড় গুণমান, শেষ সিঙ্ক
- **ফিল্টার** : প্রোটোকল, দেশের কোড, ন্যূনতম গুণমান
- **প্রক্সি টেবিল** হোস্ট, প্রোটোকল, দেশ, মানের স্কোর, লেটেন্সি, বেনামী, Google অ্যাক্সেস সহ
- **সিঙ্ক স্থিতি** success/failure ট্র্যাকিং এবং ক্রমাগত ব্যর্থতার সংখ্যা সহ প্যানেল
- **সব সাফ করুন** সমস্ত 1 প্রক্সি এন্ট্রি সরাতে

---

## API রেফারেন্স

### প্রক্সি সেটিংস API

| পদ্ধতি   | শেষবিন্দু                                      | বর্ণনা                          |
| -------- | ---------------------------------------------- | ------------------------------- |
| `GET`    | `/api/settings/proxy`                          | সম্পূর্ণ প্রক্সি কনফিগারেশন পান |
| `GET`    | `/api/settings/proxy?level=global`             | বিশ্বব্যাপী প্রক্সি পান         |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | প্রদানকারী প্রক্সি পান          |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | কার্যকর প্রক্সি সমাধান করুন     |
| `PUT`    | `/api/settings/proxy`                          | প্রক্সি কনফিগারেশন আপডেট করুন   |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | স্তরে প্রক্সি সরান              |

### প্রক্সি রেজিস্ট্রি API

| পদ্ধতি   | শেষবিন্দু                                         | বর্ণনা                       |
| -------- | ------------------------------------------------- | ---------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | সমস্ত প্রক্সি তালিকা         |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID দ্বারা প্রক্সি পান        |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | প্রক্সি অ্যাসাইনমেন্ট পান    |
| `POST`   | `/api/v1/management/proxies`                      | প্রক্সি তৈরি করুন            |
| `PATCH`  | `/api/v1/management/proxies`                      | প্রক্সি আপডেট করুন           |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | প্রক্সি মুছুন                |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | জোর করে মুছে দিন             |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | বাল্ক অ্যাসাইন               |
| `GET`    | `/api/v1/management/proxies/assignments`          | অ্যাসাইনমেন্টের তালিকা করুন  |
| `GET`    | `/api/v1/management/proxies/health`               | প্রক্সি স্বাস্থ্য পরিসংখ্যান |

### টানেল API

প্রক্সির মাধ্যমে আউটবাউন্ড রুট করার পরিবর্তে আপনার OmniRoute ইনস্ট্যান্স পাবলিক ইন্টারনেটে (Cloudflare/ngrok/Tailscale) প্রকাশ করার জন্য, [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) দেখুন। টানেল REST API `/api/tunnels/{cloudflared,ngrok,tailscale}/*` অধীনে থাকে এবং উপরে নথিভুক্ত আউটবাউন্ড প্রক্সি চেইনের জন্য অর্থোগোনাল।

### 1 প্রক্সি API

| পদ্ধতি   | শেষবিন্দু                              | বর্ণনা                         |
| -------- | -------------------------------------- | ------------------------------ |
| `GET`    | `/api/settings/oneproxy`               | 1 প্রক্সি প্রক্সির তালিকা করুন |
| `GET`    | `/api/settings/oneproxy?action=stats`  | পরিসংখ্যান + সিঙ্ক স্থিতি পান  |
| `GET`    | `/api/settings/oneproxy?action=status` | শুধুমাত্র সিঙ্ক স্থিতি পান     |
| `POST`   | `/api/settings/oneproxy`               | ট্রিগার সিঙ্ক                  |
| `POST`   | `/api/settings/oneproxy/rotate`        | পরবর্তী প্রক্সিতে ঘোরান        |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | একটি মুছুন                     |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | সব সাফ করুন                    |

### আপস্ট্রিম প্রক্সি API

| পদ্ধতি   | শেষবিন্দু                         | বর্ণনা                            |
| -------- | --------------------------------- | --------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | আপস্ট্রিম প্রক্সি কনফিগারেশন পান  |
| `PUT`    | `/api/upstream-proxy/:providerId` | আপস্ট্রিম প্রক্সি মোড সেট করুন    |
| `DELETE` | `/api/upstream-proxy/:providerId` | আপস্ট্রিম প্রক্সি কনফিগারেশন সরান |

---

## এনভায়রনমেন্ট ভেরিয়েবল

| পরিবর্তনশীল           | ডিফল্ট | বর্ণনা                                                               |
| --------------------- | ------ | -------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true` | SOCKS5 প্রক্সি সমর্থন সক্ষম করুন ( `.env.example` তে ডিফল্ট `true` ) |

---

## সমস্যা সমাধান

### "SOCKS5 প্রক্সি নিষ্ক্রিয় করা হয়েছে"

আপনার `.env` ফাইলে `ENABLE_SOCKS5_PROXY=true` সেট করুন এবং পুনরায় চালু করুন।

### প্রক্সির মাধ্যমে "সকেট হ্যাং আপ" ত্রুটিগুলি

এটি সস্তা প্রক্সিগুলির সাথে স্বাভাবিক যেগুলি নিষ্ক্রিয় সংযোগগুলি ছেড়ে দেয়৷ OmniRoute ইতিমধ্যে এটি পরিচালনা করে:

- প্রক্সি সংযোগে কিপ-লাইভ অক্ষম করা হচ্ছে (`keepAliveTimeout: 1`)
- পাইপলাইন নিষ্ক্রিয় করা (`pipelining: 0`)
- বারবার হ্যান্ডশেক এড়াতে প্রেরকদের ক্যাশে করা হচ্ছে

যদি এটি অব্যাহত থাকে, একটি ভিন্ন প্রক্সি চেষ্টা করুন বা 1proxy ঘূর্ণন বৈশিষ্ট্য ব্যবহার করুন৷

### OAuth চলাকালীন "অসমর্থিত_দেশ_অঞ্চল_প্রদেশ"

প্রক্সি কনফিগার করা হয়েছে তা নিশ্চিত করুন** আগে** OAuth প্রবাহ শুরু। কনফিগার করা প্রক্সির মাধ্যমে OmniRoute রুট OAuth টোকেন বিনিময় করে। প্রথমে একটি গ্লোবাল বা প্রদানকারী-স্তরের প্রক্সি সেট করুন, তারপর সংযোগ করুন৷

### প্রক্সি ব্যবহার করা হচ্ছে না

রেজোলিউশন অর্ডার চেক করুন:

1. `GET /api/settings/proxy?resolve=your-connection-id` দিয়ে যাচাই করুন
2. প্রক্সি `status` `active` কিনা পরীক্ষা করুন ( `inactive` নয়)
3. প্রক্সি অ্যাসাইনমেন্টের সুযোগ আপনার সংযোগের সাথে মেলে তা নিশ্চিত করুন

### 1 প্রক্সি সিঙ্ক ব্যর্থ হচ্ছে৷

সিঙ্ক স্থিতি পরীক্ষা করুন:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

যদি `consecutiveFailures >= 5`, সার্কিট ব্রেকার ট্রিপ হয়ে গেছে। রিসেট করতে সার্ভারটি রিস্টার্ট করুন বা ম্যানুয়াল রিসেটের জন্য অপেক্ষা করুন।

---

## ডাটাবেস স্কিমা

### `proxy_registry` টেবিল

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

### `proxy_assignments` টেবিল

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

## প্রক্সি স্বাস্থ্য পরীক্ষা (v3.8.16 +)

OmniRoute's** প্রক্সি দ্রুত ব্যর্থ** মেকানিজম (`src/lib/proxyHealth.ts`) একটি দ্রুত TCP সংযোগ চেকের মাধ্যমে < 2s-এ মৃত প্রক্সি সনাক্ত করে, তারপর** ফলাফল ক্যাশে** প্রতি অনুরোধ ওভারহেড এড়াতে.

### কিভাবে এটা কাজ করে

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

এটি ছাড়া, একটি মৃত প্রক্সি ব্যর্থ হওয়ার আগে সম্পূর্ণ `PROXY_TIMEOUT_MS` (ডিফল্ট 30s) এর জন্য প্রতিটি অনুরোধ ব্লক করবে।

### টিউনেবল এনভায়রনমেন্ট ভেরিয়েবল

| পরিবর্তনশীল                  | ডিফল্ট  | উদ্দেশ্য                                    |
| ---------------------------- | ------- | ------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | স্বাস্থ্য পরীক্ষা প্রতিTCP সংযোগের সময়সীমা |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | কতক্ষণ একটি স্বাস্থ্য ফলাফল ক্যাশে করা হয়  |

**প্রস্তাবিত মান:**

| দৃশ্যকল্প                 | দ্রুত ব্যর্থ সময়সীমা | ক্যাশে TTL | যুক্তি                                                                       |
| ------------------------- | --------------------- | ---------- | ---------------------------------------------------------------------------- |
| উচ্চ-থ্রুপুট API গেটওয়ে  | 1500ms                | 60000ms    | আক্রমণাত্মক ব্যর্থ-দ্রুত, চেক কমাতে দীর্ঘ ক্যাশে                             |
| জিও-ডিস্ট্রিবিউটেড নোড    | 3000ms                | 15000ms    | ধীরগতির নেটওয়ার্কের জন্য আরও সময় প্রয়োজন; দ্রুত ব্যর্থতার জন্য ছোট ক্যাশে |
| দেব/পরীক্ষা               | 1000ms                | 10000ms    | স্থানীয় প্রক্সিগুলিতে দ্রুত পুনরাবৃত্তি                                     |
| স্টিলথ / অ্যান্টি-ডিটেকশন | 2500ms                | 45000ms    | দ্রুত অনুসন্ধান এড়িয়ে চলুন যা হারের সীমা ট্রিগার করতে পারে                 |

### প্রক্সি স্বাস্থ্য পরিদর্শন

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

ক্যাশে এন্ট্রি `HEALTH_CACHE_TTL_MS` অতিক্রম করলে `stale` পতাকা `true` হয় এবং পরবর্তী অনুরোধটি একটি নতুন চেক ট্রিগার করবে।

### প্রতি-প্রক্সি টাইপ ডিফল্ট

স্বাস্থ্য পরীক্ষা URL স্কিমের উপর ভিত্তি করে বুদ্ধিমান ডিফল্ট ব্যবহার করে:

| স্কিম                      | ডিফল্ট পোর্ট |
| -------------------------- | ------------ |
| `http://`                  | 8080         |
| `https://`                 | 443          |
| `socks5://` / `socks5h://` | 1080         |

URL (`http://host:9999`) তে কাস্টম পোর্টগুলি সর্বদা স্কিম ডিফল্টের চেয়ে অগ্রাধিকার নেয়।

---

## প্রক্সি বিশ্লেষণ এবং পর্যবেক্ষণযোগ্যতা

OmniRoute প্রতি-প্রক্সি ব্যবহার ট্র্যাক করে অপারেটরদের রাউটিং প্যাটার্ন, লেটেন্সি স্পাইক এবং পুনরাবৃত্তি ব্যর্থতা নির্ণয় করতে।

### কি ট্র্যাক করা হয়েছে

একটি কনফিগার করা প্রক্সির মাধ্যমে প্রতিটি অনুরোধের জন্য, OmniRoute রেকর্ড করে:

| মেট্রিক      | বর্ণনা                                                 |
| ------------ | ------------------------------------------------------ |
| `proxy_url`  | সম্পূর্ণ প্রক্সি URL (প্রমাণপত্র মুখোশ সহ)             |
| `provider`   | আপস্ট্রিম প্রদানকারী ID (ওপেনাই, নৃতাত্ত্বিক, ইত্যাদি) |
| `latency_ms` | প্রক্সি হ্যান্ডশেক সহ মোট রাউন্ড-ট্রিপ সময়            |
| `connect_ms` | TCP সংযোগ সময় শুধুমাত্র                               |
| `status`     | আপস্ট্রিম থেকেHTTP স্ট্যাটাস কোড                       |
| `error`      | অনুরোধ ব্যর্থ হলে ত্রুটি ক্লাস                         |
| `timestamp`  | ISO 8601 UTC                                           |

### ডেটা অ্যাক্সেস করা

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

আসল শেষ বিন্দু হল `/api/usage/proxy-logs` (দেখুন `src/app/api/usage/proxy-logs/route.ts`)। এই শেষ বিন্দু সমর্থন করে:

- `GET /api/usage/proxy-logs` — প্রক্সি লগ পুনরুদ্ধার করুন
- `DELETE /api/usage/proxy-logs` — সমস্ত প্রক্সি লগ সাফ করুন

প্রয়োজনে SQL এর মাধ্যমে সরাসরি `proxy_logs` টেবিল থেকে সমষ্টিগত পরিসংখ্যান জিজ্ঞাসা করা যেতে পারে। ড্যাশবোর্ড UI সমষ্টিগত দর্শন দিতে পারে।

### সাধারণ নিদর্শন

**একটি flapping প্রক্সি সনাক্ত** ( success/failure এর মধ্যে বিকল্প):

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

**ধীর প্রক্সি খুঁজুন** (p95 লেটেন্সি > 2s):

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

## ঘূর্ণন কৌশল সিদ্ধান্ত গাছ

যখন একটি সুযোগে একাধিক প্রক্সি বরাদ্দ করা হয়, তখন OmniRoute a ব্যবহার করে** ঘূর্ণন কৌশল** প্রতিটি অনুরোধের জন্য কোনটি ব্যবহার করতে হবে তা বেছে নিতে। কৌশলটি সুযোগ স্তরে কনফিগার করা হয়েছে (গ্লোবাল, প্রতি-প্রদানকারী, প্রতি-অ্যাকাউন্ট, প্রতি-কম্বো)।

### উপলব্ধ কৌশল

| কৌশল               | কখন ব্যবহার করতে হবে            | বাণিজ্য বন্ধ                                              |
| ------------------ | ------------------------------- | --------------------------------------------------------- |
| `quality` (ডিফল্ট) | মিশ্র-মানের প্রক্সি সহ উত্পাদন  | হাই-রেটেড প্রক্সির পক্ষে; কম রেট বেশী ক্ষুধার্ত হতে পারে  |
| `random`           | লোড বিতরণ, গোপনীয়তা            | এমনকি বিতরণ; মানের সংকেত উপেক্ষা করে                      |
| `sequential`       | ডিবাগিং, ডিটারমিনিস্টিক টেস্টিং | ক্রমানুসারে প্রক্সি মাধ্যমে চক্র; সম্পর্কে যুক্তি করা সহজ |

### সিদ্ধান্ত গাছ

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

## আপনার নিজের প্রক্সির জন্য স্বয়ংক্রিয় ব্যর্থতা বর্জন

1প্রক্সি মার্কেটপ্লেস পুল ইতিমধ্যেই ব্যর্থ প্রক্সিগুলিকে স্বয়ংক্রিয়ভাবে অবনমিত করে ( [প্রক্সি কোয়ালিটি স্কোর](#proxy-quality-scores) দেখুন)। প্রক্সিদের জন্য** আপনি** রেজিস্ট্রিতে যোগ করা হয়েছে, ব্যাকগ্রাউন্ড হেলথ শিডিউলার (`src/lib/proxyHealth/scheduler.ts`) একই "একজন মৃত সদস্যকে স্বয়ংক্রিয়ভাবে চেইন থেকে বাদ দিন" আচরণ প্রদান করে, কিছু মুছে না দিয়ে:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

এটি একটি মাল্টি-প্রক্সি চেইনে কীভাবে ফিট করে:

1. শিডিউলার প্রতিটি `PROXY_HEALTH_INTERVAL_MS` প্রতিটি নিবন্ধিত প্রক্সি পরীক্ষা করে (ডিফল্ট 10 মিনিট; সর্বনিম্ন 1 মিনিট)।
2. পরপর `PROXY_AUTO_REMOVE_AFTER`** চূড়ান্ত** ব্যর্থতা (একটি সত্যিকারের সংযোগ ব্যর্থতা — একটি টাইমআউট বা প্রোবের টার্গেটের নিজস্ব 5xx কখনই গণনা করা হয় না, [প্রক্সি হেলথ চেকিং](#proxy-health-checking-v3816) দেখুন), প্রক্সির `status` `dead` এ সেট করা হয়েছে।
3. `dead` হল pool/rotation রেজোলিউশন দ্বারা ব্যবহৃত লাইভ-স্ট্যাটাস ফিল্টার বাদ দেওয়া অবস্থাগুলির মধ্যে একটি, তাই একটি স্কোপের ঘূর্ণন (রাউন্ড-রবিন / র্যান্ডম / স্টিকি / লেটেন্সি — দেখুন [রোটেশন স্ট্র্যাটেজি ডিসিশন ট্রি](#rotation-strategy-decision-tree) ) অবিলম্বে সেই প্রক্সিটিকে নতুন অনুরোধে হস্তান্তর করা বন্ধ করে দেয়৷ পুলের অন্য কোন প্রক্সি প্রভাবিত হয় না, এবং পুরো পুলটি কখনই নিঃশব্দে সরাসরি সংযোগে ফিরে আসে না — [4-লেভেল প্রক্সি সিস্টেম](#4-level-proxy-system) ব্যর্থ-বন্ধ গার্ড দেখুন।
4. The scheduler keeps probing `dead` proxies on the same interval. The next successful probe flips `status` back to `active` and it re-enters rotation — no manual re-add required.

এটা ইচ্ছাকৃতভাবে** অপ্ট-ইন এবং অ-ধ্বংসাত্মক** : ডিফল্টরূপে সময়সূচী শুধুমাত্র ব্যর্থতা গণনা করে এবং লগ করে ( `decision.ts` তে নীতি C দেখুন), এবং `PROXY_AUTO_DISABLE` কখনই একটি সারি — মুছে দেয় না যার জন্য আলাদা, আরও আক্রমনাত্মক `PROXY_AUTO_REMOVE` পতাকা। যদি উভয়ই `true` তে সেট করা থাকে, `PROXY_AUTO_REMOVE` জিতবে (একটি প্রক্সি মুছে ফেলা হবে তার মধ্যে একটি সফ্ট-অক্ষম করার জন্য কোন ব্যবহার নেই)। সম্পূর্ণ পরিবর্তনশীল তালিকার জন্য [পরিবেশ কনফিগার](../reference/ENVIRONMENT.md) রেফারেন্স দেখুন।

---

> 📖** সম্পর্কিত ডকুমেন্টেশন:**
>
> - [ব্যবহারকারীর নির্দেশিকা](../guides/USER_GUIDE.md) — সাধারণ সেটআপ এবং কনফিগারেশন - [API রেফারেন্স](../reference/API_REFERENCE.md) — সম্পূর্ণ API ডকুমেন্টেশন - [এনভায়রনমেন্ট কনফিগার](../reference/ENVIRONMENT.md) — সমস্ত পরিবেশ ভেরিয়েবল
