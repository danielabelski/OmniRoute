# Compression Engines (한국어)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

OmniRoute 압축은 엔진 계약을 중심으로 구축되었습니다. 모드는 하나의 엔진을 직접 실행하거나(`caveman` 또는 `rtk`) 여러 엔진을 순서대로 실행하는 결정적 스택 파이프라인을 실행할 수 있습니다.

## 모드

| 방법         | 엔진 경로                                                                                | 의도된 입력                                |
| ------------ | ---------------------------------------------------------------------------------------- | ------------------------------------------ |
| `off`        | 없음                                                                                     | 정확한 신속한 보존                         |
| `lite`       | 원시인 라이트 도우미                                                                     | 위험도가 낮은 상시 정리                    |
| `standard`   | 동굴 탐험가                                                                              | 자연어 프롬프트 응축                       |
| `aggressive` | Caveman + history/tool 요약자                                                            | 긴 채팅 세션                               |
| `ultra`      | 원시인 + 가지치기 도우미                                                                 | 컨텍스트 제한 복구                         |
| `rtk`        | RTK                                                                                      | 터미널, 셸, 빌드, 테스트 및 git 출력       |
| `omniglyph`  | OmniGlyph                                                                                | 기본 제공자 와이어의 이미지로서의 컨텍스트 |
| `stacked`    | 관로. 요청 기본값은 `session-dedup -> lite` 입니다. `rtk -> caveman` 는 선택 사항입니다. | 혼합된 도구 로그 및 산문, 최대 절감 효과   |

### OmniGlyph 압축 프로필

`omniglyph` 엔진(패키지 `omniglyph`, 1.4.0 +)은 압축 설정에서 `omniglyph.profile` 통해 전역적으로 설정되거나 스택 파이프라인의 단계 구성을 통해 단계별로 설정된 명명된 의미 프로필을 허용합니다.

| 윤곽          | 경계                                                                                 |
| ------------- | ------------------------------------------------------------------------------------ |
| `aggressive`  | 기본. 게시된 영수증이 — 이미지 시스템, 도구 문서 및 밀집된 기록을 측정한 정책        |
| `balanced`    | 실시간 상태를 기본으로 유지하고, 마지막 8턴을 보호하고, 이전의 닫힌 기록을 접습니다. |
| `coding-safe` | 권한, 도구 스키마 및 라이브 도구 출력을 기본으로 유지하고 마지막 12턴을 보호합니다.  |
| `passthrough` | 변형되지 않은 경로; 엔진이 생략되었습니다                                            |

프로필은** 바닥이 아닌 천장** : 패키지의 `mergeCompressionProfileOptions` 호출자가 손실이 있는 레인을 다시 열도록 허용하지 않으므로 단계별 `preserveSystemPrompt: false` `coding-safe` 에서 시스템 압축을 다시 활성화할 수 없습니다.

이 코드베이스에서 측정됨: `coding-safe` 및 `balanced` `minCompressChars` 최대값으로 높이고 시스템, 도구 스키마 및 도구 결과를 기본으로 유지하므로 기록이 아직 누적되지 않은 세션은 `below_min_chars` 에서 중지되고 엔진은 아무것도 변환하지 않습니다. 이것이 가장 안전한 프로필이 아니라 기본값이 `aggressive` 인 이유입니다.

패키지는 해당 환경 구성에서 자체 모델 범위와 프로필을 확인합니다. OmniRoute 결정을 결코 위임하지 않습니다. 어댑터는 모델 게이트를 패키지의 가장 제한적인 범위에 고정하므로 호스트 환경 설정은 허용 목록의 범위를 좁힐 수만 있고 OmniRoute 의 측정된 수신을 넘어서는 범위를 넓힐 수 없습니다.

## 엔진 레지스트리

레지스트리는 `open-sse/services/compression/engines/registry.ts` 에 있습니다. 엔진은 공유 계약을 노출합니다.

- `id`: `caveman` 또는 `rtk` 와 같은 안정적인 엔진 ID
- `apply(text, config)`: 스택 파이프라인에서 사용되는 레거시 실행 경로
- `compress(input, config)`: 텍스트를 반환하는 기본 실행 경로 + stats
- `getConfigSchema()`: JSON 스키마와 유사한 유효한 구성 형태를 반환합니다.
- `validateConfig(config)`: `{ valid, errors[] }` 반환합니다.

등록은 수락하기 전에 `assertValidEngine()` 및 `validateConfig(defaultConfig)` 호출하는 `registerCompressionEngine(engine)` (또는 고급 사례의 경우 `registerEngine` )를 사용합니다. 런타임에 엔진을 제거하려면 `unregisterCompressionEngine(id)` 사용하십시오.

`strategySelector.ts` 압축이 실행되기 전에 내장 엔진을 등록합니다. 이를 통해 미리보기, 런타임 압축, 스택 모드, 테스트 및 향후 엔진이 동일한 실행 경로를 사용할 수 있습니다.

