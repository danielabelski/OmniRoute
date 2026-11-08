# Compression Engines (Español)

🌐 **Languages:** 🇺🇸 [English](../../../../compression/COMPRESSION_ENGINES.md) · 🇪🇹 [am](../../../am/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇦 [ar](../../../ar/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇿 [az](../../../az/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇬 [bg](../../../bg/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇩 [bn](../../../bn/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇦 [bs](../../../bs/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇿 [cs](../../../cs/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇰 [da](../../../da/docs/compression/COMPRESSION_ENGINES.md) · 🇩🇪 [de](../../../de/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇷 [el](../../../el/docs/compression/COMPRESSION_ENGINES.md) · 🇪🇪 [et](../../../et/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇷 [fa](../../../fa/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇮 [fi](../../../fi/docs/compression/COMPRESSION_ENGINES.md) · 🇫🇷 [fr](../../../fr/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇪 [ga](../../../ga/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [gu](../../../gu/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ha](../../../ha/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇱 [he](../../../he/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [hi](../../../hi/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇷 [hr](../../../hr/docs/compression/COMPRESSION_ENGINES.md) · 🇭🇺 [hu](../../../hu/docs/compression/COMPRESSION_ENGINES.md) · 🇦🇲 [hy](../../../hy/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇩 [id](../../../id/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [ig](../../../ig/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇹 [it](../../../it/docs/compression/COMPRESSION_ENGINES.md) · 🇯🇵 [ja](../../../ja/docs/compression/COMPRESSION_ENGINES.md) · 🇬🇪 [ka](../../../ka/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇭 [km](../../../km/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [kn](../../../kn/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇷 [ko](../../../ko/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇹 [lt](../../../lt/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇻 [lv](../../../lv/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ml](../../../ml/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [mr](../../../mr/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇾 [ms](../../../ms/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇹 [mt](../../../mt/docs/compression/COMPRESSION_ENGINES.md) · 🇲🇲 [my](../../../my/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇵 [ne](../../../ne/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇱 [nl](../../../nl/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇴 [no](../../../no/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [or](../../../or/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [pa](../../../pa/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇭 [phi](../../../phi/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇱 [pl](../../../pl/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇹 [pt](../../../pt/docs/compression/COMPRESSION_ENGINES.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇴 [ro](../../../ro/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇺 [ru](../../../ru/docs/compression/COMPRESSION_ENGINES.md) · 🇱🇰 [si](../../../si/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇰 [sk](../../../sk/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇮 [sl](../../../sl/docs/compression/COMPRESSION_ENGINES.md) · 🇷🇸 [sr](../../../sr/docs/compression/COMPRESSION_ENGINES.md) · 🇸🇪 [sv](../../../sv/docs/compression/COMPRESSION_ENGINES.md) · 🇰🇪 [sw](../../../sw/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [ta](../../../ta/docs/compression/COMPRESSION_ENGINES.md) · 🇮🇳 [te](../../../te/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇭 [th](../../../th/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇷 [tr](../../../tr/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/compression/COMPRESSION_ENGINES.md) · 🇵🇰 [ur](../../../ur/docs/compression/COMPRESSION_ENGINES.md) · 🇺🇿 [uz](../../../uz/docs/compression/COMPRESSION_ENGINES.md) · 🇻🇳 [vi](../../../vi/docs/compression/COMPRESSION_ENGINES.md) · 🇳🇬 [yo](../../../yo/docs/compression/COMPRESSION_ENGINES.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/compression/COMPRESSION_ENGINES.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/compression/COMPRESSION_ENGINES.md)

---

La compresión OmniRoute se basa en contratos de motor. Un modo puede ejecutar un motor directamente (`caveman` o `rtk`) o una canalización apilada determinista que ejecuta varios motores en orden.

## Modos

| Modo         | Ruta del motor                                                                                             | Entrada prevista                                        |
| ------------ | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| `off`        | ninguno                                                                                                    | Preservación inmediata y exacta                         |
| `lite`       | Ayudantes de cavernícola lite                                                                              | Limpieza siempre activa y de bajo riesgo                |
| `standard`   | Cavernícola                                                                                                | Condensación de indicaciones en lenguaje natural        |
| `aggressive` | Resumidores cavernícolas + history/tool                                                                    | Largas sesiones de chat                                 |
| `ultra`      | Ayudantes de poda cavernícola +                                                                            | Recuperación de límite de contexto                      |
| `rtk`        | RTK                                                                                                        | Salida de terminal, shell, compilación, prueba y git    |
| `omniglyph`  | OmniGlyph                                                                                                  | Contexto como imagen en el cable del proveedor nativo   |
| `stacked`    | Tubería. El valor predeterminado de la solicitud es `session-dedup -> lite`. `rtk -> caveman` es opcional. | Registros de herramientas mixtas y prosa, máximo ahorro |

### perfiles de compresión OmniGlyph

El motor `omniglyph` (paquete `omniglyph`, 1.4.0 +) acepta un perfil semántico con nombre, configurado globalmente a través de `omniglyph.profile` en la configuración de compresión o por paso a través de la configuración de pasos de la canalización apilada:

| Perfil        | Límite                                                                                                                                 |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `aggressive`  | Por defecto. La política de los recibos publicados midió el sistema de imágenes —, los documentos de herramientas y la historia densa. |
| `balanced`    | Mantiene el estado vivo nativo, protege los últimos 8 turnos, colapsa el historial cerrado anterior                                    |
| `coding-safe` | Mantiene la autoridad, los esquemas de herramientas y la salida de herramientas en vivo nativa, protege los últimos 12 turnos          |
| `passthrough` | Rutas sin transformar; el motor se salta                                                                                               |

El perfil es un** techo, no piso** : `mergeCompressionProfileOptions` en el paquete se niega a permitir que una persona que llama anule la reapertura de un carril con pérdida que el perfil cerró, por lo que un `preserveSystemPrompt: false` por paso no puede volver a habilitar la compresión del sistema bajo `coding-safe`.

Medido en esta base de código: `coding-safe` y `balanced` elevan `minCompressChars` a su máximo y mantienen el sistema, los esquemas de herramientas y los resultados de las herramientas nativos, por lo que una sesión que aún no ha acumulado historial se detiene en `below_min_chars` y el motor no transforma nada. Es por eso que el valor predeterminado es `aggressive` en lugar del perfil más seguro.

El paquete resuelve su propio alcance y perfil de modelo a partir de la configuración de su entorno. OmniRoute nunca delega la decisión: el adaptador fija la puerta del modelo al alcance más restrictivo del paquete, por lo que la configuración del entorno del host solo puede limitar la lista de permitidos, nunca ampliarla más allá de los recibos medidos de OmniRoute.

## Registro de motor

El registro vive en `open-sse/services/compression/engines/registry.ts`. Los motores exponen un contrato compartido:

- `id`: ID de motor estable como `caveman` o `rtk`
- `apply(text, config)`: ruta de ejecución heredada utilizada por canalizaciones apiladas
- `compress(input, config)`: ruta de ejecución principal que devuelve texto estadísticas +
- `getConfigSchema()`: devuelve la forma similar a un esquema JSON de una configuración válida
- `validateConfig(config)`: devuelve `{ valid, errors[] }`

El registro utiliza `registerCompressionEngine(engine)` (o `registerEngine` para casos avanzados), que llama `assertValidEngine()` y `validateConfig(defaultConfig)` antes de aceptar. Utilice `unregisterCompressionEngine(id)` para eliminar un motor en tiempo de ejecución.

`strategySelector.ts` registra los motores integrados antes de que se ejecute la compresión. Esto permite que la vista previa, la compresión en tiempo de ejecución, el modo apilado, las pruebas y los motores futuros utilicen la misma ruta de ejecución.

### compresión de descripción MCP (relacionada)

Un registro separado comprime los metadatos de descripción de la herramienta MCP en el nivel de registro — consulte `open-sse/mcp-server/descriptionCompressor.ts` y [MCP-SERVER.md](../frameworks/MCP-SERVER.md). Reutiliza las reglas de Caveman pero opera con metadatos de herramientas, no solicita cargas útiles.

### Motores incorporados adicionales

Más allá de Caveman, RTK y LLMLingua-2, el registro envía varios motores estructurales/sin pérdidas especializados (utilizados por tuberías apiladas, el patio de juegos y las pruebas):

| Motor         | Identificación  | que hace                                                                                                                                                                                                                  |
| ------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CCR           | `ccr`           | Content-Compress-Retrieve (H4): reemplaza grandes bloques de texto contiguos con referencias dirigidas al contenido, por lo que los bloques repeated/large se envían una vez y se hace referencia a ellos posteriormente. |
| espacio libre | `headroom`      | SmartCrusher (H3 + N5): compactación tabular sin pérdidas de cargas útiles de matrices JSON homogéneas en una forma de columna `[N rows]`.                                                                                |
| ionizador     | `ionizer`       | Muestreo de filas Head/middle/tail para bloques homogéneos muy grandes, almacenando el medio elidido como una referencia dirigida al contenido CCR.                                                                       |
| sesión-dedup  | `session-dedup` | Deduplicación entre turnos dirigida al contenido (inspirada en TokenMizer): elimina el texto que ya se vio en turnos anteriores de la misma sesión.                                                                       |

**Instrucción de protocolo de recuperación CCR (#8033):** la primera vez que CCR reemplaza el bloque ≥ 1 en una solicitud, el motor antepone un único mensaje `system` idempotente (que comienza con el centinela `[CCR protocol]` ) enseñando a la persona que llama el contrato de la herramienta → marcador: qué significa un marcador `[CCR retrieve hash=<24hex> chars=N]`, que el hash debe copiarse palabra por palabra (los 24 caracteres hexadecimales, los hashes mal copiados — son la causa probable de errores de "bloque no encontrado"), y que un marcador `[dedup:ref sha=...]` significa "mirar en la historia", no "llamar a la herramienta". La nota esta inyectada** sólo cuando el `tools[]` anunciado por la persona que llama demuestra que realmente puede comunicarse `omniroute_ccr_retrieve`** (`callerSupportsCcrRetrieve()` en `open-sse/services/compression/engines/ccr/protocolInstruction.ts`) — una persona que llama simple y compatible con OpenAI sin esa herramienta nunca recibe una instrucción para llamar a algo a lo que no puede acceder. La idempotencia se aplica escaneando el historial de mensajes del centinela antes de inyectar, por lo que las solicitudes de varios turnos (que reproducen mensajes anteriores) no acumulan la nota una vez por turno.

## Cavernícola

El modo cavernícola se centra en la condensación semántica de la prosa normal:

- conserva bloques de código, URLs, JSON, rutas y datos estructurados
- elimina relleno, cobertura, contexto repetido y fraseo conectivo detallado
- admite paquetes de reglas de archivos con reconocimiento de idioma en `open-sse/services/compression/rules/`
- permanece disponible a través de los modos heredados `standard`, `aggressive` y `ultra`

La superficie del tablero es `Dashboard -> Context & Cache -> Caveman`.

Caveman upstream informa `~75%` menos tokens de salida, `65%` ahorros de salida promedio en puntos de referencia con un rango `22-87%` y una herramienta de compresión de entrada `~46%`. OmniRoute utiliza el número del lado de entrada de Caveman al documentar los ahorros apilados prompt/context ; El modo de salida Cavernícola sigue siendo una característica de comportamiento de respuesta separada.

## RTK

El modo RTK se centra en la salida de comandos y herramientas:

- detecta clases de salida como `git status`, `git branch`, `git diff`, Vitest/Jest/Pytest, pruebas Cargo/Go, compilaciones TypeScript/Vite/Webpack, ESLint, npm audit/installs, registros Docker, shell `find`/`grep`, seguimientos de pila y registros genéricos.
- aplica 49 filtros JSON de `open-sse/services/compression/engines/rtk/filters/`
- admite la canalización declarativa de estilo RTK: eliminación ANSI, reemplazo, cortocircuito de salida coincidente, líneas strip/keep, truncamiento por línea, truncamiento head/tail/max-line y respaldo en vacío
- admite filtros de proyectos controlados por confianza en `.rtk/filters.json` y filtros globales en `DATA_DIR/rtk/filters.json`
- elimina secuencias ANSI, ruido de progreso, líneas repetidas y texto repetitivo inútil
- conserva fallos procesables, advertencias, resúmenes, archivos modificados y contexto final
- Opcionalmente, puede conservar la salida sin procesar redactada para recovery/debugging a través de rutas de administración autenticadas.

La superficie del tablero es `Dashboard -> Context & Cache -> RTK`.

Los detalles operativos para filtros personalizados, confianza, verificación y recuperación de salida sin procesar se encuentran en [`RTK_COMPRESSION.md`](./RTK_COMPRESSION.md).

RTK upstream informa ahorros `60-90%` para la compresión de salida de comando. Su ejemplo README muestra una sesión de código Claude de 30 minutos que va de tokens `~118,000` a `~23,900` o `79.7%` guardado.

## LLMLingua-2 (poda semántica)

el modo LLMLingua-2 realiza** poda de tokens semánticos** en prosa utilizando un pequeño clasificador de tokens ONNX, que complementa los motores Caveman y RTK basados en reglas:

- comprime prosa únicamente en mensajes que no son del sistema; Los bloques de código cercados y otras construcciones preservadas nunca se modifican.
- ejecuta el backend `@atjsh/llmlingua-2` (ONNX vía `@huggingface/transformers`) en un subproceso de trabajo, por lo que la inferencia del modelo nunca bloquea el bucle de eventos de solicitud
- es** apilable** (`stackPriority` 35): en una tubería apilada se ejecuta después de los motores estructurales (CCR, session-dedup, headroom, Caveman) pero antes de `ultra`, ya que la poda semántica es más efectiva en texto ya comprimido estructuralmente — por ejemplo `rtk -> caveman -> llmlingua`
- **falla se abre ante cualquier error** (faltan departamentos opcionales, generación de trabajadores, carga del modelo, inferencia o tiempo de espera) → el texto original se devuelve sin cambios, nunca es un error

Ubicación del motor: `open-sse/services/compression/engines/llmlingua/`. La superficie del tablero es `Dashboard -> Context & Cache -> LLMLingua`.

### Modelos

El modelo predeterminado es**TinyBERT** (`atjsh/llmlingua-2-js-tinybert-meetingbank`, ~ 57 MB, rápido). Una mayor precisión** base BERT** El modelo (`Arcoldd/llmlingua4j-bert-base-onnx`, ~ 710 MB) está disponible a través del campo `model` de configuración del motor. `@huggingface/transformers` descarga el modelo seleccionado de forma perezosa desde HuggingFace Hub a `${DATA_DIR}/models/llmlingua` en la primera llamada (`modelStore.ts`); una anulación de configuración `modelPath` apunta a una copia local (instalaciones sin conexión o aisladas).

### Dependencias opcionales e instalación bajo demanda

La pila de pares de tiempo de ejecución LLMLingua podable es** opcional** . Dos paquetes se declaran como `optionalDependencies` en `package.json` y se mantienen** externo** por la compilación de producción (`scripts/build/prepublish.ts` no los agrupa):

| Paquete              | Versión (pin) | Notas                                              |
| -------------------- | ------------- | -------------------------------------------------- |
| `@atjsh/llmlingua-2` | `2.0.5`       | Paquete de entrada; declara a los demás como pares |
| `js-tiktoken`        | `^1.0.20`     | Tokenizador                                        |

`@huggingface/transformers` está fijado en `^4.2.0` (compartido con la ruta de incorporación local y también rastreado en el paquete independiente); `@atjsh/llmlingua-2@2.0.5` lo empareja con `"^3.5.2 || ^4.0.0"`, por lo que tanto Transformers.js v3 como v4 son compatibles. Desde 2.0.4, `@atjsh/llmlingua-2` ya no requiere `@tensorflow/tfjs`, lo que eliminó el mayor contribuyente (TensorFlow.js) de la pila SLM. Sólo los dos paquetes anteriores son pares SLM podables. Un `npm install` (dev) estándar instala la pila opcional automáticamente a menos que se omitan las dependencias opcionales.

**Por qué bajo demanda:** el paquete publicado por npm, el paquete independiente y el envío de imágenes Docker** sin** estos depósitos para mantenerse delgado. Cuando están ausentes, la puerta de dependencia del trabajador (una sonda de resolución `@atjsh/llmlingua-2` en `worker.ts`) falla y el motor** falla se abre silenciosamente** — al seleccionar LLMLingua se convierte en una operación no operativa (el texto se devuelve sin cambios, no se registra ningún error). Para activarlo en un entorno podado, instale la pila opcional:

```bash
# pin to the versions declared in package.json optionalDependencies
npm install @atjsh/llmlingua-2@2.0.5 js-tiktoken
```

La eliminación `@tensorflow/tfjs` (2.0.4 +) elimina el colaborador ~ 800 MB previamente dominante, — La huella restante son los tiempos de ejecución transformers.js + onnxruntime-node, más el modelo TinyBERT (~ 57 MB) descargado en el primer uso (no a través de npm).

Por entorno:

- **desarrollador/ `npm install`** — se instaló automáticamente a menos que haya pasado `--omit=optional` (o `--no-optional`). No se necesita ninguna acción.
- **Npm global (`npm i -g omniroute`) / independiente** — ejecute el comando de instalación anterior dentro del directorio del paquete instalado o reinstálelo sin omitir los deps opcionales.
- **Docker** — agrega el comando de instalación en una capa de imagen derivada; La imagen publicada se envía delgada por diseño.
- **VPS (PM2)** — instale en el `node_modules` de la aplicación, luego reinicie el proceso para que el trabajador vuelva a sondear la puerta.
- **Raw Next independiente (`npm run build` → `.build/next/standalone/server.js`)** — el rastreo independiente envía NEITHER al trabajador ni a los departamentos opcionales, por lo que el motor se abre silenciosamente. `scripts/build/colocate-standalone.mjs` vuelve a aplicar ambos (el trabajador construye el cierre de depósito opcional + en el árbol independiente); se ejecuta automáticamente a través del gancho `postbuild` npm después de cada compilación. Idempotente, suave cuando no hay depósitos.

**Verifique que esté activo:** con LLMLingua seleccionado, la prosa real en realidad se reduce (el motor deja de abrirse) y la primera solicitud activa la descarga del modelo en `${DATA_DIR}/models/llmlingua`. La puerta prueba intencionalmente solo `@atjsh/llmlingua-2` — los otros pares son solo ESM y `require.resolve` los lanza incluso cuando está presente — por lo que el trabajador aún falla al abrirse si algún par realmente falta en el momento `import()`.

## Tuberías apiladas

El modo apilado ejecuta los pasos de la canalización en orden. El valor predeterminado es:

```txt
rtk -> caveman
```

Úselo para sesiones de agente de codificación donde un mensaje combina la salida del comando con prosa humana o de asistente. RTK primero reduce los registros de herramientas ruidosos y luego Caveman comprime el lenguaje natural restante.

Los pasos de la canalización se configuran con `stackedPipeline` en la configuración de compresión o mediante combinaciones de compresión.

Cuando ambos motores reducen la misma carga útil elegible, los ahorros se acumulan:

```txt
combined = 1 - (1 - RTK savings) * (1 - Caveman input savings)
average  = 1 - (1 - 0.80) * (1 - 0.46) = 89.2%
range    = 1 - (1 - 0.60..0.90) * (1 - 0.46) = 78.4-94.6%
```

## Filtro de árbol de accesibilidad MCP

El filtro inteligente del árbol de accesibilidad MCP es una capa de compresión posterior a la ejecución que se ejecuta en MCP** resultados de la herramienta** , no en indicaciones o contexto. Se dirige a las cargas útiles detalladas del árbol de accesibilidad y de las instantáneas del navegador devueltas por herramientas como Playwright, el uso de computadoras y los servidores MCP de automatización del navegador.

### que hace

1. **Eliminación de ruido** — elimina las entradas generic/text vacías (`- generic:`, `- text: ""`)
2. **Colapso entre hermanos** — cuando ≥ `collapseThreshold` (predeterminado 30) las líneas consecutivas son repeticiones estructurales, las colapsa en las primeras `collapseKeepHead` (predeterminado 10) líneas + un resumen de recuento + las últimas `collapseKeepTail` (predeterminado 5) líneas
3. **Preservación de referencias** Los anclajes — `[ref=eXX]` requeridos por Playwright/computer-use nunca se tocan
4. **Truncamiento duro** — si el texto después del colapso aún excede `maxTextChars` (50,000 predeterminado), se trunca con una sugerencia de navegación para que el agente pueda continuar trabajando

### Ubicación del motor

```txt
open-sse/services/compression/engines/mcpAccessibility/
  index.ts            ← smartFilterText() entry point
  collapseRepeated.ts ← sibling-collapse algorithm
  constants.ts        ← DEFAULT_MCP_ACCESSIBILITY_CONFIG
```

### Configuración

Controlado por `compression.mcpAccessibility` en la configuración global (migración 056). Configuración predeterminada:

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

El filtro solo se aplica a cargas útiles de resultados de herramientas cuyo `type` es `"text"` y cuya longitud excede `minLengthToProcess`. No afecta la compresión rápida ni solicita cargas útiles.

### Ahorros esperados

Entre un 60% y un 80% en los resultados de la herramienta de instantáneas del navegador, según la complejidad de la página. El algoritmo de colapso es O(n) en el recuento de líneas y agrega una latencia insignificante.

### Este filtro frente a los motores de compresión anteriores

| Aspecto                | Cavernícola / RTK / Apilados         | filtro de accesibilidad MCP            |
| ---------------------- | ------------------------------------ | -------------------------------------- |
| Objetivo               | Solicitar mensajes/contexto          | resultados de la herramienta MCP       |
| Desencadenar           | Configuración del modo de compresión | `compression.mcpAccessibility.enabled` |
| Alcance                | Todos los mensajes SSE               | Solo resultados de herramientas        |
| Anclajes de referencia | N/A                                  | Preservado incondicionalmente          |

---

## Combinaciones de compresión

Los combos de compresión son perfiles de compresión denominados que se pueden asignar a combos de enrutamiento:

- `compression_combos`: modo de tiendas, canalización, configuración RTK, configuración de idioma y marcador predeterminado
- `compression_combo_assignments`: asigna un combo de compresión a un combo de enrutamiento
- La integración en tiempo de ejecución resuelve un combo de compresión asignado antes de que se anule el combo genérico.
- los análisis incluyen `compression_combo_id` y `engine`

Superficie del salpicadero: `Dashboard -> Context & Cache -> Compression Combos`.

## Requisitos previos/guía del operador (CCR y session-dedup)

CCR (`ccr`) y `session-dedup` reemplazan o eliminan el texto y dejan un** marcador** detrás. Esta sección es la referencia del operador para conectar un cliente, leer los dos marcadores y recuperar o diagnosticar el contenido elidido. La mecánica de cada motor se trata arriba; esta es la capa "cómo lo ejecuto".

### Transportes y puntos finales

Se puede acceder al servidor MCP que expone las herramientas CCR de tres maneras. La base URL predeterminada es `http://localhost:20128` (`OMNIROUTE_BASE_URL`):

| Transporte                             | URL /comando                            | Notas                                                                                                                                     |
| -------------------------------------- | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| Streamable HTTP (cliente, recomendado) | `http://localhost:20128/api/mcp/stream` | El punto final con el que hablan los clientes actuales MCP.                                                                               |
| Singleton SSE heredado                 | `http://localhost:20128/api/mcp/sse`    | Transporte singleton más antiguo. Él** cierra** sesiones transmitibles; use clientes `streamable-http` contra `/api/mcp/stream`, no este. |
| stdio                                  | `omniroute --mcp`                       | Para la configuración IDE MCP que genera el proceso. No hay bandera `--dev` ; `omniroute --mcp` es el punto de entrada estándar.          |

### Niveles de almacenamiento (lo que sobrevive a un reinicio)

CCR es un** dos niveles** almacenar, no solo en memoria:

- **Nivel caliente en memoria** — límite por bloque 2 MiB, por principal 16 MiB, global 64 MiB. Las entradas por defecto son de 24 TTL (máximo 7 días). La recuperación completa MCP desde la memoria tiene un límite de 256 KiB; cualquier cosa más grande aún es accesible a través de los modos a distancia/grep.
- **Nivel SQLite duradero** (`ccr_blocks`, `COMPRESSION_CCR_DURABLE_STORE`, activado de forma predeterminada) — respalda el nivel en memoria para que un bloque sobreviva al desalojo LRU, a un reinicio o a una recuperación en otra instancia. La fila mantiene el TTL del bloque, por lo que un bloque que pasa su TTL desaparece de ambos niveles.

Tres guardias mantienen el nivel duradero delimitado — un bloque permanece solo en memoria cuando:

1. el bloque ha terminado** 512 KB** (`MAX_DURABLE_BLOCK_BYTES`);
2. el tiempo de ejecución es un tiempo de ejecución en la nube (sin disco local);
3. `COMPRESSION_CCR_DURABLE_STORE=false`.

Entonces, "el bloque desapareció" no es una historia general de reinicio: un bloque sub-512 KB en un tiempo de ejecución local, fuera de la nube, sobrevive a un reinicio a través del nivel duradero hasta que se agota su TTL. Consulte [la referencia del entorno](../reference/ENVIRONMENT.md) para la variable.

### Los dos marcadores

| Marcador                              | Significado                                                                                                                                            | ¿Qué debe hacer el modelo?                                                                                                                                                                                               |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `[CCR retrieve hash=<24hex> chars=N]` | Se almacenó un bloque grande con contenido direccionado.                                                                                               | Llama `omniroute_ccr_retrieve` con el** Hash de 24 hexadecimales copiado palabra por palabra** para recuperar el texto original.                                                                                         |
| `[dedup:ref sha=…]`                   | `session-dedup` texto elidido ya enviado en un turno anterior de la misma sesión. Este es un** mirada atrás intencional** , no una pérdida o un error. | Hacer** no** llama a cualquier herramienta y hazlo** no** Intenta "reconstruirlo". La primera aparición del texto es la copia canónica; el turno actual nunca se reescribe, sino que se deduplica en un turno posterior. |

La revisión `[dedup:ref]` es una decisión de protocolo deliberada — no hay reconstrucción previa al envío. Trátelo como si "este texto exacto ya estuviera en el cable anteriormente en esta sesión".

### Requisitos previos del cliente

- **Clave (estdio):** una persona que llama stdio no tiene identidad por solicitud, por lo que se autentica con `OMNIROUTE_API_KEY` (configurado en `env` del servidor MCP ). Sin él, la persona que llama es anónima y las herramientas que requieren un principal pueden degradarse.
- **`tools[]` es la condición previa de la inyección.** Se inyecta la instrucción de protocolo de recuperación CCR (#8033).** solo** cuando el `tools[]` anunciado en la solicitud demuestra que el cliente realmente puede comunicarse con `omniroute_ccr_retrieve`. La coincidencia es una coincidencia de segmento final delimitada por un separador (`__`, `.`, `/`, `:`). — nunca es una subcadena simple — por lo que un nombre con espacio de nombres como `mcp__gateway__omniroute_ccr_retrieve` todavía cuenta. Un `tools[]` ausente o que no coincide significa que la instrucción _no_ se inyecta, por diseño.
- **`codemode:false` (clientes OpenCode ).** OpenCode utiliza de forma predeterminada el modo Código, que anuncia solo sus herramientas nativas al modelo y** no** coloque las herramientas MCP en la lista nativa `tools[]`. Configure `codemode: false` en la entrada del servidor MCP para que se anuncien las herramientas `omniroute_ccr_*`. Este es un** cliente** configuración, no una OmniRoute. Aún no se inyecta la instrucción CCR : OpenCode nombra una herramienta `<server>_<tool>`, por lo que un servidor llamado `omniroute` expone `omniroute_omniroute_ccr_retrieve` y `_` no es uno de los separadores coincidentes.
- **Directores.** El almacenamiento y la recuperación están aislados por entidad principal autenticada (por clave API ). Una clave sólo ve sus propios bloques.

### Alcances por herramienta

La aplicación del alcance siempre está activada para quienes llaman HTTP/SSE con un alcance limitado. Las herramientas `omniroute_` CCR requieren:

| Herramienta              | Alcance             |
| ------------------------ | ------------------- |
| `omniroute_ccr_store`    | `write:compression` |
| `omniroute_ccr_delete`   | `write:compression` |
| `omniroute_ccr_retrieve` | `read:compression`  |
| `omniroute_ccr_inspect`  | `read:compression`  |
| `omniroute_ccr_list`     | `read:compression`  |
| `omniroute_ccr_stats`    | `read:compression`  |

Un alcance faltante devuelve un** resultado del error de la herramienta MCP** (`isError: true`, no un HTTP 403 — el `403 LOCAL_ONLY` es la autenticación de protección de ruta de bucle invertido separada): `Error: Insufficient MCP scopes for <tool>. Missing: <scope>.` Una clave remota mínima puede contener `mcp:connect` (autoriza la exclusión solo local `/api/mcp/` ) más el alcance read/write específico que necesita.

### Matriz de clientes

| Cliente               | Transporte                                        | Configuración para usar                                                                                                                                                                                                                                     | `tools[]` anunciado? (instrucción → CCR inyectada)                                                                                                                                                              |
| --------------------- | ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Código Claude         | streaming-http                                    | `claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream`                                                                                                                                                                           | Sí — compatible con MCP; inyectado.                                                                                                                                                                             |
| Cursor / Cline        | `stdio`** o** `streamable-http`                   | stdio: `omniroute --mcp` con `OMNIROUTE_API_KEY` en `env`; o una entrada MCP remota que apunte a `http://localhost:20128/api/mcp/stream` (consulte [la Guía de instalación → MCP Client Configuration](../guides/SETUP_GUIDE.md#mcp-client-configuration) ) | Sí — anuncia las herramientas `omniroute_ccr_*`.                                                                                                                                                                |
| OpenCode              | streaming-http                                    | `opencode mcp add omniroute --url http://localhost:20128/api/mcp/stream`, más `codemode: false`                                                                                                                                                             | Herramientas anunciadas sólo con `codemode: false`; la instrucción aún no se inyecta porque `omniroute_omniroute_ccr_retrieve` no coincide (consulte [Requisitos previos del cliente](#client-prerequisites) ). |
| Compatible con OpenAI | HTTP compatible con OpenAI (finalización de chat) | cliente estándar de finalización de chat contra el punto final compatible con OpenAI                                                                                                                                                                        | **Nunca** — a una persona que llama simplemente compatible con OpenAI nunca se le dice que llame a la herramienta y la instrucción no se inyecta.                                                               |

### Límites de recuperación y paginación

Los resultados del texto de la herramienta MCP se recortan alrededor de `mcpAccessibility.maxTextChars` ( `50000` predeterminado). La recuperación `full` de un bloque tiene un límite de 256 KiB —** no hay recuperación completa ilimitada** . Cuando el `chars=N` de un bloque es grande, paginalo en lugar de extraerlo todo:

- Regla de oro:**`chars > 40000` → usa un `mode`** , nunca un completo completo.
- `mode:"grep"` — regex `pattern` coincide línea por línea, hasta 1000 líneas coincidentes (`unique: true` elimina repeticiones), más barato para "encontrar la línea que necesito".
- `mode:"lines"` — un rango de 1 línea indexada; necesita tanto `start` como `end`.
- `mode:"head"` / `mode:"tail"` — first/last `n` líneas.
- `mode:"stats"` — recuentos de líneas, caracteres y bytes sin el cuerpo.

Utilice `mode:"lines"` con `start`/`end` para recorrer un bloque largo de páginas en lugar de solicitar todo de una vez.

### Denominación de herramientas

La herramienta de recuperación actualmente se llama `omniroute_ccr_retrieve` (el prefijo `omniroute_` es una solución alternativa anticuada para las colisiones de nombres entre servidores). Un nombre de herramienta con sufijo acotado más limpio y una solución para los resultados MCP JSON truncados en mitad de la cadena se rastrean como seguimientos ascendentes; Esta página documenta únicamente el comportamiento actual enviado.

### Ciclo de vida de la sesión

Las sesiones Streamable-HTTP quedan inactivas y el servidor las cosecha; la ventana inactiva es la constante `MCP_SESSION_IDLE_MS` (a la que se hace referencia por nombre, no por un valor codificado, por lo que esta página no cambia cuando cambia). El síntoma de una sesión inactiva es un HTTP 404 con `Unknown Mcp-Session-Id` — el remedio es volver a conectar o reiniciar la sesión,** no** para rotar una clave, cambiar un alcance o cambiar el nombre de una herramienta.

## superficie API

| Ruta                                   | Objetivo                                                                       |
| -------------------------------------- | ------------------------------------------------------------------------------ |
| `/api/settings/compression`            | Configuración de compresión global (incluye configuración `mcpAccessibility` ) |
| `/api/compression/preview`             | Vista previa de cualquier modo de compresión                                   |
| `/api/compression/language-packs`      | Lista de paquetes de idiomas disponibles de Caveman                            |
| `/api/context/caveman/config`          | Alias de configuración de cavernícola                                          |
| `/api/context/rtk/config`              | Valores predeterminados y configuraciones RTK                                  |
| `/api/context/rtk/filters`             | catálogo de filtros RTK                                                        |
| `/api/context/rtk/test`                | punto final RTK preview/test                                                   |
| `/api/context/rtk/raw-output/[id]`     | Recuperación de salida sin procesar autenticada y redactada                    |
| `/api/context/combos`                  | Combo de compresión CRUD                                                       |
| `/api/context/combos/[id]/assignments` | Asignación de combinación de enrutamiento CRUD                                 |
| `/api/context/analytics`               | Alias de análisis de compresión                                                |

Las rutas de administración requieren autenticación de administración o verificaciones de políticas de clave API.

## Herramientas MCP

La compresión expone cinco herramientas MCP :

| Herramienta                         | Alcance             | Objetivo                                       |
| ----------------------------------- | ------------------- | ---------------------------------------------- |
| `omniroute_compression_status`      | `read:compression`  | Configuración, análisis, estadísticas de caché |
| `omniroute_compression_configure`   | `write:compression` | Actualizar la configuración global             |
| `omniroute_set_compression_engine`  | `write:compression` | Modo de configuración y canalización opcional  |
| `omniroute_list_compression_combos` | `read:compression`  | Listar combinaciones de compresión             |
| `omniroute_compression_combo_stats` | `read:compression`  | Leer análisis combo/engine                     |

## Alcance y exclusiones

**Las incrustaciones nunca se comprimen.** `open-sse/handlers/embeddings.ts` nunca llama a ningún motor de compresión — los cuerpos request/response pasan directamente al ejecutor intactos. Esto es estructural hoy (las incrustaciones y las finalizaciones de chat son controladores separados), no una verificación de tiempo de ejecución, pero significa que la preocupación por la distorsión vectorial en #8034 no tiene superficie de exposición en la ruta de las incrustaciones.

**Filtro de exclusión Per-model/endpoint (#8034).** Para completar el chat, un operador puede nombrar identificadores de modelo/objetivos `provider/model` que nunca deben comprimirse — una barrera de seguridad útil si la compresión se conecta más cerca de una ruta adyacente a las incrustaciones más adelante y, en general, útil para cualquier modelo cuya indicación exacta byte por byte sea importante (evaluaciones deterministas, prefijos sensibles a caché, etc.).

- Campo de configuración: `exclusions?: string[]` en la configuración de compresión global (`GET`/`PUT /api/settings/compression`), persiste a través del espacio de nombres de compresión `key_value` existente (`src/lib/db/compression.ts`) — sin tabla nueva.
- Pestaña Panel de control:** Panel → Compresión → Exclusiones** (`/dashboard/compression/exclusions`).
- Sintaxis del patrón: `*` es el único comodín. Todos los demás metacaracteres de expresiones regulares en un patrón se escapan antes de hacer coincidir, por lo que `gpt-5.6` coincide solo con la cadena literal, nunca con `gpt-5x6` (seguro para ReDoS, limitado, sin cuantificadores anidados). Los patrones coinciden sin distinguir entre mayúsculas y minúsculas tanto con la identificación del modelo simple como con el compuesto `provider/model` — `gpt-5-6`, `openai/gpt-5-6` y `openai/*`, todos funcionan, y `*` por sí solo excluye todos los modelos.
- Coincidencia: `isCompressionExcluded()` / `normalizeCompressionExclusions()` en `open-sse/services/compression/exclusions.ts`. `chatCore.ts` comprueba el objetivo excluido justo después de resolver la configuración de compresión,** antes de que cualquier motor funcione** y trata una coincidencia exactamente como si la compresión estuviera globalmente deshabilitada — el cuerpo de la solicitud sea probablemente idéntico en bytes. El salto se registra a través de `writeCompressionSkip(..., "excluded")` para visibilidad analítica.
- Predeterminado (lista empty/absent ): idéntico al comportamiento anterior a #8034 — no excluye nada.

## Limitaciones conocidas

- **LLMLingua-2 (SLM) requiere departamentos opcionales ubicados conjuntamente.** El trabajador solo se ejecuta en una compilación de producción cuando los pares `@atjsh/llmlingua-2` + están ubicados en `dist/node_modules` (consulte `scripts/build/colocateOptionals.mjs`, #4286). Sin ellos, el motor falla (devuelve el texto original). La resolución del trabajador ya no depende de `import.meta.url` (muere en el paquete independiente) — se ancla en el tiempo de ejecución cwd/ `argv[1]`.
- **Los paquetes de idioma de Caveman `de` / `fr` / `ja` son parciales.** Envían reglas `context` + `filler` + `structural` pero no paquetes `dedup` / `ultra`, por lo que la intensidad `ultra` no es más fuerte que `full` para esos idiomas (usan solo sus propias reglas — no hay un recurso silencioso a las reglas `dedup`/`ultra` en inglés, que arruinarían el texto extranjero). `en` / `es` / `id` / `pt-BR` están completos. Se aceptan aportes de `dedup.json` + `ultra.json` para los paquetes parciales.
- **La telemetría apilada solo enumera los motores que se comprimieron.** Un paso de tubería apilada cuyo motor funcionó pero produjo un ahorro del 0 % devuelve `stats:null` y, por lo tanto, no aparece en `engineBreakdown` — indistinguible de un paso que se omitió. Distinguir "ejecutado, 0 %" de "omitido" requeriría un cambio de modelo de desglose y se pospone.

## Validación

Las puertas enfocadas para esta área son:

```bash
node --import tsx/esm --test tests/unit/compression/rtk-*.test.ts tests/unit/compression/pipeline-integration.test.ts tests/unit/compression/context-compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/*.test.ts tests/golden-set/*.test.ts tests/integration/compression-pipeline.test.ts tests/unit/api/compression/compression-api.test.ts
node --import tsx/esm --test tests/unit/compression/mcpAccessibility*.test.ts
npm run typecheck:core
```
