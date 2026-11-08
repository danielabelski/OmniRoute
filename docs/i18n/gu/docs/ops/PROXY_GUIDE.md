# 🌐 OmniRoute Proxy Guide (ગુજરાતી)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **ભૌગોલિક બ્લોક્સને બાયપાસ કરો, તમારી ઓળખને સુરક્ષિત કરો અને શૂન્ય રૂપરેખાંકન જટિલતા સાથે કોઈપણ પ્રોક્સી — દ્વારા AI ટ્રાફિકને રૂટ કરો.**

OmniRoute માં સંપૂર્ણ સુવિધાયુક્ત પ્રોક્સી મેનેજમેન્ટ સિસ્ટમ શામેલ છે જે તમને અપસ્ટ્રીમ AI પ્રદાતા ટ્રાફિકને HTTP, HTTPS, અથવા SOCKS5 પ્રોક્સીઝ દ્વારા રૂટ કરવા દે છે. ભલે તમે અવરોધિત પ્રદેશમાં હોવ, IP પરિભ્રમણની જરૂર હોય, અથવા સ્ટીલ્થ ફિંગરપ્રિન્ટિંગ — આ માર્ગદર્શિકા બધું આવરી લે છે.

---

## સામગ્રીનું કોષ્ટક

- [શા માટે પ્રોક્સીઓનો ઉપયોગ કરવો?](#why-use-proxies)
- [આર્કિટેક્ચર ઝાંખી](#architecture-overview)
- [4-સ્તરની પ્રોક્સી સિસ્ટમ](#4-level-proxy-system)
- [પ્રોક્સી રજિસ્ટ્રી (CRUD)](#proxy-registry-crud)
- [1પ્રોક્સી ફ્રી માર્કેટપ્લેસ](#1proxy-free-proxy-marketplace)
- [પ્રોક્સી રોટેશન](#proxy-rotation)
- [એન્ટિ-ડિટેક્શન અને સ્ટીલ્થ](#anti-detection--stealth)
- [અપસ્ટ્રીમ પ્રોક્સી મોડ્સ](#upstream-proxy-modes)
- [ડેશબોર્ડ UI](#dashboard-ui)
- [API સંદર્ભ](#api-reference)
- [પર્યાવરણ ચલો](#environment-variables)
- [મુશ્કેલીનિવારણ](#troubleshooting)

---

## શા માટે પ્રોક્સીઓનો ઉપયોગ કરવો?

ઘણા AI પ્રદાતાઓ ભૌગોલિક પ્રદેશ દ્વારા ઍક્સેસને પ્રતિબંધિત કરે છે. માં વિકાસકર્તાઓ** રશિયા, ચીન, ઈરાન, ક્યુબા, તુર્કી** , અને અન્ય દેશોમાં ભૂલો આવે છે જેમ કે:

```
unsupported_country_region_territory
```

બહારના અવરોધિત પ્રદેશોમાં પણ, પ્રોક્સીઓ આ માટે ઉપયોગી છે:

| કેસનો ઉપયોગ કરો    | વર્ણન                                                          |
| ------------------ | -------------------------------------------------------------- |
| **ભૌગોલિક બાયપાસ** | અવરોધિત દેશોમાંથી OpenAI, Anthropic, Codex, Copilot ઍક્સેસ કરો |
| **IP પરિભ્રમણ**    | દર મર્યાદા ટાળવા માટે બહુવિધ IPs પર વિનંતીઓનું વિતરણ કરો       |
| **ગોપનીયતા**       | અપસ્ટ્રીમ પ્રદાતાઓથી તમારા વાસ્તવિક IP છુપાવો                  |
| **અનુપાલન**        | ચોક્કસ અધિકારક્ષેત્રો દ્વારા ટ્રાફિકને રૂટ કરો                 |
| **પરીક્ષણ**        | વિવિધ પ્રદેશોની વિનંતીઓનું અનુકરણ કરો                          |

---

## આર્કિટેક્ચર ઝાંખી

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

### મુખ્ય ઘટકો

| ઘટક                    | ફાઈલ                                         | ભૂમિકા                                                    |
| ---------------------- | -------------------------------------------- | --------------------------------------------------------- |
| **પ્રોક્સી રજિસ્ટ્રી** | `src/lib/db/proxies.ts`                      | પ્રોક્સી એન્ટ્રીઝ માટેCRUD + સ્કોપ અસાઇનમેન્ટ             |
| **પ્રોક્સી ડિસ્પેચર**  | `open-sse/utils/proxyDispatcher.ts`          | કેશીંગ સાથે `undici` ProxyAgent/SOCKS ડિસ્પેચર્સ બનાવે છે |
| **પ્રોક્સી આનયન**      | `open-sse/utils/proxyFetch.ts`               | પ્રોક્સી ડિસ્પેચર ઇન્જેક્શન સાથે `fetch()` લપેટી          |
| **સેટિંગ્સ રૂટ**       | `src/app/api/settings/proxy/route.ts`        | લેગસી પ્રોક્સી રૂપરેખા API (GET/PUT/DELETE)               |
| **મેનેજમેન્ટ રૂટ**     | `src/app/api/v1/management/proxies/route.ts` | રજિસ્ટ્રી CRUD API (GET/POST/PATCH/DELETE)                |
| **1 પ્રોક્સી DB**      | `src/lib/db/oneproxy.ts`                     | મફત પ્રોક્સી માર્કેટપ્લેસ દ્રઢતા                          |

---

## નવા એકાઉન્ટ્સ માટે ડિફોલ્ટ પ્રોક્સી સ્થિતિ

માં** સેટિંગ્સ → પ્રોક્સી → વૈશ્વિક ગોઠવણી** , ઉપયોગ કરો** નવા જોડાણો માટે ડિફૉલ્ટ રૂપે પ્રોક્સીને સક્ષમ કરો** નવા ઉમેરાયેલા પ્રદાતા એકાઉન્ટ્સની પ્રારંભિક પ્રોક્સી સ્થિતિ પસંદ કરવા માટે.

નવી સેટિંગ નવા ઉમેરાયેલા પ્રદાતા એકાઉન્ટ્સની પ્રારંભિક પ્રોક્સી સ્થિતિને નિયંત્રિત કરે છે. તે હાલના એકાઉન્ટ્સને બદલતું નથી અથવા વૈશ્વિક પ્રોક્સી સ્વિચને બદલતું નથી. તેનું પ્રારંભિક મૂલ્ય અગાઉના વર્તનને સાચવે છે. ડિફૉલ્ટ રૂપે અક્ષમ કરેલ પ્રોક્સી સાથે ભાવિ એકાઉન્ટ્સ બનાવવા માટે તેને એકવાર બંધ કરો.

પસંદગી હાલની સેટિંગ્સ API દ્વારા `defaultNewConnectionProxyEnabled` તરીકે સંગ્રહિત થાય છે. જ્યારે ક્યારેય સાચવવામાં ન આવે ત્યારે તે `true` પર ડિફોલ્ટ થાય છે. `false` સેવિંગ પુનઃપ્રારંભ કર્યા વિના અનુગામી નવા એકાઉન્ટ્સ માટે અસર કરે છે. `POST /api/providers` વૈકલ્પિક કડક બુલિયન `proxyEnabled` સ્વીકારે છે; સ્પષ્ટ `true` અથવા `false` સર્જન ડિફોલ્ટ પર અગ્રતા લે છે. ડુપ્લિકેટ એકાઉન્ટ અથવા OAuth રીકનેક્ટ પરની બાદબાકી તે એકાઉન્ટની સંગ્રહિત સ્થિતિને સાચવે છે. વ્યક્તિગત એકાઉન્ટ્સ પછીથી હજી પણ સક્ષમ અથવા અક્ષમ કરી શકાય છે.

પસંદગીયુક્ત પ્રદાતા ટ્રાન્સફર નવા એકાઉન્ટ્સ માટે ડેસ્ટિનેશન ઇન્સ્ટોલેશનના ડિફોલ્ટનો ઉપયોગ કરે છે અને હાલના એકાઉન્ટ્સને બદલતી વખતે ગંતવ્ય નીતિને સાચવે છે. પ્રોક્સી ટોગલ એ પોર્ટેબલ ટ્રાન્સફર ફીલ્ડ નથી. સંપૂર્ણ બેકઅપ પુનઃસ્થાપના અને ઐતિહાસિક JSON/SQL સ્થળાંતર તેમના હાલના પુનઃસ્થાપિત અર્થશાસ્ત્રને જાળવી રાખે છે, જેમાં સાચવેલ એકાઉન્ટ મૂલ્યો અને લેગસી સ્કીમા ડિફોલ્ટનો સમાવેશ થાય છે; સંપૂર્ણ સેટિંગ્સ પુનઃસ્થાપિત પણ આ પસંદગીને પુનઃસ્થાપિત કરી શકે છે.

આ પસંદગી પ્રોક્સીને સોંપતી નથી અથવા સ્થાપિત કરતી નથી કે તે સ્વસ્થ છે અથવા ઉપયોગમાં છે. વાસ્તવિક રૂટીંગ હજુ પણ વૈશ્વિક પ્રોક્સી સ્વિચ અને લાગુ પ્રોક્સી ગોઠવણી પર આધારિત છે. સતત ખાતા વિના સિન્થેટીક પ્રદાતાઓ, એકાઉન્ટ બનાવતા પહેલા OAuth ટ્રાફિક, environment/system પ્રોક્સીઓ અને બાહ્ય બેકએન્ડ્સનું નેટવર્કિંગ તેના અવકાશની બહાર છે.

## 4-સ્તરની પ્રોક્સી સિસ્ટમ

OmniRoute પર પ્રોક્સી રૂપરેખાંકનને સપોર્ટ કરે છે** ચાર સ્વતંત્ર અવકાશ** , અગ્રતા ક્રમમાં ઉકેલાઈ:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### રિઝોલ્યુશન કેવી રીતે કામ કરે છે

જ્યારે OmniRoute અપસ્ટ્રીમ પ્રદાતાને વિનંતી મોકલે છે, ત્યારે તે `resolveProxyForConnectionFromRegistry()` કૉલ કરે છે જે દરેક સ્તરને ક્રમમાં તપાસે છે:

1. **એકાઉન્ટ લેવલ** — શું આ ચોક્કસ કનેક્શન ID ને કોઈ પ્રોક્સી સોંપવામાં આવી છે?
2. **પ્રદાતા-સ્તર** — શું આ પ્રદાતાને કોઈ પ્રોક્સી સોંપવામાં આવી છે (દા.ત., `openai`)?
3. **વૈશ્વિક સ્તરે** — શું ત્યાં વૈશ્વિક પ્રોક્સી ગોઠવેલ છે?
4. **કોઈ પ્રોક્સી નથી** — પ્રદાતા સાથે સીધું જોડાણ.

પ્રથમ મેચ જીતે છે. આનો અર્થ એ છે કે તમે વૈશ્વિક પ્રોક્સીને ફોલબેક તરીકે સેટ કરી શકો છો પરંતુ ચોક્કસ પ્રદાતાઓ અથવા કનેક્શન્સ માટે તેને ઓવરરાઇડ કરી શકો છો.

### શું પ્રોક્સી થાય છે

| ટ્રાફિકનો પ્રકાર     | પ્રોક્સી? | નોંધો                                           |
| -------------------- | --------- | ----------------------------------------------- |
| ચેટ પૂર્ણતા          | ✅        | તમામ `/v1/chat/completions` વિનંતીઓ             |
| એમ્બેડિંગ્સ          | ✅        | `/v1/embeddings`                                |
| છબી જનરેશન           | ✅        | `/v1/images/generations`                        |
| ઓડિયો (TTS/STT)      | ✅        | `/v1/audio/*`                                   |
| OAuth ટોકન એક્સચેન્જ | ✅        | `unsupported_country_region_territory` ઉકેલે છે |
| કનેક્શન પરીક્ષણો     | ✅        | "ટેસ્ટ કનેક્શન" બટન પ્રોક્સીનો ઉપયોગ કરે છે     |
| ટોકન રિફ્રેશ         | ✅        | પૃષ્ઠભૂમિ OAuth નવીકરણ                          |
| મોડલ સમન્વયન         | ✅        | મોડેલ સૂચિ અને શોધ                              |

---

## પ્રોક્સી રજિસ્ટ્રી (CRUD)

પ્રોક્સી રજિસ્ટ્રી એ SQLite ટેબલ (`proxy_registry`) છે જે તમારી બધી પ્રોક્સીને સંગ્રહિત કરે છે. દરેક પ્રોક્સીમાં છે:

| ક્ષેત્ર    | પ્રકાર   | વર્ણન                                           |
| ---------- | -------- | ----------------------------------------------- |
| `id`       | UUID     | અનન્ય ઓળખકર્તા                                  |
| `name`     | શબ્દમાળા | માનવ વાંચી શકાય તેવું લેબલ                      |
| `type`     | શબ્દમાળા | પ્રોટોકોલ: `http`, `https`, `socks5`            |
| `host`     | શબ્દમાળા | પ્રોક્સી હોસ્ટનામ અથવા IP                       |
| `port`     | પૂર્ણાંક | પોર્ટ નંબર                                      |
| `username` | શબ્દમાળા | પ્રમાણીકરણ વપરાશકર્તાનામ (બાકીમાં એન્ક્રિપ્ટેડ) |
| `password` | શબ્દમાળા | પ્રમાણીકરણ પાસવર્ડ (બાકીમાં એન્ક્રિપ્ટેડ)       |
| `region`   | શબ્દમાળા | ભૌગોલિક પ્રદેશ લેબલ                             |
| `notes`    | શબ્દમાળા | મફત-ટેક્સ્ટ નોંધો                               |
| `status`   | શબ્દમાળા | `active` અથવા `inactive`                        |
| `source`   | શબ્દમાળા | `manual` અથવા `oneproxy`                        |

### પ્રોક્સી બનાવવી

**ડેશબોર્ડ દ્વારા:**

1. પર જાઓ** સેટિંગ્સ → પ્રોક્સી**
2. ક્લિક કરો** પ્રોક્સી ઉમેરો**
3. પ્રકાર, હોસ્ટ, પોર્ટ અને વૈકલ્પિક ઓથ પ્રમાણપત્રો ભરો
4. સાચવો

**API દ્વારા:**

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

### પ્રોક્સીને અપડેટ કરી રહ્યાં છીએ

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **નોંધ:** જ્યાં સુધી તમે સ્પષ્ટપણે બિન-ખાલી રિપ્લેસમેન્ટ મોકલો નહીં ત્યાં સુધી ઓળખપત્રો સાચવવામાં આવે છે. `username`/`password` માટે ખાલી સ્ટ્રિંગ્સ મોકલવાથી સંગ્રહિત મૂલ્યો જળવાઈ રહેશે.

### પ્રોક્સી કાઢી નાખી રહ્યું છે

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### લિસ્ટિંગ પ્રોક્સીઓ

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### સ્કોપ્સ માટે પ્રોક્સીઓ સોંપી રહ્યા છીએ

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

### અસરકારક પ્રોક્સીનું નિરાકરણ

આપેલ કનેક્શન માટે કઈ પ્રોક્સીનો ઉપયોગ કરવામાં આવશે તે તપાસો:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

ઉકેલાયેલ પ્રોક્સીને તેના સ્તર (`account`, `provider`, અથવા `global`) અને સ્ત્રોત સાથે પરત કરે છે.

### બલ્ક અસાઇનમેન્ટ

એક સાથે બહુવિધ પ્રદાતાઓ અથવા જોડાણોને એક પ્રોક્સી સોંપો:

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

પ્રોક્સીઓનો સમાવેશ થાય છે**Backup/Restore** સિસ્ટમ જ્યારે તમે તમારી OmniRoute ગોઠવણીની નિકાસ કરો છો:

1. પર જાઓ** ડેશબોર્ડ → સેટિંગ્સ → બેકઅપ**
2. ક્લિક કરો** નિકાસ કરો** — પ્રોક્સી રજિસ્ટ્રી અને સોંપણીઓ શામેલ છે
3. પુનઃસ્થાપિત કરવા માટે, ક્લિક કરો** આયાત કરો** અને બેકઅપ ફાઈલ અપલોડ કરો

પ્રોક્સી રજિસ્ટ્રી પણ સપોર્ટ કરે છે** યજમાન + પોર્ટ દ્વારા upsert** — જો તમે પ્રોક્સી આયાત કરો છો જે પહેલાથી અસ્તિત્વમાં છે (સમાન હોસ્ટ અને પોર્ટ), તો તે ડુપ્લિકેટ બનાવવાને બદલે અપડેટ થાય છે.

### વારસો સ્થળાંતર

જો તમે પ્રોક્સીઝને જૂના સંસ્કરણ (પ્રી-રજિસ્ટ્રી)માં ગોઠવી હોય, તો OmniRoute તેમને આપમેળે સ્થાનાંતરિત કરે છે:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

આ અપગ્રેડ પછી પ્રથમ સ્ટાર્ટઅપ પર એકવાર થાય છે. ફરીથી ચલાવવા માટે `migrateLegacyProxyConfigToRegistry({ force: true })` ઉપયોગ કરો.

---

## 1પ્રોક્સી ફ્રી પ્રોક્સી માર્કેટપ્લેસ

> 🆕** [@oyi77](https://github.com/oyi77) દ્વારા યોગદાન આપ્યું** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) ( અંક [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute સાથે સાંકળે છે** [1 પ્રોક્સી](https://1proxy-api.aitradepulse.com)** ઍક્સેસ પ્રદાન કરવા માટે સમુદાય પ્લેટફોર્મ** સેંકડો મફત, માન્ય પ્રોક્સીઓ** વિશ્વભરમાંથી. આ એવા વપરાશકર્તાઓ માટે યોગ્ય છે કે જેમની પાસે પોતાનું પ્રોક્સી ઈન્ફ્રાસ્ટ્રક્ચર નથી.

### તે કેવી રીતે કામ કરે છે

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **સમન્વય** — OmniRoute 1proxy API માંથી માન્ય પ્રોક્સી મેળવે છે
2. **સ્ટોર** — પ્રોક્સીઝ એ જ `proxy_registry` કોષ્ટકમાં `source = 'oneproxy'` સાથે સાચવવામાં આવે છે
3. **ફિલ્ટર કરો** પ્રોટોકોલ, દેશ, ગુણવત્તા સ્કોર દ્વારા — ફિલ્ટર કરો
4. **ફેરવો** — ગુણવત્તા, રેન્ડમ અથવા ક્રમિક વ્યૂહરચનાઓનો ઉપયોગ કરીને શ્રેષ્ઠ પ્રોક્સી પસંદ કરો
5. **ઓટો-ડિગ્રેડ** — નિષ્ફળ પ્રોક્સીઓ તેમના ગુણવત્તા સ્કોર ઘટાડે છે; થ્રેશોલ્ડ નીચે → નિષ્ક્રિય તરીકે ચિહ્નિત થયેલ છે

### સમન્વયિત પ્રોક્સીઓ

**ડેશબોર્ડ દ્વારા:**

1. પર જાઓ** સેટિંગ્સ → 1proxy** ટેબ
2. ક્લિક કરો** "હવે સમન્વય કરો"**
3. આંકડા જુઓ: કુલ પ્રોક્સી, સક્રિય સંખ્યા, સરેરાશ ગુણવત્તા, દેશ દ્વારા વિભાજન

**API દ્વારા:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### ફિલ્ટરિંગ પ્રોક્સીઓ

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

### પ્રોક્સી ગુણવત્તા સ્કોર્સ

દરેક 1 પ્રોક્સી પ્રોક્સી મેટાડેટા સાથે આવે છે:

| ક્ષેત્ર         | વર્ણન                                        |
| --------------- | -------------------------------------------- |
| `qualityScore`  | 1પ્રોક્સી માન્યતાથી 0-100 રેટિંગ             |
| `latencyMs`     | માપેલ નેટવર્ક લેટન્સી                        |
| `anonymity`     | `transparent`, `anonymous`, અથવા `elite`     |
| `googleAccess`  | શું પ્રોક્સી Google સેવાઓનો ઉપયોગ કરી શકે છે |
| `countryCode`   | બે અક્ષરનો ISO દેશનો કોડ                     |
| `lastValidated` | છેલ્લી માન્યતાનો ટાઇમસ્ટેમ્પ                 |

ગુણવત્તા સ્કોર્સ ગતિશીલ રીતે ગોઠવવામાં આવે છે:

- **નિષ્ફળ વિનંતીઓ** 10 પોઈન્ટ દ્વારા સ્કોર ઘટાડો
- **સ્કોર ઘટીને ≤ 10 થયો** → પ્રોક્સી `inactive` તરીકે ચિહ્નિત થયેલ છે
- નિષ્ક્રિય પ્રોક્સીને પરિભ્રમણમાંથી બાકાત રાખવામાં આવે છે

### પરિભ્રમણ વ્યૂહરચના

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

### સર્કિટ બ્રેકર

1પ્રોક્સી સિંકમાં બિલ્ટ-ઇન સર્કિટ બ્રેકર છે:

- પછી** 5 સળંગ સમન્વયન નિષ્ફળતાઓ** , વધુ સમન્વયન પ્રયાસો અવરોધિત છે
- સાથે રીસેટ કરો: `resetOneproxyCircuitBreaker()` અથવા સર્વર પુનઃપ્રારંભ કરો
- સિંક સ્ટેટસ `GET /api/settings/oneproxy?action=status` પર ઉપલબ્ધ છે

### 1પ્રોક્સી પ્રોક્સીને સાફ કરી રહ્યાં છીએ

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## એન્ટિ-ડિટેક્શન અને સ્ટીલ્થ

OmniRoute માત્ર પ્રોક્સી — દ્વારા ટ્રાફિકને રૂટ કરતું નથી તે ટ્રાફિકને કાયદેસર બનાવે છે:

### TLS ફિંગરપ્રિન્ટ સ્પૂફિંગ

બ્રાઉઝર-જેવી TLS ફિંગરપ્રિન્ટ્સ જનરેટ કરવા માટે `wreq-js` ઉપયોગ કરે છે, બોટ ડિટેક્શન સિસ્ટમ્સને બાયપાસ કરીને જે બિન-બ્રાઉઝર TLS હેન્ડશેકને ફ્લેગ કરે છે.

### CLI ફિંગરપ્રિન્ટ મેચિંગ

આ**CLI ફિંગરપ્રિન્ટ ટૉગલ** (`Settings → Security`) મૂળ CLI દ્વિસંગીઓ (Claude કોડ, Codex, વગેરે) ની ચોક્કસ સહી સાથે મેચ કરવા માટે HTTP હેડરો અને JSON બોડી ફીલ્ડને ફરીથી ગોઠવે છે. આ કામ કરે છે** ની ટોચ પર** પ્રોક્સી

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

તમે બંને મેળવો**IP માસ્કીંગ** અને** અધિકૃતતા માટે વિનંતી કરો** સાથે સાથે

### પ્રોક્સી IP જાળવણી

ડેશબોર્ડમાં કલર-કોડેડ બેજેસ બતાવે છે કે કયું પ્રોક્સી સ્તર સક્રિય છે:

| બેજ | સ્તર    | અર્થ                                            |
| --- | ------- | ----------------------------------------------- |
| 🟢  | વૈશ્વિક | તમામ ટ્રાફિક આ પ્રોક્સીમાંથી પસાર થાય છે        |
| 🟡  | પ્રદાતા | માત્ર આ પ્રદાતાનો ટ્રાફિક પ્રોક્સી છે           |
| 🔵  | જોડાણ   | આ વિશિષ્ટ key/account આ પ્રોક્સીનો ઉપયોગ કરે છે |

બેજ ચકાસણી માટે ઉકેલાયેલ પ્રોક્સી IP પણ દર્શાવે છે.

---

## અપસ્ટ્રીમ પ્રોક્સી મોડ્સ

CLIProxyAPI પેટર્નનો ઉપયોગ કરતા પ્રદાતાઓ માટે, OmniRoute ત્રણ અપસ્ટ્રીમ પ્રોક્સી મોડને સપોર્ટ કરે છે:

| મોડ           | વર્ણન                                                    |
| ------------- | -------------------------------------------------------- |
| `native`      | OmniRoute સીધા પ્રોક્સી રૂટીંગને હેન્ડલ કરે છે (ડિફોલ્ટ) |
| `cliproxyapi` | બાહ્ય CLIProxyAPI ઉદાહરણ માટે પ્રતિનિધિઓ                 |
| `fallback`    | પ્રથમ મૂળ પ્રયાસ કરે છે, CLIProxyAPI પર પાછા આવે છે      |

પ્રદાતા દીઠ ગોઠવો:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## ડેશબોર્ડ UI

### સેટિંગ્સ → પ્રોક્સી ટેબ

- **વૈશ્વિક પ્રોક્સી** ગોઠવણી (બધા ટ્રાફિક માટે એકવાર સેટ કરો)
- **પ્રતિ-પ્રદાતા પ્રોક્સી** ઓવરરાઇડ કરે છે
- **પ્રતિ-કનેક્શન પ્રોક્સી** સોંપણીઓ
- **કનેક્શન ટેસ્ટ** રૂપરેખાંકિત પ્રોક્સી દ્વારા
- **રંગ-કોડેડ બેજ** સક્રિય પ્રોક્સી સ્તર દર્શાવે છે

### સેટિંગ્સ → 1પ્રોક્સી ટેબ

- **હવે સમન્વય કરો** મફત પ્રોક્સી મેળવવા માટે બટન
- **આંકડા કાર્ડ** : કુલ, સક્રિય, સરેરાશ ગુણવત્તા, છેલ્લું સમન્વયન
- **ફિલ્ટર્સ** : પ્રોટોકોલ, દેશનો કોડ, ન્યૂનતમ ગુણવત્તા
- **પ્રોક્સી ટેબલ** યજમાન, પ્રોટોકોલ, દેશ, ગુણવત્તા સ્કોર, લેટન્સી, અનામી, Google એક્સેસ સાથે
- **સમન્વયન સ્થિતિ** success/failure ટ્રેકિંગ અને સળંગ નિષ્ફળતાની ગણતરી સાથેની પેનલ
- **બધા સાફ કરો** બધી 1 પ્રોક્સી એન્ટ્રીઓ દૂર કરવા માટે

---

## API સંદર્ભ

### પ્રોક્સી સેટિંગ્સ API

| પદ્ધતિ   | અંતિમ બિંદુ                                    | વર્ણન                          |
| -------- | ---------------------------------------------- | ------------------------------ |
| `GET`    | `/api/settings/proxy`                          | સંપૂર્ણ પ્રોક્સી રૂપરેખા મેળવો |
| `GET`    | `/api/settings/proxy?level=global`             | વૈશ્વિક પ્રોક્સી મેળવો         |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | પ્રદાતા પ્રોક્સી મેળવો         |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | અસરકારક પ્રોક્સી ઉકેલો         |
| `PUT`    | `/api/settings/proxy`                          | પ્રોક્સી રૂપરેખા અપડેટ કરો     |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | સ્તર પર પ્રોક્સી દૂર કરો       |

### પ્રોક્સી રજિસ્ટ્રી API

| પદ્ધતિ   | અંતિમ બિંદુ                                       | વર્ણન                      |
| -------- | ------------------------------------------------- | -------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | તમામ પ્રોક્સીની યાદી બનાવો |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID દ્વારા પ્રોક્સી મેળવો   |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | પ્રોક્સી સોંપણીઓ મેળવો     |
| `POST`   | `/api/v1/management/proxies`                      | પ્રોક્સી બનાવો             |
| `PATCH`  | `/api/v1/management/proxies`                      | પ્રોક્સી અપડેટ કરો         |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | પ્રોક્સી કાઢી નાખો         |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | કાઢી નાખવા દબાણ કરો        |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | જથ્થાબંધ સોંપણી            |
| `GET`    | `/api/v1/management/proxies/assignments`          | સોંપણીઓની સૂચિ બનાવો       |
| `GET`    | `/api/v1/management/proxies/health`               | પ્રોક્સી આરોગ્ય આંકડા      |

### ટનલ API

પ્રોક્સી દ્વારા આઉટબાઉન્ડને રૂટ કરવાને બદલે તમારા OmniRoute ઇન્સ્ટન્સને સાર્વજનિક ઇન્ટરનેટ (Cloudflare/ngrok/Tailscale) પર એક્સપોઝ કરવા માટે, [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) જુઓ. ટનલ REST API `/api/tunnels/{cloudflared,ngrok,tailscale}/*` હેઠળ રહે છે અને ઉપર દસ્તાવેજીકૃત આઉટબાઉન્ડ પ્રોક્સી ચેઇન માટે ઓર્થોગોનલ છે.

### 1 પ્રોક્સી API

| પદ્ધતિ   | અંતિમ બિંદુ                            | વર્ણન                            |
| -------- | -------------------------------------- | -------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | 1 પ્રોક્સી પ્રોક્સીની સૂચિ બનાવો |
| `GET`    | `/api/settings/oneproxy?action=stats`  | આંકડા + સમન્વયન સ્થિતિ મેળવો     |
| `GET`    | `/api/settings/oneproxy?action=status` | માત્ર સમન્વયન સ્થિતિ મેળવો       |
| `POST`   | `/api/settings/oneproxy`               | ટ્રિગર સિંક                      |
| `POST`   | `/api/settings/oneproxy/rotate`        | આગામી પ્રોક્સી પર ફેરવો          |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | એક કાઢી નાખો                     |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | બધું સાફ કરો                     |

### અપસ્ટ્રીમ પ્રોક્સી API

| પદ્ધતિ   | અંતિમ બિંદુ                       | વર્ણન                                |
| -------- | --------------------------------- | ------------------------------------ |
| `GET`    | `/api/upstream-proxy/:providerId` | અપસ્ટ્રીમ પ્રોક્સી રૂપરેખા મેળવો     |
| `PUT`    | `/api/upstream-proxy/:providerId` | અપસ્ટ્રીમ પ્રોક્સી મોડ સેટ કરો       |
| `DELETE` | `/api/upstream-proxy/:providerId` | અપસ્ટ્રીમ પ્રોક્સી રૂપરેખાને દૂર કરો |

---

## પર્યાવરણ ચલો

| ચલ                    | ડિફૉલ્ટ | વર્ણન                                                                  |
| --------------------- | ------- | ---------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`  | SOCKS5 પ્રોક્સી સપોર્ટ સક્ષમ કરો ( `.env.example` માં ડિફોલ્ટ `true` ) |

---

## મુશ્કેલીનિવારણ

### "SOCKS5 પ્રોક્સી અક્ષમ છે"

તમારી `.env` ફાઇલમાં `ENABLE_SOCKS5_PROXY=true` સેટ કરો અને પુનઃપ્રારંભ કરો.

### પ્રોક્સી દ્વારા "સોકેટ હેંગ અપ" ભૂલો

નિષ્ક્રિય કનેક્શન છોડતા સસ્તા પ્રોક્સીઓ સાથે આ સામાન્ય છે. OmniRoute પહેલેથી જ આને આના દ્વારા સંભાળે છે:

- પ્રોક્સી કનેક્શન્સ પર જીવંત રાખવાને અક્ષમ કરી રહ્યું છે (`keepAliveTimeout: 1`)
- પાઇપલાઇનિંગને અક્ષમ કરી રહ્યું છે (`pipelining: 0`)
- પુનરાવર્તિત હેન્ડશેક ટાળવા માટે ડિસ્પેચર્સને કેશ કરવું

જો તે ચાલુ રહે, તો અલગ પ્રોક્સી અજમાવો અથવા 1પ્રોક્સી રોટેશન સુવિધાનો ઉપયોગ કરો.

### OAuth દરમિયાન "unsupported_country_region_territory"

ખાતરી કરો કે પ્રોક્સી ગોઠવેલ છે** પહેલાં** OAuth પ્રવાહ શરૂ કરી રહ્યા છીએ. OmniRoute રૂટ્સ OAuth ટોકન એક્સચેન્જ રૂપરેખાંકિત પ્રોક્સી દ્વારા. પહેલા વૈશ્વિક અથવા પ્રદાતા-સ્તરની પ્રોક્સી સેટ કરો, પછી કનેક્ટ કરો.

### પ્રોક્સીનો ઉપયોગ થતો નથી

રિઝોલ્યુશન ઓર્ડર તપાસો:

1. `GET /api/settings/proxy?resolve=your-connection-id` સાથે ચકાસો
2. તપાસો કે પ્રોક્સી `status` `active` છે ( `inactive` નથી)
3. ખાતરી કરો કે પ્રોક્સી અસાઇનમેન્ટ સ્કોપ તમારા કનેક્શન સાથે મેળ ખાય છે

### 1પ્રોક્સી સમન્વયન નિષ્ફળ

સમન્વયન સ્થિતિ તપાસો:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

જો `consecutiveFailures >= 5`, સર્કિટ બ્રેકર ટ્રીપ થઈ ગયું છે. રીસેટ કરવા માટે સર્વરને રીસ્ટાર્ટ કરો અથવા મેન્યુઅલ રીસેટની રાહ જુઓ.

---

## ડેટાબેઝ સ્કીમા

### `proxy_registry` ટેબલ

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

### `proxy_assignments` ટેબલ

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

## પ્રોક્સી હેલ્થ ચેકિંગ (v3.8.16 +)

OmniRoute's** પ્રોક્સી ફાસ્ટ-ફેલ** મિકેનિઝમ (`src/lib/proxyHealth.ts`) ઝડપી TCP કનેક્શન ચેક દ્વારા < 2s માં મૃત પ્રોક્સીઓ શોધે છે, પછી** પરિણામને કેશ કરે છે** ઓવરહેડ દીઠ વિનંતી ટાળવા માટે.

### તે કેવી રીતે કામ કરે છે

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

આ વિના, મૃત પ્રોક્સી નિષ્ફળ થતાં પહેલાં સંપૂર્ણ `PROXY_TIMEOUT_MS` (ડિફોલ્ટ 30s) માટેની દરેક વિનંતીને અવરોધિત કરશે.

### ટ્યુનેબલ એન્વાયર્નમેન્ટ વેરીએબલ્સ

| ચલ                           | ડિફૉલ્ટ | હેતુ                                    |
| ---------------------------- | ------- | --------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | આરોગ્ય તપાસ દીઠ TCP કનેક્શન સમયસમાપ્તિ  |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | આરોગ્ય પરિણામ કેટલા સમય સુધી કેશ થાય છે |

**ભલામણ કરેલ મૂલ્યો:**

| દૃશ્ય                    | ઝડપી-નિષ્ફળ સમયસમાપ્તિ | કેશ TTL | તર્ક                                                         |
| ------------------------ | ---------------------- | ------- | ------------------------------------------------------------ |
| ઉચ્ચ થ્રુપુટ API ગેટવે   | 1500ms                 | 60000ms | ચેક ઘટાડવા માટે આક્રમક નિષ્ફળ-ઝડપી, લાંબી કેશ                |
| જીઓ-વિતરિત ગાંઠો         | 3000ms                 | 15000ms | ધીમા નેટવર્કને વધુ સમયની જરૂર છે; ઝડપી ફેલઓવર માટે ટૂંકી કેશ |
| દેવ / પરીક્ષણ            | 1000ms                 | 10000ms | સ્થાનિક પ્રોક્સીઓ પર ઝડપી પુનરાવર્તન                         |
| સ્ટીલ્થ / એન્ટી ડિટેક્શન | 2500ms                 | 45000ms | ઝડપી તપાસ ટાળો જે દર મર્યાદાને ટ્રિગર કરી શકે                |

### પ્રોક્સી આરોગ્ય તપાસી રહ્યું છે

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

જ્યારે કેશ એન્ટ્રી `HEALTH_CACHE_TTL_MS` વટાવી ગઈ હોય ત્યારે `stale` ફ્લેગ `true` છે અને આગળની વિનંતી નવી તપાસને ટ્રિગર કરશે.

### પ્રતિ-પ્રોક્સી પ્રકાર ડિફોલ્ટ્સ

આરોગ્ય તપાસ URL યોજનાના આધારે સમજદાર ડિફોલ્ટનો ઉપયોગ કરે છે:

| સ્કીમ                      | ડિફૉલ્ટ પોર્ટ |
| -------------------------- | ------------- |
| `http://`                  | 8080          |
| `https://`                 | 443           |
| `socks5://` / `socks5h://` | 1080          |

URL (`http://host:9999`) માં કસ્ટમ પોર્ટ હંમેશા સ્કીમ ડિફોલ્ટ પર અગ્રતા મેળવે છે.

---

## પ્રોક્સી એનાલિટિક્સ અને અવલોકનક્ષમતા

ઓપરેટરોને રૂટીંગ પેટર્ન, લેટન્સી સ્પાઇક્સ અને રિકરિંગ નિષ્ફળતાઓનું નિદાન કરવામાં મદદ કરવા માટેOmniRoute પ્રતિ-પ્રોક્સી વપરાશને ટ્રેક કરે છે.

### શું ટ્રૅક કર્યું છે

રૂપરેખાંકિત પ્રોક્સી દ્વારા દરેક વિનંતી માટે, OmniRoute રેકોર્ડ કરે છે:

| મેટ્રિક      | વર્ણન                                              |
| ------------ | -------------------------------------------------- |
| `proxy_url`  | સંપૂર્ણ પ્રોક્સી URL (માસ્ક કરેલ પ્રમાણપત્રો સાથે) |
| `provider`   | અપસ્ટ્રીમ પ્રદાતા ID (ઓપનાઈ, એન્થ્રોપિક, વગેરે)    |
| `latency_ms` | પ્રોક્સી હેન્ડશેક સહિત કુલ રાઉન્ડ-ટ્રીપ સમય        |
| `connect_ms` | TCP કનેક્ટ સમય જ                                   |
| `status`     | અપસ્ટ્રીમથીHTTP સ્ટેટસ કોડ                         |
| `error`      | જો વિનંતી નિષ્ફળ થઈ તો ભૂલ વર્ગ                    |
| `timestamp`  | ISO 8601 UTC                                       |

### ડેટા એક્સેસ કરી રહ્યા છીએ

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

વાસ્તવિક અંતિમ બિંદુ `/api/usage/proxy-logs` છે (જુઓ `src/app/api/usage/proxy-logs/route.ts`). આ અંતિમ બિંદુ આધાર આપે છે:

- `GET /api/usage/proxy-logs` — પ્રોક્સી લોગ પુનઃપ્રાપ્ત કરો
- `DELETE /api/usage/proxy-logs` — બધા પ્રોક્સી લોગ સાફ કરો

જો જરૂરી હોય તો SQL મારફત `proxy_logs` ટેબલમાંથી સીધા જ એકંદર આંકડાની પૂછપરછ કરી શકાય છે. ડેશબોર્ડ UI એકંદર દૃશ્યો પ્રદાન કરી શકે છે.

### સામાન્ય દાખલાઓ

**ફ્લૅપિંગ પ્રોક્સી શોધો** ( success/failure વચ્ચેના વિકલ્પો):

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

**ધીમી પ્રોક્સીઓ શોધો** (p95 લેટન્સી > 2s):

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

## પરિભ્રમણ વ્યૂહરચના નિર્ણય વૃક્ષ

જ્યારે બહુવિધ પ્રોક્સીઓ એક અવકાશને સોંપવામાં આવે છે, ત્યારે OmniRoute a નો ઉપયોગ કરે છે** પરિભ્રમણ વ્યૂહરચના** દરેક વિનંતી માટે કયો ઉપયોગ કરવો તે પસંદ કરવા માટે. વ્યૂહરચના સ્કોપ લેવલ પર ગોઠવવામાં આવી છે (વૈશ્વિક, પ્રતિ-પ્રદાતા, પ્રતિ-એકાઉન્ટ, પ્રતિ-કોમ્બો).

### ઉપલબ્ધ વ્યૂહરચના

| વ્યૂહરચના          | ક્યારે વાપરવું                          | વેપાર બંધ                                                            |
| ------------------ | --------------------------------------- | -------------------------------------------------------------------- |
| `quality` (મૂળભૂત) | મિશ્ર-ગુણવત્તાની પ્રોક્સીઓ સાથે ઉત્પાદન | ઉચ્ચ-રેટેડ પ્રોક્સીની તરફેણ કરે છે; નીચા રેટિંગવાળાઓ ભૂખે મરી શકે છે |
| `random`           | લોડ વિતરણ, ગોપનીયતા                     | સમાન વિતરણ; ગુણવત્તા સંકેતોને અવગણે છે                               |
| `sequential`       | ડિબગીંગ, નિર્ધારિત પરીક્ષણ              | ક્રમમાં પ્રોક્સીઓ દ્વારા ચક્ર; તર્ક કરવા માટે સરળ                    |

### નિર્ણય વૃક્ષ

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

## તમારા પોતાના પ્રોક્સીઓ માટે આપોઆપ નિષ્ફળતા બાકાત

1પ્રોક્સી માર્કેટપ્લેસ પૂલ પહેલાથી જ નિષ્ફળ પ્રોક્સીઓને તેની જાતે ઓટો-ડિગ્રેડ કરે છે ( [પ્રોક્સી ગુણવત્તા સ્કોર્સ](#proxy-quality-scores) જુઓ). પ્રોક્સીઓ માટે** તમે** રજિસ્ટ્રીમાં ઉમેરવામાં આવ્યું છે, બેકગ્રાઉન્ડ હેલ્થ શેડ્યૂલર (`src/lib/proxyHealth/scheduler.ts`) કંઈપણ કાઢી નાખ્યા વિના, "આપમેળે મૃત સભ્યને સાંકળમાંથી બાકાત કરો" વર્તન પ્રદાન કરે છે:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

તે મલ્ટી-પ્રોક્સી સાંકળમાં કેવી રીતે બંધબેસે છે:

1. શેડ્યૂલર દરેક રજિસ્ટર્ડ પ્રોક્સીની દરેક `PROXY_HEALTH_INTERVAL_MS` (ડિફૉલ્ટ 10 મિનિટ; ન્યૂનતમ 1 મિનિટ) પર તપાસ કરે છે.
2. `PROXY_AUTO_REMOVE_AFTER` પછી સતત** નિર્ણાયક** નિષ્ફળતાઓ (એક વાસ્તવિક જોડાણ નિષ્ફળતા — સમયસમાપ્તિ અથવા ચકાસણી લક્ષ્યનું પોતાનું 5xx ક્યારેય ગણાતું નથી, [પ્રોક્સી હેલ્થ ચેકિંગ](#proxy-health-checking-v3816) જુઓ), પ્રોક્સીનું `status` એ `dead` પર સેટ છે.
3. `dead` એ pool/rotation રિઝોલ્યુશન દ્વારા ઉપયોગમાં લેવાતા લાઇવ-સ્ટેટસ ફિલ્ટરમાંથી એક સ્ટેટસ છે, તેથી સ્કોપનું પરિભ્રમણ (રાઉન્ડ-રોબિન / રેન્ડમ / સ્ટીકી / લેટન્સી — જુઓ [રોટેશન સ્ટ્રેટેજી ડિસિઝન ટ્રી](#rotation-strategy-decision-tree) ) તરત જ તે પ્રોક્સીને નવી વિનંતીઓને સોંપવાનું બંધ કરે છે. પૂલમાં અન્ય કોઈ પ્રોક્સીને અસર થતી નથી, અને આખો પૂલ ક્યારેય ચુપચાપ ડાયરેક્ટ કનેક્શન — પર પાછો પડતો નથી, [4-લેવલ પ્રોક્સી સિસ્ટમ](#4-level-proxy-system) ફેલ-ક્લોઝ્ડ ગાર્ડ જુઓ.
4. શેડ્યૂલર સમાન અંતરાલ પર `dead` પ્રોક્સીઝની તપાસ કરતું રહે છે. આગળની સફળ ચકાસણી `status` `active` પર પાછી ફેરવે છે અને તે પરિભ્રમણ — પુનઃપ્રવેશ કરે છે કોઈ મેન્યુઅલ રી-એડ જરૂરી નથી.

આ જાણી જોઈને છે** પસંદ કરો અને બિન-વિનાશક** : ડિફૉલ્ટ રૂપે શેડ્યૂલર માત્ર નિષ્ફળતાઓની ગણતરી કરે છે અને લૉગ કરે છે ( `decision.ts` માં નીતિ C જુઓ), અને `PROXY_AUTO_DISABLE` ક્યારેય — પંક્તિને કાઢી નાખતું નથી જે અલગ, વધુ આક્રમક `PROXY_AUTO_REMOVE` ફ્લેગ માટે છે. જો બંને `true` પર સેટ કરેલ હોય, તો `PROXY_AUTO_REMOVE` જીતે છે (જે પ્રોક્સી કાઢી નાખવાની છે તેની વચ્ચે સોફ્ટ-અક્ષમ કરવાનો કોઈ ઉપયોગ નથી). સંપૂર્ણ ચલ સૂચિ માટે [પર્યાવરણ રૂપરેખા](../reference/ENVIRONMENT.md) સંદર્ભ જુઓ.

---

> 📖** સંબંધિત દસ્તાવેજો:**
>
> - [વપરાશકર્તા માર્ગદર્શિકા](../guides/USER_GUIDE.md) — સામાન્ય સેટઅપ અને રૂપરેખાંકન - [API સંદર્ભ](../reference/API_REFERENCE.md) — સંપૂર્ણ API દસ્તાવેજીકરણ - [પર્યાવરણ રૂપરેખા](../reference/ENVIRONMENT.md) — બધા પર્યાવરણ ચલો
