# 🌐 OmniRoute Proxy Guide (Português (Brasil))

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇸 [es](../../../es/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Ignore bloqueios geográficos, proteja sua identidade e roteie o tráfego AI por meio de qualquer proxy — com complexidade zero de configuração.**

OmniRoute inclui um sistema de gerenciamento de proxy completo que permite rotear o tráfego upstream do provedor AI por meio de proxies HTTP, HTTPS ou SOCKS5. Esteja você em uma região bloqueada, precise de rotação IP ou queira impressões digitais furtivas — este guia cobre tudo.

---

## Índice

- [Por que usar proxies?](#why-use-proxies)
- [Visão geral da arquitetura](#architecture-overview)
- [Sistema proxy de 4 níveis](#4-level-proxy-system)
- [Registro de proxy (CRUD)](#proxy-registry-crud)
- [1proxy Mercado Gratuito](#1proxy-free-proxy-marketplace)
- [Rotação de proxy](#proxy-rotation)
- [Antidetecção e furtividade](#anti-detection--stealth)
- [Modos de proxy upstream](#upstream-proxy-modes)
- [Painel UI](#dashboard-ui)
- [Referência API](#api-reference)
- [Variáveis de ambiente](#environment-variables)
- [Solução de problemas](#troubleshooting)

---

## Por que usar proxies?

Muitos provedores AI restringem o acesso por região geográfica. Desenvolvedores em** Rússia, China, Irã, Cuba, Turquia** e outros países encontram erros como:

```
unsupported_country_region_territory
```

Mesmo fora das regiões bloqueadas, os proxies são úteis para:

| Caso de uso           | Descrição                                                          |
| --------------------- | ------------------------------------------------------------------ |
| **Desvio geográfico** | Acesse OpenAI, Anthropic, Codex, Copilot de países bloqueados      |
| **rotação IP**        | Distribua solicitações em vários IPs para evitar limitação de taxa |
| **Privacidade**       | Esconda seu IP real de provedores upstream                         |
| **Conformidade**      | Rotear o tráfego através de jurisdições específicas                |
| **Teste**             | Simule solicitações de diferentes regiões                          |

---

## Visão geral da arquitetura

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

### Componentes principais

| Componente                | Arquivo                                      | Papel                                                 |
| ------------------------- | -------------------------------------------- | ----------------------------------------------------- |
| **Registro de proxy**     | `src/lib/db/proxies.ts`                      | CRUD para entradas de proxy atribuições de escopo +   |
| **Despachante proxy**     | `open-sse/utils/proxyDispatcher.ts`          | Cria despachantes `undici` ProxyAgent/SOCKS com cache |
| **Busca por proxy**       | `open-sse/utils/proxyFetch.ts`               | Envolve `fetch()` com injeção de despachante de proxy |
| **Rota de configurações** | `src/app/api/settings/proxy/route.ts`        | Configuração de proxy legado API (GET/PUT/DELETE)     |
| **Rota de Gestão**        | `src/app/api/v1/management/proxies/route.ts` | Registro CRUD API (GET/POST/PATCH/DELETE)             |
| **1proxy DB**             | `src/lib/db/oneproxy.ts`                     | Persistência gratuita no mercado de proxy             |

---

## Estado de proxy padrão para novas contas

Em** Configurações → Proxy → Configuração global** , usar** Habilite proxy por padrão para novas conexões** para escolher o estado inicial do proxy das contas de provedor recém-adicionadas.

A nova configuração controla o estado inicial do proxy das contas de provedor recém-adicionadas. Ele não altera as contas existentes nem substitui a opção de proxy global. Seu valor inicial preserva o comportamento anterior. Desative-o uma vez para criar contas futuras com o proxy desativado por padrão.

A preferência é armazenada como `defaultNewConnectionProxyEnabled` por meio das configurações existentes API. O padrão é `true` quando nunca é salvo. Salvar `false` entra em vigor para novas contas subsequentes sem reinicialização. `POST /api/providers` aceita um booleano estrito opcional `proxyEnabled`; um `true` ou `false` explícito tem precedência sobre o padrão de criação. A omissão em uma conta duplicada ou reconexão OAuth preserva o estado armazenado dessa conta. Contas individuais ainda podem ser ativadas ou desativadas posteriormente.

As transferências seletivas de provedor usam o padrão da instalação de destino para novas contas e preservam a política de destino ao substituir contas existentes. Os alternadores de proxy não são campos de transferência portáteis. A restauração completa do backup e a migração histórica JSON/SQL mantêm a semântica de restauração existente, incluindo valores de conta salvos e padrões de esquema legado; uma restauração completa das configurações também pode restaurar essa preferência.

Essa preferência não atribui um proxy nem estabelece que ele esteja íntegro ou em uso. O roteamento real ainda depende do switch de proxy global e da configuração de proxy aplicável. Provedores sintéticos sem uma conta persistente, tráfego OAuth antes da criação da conta, proxies environment/system e redes de back-end externos estão fora do seu escopo.

## Sistema proxy de 4 níveis

OmniRoute suporta configuração de proxy em** quatro escopos independentes** , resolvido em ordem de prioridade:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Como funciona a resolução

Quando OmniRoute envia uma solicitação a um provedor upstream, ele chama `resolveProxyForConnectionFromRegistry()`, que verifica cada nível em ordem:

1. **Nível da conta** — Existe um proxy atribuído a esta conexão específica ID?
2. **Nível do provedor** — Existe um proxy atribuído a este provedor (por exemplo, `openai`)?
3. **Nível global** — Existe um proxy global configurado?
4. **Sem proxy** — Conexão direta com o provedor.

A primeira partida vence. Isso significa que você pode definir um proxy global como substituto, mas substituí-lo por provedores ou conexões específicas.

### O que é proxy

| Tipo de tráfego         | Procurado? | Notas                                          |
| ----------------------- | ---------- | ---------------------------------------------- |
| Conclusões de bate-papo | ✅         | Todas as solicitações `/v1/chat/completions`   |
| Incorporações           | ✅         | `/v1/embeddings`                               |
| Geração de imagem       | ✅         | `/v1/images/generations`                       |
| Áudio (TTS/STT)         | ✅         | `/v1/audio/*`                                  |
| troca de token OAuth    | ✅         | Resolve `unsupported_country_region_territory` |
| Testes de conexão       | ✅         | O botão "Testar conexão" usa proxy             |
| Atualização de token    | ✅         | Renovação OAuth em segundo plano               |
| Sincronização de modelo | ✅         | Listagem e descoberta de modelos               |

---

## Registro de proxy (CRUD)

O registro de proxy é uma tabela SQLite (`proxy_registry`) que armazena todos os seus proxies. Cada proxy possui:

| Campo      | Tipo    | Descrição                                                  |
| ---------- | ------- | ---------------------------------------------------------- |
| `id`       | UUID    | Identificador exclusivo                                    |
| `name`     | Corda   | Etiqueta legível por humanos                               |
| `type`     | Corda   | Protocolo: `http`, `https`, `socks5`                       |
| `host`     | Corda   | Nome do host proxy ou IP                                   |
| `port`     | Inteiro | Número da porta                                            |
| `username` | Corda   | Nome de usuário de autenticação (criptografado em repouso) |
| `password` | Corda   | Senha de autenticação (criptografada em repouso)           |
| `region`   | Corda   | Rótulo de região geográfica                                |
| `notes`    | Corda   | Notas de texto livre                                       |
| `status`   | Corda   | `active` ou `inactive`                                     |
| `source`   | Corda   | `manual` ou `oneproxy`                                     |

### Criando um proxy

**Através do painel:**

1. Vá para** Configurações do proxy →**
2. Clique** Adicionar proxy**
3. Preencha o tipo, host, porta e credenciais de autenticação opcionais
4. Salvar

**Via API:**

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

### Atualizando um proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Observação:** As credenciais são preservadas, a menos que você envie explicitamente substituições não vazias. O envio de strings vazias para `username`/`password` manterá os valores armazenados.

### Excluindo um proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Listando Proxies

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Atribuindo Proxies aos Escopos

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

### Resolvendo proxy eficaz

Verifique qual proxy seria usado para uma determinada conexão:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Retorna o proxy resolvido com seu nível (`account`, `provider` ou `global`) e origem.

### Atribuição em massa

Atribua um proxy a vários provedores ou conexões de uma só vez:

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

Os proxies estão incluídos no**Backup/Restore** sistema. Ao exportar sua configuração OmniRoute :

1. Vá para** Painel → Configurações → Backup**
2. Clique** Exportar** registro de proxy — e atribuições estão incluídos
3. Para restaurar, clique em** Importar** e carregue o arquivo de backup

O registro proxy também suporta** upsert pelo host + port** — se você importar um proxy que já existe (mesmo host e porta), ele será atualizado em vez de criar uma duplicata.

### Migração herdada

Se você configurou proxies em uma versão mais antiga (pré-registro), OmniRoute os migrará automaticamente:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Isso acontece uma vez na primeira inicialização após a atualização. Use `migrateLegacyProxyConfigToRegistry({ force: true })` para executar novamente.

---

## Mercado de proxy gratuito 1proxy

> 🆕** Contribuição de [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Edição [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute integra-se com o** [1proxy](https://1proxy-api.aitradepulse.com)** plataforma comunitária para fornecer acesso a** centenas de proxies validados e gratuitos** de todo o mundo. Isso é perfeito para usuários que não possuem infraestrutura de proxy própria.

### Como funciona

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sincronizar** — OmniRoute busca proxies validados do 1proxy API
2. **Loja** Os proxies — são salvos na mesma tabela `proxy_registry` com `source = 'oneproxy'`
3. **Filtro** — Filtrar por protocolo, país, índice de qualidade
4. **Girar** — Escolha o melhor proxy usando estratégias de qualidade, aleatórias ou sequenciais
5. **Degradação automática** — Proxies com falha têm seu índice de qualidade reduzido; abaixo do limite → marcado como inativo

### Sincronizando Proxies

**Através do painel:**

1. Vá para** Configurações → 1proxy** aba
2. Clique** "Sincronizar agora"**
3. Ver estatísticas: total de proxies, contagem ativa, qualidade média, detalhamento por país

**Via API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtrando Proxies

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

### Índices de qualidade de proxy

Cada proxy 1proxy vem com metadados:

| Campo           | Descrição                                    |
| --------------- | -------------------------------------------- |
| `qualityScore`  | Classificação de 0 a 100 da validação 1proxy |
| `latencyMs`     | Latência de rede medida                      |
| `anonymity`     | `transparent`, `anonymous` ou `elite`        |
| `googleAccess`  | Se o proxy pode acessar os serviços Google   |
| `countryCode`   | Código de país ISO de duas letras            |
| `lastValidated` | Carimbo de data e hora da última validação   |

Os índices de qualidade são ajustados dinamicamente:

- **Solicitações com falha** reduzir a pontuação em 10 pontos
- **Pontuação cai para ≤ 10** O proxy → está marcado `inactive`
- Proxies inativos são excluídos da rotação

### Estratégias de Rotação

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

### Disjuntor

O 1proxy Sync possui um disjuntor integrado:

- Depois** 5 falhas de sincronização consecutivas** , outras tentativas de sincronização serão bloqueadas
- Reinicialize com: `resetOneproxyCircuitBreaker()` ou reinicie o servidor
- O status de sincronização está disponível em `GET /api/settings/oneproxy?action=status`

### Limpando proxies 1proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Antidetecção e furtividade

OmniRoute não apenas direciona o tráfego através de um proxy — ele faz com que o tráfego pareça legítimo:

### Falsificação de impressão digital TLS

Usa `wreq-js` para gerar impressões digitais TLS semelhantes a navegador, ignorando sistemas de detecção de bot que sinalizam handshakes TLS fora do navegador.

### Correspondência de impressão digital CLI

O** Alternar impressão digital CLI** (`Settings → Security`) reordena os cabeçalhos HTTP e os campos do corpo JSON para corresponder à assinatura exata dos binários CLI nativos (Claude Code, Codex, etc.). Isso funciona** em cima de** o procurador:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

Você consegue os dois** mascaramento IP** e** solicitar autenticidade** simultaneamente.

### Preservação de proxy IP

Crachás codificados por cores no painel mostram qual nível de proxy está ativo:

| Distintivo | Nível    | Significado                                |
| ---------- | -------- | ------------------------------------------ |
| 🟢         | Global   | Todo o tráfego passa por este proxy        |
| 🟡         | Provedor | Somente o tráfego deste provedor é proxy   |
| 🔵         | Conexão  | Este key/account específico usa este proxy |

O emblema também mostra o proxy IP resolvido para verificação.

---

## Modos de proxy upstream

Para provedores que usam o padrão CLIProxyAPI, OmniRoute oferece suporte a três modos de proxy upstream:

| Modo          | Descrição                                                     |
| ------------- | ------------------------------------------------------------- |
| `native`      | OmniRoute lida diretamente com o roteamento de proxy (padrão) |
| `cliproxyapi` | Delega para uma instância externa CLIProxyAPI                 |
| `fallback`    | Tenta o nativo primeiro, volta para CLIProxyAPI               |

Configurar por provedor:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Painel UI

### Configurações da guia proxy →

- **Procuração global** configuração (definida uma vez para todo o tráfego)
- **Proxy por provedor** substituições
- **Proxy por conexão** atribuições
- **Teste de conexão** através do proxy configurado
- **Emblemas codificados por cores** mostrando o nível de proxy ativo

### Guia Configurações → 1proxy

- **Sincronizar agora** botão para buscar proxies gratuitos
- **Cartões de estatísticas** : Total, Ativo, Qualidade Média, Última Sincronização
- **Filtros** : Protocolo, Código do País, Qualidade Mínima
- **Tabela proxy** com host, protocolo, país, índice de qualidade, latência, anonimato, acesso Google
- **Status de sincronização** painel com rastreamento success/failure e contagem consecutiva de falhas
- **Limpar tudo** para remover todas as entradas 1proxy

---

## Referência API

### Configurações de proxy API

| Método   | Ponto final                                    | Descrição                                |
| -------- | ---------------------------------------------- | ---------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Obtenha a configuração completa do proxy |
| `GET`    | `/api/settings/proxy?level=global`             | Obtenha proxy global                     |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Obtenha proxy do provedor                |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Resolver proxy eficaz                    |
| `PUT`    | `/api/settings/proxy`                          | Atualizar configuração de proxy          |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Remover proxy no nível                   |

### Registro de proxy API

| Método   | Ponto final                                       | Descrição                            |
| -------- | ------------------------------------------------- | ------------------------------------ |
| `GET`    | `/api/v1/management/proxies`                      | Listar todos os proxies              |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Obtenha proxy por ID                 |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Obtenha atribuições de proxy         |
| `POST`   | `/api/v1/management/proxies`                      | Criar proxy                          |
| `PATCH`  | `/api/v1/management/proxies`                      | Atualizar proxy                      |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Excluir proxy                        |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Forçar exclusão                      |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | Atribuição em massa                  |
| `GET`    | `/api/v1/management/proxies/assignments`          | Listar tarefas                       |
| `GET`    | `/api/v1/management/proxies/health`               | Estatísticas de integridade do proxy |

### Túneis API

Para expor sua instância OmniRoute à Internet pública (Cloudflare/ngrok/Tailscale) em vez de rotear a saída por meio de um proxy, consulte [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). O túnel REST API reside em `/api/tunnels/{cloudflared,ngrok,tailscale}/*` e é ortogonal à cadeia de proxy de saída documentada acima.

### 1proxy API

| Método   | Ponto final                            | Descrição                                         |
| -------- | -------------------------------------- | ------------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Listar proxies 1proxy                             |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Obtenha estatísticas do status de sincronização + |
| `GET`    | `/api/settings/oneproxy?action=status` | Obter apenas o status de sincronização            |
| `POST`   | `/api/settings/oneproxy`               | Sincronização de gatilho                          |
| `POST`   | `/api/settings/oneproxy/rotate`        | Girar para o próximo proxy                        |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | Excluir um                                        |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Limpar tudo                                       |

### Proxy upstream API

| Método   | Ponto final                       | Descrição                                |
| -------- | --------------------------------- | ---------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Obtenha a configuração do proxy upstream |
| `PUT`    | `/api/upstream-proxy/:providerId` | Configurar o modo proxy upstream         |
| `DELETE` | `/api/upstream-proxy/:providerId` | Remover configuração de proxy upstream   |

---

## Variáveis de ambiente

| Variável              | Padrão | Descrição                                                           |
| --------------------- | ------ | ------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true` | Habilitar suporte ao proxy SOCKS5 (padrão `true` em `.env.example`) |

---

## Solução de problemas

### "O proxy SOCKS5 está desativado"

Defina `ENABLE_SOCKS5_PROXY=true` em seu arquivo `.env` e reinicie.

### Erros de "soquete desligado" por meio de proxy

Isso é normal com proxies baratos que interrompem conexões ociosas. OmniRoute já lida com isso:

- Desativando keep-alive em conexões proxy (`keepAliveTimeout: 1`)
- Desativando pipeline (`pipelining: 0`)
- Armazenando despachantes em cache para evitar apertos de mão repetidos

Se persistir, tente um proxy diferente ou use o recurso de rotação 1proxy.

### "unsupported_country_region_territory" durante OAuth

Certifique-se de que o proxy esteja configurado** antes** iniciando o fluxo OAuth. OmniRoute roteia a troca de token OAuth por meio do proxy configurado. Defina primeiro um proxy global ou em nível de provedor e depois conecte-se.

### Proxy não está sendo usado

Confira a ordem de resolução:

1. Verifique com `GET /api/settings/proxy?resolve=your-connection-id`
2. Verifique se o proxy `status` é `active` (não `inactive`)
3. Certifique-se de que o escopo de atribuição do proxy corresponda à sua conexão

### Falha na sincronização de 1proxy

Verifique o status da sincronização:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Se `consecutiveFailures >= 5`, o disjuntor desarmou. Reinicie o servidor para redefinir ou aguarde a reinicialização manual.

---

## Esquema de banco de dados

### Tabela `proxy_registry`

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

### Tabela `proxy_assignments`

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

## Verificação de integridade do proxy (v3.8.16 +)

OmniRoute** falha rápida do proxy** mecanismo (`src/lib/proxyHealth.ts`) detecta proxies mortos em < 2s por meio de uma verificação rápida de conexão TCP, em seguida,** armazena em cache o resultado** para evitar sobrecarga por solicitação.

### Como funciona

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

Sem isso, um proxy inativo bloquearia todas as solicitações do `PROXY_TIMEOUT_MS` completo (padrão 30s) antes de falhar.

### Variáveis de ambiente ajustáveis

| Variável                     | Padrão  | Propósito                                                          |
| ---------------------------- | ------- | ------------------------------------------------------------------ |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`  | tempo limite de conexão TCP por verificação de integridade         |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000` | Por quanto tempo um resultado de integridade é armazenado em cache |

**Valores recomendados:**

| Cenário                          | Tempo limite de falha rápida | Cache TTL | Raciocínio                                                                      |
| -------------------------------- | ---------------------------- | --------- | ------------------------------------------------------------------------------- |
| Gateway API de alto rendimento   | 1500 ms                      | 60.000ms  | Cache mais longo e agressivo, com falha rápida para reduzir verificações        |
| Nós distribuídos geograficamente | 3000ms                       | 15.000ms  | Redes mais lentas precisam de mais tempo; cache mais curto para failover rápido |
| Desenvolvimento/teste            | 1000ms                       | 10.000ms  | Iteração rápida em proxies locais                                               |
| Furtivo / anti-detecção          | 2500ms                       | 45.000ms  | Evite sondagens rápidas que possam acionar limites de taxa                      |

### Inspecionando a integridade do proxy

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

O sinalizador `stale` é `true` quando a entrada do cache excede `HEALTH_CACHE_TTL_MS` e a próxima solicitação acionará uma nova verificação.

### Padrões de tipo por proxy

A verificação de integridade usa padrões sensatos baseados no esquema URL :

| Esquema                    | Porta padrão |
| -------------------------- | ------------ |
| `http://`                  | 8080         |
| `https://`                 | 443          |
| `socks5://` / `socks5h://` | 1080         |

As portas personalizadas no URL (`http://host:9999`) sempre têm precedência sobre o esquema padrão.

---

## Análise de proxy e observabilidade

OmniRoute rastreia o uso por proxy para ajudar os operadores a diagnosticar padrões de roteamento, picos de latência e falhas recorrentes.

### O que é rastreado

Para cada solicitação por meio de um proxy configurado, OmniRoute registra:

| Métrica      | Descrição                                                       |
| ------------ | --------------------------------------------------------------- |
| `proxy_url`  | Proxy URL completo (com credenciais de autenticação mascaradas) |
| `provider`   | Provedor upstream ID (openai, antrópico, etc.)                  |
| `latency_ms` | Tempo total de ida e volta, incluindo handshake de proxy        |
| `connect_ms` | TCP conectar apenas tempo                                       |
| `status`     | código de status HTTP do upstream                               |
| `error`      | Classe de erro se a solicitação falhar                          |
| `timestamp`  | ISO 8601 UTC                                                    |

### Acessando os Dados

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

O ponto final real é `/api/usage/proxy-logs` (veja `src/app/api/usage/proxy-logs/route.ts`). Este ponto de extremidade suporta:

- `GET /api/usage/proxy-logs` — recupera logs de proxy
- `DELETE /api/usage/proxy-logs` — limpar todos os logs de proxy

As estatísticas agregadas podem ser consultadas diretamente da tabela `proxy_logs` via SQL, se necessário. O painel UI pode oferecer visualizações agregadas.

### Padrões Comuns

**Detectar um proxy oscilante** (alterna entre success/failure):

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

**Encontre proxies lentos** (latência p95 > 2s):

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

## Árvore de decisão de estratégia de rotação

Quando vários proxies são atribuídos a um escopo, OmniRoute usa um** estratégia de rotação** para escolher qual usar para cada solicitação. A estratégia é configurada no nível do escopo (global, por provedor, por conta, por combinação).

### Estratégias Disponíveis

| Estratégia         | Quando usar                             | Troca                                                                                |
| ------------------ | --------------------------------------- | ------------------------------------------------------------------------------------ |
| `quality` (padrão) | Produção com proxies de qualidade mista | Favorece proxies de alta classificação; pode matar de fome os de baixa classificação |
| `random`           | Distribuição de carga, privacidade      | Distribuição uniforme; ignora sinais de qualidade                                    |
| `sequential`       | Depuração, testes determinísticos       | Percorre os proxies em ordem; fácil de raciocinar sobre                              |

### Árvore de decisão

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

## Exclusão automática de falhas para seus próprios proxies

O pool de mercado 1proxy já degrada automaticamente os proxies com falha por conta própria (consulte [Índices de qualidade do proxy](#proxy-quality-scores) ). Para proxies** você** adicionado ao registro, o agendador de integridade em segundo plano (`src/lib/proxyHealth/scheduler.ts`) fornece o mesmo comportamento de "excluir automaticamente um membro morto da cadeia", sem excluir nada:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Como isso se encaixa em uma cadeia multiproxy:

1. O agendador investiga cada proxy registrado a cada `PROXY_HEALTH_INTERVAL_MS` (padrão 10 min; mínimo 1 min).
2. Depois de `PROXY_AUTO_REMOVE_AFTER` consecutivo** conclusivo** falhas (uma falha de conexão real — um tempo limite ou o próprio 5xx do alvo da sonda nunca conta, consulte [Verificação de integridade do proxy](#proxy-health-checking-v3816) ), o `status` do proxy é definido como `dead`.
3. `dead` é um dos status que o filtro de status ativo usado pela resolução pool/rotation exclui, portanto, a rotação de um escopo (round-robin / random / sticky / latency — consulte [Rotation Strategy Decision Tree](#rotation-strategy-decision-tree) ) para imediatamente de entregar esse proxy para novas solicitações. Nenhum outro proxie no pool é afetado, e todo o pool nunca volta silenciosamente para uma conexão direta — consulte a proteção contra falha [do sistema proxy de 4 níveis](#4-level-proxy-system).
4. O agendador continua investigando os proxies `dead` no mesmo intervalo. A próxima análise bem-sucedida muda `status` de volta para `active` e ele entra novamente na rotação — sem necessidade de adição manual.

Isto é deliberadamente** opt-in e não destrutivo** : por padrão, o agendador apenas conta e registra falhas (consulte a política C em `decision.ts`), e `PROXY_AUTO_DISABLE` nunca exclui uma linha —, é para isso que serve o sinalizador `PROXY_AUTO_REMOVE` separado e mais agressivo. Se ambos estiverem definidos como `true`, `PROXY_AUTO_REMOVE` vence (um proxy prestes a ser excluído não precisa de uma desativação suave no meio). Consulte a referência [do Environment Config](../reference/ENVIRONMENT.md) para obter a lista completa de variáveis.

---

> 📖** Documentação relacionada:**
>
> - [Guia do usuário](../guides/USER_GUIDE.md) — Instalação e configuração geral - [API Referência](../reference/API_REFERENCE.md) — Documentação completa API - [Configuração do ambiente](../reference/ENVIRONMENT.md) — Todas as variáveis de ambiente
