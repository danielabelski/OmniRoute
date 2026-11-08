# Compression Engines (Português (Brasil))

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

A compactação OmniRoute é construída em torno de contratos de mecanismo. Um modo pode executar um mecanismo diretamente (`caveman` ou `rtk`) ou um pipeline empilhado determinístico que executa vários mecanismos em ordem.

## Modos

| Modo         | Caminho do motor                                                                          | Entrada pretendida                                       |
| ------------ | ----------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| `off`        | nenhum                                                                                    | Preservação imediata e exata                             |
| `lite`       | Ajudantes leves do homem das cavernas                                                     | Limpeza sempre ativa de baixo risco                      |
| `standard`   | Homem das cavernas                                                                        | Condensação imediata em linguagem natural                |
| `aggressive` | Resumidores do homem das cavernas + history/tool                                          | Longas sessões de bate-papo                              |
| `ultra`      | Ajudantes de poda do homem das cavernas +                                                 | Recuperação de limite de contexto                        |
| `rtk`        | RTK                                                                                       | Terminal, shell, compilação, teste e saída git           |
| `omniglyph`  | OmniGlyph                                                                                 | Contexto como imagem na conexão do provedor nativo       |
| `stacked`    | Gasoduto. O padrão da solicitação é `session-dedup -> lite`. `rtk -> caveman` é opcional. | Registros e prosa de ferramentas mistas, economia máxima |

### perfis de compactação OmniGlyph

O mecanismo `omniglyph` (pacote `omniglyph`, 1.4.0 +) aceita um perfil semântico nomeado, definido globalmente por meio de `omniglyph.profile` nas configurações de compactação ou por etapa por meio da configuração de etapa do pipeline empilhado:

| Perfil        | Limite                                                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Padrão. A política dos recibos publicados mediu o sistema de imagens —, documentos de ferramentas e histórico denso |
| `balanced`    | Mantém o estado ativo nativo, protege os últimos 8 turnos, colapsa o histórico fechado mais antigo                  |
| `coding-safe` | Mantém autoridade, esquemas de ferramentas e saída de ferramentas em tempo real, protegendo os últimos 12 turnos    |
| `passthrough` | Rotas sem transformação; o motor é ignorado                                                                         |

O perfil é um** teto, não um chão** : `mergeCompressionProfileOptions` no pacote se recusa a permitir que um chamador substitua a reabertura de uma pista com perdas que o perfil fechou, portanto, um `preserveSystemPrompt: false` por etapa não pode reativar a compactação do sistema em `coding-safe`.

Medido nesta base de código: `coding-safe` e `balanced` elevam `minCompressChars` ao máximo e mantêm o sistema, os esquemas de ferramentas e os resultados das ferramentas nativos, de modo que uma sessão que não acumulou histórico ainda pare em `below_min_chars` e o mecanismo não transforme nada. É por isso que o padrão é `aggressive` em vez do perfil mais seguro.

O pacote resolve seu próprio escopo e perfil de modelo a partir da configuração de seu ambiente. OmniRoute nunca delega a decisão: o adaptador fixa a porta do modelo ao escopo mais restritivo do pacote, de modo que as configurações do ambiente host podem apenas restringir a lista de permissões, nunca ampliá-la além dos recibos medidos de OmniRoute.

## Registro do motor

O registro reside em `open-sse/services/compression/engines/registry.ts`. Os mecanismos expõem um contrato compartilhado:

- `id`: ID de mecanismo estável, como `caveman` ou `rtk`
- `apply(text, config)`: caminho de execução legado usado por pipelines empilhados
- `compress(input, config)`: caminho de execução primário retornando texto + stats
- `getConfigSchema()`: retorna o formato do esquema JSON da configuração válida
- `validateConfig(config)`: retorna `{ valid, errors[] }`

O registro usa `registerCompressionEngine(engine)` (ou `registerEngine` para casos avançados), que chama `assertValidEngine()` e `validateConfig(defaultConfig)` antes de aceitar. Use `unregisterCompressionEngine(id)` para remover um mecanismo em tempo de execução.