### MCP 설명 압축(관련)

별도의 레지스트리는 레지스트리 수준 — 에서 MCP 도구 설명 메타데이터를 압축합니다. `open-sse/mcp-server/descriptionCompressor.ts` 및 [MCP-SERVER.md](../frameworks/MCP-SERVER.md) 참조하세요. Caveman 규칙을 재사용하지만 요청 페이로드가 아닌 도구 메타데이터에서 작동합니다.

### 추가 내장 엔진

Caveman, RTK 및 LLMLingua-2 외에도 레지스트리는 여러 특수 무손실/구조적 엔진(스택 파이프라인, 플레이그라운드 및 테스트에서 사용)을 제공합니다.

| 엔진           | ID              | 기능                                                                                                                                            |
| -------------- | --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR            | `ccr`           | Content-Compress-Retrieve(H4): 큰 연속 텍스트 블록을 콘텐츠 주소 지정 참조로 대체하므로 repeated/large 블록이 한 번 전송되고 이후에 참조됩니다. |
| 헤드룸         | `headroom`      | SmartCrusher (H3 + N5): 동종 JSON 배열 페이로드를 열형 `[N rows]` 형식으로 무손실 표 형식으로 압축합니다.                                       |
| 이온화 장치    | `ionizer`       | 매우 큰 동종 블록에 대한 Head/middle/tail 행 샘플링. 생략된 중간 부분을 CCR 콘텐츠 주소 참조로 저장합니다.                                      |
| 세션 중복 제거 | `session-dedup` | 콘텐츠 주소 지정 교차 중복 제거(TokenMizer에서 영감을 받음): 동일한 세션의 이전 차례에서 이미 표시된 텍스트를 제거합니다.                       |

