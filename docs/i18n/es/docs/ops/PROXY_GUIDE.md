# 🌐 OmniRoute Proxy Guide (Español)

🌐 **Languages:** 🇺🇸 [English](../../../../ops/PROXY_GUIDE.md) · 🇪🇹 [am](../../../am/docs/ops/PROXY_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/ops/PROXY_GUIDE.md) · 🇦🇿 [az](../../../az/docs/ops/PROXY_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/ops/PROXY_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/ops/PROXY_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/ops/PROXY_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/ops/PROXY_GUIDE.md) · 🇩🇰 [da](../../../da/docs/ops/PROXY_GUIDE.md) · 🇩🇪 [de](../../../de/docs/ops/PROXY_GUIDE.md) · 🇬🇷 [el](../../../el/docs/ops/PROXY_GUIDE.md) · 🇪🇪 [et](../../../et/docs/ops/PROXY_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/ops/PROXY_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/ops/PROXY_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/ops/PROXY_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/ops/PROXY_GUIDE.md) · 🇮🇱 [he](../../../he/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/ops/PROXY_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/ops/PROXY_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/ops/PROXY_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/ops/PROXY_GUIDE.md) · 🇮🇩 [id](../../../id/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/ops/PROXY_GUIDE.md) · 🇮🇹 [it](../../../it/docs/ops/PROXY_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/ops/PROXY_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/ops/PROXY_GUIDE.md) · 🇰🇭 [km](../../../km/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/ops/PROXY_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/ops/PROXY_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/ops/PROXY_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/ops/PROXY_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/ops/PROXY_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/ops/PROXY_GUIDE.md) · 🇲🇲 [my](../../../my/docs/ops/PROXY_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/ops/PROXY_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/ops/PROXY_GUIDE.md) · 🇳🇴 [no](../../../no/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [or](../../../or/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/ops/PROXY_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/ops/PROXY_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/ops/PROXY_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/ops/PROXY_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/ops/PROXY_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/ops/PROXY_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/ops/PROXY_GUIDE.md) · 🇱🇰 [si](../../../si/docs/ops/PROXY_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/ops/PROXY_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/ops/PROXY_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/ops/PROXY_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/ops/PROXY_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/ops/PROXY_GUIDE.md) · 🇮🇳 [te](../../../te/docs/ops/PROXY_GUIDE.md) · 🇹🇭 [th](../../../th/docs/ops/PROXY_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/ops/PROXY_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/ops/PROXY_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/ops/PROXY_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/ops/PROXY_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/ops/PROXY_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/ops/PROXY_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/ops/PROXY_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/ops/PROXY_GUIDE.md)

---

> **Evite los bloqueos geográficos, proteja su identidad y dirija el tráfico AI a través de cualquier proxy — sin complejidad de configuración.**

OmniRoute incluye un sistema de administración de proxy con todas las funciones que le permite enrutar el tráfico ascendente del proveedor AI a través de servidores proxy HTTP, HTTPS o SOCKS5. Ya sea que se encuentre en una región bloqueada, necesite rotación IP o desee tomar huellas digitales sigilosas — esta guía lo cubre todo.

---

## Tabla de contenido

- [¿Por qué utilizar servidores proxy?](#why-use-proxies)
- [Descripción general de la arquitectura](#architecture-overview)
- [Sistema de proxy de 4 niveles](#4-level-proxy-system)
- [Registro de proxy (CRUD)](#proxy-registry-crud)
- [Mercado gratuito 1proxy](#1proxy-free-proxy-marketplace)
- [Rotación de proxy](#proxy-rotation)
- [Antidetección y sigilo](#anti-detection--stealth)
- [Modos de proxy ascendentes](#upstream-proxy-modes)
- [Tablero UI](#dashboard-ui)
- [Referencia API](#api-reference)
- [Variables de entorno](#environment-variables)
- [Solución de problemas](#troubleshooting)

---

## ¿Por qué utilizar servidores proxy?

Muchos proveedores AI restringen el acceso por región geográfica. Desarrolladores en** Rusia, China, Irán, Cuba, Turquía** y otros países encuentran errores como:

```
unsupported_country_region_territory
```

Incluso fuera de las regiones bloqueadas, los proxies son útiles para:

| Caso de uso                   | Descripción                                                                       |
| ----------------------------- | --------------------------------------------------------------------------------- |
| **circunvalación geográfica** | Acceda OpenAI, Anthropic, Codex, Copilot desde países bloqueados                  |
| **rotación IP**               | Distribuya solicitudes entre múltiples IPs para evitar la limitación de velocidad |
| **Privacidad**                | Oculte su IP real de los proveedores ascendentes                                  |
| **Cumplimiento**              | Dirigir el tráfico a través de jurisdicciones específicas                         |
| **Pruebas**                   | Simular solicitudes de diferentes regiones                                        |

---

## Descripción general de la arquitectura

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

### Componentes clave

| Componente                | Archivo                                      | Role                                                                     |
| ------------------------- | -------------------------------------------- | ------------------------------------------------------------------------ |
| **Registro de proxy**     | `src/lib/db/proxies.ts`                      | CRUD para entradas de proxy asignaciones de alcance +                    |
| **Despachador de proxy**  | `open-sse/utils/proxyDispatcher.ts`          | Crea despachadores `undici` ProxyAgent/SOCKS con almacenamiento en caché |
| **Recuperación de proxy** | `open-sse/utils/proxyFetch.ts`               | Envuelve `fetch()` con inyección de despachador de proxy                 |
| **Ruta de configuración** | `src/app/api/settings/proxy/route.ts`        | Configuración de proxy heredado API (GET/PUT/DELETE)                     |
| **Ruta de Gestión**       | `src/app/api/v1/management/proxies/route.ts` | Registro CRUD API (GET/POST/PATCH/DELETE)                                |
| **1proxy DB**             | `src/lib/db/oneproxy.ts`                     | Persistencia del mercado de proxy gratuito                               |

---

## Estado de proxy predeterminado para cuentas nuevas

En** Configuración → Proxy → Configuración global** , usar** Habilite el proxy de forma predeterminada para nuevas conexiones** para elegir el estado de proxy inicial de las cuentas de proveedores recién agregadas.

La nueva configuración controla el estado del proxy inicial de las cuentas de proveedores recién agregadas. No cambia las cuentas existentes ni reemplaza el conmutador de proxy global. Su valor inicial conserva el comportamiento anterior. Desactívelo una vez para crear cuentas futuras con el proxy desactivado de forma predeterminada.

La preferencia se almacena como `defaultNewConnectionProxyEnabled` a través de la Configuración API existente. El valor predeterminado es `true` cuando nunca se guarda. Guardar `false` tiene efecto para las cuentas nuevas posteriores sin reiniciar. `POST /api/providers` acepta un `proxyEnabled` booleano estricto opcional; un `true` o `false` explícito tiene prioridad sobre el valor predeterminado de creación. La omisión de una cuenta duplicada o la reconexión OAuth preserva el estado almacenado de esa cuenta. Las cuentas individuales aún se pueden habilitar o deshabilitar después.

Las transferencias selectivas de proveedores utilizan el valor predeterminado de instalación de destino para cuentas nuevas y preservan la política de destino al reemplazar cuentas existentes. Los conmutadores de proxy no son campos de transferencia portátiles. La restauración completa de la copia de seguridad y la migración histórica JSON/SQL conservan su semántica de restauración existente, incluidos los valores de cuenta guardados y los valores predeterminados del esquema heredado; una restauración completa de la configuración también puede restaurar esta preferencia.

Esta preferencia no asigna un proxy ni establece que uno esté en buen estado o en uso. El enrutamiento real aún depende del conmutador de proxy global y de la configuración de proxy aplicable. Los proveedores sintéticos sin una cuenta persistente, el tráfico OAuth antes de la creación de la cuenta, los proxies environment/system y las redes de servidores externos están fuera de su alcance.

## Sistema de proxy de 4 niveles

OmniRoute admite la configuración de proxy en** cuatro alcances independientes** , resuelto en orden de prioridad:

```
Priority Resolution Order (highest → lowest):

  1. 🔵 Account/Connection Proxy  →  per API key / OAuth connection
  2. 🟡 Provider Proxy            →  per provider (e.g., all OpenAI traffic)
  3. 🟠 Combo Proxy               →  per combo/routing configuration
  4. 🟢 Global Proxy              →  all traffic, all providers
```

### Cómo funciona la resolución

Cuando OmniRoute envía una solicitud a un proveedor ascendente, llama a `resolveProxyForConnectionFromRegistry()`, que verifica cada nivel en orden:

1. **Nivel de cuenta** — ¿Hay un proxy asignado a esta conexión específica ID?
2. **Nivel de proveedor** — ¿Hay un proxy asignado a este proveedor (por ejemplo, `openai`)?
3. **Nivel global** — ¿Hay un proxy global configurado?
4. **Sin proxy** — Conexión directa al proveedor.

El primer partido gana. Esto significa que puede configurar un proxy global como respaldo pero anularlo para proveedores o conexiones específicos.

### Qué se representa

| Tipo de tráfico             | ¿Representado? | Notas                                           |
| --------------------------- | -------------- | ----------------------------------------------- |
| Finalizaciones de chat      | ✅             | Todas las solicitudes `/v1/chat/completions`    |
| Incrustaciones              | ✅             | `/v1/embeddings`                                |
| Generación de imágenes      | ✅             | `/v1/images/generations`                        |
| Audio (TTS/STT)             | ✅             | `/v1/audio/*`                                   |
| intercambio de tokens OAuth | ✅             | Resuelve `unsupported_country_region_territory` |
| Pruebas de conexión         | ✅             | El botón "Probar conexión" utiliza proxy        |
| Actualización de token      | ✅             | Renovación de fondo OAuth                       |
| Sincronización de modelos   | ✅             | Listado y descubrimiento de modelos             |

---

## Registro de proxy (CRUD)

El registro de proxy es una tabla SQLite (`proxy_registry`) que almacena todos sus servidores proxy. Cada proxy tiene:

| Campo      | Tipo   | Descripción                                            |
| ---------- | ------ | ------------------------------------------------------ |
| `id`       | UUID   | Identificador único                                    |
| `name`     | Cadena | Etiqueta legible por humanos                           |
| `type`     | Cadena | Protocolo: `http`, `https`, `socks5`                   |
| `host`     | Cadena | Nombre de host proxy o IP                              |
| `port`     | Entero | Número de puerto                                       |
| `username` | Cadena | Nombre de usuario de autenticación (cifrado en reposo) |
| `password` | Cadena | Contraseña de autenticación (cifrada en reposo)        |
| `region`   | Cadena | Etiqueta de región geográfica                          |
| `notes`    | Cadena | Notas de texto libre                                   |
| `status`   | Cadena | `active` o `inactive`                                  |
| `source`   | Cadena | `manual` o `oneproxy`                                  |

### Creando un proxy

**A través del Panel de control:**

1. Ir a** Configuración de proxy →**
2. Hacer clic** Agregar proxy**
3. Complete el tipo, host, puerto y credenciales de autenticación opcionales
4. Ahorrar

**Vía API:**

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

### Actualizar un proxy

```bash
curl -X PATCH http://localhost:20128/api/v1/management/proxies \
  -H "Content-Type: application/json" \
  -d '{
    "id": "proxy-uuid-here",
    "host": "new-proxy.example.com",
    "port": 9090
  }'
```

> **Nota:** Las credenciales se conservan a menos que envíe explícitamente reemplazos que no estén vacíos. El envío de cadenas vacías para `username`/`password` mantendrá los valores almacenados.

### Eliminar un proxy

```bash
# Fails if proxy is assigned to any scope
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid"

# Force delete (removes assignments too)
curl -X DELETE "http://localhost:20128/api/v1/management/proxies?id=proxy-uuid&force=1"
```

### Listado de proxies

```bash
curl "http://localhost:20128/api/v1/management/proxies?limit=50&offset=0"
```

### Asignación de poderes a ámbitos

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

### Resolución de proxy efectivo

Compruebe qué proxy se utilizaría para una conexión determinada:

```bash
curl "http://localhost:20128/api/settings/proxy?resolve=connection-uuid"
```

Devuelve el proxy resuelto con su nivel (`account`, `provider` o `global`) y fuente.

### Asignación masiva

Asigne un proxy a múltiples proveedores o conexiones a la vez:

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

Los apoderados están incluidos en el**Backup/Restore** sistema. Cuando exportas tu configuración OmniRoute :

1. Ir a** Panel de control Configuración → Copia de seguridad →**
2. Hacer clic** Exportar** Se incluyen el registro de proxy — y las asignaciones.
3. Para restaurar, haga clic en** Importar** y sube el archivo de respaldo

El registro de proxy también admite** upsert por el puerto + del host** — si importa un proxy que ya existe (mismo host y puerto), se actualiza en lugar de crear un duplicado.

### Migración heredada

Si configuró proxies en una versión anterior (registro previo), OmniRoute los migra automáticamente:

```
Legacy key_value store → proxy_registry + proxy_assignments
```

Esto sucede una vez en el primer inicio después de la actualización. Utilice `migrateLegacyProxyConfigToRegistry({ force: true })` para volver a ejecutar.

---

## 1proxy Mercado de proxy gratuito

> 🆕** Contribuido por [@oyi77](https://github.com/oyi77)** — PR [#1847](https://github.com/diegosouzapw/OmniRoute/pull/1847) (Emitir [#1788](https://github.com/diegosouzapw/OmniRoute/issues/1788) )

OmniRoute se integra con el** [1proxy](https://1proxy-api.aitradepulse.com)** plataforma comunitaria para proporcionar acceso a** cientos de servidores proxy validados y gratuitos** de todo el mundo. Esto es perfecto para usuarios que no tienen su propia infraestructura de proxy.

### Cómo funciona

```
┌─────────────┐     Sync      ┌─────────────────┐    Rotate     ┌──────────┐
│  1proxy API │ ────────────▶ │  proxy_registry  │ ────────────▶ │ Provider │
│  (external) │   up to 500   │  source=oneproxy │  by quality   │   API    │
└─────────────┘    proxies    └─────────────────┘               └──────────┘
```

1. **Sincronizar** — OmniRoute obtiene proxies validados del 1proxy API
2. **Almacenar** Los proxy — se guardan en la misma tabla `proxy_registry` con `source = 'oneproxy'`
3. **Filtrar** — Filtrar por protocolo, país, nivel de calidad
4. **Girar** — Elija el mejor proxy utilizando estrategias de calidad, aleatorias o secuenciales
5. **Degradación automática** — Los proxies fallidos ven reducido su nivel de calidad; por debajo del umbral → marcado como inactivo

### Sincronización de servidores proxy

**A través del Panel de control:**

1. Ir a** Configuración → 1proxy** pestaña
2. Hacer clic** "Sincronizar ahora"**
3. Ver estadísticas: proxies totales, recuento activo, calidad promedio, desglose por país

**Vía API:**

```bash
# Trigger sync
curl -X POST http://localhost:20128/api/settings/oneproxy \
  -H "Content-Type: application/json" \
  -d '{}'

# Response:
# { "success": true, "added": 127, "updated": 45, "failed": 2, "total": 172 }
```

### Filtrado de servidores proxy

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

### Puntuaciones de calidad del proxy

Cada proxy de 1proxy viene con metadatos:

| Campo           | Descripción                                      |
| --------------- | ------------------------------------------------ |
| `qualityScore`  | Calificación 0-100 de la validación de 1proxy    |
| `latencyMs`     | Latencia de red medida                           |
| `anonymity`     | `transparent`, `anonymous` o `elite`             |
| `googleAccess`  | Si el proxy puede acceder a los servicios Google |
| `countryCode`   | Código de país ISO de dos letras                 |
| `lastValidated` | Marca de tiempo de la última validación          |

Los puntajes de calidad se ajustan dinámicamente:

- **Solicitudes fallidas** reducir la puntuación en 10 puntos
- **La puntuación cae a ≤ 10** El proxy → está marcado `inactive`
- Los apoderados inactivos quedan excluidos de la rotación

### Estrategias de rotación

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

### Cortacircuitos

La sincronización 1proxy tiene un disyuntor incorporado:

- Después** 5 fallos de sincronización consecutivos** , se bloquean más intentos de sincronización
- Restablecer con: `resetOneproxyCircuitBreaker()` o reiniciar el servidor
- El estado de sincronización está disponible en `GET /api/settings/oneproxy?action=status`

### Borrar servidores proxy de 1proxy

```bash
# Delete a single 1proxy proxy
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?id=proxy-uuid"

# Clear ALL 1proxy proxies (manual proxies are untouched)
curl -X DELETE "http://localhost:20128/api/settings/oneproxy?clearAll=1"
```

---

## Antidetección y sigilo

OmniRoute no sólo enruta el tráfico a través de un proxy — sino que hace que el tráfico parezca legítimo:

### Suplantación de huellas dactilares TLS

Utiliza `wreq-js` para generar huellas digitales TLS similares a las de un navegador, evitando los sistemas de detección de bots que señalan los apretones de manos TLS no son del navegador.

### Coincidencia de huellas dactilares CLI

El** Alternar huella digital CLI** (`Settings → Security`) reordena los encabezados HTTP y los campos del cuerpo JSON para que coincidan con la firma exacta de los binarios nativos CLI (código Claude, Codex, etc.). Esto funciona** encima de** el apoderado:

```
Your IP (blocked) → Proxy IP (US) → Provider API
                    + TLS spoof
                    + CLI fingerprint
```

obtienes ambos** enmascaramiento IP** y** solicitar autenticidad** simultáneamente.

### Preservación de proxy IP

Las insignias codificadas por colores en el panel muestran qué nivel de proxy está activo:

| Insignia | Nivel     | Significado                                 |
| -------- | --------- | ------------------------------------------- |
| 🟢       | Global    | Todo el tráfico pasa por este proxy.        |
| 🟡       | Proveedor | Sólo el tráfico de este proveedor es proxy  |
| 🔵       | Conexión  | Este key/account específico usa este proxy. |

La insignia también muestra el proxy IP resuelto para su verificación.

---

## Modos de proxy ascendentes

Para los proveedores que utilizan el patrón CLIProxyAPI, OmniRoute admite tres modos de proxy ascendentes:

| Modo          | Descripción                                                          |
| ------------- | -------------------------------------------------------------------- |
| `native`      | OmniRoute maneja el enrutamiento proxy directamente (predeterminado) |
| `cliproxyapi` | Delegados a una instancia CLIProxyAPI externa                        |
| `fallback`    | Intenta primero con el nativo, pero vuelve a CLIProxyAPI             |

Configurar por proveedor:

```bash
curl -X PUT "http://localhost:20128/api/upstream-proxy/openai" \
  -H "Content-Type: application/json" \
  -d '{"mode": "native", "enabled": true}'
```

---

## Tablero UI

### Configuración de la pestaña Proxy →

- **proxy global** configuración (establecida una vez para todo el tráfico)
- **Proxy por proveedor** anula
- **Proxy por conexión** asignaciones
- **Prueba de conexión** a través del proxy configurado
- **Insignias codificadas por colores** mostrando el nivel de proxy activo

### Configuración de la pestaña → 1proxy

- **Sincronizar ahora** botón para buscar proxies gratuitos
- **Tarjetas de estadísticas** : Total, Activo, Calidad promedio, Última sincronización
- **Filtros** : Protocolo, Código de país, Calidad mínima
- **tabla de proxy** con host, protocolo, país, nivel de calidad, latencia, anonimato, acceso Google
- **Estado de sincronización** Panel con seguimiento success/failure y recuento de fallos consecutivos.
- **Borrar todo** para eliminar todas las entradas de 1proxy

---

## Referencia API

### Configuración de proxy API

| Método   | Punto final                                    | Descripción                             |
| -------- | ---------------------------------------------- | --------------------------------------- |
| `GET`    | `/api/settings/proxy`                          | Obtener configuración de proxy completa |
| `GET`    | `/api/settings/proxy?level=global`             | Obtener proxy global                    |
| `GET`    | `/api/settings/proxy?level=provider&id=openai` | Obtener proxy de proveedor              |
| `GET`    | `/api/settings/proxy?resolve=connectionId`     | Resolver proxy efectivo                 |
| `PUT`    | `/api/settings/proxy`                          | Actualizar la configuración del proxy   |
| `DELETE` | `/api/settings/proxy?level=provider&id=openai` | Eliminar proxy en el nivel              |

### Registro de proxy API

| Método   | Punto final                                       | Descripción                       |
| -------- | ------------------------------------------------- | --------------------------------- |
| `GET`    | `/api/v1/management/proxies`                      | Listar todos los servidores proxy |
| `GET`    | `/api/v1/management/proxies?id=uuid`              | Obtener proxy por ID              |
| `GET`    | `/api/v1/management/proxies?id=uuid&where_used=1` | Obtener asignaciones de proxy     |
| `POST`   | `/api/v1/management/proxies`                      | Crear proxy                       |
| `PATCH`  | `/api/v1/management/proxies`                      | Actualizar proxy                  |
| `DELETE` | `/api/v1/management/proxies?id=uuid`              | Eliminar proxy                    |
| `DELETE` | `/api/v1/management/proxies?id=uuid&force=1`      | Forzar eliminación                |
| `POST`   | `/api/v1/management/proxies/bulk-assign`          | asignación masiva                 |
| `GET`    | `/api/v1/management/proxies/assignments`          | Listar tareas                     |
| `GET`    | `/api/v1/management/proxies/health`               | Estadísticas de salud del proxy   |

### Túneles API

Para exponer su instancia OmniRoute a la Internet pública (Cloudflare/ngrok/Tailscale) en lugar de enrutar la salida a través de un proxy, consulte [TUNNELS_GUIDE.md](./TUNNELS_GUIDE.md). El túnel REST API se encuentra bajo `/api/tunnels/{cloudflared,ngrok,tailscale}/*` y es ortogonal a la cadena de proxy saliente documentada anteriormente.

### 1proxy API

| Método   | Punto final                            | Descripción                                         |
| -------- | -------------------------------------- | --------------------------------------------------- |
| `GET`    | `/api/settings/oneproxy`               | Lista 1proxys proxy                                 |
| `GET`    | `/api/settings/oneproxy?action=stats`  | Obtener estadísticas del estado de sincronización + |
| `GET`    | `/api/settings/oneproxy?action=status` | Obtener solo el estado de sincronización            |
| `POST`   | `/api/settings/oneproxy`               | Sincronización del disparador                       |
| `POST`   | `/api/settings/oneproxy/rotate`        | Girar al siguiente proxy                            |
| `DELETE` | `/api/settings/oneproxy?id=uuid`       | eliminar uno                                        |
| `DELETE` | `/api/settings/oneproxy?clearAll=1`    | Borrar todo                                         |

### Proxy ascendente API

| Método   | Punto final                       | Descripción                                    |
| -------- | --------------------------------- | ---------------------------------------------- |
| `GET`    | `/api/upstream-proxy/:providerId` | Obtener configuración de proxy ascendente      |
| `PUT`    | `/api/upstream-proxy/:providerId` | Configurar el modo proxy ascendente            |
| `DELETE` | `/api/upstream-proxy/:providerId` | Eliminar la configuración del proxy ascendente |

---

## Variables de entorno

| Variable              | Por defecto | Descripción                                                                            |
| --------------------- | ----------- | -------------------------------------------------------------------------------------- |
| `ENABLE_SOCKS5_PROXY` | `true`      | Habilite la compatibilidad con proxy SOCKS5 ( `true` predeterminado en `.env.example`) |

---

## Solución de problemas

### "El proxy SOCKS5 está deshabilitado"

Configure `ENABLE_SOCKS5_PROXY=true` en su archivo `.env` y reinicie.

### Errores de "colgar el socket" a través del proxy

Esto es normal con servidores proxy baratos que interrumpen las conexiones inactivas. OmniRoute ya maneja esto mediante:

- Deshabilitar keep-alive en conexiones proxy (`keepAliveTimeout: 1`)
- Deshabilitar la canalización (`pipelining: 0`)
- Almacenamiento en caché de los despachadores para evitar apretones de manos repetidos

Si persiste, pruebe con un proxy diferente o utilice la función de rotación 1proxy.

### "unsupported_country_region_territory" durante OAuth

Asegúrese de que el proxy esté configurado** antes** iniciando el flujo OAuth. OmniRoute enruta el intercambio de tokens OAuth a través del proxy configurado. Primero configure un proxy global o de nivel de proveedor y luego conéctese.

### No se utiliza el proxy

Consulta el orden de resolución:

1. Verificar con `GET /api/settings/proxy?resolve=your-connection-id`
2. Compruebe si el proxy `status` es `active` (no `inactive`)
3. Asegúrese de que el alcance de la asignación de proxy coincida con su conexión

### 1 error de sincronización de proxy

Verifique el estado de sincronización:

```bash
curl "http://localhost:20128/api/settings/oneproxy?action=status"
```

Si `consecutiveFailures >= 5`, el disyuntor se ha disparado. Reinicie el servidor para restablecerlo o espere el reinicio manual.

---

## Esquema de base de datos

### Mesa `proxy_registry`

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

### Mesa `proxy_assignments`

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

## Comprobación del estado del proxy (v3.8.16 +)

OmniRoute's** proxy de fallo rápido** El mecanismo (`src/lib/proxyHealth.ts`) detecta servidores proxy inactivos en < 2 mediante una verificación rápida de la conexión TCP, luego** almacena en caché el resultado** para evitar gastos generales por solicitud.

### Cómo funciona

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

Sin esto, un proxy inactivo bloquearía todas las solicitudes durante el `PROXY_TIMEOUT_MS` completo (30 segundos por defecto) antes de fallar.

### Variables de entorno ajustables

| Variable                     | Por defecto | Objetivo                                                   |
| ---------------------------- | ----------- | ---------------------------------------------------------- |
| `PROXY_FAST_FAIL_TIMEOUT_MS` | `2000`      | Tiempo de espera de conexión TCP por control de estado     |
| `PROXY_HEALTH_CACHE_TTL_MS`  | `30000`     | ¿Cuánto tiempo se almacena en caché un resultado de salud? |

**Valores recomendados:**

| Guión                                    | Tiempo de espera de fallo rápido | caché TTL | Razonamiento                                                                                     |
| ---------------------------------------- | -------------------------------- | --------- | ------------------------------------------------------------------------------------------------ |
| Puerta de enlace API de alto rendimiento | 1500ms                           | 60000ms   | Caché más largo y agresivo a prueba de fallos para reducir las comprobaciones                    |
| Nodos geodistribuidos                    | 3000ms                           | 15000ms   | Las redes más lentas necesitan más tiempo; caché más corto para una conmutación por error rápida |
| Desarrollo/pruebas                       | 1000ms                           | 10000ms   | Iteración rápida en proxies locales                                                              |
| Sigilo / anti-detección                  | 2500ms                           | 45000ms   | Evite sondeos rápidos que podrían activar límites de tarifas                                     |

### Inspeccionar el estado del proxy

```ts
import { getAllProxyHealthStatuses, invalidateProxyHealth } from "omniroute/proxyHealth";

const statuses = getAllProxyHealthStatuses();
for (const s of statuses) {
  console.log(`${s.proxyUrl} → healthy=${s.healthy}, stale=${s.stale}`);
}

// Force re-check a specific proxy
invalidateProxyHealth("http://user:pass@203.0.113.7:8080");
```

El indicador `stale` es `true` cuando la entrada de caché ha excedido `HEALTH_CACHE_TTL_MS` y la siguiente solicitud activará una nueva verificación.

### Valores predeterminados de tipo por proxy

La verificación de estado utiliza valores predeterminados sensatos basados en el esquema URL :

| Esquema                    | Puerto predeterminado |
| -------------------------- | --------------------- |
| `http://`                  | 8080                  |
| `https://`                 | 443                   |
| `socks5://` / `socks5h://` | 1080                  |

Los puertos personalizados en URL (`http://host:9999`) siempre tienen prioridad sobre el esquema predeterminado.

---

## Análisis de proxy y observabilidad

OmniRoute rastrea el uso por proxy para ayudar a los operadores a diagnosticar patrones de enrutamiento, picos de latencia y fallas recurrentes.

### Qué se rastrea

Para cada solicitud a través de un proxy configurado, OmniRoute registra:

| Métrico      | Descripción                                                            |
| ------------ | ---------------------------------------------------------------------- |
| `proxy_url`  | Proxy URL completo (con credenciales de autenticación enmascaradas)    |
| `provider`   | Proveedor upstream ID (openai, anthropic, etc.)                        |
| `latency_ms` | Tiempo total de ida y vuelta, incluido el protocolo de enlace de proxy |
| `connect_ms` | TCP solo tiempo de conexión                                            |
| `status`     | código de estado HTTP desde aguas arriba                               |
| `error`      | Clase de error si la solicitud falló                                   |
| `timestamp`  | ISO 8601 UTC                                                           |

### Accediendo a los datos

```bash
# Recent proxy events
curl -H "Authorization: Bearer $OMNIROUTE_KEY" \
  "http://localhost:20128/api/usage/proxy-logs?limit=100"
```

El punto final real es `/api/usage/proxy-logs` (ver `src/app/api/usage/proxy-logs/route.ts`). Este punto final admite:

- `GET /api/usage/proxy-logs` — recuperar registros de proxy
- `DELETE /api/usage/proxy-logs` — borrar todos los registros de proxy

Las estadísticas agregadas se pueden consultar directamente desde la tabla `proxy_logs` a través de SQL si es necesario. El panel UI puede ofrecer vistas agregadas.

### Patrones comunes

**Detectar un proxy agitado** (alterna entre success/failure):

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

**Encuentra proxies lentos** (p95 latencia > 2s):

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

## Árbol de decisión de estrategia de rotación

Cuando se asignan varios servidores proxy a un ámbito, OmniRoute utiliza un** estrategia de rotación** para elegir cuál usar para cada solicitud. La estrategia se configura a nivel de alcance (global, por proveedor, por cuenta, por combo).

### Estrategias disponibles

| Estrategia                 | cuando usar                             | Compensación                                                                                          |
| -------------------------- | --------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| `quality` (predeterminado) | Producción con proxies de calidad mixta | Favorece a los representantes de alta calificación; pueden matar de hambre a los de baja calificación |
| `random`                   | Distribución de carga, privacidad.      | Distribución uniforme; ignora las señales de calidad                                                  |
| `sequential`               | Depuración, pruebas deterministas       | Recorre los proxies en orden; fácil de razonar sobre                                                  |

### Árbol de decisión

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

## Exclusión automática de fallas para sus propios proxy

El grupo de mercado 1proxy ya degrada automáticamente los proxies fallidos por sí solo (consulte [Niveles de calidad de proxy](#proxy-quality-scores) ). Para apoderados** tú** agregado al registro, el programador de salud en segundo plano (`src/lib/proxyHealth/scheduler.ts`) proporciona el mismo comportamiento de "excluir un miembro muerto de la cadena automáticamente", sin eliminar nada:

```bash
# .env — soft-disable a proxy after 3 consecutive failed probes, re-enable it
# automatically once it starts answering probes again.
PROXY_AUTO_DISABLE=true
PROXY_AUTO_REMOVE_AFTER=3
```

Cómo encaja en una cadena multiproxy:

1. El programador sondea cada proxy registrado cada `PROXY_HEALTH_INTERVAL_MS` (predeterminado 10 min; mínimo 1 min).
2. Después de `PROXY_AUTO_REMOVE_AFTER` consecutivo** concluyente** fallas (una falla de conexión real — un tiempo de espera o el propio 5xx del objetivo de la sonda nunca cuenta, consulte [Comprobación del estado del proxy](#proxy-health-checking-v3816) ), el `status` del proxy se establece en `dead`.
3. `dead` es uno de los estados que excluye el filtro de estado activo utilizado por la resolución pool/rotation, por lo que la rotación de un alcance (por turnos/aleatorio/fijo/latencia — consulte [Árbol de decisión de estrategia de rotación](#rotation-strategy-decision-tree) ) inmediatamente deja de entregar ese proxy a nuevas solicitudes. Ningún otro proxy en el grupo se ve afectado, y todo el [grupo](#4-level-proxy-system) — recurre silenciosamente a una conexión directa.
4. El programador sigue sondeando proxies `dead` en el mismo intervalo. La siguiente sonda exitosa vuelve a girar `status` a `active` y vuelve a ingresar a la rotación — no es necesario volver a agregarla manualmente.

Esto es deliberadamente** opt-in y no destructivo** : de forma predeterminada, el programador solo cuenta y registra fallas (consulte la política C en `decision.ts`), y `PROXY_AUTO_DISABLE` nunca elimina una fila — para eso sirve el indicador `PROXY_AUTO_REMOVE` separado y más agresivo. Si ambos están configurados en `true`, `PROXY_AUTO_REMOVE` gana (un proxy a punto de ser eliminado no sirve para una desactivación suave en el medio). Consulte la referencia [de configuración del entorno](../reference/ENVIRONMENT.md) para obtener la lista completa de variables.

---

> 📖** Documentación relacionada:**
>
> - [Guía del usuario](../guides/USER_GUIDE.md) — Instalación y configuración general - [API Referencia](../reference/API_REFERENCE.md) — Documentación completa API - [Configuración de entorno](../reference/ENVIRONMENT.md) — Todas las variables de entorno
