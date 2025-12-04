# Protocolo de Actuación: Rango Moderador

## Alcance de Autoridad
El Moderador posee permisos elevados para la gestión de sanciones graves y administración de la integridad del servidor. Este rango incluye todas las competencias del rango Helper.

!!! warning "Advertencia"
    El uso incorrecto de las herramientas de bloqueo (ban) puede resultar en la revocación de permisos. Siga estrictamente la tabla de tiempos estipulada.

---

## Protocolo de Bloqueos (Bans)

### Bloqueo Temporal
*   **Comando:** `/tempban <jugador> <tiempo> <razón>`
*   **Sintaxis de Tiempo:** `m` (minutos), `h` (horas), `d` (días). Ej: `12h`.
*   **Aplicación:** Infracciones medias (Hacks confirmados primera ofensa, toxicidad reiterada).

### Bloqueo Permanente
*   **Comando:** `/ban <jugador> <razón>`
*   **Aplicación:** Infracciones críticas (Ataques al servidor, duplicación de ítems, reincidencia de hacks).

### Revocación
*   **Comando:** `/unban <jugador>`
*   **Nota:** Requiere justificación en los logs internos.

---

## Protocolo de Silencio (Mutes)

### Silencio Temporal
*   **Comando:** `/tempmute <jugador> <tiempo> <razón>`
*   **Aplicación:** Infracciones de chat reiteradas o graves.

### Silencio Permanente
*   **Comando:** `/mute <jugador> <razón>`
*   **Aplicación:** Spam masivo de bots o publicidad no autorizada.

---

## Gestión Administrativa

### Inventarios y Datos
*   **`/clearinventory <jugador>`**: Eliminación total del inventario. Acción irreversible.
*   **`/clearenderchest <jugador>`**: Eliminación del contenido del cofre de ender.

### Modos de Juego y Vuelo
*   **`/fly`**: Habilita el modo vuelo para facilitar la supervisión aérea.
*   **`/gamemode spectator`** (`/gmsp`): Modo espectador para atravesar estructuras y observar sin interferir en las mecánicas de juego.

### Registros Avanzados
*   **`/banlist`**: Listado de usuarios bloqueados activos.
*   **`/namehistory <jugador>`**: Historial de cambios de nombre de usuario (Mojang). Útil para identificar evasión de identidad.

---

## Movimiento Avanzado
*   **`/tphere <jugador>`**: Teletransporta al usuario a la posición del moderador.
    *   *Uso:* Interrogatorios o traslado a zonas de soporte.