**CCR 검색 프로토콜 명령(#8033):** CCR 요청에서 처음으로 ≥ 1 블록을 대체할 때 엔진은 호출자에게 마커를 가르치는 단일 멱등성 `system` 메시지( `[CCR protocol]` 센티넬로 이어짐)를 앞에 추가합니다. → 도구 계약: `[CCR retrieve hash=<24hex> chars=N]` 마커의 의미, 해시는 그대로 복사해야 한다는 것(모든 24개의 16진수 문자 — 잘못 복사된 해시는 "블록을 찾을 수 없음" 누락의 원인일 수 있음), `[dedup:ref sha=...]` 마커 "도구 호출"이 아니라 "역사를 되돌아보기"를 의미합니다. 메모가 주입됩니다.** 호출자가 광고한 `tools[]` 실제로 `omniroute_ccr_retrieve` 에 도달할 수 있음을 증명할 때만** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — 해당 도구가 없는 일반 OpenAI 호환 호출자는 도달할 수 없는 것을 호출하라는 명령을 결코 받지 않습니다. 멱등성은 삽입하기 전에 센티넬에 대한 메시지 기록을 스캔하여 적용되므로 다중 턴 요청(이전 메시지를 재생함)은 턴당 한 번씩 메모를 쌓지 않습니다.

## 동굴 탐험가

Caveman 모드는 일반적인 산문의 의미론적 압축에 중점을 둡니다.

- 코드 블록, URLs, JSON, 경로 및 구조화된 데이터를 보존합니다.
- 필러, 헤징, 반복되는 문맥 및 장황한 연결 표현을 제거합니다.
- `open-sse/services/compression/rules/` 에서 언어 인식 파일 규칙 팩을 지원합니다.
- 레거시 `standard`, `aggressive` 및 `ultra` 모드를 통해 계속 사용할 수 있습니다.

대시보드 표면은 `Dashboard -> Context & Cache -> Caveman` 입니다.

Caveman 업스트림은 `~75%` 더 적은 출력 토큰, `22-87%` 범위의 벤치마크에서 `65%` 평균 출력 절감 및 `~46%` 입력 압축 도구를 보고합니다. OmniRoute 누적된 prompt/context 절감액을 문서화할 때 Caveman 입력 측 번호를 사용합니다. Caveman 출력 모드는 별도의 응답 동작 기능으로 유지됩니다.

## RTK

RTK 모드는 명령 및 도구 출력에 중점을 둡니다.

- `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, Cargo/Go 테스트, TypeScript/Vite/Webpack 빌드, ESLint, npm audit/installs, Docker 로그, 쉘 `find`/`grep`, 스택 추적 및 일반 로그와 같은 출력 클래스를 감지합니다.
- `open-sse/services/compression/engines/rtk/filters/` 에서 49개의 JSON 필터를 적용합니다.
- RTK 스타일 선언적 파이프라인 지원: ANSI 스트리핑, 대체, 일치 출력 단락, strip/keep 라인, 라인별 잘림, head/tail/max-line 잘림 및 비어 있는 경우 폴백
- `.rtk/filters.json` 의 신뢰 제어 프로젝트 필터와 `DATA_DIR/rtk/filters.json` 의 전역 필터를 지원합니다.
- ANSI 시퀀스, 진행 노이즈, 반복되는 줄 및 도움이 되지 않는 상용구를 제거합니다.
- 실행 가능한 오류, 경고, 요약, 변경된 파일 및 테일 컨텍스트를 보존합니다.
- 인증된 관리 경로를 통해 선택적으로 recovery/debugging 에 대한 수정된 원시 출력을 유지할 수 있습니다.

대시보드 표면은 `Dashboard -> Context & Cache -> RTK` 입니다.

사용자 정의 필터, 신뢰, 확인 및 원시 출력 복구에 대한 운영 세부 사항은 [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md) 에 있습니다.

RTK upstream은 명령 출력 압축에 대한 `60-90%` 절감을 보고합니다. README 예제는 `~118,000` 토큰에서 `~23,900` 또는 `79.7%` 로 저장되는 30분 Claude 코드 세션을 보여줍니다.

## LLMLingua-2 (의미적 가지치기)

LLMLingua-2 모드 수행** 의미론적 토큰 가지치기** 규칙 기반 Caveman 및 RTK 엔진을 보완하는 작은 ONNX 토큰 분류기를 사용하는 산문:

- 비시스템 메시지에서만 문장을 압축합니다. 울타리 코드 블록 및 기타 보존된 구성은 변경되지 않습니다.
- 작업자 스레드에서 `@atjsh/llmlingua-2` 백엔드( `@huggingface/transformers` 통한 ONNX )를 실행하므로 모델 추론이 요청 이벤트 루프를 차단하지 않습니다.
- ~이다** 쌓을 수 있는** (`stackPriority` 35): 스택 파이프라인에서는 구조 엔진(CCR, session-dedup, headroom, Caveman) 이후에 실행되지만 `ultra` 이전에 실행됩니다. 의미 체계 가지치기는 이미 구조적으로 압축된 텍스트 — (예: `rtk -> caveman -> llmlingua` 에 가장 효과적이기 때문입니다.
- **오류 발생 시 페일오픈(fail-open)** (선택적 deps, 작업자 생성, 모델 로드, 추론 또는 시간 초과 누락) → 원본 텍스트는 변경되지 않고 반환되며 오류는 발생하지 않습니다.

엔진 위치: `open-sse/services/compression/engines/llmlingua/`. 대시보드 표면은 `Dashboard -> Context & Cache -> LLMLingua` 입니다.

### 모델

기본 모델은**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, 빠름). 더 높은 정확도** BERT 기반** 모델(`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB)은 엔진 구성 `model` 필드를 통해 사용할 수 있습니다. `@huggingface/transformers` 첫 번째 호출(`modelStore.ts`)에서 선택한 모델을 HuggingFace 허브에서 `${DATA_DIR}/models/llmlingua` 로 느리게 다운로드합니다. `modelPath` 구성 재정의는 대신 로컬 복사본을 가리킵니다(오프라인/에어갭 설치).

### 선택적 종속성 및 주문형 설치

정리 가능한 LLMLingua 런타임 피어 스택은 다음과 같습니다.** 선택 과목** . 두 개의 패키지가 `package.json` 에서 `optionalDependencies` 로 선언되고 유지됩니다.** 외부** 프로덕션 빌드에 따라(`scripts/build/prepublish.ts` 이를 번들로 제공하지 않습니다):

