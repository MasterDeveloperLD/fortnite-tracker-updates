# 🎮 Fortnite Score Overlay

Overlay en tiempo real para Fortnite que muestra tu marcador contra otros jugadores (kills vs deaths), con sistema de prioridades, búsqueda en overlay y actualizaciones automáticas.

<img width="547" height="308" alt="New3" src="https://github.com/user-attachments/assets/62a7bc20-8de8-479e-b16e-4ea66e553d22" />


---

## ✨ Características

- 🧠 Detección automática de eventos (kill / death) desde Overwolf  
- 📊 Historial y conteo de batallas por jugador  
- 🔎 Búsqueda de jugadores en overlay (Muestra el score entre tu y el oponente, si está en la misma partida y quienes están en su equipo)
- ⭐ Al comenzar una partida se mostrarán los jugadores con prioridad que estan dentro de la partida, junto a quienes conforman su equipo.
- ⭐ Sistema de jugadores prioritarios. (En una primera batalla contra un jugador despues de hacer kill o tener Death podras decidir si el jugador se guarda bajo prioridad)
- 🧾 Soporte de almacenamiento:  
  - MySQL  
  - SQLite  
  - Excel  
- 🖥️ Overlay configurable en pantalla (Tu decides donde aparecerá el Overlay de eventos)
- 🔄 Actualizaciones automáticas desde GitHub  
- 🎯 Optimizado para uso en partida (sin mouse)  

---

## ⚙️ Requisitos

Antes de usar la aplicación necesitas:

- ✅ Tener instalado Overwolf  
- ✅ Tener activo Fortnite Tracker (Overwolf App)  
- ✅ Haber jugado al menos una partida (para generar logs)  

---

## 📦 Instalación

1. Descarga el archivo `.zip` desde la sección de **Releases**.  
2. Extrae el contenido en una carpeta.  
3. Asegúrate de que ambos archivos estén juntos:  
   - `Fortnite Score Overlay.exe`  
   - `Updater.exe`  

---

## 🚀 Uso

1. Ejecuta `Fortnite Score Overlay.exe`  
2. Configura:
   - Ubicación del log de Overwolf (`background.html.log`) (Generalmente se encuentra en AppData\Local\Overwolf\Log\Apps\Fortnite Live Tracker\background.html.log) 
   - Tipo de base de datos (MySQL / SQLite / Excel)  Si no sabes cual elegir, te recomiendo elegir SQLite
   - Las bases de datos se crearán de forma automática, en el caso de MySQL solo se deberá crear la base de datos, las tablas se crearán de forma automática.
   - Definir el área del overlay  (Considerar un area rectangular de un tamaño decente)
3. Presiona **Comenzar**  

---

## 🎮 Controles

| Acción                | Tecla      |
|----------------------|-----------|
| Buscar jugador       | CTRL + H  |
| Mostrar prioritarios (en partida) | CTRL + J  |
| Marcar prioridad     | J         |
| Quitar prioridad     | K         |

*(Las teclas pueden configurarse en la aplicación)*

---

## 🔄 Actualizaciones

El programa incluye actualización automática:

- No necesitas hacer nada manualmente.

---

## ⚠️ Notas importantes

- No muevas ni renombres `Updater.exe`  
- No ejecutes la app desde dentro del ZIP  

---

## 📁 Almacenamiento

Puedes elegir entre:

- 🟡 SQLite (automático)  
- 🟢 Excel (automático)  
- 🔵 MySQL (configurable)  

Los archivos se crean automáticamente si no existen.

---

## 🛠️ Soporte

Si encuentras algún problema:

Revisa el log:
- `%LOCALAPPDATA%\FortniteTrackerWatcher`  
- `%TEMP%\ft_updater_log.txt`  

---

## 👤 Autor

Desarrollado por **MasterDeveloperLD**

---

## ⚡ Licencia

Uso personal.


<img width="288" height="269" alt="New Kill" src="https://github.com/user-attachments/assets/21dd168c-19c5-4299-8379-8a3722436298" />
<img width="300" height="286" alt="new2" src="https://github.com/user-attachments/assets/662cd972-72a4-4de4-a731-dc1e40b9aab6" />
<img width="284" height="349" alt="NEW1" src="https://github.com/user-attachments/assets/6bef9ecb-b5ee-4688-a65c-72f65b60f12d" />

