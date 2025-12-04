# Referencia de Plantillas (Templates)

Este documento detalla las plantillas de sanción configuradas. El sistema utiliza **escalada automática (Ladders)**.

## Leyenda
*   🛡️ **IP Ban**: Bloquea también la dirección IP.
*   👮 **Rango**: Nivel mínimo de staff requerido para usar esta plantilla.

---

## Plantillas de Bloqueo (Bans)

| ID Plantilla | Rango Mínimo | Razón Automática | Escalada (Ladder) | Notas |
| :--- | :--- | :--- | :--- | :--- |
| `Hack-General` | **Moderador** | Uso de Cliente Modificado | 30d -> Permanente | 🛡️ **IP Ban** |
| `XRay` | **Moderador** | Uso de X-Ray / Texturas | 7d -> 14d -> Permanente | |
| `Toxicidad-Extrema` | **Moderador** | Toxicidad Extrema / Odio | 7d -> Permanente | |
| `Acoso` | **Moderador** | Acoso a usuarios o Staff | 5d -> 30d -> Permanente | |
| `Bot-Attack` | **ADMIN** | Ataque de Bots | **Permanente** | 🛡️ **IP Ban** |

**Ejemplo de uso:**
`/tempban Jugador #Hack-General`

---

## Plantillas de Silencio (Mutes)

| ID Plantilla | Rango Mínimo | Razón Automática | Escalada (Ladder) |
| :--- | :--- | :--- | :--- |
| `Spam` | **Helper** | Spam / Flood en chat | 15m -> 1h -> 6h -> 1d |
| `Toxicidad-Leve` | **Helper** | Falta de respeto / Toxicidad leve | 30m -> 3h -> 1d -> 3d |
| `Publicidad` | **Helper** | Publicidad no autorizada | 7d -> Permanente |

**Ejemplo de uso:**
`/tempmute Jugador #Spam`

---

## Plantillas de Advertencia (Warns)

| ID Plantilla | Rango Mínimo | Razón Automática | Duración Activa |
| :--- | :--- | :--- | :--- |
| `Advertencia-General` | **Helper** | Incumplimiento de normativas | 7 días |
| `Mayusculas` | **Helper** | Uso excesivo de mayúsculas | 3 días |

**Ejemplo de uso:**
`/warn Jugador #Mayusculas`