| 패키지               | 버전(핀)  | 메모                                          |
| -------------------- | --------- | --------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`   | 참가 패키지; 다른 사람들을 동료로 선언합니다. |
| `js-tiktoken`        | `^1.0.20` | 토크나이저                                    |

`@huggingface/transformers` 는 `^4.2.0` 에 고정되어 있습니다(로컬 임베딩 경로와 공유되며 독립 실행형 번들로도 추적됩니다). `@atjsh/llmlingua-2@2.0.5` `"^3.5.2 || ^4.0.0"` 와 피어링하므로 Transformers.js v3 및 v4가 모두 지원됩니다. 2.0.4부터 `@atjsh/llmlingua-2` SLM 스택에서 가장 큰 단일 기여자(TensorFlow.js)가 제거된 `@tensorflow/tfjs` 더 이상 필요하지 않습니다. 위의 두 패키지만 정리 가능한 SLM 피어입니다. 표준 `npm install` (dev)는 선택적 종속성이 생략되지 않는 한 자동으로 선택적 스택을 설치합니다.

**온디맨드인 이유:** npm 게시 패키지, 독립형 번들 및 Docker 이미지 배송** 없이** 이 깊이는 슬림함을 유지합니다. 해당 항목이 없으면 작업자의 종속성 게이트( `worker.ts` 의 `@atjsh/llmlingua-2` 해결 프로브)가 실패하고 엔진이** 자동으로 페일오픈(fail-open)** — LLMLingua 선택하면 아무 작업도 수행되지 않습니다(텍스트가 변경되지 않고 반환되고 오류가 기록되지 않음). 정리된 환경에서 활성화하려면 선택적 스택을 설치하십시오.

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

`@tensorflow/tfjs` 제거(2.0.4 +)는 이전에 지배적인 ~ 800 MB 기여자 — 제거합니다. 남은 공간은 transformers.js + onnxruntime-node 런타임과 처음 사용 시 다운로드된 TinyBERT 모델(~ 57 MB)입니다(npm을 통하지 않음).

환경별:

- **개발/ `npm install`** `--omit=optional` (또는 `--no-optional`)를 전달하지 않으면 — 자동으로 설치됩니다. 조치가 필요하지 않습니다.
- **글로벌 npm(`npm i -g omniroute`) / 독립형** — 설치된 패키지 디렉터리 내에서 위의 설치 명령을 실행하거나 선택적 deps를 생략하지 않고 다시 설치하세요.
- **Docker** — 파생된 이미지 레이어에 설치 명령을 추가합니다. 게시된 이미지는 디자인상 슬림하게 제공됩니다.
- **VPS (PM2)** — 앱의 `node_modules` 에 설치한 다음 프로세스를 다시 시작하여 작업자가 게이트를 다시 검색하도록 합니다.
- **Raw Next 독립형(`npm run build` → `.build/next/standalone/server.js`)** — 독립 실행형 추적은 NEITHER 작업자 또는 선택적 deps를 제공하므로 엔진이 자동으로 페일오픈됩니다. `scripts/build/colocate-standalone.mjs` 두 가지를 모두 다시 적용합니다(작업자 esbuild + 선택적인-dep 클로저를 독립 실행형 트리에 적용). 모든 빌드 후에 `postbuild` npm 후크를 통해 자동으로 실행됩니다. Deps가 없을 때 멱등성이 있고 페일소프트(fail-soft)입니다.

**활성 상태인지 확인하세요.** LLMLingua 선택하면 실제 문장이 실제로 줄어들고(엔진이 페일오픈을 중지함) 첫 번째 요청으로 인해 모델이 `${DATA_DIR}/models/llmlingua` 로 다운로드됩니다. 게이트는 의도적으로 `@atjsh/llmlingua-2` — 만 조사합니다. 다른 피어는 ESM 전용이고 `require.resolve` — 존재하는 경우에도 해당 피어를 처리하므로 `import()` 시간에 피어가 실제로 누락된 경우 작업자는 여전히 페일오픈을 수행합니다.

## 누적 파이프라인

스택 모드는 파이프라인 단계를 순서대로 실행합니다. 기본값은 다음과 같습니다.

```txt
rtk -> caveman
```

프롬프트가 명령 출력과 인간 또는 보조 산문을 결합하는 코딩 에이전트 세션에 이 기능을 사용하세요. RTK 먼저 시끄러운 도구 로그를 줄이고 Caveman은 나머지 자연어를 압축합니다.

파이프라인 단계는 압축 설정에서 또는 압축 콤보를 통해 `stackedPipeline` 로 구성됩니다.

두 엔진 모두 동일한 적격 탑재량을 줄이면 비용 절감 효과는 다음과 같습니다.

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## MCP 접근성 트리 필터

MCP 접근성 트리 스마트 필터는 MCP 에서 실행되는 실행 후 압축 계층입니다.** 도구 결과** , 프롬프트나 컨텍스트가 아닙니다. 이는 Playwright, 컴퓨터 사용 및 브라우저 자동화 MCP 서버와 같은 도구에서 반환된 자세한 접근성 트리 및 브라우저 스냅샷 페이로드를 대상으로 합니다.

### 기능

1. **소음 제거** — 빈 generic/text 항목(`- generic:`, `- text: ""`)을 제거합니다.
2. **형제 붕괴** — ≥ `collapseThreshold` (기본값 30) 연속 라인이 구조적 반복인 경우 이를 첫 번째 `collapseKeepHead` (기본값 10) 라인으로 축소합니다 + 개수 요약 + 마지막 `collapseKeepTail` (기본값 5) 라인
3. **참조 보존** Playwright/computer-use 에 필요한 — `[ref=eXX]` 앵커는 절대 건드리지 않습니다.
4. **하드 잘림** — 축소 후에도 텍스트가 여전히 `maxTextChars` (기본값 50,000)를 초과하는 경우 에이전트가 계속 작업할 수 있도록 탐색 힌트로 잘립니다.

### 엔진 위치

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### 구성

전역 설정에서 `compression.mcpAccessibility` 에 의해 제어됩니다(마이그레이션 056). 기본 구성:

```json
{
  "enabled": true,
  "maxTextChars": 50000,
  "collapseThreshold": 30,
  "collapseKeepHead": 10,
  "collapseKeepTail": 5,
  "minLengthToProcess": 2000
}
```

필터는 `type` 가 `"text"` 이고 길이가 `minLengthToProcess` 초과하는 도구 결과 페이로드에만 적용됩니다. 프롬프트 압축이나 요청 페이로드에는 영향을 미치지 않습니다.

### 예상 절감액

페이지 복잡성에 따라 브라우저 스냅샷 도구 결과의 60~80%. 축소 알고리즘은 줄 수에서 O(n)이며 무시할 수 있는 대기 시간을 추가합니다.

### 이 필터와 위의 압축 엔진 비교

| 측면      | 원시인 / RTK / 스택    | MCP 접근성 필터                        |
| --------- | ---------------------- | -------------------------------------- |
| 목표      | 요청 프롬프트/컨텍스트 | MCP 도구 결과                          |
| 방아쇠    | 압축 모드 설정         | `compression.mcpAccessibility.enabled` |
| 범위      | 모든 SSE 메시지        | 도구 결과만                            |
| 참조 앵커 | N/A                    | 무조건 보존                            |

---

## 압축 콤보

압축 콤보는 라우팅 콤보에 할당할 수 있는 압축 프로필로 명명됩니다.

- `compression_combos`: 모드, 파이프라인, RTK 구성, 언어 구성 및 기본 마커를 저장합니다.
- `compression_combo_assignments`: 압축 콤보를 라우팅 콤보에 매핑합니다.
- 런타임 통합은 일반 콤보 재정의 전에 할당된 압축 콤보를 해결합니다.
- 분석에는 `compression_combo_id` 및 `engine` 포함됩니다.

대시보드 표면: `Dashboard -> Context & Cache -> Compression Combos`.

## 전제조건/운영자 가이드(CCR & session-dedup)

CCR (`ccr`) 및 `session-dedup` 텍스트를 바꾸거나 삭제하고** 채점자** 뒤에. 이 섹션은 클라이언트 연결, 두 마커 읽기, 누락된 콘텐츠 검색 또는 진단을 위한 운영자 참조입니다. 각 엔진의 메커니즘은 위에 설명되어 있습니다. 이것은 "어떻게 실행합니까?" 레이어입니다.

### 전송 및 엔드포인트

CCR 도구를 노출하는 MCP 서버는 세 가지 방법으로 접근할 수 있습니다. 기본 기본 URL 는 `http://localhost:20128` (`OMNIROUTE_BASE_URL`)입니다.

