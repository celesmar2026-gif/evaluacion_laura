# Módulo Backend CRUD - Sistema IPASME (UNETI)

Proyecto desarrollado en Node.js, Express y MongoDB Atlas adaptado al Proyecto Sociotecnológico III (PWA IPASME "Dr. Julio de Armas"). Este módulo gestiona el agendamiento y control de citas médicas mediante una arquitectura RESTful ligera.

---

## 🗄️ Estructura de la Base de Datos

La base de datos ipasme_db en MongoDB Atlas está conformada por 5 colecciones principales:

1. **citas_medicas** (Módulo principal): Registra las citas de los afiliados (id_cita, cedula_paciente, especialidad_medica, estado_cita).
2. **usuarios**: Gestión del personal médico y administrativo (cedula, nombre_completo, rol, especialidad).
3. **pacientes**: Registro de beneficiarios y afiliados al IPASME (cedula_afiliado, nombre_completo, tipo_afiliado, telefono).
4. **historias_medicas**: Histórico clínico de atenciones (id_historia, cedula_paciente, diagnostico, fecha_atencion).
5. **medicamentos**: Control de inventario farmacéutico (codigo_item, nombre_medicamento, cantidad_disponible, laboratorio).

---

## 🛠️ Requisitos Previos

* Node.js (versión 14 o superior)
* npm (gestor de paquetes de Node)
* Una cuenta y clúster activo en MongoDB Atlas

---

## 🚀 Instrucciones de Instalación y Ejecución

Sigue estos pasos para ejecutar el proyecto en tu entorno local:

### 1. Clonar el repositorio
`bash
git clone https://github.com/LauraLDEV/evaluacion_laura.git)
cd evaluacion-node-ipasme
