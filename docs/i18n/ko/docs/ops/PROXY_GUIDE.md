# 🌐 OmniRoute Proxy Guide (한국어)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **지리적 블록을 우회하고, 신원을 보호하며, 구성 복잡성 없이 모든 프록시 — 통해 AI 트래픽을 라우팅합니다.**

OmniRoute HTTP, HTTPS 또는 SOCKS5 프록시를 통해 업스트림 AI 공급자 트래픽을 라우팅할 수 있는 모든 기능을 갖춘 프록시 관리 시스템이 포함되어 있습니다. 차단된 지역에 있든, IP 회전이 필요하든, 스텔스 지문 인식 — 원하든 이 가이드에서는 모든 것을 다룹니다.

---

## 목차

- [프록시를 사용하는 이유는 무엇입니까?](#why-use-proxies)
- [아키텍처 개요](#architecture-overview)
- [4레벨 프록시 시스템](#4-level-proxy-system)
- [프록시 레지스트리(CRUD)](#proxy-registry-crud)
- [1프록시 무료 마켓플레이스](#1proxy-free-proxy-marketplace)
- [프록시 회전](#proxy-rotation)
- [탐지 방지 및 스텔스](#anti-detection--stealth)
- [업스트림 프록시 모드](#upstream-proxy-modes)
- [대시보드 UI](#dashboard-ui)
- [API 참조](#api-reference)
- [환경 변수](#environment-variables)
- [문제 해결](#troubleshooting)

---

## 프록시를 사용하는 이유는 무엇입니까?

많은 AI 제공업체는 지역별로 액세스를 제한합니다. 개발자** 러시아, 중국, 이란, 쿠바, 터키** , 기타 국가에서는 다음과 같은 오류가 발생합니다.

```
unsupported_country_region_territory
```

차단된 지역 외부에서도 프록시는 다음과 같은 경우에 유용합니다.

| 사용 사례       | 설명                                                               |
| --------------- | ------------------------------------------------------------------ |
| **지리적 우회** | 차단된 국가에서 OpenAI, Anthropic, Codex, Copilot 에 액세스하세요. |
| **IP 회전**     | 속도 제한을 피하기 위해 여러 IPs 에 요청을 분산시킵니다.           |
| **은둔**        | 업스트림 공급자로부터 실제 IP 숨기세요                             |
| **규정 준수**   | 특정 관할권을 통해 트래픽 라우팅                                   |
| **테스트**      | 다양한 지역의 요청 시뮬레이션                                      |

---

## 아키텍처 개요

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

### 주요 구성 요소

| 요소                  | 파일                                         | 역할                                                    |
| --------------------- | -------------------------------------------- | ------------------------------------------------------- |
| **프록시 레지스트리** | `src/lib/db/proxies.ts`                      | 프록시 항목에 대한 CRUD + 범위 할당                     |
| **프록시 디스패처**   | `open-sse/utils/proxyDispatcher.ts`          | 캐싱을 사용하여 `undici` ProxyAgent/SOCKS 디스패처 생성 |
| **프록시 가져오기**   | `open-sse/utils/proxyFetch.ts`               | 프록시 디스패처 주입으로 `fetch()` 래핑합니다.          |
| **설정 경로**         | `src/app/api/settings/proxy/route.ts`        | 레거시 프록시 구성 API (GET/PUT/DELETE)                 |
| **관리경로**          | `src/app/api/v1/management/proxies/route.ts` | 레지스트리 CRUD API (GET/POST/PATCH/DELETE)             |
| **1프록시 DB**        | `src/lib/db/oneproxy.ts`                     | 무료 프록시 마켓플레이스 지속성                         |

---

## 새 계정의 기본 프록시 상태

~ 안에** 설정 → 프록시 → 글로벌 구성** , 사용** 새 연결에 대해 기본적으로 프록시 활성화** 새로 추가된 공급자 계정의 초기 프록시 상태를 선택합니다.

새로운 설정은 새로 추가된 공급자 계정의 초기 프록시 상태를 제어합니다. 기존 계정을 변경하거나 글로벌 프록시 스위치를 교체하지 않습니다. 초기값은 이전 동작을 유지합니다. 기본적으로 프록시가 비활성화된 상태로 향후 계정을 만들려면 이 기능을 한 번 끄세요.

기본 설정은 기존 설정 API 통해 `defaultNewConnectionProxyEnabled` 로 저장됩니다. 저장되지 않은 경우 기본값은 `true` 입니다. `false` 저장하면 다시 시작하지 않고도 후속 새 계정에 적용됩니다. `POST /api/providers` 선택적 엄격한 부울 `proxyEnabled` 허용합니다. 명시적인 `true` 또는 `false` 생성 기본값보다 우선합니다. 중복 계정을 생략하거나 OAuth 다시 연결하면 해당 계정의 저장된 상태가 유지됩니다. 개별 계정은 나중에 활성화하거나 비활성화할 수 있습니다.

선택적 공급자 전송은 새 계정에 대해 대상 설치의 기본값을 사용하고 기존 계정을 교체할 때 대상 정책을 유지합니다. 프록시 토글은 휴대용 전송 필드가 아닙니다. 전체 백업 복원 및 기록 JSON/SQL 마이그레이션은 저장된 계정 값 및 레거시 스키마 기본값을 포함하여 기존 복원 의미를 유지합니다. 전체 설정 복원을 통해 이 기본 설정도 복원할 수 있습니다.

이 기본 설정은 프록시를 할당하거나 해당 프록시가 정상인지 또는 사용 중인지 설정하지 않습니다. 실제 라우팅은 여전히 글로벌 프록시 스위치와 적용 가능한 프록시 구성에 따라 달라집니다. 영구 계정이 없는 합성 공급자, 계정 생성 전의 OAuth 트래픽, environment/system 프록시 및 외부 백엔드의 네트워킹은 범위를 벗어납니다.

## 4레벨 프록시 시스템

OmniRoute 다음에서 프록시 구성을 지원합니다.** 4개의 독립적인 범위** , 우선순위에 따라 해결됨:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### 해결 방법

OmniRoute 업스트림 공급자에게 요청을 보낼 때 각 수준을 순서대로 확인하는 `resolveProxyForConnectionFromRegistry()` 호출합니다.

1. **계정 수준** — 이 특정 연결 ID 에 프록시가 할당되어 있습니까?
2. **공급자 수준** — 이 공급자에게 할당된 프록시가 있습니까(예: `openai`)?
3. **글로벌 수준** — 글로벌 프록시가 구성되어 있습니까?
4. **프록시 없음** — 공급자에 대한 직접 연결입니다.

첫 번째 경기가 승리합니다. 이는 글로벌 프록시를 폴백으로 설정할 수 있지만 특정 공급자 또는 연결에 대해서는 이를 재정의할 수 있음을 의미합니다.

### 프록시되는 항목

| 트래픽 유형     | 프록시되었나요? | 메모                                               |
| --------------- | --------------- | -------------------------------------------------- |
| 채팅 완료       | ✅              | 모든 `/v1/chat/completions` 요청                   |
| 임베딩          | ✅              | `/v1/embeddings`                                   |
| 이미지 생성     | ✅              | `/v1/images/generations`                           |
| 오디오(TTS/STT) | ✅              | `/v1/audio/*`                                      |
| OAuth 토큰 교환 | ✅              | `unsupported_country_region_territory` 해결합니다. |
| 연결 테스트     | ✅              | "연결 테스트" 버튼은 프록시를 사용합니다.          |
| 토큰 새로고침   | ✅              | 배경 OAuth 갱신                                    |
| 모델 동기화     | ✅              | 모델 목록 및 검색                                  |

---

## 프록시 레지스트리(CRUD)

프록시 레지스트리는 모든 프록시를 저장하는 SQLite 테이블(`proxy_registry`)입니다. 각 프록시에는 다음이 포함됩니다.

| 필드       | 유형 | 설명                                |
| ---------- | ---- | ----------------------------------- |
| `id`       | UUID | 고유 식별자                         |
| `name`     | 끈   | 사람이 읽을 수 있는 라벨            |
| `type`     | 끈   | 프로토콜: `http`, `https`, `socks5` |
| `host`     | 끈   | 프록시 호스트 이름 또는 IP          |
| `port`     | 정수 | 포트 번호                           |
| `username` | 끈   | 인증 사용자 이름(저장 시 암호화됨)  |
| `password` | 끈   | 인증 비밀번호(저장 시 암호화됨)     |
| `region`   | 끈   | 지리적 지역 라벨                    |
| `notes`    | 끈   | 자유 텍스트 메모                    |
| `status`   | 끈   | `active` 또는 `inactive`            |
| `source`   | 끈   | `manual` 또는 `oneproxy`            |

### 프록시 만들기

**대시보드를 통해:**

1. 이동** 설정 → 프록시**
2. 딸깍 하는 소리** 프록시 추가**
3. 유형, 호스트, 포트 및 선택적 인증 자격 증명을 입력합니다.
4. 구하다

**API 통해 :**

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

### 프록시 업데이트

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **메모:** 비어 있지 않은 대체 항목을 명시적으로 보내지 않는 한 자격 증명은 유지됩니다. `username`/`password` 에 대해 빈 문자열을 보내면 저장된 값이 유지됩니다.

### 프록시 삭제

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### 프록시 나열

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### 범위에 프록시 할당

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

### 효과적인 프록시 해결

특정 연결에 어떤 프록시가 사용되는지 확인하세요.

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

해당 레벨(`account`, `provider` 또는 `global`) 및 소스와 함께 확인된 프록시를 반환합니다.

### 대량 할당

한 번에 여러 공급자 또는 연결에 하나의 프록시를 할당합니다.

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

프록시는**Backup/Restore** 체계. OmniRoute 구성을 내보낼 때:

1. 이동** 대시보드 → 설정 → 백업**
2. 딸깍 하는 소리** 내보내다** — 프록시 레지스트리 및 할당이 포함됩니다.
3. 복원하려면** 수입** 그리고 백업 파일 업로드

프록시 레지스트리도 지원합니다.** 호스트 + 포트로 upsert** — 이미 존재하는 프록시(동일한 호스트 및 포트)를 가져오는 경우 복제본을 생성하는 대신 업데이트됩니다.

### 레거시 마이그레이션

이전 버전(사전 레지스트리)에서 프록시를 구성한 경우 OmniRoute 자동으로 프록시를 마이그레이션합니다.

```
Legacy key_value store → proxy_registry + proxy_assignments
```

이 문제는 업그레이드 후 처음 시작할 때 한 번 발생합니다. 다시 실행하려면 `migrateLegacyProxyConfigToRegistry({ force: true })` 사용하세요.

---

## 1proxy 무료 프록시 마켓플레이스

> 🆕** 작성자: [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (문제 [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute 다음과 통합됩니다.** [1프록시](https://1proxy-api.aitradepulse.com)** 액세스를 제공하는 커뮤니티 플랫폼** 수백 개의 검증된 무료 프록시** 전 세계에서. 이는 자체 프록시 인프라가 없는 사용자에게 적합합니다.

### 작동 방식

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **동조** — OmniRoute 1proxy API 에서 검증된 프록시를 가져옵니다.
2. **가게** — 프록시는 `source = 'oneproxy'` 와 동일한 `proxy_registry` 테이블에 저장됩니다.
3. **필터** — 프로토콜, 국가, 품질 점수별로 필터링
4. **회전** — 품질, 무작위 또는 순차 전략을 사용하여 최고의 프록시를 선택하세요.
5. **자동 저하** — 실패한 프록시는 품질 점수가 낮아집니다. 임계값 미만 → 비활성으로 표시됨

### 프록시 동기화 중

**대시보드를 통해:**

1. 이동** 설정 → 1proxy** 꼬리표
2. 딸깍 하는 소리** "지금 동기화"**
3. 통계 보기: 총 프록시, 활성 개수, 평균 품질, 국가별 분석

**API 통해 :**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### 프록시 필터링

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

### 프록시 품질평가점수

각 1proxy 프록시에는 메타데이터가 제공됩니다.

| 필드            | 설명                                             |
| --------------- | ------------------------------------------------ |
| `qualityScore`  | 1개의 프록시 검증에서 0~100 등급                 |
| `latencyMs`     | 측정된 네트워크 대기 시간                        |
| `anonymity`     | `transparent`, `anonymous` 또는 `elite`          |
| `googleAccess`  | 프록시가 Google 서비스에 액세스할 수 있는지 여부 |
| `countryCode`   | 두 글자로 된 ISO 국가 코드                       |
| `lastValidated` | 마지막 검증의 타임스탬프                         |

품질평가점수는 동적으로 조정됩니다.

- **실패한 요청** 점수를 10점 감점하다
- **점수가 ≤ 10으로 떨어졌습니다.** → 프록시는 `inactive` 로 표시됩니다.
- 비활성 프록시는 순환에서 제외됩니다.

### 순환 전략

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

### 회로 차단기

1proxy 동기화에는 회로 차단기가 내장되어 있습니다.

- 후에** 5회 연속 동기화 실패** , 추가 동기화 시도가 차단됩니다.
- 다음으로 재설정: `resetOneproxyCircuitBreaker()` 또는 서버 다시 시작
- 동기화 상태는 `GET /api/settings/oneproxy?action=status` 에서 확인할 수 있습니다.

### 1개의 프록시 프록시 지우기

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## 탐지 방지 및 스텔스

OmniRoute 프록시 — 통해 트래픽을 라우팅하는 것이 아니라 트래픽이 합법적인 것처럼 보이게 만듭니다.

### TLS 지문 스푸핑

`wreq-js` 사용하여 브라우저와 유사한 TLS 지문을 생성하고 브라우저가 아닌 TLS 핸드셰이크에 플래그를 지정하는 봇 감지 시스템을 우회합니다.

### CLI 지문 매칭

그만큼**CLI 지문 토글** (`Settings → Security`)는 기본 CLI 바이너리(Claude 코드, Codex 등)의 정확한 서명과 일치하도록 HTTP 헤더 및 JSON 본문 필드를 재정렬합니다. 이것은 작동합니다** 위에** 프록시:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

당신은 둘 다 얻습니다**IP 마스킹** 그리고** 진정성을 요청하다** 동시에.

### 프록시 IP 보존

대시보드의 색상으로 구분된 배지는 활성화된 프록시 수준을 보여줍니다.

| 배지 | 수준   | 의미                                        |
| ---- | ------ | ------------------------------------------- |
| 🟢   | 글로벌 | 모든 트래픽은 이 프록시를 통과합니다.       |
| 🟡   | 공급자 | 이 공급자의 트래픽만 프록시됩니다.          |
| 🔵   | 연결   | 이 특정 key/account 이 프록시를 사용합니다. |

배지에는 확인을 위해 해결된 프록시 IP 도 표시됩니다.

---

## 업스트림 프록시 모드

CLIProxyAPI 패턴을 사용하는 공급자의 경우 OmniRoute 세 가지 업스트림 프록시 모드를 지원합니다.

| 방법          | 설명                                                |
| ------------- | --------------------------------------------------- |
| `native`      | OmniRoute 프록시 라우팅을 직접 처리합니다(기본값)   |
| `cliproxyapi` | 외부 CLIProxyAPI 인스턴스에 위임                    |
| `fallback`    | 먼저 네이티브를 시도하고 CLIProxyAPI 로 돌아갑니다. |

공급자별 구성:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## 대시보드 UI

### 설정 → 프록시 탭

- **글로벌 프록시** 구성(모든 트래픽에 대해 한 번 설정)
- **공급자별 프록시** 재정의
- **연결별 프록시** 과제
- **연결 테스트** 구성된 프록시를 통해
- **색상으로 구분된 배지** 활성 프록시 수준 표시

### 설정 → 1proxy 탭

- **지금 동기화** 무료 프록시를 가져오는 버튼
- **통계 카드** : 전체, 활성, 평균 품질, 마지막 동기화
- **필터** : 프로토콜, 국가 코드, 최소 품질
- **프록시 테이블** 호스트, 프로토콜, 국가, 품질 점수, 대기 시간, 익명성, Google 액세스 포함
- **동기화 상태** success/failure 추적 및 연속 실패 횟수가 포함된 패널
- **모두 지우기** 1개의 프록시 항목을 모두 제거하려면

---

## API 참조

### 프록시 설정 API

| 방법     | 엔드포인트                                     | 설명                      |
| -------- | ---------------------------------------------- | ------------------------- |
| `GET`    | `/api/settings/proxy`                          | 전체 프록시 구성 가져오기 |
| `GET`    | `/api/settings/proxy?level=global`             | 글로벌 프록시 받기        |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | 공급자 프록시 받기        |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | 효과적인 프록시 해결      |
| `PUT`    | `/api/settings/proxy`                          | 프록시 구성 업데이트      |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | 수준에서 프록시 제거      |

### 프록시 레지스트리 API

| 방법     | 엔드포인트                                        | 설명              |
| -------- | ------------------------------------------------- | ----------------- |
| `GET`    | `/api/v1/management/proxies`                      | 모든 프록시 나열  |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | ID 로 프록시 받기 |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | 프록시 할당 받기  |
| `POST`   | `/api/v1/management/proxies`                      | 프록시 만들기     |
| `PATCH`  | `/api/v1/management/proxies`                      | 프록시 업데이트   |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | 프록시 삭제       |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | 강제 삭제         |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | 대량 할당         |
| `GET`    | `/api/v1/management/proxies/assignments`          | 과제 나열         |
| `GET`    | `/api/v1/management/proxies/health`               | 프록시 상태 통계  |

### 터널 API

프록시를 통해 아웃바운드를 라우팅하는 대신 OmniRoute 인스턴스를 공용 인터넷(Cloudflare/ngrok/Tailscale)에 노출하려면 [TUNNELS_GUIDE.md 를](./TUNNELS_GUIDE.md) 참조하세요. 터널 REST API `/api/tunnels/{cloudflared,ngrok,tailscale}/*` 아래에 있으며 위에 문서화된 아웃바운드 프록시 체인과 직교합니다.

### 1프록시 API

| 방법     | 엔드포인트                             | 설명                        |
| -------- | -------------------------------------- | --------------------------- |
| `GET`    | `/api/settings/oneproxy`               | 1개의 프록시 프록시 나열    |
| `GET`    | `/api/settings/oneproxy?action=stats`  | 통계 + 동기화 상태 가져오기 |
| `GET`    | `/api/settings/oneproxy?action=status` | 동기화 상태만 가져오기      |
| `POST`   | `/api/settings/oneproxy`               | 트리거 동기화               |
| `POST`   | `/api/settings/oneproxy/rotate`        | 다음 프록시로 회전          |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | 하나 삭제                   |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | 모두 지우기                 |

### 업스트림 프록시 API

| 방법     | 엔드포인트                        | 설명                          |
| -------- | --------------------------------- | ----------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | 업스트림 프록시 구성 가져오기 |
| `PUT`    | `/api/upstream-proxy/:providerId` | 업스트림 프록시 모드 설정     |
| `DELETE` | `/api/upstream-proxy/:providerId` | 업스트림 프록시 구성 제거     |

---

## 환경 변수

| 변하기 쉬운           | 기본   | 설명                                                       |
| --------------------- | ------ | ---------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true` | SOCKS5 프록시 지원 활성화( `.env.example` 의 기본 `true` ) |

---

## 문제 해결

### "SOCKS5 프록시가 비활성화되었습니다"

`.env` 파일에 `ENABLE_SOCKS5_PROXY=true` 설정하고 다시 시작하세요.

### 프록시를 통한 "소켓 끊기" 오류

유휴 연결을 끊는 값싼 프록시에서는 이는 정상적인 현상입니다. OmniRoute 이미 다음을 통해 이를 처리합니다.

- 프록시 연결에서 연결 유지 비활성화(`keepAliveTimeout: 1`)
- 파이프라이닝 비활성화(`pipelining: 0`)
- 반복적인 핸드셰이크를 방지하기 위해 디스패처 캐싱

지속되면 다른 프록시를 시도하거나 1프록시 순환 기능을 사용하십시오.

### OAuth 중 "unsupported_country_region_territory"

프록시가 구성되어 있는지 확인하세요.** ~ 전에** OAuth 흐름을 시작합니다. OmniRoute 구성된 프록시를 통해 OAuth 토큰 교환을 라우팅합니다. 먼저 글로벌 또는 공급자 수준 프록시를 설정한 다음 연결하세요.

### 프록시가 사용되지 않음

해결 순서를 확인하세요.

1. `GET /api/settings/proxy?resolve=your-connection-id` 로 확인
2. 프록시 `status` `active` ( `inactive` 아님)인지 확인하세요.
3. 프록시 할당 범위가 연결과 일치하는지 확인하세요.

### 1프록시 동기화 실패

동기화 상태를 확인하세요.

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

`consecutiveFailures >= 5` 인 경우 회로 차단기가 작동된 것입니다. 재설정하려면 서버를 다시 시작하거나 수동 재설정을 기다립니다.

---

## 데이터베이스 스키마

### `proxy_registry` 테이블

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

### `proxy_assignments` 테이블

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

## 프록시 상태 확인(v3.8.16 +)

OmniRoute 의** 프록시 빠른 실패** 메커니즘(`src/lib/proxyHealth.ts`)은 빠른 TCP 연결 확인을 통해 < 2s에서 죽은 프록시를 감지한 다음** 결과를 캐시합니다** 요청별 오버헤드를 방지합니다.

### 작동 방식

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

이것이 없으면 데드 프록시는 실패하기 전에 전체 `PROXY_TIMEOUT_MS` (기본값 30초)에 대한 모든 요청을 차단합니다.

### 조정 가능한 환경 변수

| 변하기 쉬운                  | 기본    | 목적                           |
| ---------------------------- | ------- | ------------------------------ |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | 상태 확인당 TCP 연결 시간 초과 |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | 건강 결과가 캐시되는 기간      |

**권장 값:**

| 대본                         | 빠른 실패 시간 초과 | 캐시 TTL | 추리                                                                            |
| ---------------------------- | ------------------- | -------- | ------------------------------------------------------------------------------- |
| 처리량이 높은 API 게이트웨이 | 1500ms              | 60000ms  | 공격적인 오류 방지, 더 긴 캐시로 검사 횟수 감소                                 |
| 지리적으로 분산된 노드       | 3000ms              | 15000ms  | 느린 네트워크에는 더 많은 시간이 필요합니다. 빠른 장애 조치를 위한 더 짧은 캐시 |
| 개발/테스트                  | 1000ms              | 10000ms  | 로컬 프록시에 대한 빠른 반복                                                    |
| 스텔스/탐지 방지             | 2500ms              | 45000ms  | 속도 제한을 유발할 수 있는 신속한 조사를 피하세요.                              |

### 프록시 상태 검사

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

캐시 항목이 `HEALTH_CACHE_TTL_MS` 초과하고 다음 요청이 새로운 검사를 트리거할 때 `stale` 플래그는 `true` 입니다.

### 프록시 유형별 기본값

상태 확인에서는 URL 구성표에 따라 합리적인 기본값을 사용합니다.

| 계획                       | 기본 포트 |
| -------------------------- | --------- |
| `http://`                  | 8080      |
| `https://`                 | 443       |
| `socks5://` / `socks5h://` | 1080      |

URL (`http://host:9999`)의 사용자 정의 포트는 항상 구성표 기본값보다 우선합니다.

---

## 프록시 분석 및 관찰 가능성

OmniRoute 프록시별 사용량을 추적하여 운영자가 라우팅 패턴, 대기 시간 급증 및 반복되는 오류를 진단하는 데 도움을 줍니다.

### 추적되는 내용

구성된 프록시를 통한 모든 요청에 대해 OmniRoute 다음을 기록합니다.

| 미터법       | 설명                                        |
| ------------ | ------------------------------------------- |
| `proxy_url`  | 전체 프록시 URL (인증 자격 증명이 마스크됨) |
| `provider`   | 업스트림 공급자 ID (openai, anthropic 등)   |
| `latency_ms` | 프록시 핸드셰이크를 포함한 총 왕복 시간     |
| `connect_ms` | TCP 연결 시간만                             |
| `status`     | 업스트림의 HTTP 상태 코드                   |
| `error`      | 요청이 실패한 경우 오류 클래스              |
| `timestamp`  | ISO 8601 UTC                                |

### 데이터에 접근하기

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

실제 끝점은 `/api/usage/proxy-logs` 입니다( `src/app/api/usage/proxy-logs/route.ts` 참조). 이 엔드포인트는 다음을 지원합니다.

- `GET /api/usage/proxy-logs` — 프록시 로그 검색
- `DELETE /api/usage/proxy-logs` — 모든 프록시 로그 지우기

필요한 경우 SQL 통해 `proxy_logs` 테이블에서 직접 집계 통계를 쿼리할 수 있습니다. 대시보드 UI 는 집계 보기를 제공할 수 있습니다.

### 일반적인 패턴

**플래핑 프록시 감지** ( success/failure 사이에서 대체):

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

**느린 프록시 찾기** (p95 대기 시간 > 2s):

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

## 순환 전략 결정 트리

여러 프록시가 범위에 할당되면 OmniRoute 는** 순환 전략** 각 요청에 사용할 것을 선택합니다. 전략은 범위 수준(전역, 공급자별, 계정별, 콤보별)에서 구성됩니다.

### 사용 가능한 전략

| 전략               | 언제 사용하나요?               | 절충안                                                                        |
| ------------------ | ------------------------------ | ----------------------------------------------------------------------------- |
| `quality` (기본값) | 혼합 품질 프록시를 사용한 제작 | 높은 등급의 프록시를 선호합니다. 낮은 등급의 사람들은 굶어 죽을 수도 있습니다 |
| `random`           | 부하 분산, 개인 정보 보호      | 균일한 분포; 품질 신호를 무시합니다                                           |
| `sequential`       | 디버깅, 결정론적 테스트        | 프록시를 순서대로 순환합니다. 추론하기 쉽다                                   |

### 의사결정 트리

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

## 자신의 프록시에 대한 자동 실패 제외

1proxy 마켓플레이스 풀은 이미 실패한 프록시의 품질을 자동으로 저하시킵니다( [프록시 품질 점수](#proxy-quality-scores) 참조). 프록시의 경우** 너** 레지스트리에 추가되면 백그라운드 상태 스케줄러(`src/lib/proxyHealth/scheduler.ts`)는 아무것도 삭제하지 않고 동일한 "체인에서 자동으로 죽은 멤버 제외" 동작을 제공합니다.

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

다중 프록시 체인에 적용되는 방법:

1. 스케줄러는 `PROXY_HEALTH_INTERVAL_MS` (기본값 10분, 최소 1분)마다 등록된 모든 프록시를 조사합니다.
2. `PROXY_AUTO_REMOVE_AFTER` 연속 이후** 단호한** 실패(실제 연결 실패 — 시간 초과 또는 프로브 대상 자체의 5xx는 계산되지 않습니다. [프록시 상태 확인](#proxy-health-checking-v3816) 참조), 프록시의 `status` `dead` 로 설정됩니다.
3. `dead` 는 pool/rotation 확인에서 사용되는 활성 상태 필터가 제외하는 상태 중 하나이므로 범위의 회전(라운드 로빈/랜덤/고정/대기 시간 — 참조 [회전 전략 결정 트리](#rotation-strategy-decision-tree) 참조)은 해당 프록시를 새 요청에 전달하는 것을 즉시 중지합니다. 풀의 다른 프록시는 영향을 받지 않으며 전체 풀은 자동으로 직접 연결로 폴백되지 않습니다 — [4레벨 프록시 시스템](#4-level-proxy-system) 페일클로즈 가드를 참조하세요.
4. 스케줄러는 동일한 간격으로 `dead` 프록시를 계속 검색합니다. 다음번 성공적인 프로브는 `status` `active` 로 다시 뒤집고 수동 재추가가 필요하지 않은 회전 — 에 다시 들어갑니다.

이건 고의로** 옵트인 및 비파괴적** : 기본적으로 스케줄러는 실패만 계산하고 기록하며( `decision.ts` 의 정책 C 참조), `PROXY_AUTO_DISABLE` 별도의 보다 공격적인 `PROXY_AUTO_REMOVE` 플래그의 용도인 — 행을 삭제하지 않습니다. 둘 다 `true` 로 설정되면 `PROXY_AUTO_REMOVE` 승리합니다(삭제될 프록시는 그 사이에 소프트 비활성화를 사용하지 않습니다). 전체 변수 목록은 [환경 구성](../reference/ENVIRONMENT.md) 참조를 확인하세요.

---

> 📖** 관련 문서:**
>
> - [사용자 가이드](../guides/USER_GUIDE.md) — 일반 설정 및 구성 - [API 참조](../reference/API_REFERENCE.md) — 전체 API 문서 - [환경 구성](../reference/ENVIRONMENT.md) — 모든 환경 변수
