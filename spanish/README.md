
# CarLogBot – Chatbot de Telegram para Manejo de QR Secure

**Repositorio:** [CarLogBot en GitHub](https://github.com/netrix4/CarLogBot)  
**Autores:** Mario, Rubén  
**Estado:** 🟡 *In Review*  
**Última actualización:** 2025-03-31

---

## Objetivo

Desarrollar un chatbot en Telegram que utilice **códigos QR como identificadores únicos** para objetos pertenecientes a estudiantes y docentes. Su propósito es facilitar la recuperación de objetos perdidos y permitir la notificación de incidentes dentro del campus, promoviendo un entorno más seguro, colaborativo y organizado.

---

## 🧩 Funcionalidades Clave (Goals)

-  Registro de usuarios y asociación de objetos personales a **códigos QR únicos**.
-  Escaneo de códigos QR para **reportar objetos extraviados o encontrados**.
-  Notificación de **incidentes comunitarios** como llantas ponchadas, mochilas olvidadas, etc.
-  Listado de objetos asociados a una cuenta para fácil gestión.
-  **Moderación comunitaria**: reporte de usuarios por mal uso con mecanismo de sanción.
-  Comunicación entre usuarios mediante el bot tras escanear un QR.

---

## 🚫 Alcances No Incluidos (Non-Goals)

- No se busca reemplazar los sistemas institucionales de vigilancia o seguridad.
- No se gestiona información financiera ni se contempla procesamiento de pagos.

---

##  Contexto del Problema

En entornos universitarios, la pérdida de objetos personales y la falta de canales para reportar incidentes menores representan un problema común. Este proyecto surge para llenar ese vacío utilizando una herramienta accesible como Telegram, ampliamente adoptada entre estudiantes y docentes.

### Ejemplos de uso:
- Un estudiante encuentra una mochila con un QR. Escanea el código y contacta al propietario a través del bot.
- Un auto tiene una llanta ponchada en el estacionamiento. Otro estudiante lo reporta desde el bot para alertar al dueño.

---

##  Tecnologías Utilizadas

- **Telegram Bot API** – Para gestionar interacciones con usuarios.
- **Python** – Lógica backend del chatbot.
- **PostgreSQL** – Base de datos relacional para gestionar usuarios, objetos y reportes.
- **QR Code Libraries** – Generación e interpretación de códigos QR.
- **Testing** – Pruebas de integridad de base de datos y validación de operaciones.

---

