# Sprint 1 — Base integrada

**Periodo:** 28 de septiembre al 4 de octubre de 2026

## Objetivo
Dejar una base técnica integrada y demostrable de AlertaMuni, con autenticación común para móvil y web, backend Spring Boot conectado a PostgreSQL y catálogo inicial de categorías.

## Entregable mínimo
- Spring Boot ejecutando con estructura base de monolito modular.
- PostgreSQL conectado mediante JPA/Hibernate.
- Registro y login con JWT.
- Endpoint de categorías operativo.
- Android Kotlin con registro/login conectado a la API.
- React con login administrativo conectado a la API.
- Pruebas básicas de integración y evidencias.

## Responsables

### Rafael — Backend
- BACK-001 Inicializar Spring Boot.
- BACK-002 Configurar PostgreSQL y JPA.
- BACK-003 Implementar Identity/Auth.
- BACK-004 Implementar catálogo de categorías.

### Carlos — Android Kotlin
- MOB-001 Inicializar proyecto Android Kotlin.
- MOB-002 Implementar registro y login móvil.

### Ricardo — React
- WEB-001 Inicializar portal React.
- WEB-002 Implementar login administrativo.

### Abraham — Integración, QA y documentación
- INT-001 Integrar Kotlin con Spring Boot.
- INT-002 Integrar React con Spring Boot.
- QA-002 Preparar datos y ambiente de pruebas.
- DOC-DEV-001 Mantener documentación técnica.

## Criterio de cierre
El Sprint 1 se considera cerrado cuando móvil y web pueden autenticarse contra la misma API Spring Boot, los usuarios se persisten en PostgreSQL, el catálogo de categorías puede ser consultado y no existen defectos críticos abiertos en este flujo.

> Las funcionalidades de incidencias, cámara, GPS, mapa y seguimiento quedan para los siguientes sprints.
