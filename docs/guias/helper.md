# Protocolo de Actuación: Rango Helper

## Descripción del Rol
Asistencia a usuarios y moderación preventiva del chat.

---

## Sistema de Sanciones Automatizado

El servidor utiliza un sistema de plantillas predefinidas. Es obligatorio utilizar el identificador de la plantilla en lugar de escribir razones manuales.

### Advertencias
Emite una advertencia registrada en el historial.

*   **Comando:** `/warn <jugador> <plantilla>`
*   **Ejemplo:** `/warn Jugador Mayusculas`

### Silencios (Mutes)
Aplica un silencio temporal. La duración es calculada automáticamente por el sistema según la reincidencia.

*   **Comando:** `/tempmute <jugador> <plantilla>`
*   **Ejemplo:** `/tempmute Jugador Spam`

### Lista de Plantillas Disponibles
*   `Mayusculas`
*   `Advertencia-General`
*   `Spam`
*   `Toxicidad-Leve`
*   `Publicidad`

---

## Herramientas de Investigación

*   **`/history <jugador>`**: Visualizar historial de sanciones.
*   **`/checkban <jugador>`**: Verificar estado de bloqueo.
*   **`/checkmute <jugador>`**: Verificar estado de silencio.
*   **`/dupeip <jugador>`**: Escaneo de coincidencias de IP (Multicuentas).
*   **`/geoip <jugador>`**: Geolocalización de la conexión.

---

## Herramientas de Supervisión

*   **`/vanish`**: Modo invisible.
*   **`/invsee <jugador>`**: Inspección de inventario.
*   **`/staffchat`**: Canal de comunicación interna.
*   **`/tp <jugador>`**: Teletransportación.
