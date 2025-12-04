# Referencia de Plantillas (Templates)

Este documento detalla las plantillas de sanción configuradas en el servidor. El sistema utiliza **escalada automática (Ladders)**: si un usuario reincide en la misma falta dentro del tiempo de expiración, la sanción será automáticamente más severa.

## Leyenda
*   🛡️ **IP Ban**: La plantilla bloquea también la dirección IP del usuario.
*   🪜 **Escalada**: Tiempo que tarda en "reiniciarse" el nivel de gravedad de la falta.

---

## Plantillas de Bloqueo (Bans)

| ID Plantilla | Razón Automática | Escalada (Ladder) | Notas |
| :--- | :--- | :--- | :--- |
| `Hack-General` | Uso de Cliente Modificado | 30d -> Permanente | 🛡️ **IP Ban activado** |
| `XRay` | Uso de X-Ray / Texturas | 7d -> 14d -> Permanente | No afecta IP |
| `Toxicidad-Extrema` | Toxicidad Extrema / Odio | 7d -> Permanente | Faltas graves de respeto |
| `Acoso` | Acoso a usuarios o Staff | 5d -> 30d -> Permanente | |
| `Bot-Attack` | Ataque de Bots | **Permanente** | 🛡️ Solo Admins |

**Ejemplo de uso:**
`/tempban Jugador #Hack-General`

---

## Plantillas de Silencio (Mutes)

| ID Plantilla | Razón Automática | Escalada (Ladder) |
| :--- | :--- | :--- |
| `Spam` | Spam / Flood en chat | 15m -> 1h -> 6h -> 1d |
| `Toxicidad-Leve` | Falta de respeto / Toxicidad leve | 30m -> 3h -> 1d -> 3d |
| `Publicidad` | Publicidad no autorizada | 7d -> Permanente |

**Ejemplo de uso:**
`/tempmute Jugador #Spam`

---

## Plantillas de Advertencia (Warns)

| ID Plantilla | Razón Automática | Duración Activa |
| :--- | :--- | :--- |
| `Advertencia-General` | Incumplimiento de normativas | 7 días |
| `Mayusculas` | Uso excesivo de mayúsculas | 3 días |

**Ejemplo de uso:**
`/warn Jugador #Mayusculas`