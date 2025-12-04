# Protocolo de Actuación: Rango Helper

## Descripción del Rol
El rol de Helper tiene como objetivo principal la asistencia a usuarios y la moderación preventiva del chat. Se espera un comportamiento imparcial y profesional en todo momento.

!!! info "Nota Importante"
    Toda sanción debe estar respaldada por evidencia gráfica (capturas de pantalla o video).

---

## Procedimientos de Sanción (Advertencias)

### Comando: /warn
*   **Sintaxis:** `/warn <jugador> <razón>`
*   **Descripción:** Emite una advertencia formal registrada en el historial del usuario.
*   **Aplicación:** Infracciones leves de chat (mayúsculas, spam menor) o comportamiento inadecuado inicial.

### Comando: /kick
*   **Sintaxis:** `/kick <jugador> <razón>`
*   **Descripción:** Desconexión forzada del servidor.
*   **Aplicación:** Situaciones de bloqueo (bug), AFK excesivo en zonas saturadas o advertencia final ante caso omiso de instrucciones.

### Comando: /warnings
*   **Sintaxis:** `/warnings <jugador>`
*   **Descripción:** Consulta el historial de advertencias activas.

---

## Herramientas de Investigación

### Auditoría de Historial
*   **`/checkban <jugador>`**: Verifica estado de bloqueo actual.
*   **`/checkmute <jugador>`**: Verifica estado de silencio actual.
*   **`/history <jugador>`**: Despliega el historial completo de infracciones previas.

### Análisis de IP y Cuentas
*   **`/dupeip <jugador>`**: Escanea coincidencias de IP para detectar cuentas alternas (multicuentas).
*   **`/geoip <jugador>`**: Provee información de geolocalización de la conexión.
    *   *Uso:* Detección de accesos inusuales o cuentas comprometidas.

---

## Herramientas de Supervisión

### Modos de Visibilidad
*   **`/vanish`**: Activa el modo invisible. Es obligatorio su uso durante procesos de monitoreo de sospechosos.

### Inspección de Inventarios
*   **`/invsee <jugador>`**: Visualización del inventario en tiempo real.
*   **`/enderchest <jugador>`**: Visualización del cofre de ender.

### Comunicación Interna
*   **`/staffchat`**: Canal exclusivo de comunicación del equipo.
    *   *Protocolo:* Todo reporte interno o duda sobre sanciones debe tratarse por este medio.

---

## Movimiento
*   **`/tp <jugador>`**: Teletransportación directa a la ubicación del usuario.
