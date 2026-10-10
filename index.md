---
layout: default
title: Cristian Recabarren Madrid
description: Ingeniero Civil en Computación · Arquitectura de software · Backend · Sistemas operativos
---

# Cristian Recabarren Madrid

**Ingeniero Civil en Computación, mención Informática**  
**Magíster en Gestión y Emprendimiento Tecnológico**

**Software Engineer · Software Architect · Founder / Lead Software Engineer en Flō Finanstic**

Santiago, Chile · [Email](mailto:crecabar_cl@me.com) · [LinkedIn](https://www.linkedin.com/in/crecabar/) · [GitHub](https://github.com/crecabar)

[Experiencia](#experiencia-profesional) · [Proyectos](#proyectos-destacados) · [Competencias](#competencias-técnicas) · [Formación](#formación-académica)

---

## Perfil profesional

Ingeniero de software con **más de 15 años de experiencia** en desarrollo, arquitectura y liderazgo técnico. Actualmente especializado en soluciones web con **PHP/Laravel, MySQL, Docker y AWS**, con experiencia en aplicaciones en producción, APIs, integraciones, bases de datos, CI/CD y modernización de sistemas.

He trabajado en desarrollo de productos, gestión técnica en el sector público, proyectos de investigación y desarrollo, y aseguramiento de calidad de software. En paralelo, desarrollo proyectos abiertos de programación de sistemas y aprendizaje de sistemas operativos.

**Servicios profesionales:** desarrollo backend, resolución de bugs, modernización y upgrades, dockerización, revisión técnica de sistemas y proyectos de software acotados.

## Experiencia profesional

### Flō Finanstic — Founder / Lead Software Engineer
**2025 – actualidad**

Diseño, desarrollo y operación end-to-end de una plataforma SaaS de planificación financiera personal.

- Diseñé la arquitectura usando **PHP/Laravel, Vue.js con Inertia, MySQL, Redis y Nginx**, con límites explícitos entre dominio, aplicación e infraestructura.
- Desarrollé funcionalidades de presupuestos, cuentas, transacciones, transferencias, objetivos financieros y onboarding.
- Estandaricé entornos de desarrollo y producción mediante **Docker Compose**.
- Implementé testing automatizado, **PHPStan**, Laravel Pint y pruebas de arquitectura para proteger refactors y regresiones.
- Opero la infraestructura productiva sobre **AWS**, con aplicación web, Nginx, MySQL y workers respaldados por Redis.
- Establecí prácticas de **Git/GitHub y CI/CD** para despliegues reproducibles.

[Producto Flō](https://flofinanstic.com/) · [Organización GitHub](https://github.com/flofinanstic) (aplicación principal privada)

### Comisión Nacional de Energía (CNE) — Profesional, Subdepartamento de Tecnologías de la Información
**2018 – 2025**

- Lideré iniciativas de desarrollo y modernización de software, articulando áreas de negocio, proveedores y equipos internos.
- Fui contraparte técnica en el desarrollo de **GEMA**, plataforma orientada a la organización de información de contratos de energía en el mercado eléctrico.
- Participé en el levantamiento, modelamiento y digitalización de trámites para iniciativas de transformación digital del Estado.

### Ministerio de Energía — Profesional TI
**2016 – 2018**

- Lideré y desarrollé soluciones de software para atención ciudadana y reporte de eficiencia energética de organismos públicos.
- Contribuí a mejoras de procesos que redujeron el tiempo medio de respuesta a solicitudes de información de **9 a 5 días**.
- Lideré correcciones a la plataforma de reportería de eficiencia energética y diseñé la arquitectura de una nueva versión.

### RG Labs SpA — Socio fundador
**2013 – 2018**

- Cofundé una empresa orientada a I+D y desarrollo de software a medida.
- Lideré una solución de visión computacional y análisis de imágenes vinculada a un proyecto de innovación **Corfo**.
- Lideré la estrategia tecnológica para un joint venture con la empresa italiana **GPI SpA**, incluyendo capacitación en Trento, Italia.

### Observatorio ALMA — Ingeniero en Aseguramiento de Calidad de Software
**2010 – 2013**

- Analicé y reporté fallas de software usando JIRA y herramientas internas para identificar problemas recurrentes.
- Preparé documentación y participé en auditorías internas del Departamento de Computación.
- Implementé políticas y procedimientos de gestión de calidad alineados con **ISO 9001**.

## Proyectos destacados

### [MyOS — sistema operativo Unix-like educativo](https://github.com/crecabar/myos)

Proyecto open source para **x86-64**, escrito principalmente en **C**, que estudia cómo construir un sistema operativo desde el arranque hasta el entorno de usuario.

- Arranque UEFI mediante **Limine** y ejecución validada tanto con **QEMU** como en hardware físico.
- Kernel con memoria virtual, aislamiento ring 0/ring 3, procesos, planificación preventiva y syscalls.
- Carga y ejecución de programas **ELF**; infraestructura de VFS, descriptores de archivo, initramfs y dispositivos.
- Comandos Unix iniciales integrados; en desarrollo la primera shell interactiva **`myos $ `**.
- Compilación freestanding con **LLVM/Clang y LLD**; depuración con **GDB** y pruebas automatizadas.
- Objetivo de largo plazo: userland propio, filesystem **MFS**, soporte de dispositivos, entorno gráfico capaz de ejecutar `startx` / `xclock` y eventualmente self-hosting.

**Ecosistema en distintas etapas de desarrollo:** [libc](https://github.com/crecabar/myos-libc) · [userland](https://github.com/crecabar/myos-userland) · [MFS](https://github.com/crecabar/myos-mfs) · [port de Vim](https://github.com/crecabar/myos-vim)

### [Flō Finanstic — planificación financiera personal](https://flofinanstic.com/)

Producto SaaS que ayuda a decidir cuánto dinero se puede gastar **antes de gastar**, mediante la asignación del dinero disponible a prioridades, obligaciones y metas.

- Desarrollo integral de producto, modelo financiero, backend, frontend y operación.
- Arquitectura modular con separación de responsabilidades, pruebas automatizadas y análisis estático.
- Aplicación actualmente en evolución mediante beta privada; su código productivo es privado.

### [deitel-book — ejercicios y herramientas en C](https://github.com/crecabar/deitel-book)

- Soluciones independientes para ejercicios del libro de Deitel & Deitel.
- Launcher interactivo, descubrimiento automático de ejercicios y compilación con **GNU Make**.
- Estudio de C y programación de sistemas con prácticas reproducibles.

### [utem_thesis_template — plantilla LaTeX](https://github.com/crecabar/utem_thesis_template)

- Plantilla pública reutilizable para memorias de ingeniería de la Universidad Tecnológica Metropolitana.
- Ejemplo de contribución técnica y académica compartida con la comunidad.

## Competencias técnicas

| Área | Tecnologías y conocimientos |
| --- | --- |
| **Backend** | PHP, Laravel, REST APIs, Java, C# |
| **Frontend** | Vue.js, Inertia.js, TypeScript, JavaScript |
| **Bases de datos** | MySQL, PostgreSQL, SQL Server |
| **Infraestructura** | Linux, AWS, Docker, Nginx, Redis, CI/CD |
| **Ingeniería de software** | Git/GitHub, pruebas automatizadas, PHPStan, arquitectura de software, diseño de dominios |
| **Sistemas y bajo nivel** | C, C++, Assembly, x86-64, kernel, memoria virtual, procesos, scheduling, syscalls, VFS, drivers, QEMU, GDB |
| **Otros** | Python, LLVM/Clang, GNU Make |

## Formación académica

- **2024** — Magíster en Gestión y Emprendimiento Tecnológico, **Universidad Adolfo Ibáñez**, Santiago.
- **2023** — **Babson MBA Build Program**, Babson College, Massachusetts.
- **2017** — Ingeniero Civil en Computación, **Universidad Tecnológica Metropolitana**, Santiago.

## Idiomas

- **Inglés:** B2, avanzado.
- **Alemán:** A1.1, básico.

---

## Contacto

Disponible para conversar sobre desarrollo de software, arquitectura, backend y proyectos tecnológicos.

**[Escribirme por correo](mailto:crecabar_cl@me.com)** · **[LinkedIn](https://www.linkedin.com/in/crecabar/)** · **[Repositorios en GitHub](https://github.com/crecabar)**

<small>Última revisión: octubre de 2026. La experiencia profesional y formación se basan en mi CV; los proyectos complementan esa información desde mi perfil público de GitHub.</small>
