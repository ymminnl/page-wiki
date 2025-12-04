# Protocolo de Actuación: Rango Moderador

## Alcance de Autoridad
Gestión de sanciones graves y seguridad del servidor.

!!! danger "IMPORTANTE: Sistema de Escalada (Ladders)"
    **NUNCA** especifiques el tiempo de un baneo manualmente (ej: `7d`).
    Usa solo el **Nombre de la Plantilla**. El sistema calculará automáticamente si corresponde un baneo temporal o permanente basándose en el historial del jugador.

---

## Protocolo de Bloqueos (Bans)

Para aplicar un baneo, usa el comando `/tempban` seguido de la plantilla. No te preocupes por la duración, la plantilla la define.

### Sintaxis Única
*   **Comando:** `/tempban <jugador> <Plantilla>`
*   **✅ Correcto:** `/tempban Hacker123 Hack-General`
*   **❌ Incorrecto:** `/tempban Hacker123 30d Uso de hacks`

### Plantillas de Moderación
Consulta la sección [Códigos de Sanción](../guias/plantillas.md) para la lista completa.

*   `Hack-General` (Aplica IP Ban automáticamente)
*   `XRay`
*   `Toxicidad-Extrema`
*   `Acoso`

### Revocación
*   **Comando:** `/unban <jugador>`
*   **Nota:** Requiere justificación obligatoria en el StaffChat o Discord.

---

## Protocolo de Silencio (Mutes)

Al igual que los bans, usa plantillas para que el castigo aumente si el usuario repite la falta.

*   **Comando:** `/tempmute <jugador> <Plantilla>`
*   **Ejemplo:** `/tempmute Toxico777 Toxicidad-Leve`

---

## Gestión Administrativa

### Inventarios y Datos
*   **`/clearinventory <jugador>`**: Borrado total de inventario (Irreversible).
*   **`/clearenderchest <jugador>`**: Borrado de Ender Chest.

### Modos de Juego
*   **`/fly`**: Modo vuelo.
*   **`/gmsp`**: Modo espectador (Ghost).

### Investigación Avanzada
*   **`/banlist`**: Lista de baneados activos.
*   **`/namehistory <jugador>`**: Detectar evasión por cambio de nombre.
*   **`/tphere <jugador>`**: Traer jugador a tu posición (Interrogatorios).