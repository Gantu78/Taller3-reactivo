# Sistema de Gestión de Notas (Spring WebFlux + React)

Sistema reactivo para la gestión de notas de estudiantes desarrollado con Spring WebFlux y React.

## Características

- Gestión de estudiantes (CRUD)
- Gestión de materias (CRUD)
- Gestión de notas con cálculo de promedio
- Validaciones en tiempo real
- Interfaz reactiva y moderna
- Manejo de errores robusto

## Tecnologías Utilizadas

### Backend
- Spring Boot
- Spring WebFlux
- R2DBC
- PostgreSQL
- Maven

### Frontend
- React
- Vite
- Axios
- Bootstrap

## Requisitos Previos

- Java 17 o superior
- Node.js 14 o superior
- PostgreSQL

## Configuración

### Base de Datos
1. Crear una base de datos PostgreSQL
2. Actualizar las credenciales en `backend/src/main/resources/application.properties`

### Backend
```bash
cd backend
./mvnw spring-boot:run
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

## Funcionalidades

- Gestión completa de estudiantes
- Gestión de materias
- Registro y edición de notas
- Cálculo automático de promedios
- Validaciones de porcentajes
- Interfaz intuitiva y responsive
- Manejo de errores con mensajes específicos

## Características Reactivas

- Server-Sent Events (SSE) para actualizaciones en tiempo real
- Flujos reactivos con Spring WebFlux
- Actualizaciones automáticas de promedios
- Validaciones instantáneas