# 🛡️ Secure Asset Fortress v6.0

**Nombre Técnico:** `Secure-Gateway-Asset-Monitor.html`  
**Área:** Gestión de Activos Críticos / Ciberseguridad Frontend  

## 📖 Descripción del Proyecto
Este script es un **Nodo de Monitoreo de Activos** diseñado para entornos donde la integridad de los datos y la protección del código son críticas. Implementa una interfaz de "Consola Blindada" que captura métricas de hardware y sincroniza datos financieros externos bajo capas de seguridad reactiva.

## 🚀 Funcionalidades y Operación
1. **Auditoría de Hardware:** Recupera en tiempo real núcleos, RAM y plataforma del activo local.
2. **Sincronización de API:** Conexión segura a `coincap.io` para activos digitales.
3. **Conversión a Texto Plano:** Todo dato recibido pasa por un motor de sanitización activa antes de ser renderizado, neutralizando ataques XSS.
4. **Sentinel Logs:** Panel de trazabilidad que registra cada evento, error o intento de intrusión para auditoría posterior.

## 🔐 Matriz de Seguridad (Defensa en Profundidad)

| Protección | Tipo | Descripción |
| :--- | :--- | :--- |
| **IIFE Encapsulation** | Lógica | Aísla el código del "Scope" global. La consola del navegador no puede ver ni llamar a las funciones internas. |
| **Anti-Debugging** | Reactiva | Detecta si las herramientas de desarrollador (F12) están abiertas y lanza alertas al Sentinel Log. |
| **Flood Protection** | Preventiva | Bloqueo total del sistema ante sospecha de ataque por fuerza bruta (clics masivos). |
| **Watchdog Timer** | Física | Auto-bloqueo por inactividad de 60 segundos para proteger el acceso físico al nodo. |
| **UI Shield** | Acceso | Bloqueo de Clic Derecho, Ctrl+U (Ver fuente), Ctrl+S (Guardar) y Ctrl+I (Inspeccionar). |
| **Code Obfuscation** | Intelectual | Código transformado en un bloque ilegible para prevenir ingeniería inversa. |

## 🛠️ Instalación y Uso
1. Clonar el repositorio: `Ciberseguridad-Frontend.git`
2. Abrir el archivo `Secure-Gateway-Asset-Monitor.html` en cualquier navegador moderno.
3. Interactuar con los paneles de comando y observar la auditoría en tiempo real en el panel Sentinel.
