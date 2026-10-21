# Hola, soy John Alexander García Valencia 👋
### Desarrollador de Software Full-Stack & Analista de Soluciones TI

> *"Construyendo infraestructura de software que opera donde otros sistemas fallan — entornos offline, hardware industrial y producción 24/7."*

[![Portafolio Web](https://img.shields.io/badge/🌐_Portafolio_Web-johngarciav.com-000000?style=for-the-badge&logo=astro&logoColor=white)](https://johngarciav.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ldalexander1)
[![Email](https://img.shields.io/badge/Email-garciajohn221%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:garciajohn221@gmail.com)

---

### ⚡ Sobre mí

Soy **Analista de Soluciones TI y Desarrollador de Software** en **Detcuador S.A.** (Ecuador), especializado en diseñar e implementar sistemas críticos desde primeros principios: entendiendo el problema operativo real en planta antes de elegir las herramientas.

- 🏭 **Impacto en Producción:** He diseñado y desplegado arquitecturas que integran **ERPs corporativos (MBA3)**, **hardware biométrico/térmico (ZKTeco)** y **aplicaciones móviles nativas Offline-First** con **>99% de uptime**.
- 🎓 **Formación Continua:** Estudiante de Tecnología en Análisis y Desarrollo de Software en el **SENA** y cursando el programa de **Ciencia de Datos e Inteligencia Artificial (GCI)** en **The University of Tokyo (Matsuo-Iwasawa Lab)**.
- 🧠 **Enfoque Técnico:** Fiabilidad de datos, sincronización idempotente en redes inestables, automatización de flujos industriales y modelos predictivos de inventario.

---

### 🛠️ Stack Tecnológico

**Backend & Ciencia de Datos**
![Python](https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy_%2F_NumPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.IO_%2F_WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Frontend & Mobile (Planta Industrial)**
![Kotlin](https://img.shields.io/badge/Kotlin_(Android_Nativo)-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native_(Expo)-000020?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-FF5D01?style=flat-square&logo=astro&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Bases de Datos, Infraestructura & Hardware**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL_%2F_MariaDB-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite_(Room)-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Server_(Ubuntu)-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi_5_%2F_ZKTeco-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

---

### 🚀 Sistemas en Producción (Casos de Estudio)

> 🔒 **Nota sobre confidencialidad:** Mis sistemas principales operan actualmente en producción 24/7 dentro de la infraestructura corporativa de **Detcuador S.A.**, por lo que su código fuente es privado. Puedes explorar la arquitectura detallada y métricas en vivo en **[johngarciav.com](https://johngarciav.com/)**.

| Sistema | Arquitectura & Stack | Problema Resuelto & Impacto Cuantificable |
| :--- | :--- | :--- |
| **Zyncro Abastecimiento**<br>*(Inteligencia de Inventario & ERP)* | `Python 3.12` `FastAPI` `SciPy` `MySQL` `Bridge ODBC` `React 18` `React Native` | Sincroniza **~1,000,000 de filas por ciclo** (3 veces al día) desde el ERP MBA3. Calcula puntos de reorden estadísticos (Z-score), explosión de materiales (BOM) y proyecta quiebres de stock para **~500 SKUs** con un nivel de servicio del **98%**. |
| **SIGEP**<br>*(Ejecución de Planta y Logística)* | `Kotlin (Android)` `Room SQLite` `Coroutines` `FastAPI` `WebSockets` `PostgreSQL` | Plataforma **Offline-First** con cola de sincronización idempotente. Coordina **~20 tablets industriales** en planta con WiFi intermitente, logrando **100% de trazabilidad de lotes** y **0 pérdida de datos** al reconectar. |
| **SIGAC**<br>*(Control Biométrico e IoT)* | `Python (TCP Worker)` `Node.js` `Socket.IO` `React 18` `MariaDB` `ZKTeco K40` `ESC/POS` | Integración directa por protocolo TCP con hardware biométrico e impresoras térmicas. Automatizó el flujo de **~140 empleados** en 3 turnos con **latencia <2s**, **>99% de uptime** y **0 incidentes de fraude**. |
| **Motor de Órdenes MBA3**<br>*(Automatización Comercial)* | `Python` `Extracción PDF` `REST APIs / WebServices` `ERP MBA3` | Lectura estructurada y procesamiento desatendido de órdenes de compra en PDF, inyectando transacciones directamente al ERP sin intervención humana ni errores de digitación. |

---

### 📫 Contacto Directo

- 🌐 **Portafolio & Arquitectura de Proyectos:** [johngarciav.com](https://johngarciav.com/)
- 💼 **LinkedIn:** [linkedin.com/in/ldalexander1](https://www.linkedin.com/in/ldalexander1)
- 📧 **Correo:** [garciajohn221@gmail.com](mailto:garciajohn221@gmail.com)
