# 🌐 OmniRoute Proxy Guide (ไทย)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **หลีกเลี่ยงการบล็อกทางภูมิศาสตร์ ปกป้องตัวตนของคุณ และกำหนดเส้นทางการรับส่งข้อมูล AI ผ่านพร็อกซี — ใด ๆ ที่ไม่ซับซ้อนในการกำหนดค่า**

OmniRoute มีระบบการจัดการพร็อกซีที่มีคุณสมบัติครบถ้วน ซึ่งช่วยให้คุณกำหนดเส้นทางการรับส่งข้อมูลของผู้ให้บริการ AI อัปสตรีมผ่านพร็อกซี HTTP, HTTPS หรือ SOCKS5 ไม่ว่าคุณจะอยู่ในภูมิภาคที่ถูกบล็อก ต้องการการหมุนเวียน IP หรือต้องการเก็บลายนิ้วมือ — คู่มือนี้ครอบคลุมทุกอย่าง

---

## สารบัญ

- [เหตุใดจึงต้องใช้พรอกซี?](#why-use-proxies)
- [ภาพรวมสถาปัตยกรรม](#architecture-overview)
- [ระบบพร็อกซี 4 ระดับ](#4-level-proxy-system)
- [รีจิสทรีพร็อกซี (CRUD)](#proxy-registry-crud)
- [1proxy ตลาดฟรี](#1proxy-free-proxy-marketplace)
- [การหมุนพร็อกซี](#proxy-rotation)
- [ป้องกันการตรวจจับและการลักลอบ](#anti-detection--stealth)
- [โหมดพร็อกซีอัปสตรีม](#upstream-proxy-modes)
- [แดชบอร์ด UI](#dashboard-ui)
- [อ้างอิง API](#api-reference)
- [ตัวแปรสภาพแวดล้อม](#environment-variables)
- [การแก้ไขปัญหา](#troubleshooting)

---

## เหตุใดจึงต้องใช้พรอกซี?

ผู้ให้บริการ AI หลายรายจำกัดการเข้าถึงตามภูมิภาคทางภูมิศาสตร์ นักพัฒนาใน** รัสเซีย จีน อิหร่าน คิวบา ตุรกี** และประเทศอื่นๆ พบข้อผิดพลาด เช่น:

```
unsupported_country_region_territory
```

แม้จะอยู่นอกภูมิภาคที่ถูกบล็อก พร็อกซียังมีประโยชน์สำหรับ:

| ใช้กรณี                 | คำอธิบาย                                                       |
| ----------------------- | -------------------------------------------------------------- |
| **บายพาสทางภูมิศาสตร์** | เข้าถึง OpenAI, Anthropic, Codex, Copilot จากประเทศที่ถูกบล็อก |
| **การหมุน IP**          | กระจายคำขอไปยังหลาย IPs เพื่อหลีกเลี่ยงการจำกัดอัตรา           |
| **ความเป็นส่วนตัว**     | ซ่อน IP จริงของคุณจากผู้ให้บริการต้นน้ำ                        |
| **การปฏิบัติตาม**       | กำหนดเส้นทางการจราจรผ่านเขตอำนาจศาลเฉพาะ                       |
| **การทดสอบ**            | จำลองคำขอจากภูมิภาคต่างๆ                                       |

---

## ภาพรวมสถาปัตยกรรม

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

### ส่วนประกอบสำคัญ

| ส่วนประกอบ              | ไฟล์                                         | บทบาท                                                       |
| ----------------------- | -------------------------------------------- | ----------------------------------------------------------- |
| **รีจิสทรีพร็อกซี**     | `src/lib/db/proxies.ts`                      | CRUD สำหรับรายการพร็อกซี การกำหนดขอบเขต +                   |
| **ผู้จัดส่งพร็อกซี**    | `open-sse/utils/proxyDispatcher.ts`          | สร้างโปรแกรมเลือกจ่ายงาน `undici` ProxyAgent/SOCKS พร้อมแคช |
| **การดึงข้อมูลพร็อกซี** | `open-sse/utils/proxyFetch.ts`               | ล้อม `fetch()` ด้วยการฉีดพร็อกซีดิสแพตเชอร์                 |
| **เส้นทางการตั้งค่า**   | `src/app/api/settings/proxy/route.ts`        | การกำหนดค่าพร็อกซีดั้งเดิม API (GET/PUT/DELETE)             |
| **เส้นทางการจัดการ**    | `src/app/api/v1/management/proxies/route.ts` | รีจิสทรี CRUD API (GET/POST/PATCH/DELETE)                   |
| **1พรอกซี DB**          | `src/lib/db/oneproxy.ts`                     | ความคงอยู่ของตลาดพร็อกซีฟรี                                 |

---

## สถานะพร็อกซีเริ่มต้นสำหรับบัญชีใหม่

ใน** การตั้งค่า → Proxy → การกำหนดค่าส่วนกลาง** , ใช้** เปิดใช้งานพรอกซีตามค่าเริ่มต้นสำหรับการเชื่อมต่อใหม่** เพื่อเลือกสถานะพร็อกซีเริ่มต้นของบัญชีผู้ให้บริการที่เพิ่มใหม่

การตั้งค่าใหม่จะควบคุมสถานะพร็อกซีเริ่มต้นของบัญชีผู้ให้บริการที่เพิ่มใหม่ จะไม่เปลี่ยนบัญชีที่มีอยู่หรือแทนที่สวิตช์พร็อกซีส่วนกลาง ค่าเริ่มต้นจะคงลักษณะการทำงานก่อนหน้านี้ไว้ ปิดหนึ่งครั้งเพื่อสร้างบัญชีในอนาคตโดยปิดใช้งานพร็อกซีตามค่าเริ่มต้น

การตั้งค่าจะถูกจัดเก็บเป็น `defaultNewConnectionProxyEnabled` ผ่านการตั้งค่าที่มีอยู่ API โดยค่าเริ่มต้นจะเป็น `true` เมื่อไม่เคยบันทึก การบันทึก `false` จะมีผลกับบัญชีใหม่ในภายหลังโดยไม่ต้องรีสตาร์ท `POST /api/providers` ยอมรับตัวเลือกบูลีนที่เข้มงวด `proxyEnabled`; `true` หรือ `false` ที่ชัดเจนจะมีความสำคัญมากกว่าค่าเริ่มต้นของการสร้าง การละเว้นบัญชีที่ซ้ำกันหรือการเชื่อมต่อ OAuth อีกครั้งจะรักษาสถานะที่จัดเก็บของบัญชีนั้นไว้ บัญชีส่วนบุคคลยังสามารถเปิดหรือปิดใช้งานได้ในภายหลัง

การโอนย้ายผู้ให้บริการแบบเลือกใช้ค่าเริ่มต้นของการติดตั้งปลายทางสำหรับบัญชีใหม่และรักษานโยบายปลายทางเมื่อแทนที่บัญชีที่มีอยู่ การสลับพร็อกซีไม่ใช่ช่องถ่ายโอนแบบพกพา การกู้คืนข้อมูลสำรองแบบเต็มและการโยกย้าย JSON/SQL ในอดีตจะรักษาความหมายการคืนค่าที่มีอยู่ รวมถึงค่าบัญชีที่บันทึกไว้และค่าเริ่มต้นของสคีมาแบบเดิม การคืนค่าการตั้งค่าแบบเต็มสามารถคืนค่าการตั้งค่านี้ได้

การตั้งค่านี้ไม่ได้กำหนดพร็อกซีหรือกำหนดว่าพร็อกซีนั้นมีประสิทธิภาพดีหรือใช้งานอยู่ การกำหนดเส้นทางจริงยังคงขึ้นอยู่กับสวิตช์พร็อกซีส่วนกลางและการกำหนดค่าพร็อกซีที่เกี่ยวข้อง ผู้ให้บริการสังเคราะห์ที่ไม่มีบัญชีถาวร ปริมาณการใช้ OAuth ก่อนการสร้างบัญชี พร็อกซี environment/system และเครือข่ายแบ็กเอนด์ภายนอกอยู่นอกขอบเขต

## ระบบพร็อกซี 4 ระดับ

OmniRoute รองรับการกำหนดค่าพร็อกซีที่** สี่ขอบเขตที่เป็นอิสระ** ได้รับการแก้ไขตามลำดับความสำคัญ:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### ความละเอียดทำงานอย่างไร

เมื่อ OmniRoute ส่งคำขอไปยังผู้ให้บริการอัปสตรีม มันจะเรียก `resolveProxyForConnectionFromRegistry()` ซึ่งจะตรวจสอบแต่ละระดับตามลำดับ:

1. **ระดับบัญชี** — มีพรอกซีที่กำหนดให้กับการเชื่อมต่อเฉพาะนี้ ID หรือไม่?
2. **ระดับผู้ให้บริการ** — มีพรอกซีที่กำหนดให้กับผู้ให้บริการรายนี้ (เช่น `openai`) หรือไม่?
3. **ระดับโลก** — มีการกำหนดค่าพร็อกซีส่วนกลางหรือไม่
4. **ไม่มีพร็อกซี** — การเชื่อมต่อโดยตรงกับผู้ให้บริการ

นัดแรกชนะ ซึ่งหมายความว่าคุณสามารถตั้งค่าพร็อกซีส่วนกลางเป็นทางเลือก แต่แทนที่พร็อกซีสำหรับผู้ให้บริการหรือการเชื่อมต่อเฉพาะได้

### สิ่งที่ได้รับมอบฉันทะ

| ประเภทการรับส่งข้อมูล     | พร็อกซี? | หมายเหตุ                                   |
| ------------------------- | -------- | ------------------------------------------ |
| เสร็จสิ้นการแชท           | ✅       | คำขอ `/v1/chat/completions` ทั้งหมด        |
| การฝัง                    | ✅       | `/v1/embeddings`                           |
| การสร้างภาพ               | ✅       | `/v1/images/generations`                   |
| เสียง (TTS/STT)           | ✅       | `/v1/audio/*`                              |
| การแลกเปลี่ยนโทเค็น OAuth | ✅       | แก้ `unsupported_country_region_territory` |
| การทดสอบการเชื่อมต่อ      | ✅       | ปุ่ม "ทดสอบการเชื่อมต่อ" ใช้พรอกซี         |
| รีเฟรชโทเค็น              | ✅       | พื้นหลังการต่ออายุ OAuth                   |
| การซิงค์โมเดล             | ✅       | รายชื่อรุ่นและการค้นพบ                     |

---

## รีจิสทรีพร็อกซี (CRUD)

รีจิสทรีพร็อกซีคือตาราง SQLite (`proxy_registry`) ที่เก็บพร็อกซีทั้งหมดของคุณ พร็อกซีแต่ละตัวมี:

| สนาม       | พิมพ์     | คำอธิบาย                                                |
| ---------- | --------- | ------------------------------------------------------- |
| `id`       | UUID      | ตัวระบุที่ไม่ซ้ำ                                        |
| `name`     | สตริง     | ฉลากที่มนุษย์สามารถอ่านได้                              |
| `type`     | สตริง     | โปรโตคอล: `http`, `https`, `socks5`                     |
| `host`     | สตริง     | ชื่อโฮสต์พร็อกซีหรือ IP                                 |
| `port`     | จำนวนเต็ม | หมายเลขพอร์ต                                            |
| `username` | สตริง     | ชื่อผู้ใช้รับรองความถูกต้อง (เข้ารหัสเมื่อไม่ได้ใช้งาน) |
| `password` | สตริง     | รหัสผ่านการตรวจสอบสิทธิ์ (เข้ารหัสเมื่อไม่ได้ใช้งาน)    |
| `region`   | สตริง     | ป้ายชื่อภูมิภาค                                         |
| `notes`    | สตริง     | บันทึกข้อความอิสระ                                      |
| `status`   | สตริง     | `active` หรือ `inactive`                                |
| `source`   | สตริง     | `manual` หรือ `oneproxy`                                |

### การสร้างพร็อกซี

**ผ่านแดชบอร์ด:**

1. ไปที่** การตั้งค่า → พร็อกซี**
2. คลิก** เพิ่มพร็อกซี**
3. กรอกประเภท โฮสต์ พอร์ต และข้อมูลรับรองการตรวจสอบเพิ่มเติม
4. บันทึก

**ผ่าน API:**

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

### กำลังอัปเดตพร็อกซี

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **บันทึก:** ข้อมูลประจำตัวจะถูกเก็บรักษาไว้ เว้นแต่คุณจะส่งเอกสารทดแทนที่ไม่ว่างเปล่าอย่างชัดเจน การส่งสตริงว่างสำหรับ `username`/`password` จะเก็บค่าที่เก็บไว้

### การลบพร็อกซี

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### รายชื่อผู้รับมอบฉันทะ

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### การกำหนดผู้รับมอบฉันทะให้กับขอบเขต

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

### การแก้ไขพร็อกซีที่มีประสิทธิภาพ

ตรวจสอบว่าจะใช้พรอกซีใดสำหรับการเชื่อมต่อที่กำหนด:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

ส่งคืนพร็อกซีที่ได้รับการแก้ไขพร้อมกับระดับ (`account`, `provider` หรือ `global`) และแหล่งที่มา

### การมอบหมายเป็นกลุ่ม

กำหนดพร็อกซีหนึ่งตัวให้กับผู้ให้บริการหลายรายหรือการเชื่อมต่อพร้อมกัน:

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

ผู้รับมอบฉันทะรวมอยู่ใน**Backup/Restore** ระบบ. เมื่อคุณส่งออกการกำหนดค่า OmniRoute ของคุณ:

1. ไปที่** แดชบอร์ดการตั้งค่า → การสำรองข้อมูล →**
2. คลิก** ส่งออก** รวมการลงทะเบียนพร็อกซี — และการกำหนดไว้ด้วย
3. หากต้องการคืนค่า ให้คลิก** นำเข้า** และอัพโหลดไฟล์สำรอง

การลงทะเบียนพร็อกซียังรองรับ** upsert โดยพอร์ตโฮสต์+** — หากคุณนำเข้าพรอกซีที่มีอยู่แล้ว (โฮสต์และพอร์ตเดียวกัน) พรอกซีจะอัปเดตแทนที่จะสร้างรายการซ้ำ

### การโยกย้ายมรดก

หากคุณกำหนดค่าพร็อกซีในเวอร์ชันเก่า (การลงทะเบียนล่วงหน้า) OmniRoute จะย้ายข้อมูลเหล่านั้นโดยอัตโนมัติ:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

สิ่งนี้จะเกิดขึ้นครั้งเดียวในการเริ่มต้นระบบครั้งแรกหลังการอัพเกรด ใช้ `migrateLegacyProxyConfigToRegistry({ force: true })` เพื่อรันใหม่

---

## 1proxy ตลาดพร็อกซีฟรี

> 🆕** สนับสนุนโดย [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (ฉบับ [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute ทำงานร่วมกับ** [1พรอกซี](https://1proxy-api.aitradepulse.com)** แพลตฟอร์มชุมชนเพื่อให้เข้าถึงได้** พรอกซีฟรีที่ผ่านการตรวจสอบแล้วหลายร้อยรายการ** จากทั่วโลก เหมาะสำหรับผู้ใช้ที่ไม่มีโครงสร้างพื้นฐานพร็อกซีเป็นของตัวเอง

### มันทำงานอย่างไร

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **ซิงค์** — OmniRoute ดึงข้อมูลพรอกซีที่ผ่านการตรวจสอบแล้วจาก 1proxy API
2. **เก็บ** พร็อกซี — จะถูกบันทึกไว้ในตาราง `proxy_registry` เดียวกันกับ `source = 'oneproxy'`
3. **กรอง** — กรองตามโปรโตคอล ประเทศ คะแนนคุณภาพ
4. **หมุน** — เลือกพร็อกซีที่ดีที่สุดโดยใช้กลยุทธ์คุณภาพ แบบสุ่ม หรือตามลำดับ
5. **ย่อยสลายอัตโนมัติ** — ผู้รับมอบฉันทะที่ล้มเหลวจะทำให้คะแนนคุณภาพลดลง ต่ำกว่าเกณฑ์ → ทำเครื่องหมายว่าไม่ได้ใช้งาน

### กำลังซิงค์พรอกซี

**ผ่านแดชบอร์ด:**

1. ไปที่** การตั้งค่า → 1proxy** แท็บ
2. คลิก** "ซิงค์ทันที"**
3. ดูสถิติ: ผู้รับมอบฉันทะทั้งหมด จำนวนที่ใช้งานอยู่ คุณภาพโดยเฉลี่ย รายละเอียดตามประเทศ

**ผ่าน API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### การกรองพร็อกซี

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

### คะแนนคุณภาพพร็อกซี

พร็อกซี 1proxy แต่ละตัวมาพร้อมกับข้อมูลเมตา:

| สนาม            | คำอธิบาย                                          |
| --------------- | ------------------------------------------------- |
| `qualityScore`  | การให้คะแนน 0-100 จากการตรวจสอบความถูกต้อง 1proxy |
| `latencyMs`     | วัดเวลาแฝงของเครือข่าย                            |
| `anonymity`     | `transparent`, `anonymous` หรือ `elite`           |
| `googleAccess`  | พร็อกซีสามารถเข้าถึงบริการ Google ได้หรือไม่      |
| `countryCode`   | รหัสประเทศ ISO สองตัว                             |
| `lastValidated` | การประทับเวลาของการตรวจสอบครั้งล่าสุด             |

คะแนนคุณภาพได้รับการปรับแบบไดนามิก:

- **คำขอที่ล้มเหลว** ลดคะแนนลง 10 คะแนน
- **คะแนนลดลงเหลือ ≤ 10** พร็อกซี → ถูกทำเครื่องหมาย `inactive`
- พรอกซีที่ไม่ได้ใช้งานจะไม่รวมอยู่ในการหมุนเวียน

### กลยุทธ์การหมุน

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

### เบรกเกอร์

การซิงค์ 1proxy มีเบรกเกอร์ในตัว:

- หลังจาก** ความล้มเหลวในการซิงค์ติดต่อกัน 5 ครั้ง** ความพยายามในการซิงค์เพิ่มเติมจะถูกบล็อก
- รีเซ็ตด้วย: `resetOneproxyCircuitBreaker()` หรือรีสตาร์ทเซิร์ฟเวอร์
- สถานะการซิงค์มีอยู่ที่ `GET /api/settings/oneproxy?action=status`

### กำลังล้างพร็อกซี 1proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## ป้องกันการตรวจจับและการลักลอบ

OmniRoute ไม่เพียงแต่กำหนดเส้นทางการรับส่งข้อมูลผ่านพร็อกซี — เท่านั้น แต่ยังทำให้การรับส่งข้อมูลดูถูกต้อง:

### การปลอมแปลงลายนิ้วมือ TLS

ใช้ `wreq-js` เพื่อสร้างลายนิ้วมือ TLS ที่เหมือนกับเบราว์เซอร์ โดยข้ามระบบการตรวจจับบอทที่ทำเครื่องหมายการจับมือ TLS ที่ไม่ใช่เบราว์เซอร์

### การจับคู่ลายนิ้วมือ CLI

ที่** สลับลายนิ้วมือ CLI** (`Settings → Security`) เรียงลำดับส่วนหัว HTTP และฟิลด์เนื้อหา JSON เพื่อให้ตรงกับลายเซ็นที่แน่นอนของไบนารี CLI ดั้งเดิม (Claude Code, Codex ฯลฯ ) มันได้ผล** ด้านบนของ** พร็อกซี:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

คุณได้รับทั้งสองอย่าง**IP ปิดบัง** และ** ขอความถูกต้อง** พร้อมกัน

### การเก็บรักษาพร็อกซี IP

ป้ายรหัสสีในแดชบอร์ดแสดงว่าระดับพร็อกซีใดที่ใช้งานอยู่:

| ตราสัญลักษณ์ | ระดับ        | ความหมาย                                                        |
| ------------ | ------------ | --------------------------------------------------------------- |
| 🟢           | ทั่วโลก      | การรับส่งข้อมูลทั้งหมดผ่านพรอกซีนี้                             |
| 🟡           | ผู้ให้บริการ | เฉพาะการรับส่งข้อมูลของผู้ให้บริการรายนี้เท่านั้นที่เป็นพร็อกซี |
| 🔵           | การเชื่อมต่อ | key/account เฉพาะนี้ใช้พร็อกซีนี้                               |

ป้ายยังแสดงพร็อกซี IP ที่แก้ไขแล้วสำหรับการตรวจสอบด้วย

---

## โหมดพร็อกซีอัปสตรีม

สำหรับผู้ให้บริการที่ใช้รูปแบบ CLIProxyAPI OmniRoute รองรับโหมดพร็อกซีอัปสตรีมสามโหมด:

| โหมด          | คำอธิบาย                                                   |
| ------------- | ---------------------------------------------------------- |
| `native`      | OmniRoute จัดการการกำหนดเส้นทางพร็อกซีโดยตรง (ค่าเริ่มต้น) |
| `cliproxyapi` | มอบสิทธิ์ให้กับอินสแตนซ์ CLIProxyAPI ภายนอก                |
| `fallback`    | ลองใช้เนทิฟก่อน แล้วกลับไปใช้ CLIProxyAPI                  |

กำหนดค่าต่อผู้ให้บริการ:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## แดชบอร์ด UI

### การตั้งค่าแท็บพร็อกซี →

- **พร็อกซีทั่วโลก** การกำหนดค่า (ตั้งค่าครั้งเดียวสำหรับการรับส่งข้อมูลทั้งหมด)
- **พร็อกซีต่อผู้ให้บริการ** แทนที่
- **พร็อกซีต่อการเชื่อมต่อ** การมอบหมายงาน
- **การทดสอบการเชื่อมต่อ** ผ่านพร็อกซีที่กำหนดค่าไว้
- **ป้ายรหัสสี** แสดงระดับพร็อกซีที่ใช้งานอยู่

### การตั้งค่าแท็บ → 1proxy

- **ซิงค์ทันที** ปุ่มเพื่อดึงพรอกซีฟรี
- **การ์ดสถิติ** : ทั้งหมด, ใช้งานอยู่, คุณภาพเฉลี่ย, ซิงค์ล่าสุด
- **ตัวกรอง** : โปรโตคอล, รหัสประเทศ, คุณภาพขั้นต่ำ
- **ตารางมอบฉันทะ** ด้วยโฮสต์ โปรโตคอล ประเทศ คะแนนคุณภาพ เวลาแฝง การไม่เปิดเผยตัวตน การเข้าถึง Google
- **สถานะการซิงค์** แผงที่มีการติดตาม success/failure และการนับความล้มเหลวติดต่อกัน
- **ล้างทั้งหมด** เพื่อลบรายการ 1proxy ทั้งหมด

---

## อ้างอิง API

### การตั้งค่าพร็อกซี API

| วิธี     | จุดสิ้นสุด                                     | คำอธิบาย                     |
| -------- | ---------------------------------------------- | ---------------------------- |
| `GET`    | `/api/settings/proxy`                          | รับการกำหนดค่าพร็อกซีแบบเต็ม |
| `GET`    | `/api/settings/proxy?level=global`             | รับพร็อกซีทั่วโลก            |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | รับพร็อกซีผู้ให้บริการ       |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | แก้ไขพร็อกซีที่มีประสิทธิภาพ |
| `PUT`    | `/api/settings/proxy`                          | อัปเดตการกำหนดค่าพร็อกซี     |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | ลบพรอกซีในระดับ              |

### พร็อกซีรีจิสทรี API

| วิธี     | จุดสิ้นสุด                                        | คำอธิบาย                     |
| -------- | ------------------------------------------------- | ---------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | รายชื่อผู้รับมอบฉันทะทั้งหมด |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | รับพรอกซีโดย ID              |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | รับการมอบหมายพร็อกซี         |
| `POST`   | `/api/v1/management/proxies`                      | สร้างพร็อกซี                 |
| `PATCH`  | `/api/v1/management/proxies`                      | อัปเดตพร็อกซี                |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | ลบพร็อกซี                    |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | บังคับลบ                     |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | มอบหมายเป็นกลุ่ม             |
| `GET`    | `/api/v1/management/proxies/assignments`          | มอบหมายรายการ                |
| `GET`    | `/api/v1/management/proxies/health`               | สถิติสุขภาพพร็อกซี           |

### อุโมงค์ API

หากต้องการเปิดเผยอินสแตนซ์ OmniRoute ของคุณบนอินเทอร์เน็ตสาธารณะ (Cloudflare/ngrok/Tailscale) แทนที่จะกำหนดเส้นทางขาออกผ่านพร็อกซี โปรดดู [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md) ช่องสัญญาณ REST API อยู่ภายใต้ `/api/tunnels/{cloudflared,ngrok,tailscale}/*` และตั้งฉากกับห่วงโซ่พร็อกซีขาออกที่จัดทำเอกสารไว้ข้างต้น

### 1พรอกซี API

| วิธี     | จุดสิ้นสุด                             | คำอธิบาย                          |
| -------- | -------------------------------------- | --------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | แสดงรายการผู้รับมอบฉันทะ 1 รายการ |
| `GET`    | `/api/settings/oneproxy?action=stats`  | รับสถิติสถานะการซิงค์ +           |
| `GET`    | `/api/settings/oneproxy?action=status` | รับสถานะการซิงค์เท่านั้น          |
| `POST`   | `/api/settings/oneproxy`               | ทริกเกอร์การซิงค์                 |
| `POST`   | `/api/settings/oneproxy/rotate`        | หมุนไปที่พร็อกซีถัดไป             |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | ลบอันหนึ่ง                        |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | เคลียร์ทั้งหมด                    |

### พร็อกซีอัปสตรีม API

| วิธี     | จุดสิ้นสุด                        | คำอธิบาย                      |
| -------- | --------------------------------- | ----------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | รับการกำหนดค่าพร็อกซีอัปสตรีม |
| `PUT`    | `/api/upstream-proxy/:providerId` | ตั้งค่าโหมดพร็อกซีอัปสตรีม    |
| `DELETE` | `/api/upstream-proxy/:providerId` | ลบการกำหนดค่าพร็อกซีอัปสตรีม  |

---

## ตัวแปรสภาพแวดล้อม

| ตัวแปร                | ค่าเริ่มต้น | คำอธิบาย                                                                   |
| --------------------- | ----------- | -------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`      | เปิดใช้งานการสนับสนุนพร็อกซี SOCKS5 (ค่าเริ่มต้น `true` ใน `.env.example`) |

---

## การแก้ไขปัญหา

### "พร็อกซีSOCKS5 ถูกปิดใช้งาน"

ตั้งค่า `ENABLE_SOCKS5_PROXY=true` ในไฟล์ `.env` ของคุณแล้วรีสตาร์ท

### ข้อผิดพลาด "ซ็อกเก็ตวางสาย" ผ่านพรอกซี

นี่เป็นเรื่องปกติสำหรับพรอกซีราคาถูกที่ทำให้การเชื่อมต่อที่ไม่ได้ใช้งานหลุดออกไป OmniRoute จัดการสิ่งนี้โดย:

- ปิดการใช้งาน Keep-alive บนการเชื่อมต่อพร็อกซี (`keepAliveTimeout: 1`)
- ปิดการใช้งานไปป์ไลน์ (`pipelining: 0`)
- แคชโปรแกรมเลือกจ่ายงานเพื่อหลีกเลี่ยงการจับมือกันซ้ำๆ

หากยังคงมีอยู่ ให้ลองใช้พร็อกซีอื่นหรือใช้ฟีเจอร์การหมุน 1proxy

### "unsupported_country_region_territory" ในช่วง OAuth

ตรวจสอบให้แน่ใจว่าได้กำหนดค่าพรอกซีแล้ว** ก่อน** เริ่มต้นโฟลว์ OAuth OmniRoute กำหนดเส้นทางการแลกเปลี่ยนโทเค็น OAuth ผ่านพร็อกซีที่กำหนดค่าไว้ ตั้งค่าพร็อกซีส่วนกลางหรือระดับผู้ให้บริการก่อน จากนั้นจึงเชื่อมต่อ

### ไม่ได้ใช้พร็อกซี

ตรวจสอบลำดับการแก้ปัญหา:

1. ตรวจสอบด้วย `GET /api/settings/proxy?resolve=your-connection-id`
2. ตรวจสอบว่าพร็อกซี `status` คือ `active` (ไม่ใช่ `inactive`)
3. ตรวจสอบให้แน่ใจว่าขอบเขตการกำหนดพร็อกซีตรงกับการเชื่อมต่อของคุณ

### การซิงค์พร็อกซี 1 รายการล้มเหลว

ตรวจสอบสถานะการซิงค์:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

ถ้า `consecutiveFailures >= 5` แสดงว่าเซอร์กิตเบรกเกอร์สะดุด รีสตาร์ทเซิร์ฟเวอร์เพื่อรีเซ็ต หรือรอการรีเซ็ตด้วยตนเอง

---

## สคีมาฐานข้อมูล

### ตาราง `proxy_registry`

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

### ตาราง `proxy_assignments`

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

## การตรวจสุขภาพพร็อกซี (v3.8.16 +)

OmniRoute คา** พรอกซีล้มเหลวอย่างรวดเร็ว** กลไก (`src/lib/proxyHealth.ts`) ตรวจจับพร็อกซีที่ไม่ทำงานใน < 2s ผ่านการตรวจสอบการเชื่อมต่อ TCP อย่างรวดเร็ว จากนั้น** แคชผลลัพธ์** เพื่อหลีกเลี่ยงค่าใช้จ่ายต่อคำขอ

### มันทำงานอย่างไร

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

หากไม่มีสิ่งนี้ พร็อกซีที่ไม่ทำงานจะบล็อกทุกคำขอสำหรับ `PROXY_TIMEOUT_MS` แบบเต็ม (30 เริ่มต้น) ก่อนที่จะล้มเหลว

### ตัวแปรสภาพแวดล้อมที่ปรับได้

| ตัวแปร                       | ค่าเริ่มต้น | วัตถุประสงค์                             |
| ---------------------------- | ----------- | ---------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`      | หมดเวลาการเชื่อมต่อ TCP ต่อการตรวจสุขภาพ |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`     | ระยะเวลาที่ผลลัพธ์ด้านสุขภาพถูกแคชไว้    |

**ค่าที่แนะนำ:**

| สถานการณ์                     | หมดเวลาอย่างรวดเร็วล้มเหลว | แคช TTL  | การใช้เหตุผล                                                                |
| ----------------------------- | -------------------------- | -------- | --------------------------------------------------------------------------- |
| เกตเวย์ API ความเร็วสูง       | 1500ms                     | 60,000ms | แคชที่ยาวขึ้นและรวดเร็วเมื่อล้มเหลวเพื่อลดการตรวจสอบ                        |
| โหนดที่กระจายทางภูมิศาสตร์    | 3000ms                     | 15,000ms | เครือข่ายที่ช้ากว่าต้องใช้เวลามากขึ้น แคชสั้นลงเพื่อการเฟลโอเวอร์ที่รวดเร็ว |
| การพัฒนา/การทดสอบ             | 1,000ms                    | 10,000ms | การวนซ้ำอย่างรวดเร็วบนพรอกซีท้องถิ่น                                        |
| การลักลอบ / ป้องกันการตรวจจับ | 2500ms                     | 45,000ms | หลีกเลี่ยงการซักถามอย่างรวดเร็วซึ่งอาจทำให้เกิดขีดจำกัดอัตรา                |

### การตรวจสอบความสมบูรณ์ของพร็อกซี

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

ค่าสถานะ `stale` จะเป็น `true` เมื่อรายการแคชเกิน `HEALTH_CACHE_TTL_MS` และคำขอถัดไปจะทริกเกอร์การตรวจสอบใหม่

### ค่าเริ่มต้นประเภทต่อพร็อกซี

การตรวจสอบสภาพใช้ค่าเริ่มต้นที่สมเหตุสมผลตามรูปแบบ URL :

| โครงการ                    | พอร์ตเริ่มต้น |
| -------------------------- | ------------- |
| `http://`                  | 8080          |
| `https://`                 | 443           |
| `socks5://` / `socks5h://` | 1080          |

พอร์ตแบบกำหนดเองใน URL (`http://host:9999`) จะมีความสำคัญมากกว่าค่าเริ่มต้นของโครงร่างเสมอ

---

## การวิเคราะห์พร็อกซีและความสามารถในการสังเกต

OmniRoute ติดตามการใช้งานต่อพร็อกซี เพื่อช่วยให้ผู้ปฏิบัติงานวิเคราะห์รูปแบบการกำหนดเส้นทาง เวลาแฝงที่เพิ่มขึ้นอย่างรวดเร็ว และความล้มเหลวที่เกิดซ้ำ

### สิ่งที่ติดตาม

สำหรับทุกคำขอผ่านพร็อกซีที่กำหนดค่าไว้ OmniRoute จะบันทึก:

| เมตริก       | คำอธิบาย                                              |
| ------------ | ----------------------------------------------------- |
| `proxy_url`  | พร็อกซี URL แบบเต็ม (โดยปิดบังข้อมูลรับรองการตรวจสอบ) |
| `provider`   | ผู้ให้บริการต้นน้ำ ID (openai, anthropic ฯลฯ )        |
| `latency_ms` | เวลาไปกลับรวมการจับมือพร็อกซี                         |
| `connect_ms` | เวลาเชื่อมต่อ TCP เท่านั้น                            |
| `status`     | รหัสสถานะ HTTP จากอัปสตรีม                            |
| `error`      | คลาสผิดพลาดหากคำขอล้มเหลว                             |
| `timestamp`  | ISO 8601 UTC                                          |

### การเข้าถึงข้อมูล

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

จุดสิ้นสุดที่แท้จริงคือ `/api/usage/proxy-logs` (ดู `src/app/api/usage/proxy-logs/route.ts`) ตำแหน่งข้อมูลนี้รองรับ:

- `GET /api/usage/proxy-logs` — ดึงข้อมูลบันทึกพร็อกซี
- `DELETE /api/usage/proxy-logs` — ล้างบันทึกพร็อกซีทั้งหมด

สามารถสอบถามสถิติรวมได้โดยตรงจากตาราง `proxy_logs` ผ่าน SQL หากจำเป็น แดชบอร์ด UI อาจเสนอมุมมองแบบรวม

### รูปแบบทั่วไป

**ตรวจจับพร็อกซีที่กระพือปีก** (สลับระหว่าง success/failure):

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

**ค้นหาผู้รับมอบฉันทะที่ช้า** (เวลาแฝง p95 > 2 วินาที):

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

## แผนภูมิการตัดสินใจกลยุทธ์การหมุน

เมื่อกำหนดพรอกซีหลายรายการให้กับขอบเขต OmniRoute จะใช้ a** กลยุทธ์การหมุนเวียน** เพื่อเลือกอันที่จะใช้สำหรับแต่ละคำขอ กลยุทธ์ได้รับการกำหนดค่าในระดับขอบเขต (ทั่วโลก ต่อผู้ให้บริการ ต่อบัญชี ต่อคอมโบ)

### กลยุทธ์ที่มีอยู่

| กลยุทธ์                 | เมื่อจะใช้                         | การแลกเปลี่ยน                                                  |
| ----------------------- | ---------------------------------- | -------------------------------------------------------------- |
| `quality` (ค่าเริ่มต้น) | การผลิตด้วยผู้รับมอบฉันทะผสมคุณภาพ | โปรดปรานผู้รับมอบฉันทะที่มีคะแนนสูง อาจอดอาหารที่มีคะแนนต่ำได้ |
| `random`                | การกระจายโหลดความเป็นส่วนตัว       | การกระจายตัวสม่ำเสมอ ละเว้นสัญญาณคุณภาพ                        |
| `sequential`            | การดีบัก การทดสอบเชิงกำหนด         | หมุนเวียนผ่านผู้รับมอบฉันทะตามลำดับ ง่ายต่อการให้เหตุผล        |

### ต้นไม้การตัดสินใจ

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

## การยกเว้นความล้มเหลวอัตโนมัติสำหรับพร็อกซีของคุณเอง

กลุ่มตลาดกลาง 1proxy ลดระดับพร็อกซีที่ล้มเหลวโดยอัตโนมัติอยู่แล้ว (ดู [คะแนนคุณภาพพร็อกซี](#proxy-quality-scores) ) สำหรับผู้รับมอบฉันทะ** คุณ** เพิ่มลงในรีจิสทรี ตัวกำหนดเวลาสุขภาพพื้นหลัง (`src/lib/proxyHealth/scheduler.ts`) ให้พฤติกรรม "แยกสมาชิกที่ตายแล้วออกจากห่วงโซ่โดยอัตโนมัติ" แบบเดียวกันโดยไม่ต้องลบสิ่งใดเลย:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

มันเข้ากับ multi-proxy chain ได้อย่างไร:

1. ตัวกำหนดเวลาจะตรวจสอบพร็อกซีที่ลงทะเบียนทุกตัวทุกๆ `PROXY_HEALTH_INTERVAL_MS` (ค่าเริ่มต้น 10 นาที; ขั้นต่ำ 1 นาที)
2. หลังจาก `PROXY_AUTO_REMOVE_AFTER` ติดต่อกัน** สรุปได้** ความล้มเหลว (ความล้มเหลวในการเชื่อมต่อจริง — การหมดเวลาหรือ 5xx ของเป้าหมายโพรบจะไม่นับรวม โปรดดูที่ [การตรวจสุขภาพพร็อกซี](#proxy-health-checking-v3816) ) `status` ของพร็อกซีถูกตั้งค่าเป็น `dead`
3. `dead` เป็นหนึ่งในสถานะที่ตัวกรองสถานะยังมีชีวิตอยู่ซึ่งใช้โดยการแก้ไข pool/rotation จะไม่รวม ดังนั้นการหมุนของขอบเขต (round-robin / Random / Sticky / latency — ดู [Rotation Strategy Decision Tree](#rotation-strategy-decision-tree) ) จะหยุดส่งพร็อกซีนั้นให้กับคำขอใหม่ทันที ไม่มีพร็อกซีอื่นใดในพูลที่ได้รับผลกระทบ และพูลทั้งหมดจะไม่ถอยกลับไปยังการเชื่อมต่อโดยตรง — ดู [4-Level Proxy System](#4-level-proxy-system) failed-closed guard
4. The scheduler keeps probing `dead` proxies on the same interval. The next successful probe flips `status` back to `active` and it re-enters rotation — no manual re-add required.

นี่เป็นการจงใจ** เลือกใช้และไม่ทำลาย** : โดยค่าเริ่มต้นตัวกำหนดตารางเวลาจะนับและบันทึกความล้มเหลวเท่านั้น (ดูนโยบาย C ใน `decision.ts`) และ `PROXY_AUTO_DISABLE` จะไม่ลบแถว — ซึ่งเป็นสิ่งที่แยกกัน `PROXY_AUTO_REMOVE` แฟล็กที่ก้าวร้าวมากขึ้น หากตั้งค่าทั้งสองเป็น `true` `PROXY_AUTO_REMOVE` จะชนะ (พร็อกซีที่กำลังจะลบไม่มีประโยชน์สำหรับการปิดการใช้งานแบบ soft ในระหว่างนั้น) ดูการอ้างอิง [การกำหนดค่าสภาพแวดล้อม](../reference/ENVIRONMENT.md) สำหรับรายการตัวแปรทั้งหมด

---

> 📖** เอกสารที่เกี่ยวข้อง:**
>
> - [คู่มือผู้ใช้](../guides/USER_GUIDE.md) — การตั้งค่าและการกำหนดค่าทั่วไป - [API การอ้างอิง](../reference/API_REFERENCE.md) — เอกสารประกอบ API แบบเต็ม - [การกำหนดค่าสภาพแวดล้อม](../reference/ENVIRONMENT.md) — ตัวแปรสภาพแวดล้อมทั้งหมด