`strategySelector.ts` registra os mecanismos integrados antes da execução da compactação. Isso permite que a visualização, a compactação de tempo de execução, o modo empilhado, os testes e os mecanismos futuros usem o mesmo caminho de execução.

### compactação de descrição MCP (relacionado)

Um registro separado compacta os metadados de descrição da ferramenta MCP no nível do registro — consulte `open-sse/mcp-server/descriptionCompressor.ts` e [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Ele reutiliza as regras do Caveman, mas opera com base em metadados de ferramentas, e não em cargas úteis de solicitação.

### Motores integrados adicionais

Além de Caveman, RTK e LLMLingua-2, o registro fornece vários mecanismos estruturais/sem perdas especializados (usados por pipelines empilhados, playground e testes):

| Motor                   | Eu ia           | O que isso faz                                                                                                                                                                                                    |
| ----------------------- | --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR                     | `ccr`           | Content-Compress-Retrieve (H4): substitui grandes blocos de texto contíguos por referências endereçadas ao conteúdo, de forma que os blocos repeated/large sejam enviados uma vez e referenciados posteriormente. |
| altura livre            | `headroom`      | SmartCrusher (H3 + N5): compactação tabular sem perdas de cargas úteis de array JSON homogêneas em um formato `[N rows]` colunar.                                                                                 |
| ionizador               | `ionizer`       | amostragem de linha Head/middle/tail para blocos homogêneos muito grandes, armazenando o meio elidido como uma referência CCR endereçada ao conteúdo.                                                             |
| desduplicação de sessão | `session-dedup` | Desduplicação de turnos cruzados endereçado ao conteúdo (inspirado no TokenMizer): elimina o texto já visto em turnos anteriores da mesma sessão.                                                                 |

**Instrução do protocolo de recuperação CCR (#8033):** na primeira vez CCR substitui o bloco ≥ 1 em uma solicitação, o mecanismo acrescenta uma mensagem `system` única e idempotente (iniciando com o sentinela `[CCR protocol]` ) ensinando ao chamador o contrato da ferramenta → marcador: o que um marcador `[CCR retrieve hash=<24hex> chars=N]` significa, que o hash deve ser copiado literalmente (todos os 24 caracteres hexadecimais hashes — mal copiados são a causa provável de falhas de "bloco não encontrado"), e que um marcador `[dedup:ref sha=...]` significa "olhar para trás em histórico", não "chame a ferramenta". A nota é injetada** somente quando o `tools[]` anunciado pelo chamador provar que ele pode realmente alcançar `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — um chamador simples compatível com OpenAI sem essa ferramenta nunca recebe uma instrução para chamar algo que não pode alcançar. A idempotência é reforçada verificando o histórico de mensagens em busca do sentinela antes de injetar, de modo que solicitações multi-turno (que reproduzem mensagens anteriores) não empilhem a nota uma vez por turno.

## Homem das cavernas

O modo Caveman concentra-se na condensação semântica da prosa normal:

- preserva blocos de código, URLs, JSON, caminhos e dados estruturados
- remove preenchimento, cobertura, contexto repetido e fraseado conectivo detalhado
- suporta pacotes de regras de arquivos com reconhecimento de idioma no `open-sse/services/compression/rules/`
- permanece disponível através dos modos herdados `standard`, `aggressive` e `ultra`

A superfície do painel é `Dashboard -> Context & Cache -> Caveman`.

O upstream do Caveman relata `~75%` menos tokens de saída, economia média de produção `65%` em benchmarks com um intervalo `22-87%` e uma ferramenta de compactação de entrada `~46%`. OmniRoute usa o número do lado de entrada do Caveman ao documentar economias prompt/context empilhadas; O modo de saída Caveman continua sendo um recurso de comportamento de resposta separado.

## RTK

O modo RTK concentra-se na saída de comandos e ferramentas:

- detecta classes de saída como `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, testes Cargo/Go, compilações TypeScript/Vite/Webpack, ESLint, npm audit/installs, logs Docker, shell `find`/`grep`, rastreamentos de pilha e logs genéricos
- aplica 49 filtros JSON do `open-sse/services/compression/engines/rtk/filters/`
- suporta o pipeline declarativo estilo RTK: remoção ANSI, substituição, curto-circuito de saída correspondente, linhas strip/keep, truncamento por linha, truncamento head/tail/max-line e fallback on-empty
- suporta filtros de projeto confiáveis em `.rtk/filters.json` e filtros globais em `DATA_DIR/rtk/filters.json`
- remove sequências ANSI, ruído de progresso, linhas repetidas e clichês inúteis
- preserva falhas acionáveis, avisos, resumos, arquivos alterados e contexto final
- opcionalmente, pode reter a saída bruta editada para recovery/debugging por meio de rotas de gerenciamento autenticadas

A superfície do painel é `Dashboard -> Context & Cache -> RTK`.

Detalhes operacionais para filtros personalizados, confiança, verificação e recuperação de saída bruta estão disponíveis em [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream relata economia de `60-90%` para compactação de saída de comando. Seu exemplo README mostra uma sessão de código Claude de 30 minutos indo de tokens `~118,000` para `~23,900` ou `79.7%` salvos.

## LLMLingua-2 (poda semântica)

modo LLMLingua-2 executa** poda de token semântico** em prosa usando um pequeno classificador de token ONNX, complementando os mecanismos Caveman e RTK baseados em regras:

- compacta a prosa apenas em mensagens que não são do sistema; blocos de código protegidos e outras construções preservadas nunca são alteradas
- executa o back-end `@atjsh/llmlingua-2` (ONNX via `@huggingface/transformers`) em um thread de trabalho, para que a inferência do modelo nunca bloqueie o loop de eventos de solicitação
- é** empilhável** (`stackPriority` 35): em um pipeline empilhado, ele é executado após os mecanismos estruturais (CCR, session-dedup, headroom, Caveman), mas antes de `ultra`, uma vez que a poda semântica é mais eficaz em texto já compactado estruturalmente — por exemplo `rtk -> caveman -> llmlingua`
- **fail-opens em qualquer erro** (faltando dependências opcionais, geração de trabalhadores, carregamento de modelo, inferência ou tempo limite) → o texto original é retornado inalterado, nunca um erro

Localização do motor: `open-sse/services/compression/engines/llmlingua/`. A superfície do painel é `Dashboard -> Context & Cache -> LLMLingua`.

### Modelos

O modelo padrão é**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, rápido). Uma maior precisão** Base BERT** modelo (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) está disponível através do campo `model` de configuração do mecanismo. `@huggingface/transformers` baixa lentamente o modelo selecionado do HuggingFace Hub para `${DATA_DIR}/models/llmlingua` na primeira chamada (`modelStore.ts`); uma substituição de configuração `modelPath` aponta para uma cópia local (instalações off-line/air-gapped).

### Dependências opcionais e instalação sob demanda

A pilha de pares de tempo de execução LLMLingua prundível é** opcional** . Dois pacotes são declarados como `optionalDependencies` em `package.json` e mantidos** externo** pela compilação de produção (`scripts/build/prepublish.ts` não os agrupa):

| Pacote               | Versão (pino) | Notas                                           |
| -------------------- | ------------- | ----------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`       | Pacote de entrada; declara os outros como pares |
| `js-tiktoken`        | `^1.0.20`     | Tokenizador                                     |

`@huggingface/transformers` é fixado em `^4.2.0` (compartilhado com o caminho de embeddings local e também rastreado no pacote independente); `@atjsh/llmlingua-2@2.0.5` peers nele com `"^3.5.2 || ^4.0.0"`, portanto, tanto Transformers.js v3 quanto v4 são suportados. Desde a versão 2.0.4, `@atjsh/llmlingua-2` não requer mais `@tensorflow/tfjs`, o que removeu o maior contribuidor único (TensorFlow.js) da pilha SLM. Apenas os dois pacotes acima são pares SLM prudáveis. Um `npm install` (dev) padrão instala a pilha opcional automaticamente, a menos que dependências opcionais sejam omitidas.

**Por que sob demanda:** o pacote publicado pelo npm, o pacote independente e o envio da imagem Docker** sem** essas dependências para permanecerem magras. Quando eles estão ausentes, o portão de dependência do trabalhador (um teste `@atjsh/llmlingua-2` resolve em `worker.ts`) falha e o mecanismo** falha abre silenciosamente** — selecionando LLMLingua torna-se autônomo (texto retornado inalterado, nenhum erro registrado). Para ativá-lo em um ambiente limpo, instale a pilha opcional:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

A remoção `@tensorflow/tfjs` (2.0.4 +) elimina o contribuidor ~ 800 MB anteriormente dominante — o espaço restante são os tempos de execução transformers.js + onnxruntime-node, mais o modelo TinyBERT (~ 57 MB) baixado no primeiro uso (não via npm).

Por ambiente:

- **Dev/ `npm install`** — instalado automaticamente, a menos que você passe `--omit=optional` (ou `--no-optional`). Nenhuma ação necessária.
- **Npm global (`npm i -g omniroute`)/autônomo** — execute o comando de instalação acima dentro do diretório do pacote instalado ou reinstale sem omitir deps opcionais.
- **Docker** — adicione o comando de instalação em uma camada de imagem derivada; a imagem publicada é elegante por design.
- **VPS (PM2)** — instale no `node_modules` do aplicativo e reinicie o processo para que o trabalhador teste novamente o portão.
- **Raw Próximo autônomo (`npm run build` → `.build/next/standalone/server.js`)** — o rastreamento independente envia NEITHER o trabalhador nem as dependências opcionais, de modo que o mecanismo falha silenciosamente. `scripts/build/colocate-standalone.mjs` reaplica ambos (worker esbuild + opcional-dep encerramento na árvore autônoma); ele é executado automaticamente por meio do gancho `postbuild` npm após cada compilação. Idempotente, anti-falha quando as dependências estão ausentes.

**Verifique se está ativo:** com LLMLingua selecionado, a prosa real realmente diminui (o mecanismo para de abrir com falha) e a primeira solicitação aciona o download do modelo em `${DATA_DIR}/models/llmlingua`. O portão testa intencionalmente apenas `@atjsh/llmlingua-2` — os outros pares são apenas ESM e `require.resolve` lança sobre eles mesmo quando — está presente, de modo que o trabalhador ainda falha na abertura se algum par estiver realmente faltando no momento `import()`.

## Pipelines empilhados

O modo empilhado executa as etapas do pipeline em ordem. O padrão é:

```txt
rtk -> caveman
```

Use isto para sessões do agente de codificação em que um prompt combina a saída do comando com prosa humana ou assistente. RTK reduz primeiro os logs de ferramentas barulhentos e, em seguida, o Caveman compacta a linguagem natural restante.

As etapas do pipeline são configuradas com `stackedPipeline` nas configurações de compactação ou por meio de combos de compactação.

Quando ambos os motores reduzem a mesma carga útil elegível, a economia aumenta:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## Filtro de árvore de acessibilidade MCP

O filtro inteligente de árvore de acessibilidade MCP é uma camada de compactação pós-execução que roda em MCP** resultados da ferramenta** , não em prompts ou contexto. Ele tem como alvo as cargas detalhadas da árvore de acessibilidade e do instantâneo do navegador retornadas por ferramentas como Playwright, uso do computador e servidores MCP de automação do navegador.

### O que isso faz

1. **Remoção de ruído** — remove entradas generic/text vazias (`- generic:`, `- text: ""`)
2. **Colapso de irmão** — quando ≥ `collapseThreshold` (padrão 30) linhas consecutivas são repetições estruturais, recolhe-as nas primeiras linhas `collapseKeepHead` (padrão 10) + um resumo de contagem + as últimas linhas `collapseKeepTail` (padrão 5)
3. **Preservação de referência** As âncoras — `[ref=eXX]` exigidas pelo Playwright/computer-use nunca são tocadas
4. **Truncamento rígido** — se o texto após o recolhimento ainda exceder `maxTextChars` (padrão 50.000), será truncado com uma dica de navegação para que o agente possa continuar trabalhando

### Localização do motor

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Configuração

Controlado por `compression.mcpAccessibility` em configurações globais (migração 056). Configuração padrão:

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

O filtro é aplicado apenas a cargas de resultado de ferramenta cujo `type` é `"text"` e cujo comprimento excede `minLengthToProcess`. Isso não afeta a compactação de prompt ou cargas úteis de solicitação.

### Economia esperada

60–80% nos resultados da ferramenta de instantâneo do navegador, dependendo da complexidade da página. O algoritmo de colapso é O(n) na contagem de linhas e adiciona latência insignificante.

### Este filtro versus os mecanismos de compressão acima

| Aspecto               | Homem das cavernas / RTK / empilhado | filtro de acessibilidade MCP           |
| --------------------- | ------------------------------------ | -------------------------------------- |
| Alvo                  | Solicitar prompts/contexto           | resultados da ferramenta MCP           |
| Acionar               | Configuração do modo de compressão   | `compression.mcpAccessibility.enabled` |
| Escopo                | Todas as mensagens SSE               | Somente resultados da ferramenta       |
| Âncoras de referência | N/A                                  | Preservado incondicionalmente          |

---

## Combos de compressão

Os combos de compactação são chamados de perfis de compactação que podem ser atribuídos aos combos de roteamento:

- `compression_combos`: armazena modo, pipeline, configuração RTK, configuração de idioma e marcador padrão
- `compression_combo_assignments`: mapeia um combo de compactação para um combo de roteamento
- a integração em tempo de execução resolve um combo de compactação atribuído antes das substituições de combos genéricos
- análises incluem `compression_combo_id` e `engine`

Superfície do painel: `Dashboard -> Context & Cache -> Compression Combos`.

## Pré-requisitos/guia do operador (CCR e session-dedup)

CCR (`ccr`) e `session-dedup` substituem ou eliminam o texto e deixam um** marcador** atrás. Esta seção é a referência do operador para conectar um cliente, ler os dois marcadores e recuperar ou diagnosticar o conteúdo elidido. A mecânica de cada motor é abordada acima; esta é a camada "como faço para executá-la".

### Transportes e terminais

O servidor MCP que expõe as ferramentas CCR pode ser acessado de três maneiras. A base URL padrão é `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transporte                             | URL / comando                           | Notas                                                                                                                                      |
| -------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| HTTP streamável (cliente, recomendado) | `http://localhost:20128/api/mcp/stream` | O endpoint com o qual os clientes MCP atuais conversam.                                                                                    |
| Singleton SSE legado                   | `http://localhost:20128/api/mcp/sse`    | Transporte singleton mais antigo. Isto** fecha** sessões transmitíveis; use clientes `streamable-http` contra `/api/mcp/stream`, não este. |
| estúdio                                | `omniroute --mcp`                       | Para IDE MCP config que gera o processo. Não há sinalizador `--dev` ; `omniroute --mcp` é o ponto de entrada do stdio.                     |

### Camadas de armazenamento (o que sobrevive a uma reinicialização)

CCR é um** dois níveis** armazenar, não apenas na memória:

- **Camada quente na memória** — por bloco cap 2 MiB, por principal 16 MiB, global 64 MiB. As inscrições têm como padrão um TTL de 24 horas (máximo 7 dias). A recuperação completa MCP da memória é limitada a 256 KiB; qualquer coisa maior ainda pode ser alcançada através dos modos ranged/grep.
- **Camada SQLite durável** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, on por padrão) — faz backup da camada de memória para que um bloco sobreviva à remoção LRU, a uma reinicialização ou a uma recuperação em outra instância. A linha mantém o bloco TTL, portanto, um bloco após seu TTL desaparece de ambas as camadas.

Três guardas mantêm a camada durável limitada — um bloco permanece somente na memória quando:

1. o bloco acabou** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. o tempo de execução é um tempo de execução em nuvem (sem disco local);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Portanto, "o bloco desapareceu" não é uma história de reinicialização geral: um bloco sub-512 KB em um tempo de execução local, fora da nuvem, sobrevive a uma reinicialização por meio da camada durável até que seu TTL se esgote. Consulte [Referência de ambiente](../reference/ENVIRONMENT.md) para a variável.

### Os dois marcadores

| Marcador                              | Significado                                                                                                                                        | O que o modelo deve fazer                                                                                                                                                                                   |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Um grande bloco foi armazenado com conteúdo endereçado.                                                                                            | Ligue para `omniroute_ccr_retrieve` com o** Hash de 24 hexadecimais copiado literalmente** para recuperar o texto original.                                                                                 |
| `[dedup:ref sha=…]`                   | `session-dedup` texto elidido já enviado em um turno anterior da mesma sessão. Este é um** retrospectiva intencional** , não uma perda ou um erro. | Fazer** não** chame qualquer ferramenta e faça** não** tente "reconstruí-lo". A primeira ocorrência do texto é a cópia canônica; o turno atual nunca é reescrito, ele é desduplicado em um turno posterior. |

A retrospectiva `[dedup:ref]` é uma decisão deliberada do protocolo — não há reconstrução pré-envio. Trate-o como "este texto exato já estava sendo transmitido no início desta sessão".

### Pré-requisitos do cliente

- **Chave (estdio):** um chamador stdio não carrega nenhuma identidade por solicitação, portanto, ele é autenticado com `OMNIROUTE_API_KEY` (definido no `env` do servidor MCP ). Sem ele, o chamador é anônimo e as ferramentas que exigem um principal podem ser degradadas.
- **`tools[]` é a pré-condição da injeção.** A instrução do protocolo de recuperação CCR (#8033) é injetada** apenas** quando o `tools[]` anunciado da solicitação prova que o cliente pode realmente alcançar `omniroute_ccr_retrieve`. A correspondência é uma correspondência de segmento final delimitada por um separador (`__`, `.`, `/`, `:`) — nunca uma substring nua — portanto, um nome com namespace como `mcp__gateway__omniroute_ccr_retrieve` ainda conta. Um `tools[]` ausente ou não correspondente significa que a instrução _não_ foi injetada, por design.
- **`codemode:false` (clientes OpenCode ).** O padrão do OpenCode é o Modo Código, que anuncia apenas suas ferramentas nativas para o modelo e** não** coloque as ferramentas MCP na lista nativa `tools[]`. Defina `codemode: false` na entrada do servidor MCP para que as ferramentas `omniroute_ccr_*` sejam anunciadas. Este é um** cliente** configuração, não OmniRoute. A instrução CCR ainda não foi injetada: OpenCode nomeia uma ferramenta `<server>_<tool>`, portanto, um servidor chamado `omniroute` expõe `omniroute_omniroute_ccr_retrieve` e `_` não é um dos separadores correspondentes.
- **Diretores.** O armazenamento e a recuperação são isolados por entidade autenticada (por chave API ). Uma chave vê apenas seus próprios blocos.

### Escopos por ferramenta

A aplicação do escopo está sempre ativada para chamadores HTTP/SSE com escopo restrito. As ferramentas `omniroute_` CCR requerem:

| Ferramenta               | Escopo              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Um escopo ausente retorna um** resultado de erro da ferramenta MCP** (`isError: true`, não um HTTP 403 — o `403 LOCAL_ONLY` é a autenticação de proteção de rota de loopback separada): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Uma chave remota mínima pode conter `mcp:connect` (autoriza a divisão `/api/mcp/` apenas local) mais o escopo read/write específico necessário.

### Matriz de clientes

| Cliente               | Transporte                                           | Configuração para usar                                                                                                                                                                                                                                          | `tools[]` anunciado? (instrução → CCR injetada)                                                                                                                                                                   |
| --------------------- | ---------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Código Claude         | streaming-http                                       | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                               | Sim — compatível com MCP; injetado.                                                                                                                                                                               |
| Cursor / Cline        | `stdio`** ou** `streamable-http`                     | stdio: `omniroute --mcp` com `OMNIROUTE_API_KEY` em `env`; ou uma entrada MCP remota apontando para `http://localhost:20128/api/mcp/stream` (consulte [Guia de configuração → MCP Configuração do cliente](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Sim — anuncia as ferramentas `omniroute_ccr_*`.                                                                                                                                                                   |
| OpenCode              | streaming-http                                       | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, mais `codemode: false`                                                                                                                                                                | Ferramentas anunciadas apenas com `codemode: false`; a instrução ainda não foi injetada porque `omniroute_omniroute_ccr_retrieve` não corresponde (consulte [Pré-requisitos do cliente](#client-prerequisites) ). |
| Compatível com OpenAI | HTTP compatível com OpenAI (conclusões de bate-papo) | cliente padrão de conclusão de bate-papo em relação ao endpoint compatível com OpenAI                                                                                                                                                                           | **Nunca** — um chamador simples compatível com OpenAI nunca é instruído a chamar a ferramenta e a instrução não é injetada.                                                                                       |

### Limites de recuperação e paginação

Os resultados do texto da ferramenta MCP são recortados em torno de `mcpAccessibility.maxTextChars` (padrão `50000`). Uma recuperação `full` de um bloco é limitada a 256 KiB —** não há recuperação completa ilimitada** . Quando o `chars=N` de um bloco for grande, page-o em vez de extrair tudo:

- Regra prática:**`chars > 40000` → use um `mode`** , nunca totalmente cheio.
- `mode:"grep"` — regex `pattern` combinado linha por linha, até 1.000 linhas correspondentes (`unique: true` elimina repetições), mais barato para "encontrar a linha que preciso".
- `mode:"lines"` — um intervalo de linhas indexadas em 1; precisa de `start` e `end`.
- linhas `mode:"head"` / `mode:"tail"` — first/last `n`.
- `mode:"stats"` — contagens de linhas, caracteres e bytes sem o corpo.

Use `mode:"lines"` com `start`/`end` para percorrer um longo bloco nas páginas, em vez de solicitar tudo de uma vez.

### Nomenclatura de ferramentas

A ferramenta de recuperação atualmente é chamada `omniroute_ccr_retrieve` (o prefixo `omniroute_` é uma solução alternativa desatualizada para colisões de nomes entre servidores). Um nome de ferramenta de sufixo limitado mais limpo e uma correção para resultados MCP JSON truncados no meio da string são rastreados como acompanhamentos upstream; esta página documenta apenas o comportamento atual enviado.

### Ciclo de vida da sessão

As sessões Streamable-HTTP ficam inativas e o servidor as colhe; a janela inativa é a constante `MCP_SESSION_IDLE_MS` (referenciada pelo nome, não por um valor codificado, portanto, esta página não oscila quando muda). O sintoma de uma sessão ociosa é um HTTP 404 com `Unknown Mcp-Session-Id` — a solução é reconectar ou reiniciar a sessão,** não** para girar uma chave, alterar um escopo ou renomear uma ferramenta.

## Superfície API

| Rota                                   | Propósito                                                                     |
| -------------------------------------- | ----------------------------------------------------------------------------- |
| `/api/settings/compression`            | Configurações de compactação global (inclui configuração `mcpAccessibility` ) |
| `/api/compression/preview`             | Visualize qualquer modo de compactação                                        |
| `/api/compression/language-packs`      | Listar os pacotes de idiomas Caveman disponíveis                              |
| `/api/context/caveman/config`          | Alias de configurações do Caveman                                             |
| `/api/context/rtk/config`              | Padrões e configurações RTK                                                   |
| `/api/context/rtk/filters`             | catálogo de filtros RTK                                                       |
| `/api/context/rtk/test`                | ponto de extremidade RTK preview/test                                         |
| `/api/context/rtk/raw-output/[id]`     | Recuperação de saída bruta autenticada e redigida                             |
| `/api/context/combos`                  | Combinação de compressão CRUD                                                 |
| `/api/context/combos/[id]/assignments` | Atribuição de combinação de roteamento CRUD                                   |
| `/api/context/analytics`               | Alias de análise de compactação                                               |

As rotas de gerenciamento exigem autenticação de gerenciamento ou verificações de políticas de chave de API.

## Ferramentas MCP

A compactação expõe cinco ferramentas MCP :

| Ferramenta                          | Escopo              | Propósito                                      |
| ----------------------------------- | ------------------- | ---------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Configurações, análises, estatísticas de cache |
| `omniroute_compression_configure`   | `write:compression` | Atualizar configurações globais                |
| `omniroute_set_compression_engine`  | `write:compression` | Definir modo e pipeline opcional               |
| `omniroute_list_compression_combos` | `read:compression`  | Combinações de compactação de lista            |
| `omniroute_compression_combo_stats` | `read:compression`  | Leia análises combo/engine                     |

## Escopo e exclusões

**Os embeddings nunca são compactados.** `open-sse/handlers/embeddings.ts` nunca chama nenhum mecanismo de compressão — os corpos request/response passam direto para o executor sem serem tocados. Isso é estrutural hoje (embeddings e conclusões de bate-papo são manipuladores separados), não uma verificação de tempo de execução, mas significa que a preocupação com distorção vetorial no #8034 não tem superfície de exposição no caminho dos embeddings.

**filtro de exclusão Per-model/endpoint (#8034).** Para conclusões de bate-papo, um operador pode nomear ids de modelo/alvos `provider/model` que nunca devem ser compactados — um guardrail útil se a compactação for conectada mais perto de um caminho adjacente aos embeddings posteriormente e geralmente útil para qualquer modelo cujo prompt exato de byte por byte é importante (avaliações determinísticas, prefixos sensíveis ao cache, etc.).

- Campo de configurações: `exclusions?: string[]` na configuração de compactação global (`GET`/`PUT /api/settings/compression`), persistido por meio do namespace de compactação `key_value` existente (`src/lib/db/compression.ts`) — sem nova tabela.
- Guia Painel:** Dashboard → Compressão → Exclusões** (`/dashboard/compression/exclusions`).
- Sintaxe do padrão: `*` é o único curinga. Todos os outros metacaracteres regex em um padrão são escapados antes da correspondência, então `gpt-5.6` corresponde apenas à string literal, nunca `gpt-5x6` (seguro para ReDoS, limitado, sem quantificadores aninhados). Os padrões não diferenciam maiúsculas de minúsculas do id do modelo simples e do `provider/model` composto — `gpt-5-6`, `openai/gpt-5-6` e `openai/*` funcionam, e `*` sozinho exclui todos os modelos.
- Correspondência: `isCompressionExcluded()` / `normalizeCompressionExclusions()` em `open-sse/services/compression/exclusions.ts`. `chatCore.ts` verifica o alvo excluído logo após resolver as configurações de compactação,** antes de qualquer motor funcionar** e trata uma correspondência exatamente como a compactação sendo desativada globalmente — o corpo da solicitação é provavelmente idêntico em bytes. O salto é registrado via `writeCompressionSkip(..., "excluded")` para visibilidade analítica.
- Padrão (lista empty/absent ): idêntico ao comportamento pré-#8034 — nada é excluído.

## Limitações conhecidas

- **LLMLingua-2 (SLM) requer dependências opcionais co-localizadas.** O trabalhador só é executado em uma construção de produção quando os pares `@atjsh/llmlingua-2` + estão co-localizados em `dist/node_modules` (consulte `scripts/build/colocateOptionals.mjs`, #4286). Sem eles o motor falha (retorna o texto original). A resolução do trabalhador não depende mais de `import.meta.url` (ele morre no pacote independente) — ele ancora no tempo de execução cwd / `argv[1]`.
- **Os pacotes de idiomas Caveman `de` / `fr` / `ja` são parciais.** Eles enviam regras `context` + `filler` + `structural`, mas não há pacotes `dedup` / `ultra`, então a intensidade `ultra` não é mais forte que `full` para esses idiomas (eles usam apenas suas próprias regras — não há retorno silencioso às regras `dedup`/`ultra` em inglês, o que distorceria o texto estrangeiro). `en` / `es` / `id` / `pt-BR` estão completos. Contribuições de `dedup.json` + `ultra.json` para os pacotes parciais são bem-vindas.
- **A telemetria empilhada lista apenas os mecanismos compactados.** Uma etapa de pipeline empilhado cujo mecanismo funcionou, mas produziu 0% de economia, retorna `stats:null` e, portanto, não aparece em `engineBreakdown` — indistinguível de uma etapa que foi ignorada. Distinguir "executado, 0%" de "ignorado" exigiria uma mudança no modelo de detalhamento e é adiado.

## Validação

Os portões focados para esta área são:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
