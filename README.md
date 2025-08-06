# 🛒 Sistema de Ventas en Java

Este es un sistema de ventas desarrollado en Java utilizando Swing para la interfaz gráfica y MySQL como base de datos. El objetivo es ofrecer una solución para gestionar productos, ventas y facturas.

## 📁 Estructura del Proyecto

- `Conexion/`: Contiene la clase responsable de conectarse a la base de datos MySQL.
- `modelo/`: Clases que representan las entidades del sistema (Producto, Usuario, etc.).
- `controlador/`: Lógica de negocio, validaciones y operaciones CRUD.
- `vista/`: Interfaces gráficas construidas con Java Swing.

## ⚙️ Requisitos

- **Java JDK 8** o superior
- **MySQL Server**
- **IDE** (NetBeans)
- **Conector JDBC** (`mysql-connector-java-x.x.xx.jar`)

## 🧠 Configuración Inicial

1. **Configurar la conexión a la base de datos:**

 - Abre el archivo dentro de la carpeta `Conexion` y modifica las credenciales para que coincidan con tu entorno local(MySQL):

2. **Importar la base de datos:**

- Dentro del proyecto encontrarás un archivo .sql con la estructura de la base de datos.

- Usa MySQL Workbench para importarlo.

3. **Crear un usuario en la base de datos:**

- El sistema requiere que exista al menos un usuario registrado para poder iniciar sesión.

