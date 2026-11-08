# Compression Engines (Português (Portugal))

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇸 [es](../../../es/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

A compressão OmniRoute é construída em torno de contratos de mecanismo. Um modo pode executar um mecanismo directamente (`caveman` ou `rtk`) ou um pipeline empilhado determinístico que executa vários mecanismos por ordem.

## Modos

| Modo         | Caminho do motor                                                                     | Entrada pretendida                                      |
| ------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------- |
| `off`        | nenhum                                                                               | Preservação imediata e exata                            |
| `lite`       | Ajudantes ligeiros do homem das cavernas                                             | Limpeza sempre ativa de baixo risco                     |
| `standard`   | Homem das cavernas                                                                   | Condensação imediata em linguagem natural               |
| `aggressive` | Resumidores do homem das cavernas + history/tool                                     | Longas sessões de chat                                  |
| `ultra`      | Ajudantes de poda do homem das cavernas +                                            | Recuperação de limite de contexto                       |
| `rtk`        | RTK                                                                                  | Terminal, shell, compilação, teste e saída git          |
| `omniglyph`  | OmniGlyph                                                                            | Contexto como imagem na ligação do fornecedor nativo    |
| `stacked`    | Gasoduto. O padrão do pedido é `session-dedup -> lite`. `rtk -> caveman` é opcional. | Registos e prosa de ferramentas mistas, poupança máxima |

### perfis de compressão OmniGlyph

O mecanismo `omniglyph` ( `omniglyph` package , 1.4.0 +) aceita um perfil semântico nomeado, definido globalmente através de `omniglyph.profile` nas definições de compressão ou por passo através da configuração de passo do pipeline empilhado:

| Perfil        | Limite                                                                                                                  |
| ------------- | ----------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Padrão. A política dos recibos publicados mediu o sistema de imagens —, documentos de ferramentas e histórico denso     |
| `balanced`    | Mantém o estado ativo nativo, protege os últimos 8 turnos, colapsa o histórico fechado mais antigo                      |
| `coding-safe` | Mantém a autoridade, os esquemas de ferramentas e a saída de ferramentas em tempo real, protegendo os últimos 12 turnos |
| `passthrough` | Rotas sem transformação; o motor é ignorado                                                                             |

O perfil é um** teto, e não um chão** : `mergeCompressionProfileOptions` no pacote recusa-se a permitir que um chamador substitua a reabertura de uma pista com perdas que o perfil fechou, pelo que um `preserveSystemPrompt: false` por passo não pode reactivar a compressão do sistema em `coding-safe`.

Medido nesta base de código: `coding-safe` e `balanced` elevam `minCompressChars` ao máximo e mantêm o sistema, os esquemas de ferramentas e os resultados das ferramentas nativas, de modo que uma sessão que não acumulou histórico ainda pare em `below_min_chars` e o motor não transforme nada. É por isso que o padrão é `aggressive` em vez do perfil mais seguro.

O pacote resolve o seu próprio âmbito e perfil de modelo a partir da configuração do seu ambiente. OmniRoute nunca delega a decisão: o adaptador fixa a porta do modelo ao âmbito mais restritivo do pacote, pelo que as definições do ambiente host apenas podem restringir a lista de permissões, nunca ampliá-la para além dos recibos medidos do OmniRoute.

## Registo do motor

O registo reside em `open-sse/services/compression/engines/registry.ts`. Os mecanismos expõem um contrato partilhado:

- `id`: ID de mecanismo estável, como `caveman` ou `rtk`
- `apply(text, config)`: caminho de execução legado utilizado por pipelines empilhados
- `compress(input, config)`: caminho de execução primário que retorna texto + stats
- `getConfigSchema()`: devolve o formato do esquema JSON da configuração válida
- `validateConfig(config)`: retorna `{ valid, errors[] }`

O registo utiliza `registerCompressionEngine(engine)` (ou `registerEngine` para casos avançados), que chama `assertValidEngine()` e `validateConfig(defaultConfig)` antes de aceitar. Utilize `unregisterCompressionEngine(id)` para remover um motor em tempo de execução.

`strategySelector.ts` regista os mecanismos integrados antes da execução da compressão. Isto permite que a visualização, a compressão em tempo de execução, o modo empilhado, os testes e os mecanismos futuros utilizem o mesmo caminho de execução.

### compressão de descrição MCP (relacionado)

Um registo separado comprime os metadados de descrição da ferramenta MCP ao nível do registo — consulte `open-sse/mcp-server/descriptionCompressor.ts` e [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Reutiliza as regras do Caveman, mas opera com base em metadados de ferramentas, e não em cargas úteis de pedido.

### Motores integrados adicionais

Além de Caveman, RTK e LLMLingua-2, o registo fornece vários mecanismos estruturais/sem perdas especializados (utilizados por pipelines empilhados, playground e testes):

| Motor                   | Eu ia           | O que faz                                                                                                                                                                                                          |
| ----------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CCR                     | `ccr`           | Content-Compress-Retrieve (H4): substitui grandes blocos de texto contíguos por referências endereçadas ao conteúdo, de modo a que os blocos repeated/large sejam enviados uma vez e referenciados posteriormente. |
| altura livre            | `headroom`      | SmartCrusher (H3 + N5): compressão tabular sem perdas de cargas úteis de array JSON homogéneas num formato `[N rows]` colunar.                                                                                     |
| ionizador               | `ionizer`       | amostragem de linhas Head/middle/tail para blocos homogéneos muito grandes, armazenando o meio elidido como uma referência CCR endereçada ao conteúdo.                                                             |
| desduplicação de sessão | `session-dedup` | Desduplicação de turnos cruzados endereçado ao conteúdo (inspirado no TokenMizer): elimina o texto já visto em turnos anteriores da mesma sessão.                                                                  |

**Instrução do protocolo de recuperação CCR (#8033):** na primeira vez CCR substitui o bloco ≥ 1 num pedido, o motor acrescenta uma única mensagem `system` idempotente (iniciando com a sentinela `[CCR protocol]` ) ensinando ao chamador o contrato da ferramenta → marcador: o que um marcador `[CCR retrieve hash=<24hex> chars=N]` significa, que o hash deve ser copiado literalmente (todos os 24 caracteres hexadecimais — hashes mal copiados são a causa provável de falhas de "bloco não encontrado"), e que um marcador `[dedup:ref sha=...]` significa "olhar para trás em histórico", não "chame a ferramenta". A nota é injetada** apenas quando o `tools[]` anunciado pelo chamador provar que pode realmente atingir `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` in `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — um chamador simples compatível com OpenAI sem esta ferramenta nunca recebe uma instrução para chamar algo que não consegue alcançar. A idempotência é reforçada verificando o histórico de mensagens em busca do sentinela antes de injetar, de modo a que os pedidos multi-turno (que reproduzem mensagens anteriores) não empilhem a nota uma vez por turno.

## Homem das cavernas

O modo Caveman centra-se na condensação semântica da prosa normal:

- preserva blocos de código, URLs, JSON, caminhos e dados estruturados
- remove o preenchimento, a cobertura, o contexto repetido e o fraseado conectivo detalhado
- suporta pacotes de regras de ficheiros com reconhecimento de idioma no `open-sse/services/compression/rules/`
- permanece disponível através dos modos herdados `standard`, `aggressive` e `ultra`

A superfície do painel é `Dashboard -> Context & Cache -> Caveman`.

O upstream do Caveman reporta `~75%` menos tokens de saída, poupança média de produção `65%` em benchmarks com um intervalo `22-87%` e uma ferramenta de compressão de entrada `~46%`. OmniRoute utiliza o número do lado de entrada do Caveman ao documentar poupanças prompt/context empilhadas; O modo de saída Caveman continua a ser uma funcionalidade de comportamento de resposta separada.

## RTK

O modo RTK concentra-se na saída de comandos e ferramentas:

- deteta classes de saída como `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, testes Cargo/Go, compilações TypeScript/Vite/Webpack, ESLint, npm audit/installs, logs Docker, shell `find`/`grep`, stack traces e logs genéricos
- aplica 49 filtros JSON do `open-sse/services/compression/engines/rtk/filters/`
- suporta o pipeline declarativo estilo RTK: remoção ANSI, substituição, curto-circuito de saída correspondente, linhas strip/keep, truncamento por linha, truncamento head/tail/max-line e fallback on-empty
- suporta filtros de projeto fiáveis em `.rtk/filters.json` e filtros globais em `DATA_DIR/rtk/filters.json`
- remove sequências ANSI, ruído de progresso, linhas repetidas e clichés inúteis
- preserva falhas acionáveis, avisos, resumos, ficheiros alterados e contexto final
- opcionalmente, pode reter a saída bruta editada para recovery/debugging através de rotas de gestão autenticadas

A superfície do painel é `Dashboard -> Context & Cache -> RTK`.

Os detalhes operacionais para filtros personalizados, confiança, verificação e recuperação de saída bruta estão disponíveis em [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream reporta poupança de `60-90%` para compressão de saída de comando. O seu exemplo README mostra uma sessão de código Claude de 30 minutos a passar de tokens `~118,000` para `~23,900` ou `79.7%` guardados.

## LLMLingua-2 (poda semântica)

O modo LLMLingua-2 executa** poda de token semântico** em prosa utilizando um pequeno classificador de tokens ONNX, complementando os mecanismos de Caveman e RTK baseados em regras:

- compacta a prosa apenas em mensagens que não sejam do sistema; blocos de código protegidos e outras construções preservadas nunca são alteradas
- executa o back-end `@atjsh/llmlingua-2` (ONNX via `@huggingface/transformers`) num thread de trabalho, para que a inferência do modelo nunca bloqueie o ciclo de eventos de pedido
- é** empilhável** (`stackPriority` 35): num pipeline empilhado, é executado após os mecanismos estruturais (CCR, session-dedup, headroom, Caveman), mas antes de `ultra`, uma vez que a poda semântica é mais eficaz em texto já compactado estruturalmente — por exemplo `rtk -> caveman -> llmlingua`
- **fail-opens em qualquer erro** (faltam dependências opcionais, geração de trabalhadores, carregamento de modelos, inferência ou tempo limite) → o texto original é devolvido inalterado, nunca um erro

Localização do motor: `open-sse/services/compression/engines/llmlingua/`. A superfície do painel é `Dashboard -> Context & Cache -> LLMLingua`.

### Modelos

O modelo padrão é**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, rápido). Uma maior precisão** Base BERT** modelo (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) está disponível através do campo `model` de configuração do mecanismo. `@huggingface/transformers` descarrega lentamente o modelo seleccionado do HuggingFace Hub para `${DATA_DIR}/models/llmlingua` na primeira chamada (`modelStore.ts`); uma substituição de configuração `modelPath` aponta para uma cópia local (instalações offline/air-gapped).

### Dependências opcionais e instalação a pedido

A pilha de pares de tempo de execução LLMLingua prundível é** opcional** . Dois pacotes são declarados como `optionalDependencies` em `package.json` e mantidos** externo** pela compilação de produção (`scripts/build/prepublish.ts` não os agrupa):

| Pacote               | Versão (pino) | Notas                                           |
| -------------------- | ------------- | ----------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`       | Pacote de entrada; declara os outros como pares |
| `js-tiktoken`        | `^1.0.20`     | Tokenizador                                     |

`@huggingface/transformers` é fixado em `^4.2.0` (partilhado com o caminho de embeddings local e também rastreado no pacote independente); `@atjsh/llmlingua-2@2.0.5` peers nele com `"^3.5.2 || ^4.0.0"`, portanto, tanto Transformers.js v3 como v4 são suportados. Desde a versão 2.0.4, `@atjsh/llmlingua-2` já não requer `@tensorflow/tfjs`, o que removeu o maior contribuidor único (TensorFlow.js) da pilha SLM. Apenas os dois pacotes acima são pares SLM prudáveis. Um `npm install` (dev) padrão instala a pilha opcional automaticamente, a menos que as dependências opcionais sejam omitidas.

**Porquê sob demanda:** o pacote publicado pelo npm, o pacote independente e o envio da imagem Docker** sem** estas dependências para se manterem magras. Quando estão ausentes, o portão de dependência do trabalhador (um teste `@atjsh/llmlingua-2` resolve em `worker.ts`) falha e o mecanismo** falha abre silenciosamente** — selecionando LLMLingua torna-se autónomo (texto devolvido inalterado, sem erro registado). Para o ativar num ambiente limpo, instale a pilha opcional:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

A remoção `@tensorflow/tfjs` (2.0.4 +) elimina o contribuidor ~ 800 MB anteriormente dominante — o espaço restante são os tempos de execução transformers.js + onnxruntime-node, mais o modelo TinyBERT (~ 57 MB) descarregado na primeira utilização (não via npm).

Por ambiente:

- **Dev/ `npm install`** — instalado automaticamente, a menos que passe `--omit=optional` (ou `--no-optional`). Nenhuma ação necessária.
- **Npm global (`npm i -g omniroute`)/autónomo** — execute o comando de instalação acima dentro do diretório do pacote instalado ou reinstale sem omitir deps opcionais.
- **Docker** — adicione o comando de instalação numa camada de imagem derivada; a imagem publicada é elegante por design.
- **VPS (PM2)** — instale no `node_modules` da aplicação e reinicie o processo para que o trabalhador teste novamente o portão.
- **Raw Próximo autónomo (`npm run build` → `.build/next/standalone/server.js`)** — o rastreio independente envia NEITHER o trabalhador nem as dependências opcionais, de modo que o mecanismo falha silenciosamente. `scripts/build/colocate-standalone.mjs` reaplica ambos (worker esbuild + opcional-dep encerramento na árvore autónoma); é executado automaticamente através do gancho `postbuild` npm após cada compilação. Idempotente, anti-falha quando as dependências estão ausentes.

**Verifique se está ativo:** com LLMLingua seleccionado, a prosa real diminui realmente (o mecanismo deixa de abrir com falha) e o primeiro pedido desencadeia o download do modelo em `${DATA_DIR}/models/llmlingua`. O portão testa intencionalmente apenas `@atjsh/llmlingua-2` — os outros pares são apenas ESM e `require.resolve` lança sobre eles mesmo quando — está presente, de modo que o trabalhador ainda falha a abertura se algum par estiver realmente em falta no momento `import()`.

## Pipelines empilhados

O modo empilhado executa os passos do pipeline por ordem. O padrão é:

```txt
rtk -> caveman
```

Utilize isto para sessões do agente de codificação em que um prompt combina a saída do comando com prosa humana ou assistente. RTK reduz primeiro os registos de ferramentas ruidosos e, em seguida, o Caveman compacta a linguagem natural restante.

As etapas do pipeline são configuradas com `stackedPipeline` nas definições de compressão ou através de combos de compressão.

Quando ambos os motores reduzem a mesma carga útil elegível, a poupança aumenta:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## Filtro de árvore de acessibilidade MCP

O filtro inteligente de árvore de acessibilidade MCP é uma camada de compressão pós-execução que corre em MCP** resultados da ferramenta** , e não em prompts ou contexto. Tem como alvo as cargas detalhadas da árvore de acessibilidade e do instantâneo do browser devolvidas por ferramentas como Playwright, a utilização do computador e os servidores MCP de automatização do browser.

### O que faz

1. **Remoção de ruído** — remove entradas generic/text vazias (`- generic:`, `- text: ""`)
2. **Colapso de irmão** — quando ≥ `collapseThreshold` (padrão 30) linhas consecutivas são repetições estruturais, recolhe-as nas primeiras linhas `collapseKeepHead` (padrão 10) + um resumo de contagem + as últimas linhas `collapseKeepTail` (padrão 5)
3. **Preservação de referência** As âncoras — `[ref=eXX]` exigidas pelo Playwright/computer-use nunca são tocadas
4. **Truncamento rígido** — se o texto após a recolha ainda exceder `maxTextChars` (padrão 50.000), será truncado com uma dica de navegação para que o agente possa continuar a trabalhar

### Localização do motor

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Configuração

Controlado por `compression.mcpAccessibility` nas definições globais (migração 056). Configuração padrão:

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

O filtro é aplicado apenas a cargas de resultados de ferramentas cujo `type` é `"text"` e cujo comprimento excede `minLengthToProcess`. Isto não afeta a compressão de prompt ou cargas úteis de solicitação.

### Economia esperada

60–80% nos resultados da ferramenta de instantâneo do browser, dependendo da complexidade da página. O algoritmo de colapso é O(n) na contagem de linhas e adiciona latência insignificante.

### Este filtro versus os mecanismos de compressão acima

| Aspeto                | Homem das cavernas / RTK / empilhado | filtro de acessibilidade MCP           |
| --------------------- | ------------------------------------ | -------------------------------------- |
| Objetivo              | Solicitar prompts/contexto           | resultados da ferramenta MCP           |
| Gatilho               | Configuração do modo de compressão   | `compression.mcpAccessibility.enabled` |
| Âmbito                | Todas as mensagens SSE               | Apenas resultados da ferramenta        |
| Âncoras de referência | N/A                                  | Preservado incondicionalmente          |

---

## Combos de compressão

Os combos de compressão são designados por perfis de compressão que podem ser atribuídos aos combos de encaminhamento:

- `compression_combos`: armazena o modo, pipeline, configuração RTK, configuração de idioma e marcador padrão
- `compression_combo_assignments`: mapeia um combo de compressão para um combo de encaminhamento
- a integração em tempo de execução resolve um combo de compressão atribuído antes das substituições de combos genéricos
- análises incluem `compression_combo_id` e `engine`

Superfície do painel: `Dashboard -> Context & Cache -> Compression Combos`.

## Pré-requisitos/guia do operador (CCR e session-dedup)

CCR (`ccr`) e `session-dedup` substituem ou eliminam o texto e deixam um** marcador** atrás. Esta secção é a referência do operador para ligar um cliente, ler ambos os marcadores e recuperar ou diagnosticar o conteúdo elidido. A mecânica de cada motor é abordada acima; esta é a camada "como faço para a executar".

### Transportes e terminais

O servidor MCP que expõe as ferramentas CCR pode ser acedido de três formas. A base URL por defeito é `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transporte                             | URL / comando                           | Notas                                                                                                                                      |
| -------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| HTTP streamável (cliente, recomendado) | `http://localhost:20128/api/mcp/stream` | O endpoint com o qual os clientes MCP atuais conversam.                                                                                    |
| Singleton SSE legado                   | `http://localhost:20128/api/mcp/sse`    | Transporte singleton mais antigo. Isto** fecha** sessões transmitíveis; use clientes `streamable-http` contra `/api/mcp/stream`, não este. |
| estúdio                                | `omniroute --mcp`                       | Para IDE MCP config que gera o processo. Não existe sinalizador `--dev` ; `omniroute --mcp` é o ponto de entrada do stdio.                 |

### Camadas de armazenamento (o que sobrevive a um reinício)

CCR é um** dois níveis** armazenar, e não apenas na memória:

- **Camada quente na memória** — por bloco cap 2 MiB, por principal 16 MiB, global 64 MiB. As inscrições têm como padrão um TTL de 24 horas (máximo 7 dias). A recuperação completa MCP da memória está limitada a 256 KiB; qualquer coisa maior ainda pode ser alcançada através dos modos ranged/grep.
- **Camada SQLite durável** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, on por defeito) — faz o backup da camada de memória para que um bloco sobreviva à remoção LRU, a um reinício ou a uma recuperação noutra instância. A linha mantém o bloco TTL, pelo que um bloco após o seu TTL desaparece de ambas as camadas.

Três guardas mantêm a camada durável limitada — um bloco permanece apenas na memória quando:

1. o bloco acabou** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. o tempo de execução é um tempo de execução na nuvem (sem disco local);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Portanto, "o bloco desapareceu" não é uma história de reinicialização geral: um bloco sub-512 KB num tempo de execução local, fora da nuvem, sobrevive a uma reinicialização através da camada durável até que o seu TTL se esgote. Consulte [Referência de ambiente](../reference/ENVIRONMENT.md) para a variável.

### Os dois marcadores

| Marcador                              | Significado                                                                                                                                        | O que deve o modelo fazer                                                                                                                                                                             |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[CCR retrieve hash=<24hex> chars=N]` | Um bloco grande foi armazenado com conteúdo endereçado.                                                                                            | Ligue para a `omniroute_ccr_retrieve` com o** Hash de 24 hexadecimais copiado literalmente** para recuperar o texto original.                                                                         |
| `[dedup:ref sha=…]`                   | `session-dedup` texto elidido já enviado num turno anterior da mesma sessão. Este é um** retrospectiva intencional** , e não uma perda ou um erro. | Fazer** não** chame qualquer ferramenta e faça** não** tente "reconstruí-lo". A primeira ocorrência do texto é a cópia canónica; o turno atual nunca é reescrito, é desduplicado num turno posterior. |

A retrospetiva `[dedup:ref]` é uma decisão deliberada do protocolo — não há reconstrução pré-envio. Trate-o como "este texto exato já estava a ser transmitido no início desta sessão".

### Pré-requisitos do cliente

- **Chave (estdio):** um chamador stdio não transporta qualquer identidade por pedido, pelo que é autenticado com `OMNIROUTE_API_KEY` (definido no `env` do servidor MCP ). Sem ele, o chamador é anónimo e as ferramentas que requerem um principal podem ser degradadas.
- **`tools[]` é a pré-condição da injecção.** A instrução do protocolo de recuperação CCR (#8033) é injectada** apenas** quando o `tools[]` anunciado do pedido prova que o cliente pode realmente alcançar `omniroute_ccr_retrieve`. A correspondência é uma correspondência de segmento final delimitada por um separador (`__`, `.`, `/`, `:`) — nunca uma substring nua — portanto, um nome com namespace como `mcp__gateway__omniroute_ccr_retrieve` ainda conta. Um `tools[]` em falta ou não correspondente significa que a instrução _não_ foi injetada, por design.
- **`codemode:false` (clientes OpenCode ).** O padrão do OpenCode é o Modo Código, que anuncia apenas as suas ferramentas nativas para o modelo e** não** coloque as ferramentas MCP na lista nativa `tools[]`. Defina `codemode: false` na entrada do servidor MCP para que as ferramentas `omniroute_ccr_*` sejam anunciadas. Este é um** cliente** configuração, e não OmniRoute. A instrução CCR ainda não foi injectada: OpenCode nomeia uma ferramenta `<server>_<tool>`, pelo que um servidor chamado `omniroute` expõe `omniroute_omniroute_ccr_retrieve` e `_` não é um dos separadores correspondentes.
- **Diretores.** O armazenamento e a recuperação são isolados por entidade autenticada (por chave API ). Uma chave vê apenas os seus próprios blocos.

### Escopos por ferramenta

A aplicação do âmbito está sempre ativada para os chamadores HTTP/SSE com âmbito restrito. As ferramentas `omniroute_` CCR requerem:

| Ferramenta               | Âmbito              |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Um âmbito em falta retorna um** resultado de erro da ferramenta MCP** (`isError: true`, não um HTTP 403 — o `403 LOCAL_ONLY` é a autenticação de proteção de rota de loopback separada): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Uma chave remota mínima pode conter `mcp:connect` (autoriza a divisão `/api/mcp/` apenas local) mais o âmbito read/write específico necessário.

### Matriz de clientes

| Cliente               | Transporte                                      | Configuração para utilizar                                                                                                                                                                                                                                       | `tools[]` anunciado? (instrução → CCR injetada)                                                                                                                                                                   |
| --------------------- | ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Código Claude         | streaming-http                                  | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                                | Sim — compatível com MCP; injetado.                                                                                                                                                                               |
| Cursor / Cline        | `stdio`** ou** `streamable-http`                | stdio: `omniroute --mcp` com `OMNIROUTE_API_KEY` em `env`; ou uma entrada MCP remota que aponta para `http://localhost:20128/api/mcp/stream` (consulte [Guia de configuração → MCP Configuração do cliente](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Sim — anuncia as ferramentas `omniroute_ccr_*`.                                                                                                                                                                   |
| OpenCode              | streaming-http                                  | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, mais `codemode: false`                                                                                                                                                                 | Ferramentas anunciadas apenas com `codemode: false`; a instrução ainda não foi injetada porque `omniroute_omniroute_ccr_retrieve` não corresponde (consulte [Pré-requisitos do cliente](#client-prerequisites) ). |
| Compatível com OpenAI | HTTP compatível com OpenAI (conclusões de chat) | cliente padrão de conclusão de chat em relação ao endpoint compatível com OpenAI                                                                                                                                                                                 | **Nunca** — um chamador simples compatível com OpenAI nunca é instruído para chamar a ferramenta e a instrução não é injectada.                                                                                   |

### Limites de recuperação e paginação

Os resultados do texto da ferramenta MCP são recortados em torno de `mcpAccessibility.maxTextChars` (padrão `50000`). Uma recuperação `full` de um bloco está limitada a 256 KiB —** não há recuperação completa ilimitada** . Quando o `chars=N` de um bloco é grande, faça-o page-o em vez de extrair tudo:

- Regra prática:**`chars > 40000` → utilize um `mode`** , nunca totalmente cheio.
- `mode:"grep"` — regex `pattern` combinado linha a linha, até 1.000 linhas correspondentes (`unique: true` elimina repetições), mais barato para "encontrar a linha que preciso".
- `mode:"lines"` — um intervalo de linhas indexadas em 1; precisa de `start` e `end`.
- linhas `mode:"head"` / `mode:"tail"` — first/last `n`.
- `mode:"stats"` — contagens de linhas, caracteres e bytes sem o corpo.

Utilize `mode:"lines"` com `start`/`end` para percorrer um bloco longo nas páginas, em vez de solicitar tudo de uma só vez.

### Nomenclatura de ferramentas

A ferramenta de recuperação é atualmente chamada `omniroute_ccr_retrieve` (o prefixo `omniroute_` é uma solução alternativa desatualizada para colisões de nomes entre servidores). Um nome de ferramenta de sufixo limitado mais limpo e uma correção para resultados MCP JSON truncados no meio da string são rastreados como acompanhamentos upstream; esta página documenta apenas o comportamento atual enviado.

### Ciclo de vida da sessão

As sessões Streamable-HTTP ficam inativas e o servidor recolhe-as; a janela inativa é a constante `MCP_SESSION_IDLE_MS` (referenciada pelo nome, e não por um valor codificado, pelo que esta página não oscila quando muda). O sintoma de uma sessão em idle é um HTTP 404 com `Unknown Mcp-Session-Id` — a solução é voltar a ligar ou reiniciar a sessão,** não** para rodar uma chave, alterar um âmbito ou renomear uma ferramenta.

## Superfície API

| Rota                                   | Finalidade                                                                   |
| -------------------------------------- | ---------------------------------------------------------------------------- |
| `/api/settings/compression`            | Configurações de compressão global (inclui configuração `mcpAccessibility` ) |
| `/api/compression/preview`             | Visualize qualquer modo de compressão                                        |
| `/api/compression/language-packs`      | Listar os pacotes de idiomas Caveman disponíveis                             |
| `/api/context/caveman/config`          | Alias de configurações do Caveman                                            |
| `/api/context/rtk/config`              | Padrões e definições RTK                                                     |
| `/api/context/rtk/filters`             | catálogo de filtros RTK                                                      |
| `/api/context/rtk/test`                | ponto final RTK preview/test                                                 |
| `/api/context/rtk/raw-output/[id]`     | Recuperação de saída em bruto autenticada e redigida                         |
| `/api/context/combos`                  | Combinação de compressão CRUD                                                |
| `/api/context/combos/[id]/assignments` | Atribuição de combinação de encaminhamento CRUD                              |
| `/api/context/analytics`               | Alias de análise de compressão                                               |

As rotas de gestão exigem autenticação de gestão ou verificações de políticas de chave API.

## Ferramentas MCP

A compressão expõe cinco ferramentas MCP :

| Ferramenta                          | Âmbito              | Finalidade                                     |
| ----------------------------------- | ------------------- | ---------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Configurações, análises, estatísticas de cache |
| `omniroute_compression_configure`   | `write:compression` | Atualizar as configurações globais             |
| `omniroute_set_compression_engine`  | `write:compression` | Definir modo e pipeline opcional               |
| `omniroute_list_compression_combos` | `read:compression`  | Combinações de compressão de lista             |
| `omniroute_compression_combo_stats` | `read:compression`  | Leia as avaliações combo/engine                |

## Âmbito e exclusões

**Os embeddings nunca são comprimidos.** `open-sse/handlers/embeddings.ts` nunca chama nenhum mecanismo de compressão — os corpos request/response passam directamente para o executante sem serem tocados. Isto é estrutural hoje (embeddings e conclusões de chat são manipuladores separados), não uma verificação de tempo de execução, mas significa que a preocupação com a distorção vetorial no #8034 não tem superfície de exposição no caminho dos embeddings.

**filtro de exclusão Per-model/endpoint (#8034).** Para conclusões de chat, um operador pode nomear ids de modelo/alvos `provider/model` que nunca devem ser comprimidos — um guardrail útil se a compressão for ligada mais perto de um caminho adjacente aos embeddings posteriormente e geralmente útil para qualquer modelo cujo prompt exato de byte por byte seja importante (avaliações determinísticas, prefixos sensíveis à cache, etc.).

- Campo de definições: `exclusions?: string[]` na configuração de compressão global (`GET`/`PUT /api/settings/compression`), persistido através do namespace de compressão `key_value` existente (`src/lib/db/compression.ts`) — sem nova tabela.
- Separador Painel:** Dashboard → Compressão → Exclusões** (`/dashboard/compression/exclusions`).
- Sintaxe do padrão: `*` é o único joker. Todos os outros metacaracteres regex num padrão são escapados antes da correspondência, pelo que `gpt-5.6` corresponde apenas à string literal, nunca `gpt-5x6` (seguro para ReDoS, limitado, sem quantificadores aninhados). Os padrões não distinguem maiúsculas de minúsculas do id do modelo simples e do `provider/model` composto — `gpt-5-6`, `openai/gpt-5-6` e `openai/*` funcionam, e `*` por si só exclui todos os modelos.
- Correspondência: `isCompressionExcluded()` / `normalizeCompressionExclusions()` em `open-sse/services/compression/exclusions.ts`. `chatCore.ts` verifica o alvo excluído logo após resolver as definições de compressão,** antes de qualquer motor funcionar** e trata uma correspondência exatamente como a compressão que está a ser desativada globalmente — o corpo do pedido é provavelmente idêntico em bytes. O salto é registado através de `writeCompressionSkip(..., "excluded")` para visibilidade analítica.
- Padrão (lista empty/absent ): idêntico ao comportamento pré-#8034 — nada é excluído.

## Limitações conhecidas

- **LLMLingua-2 (SLM) requer dependências opcionais co-localizadas.** O trabalhador só é executado numa construção de produção quando os pares `@atjsh/llmlingua-2` + estão co-localizados em `dist/node_modules` (consulte `scripts/build/colocateOptionals.mjs`, #4286). Sem eles o motor falha (retorna o texto original). A resolução do trabalhador já não depende de `import.meta.url` (morre no pacote independente) — ancora no tempo de execução cwd / `argv[1]`.
- **Os pacotes de idiomas `de` / `fr` / `ja` do Caveman são parciais.** Enviam regras `context` + `filler` + `structural`, mas não há pacotes `dedup` / `ultra`, pelo que a intensidade `ultra` não é mais forte do que `full` para estas línguas (eles apenas usam as suas próprias regras — não há um retorno silencioso às regras `dedup`/`ultra` em inglês, o que distorceria o texto estrangeiro). `en` / `es` / `id` / `pt-BR` estão completos. Contribuições de `dedup.json` + `ultra.json` para os pacotes parciais são bem-vindas.
- **A telemetria empilhada lista apenas os mecanismos comprimidos.** Uma etapa de pipeline empilhado cujo mecanismo funcionou, mas produziu 0% de poupança, retorna `stats:null` e, portanto, não aparece em `engineBreakdown` — indistinguível de uma etapa que foi ignorada. Distinguir "executado, 0%" de "ignorado" exigiria uma alteração no modelo de detalhe e é adiado.

## Validação

Os portões focados para esta área são:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
