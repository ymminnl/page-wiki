# Protocolo de Actuación: Rango Helper

## Descripción del Rol
El rol de Helper tiene como objetivo principal la asistencia a usuarios y la moderación preventiva del chat.

!!! failure "Prohibido Sanciones Manuales"
    **NO** escribas razones o tiempos manualmente. Debes usar siempre los **Códigos de Plantilla** para que el sistema registre correctamente la infracción.

---

## Procedimientos de Sanción

### Advertencias (`/warn`)
El comando de advertencia debe usarse siempre con una plantilla para asegurar uniformidad.

*   **Sintaxis Correcta:** `/warn <jugador> <Plantilla>`
*   **❌ Incorrecto:** `/warn Steve deja de hacer spam`
*   **✅ Correcto:** `/warn Steve Mayusculas`
    *(El sistema pondrá automáticamente la razón y duración)*.

### Silencios (`/tempmute`)
Para casos de spam o toxicidad rápida.

*   **Sintaxis Correcta:** `/tempmute <jugador> <Plantilla>`
*   **Ejemplo:** `/tempmute Steve Spam`
    *(Si es la primera vez, le dará 15m. Si es la quinta, le dará 30 días automáticamente).*

### Listado de Plantillas Comunes (Helper)
*   `Mayusculas`
*   `Advertencia-General`
*   `Spam`
*   `Toxicidad-Leve`
*   `Publicidad`

---

## Herramientas de Investigación

### Auditoría
*   **`/history <jugador>`**: Muestra el historial. Fundamental revisar esto antes de sancionar para ver si es reincidente.
*   **`/checkban <jugador>`** / **`/checkmute <jugador>`**: Verificar estado actual.

### Análisis de IP
*   **`/dupeip <jugador>`**: Revisa si el jugador tiene otras cuentas.
*   **`/geoip <jugador>`**: Ubicación de conexión.

---

## Herramientas de Supervisión

*   **`/vanish`**: Modo invisible obligatorio para espectar.
*   **`/invsee <jugador>`**: Ver inventario.
*   **`/staffchat`**: Comunicación interna.
*   **`/tp <jugador>`**: Teletransporte.