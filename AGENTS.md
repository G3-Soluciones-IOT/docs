# AGENTS.md

- Este repositorio contiene documentación académica en Markdown.
- Prioriza revisión estructural, formato Markdown y alineación con la rúbrica.
- No reescribas secciones completas sin pedirlo.
- Para revisiones, primero reporta hallazgos; edita solo si se solicita.
- No inventes contenido técnico no presente en el documento.
# AGENTS.md

## 1. Project Context

This project is a distributed IoT system for nutritional monitoring, composed of multiple independent systems and repositories.

The solution includes:

- IoT Devices (Embedded Systems)
- Edge Computing
- Cloud Backend Services
- Web Application
- Mobile Application
- AI-based validation services

---

## 2. Repository Strategy (CRITICAL)

This project uses a **multi-repository architecture**.

### 2.1 Documentation Repository

This repository ONLY contains:

- Project report (Markdown)
- UX artifacts (Lean UX, Personas, Journey Maps)
- Architecture documentation (DDD, C4)
- Research evidence
- Diagrams and assets

This repository MUST NOT contain:
- Source code
- Backend/frontend/mobile implementations

---

### 2.2 Code Repositories

Each system component is isolated in its own repository:

- backend-services
- frontend-web-app
- mobile-app
- iot-devices
- edge-services

Each repository:
- Has its own lifecycle
- Uses its own GitFlow
- Is independently deployable

---

### 2.3 Relationship Between Repositories

Documentation MUST reference:

- APIs defined in backend repository
- Features implemented in frontend/mobile
- Data produced by IoT devices

All documentation must remain consistent with implementation.

---

## 3. Engineering Approach

The project MUST follow:

- Lean UX
- UX Research
- Domain-Driven Design
- C4 Model
- Agile (Scrum, Product Backlog)

---

## 4. Documentation Rules

All documentation MUST:

- Be written in Markdown
- Be traceable to research (interviews, personas)
- Maintain consistency with Ubiquitous Language
- Avoid assumptions without evidence

---

## 5. Content Generation Rules

### DO:
- Generate content ONLY for documentation repository
- Align with rubric requirements
- Maintain UX → Requirements → Architecture traceability

### DO NOT:
- Generate source code in this repository
- Mix implementation with documentation
- Create generic or non-contextual content

---

## 6. Architecture Constraints

- Must reflect distributed IoT architecture
- Must include Edge + Cloud separation
- Must define REST APIs (even if implemented elsewhere)
- Must align with DDD bounded contexts

---

## 7. UX Constraints

- All features MUST originate from:
  - Interviews
  - Personas
  - Journey Maps

---

## 8. Validation Requirements

- Must include real user interviews
- Must provide video evidence
- Must reflect iteration and improvements

---

## 9. Consistency Rules

- Same domain terms across:
  - UX artifacts
  - DDD models
  - Documentation

---

## 10. Anti-Patterns

- Mixing code and documentation
- Designing without UX validation
- Creating features not backed by research
- Overengineering AI without justification