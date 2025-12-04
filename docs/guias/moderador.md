# Guía de Rango Moderador

Como **Moderador**, tienes acceso a herramientas avanzadas para proteger la integridad del servidor. Tienes todos los permisos de [Helper](helper.md), más los siguientes.

!!! danger "Responsabilidad"
    Los comandos de baneo y muteo afectan gravemente la experiencia de juego. Úsalos con responsabilidad y siempre siguiendo la tabla de sanciones oficial.

---

## 🚫 Sanciones Graves (Baneos)

### `/tempban`
*   **Uso:** `/tempban <jugador> <tiempo> <razón>`
*   **Descripción:** Banea al jugador por un tiempo limitado.
*   **Formatos de tiempo:** `10m` (minutos), `2h` (horas), `1d` (días).
*   **Ejemplo:** `/tempban Steve 7d Uso de Hacks (KillAura)`

### `/ban`
*   **Uso:** `/ban <jugador> <razón>`
*   **Descripción:** Baneo permanente. El jugador no podrá volver a entrar nunca.
*   **¿Cuándo usarlo?:** Ataques al servidor, hacks graves reincidentes, spam de bots.

### `/unban`
*   **Uso:** `/unban <jugador>`
*   **Descripción:** Retira un baneo (temporal o permanente).

---

## 🤐 Gestión de Chat (Muteos)

Si un usuario es tóxico pero no merece ser expulsado, siléncialo.

### `/tempmute`
*   **Uso:** `/tempmute <jugador> <tiempo> <razón>`
*   **Descripción:** Silencia al jugador temporalmente. No podrá hablar en el chat público ni privado.
*   **Ejemplo:** `/tempmute Alex 30m Insultos reiterados`

### `/mute`
*   **Uso:** `/mute <jugador> <razón>`
*   **Descripción:** Silencio permanente.
*   **Caso de uso:** Spam de IP o publicidad masiva.

### `/unmute`
*   **Uso:** `/unmute <jugador>`
*   **Descripción:** Devuelve el habla al jugador.

---

## 🛠️ Gestión de Jugadores e Inventarios

Herramientas para corregir situaciones o investigar a fondo.

### `/clearinventory` (o `/ci`)
*   **Uso:** `/ci <jugador>`
*   **Descripción:** Borra TODO el inventario del jugador.
*   **¡Cuidado!:** Esta acción es irreversible. Úsalo solo para borrar items ilegales masivos.

### `/clearenderchest`
*   **Uso:** `/clearenderchest <jugador>`
*   **Descripción:** Borra todo el contenido del cofre de ender del jugador.

### `/fly`
*   **Uso:** `/fly` o `/fly <jugador>`
*   **Descripción:** Activa o desactiva el modo vuelo. Útil para patrullar áreas grandes o construir.

### `/gamemode` (gms, gmsp)
*   **`/gms`**: Te pone en modo **Supervivencia**.
*   **`/gmsp`**: Te pone en modo **Espectador** (útil para atravesar bloques sin ser visto, similar al vanish).

---

## 📜 Historial y Logs Avanzados

### `/banlist`
*   **Uso:** `/banlist`
*   **Descripción:** Muestra la lista de jugadores actualmente baneados.

### `/namehistory`
*   **Uso:** `/namehistory <jugador>`
*   **Descripción:** Muestra los nombres anteriores que ha tenido esa cuenta de Minecraft.
*   **Caso de uso:** Identificar a usuarios que se cambian el nombre para evadir mala fama.

---

## 🎣 Movimiento Avanzado

### `/tphere`
*   **Uso:** `/tphere <jugador>`
*   **Descripción:** Teletransporta al jugador HACIA TI (al revés que el `/tp`).
*   **Caso de uso:** Traer a un usuario a la zona de soporte o cárcel.
