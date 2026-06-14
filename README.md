# VIKPORT

> 🇨🇴 [Español](#español) | 🇺🇸 [English](#english)

---

## Español

### ¿Qué es Vikport?

**Vikport** es una plataforma tecnológica para el sector de transporte de carga en Colombia. Conecta conductores, generadores de carga, navieras, operadores portuarios, parqueaderos y coordinadores de flota en un solo ecosistema digital.

Desarrollada por un equipo con más de 18 años de experiencia en el sector portuario de Buenaventura, la plataforma busca modernizar la logística de carga colombiana con tecnología accesible, segura y escalable.

### Actores del ecosistema

- 🚛 **Conductores** — Acceso a ofertas de carga locales, nacionales y de empleo
- 📦 **Generadores de carga** — Publicación y gestión de cargas disponibles
- 🚢 **Navieras** — Publicación de itinerarios y buques
- 🏗 **Operadores portuarios** — Gestión de turnos y citas portuarias
- 🅿️ **Parqueaderos** — Visibilidad y disponibilidad en tiempo real
- 🗂 **Coordinadores de flota** — Supervisión y asignación de vehículos

### Stack tecnológico

| Capa | Tecnología |
|------|-----------|
| App móvil | React Native + Expo (JavaScript) |
| Backend | Node.js en Amazon EC2 |
| Base de datos | PostgreSQL via Supabase (RLS habilitado) |
| Almacenamiento | Amazon S3 (documentos y fotos) |
| Pagos | Wompi |
| Control de versiones | GitHub |
| Mapas | OpenStreetMap (embed gratuito) |

### Arquitectura de seguridad

- Control de acceso basado en roles (RBAC) dinámico
- 7 roles predefinidos, configurables desde base de datos
- Row Level Security (RLS) en todas las tablas
- Permisos granulares por módulo, sin cambios de código

### Estado del proyecto

- ✅ MVP en fase beta avanzada (75% completado)
- ✅ 17+ tablas en base de datos productiva
- ✅ Autenticación, perfiles, ofertas, roles y permisos funcionales
- ✅ Módulo de programación de buques con demo para inversionistas
- 🔄 Lanzamiento oficial proyectado: Q3 2026
- 🔄 Expansión a Barranquilla, Cartagena y Barrancabermeja

### Constitución legal

Vikport está siendo constituida como **Sociedad por Acciones Simplificada (S.A.S.)** en Colombia, con marca registrada ante la **SIC** en 3 clases.

### Contacto

- 🌐 [vikport.carrd.co](https://vikport.carrd.co)
- 💼 [linkedin.com/company/vikport](https://linkedin.com/company/vikport)

---

## English

### What is Vikport?

**Vikport** is a logistics technology platform for Colombia's cargo transport sector. It connects truck drivers, cargo generators, shipping lines, port operators, parking facilities, and fleet coordinators in a single digital ecosystem.

Built by a team with over 18 years of experience in the port sector of Buenaventura — Colombia's largest Pacific port — Vikport modernizes cargo logistics through accessible, secure, and internationally scalable technology.

### Ecosystem actors

- 🚛 **Truck drivers** — Access to local, national, and employment cargo offers
- 📦 **Cargo generators** — Publishing and managing available loads
- 🚢 **Shipping lines** — Vessel scheduling and itinerary management
- 🏗 **Port operators** — Port appointment and shift management
- 🅿️ **Parking facilities** — Real-time availability and visibility
- 🗂 **Fleet coordinators** — Vehicle supervision and assignment

### Tech stack

| Layer | Technology |
|-------|-----------|
| Mobile app | React Native + Expo (JavaScript) |
| Backend | Node.js on Amazon EC2 |
| Database | PostgreSQL via Supabase (RLS enabled) |
| Storage | Amazon S3 (documents & photos) |
| Payments | Wompi |
| Version control | GitHub |
| Maps | OpenStreetMap (free embed) |

### AWS usage

- **Amazon EC2** — Node.js REST API server powering the platform backend
- **Amazon S3** — Secure storage for driver licenses, vehicle photos, and compliance documents
- **Architecture** — Designed for multi-region scalability across Latin America and beyond

### Security architecture

- Dynamic Role-Based Access Control (RBAC)
- 7 predefined roles, fully configurable from the database
- Row Level Security (RLS) on all tables
- Granular per-module permissions — no code changes needed to configure new roles

### Project status

- ✅ MVP in advanced beta (75% complete)
- ✅ 17+ tables in production database
- ✅ Auth, profiles, cargo offers, roles and permissions fully functional
- ✅ Vessel scheduling module with investor demo
- 🔄 Official launch: Q3 2026
- 🔄 Expansion to Barranquilla, Cartagena and Barrancabermeja

### Legal

Vikport is being incorporated as a **Sociedad por Acciones Simplificada (S.A.S.)** in Colombia, with trademark registered at the **SIC** (Colombian Superintendence of Industry and Commerce) in 3 classes.

### Contact

- 🌐 [vikport.carrd.co](https://vikport.carrd.co)
- 💼 [linkedin.com/company/vikport](https://linkedin.com/company/vikport)
