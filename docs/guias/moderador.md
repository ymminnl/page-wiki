# Protocolo de Actuación: Rango Moderador

## Alcance de Autoridad
Gestión de sanciones graves, seguridad del servidor y administración de usuarios.

---

## Protocolo de Bloqueos (Bans)

El tiempo de sanción es gestionado por el sistema de escalada (Ladder). No se deben especificar duraciones manualmente.

### Aplicación de Sanción
*   **Comando:** `/tempban <jugador> <plantilla>`
*   **Ejemplo:** `/tempban Jugador Hack-General`

Las plantillas definen automáticamente si el bloqueo es temporal o permanente basándose en el historial del usuario.

### Plantillas de Moderación
*   `Hack-General` (Aplica bloqueo de IP)
*   `XRay`
*   `Toxicidad-Extrema`
*   `Acoso`

### Revocación
*   **Comando:** `/unban <jugador>`
*   **Requisito:** Justificación obligatoria en registros internos.

---

## Protocolo de Silencio (Mutes)

*   **Comando:** `/tempmute <jugador> <plantilla>`
*   **Ejemplo:** `/tempmute Jugador Toxicidad-Leve`

---

## Gestión Administrativa

### Datos y Propiedades
*   **`/clearinventory <jugador>`**: Eliminación total de inventario.
*   **`/clearenderchest <jugador>`**: Eliminación de contenido de Ender Chest.

### Modos de Juego
*   **`/fly`**: Modo vuelo.
*   **`/gmsp`**: Modo espectador.

### Investigación Avanzada
*   **`/banlist`**: Listado de bloqueos activos.
*   **`/namehistory <jugador>`**: Historial de cambios de nombre (Mojang).
*   **`/tphere <jugador>`**: Teletransportar usuario a la posición del moderador.
