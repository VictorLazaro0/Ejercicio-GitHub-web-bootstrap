# Ejercicio-GitHub-web-bootstrap
   
## Nombre de los integrantes del equipo
## Victor Manuel Lazaro Bravo
## Alexia Pichardo 
## Gonzalo Ramos Amador 


# Práctica de Git y GitHub: Flujo de Trabajo Colaborativo

## Objetivo
Reforzar los conocimientos adquiridos en las sesiones de Git y GitHub mediante la construcción de una página web sencilla en equipo y la simulación de escenarios reales de control de versiones.

---

## Instrucciones y Elementos del Proyecto
La página web base incluye:
- **`index.html`**: La página de inicio.
- **Bootstrap 5**: Incluido mediante CDN dentro del proyecto.
- **Carpeta `css/` con `global.css`**: Archivo para los estilos personalizados de la página.

---

## Tareas del Ejercicio

### 1. Creación del Repositorio y Colaboradores
- Se creó un repositorio central en GitHub.
- Se agregaron a los integrantes del equipo como colaboradores con permisos de escritura para gestionar ramas y contribuciones de manera conjunta.

---

### 2. Definición del Flujo de Trabajo (Git Flow simplificado)
Se estableció la siguiente estructura de ramas para evitar cruces de código y mantener el proyecto ordenado:
- **`main`**: Rama principal de producción. Contiene únicamente las versiones estables y aprobadas del proyecto. Nadie programa directamente en ella.
- **`develop`**: Rama de integración. Es el punto central donde se unen los avances de todos los colaboradores antes de pasar a `main`.
- **Ramas de funcionalidad (`feature/nombre-colaborador` o `feature/tarea`)**: Ramas individuales creadas a partir de `develop` donde cada integrante desarrolla su parte de forma aislada.

---

### 3. Selección del Modelo de IA
- **IA seleccionada:** Gemini (Google).
- **Rol asignado:** Instructor práctico de Git y GitHub, enfocado exclusivamente en guiar los procesos de sincronización, subida, descarga y resolución de incidencias entre el entorno local y GitHub.

---

### 4. Guía de Escenarios Reales de Trabajo con Git y GitHub

#### Escenario 1: Todo funciona correctamente (Flujo diario)
1. **Clonar el repositorio por primera vez:**
   ```bash
   git clone <url-del-repositorio>
   cd nombre-repositorio
