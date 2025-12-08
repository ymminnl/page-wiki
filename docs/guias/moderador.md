# Moderadores

## Autoridad
Gestión de sanciones graves, seguridad del servidor y administración de usuarios. Incluye todas las competencias del rango Helper.

---

## Bans (Bloqueos)

*   **`/ban <jugador> <plantilla>`**: Bloquea el acceso al servidor. La plantilla define si es temporal o permanente.
*   **`/unban <jugador>`**: Revoca un bloqueo activo. Requiere justificación.
*   **`/banlist`**: Muestra la lista de los últimos usuarios bloqueados.

### Plantillas de Moderación
Puedes ver la lista completa y sus códigos aquí:
👉 [**Ver todas las Plantillas**](../plantillas.md)

*   `Hack-General` (Aplica bloqueo de IP automático)
*   `XRay`
*   `Toxicidad-Extrema`
*   `Acoso`

---

## Mutes y Warns

*   **`/mute <jugador> <plantilla>`**: Silencia al usuario en el chat.
*   **`/unmute <jugador>`**: Revoca un silencio activo.
*   **`/warn <jugador> <plantilla>`**: Emite una advertencia formal.
*   **`/unwarn <jugador>`**: Elimina una advertencia específica del historial.
*   **`/warnings <jugador>`**: Muestra el listado de advertencias activas.

---

## Administración

*   **`/clearinventory <jugador>`**: Borra permanentemente todo el inventario del jugador.
*   **`/clearenderchest <jugador>`**: Borra permanentemente el contenido del Ender Chest.
*   **`/freeze <jugador>`**: Congelar movimiento del usuario.
*   **`/kick <jugador>`**: Desconexión forzada del servidor.

## Modos de Juego

*   **`/fly`**: Activa o desactiva el modo de vuelo.
*   **`/gms`**: Cambia tu modo de juego a Supervivencia.
*   **`/gmsp`**: Cambia tu modo de juego a Espectador (Ghost Mode).
*   **`/tphere <jugador>`**: Teletransporta al usuario hacia tu posición.
*   **`/tp <jugador>`**: Teletransportarse a la posición de un usuario.
*   **`/mv`**: Acceso a comandos de gestión de mundos (Multiverse).

---

## Investigación Avanzada

*   **`/namehistory <jugador>`**: Historial de cambios de nombre de usuario (Mojang).
*   **`/dupeip <jugador>`**: Detección de cuentas compartidas o multicuentas.
*   **`/iphistory <jugador>`**: Registro histórico de IPs de conexión.
*   **`/geoip <jugador>`**: Localización geográfica de la IP.
*   **`/history <jugador>`**: Historial completo de LiteBans.
*   **`/socialspy`**: Monitorización de mensajes privados.
*   **`/invsee`** / **`/enderchest`**: Inspección de inventarios.
*   **`/vanish`**: Modo invisible.
*   **`/staffchat`**: Comunicación interna.

---

## CoreProtect (Logs e Inspección)
Herramienta fundamental para investigar robos y grifeos.

!!! info "Funciones Restringidas"
    Los comandos de restauración (`/co rollback`, `/co restore`) están **desactivados** para este rango por seguridad, para evitar alteraciones accidentales en el mapa. Si necesitas revertir un grifeo masivo, solicita ayuda a un Admin.

### Comandos de Inspección
*   **`/co inspect`** o **`/co i`**: Activa el modo inspector.
    *   Golpea un bloque (click izq) para ver quién lo puso/rompió.
    *   Interactúa (click der) con cofres, puertas o palancas para ver quién los usó.
*   **`/co near`**: Busca cambios en un radio de 5 bloques alrededor de tu posición.
*   **`/co status`**: Muestra el estado del plugin y la versión.

### Búsqueda Avanzada (`/co lookup`)
Usa `/co lookup` o `/co l` para buscar en los registros sin modificar nada.
**Formato:** `/co l <parámetros>`

#### Parámetros Disponibles
Puedes combinarlos como necesites (orden no importa).

*   **`u:<usuario>`**: Filtra por jugador.
    *   Ej: `u:Notch` (Solo Notch)
    *   Ej: `u:Notch,Jeb` (Notch O Jeb)
*   **`t:<tiempo>`**: Tiempo atrás a investigar. (w=semanas, d=días, h=horas, m=minutos, s=segundos).
    *   Ej: `t:10m` (Últimos 10 min)
    *   Ej: `t:2d5h` (Últimos 2 días y 5 horas)
*   **`r:<radio>`**: Radio de bloques desde tu posición.
    *   Ej: `r:10` (10 bloques alrededor)
    *   Ej: `r:#global` (Todo el servidor)
*   **`a:<acción>`**: Filtra por tipo de acción.
    *   `block`: Bloques puestos/rotos.
    *   `container`: Cofres (ítems metidos/sacados).
    *   `chat`: Mensajes de chat.
    *   `kill`: Mobs/animales matados.
    *   `click`: Interacciones (puertas, botones).
    *   `session`: Conexiones/Desconexiones.
    *   `username`: Cambios de nombre.
*   **`i:<incluir>`**: Incluir solo bloques/ítems específicos.
    *   Ej: `i:stone` (Solo piedra)
    *   Ej: `i:diamond_ore,gold_ore` (Solo menas de diamante u oro)
*   **`e:<excluir>`**: Ignorar bloques/ítems específicos.
    *   Ej: `e:tnt` (Mostrar todo MENOS tnt)

#### Ejemplos Prácticos
*   **¿Quién robó diamantes de este cofre hoy?**
    *   `/co l a:container i:diamond t:24h r:5`
*   **¿Qué dijo este usuario hace poco?**
    *   `/co l u:JugadorToxico a:chat t:1h`
*   **¿Quién rompió bloques aquí?**
    *   `/co l a:block r:10 t:1h`
*   **Ver logins de un usuario**
    *   `/co l u:Sospechoso a:session t:30d`

### Comandos Administrativos (Solo Admins)
Estos comandos modifican el mundo o la base de datos. **NO USAR.**
*   `/co rollback` / `/co rb`
*   `/co restore` / `/co rs`
*   `/co purge`
*   `/co migrate-db`
*   `/co consumer`