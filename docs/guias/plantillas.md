# Referencia de Plantillas (Templates)

Esta sección detalla los códigos de plantilla preconfigurados en el sistema LiteBans. El uso de plantillas garantiza la estandarización de los tiempos y razones de sanción.

## Plantillas de Bloqueo (Bans)

| ID Plantilla | Razón Automática | Escalada (Ladder) |
| :--- | :--- | :--- |
| `Hack-General` | Uso de Cliente Modificado / Ventaja Injusta | 30d -> Permanente |
| `XRay` | Uso de X-Ray o Paquetes ilegales | 7d -> 14d -> Permanente |
| `Toxicidad-Extrema` | Toxicidad Extrema / Discurso de Odio | 7d -> Permanente |
| `Acoso` | Acoso a usuarios o Staff | 5d -> 30d -> Permanente |

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
