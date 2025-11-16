# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. These descriptions include responsibilities, communication patterns, and how each persona interacts with existing roles to improve clarity and accountability.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers (PdM)

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers (PM)

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Lead / Quality Advocate (nuevo)

### Role Summary
Un QA Lead se encarga de la estrategia de pruebas, gates de calidad y validación a lo largo del pipeline de entrega para asegurar que las releases cumplan criterios funcionales y no funcionales.

### Responsibilities
- Definir estrategia de pruebas y gates de calidad para releases
- Crear o coordinar criterios de aceptación y planes de prueba
- Triage de defectos y coordinación de remediaciones con desarrolladores
- Asegurar cobertura automatizada crítica y pruebas de humo
- Enseñar al equipo sobre testabilidad y definición de hecho (DoD)

### Interacciones con roles existentes
- Con PdM para asegurar que los criterios de aceptación capturen expectativas de negocio
- Con Developers para diseñar requisitos testeables y corregir fallos
- Con PM para decisiones de readiness y gestión de riesgos
- Con DevOps para necesidades de entornos de prueba y pipelines

### Cuándo involucrar
- En planificación para definir aceptación y estrategia de pruebas
- Antes de la release para validación y sign-off

---

## Scrum Master / Delivery Lead (nuevo)

### Role Summary
Facilita la entrega del equipo, elimina impedimentos y fomenta prácticas de mejora continua.

### Responsibilities
- Facilitar ceremonias ágiles (daily, planning, retro, demo)
- Eliminar bloqueos y escalar impedimentos
- Coach al equipo en métricas de entrega y buenas prácticas
- Mejorar el flujo y predictibilidad de entrega

### Interacciones
- Con PM para resolver dependencias cross-team
- Con PdM para asegurar que el backlog esté listo para desarrollo
- Con Developers y QA para quitar obstáculos organizacionales

### Cuándo involucrar
- Durante toda la ejecución; especialmente en planificación y retrospectivas

---

## UX Designer (nuevo)

### Role Summary
Diseña la experiencia del usuario, traduce investigación en soluciones y valida usabilidad y accesibilidad.

### Responsibilities
- Conducir investigación y tests de usabilidad
- Crear wireframes, prototipos y especificaciones de diseño
- Definir criterios de aceptación UX y checks de accesibilidad
- Validar diseños con stakeholders e iterar según feedback

### Interacciones
- Con PdM para alinear objetivos de usuario
- Con Developers para entregar assets y aclarar comportamiento
- Con QA para verificar usabilidad y accesibilidad

### Cuándo involucrar
- En discovery y planificación; durante el desarrollo para validación

---

## Business Analyst (BA) (nuevo)

### Role Summary
Traduce necesidades de negocio en requisitos claros y testeables; alinea soluciones técnicas con objetivos organizacionales.

### Responsibilities
- Documentar workflows de negocio y requisitos detallados
- Crear criterios de aceptación y escenarios de ejemplo
- Identificar stakeholders y puntos de decisión
- Apoyar análisis de impacto ante cambios

### Interacciones
- Con PdM para refinar requisitos de producto
- Con PM para mapear dependencias y necesidades de stakeholders
- Con Developers y QA para clarificar casos límite y aceptación

### Cuándo involucrar
- En iniciación y planificación; disponible durante ejecución para aclaraciones

---

## DevOps Engineer (nuevo)

### Role Summary
Mantiene e impulsa prácticas de build, deployment e infraestructura para releases repetibles y recuperación rápida ante incidentes.

### Responsibilities
- Implementar y mantener pipelines CI/CD
- Definir infra-as-code y configuraciones de entornos
- Automatizar despliegues y estrategias de rollback
- Colaborar en observabilidad, alertas y respuesta a incidentes

### Interacciones
- Con Developers para automatizar builds y despliegues
- Con QA para disponibilidad de entornos de staging/test
- Con PM/PdM para comunicar restricciones operativas y planes de rollout

### Cuándo involucrar
- En planificación para consideraciones de despliegue; en cambios infra

---

## Stakeholder (definición ampliada)

### Role Summary
Aporta contexto de negocio, aprobaciones y prioridades. Esta definición amplía tipos de stakeholders y expectativas.

### Tipos típicos de stakeholders
- Representantes de clientes / usuarios finales
- Sponsors y dueños del producto
- Seguridad / cumplimiento / legal
- Soporte u operaciones

### Responsibilities
- Proveer input de dominio y decisiones a tiempo
- Revisar criterios de aceptación y entregables mayores
- Aprobar releases cuando requerido por negocio o cumplimiento

### Interacciones
- Con PdM en priorización
- Con PM para comunicaciones y estado
- Con QA/DevOps para checks de readiness y cumplimiento

---

## Guía de interacción y handoffs

- Propiedad de criterios de aceptación: PdM define criterios funcionales; QA Lead valida cobertura; Developers implementan y verifican.
- Readiness de release: PM coordina revisión de readiness; DevOps valida pipelines; QA hace verificación final.
- Dependencias cross-team: PM documenta y escala riesgos; Scrum Master hace seguimiento; BA documenta integraciones necesarias.
- Canales de comunicación: usar project board como fuente de verdad, sincronizaciones semanales entre PM+PdM y Slack/email para escalaciones críticas.

---

## Uso de estas personas en ejercicios
- Emplear estas definiciones para enmarcar escenarios y ejercicios de Skills.
- Cada persona puede convertirse en prompt para Copilot Spaces para obtener guías específicas por rol.
