<div align="center">

```
███╗   ███╗██╗ ██████╗ ██╗   ██╗███████╗██╗
████╗ ████║██║██╔════╝ ██║   ██║██╔════╝██║
██╔████╔██║██║██║  ███╗██║   ██║█████╗  ██║
██║╚██╔╝██║██║██║   ██║██║   ██║██╔══╝  ██║
     ██║ ╚═╝ ██║██║╚██████╔╝╚██████╔╝███████╗███████╗
     ╚═╝     ╚═╝╚═╝ ╚═════╝  ╚═════╝ ╚══════╝╚══════╝
```

# Miguel Ángel Blandón Montes
### Desarrollador de Software · Administrador de Sistemas

[![Location](https://img.shields.io/badge/📍-Medellín,_Colombia-1a1a2e?style=flat-square)](https://maps.google.com/?q=Medellin,Colombia)
[![GitHub](https://img.shields.io/badge/GitHub-Sudo--CrocPenguin-0f3460?style=flat-square&logo=github)](https://github.com/Sudo-CrocPenguin)
[![Email](https://img.shields.io/badge/Email-miguel.blandonmo%40amigo.edu.co-16213e?style=flat-square&logo=gmail)](mailto:miguel.blandonmo@amigo.edu.co)

</div>

---

## `$ whoami`

Desarrollador de Software Junior con base sólida en **infraestructura de sistemas y desarrollo backend**, actualmente en cuarto semestre de Tecnología en Desarrollo de Software en la **Universidad Católica Luis Amigó**.

Con experiencia práctica en proyectos fullstack y administración de servidores Linux, orientado a la calidad del código mediante **arquitectura limpia, DDD y buenas prácticas**. Llevo mis proyectos desde el desarrollo hasta producción en infraestructura propia.

> _"Uso mis propias aplicaciones como estándar de calidad: si no las usaría, no están listas para otros."_

---


## `$ cat stack.json`

### ⚙️ Backend
![Java](https://img.shields.io/badge/Java-Spring_Boot-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring-Security_·_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### 📱 Frontend & Mobile
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-Next.js_·_Vite-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-Expo_·_Expo_Router-000020?style=flat-square&logo=expo&logoColor=white)

### 🗄️ Datos & Backend as a Service
![SQL](https://img.shields.io/badge/SQL-MariaDB_·_PostgreSQL-003545?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Auth_·_Storage_·_RLS-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-Migrations-CC0200?style=flat-square&logo=flyway&logoColor=white)

### 🔐 Seguridad
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Argon2](https://img.shields.io/badge/Argon2-Hashing-555?style=flat-square)
![AES-256](https://img.shields.io/badge/AES--256--GCM-Encryption-555?style=flat-square)
![OAuth2](https://img.shields.io/badge/OAuth_2.0-Google-4285F4?style=flat-square&logo=google&logoColor=white)

### 🖥️ Infraestructura & DevOps
![Linux](https://img.shields.io/badge/Linux-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![SSH](https://img.shields.io/badge/SSH-Hardening-1a1a2e?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-Scripting-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

### 🧪 Testing & Herramientas
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-555?style=flat-square)
![Git](https://img.shields.io/badge/Git-Semantic_Commits-F05032?style=flat-square&logo=git&logoColor=white)

---

## `$ ls proyectos/`

### 📬 Auto-Gmail-code
**Plataforma cliente-servidor para gestión inteligente de Gmail vía OAuth**

Backend HTTP que conecta múltiples cuentas Gmail (solo por OAuth, nunca por contraseña), sincroniza correos, los clasifica por remitente/importancia/spam, genera alertas de seguridad y deja auditoría de acciones sensibles. Pensado para ser consumido por un frontend web, móvil o de escritorio.

![Node.js](https://img.shields.io/badge/Node.js_20-339933?style=flat-square&logo=node.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Prisma-336791?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

- Arquitectura por *features* (auth, gmail-accounts, emails, alerts, senders, rules, analytics, audit) con capas domain / application / infraestructura
- Tokens Gmail cifrados con AES-256-GCM · sesiones JWT revocables · flujo OAuth con `state` firmado y de un solo uso
- Reglas automáticas de clasificación, sistema de alertas y analítica de correo
- Tests con Vitest + Supertest, documentación OpenAPI y guías completas en `/docs`

**[→ Ver repositorio](https://github.com/Sudo-CrocPenguin/Auto-Gmail-code)**

---

### 🎫 Ticket Order
**Sistema multiempresa para el seguimiento de tickets de desarrollo**

Aplicación completa para que equipos de desarrollo registren bugs, adjunten evidencias y den seguimiento al estado de cada problema por empresa y por aplicación. Empezó como una app Expo con almacenamiento local y evolucionó a una solución con backend real.

![Expo](https://img.shields.io/badge/Expo_SDK_54-000020?style=flat-square&logo=expo&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native_0.81-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

- Monorepo con app móvil (Expo), dashboard web (Next.js) y dominio compartido en DDD/POO
- Cuentas globales con membresías en múltiples empresas, invitaciones y cambio de empresa activa
- Supabase como backend central: Auth, Postgres con Row Level Security y Storage para evidencias
- Actualizaciones OTA con Expo EAS Update, notificaciones push y modo offline con caché local

**[→ Ver repositorio](https://github.com/Sudo-CrocPenguin/ticket-order)**

---

### 💰 Adulto Funcional — Sistema de Gestión Financiera y Agenda
**Ecosistema personal de finanzas, agenda y gestor de contraseñas**

Organización propia con backend, cliente web y cliente móvil separados, comunicándose por API REST.

![Java](https://img.shields.io/badge/Java-Spring_Boot_3-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![React](https://img.shields.io/badge/React-TypeScript_·_Vite-61DAFB?style=flat-square&logo=react&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-Expo_Router-000020?style=flat-square&logo=expo&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-Flyway-003545?style=flat-square&logo=mariadb&logoColor=white)

- **Backend** ([`adulto-funcional-server`](https://github.com/adulto-funcional/adulto-funcional-server)): Clean Architecture en Spring Boot 3, autenticación JWT + Argon2, identificadores UUID v7, migraciones con Flyway
- **Web** ([`adulto-funcional-web`](https://github.com/adulto-funcional/adulto-funcional-web)): React + TypeScript + Vite
- **Móvil** ([`adulto-funcional-movil`](https://github.com/adulto-funcional/adulto-funcional-movil)): React Native + Expo Router, con almacenamiento local seguro

**[→ Ver organización](https://github.com/adulto-funcional)**

---

### 👁️ The All Seeing Eye
**Plataforma de auditoría de red para equipos corporativos**

Sistema para registrar actividad de red autorizada en computadores de equipos de desarrollo: dispositivo, IP local/pública, conexiones, dominios y puertos destino. Pensado para ambientes donde los empleados son informados de la auditoría — no es monitoreo oculto ni captura no consentida de datos personales.

![Python](https://img.shields.io/badge/Python-FastAPI-3776AB?style=flat-square&logo=python&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-SQLAlchemy_·_Alembic-336791?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

- Arquitectura hexagonal por dominios (`audit`, `devices`, `shared`) con capas domain / application / infraestructura / presentación, tanto en el backend como en el agente
- Agente por equipo (Windows/Linux) que reporta telemetría de red y heartbeats; el backend detecta ausencias y recuperaciones de reporte
- Pensado para escalar a un proxy/VPN corporativo con inspección TLS autorizada y redacción automática de secretos
- Desarrollo bajo GitFlow con commits convencionales en español; **v1 en camino**, todo el avance vive hoy en la rama `develop`

**[→ Ver repositorio](https://github.com/Sudo-CrocPenguin/the-all-seeing-eye)**

---

### 🖲️ admin-serverOP *(en fase de diseño)*
**Panel de monitoreo visual para servidores y homelabs**

Idea ya definida, desarrollo por comenzar: un panel que muestra en tiempo real las especificaciones del sistema, puertos abiertos, procesos activos, flujo de datos de red, conexiones entrantes y solicitudes de acceso. Pensado como herramienta puramente informativa — sin capacidad de ejecutar acciones sobre el sistema.

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**[→ Ver repositorio](https://github.com/Sudo-CrocPenguin/admin-serverOP)**

---

## `$ cat infraestructura.log`

Servidor personal Ubuntu corriendo en producción con múltiples servicios activos:

- Tres sitios web en producción con Nginx, dominios y certificados SSL
- Hardening SSH: cambio de puertos, llaves públicas, restricción por IP
- Pipelines de monitoreo y alertas mediante scripting en Bash
- APIs REST con Spring Boot y persistencia en MariaDB

---

## `$ cat formacion.txt`

| Institución | Título | Estado |
|---|---|---|
| Universidad Católica Luis Amigó | Tecnología en Desarrollo de Software | En curso · 4to semestre · 2025– |
| Great Learning | Programación Java | ✅ Feb. 2026 |
| Coursera · U. de los Andes | Programación Python | ✅ Oct. 2023 |

**Idiomas:** Español nativo · Inglés técnico (lectura y documentación)

---

<div align="center">

`miguel.blandonmo@amigo.edu.co`

</div>
