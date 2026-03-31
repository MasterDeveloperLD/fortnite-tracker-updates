# 🎮 Fortnite Score Overlay

Overlay en tiempo real para Fortnite que muestra tu marcador contra otros jugadores (kills vs deaths), con sistema de prioridades, búsqueda en overlay y actualizaciones automáticas.

<img width="547" height="308" alt="completo" src="https://github.com/user-attachments/assets/3c59fcdc-ae28-4912-a270-f3ac6982e69c" />


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

<img width="285" height="164" alt="Death" src="https://github.com/user-attachments/assets/2b3f41aa-4081-4940-9972-a45e594ebfc3" />
<img width="285" height="161" alt="Prioritario" src="https://github.com/user-attachments/assets/82de16e3-ce67-4508-a9f3-f3a4590ff816" />
<img width="285" height="322" alt="search" src="https://github.com/user-attachments/assets/308f5f67-4c96-4371-90b7-fabd35f18e5e" />


