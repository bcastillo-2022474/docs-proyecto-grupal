# Módulos del Sistema de Gestión Hotelera

## 1. Módulo de Gestión de Usuarios

- Registro e inicio de sesión de usuarios
- Perfiles de usuarios (`CLIENT`, `ADMIN_HOTEL`, `ADMIN_PLATFORM`)
  - **CLIENT**: Persona en búsqueda de un hotel
    - Capacidades: Registrarse, iniciar sesión, buscar y reservar hoteles, ver historial de reservaciones.
  - **ADMIN_HOTEL**: Persona encargada de un hotel, puede modificar información y detalles del mismo
    - Capacidades: Registrarse, iniciar sesión, crear y administrar hoteles (CRUD), gestionar habitaciones, ver reservaciones del hotel.
  - **ADMIN_PLATFORM**: Administrador de toda la plataforma, puede banear y modificar información de hoteles
    - Capacidades: Registrarse, iniciar sesión, gestionar usuarios (activar, desactivar, banear), acceder a estadísticas y reportes, configurar parámetros del sistema.
- Autenticación y autorización basada en roles y permisos
- Login
- Signup
  2 signup diferentes para `ADMIN_HOTEL` y `CLIENT`

## 2. Módulo de Hoteles

- Registro y administración de hoteles (CRUD)
  - Capacidad para que un usuario `ADMIN_HOTEL` pueda crear, editar, eliminar y gestionar hoteles
  - Gestión de información detallada de hoteles (dirección, categoría, precios, comodidades, servicios, instalaciones, etc.)
- Gestión de habitaciones
  - Tipos de habitaciones (individual, doble, suite, etc.)
  - Capacidad de cada habitación (número de personas)
  - Disponibilidad de habitaciones por fechas
  - Precios de habitaciones según tipo y temporada

## 3. Módulo de Reservaciones

- Búsqueda y reserva de hoteles y habitaciones
  - Filtros de búsqueda (ubicación, fechas, precios, servicios, etc.)
  - Selección de habitaciones disponibles
  - Proceso de reserva y pago (simulado)
- Visualización de disponibilidad de habitaciones
  - Calendarios de disponibilidad por hotel y tipo de habitación
  - Debe Desplegar un Calendario con fechas disponibles y todo.
- Proceso de check-in y check-out
  - Registro de entrada y salida de huéspedes
  - Cálculo de estancia y costos
- Historial de reservaciones para usuarios
  - Detalles de reservaciones pasadas y futuras
- Agregar hoteles a favoritos
  - Opción para marcar hoteles como favoritos durante la búsqueda
  - Lista de hoteles favoritos en el perfil del usuario
  - Acceso rápido a hoteles favoritos para futuras reservaciones

## 4. Módulo de Facturación

- Generación de facturas simuladas al finalizar la estadía de huéspedes
  - Detalles de la reservación (fechas, habitaciones, servicios)
  - Cálculo del costo total de la estadía
- Simulación del proceso de pago
  - Opciones de pago (efectivo, tarjeta de crédito/débito)
  - Validación de información de pago
  - Confirmación de pago exitoso

<!-- OBLIGATORIO -->
## 5. Módulo de Eventos

<!-- Aun no se como haremos esto -->
- Programación y modificación de eventos en hoteles (por ejemplo: conferencias, bodas, reuniones)
<!-- Que clase de recursos, que clase de servicios? -->
- Asignación de recursos y servicios adicionales para eventos
<!-- Que implica reservar un evento? es un costo fijo dependiendo el tipo de evento? comunicacion manual?
Como? esto implica hacer un sistema de Eventos, es una aplicación en si, preferiria no hacerla. pero
es obligatoria, leer requerimientos.
 -->
- Gestión de reservaciones de eventos

## 6. Módulo de Administración

- Gestión de usuarios registrados en la plataforma
  - Activar, desactivar y banear usuarios
  - Asignar roles y permisos a usuarios
- Acceso a estadísticas y rendimiento de operaciones
  - Métricas de reservaciones, ocupación, demanda, ingresos
  - Reportes y dashboards analíticos
- Configuración y mantenimiento del sistema
  - Parámetros generales (impuestos, tarifas, políticas, etc.)
  - Reglas de negocio (políticas de cancelación, restricciones, etc.)
  - Gestión de contenido (descripciones, imágenes, promociones, etc.)

<!-- PRIORIDAD BAJA -->
## 7. Módulo de Reviews

- Permitir a los usuarios dejar reseñas y calificaciones sobre los hoteles
  - Calificación con estrellas (1 a 5)
  - Comentario textual sobre su experiencia
- Visualización de reseñas y calificaciones promedio de cada hotel
  - Lista de reseñas más recientes
  - Calificación promedio calculada
<!-- Si nos queremos poner salsas -->
- Funcionalidades adicionales:
  - Reportar reseñas inapropiadas
  - Responder reseñas (para administradores de hotel)
  - Filtrar reseñas por calificación, fecha, etc.

<!-- PRIORIDAD BAJA -->
## 8. Módulo de Informes y Estadísticas

- Generación de informes de demanda de hoteles
  - Hoteles más solicitados por ubicación y temporada
  - Ocupación de habitaciones por hotel
- Estadísticas de reservaciones
  - Reservaciones por periodos de tiempo
  - Ingresos generados por reservaciones
- Reportes de reservaciones realizadas por hotel
  - Detalles de huéspedes, habitaciones, fechas, ingresos
- Gráficos y visualizaciones de datos
  - Dashboards interactivos para análisis de datos

