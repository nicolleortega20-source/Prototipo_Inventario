# SCII — Sistema de Control de Ítems e Ingresos

## Prototipo HTML v2.0

**Universidad Autónoma de Aguascalientes**
**Centro de Ciencias de la Empresa (CCE)**
**Licenciatura en Tecnologías de Información y Comunicación (LITC)**

---

# Objetivo

Desarrollar un sistema que permita gestionar de manera eficiente el inventario de ítems del Centro de Ciencias de la Empresa, facilitando el registro y control de entradas y salidas, la consulta de movimientos históricos, la generación de reportes y la administración de usuarios con distintos niveles de acceso.

---

# Descripción

SCII (Sistema de Control de Ítems e Ingresos) es un prototipo de interfaz de usuario diseñado para apoyar la gestión del inventario del Centro de Ciencias de la Empresa.

El sistema permite controlar existencias, registrar movimientos de inventario, consultar historiales, generar reportes y administrar usuarios mediante una interfaz sencilla y orientada a usuarios administrativos.

Este prototipo fue desarrollado utilizando HTML, CSS y JavaScript puro en un único archivo autocontenido. No requiere instalación de software adicional, bases de datos ni conexión a internet para su ejecución.

---

# Cómo ejecutar el prototipo

1. Descargar el archivo **prototipo_inventario_v2.html**.
2. Abrir el archivo directamente en cualquier navegador moderno:

   * Google Chrome
   * Mozilla Firefox
   * Microsoft Edge
   * Safari
3. Navegar entre las pantallas utilizando los botones y opciones disponibles dentro de la interfaz.
4. No se requiere servidor local ni configuración adicional.

---

# Estructura del repositorio

```text
/
├── prototipo/
│   └── prototipo_inventario_v2.html
│
├── documentacion/
│   ├── Especificacion_Final_Proyecto.docx
│   ├── Matriz_Requerimientos.xlsx
│   └── Matriz_Trazabilidad.xlsx
│
├── diagramas/
│   ├── Diagrama_AS-IS.pdf
│   ├── Diagrama_TO-BE.pdf
│   ├── Diagrama_ER.png
│   └── Diagrama_ER.mwb
│
├── minutas/
│   ├── Minutas_Entrevistas.pdf
│   └── Minuta_Validacion_Prototipo.docx
│
└── README.md
```

---

# Flujo principal del prototipo

```text
PNT-01 Dashboard
        ↓
PNT-02 Inventario
        ↓
PNT-03 Movimientos
        ↓
PNT-04 Reportes
        ↓
PNT-05 Usuarios
```

---

# Pantallas del prototipo

| ID     | Nombre      | Descripción                                                                                                                                 |
| ------ | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| PNT-01 | Dashboard   | Vista general del sistema con indicadores clave, alertas de inventario, movimientos recientes y accesos rápidos a las principales funciones |
| PNT-02 | Inventario  | Gestión de artículos, consulta de existencias, edición de información, control de estados, préstamos y categorías                           |
| PNT-03 | Movimientos | Historial de entradas y salidas con filtros y clasificación por tipo de movimiento                                                          |
| PNT-04 | Reportes    | Generación y exportación de reportes relacionados con inventario, movimientos y préstamos                                                   |
| PNT-05 | Usuarios    | Administración de usuarios, roles y estados dentro del sistema                                                                              |

---

# Cambios incorporados en la versión 2.0

Las siguientes mejoras fueron implementadas a partir de la retroalimentación obtenida durante la sesión formal de validación con el cliente realizada el 29 de mayo de 2026.

### PNT-01 Dashboard

* Actualización de la paleta visual utilizando colores institucionales de la UAA.
* Incorporación del logotipo institucional.
* Implementación de botones interactivos para acceso rápido.
* Tarjetas KPI navegables.

### PNT-02 Inventario

* Modal de confirmación para ajustes de cantidad.
* Confirmación previa al guardado de cambios.
* Inclusión del campo "Docente Responsable" en préstamos.
* Visualización del historial de préstamos por artículo.

### PNT-03 Movimientos

* Implementación de pestañas independientes:

  * Todos
  * Entradas
  * Salidas
* Contadores por categoría de movimiento.

### PNT-04 Reportes

* Actualización visual con colores institucionales.
* Inclusión de reporte de historial de préstamos por artículo.

### PNT-05 Usuarios

* Actualización de diseño visual utilizando la identidad gráfica institucional.

---

# Cobertura de requerimientos

Todos los requerimientos funcionales clasificados como **Must-have** en la Matriz de Requerimientos cuentan con representación visual dentro del prototipo y pueden ser rastreados mediante la Matriz de Trazabilidad incluida en este repositorio.

---

# Requerimientos no funcionales

Los requerimientos no funcionales relacionados con aspectos técnicos de implementación no pueden validarse mediante un prototipo HTML estático.

Por lo tanto, los siguientes requerimientos se clasifican como:

**"No aplica al prototipo"**

y serán validados durante la etapa de implementación real del sistema:

* RNF-02 Red interna institucional.
* RNF-03 Rendimiento del sistema.
* RNF-04 Disponibilidad.
* RNF-05 Soporte multiusuario.
* RNF-06 Integridad y consistencia de datos.

---

# Validación del cliente

El prototipo fue presentado al cliente para su revisión formal.

**Cliente responsable:**
Luis Armando Pedroza Sustaita
Jefe de Departamento — Centro de Ciencias Económicas

**Fecha de validación:**
29 de mayo de 2026

**Resultado de validación:**
Aprobado con los cambios indicados en la Minuta de Validación del Prototipo.

Las observaciones recibidas fueron incorporadas en la versión final 2.0 entregada para evaluación académica.

---

# Equipo desarrollador

| Integrante                         | Rol                  |
| ---------------------------------- | -------------------- |
| Carmen Elizabeth González Guerrero | Equipo desarrollador |
| Carla Alejandra Montalvo Ojeda     | Equipo desarrollador |
| Nicolle Ortega Moreno              | Equipo desarrollador |

---

# Evidencias incluidas

El repositorio contiene:

* Prototipo HTML navegable.
* Matriz de Requerimientos validada.
* Matriz de Trazabilidad.
* Especificación Final del Proyecto.
* Diagramas AS-IS y TO-BE.
* Modelo Entidad-Relación.
* Archivo MySQL Workbench (.mwb).
* Minutas de entrevistas.
* Minuta de validación del prototipo.

---

# Información de la entrega

Versión: 2.0

Fecha de validación del prototipo: 29/05/2026

Fecha de entrega final: 19/06/2026

Universidad Autónoma de Aguascalientes