| 수송                                    | URL / 명령                              | 메모                                                                                                                                                   |
| --------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 스트리밍 가능한 HTTP (클라이언트, 권장) | `http://localhost:20128/api/mcp/stream` | 현재 MCP 클라이언트가 대화하는 엔드포인트입니다.                                                                                                       |
| 레거시 SSE 싱글톤                       | `http://localhost:20128/api/mcp/sse`    | 이전 싱글톤 전송. 그것** 닫는다** 스트리밍 가능한 세션; `/api/mcp/stream` 에 대해 `streamable-http` 클라이언트를 사용하세요. 이 클라이언트는 아닙니다. |
| 스튜디오                                | `omniroute --mcp`                       | 프로세스를 생성하는 IDE MCP 구성의 경우. `--dev` 플래그가 없습니다. `omniroute --mcp` 는 stdio 진입점입니다.                                           |

### 스토리지 계층(다시 시작해도 유지되는 계층)

CCR 는** 2층** 메모리 전용이 아닌 저장:

- **핫 인메모리 계층** — 블록당 한도 2 MiB, 주체당 16 MiB, 전역 64 MiB. 항목은 기본적으로 24시간 TTL (최대 7일)로 설정됩니다. 메모리에서 전체 MCP 검색은 256 KiB 로 제한됩니다. 더 큰 것은 여전히 ranged/grep 모드를 통해 접근할 수 있습니다.
- **내구성이 뛰어난 SQLite 계층** ( 기본적으로 `ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, on) — 인 메모리 계층을 지원하므로 블록은 LRU 제거, 재시작 또는 다른 인스턴스에 대한 검색 착륙에서 살아남습니다. 행은 블록의 TTL 유지하므로 해당 TTL 지나는 블록은 두 계층 모두에서 사라집니다.

세 명의 가드가 내구성 계층 — 제한적으로 유지합니다. 다음과 같은 경우 블록은 메모리 전용으로 유지됩니다.

1. 블록이 끝났어** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. 런타임은 클라우드 런타임입니다(로컬 디스크 없음).
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

따라서 "블록이 사라졌습니다"는 포괄적인 재시작 이야기가 아닙니다. 클라우드가 아닌 로컬 런타임의 sub-512 KB 블록은 해당 TTL 소진될 때까지 내구성 계층을 통해 재시작 후에도 유지됩니다. 변수에 대한 [환경 참조를](../reference/ENVIRONMENT.md) 참조하세요.

### 두 개의 마커

| 채점자                                | 의미                                                                                                                                      | 모델이 해야 할 일                                                                                                                                                                                   |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | 큰 블록이 콘텐츠 주소로 저장되었습니다.                                                                                                   | 다음과 같이 `omniroute_ccr_retrieve` 에 전화하세요.** 24-16진수 해시가 그대로 복사됨** 원본 텍스트를 다시 얻으려면.                                                                                 |
| `[dedup:ref sha=…]`                   | `session-dedup` 동일한 세션의 이전 단계에서 이미 전송된 텍스트를 삭제했습니다. 이것은** 의도적인 뒤돌아보기** , 손실이나 오류가 아닙니다. | 하다** ~ 아니다** 어떤 도구를 호출하고 수행** ~ 아니다** 그것을 "재구성"하려고 노력하십시오. 텍스트의 첫 번째 항목은 정식 사본입니다. 현재 턴은 다시 작성되지 않으며 이후 턴에서 중복이 제거됩니다. |

`[dedup:ref]` 룩백은 의도적인 프로토콜 결정입니다. — 사전 전송 재구성이 없습니다. "이 정확한 텍스트는 이 세션 초기에 이미 전송되었습니다."로 처리하세요.

### 클라이언트 전제조건

- **키(stdio):** stdio 호출자는 요청별 ID를 전달하지 않으므로 `OMNIROUTE_API_KEY` ( MCP 서버의 `env` 에 설정됨)로 인증합니다. 이것이 없으면 호출자는 익명이 되며 주체가 필요한 도구의 성능이 저하될 수 있습니다.
- **`tools[]` 는 주입 전제조건입니다.** CCR 검색 프로토콜 명령(#8033)이 삽입됩니다.** 오직** 요청의 광고된 `tools[]` 클라이언트가 실제로 `omniroute_ccr_retrieve` 에 도달할 수 있음을 증명할 때. 일치는 구분 기호(`__`, `.`, `/`, `:`)로 묶인 후행 세그먼트 일치입니다. — 절대 하위 문자열 — 아니므로 `mcp__gateway__omniroute_ccr_retrieve` 과 같은 네임스페이스 이름은 여전히 계산됩니다. `tools[]` 이 없거나 일치하지 않는다는 것은 의도적으로 명령어가 주입되지 _않았다_는 것을 의미합니다.
- **`codemode:false` (OpenCode 클라이언트).** OpenCode 기본적으로 코드 모드로 설정되어 있으며, 기본 도구만 모델에 광고하고** 그렇지 않다** MCP 도구를 기본 `tools[]` 목록에 추가하세요. `omniroute_ccr_*` 도구가 보급되도록 MCP 서버 항목에 `codemode: false` 설정합니다. 이것은** 고객** 설정은 OmniRoute 설정이 아닙니다. 아직 CCR 명령어가 삽입되지 않았습니다. OpenCode 도구에 `<server>_<tool>` 이름을 지정하므로 `omniroute` 이라는 서버는 `omniroute_omniroute_ccr_retrieve` 노출하고 `_` 일치하는 구분 기호 중 하나가 아닙니다.
- **교장.** 저장 및 검색은 인증된 주체별로( API 키별로) 격리됩니다. 키는 자체 블록만 볼 수 있습니다.

### 도구별 범위

범위가 좁은 HTTP/SSE 호출자에 대해서는 범위 적용이 항상 켜져 있습니다. `omniroute_` CCR 도구에는 다음이 필요합니다.

| 도구                     | 범위                |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

누락된 범위는 다음을 반환합니다.**MCP 도구 오류 결과** (`isError: true`, HTTP 403 — 아님 `403 LOCAL_ONLY` 는 별도의 루프백 경로 보호 인증입니다.): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` 최소 원격 키는 `mcp:connect` ( `/api/mcp/` 로컬 전용 분할 승인)와 필요한 특정 read/write 범위를 보유할 수 있습니다.

### 클라이언트 매트릭스

| 고객           | 수송                               | 사용할 구성                                                                                                                                                                                                                       | `tools[]` 광고했어? (→ CCR 명령어 삽입됨)                                                                                                                                           |
| -------------- | ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Claude 코드    | 스트리밍 가능-http                 | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                 | 예 — MCP 가능; 주입.                                                                                                                                                                |
| Cursor / Cline | `stdio`** 또는** `streamable-http` | stdio: `env` 에 `OMNIROUTE_API_KEY` 있는 `omniroute --mcp` ; 또는 `http://localhost:20128/api/mcp/stream` 를 가리키는 원격 MCP 항목( [설정 가이드 → MCP 클라이언트 구성](../guides/SETUP_GUIDE.md#mcp-client-configuration) 참조) | 예 — `omniroute_ccr_*` 도구를 광고합니다.                                                                                                                                           |
| OpenCode       | 스트리밍 가능-http                 | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, 플러스 `codemode: false`                                                                                                                                | `codemode: false` 로만 광고되는 도구; `omniroute_omniroute_ccr_retrieve` 일치하지 않기 때문에 명령이 여전히 주입되지 않습니다( [클라이언트 전제 조건](#client-prerequisites) 참조). |
| OpenAI 호환    | OpenAI 호환 HTTP (채팅 완료)       | OpenAI 호환 엔드포인트에 대한 표준 채팅 완료 클라이언트                                                                                                                                                                           | **절대** 일반 OpenAI 호환 호출자 — 도구를 호출하라는 지시가 전혀 전달되지 않으며 명령도 주입되지 않습니다.                                                                          |

### 검색 제한 및 페이지 매기기

MCP 도구 텍스트 결과는 `mcpAccessibility.maxTextChars` 주위에서 잘립니다(기본값 `50000`). 블록의 `full` 검색은 256 KiB — 로 제한됩니다.** 무제한의 전체 검색이 없습니다.** . 블록의 `chars=N` 큰 경우 전체를 가져오는 대신 페이징하세요.

- 경험 법칙:**`chars > 40000` → `mode` 사용하세요** , 결코 꽉 차 있지 않습니다.
- `mode:"grep"` — regex `pattern` 한 줄씩 일치하며 최대 1,000개의 일치하는 줄(`unique: true` 반복 삭제), "필요한 한 줄 찾기"에 가장 저렴합니다.
- `mode:"lines"` — 1 인덱스 라인 범위; `start` 와 `end` 모두 필요합니다.
- `mode:"head"` / `mode:"tail"` — first/last `n` 라인.
- `mode:"stats"` — 본문 없이 행, 문자 및 바이트 수를 계산합니다.

`start`/`end` 와 함께 `mode:"lines"` 사용하면 한 번에 모든 것을 요청하는 대신 페이지 단위로 긴 블록을 탐색할 수 있습니다.

### 도구 이름 지정

검색 도구의 이름은 현재 `omniroute_ccr_retrieve` 입니다( `omniroute_` 접두사는 서버 간 이름 충돌에 대한 오래된 해결 방법입니다). 더 깔끔한 경계 접미사 도구 이름과 MCP JSON 결과 잘린 중간 문자열에 대한 수정 사항은 업스트림 후속 조치로 추적됩니다. 이 페이지에는 현재 제공된 동작만 문서화되어 있습니다.

### 세션 수명주기

스트리밍 가능한 HTTP 세션이 유휴 상태가 되면 서버가 해당 세션을 확보합니다. 유휴 창은 `MCP_SESSION_IDLE_MS` 상수입니다(하드코드된 값이 아닌 이름으로 참조되므로 이 페이지가 변경될 때 표류하지 않습니다). 유휴 세션의 증상은 `Unknown Mcp-Session-Id` — 가 있는 HTTP 404입니다. 해결 방법은 세션을 다시 연결하거나 다시 시작하는 것입니다.** ~ 아니다** 키를 회전하거나, 범위를 변경하거나, 도구 이름을 바꾸려면

## API 표면

| 노선                                   | 목적                                          |
| -------------------------------------- | --------------------------------------------- |
| `/api/settings/compression`            | 전역 압축 설정( `mcpAccessibility` 구성 포함) |
| `/api/compression/preview`             | 모든 압축 모드 미리보기                       |
| `/api/compression/language-packs`      | 사용 가능한 Caveman 언어 팩 목록              |
| `/api/context/caveman/config`          | 원시인 설정 별칭                              |
| `/api/context/rtk/config`              | RTK 기본값 및 설정                            |
| `/api/context/rtk/filters`             | RTK 필터 카탈로그                             |
| `/api/context/rtk/test`                | RTK preview/test 엔드포인트                   |
| `/api/context/rtk/raw-output/[id]`     | 인증된 수정된 원시 출력 복구                  |
| `/api/context/combos`                  | 압축 콤보 CRUD                                |
| `/api/context/combos/[id]/assignments` | 라우팅 콤보 할당 CRUD                         |
| `/api/context/analytics`               | 압축 분석 별칭                                |

관리 경로에는 관리 인증 또는 API 키 정책 확인이 필요합니다.

## MCP 도구

압축은 다섯 가지 MCP 도구를 노출합니다.

| 도구                                | 범위                | 목적                           |
| ----------------------------------- | ------------------- | ------------------------------ |
| `omniroute_compression_status`      | `read:compression`  | 설정, 분석, 캐시 통계          |
| `omniroute_compression_configure`   | `write:compression` | 전역 설정 업데이트             |
| `omniroute_set_compression_engine`  | `write:compression` | 모드 설정 및 선택적 파이프라인 |
| `omniroute_list_compression_combos` | `read:compression`  | 압축 콤보 나열                 |
| `omniroute_compression_combo_stats` | `read:compression`  | combo/engine 분석 읽기         |

## 범위 및 제외

**임베딩은 압축되지 않습니다.** `open-sse/handlers/embeddings.ts` 압축 엔진 — 를 호출하지 않으며 request/response 본체는 그대로 실행자에게 바로 전달됩니다. 이는 오늘날 구조적이며(임베딩 및 채팅 완료는 분리된 핸들러입니다) 런타임 검사는 아니지만 이는 #8034 의 벡터 왜곡 문제가 임베딩 경로에 노출 표면이 없음을 의미합니다.

**Per-model/endpoint 제외 필터(#8034).** 채팅 완료를 위해 운영자는 절대 압축해서는 안 되는 모델 ID/ `provider/model` 대상의 이름을 지정할 수 있습니다. — 는 나중에 압축이 임베딩 인접 경로에 더 가깝게 연결되는 경우 유용하며 일반적으로 바이트 단위의 정확한 프롬프트가 중요한 모든 모델(결정론적 평가, 캐시에 민감한 접두사 등)에 유용합니다.

- 설정 필드: 전역 압축 구성(`GET`/`PUT /api/settings/compression`)의 `exclusions?: string[]`, 기존 `key_value` 압축 네임스페이스(`src/lib/db/compression.ts`)를 통해 유지됨 — 새 테이블 없음.
- 대시보드 탭:** 대시보드 → 압축 → 제외** (`/dashboard/compression/exclusions`).
- 패턴 구문: `*` 는 유일한 와일드카드입니다. 패턴의 다른 모든 정규식 메타 문자는 일치하기 전에 이스케이프되므로 `gpt-5.6` 리터럴 문자열에만 일치하며 `gpt-5x6` (ReDoS 안전, 경계, 중첩 수량자 없음)는 일치하지 않습니다. 패턴은 기본 모델 ID와 `provider/model` 복합 — `gpt-5-6`, `openai/gpt-5-6` 및 `openai/*` 모두에 대해 대소 문자를 구분하지 않고 일치하며 `*` 만으로는 모든 모델을 제외합니다.
- 일치: `open-sse/services/compression/exclusions.ts` 의 `isCompressionExcluded()` / `normalizeCompressionExclusions()`. `chatCore.ts` 압축 설정을 확인한 후 바로 제외된 대상을 확인합니다.** 엔진이 작동하기 전에** , 전역적으로 비활성화된 압축과 정확히 일치하는 항목을 처리합니다 — 요청 본문은 바이트와 동일하다는 것이 증명됩니다. 건너뛰기는 분석 가시성을 위해 `writeCompressionSkip(..., "excluded")` 통해 기록됩니다.
- 기본값(empty/absent 목록):#8034 이전 동작과 동일합니다. — 아무것도 제외되지 않습니다.

## 알려진 제한사항

- **LLMLingua-2 (SLM)에는 함께 배치된 선택적 deps가 필요합니다.** 작업자는 `@atjsh/llmlingua-2` + 피어가 `dist/node_modules` 에 같은 위치에 있는 경우에만 프로덕션 빌드에서 실행됩니다( `scripts/build/colocateOptionals.mjs`, #4286 참조). 해당 항목이 없으면 엔진 페일오픈이 발생합니다(원본 텍스트 반환). 작업자 해상도는 더 이상 `import.meta.url` 에 의존하지 않습니다(독립형 번들에서는 종료됨). — 는 런타임 cwd / `argv[1]` 에 고정됩니다.
- **Caveman 언어 팩 `de` / `fr` / `ja` 는 부분적입니다.** 그들은 `context` + `filler` + `structural` 규칙을 제공하지만 `dedup` / `ultra` 팩은 제공하지 않으므로 해당 언어의 경우 `ultra` 강도는 `full` 보다 강력하지 않습니다(그들은 자체 규칙만 사용합니다 — 영어 `dedup`/`ultra` 규칙으로 자동 대체되지 않아 외국 텍스트가 엉망이 됩니다). `en` / `es` / `id` / `pt-BR` 완료되었습니다. 부분 팩에 대한 `dedup.json` + `ultra.json` 의 기여를 환영합니다.
- **누적 원격 분석은 압축된 엔진만 나열합니다.** 엔진이 실행되었지만 절감 효과가 0%인 스택 파이프라인 단계는 `stats:null` 반환하므로 건너뛴 단계와 구별할 수 없는 `engineBreakdown` — 에 표시되지 않습니다. "런, 0%"를 "건너뛰기"와 구별하려면 분석 모델 변경이 필요하므로 연기됩니다.

## 확인

이 영역의 집중 게이트는 다음과 같습니다.

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
