# Proyecto práctica
## Descripción
Página de crowfunding para proyectos universitarios con fines académicos y/o investigación, que les permite recaudar fondos necesarios para ejecutar su idea o proyecto.

## Alcance

### Objetivos

### Público
1. Estudiantes de pregrado.
2. Estudiantes de postgrado.
3. Investigadores académicos.

## Requerimientos 

### Funcionales
### 1. Autenticación y Autorización
- Registro de nuevos usuarios (estudiantes o investigadores)
- Inicio de sesión (login) y cierre de sesión
- Recuperación de contraseña por correo
- Gestión de roles de usuario: inversor / creador de proyecto / administrador

### 2. Gestión de Proyectos
- Crear nuevo proyecto de crowdfunding
- Editar información de un proyecto (nombre, descripción, meta, fecha límite)
- Eliminar proyecto propio
- Subir imágenes o archivos del proyecto
- Visualizar estado actual de recaudación de fondos

### 3. Explorar e Invertir
- Listar todos los proyectos disponibles
- Filtrar proyectos por categoría, universidad o estado
- Visualizar detalles del proyecto (descripción, video, metas, autor)
- Realizar aportes/donaciones a un proyecto
- Ver historial de aportes realizados

### 4. Perfil de Usuario
- Visualizar y editar perfil personal
- Ver proyectos creados por el usuario
- Consultar contribuciones realizadas como inversor
- Recibir notificaciones sobre actividad (nuevos aportes, fechas límite, etc.)

### 5. Panel de Administración (solo para administradores)
- Gestionar usuarios registrados
- Ver y moderar todos los proyectos publicados
- Eliminar proyectos que incumplan políticas
- Generar reportes de actividad y estadísticas del sistema

### 6. Integraciones Externas
- Envío de notificaciones por WhatsApp (WhatsApp Cloud API)
- Conexión con Gemma 3 para funcionalidades IA (pendiente de definir uso)

### No funcionales

## Arquitectura

### Base de Datos
- Postgresql

### Front-end
- React
### Back-end
- Django
- JWT
- Python

### Servicios de externos
- Cloud API Whatsapp
- Gemma 3
- Blockchain