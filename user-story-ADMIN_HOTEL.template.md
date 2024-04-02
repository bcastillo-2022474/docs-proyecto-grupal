# Historia de Usuario: Usuario ADMIN_HOTEL

Como usuario `ADMIN_HOTEL`, quiero poder:

1. **Registrar y Administrar mi Hotel**
   - Crear una nueva cuenta de usuario llenando un formulario con mis datos personales y credenciales.
   - Registrar un nuevo hotel, proporcionando información detallada como nombre, dirección, categoría, servicios, instalaciones, etc.
   - Editar y actualizar la información de mi hotel en cualquier momento.

2. **Gestionar Habitaciones**
   - Crear, editar y eliminar diferentes tipos de habitaciones (individual, doble, suite, etc.) para mi hotel.
   - Definir la capacidad, precios y disponibilidad de cada tipo de habitación.
   - Actualizar el inventario de habitaciones disponibles en función de las reservaciones realizadas.

3. **Gestionar Reservaciones**
   - Acceder a una sección de "Reservaciones" donde pueda ver todas las reservaciones realizadas para mi hotel.
   - Ver detalles de cada reservación, incluyendo información del huésped, habitaciones reservadas, fechas, costo total, etc.
   - Realizar el check-in y check-out de huéspedes.
   - Cancelar o modificar reservaciones existentes (sujeto a políticas y restricciones).

4. **Generar Facturas**
   - Generar facturas detalladas para los huéspedes al finalizar su estadía.
   - Incluir cargos adicionales por servicios extras (si aplica).
   - Registrar pagos realizados por los huéspedes.

5. **Acceder a Reportes y Estadísticas**
   - Ver reportes y estadísticas sobre la ocupación de habitaciones, ingresos generados, reservaciones por periodo, etc.
   - Analizar tendencias y patrones de demanda para mi hotel.

6. **Gestionar Reseñas y Calificaciones**
   - Ver las reseñas y calificaciones dejadas por los huéspedes sobre mi hotel.
   - Responder a las reseñas y comentarios de los usuarios.
   - Reportar reseñas inapropiadas o engañosas.

7. **Configurar Políticas y Reglas de Negocio**
   - Definir políticas de cancelación, restricciones y reglas específicas para mi hotel.
   - Establecer tarifas, descuentos y promociones especiales.
   - Gestionar contenido e imágenes relacionadas con mi hotel.

Esta historia de usuario cubre las principales funcionalidades y el flujo de uso esperado para un usuario ADMIN_HOTEL en el Sistema de Gestión Hotelera. Incluye aspectos como el registro y administración del hotel, la gestión de habitaciones y reservaciones, la generación de facturas, el acceso a reportes y estadísticas, la gestión de reseñas y calificaciones, y la configuración de políticas y reglas de negocio específicas para el hotel.

Cada uno de estos puntos puede ser desglosado en tareas y requerimientos más específicos durante el proceso de diseño y desarrollo de la interfaz de usuario y las funcionalidades correspondientes al rol ADMIN_HOTEL.

## Diagrama de flujo

Claro, separaré los flujos del usuario `ADMIN_HOTEL` en diferentes diagramas utilizando Mermaid para una mejor explicación:

1. **Flujo de Registro y Administración del Hotel**:

Este diagrama muestra el flujo de registro e inicio de sesión para un `ADMIN_HOTEL`

```mermaid
graph LR
    A[Inicio] --> B{Tiene cuenta?}
    B -->|No| C[Registrarse]
    C --> D[Llenar Formulario]
    D --> E[Crear Cuenta]
    E --> F[Iniciar Sesión]
    B -->|Sí| F[Iniciar Sesión]
    F --> G[Acceder a la Plataforma]
```

2. **Flujo de Gestion de creacion de un hotel**

Este diagrama de flujo detalla los siguientes pasos para el registro y administración de un nuevo hotel por parte de un usuario ADMIN_HOTEL

```mermaid
graph LR
    A[Acceder a la Plataforma] --> B[Registrar Nuevo Hotel]
    B --> C[Llenar Información del Hotel]
    C --> D{Información Completa?}
    D -->|No| C
    D -->|Sí| E[Enviar Solicitud de Registro]
    E --> F{Solicitud Aprobada?}
    F -->|No| G[Corregir Información]
    G --> E
    F -->|Sí| H[Hotel Registrado]
    H --> I[Ver Detalles del Hotel]
    I --> J{Editar Detalles?}
    J -->|Sí| K[Editar Detalles del Hotel]
    K --> L[Guardar Cambios]
    L --> I
    J -->|No| I
```

3. **Flujo de Gestión de Habitaciones**:

En este diagrama, se detalla el flujo para la gestión de habitaciones de un hotel, incluyendo la creación, definición de detalles, actualización del inventario, edición y eliminación de habitaciones.

```mermaid
graph LR
    A[Administrar Hotel] --> B[Gestionar Habitaciones]
    B --> C[Crear Habitación]
    C --> D[Definir Tipo, Capacidad y Precio]
    D --> E[Actualizar Inventario]
    E --> F[Editar Habitación]
    F --> G[Eliminar Habitación]
```

4. **Flujo de Gestión de Reservaciones**:

Este diagrama cubre el flujo de gestión de reservaciones para un `ADMIN_HOTEL`, incluyendo la visualización de reservaciones, la realización de check-in y check-out, la cancelación y modificación de reservaciones, y la actualización del inventario de habitaciones.

```mermaid
graph TD
    A[Administrar Hotel] --> B[Gestionar Reservaciones]
    B --> C[Ver Reservaciones]
    C --> D{Acción a Realizar}
    D -->|Check-in| E[Realizar Check-in]
    D -->|Check-out| F[Realizar Check-out]
    D -->|Cancelar| G[Cancelar Reservación]
    D -->|Modificar| H[Modificar Reservación]
    G --> I[Actualizar Inventario]
    H --> I[Actualizar Inventario]
```

5. **Flujo de Generación de Facturas y Reportes**:

En este diagrama, se muestra el flujo para la generación de facturas después del check-out de un huésped, incluyendo el registro de pagos, así como el acceso a reportes y estadísticas para el análisis del rendimiento del hotel.

```mermaid
graph TD
    A[Administrar Hotel] --> B{Acción a Realizar}
    B -->|Generar Factura| C[Generar Factura]
    C --> D[Registrar Pago]
    B -->|Ver Reportes| E[Acceder a Reportes]
    E --> F[Analizar Estadísticas]
```

6. **Flujo de Gestión de Reseñas y Configuración**:

Este último diagrama cubre el flujo para la gestión de reseñas y calificaciones de los huéspedes, incluyendo la respuesta y reporte de reseñas, así como la configuración de políticas, tarifas, promociones y contenido relacionado con el hotel.

Estos diagramas proporcionan una representación visual de los diferentes flujos de trabajo y funcionalidades que un usuario `ADMIN_HOTEL` puede realizar en el Sistema de Gestión Hotelera. Cada diagrama se enfoca en un aspecto específico, lo que facilita la comprensión del flujo y puede ser útil para el diseño y desarrollo de la interfaz de usuario correspondiente.

```mermaid
graph TD
    A[Administrar Hotel] --> B{Acción a Realizar}
    B -->|Gestionar Reseñas| C[Ver Reseñas]
    C --> D[Responder Reseña]
    C --> E[Reportar Reseña]
    B -->|Configurar Hotel| F[Definir Políticas]
    F --> G[Establecer Tarifas y Promociones]
    G --> H[Gestionar Contenido]
```
