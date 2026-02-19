#  Arquitectura del Sistema  
## Sistema de Gestión de Ventas.

---

##  Entradas (Inputs)

### 🔹 ¿Qué datos recibe el sistema.?
- Datos de clientes (nombre, cédula, teléfono, correo).
- Datos de productos (nombre, precio, cantidad en inventario).
- Datos de ventas (producto, cantidad, fecha).
- Credenciales de usuario (usuario y contraseña).


### 🔹 ¿Quién los ingresa?
- Administrador.
- Empleado de ventas.

### 🔹 Tipo de datos
-  Texto: nombres, correos, descripciones.
-  Números: precios, cantidades, totales.
-  Fechas: fecha de venta.
-  Archivos (opcional): reportes PDF o Excel.

---

## ⚙️ Procesos

### 🔹 ¿Qué hace el sistema.?
- Registra clientes y productos.
- Procesa ventas.
- Actualiza inventario automáticamente.
- Genera reportes.
- Controla acceso mediante autenticación.

### 🔹 Validaciones
- Campos obligatorios no vacíos.
- Cantidad disponible en inventario.
- Usuario y contraseña correctos.
- Formato correcto de datos (correo, números).

### 🔹 Cálculos
- Total de la venta.
- Impuestos.
- Ganancias.
- Stock disponible.

### 🔹 Almacenamiento
- Base de datos de clientes.
- Base de datos de productos.
- Historial de ventas.
- Registro de usuarios.

---

##  Salidas (Outputs).


### 🔹 ¿Qué obtiene el usuario?
- Confirmación de venta.
- Factura o comprobante.
- Lista de productos disponibles.
- Reportes de ventas.

### 🔹 ¿Qué genera el sistema?
- Reportes diarios, semanales y mensuales.
- Alertas de inventario bajo.
- Estadísticas de ventas.

### 🔹 ¿Permite tomar decisiones?
Sí:
- Reabastecer productos.
- Analizar productos más vendidos.
- Evaluar ganancias.
- Controlar rendimiento de ventas.

---

##  Usuarios y Roles.

### 🔹 Administrador
- Agregar, editar y eliminar productos.
- Gestionar usuarios.
- Ver reportes completos.
- Control total del sistema.

### 🔹 Usuario (Empleado de ventas)
- Registrar ventas.
- Consultar productos.
- Ver su historial de ventas.
- No puede eliminar productos ni usuarios.

---

## 🔐 Información Manejada

### 🔹 Datos críticos.
- Historial de ventas.
- Información financiera.
- Inventario.
- Credenciales de acceso.
- Datos de clientes.

### 🔹 Información que no se puede perder
- Registro de ventas.
- Control de inventario.
- Datos financieros.
- Usuarios registrados.

---

##  Tecnologías Sugeridas (Opcional)

- Lenguaje: Java
- Base de datos: MySQL
- Interfaz: Consola o aplicación gráfica
- Control de versiones: Git & GitHub
