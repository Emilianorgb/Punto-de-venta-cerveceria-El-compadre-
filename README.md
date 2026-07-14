💾Sistema de Gestión para la Cervecería "El Compadre"


📝Introducción

La administración eficiente de un bar o cervecería requiere controlar múltiples procesos de forma simultánea, como la gestión de clientes, empleados, productos, inventario, compras, ventas, mesas y pagos. Cuando estas actividades se realizan de manera manual o mediante herramientas independientes, es común que se presenten errores en el registro de información, pérdidas de inventario, retrasos en la atención al cliente y dificultades para generar reportes que apoyen la toma de decisiones.


📝Planteamiento del Problema

Actualmente, muchos bares y cervecerías administran sus operaciones utilizando registros manuales o aplicaciones que no están integradas entre sí. Esta situación ocasiona problemas como:

✏️Errores en el registro de ventas.

✏️Pérdida o duplicidad de información.

✏️Descontrol del inventario.

✏️Dificultad para conocer la disponibilidad de productos.

✏️Retrasos en la asignación de mesas.

✏️Falta de control sobre los pagos realizados.

✏️Escasa generación de reportes para la administración del negocio.

Estas limitaciones afectan la productividad del establecimiento y dificultan la toma de decisiones oportunas.

Con el propósito de optimizar la operación del establecimiento, se propone desarrollar un Sistema de Gestión para Bar y Cervecería que centralice toda la información en una única plataforma, permitiendo automatizar los procesos administrativos y operativos mediante una interfaz gráfica intuitiva y una base de datos relacional.


📝Justificación

El desarrollo de un sistema informático permitirá automatizar las actividades principales del negocio, reduciendo errores humanos y mejorando el control de la información.

Además, facilitará el seguimiento de las ventas, el control del inventario, la administración de clientes y proveedores, así como la generación de reportes que apoyen la toma de decisiones del administrador.

La implementación de este sistema contribuirá a mejorar la eficiencia operativa, optimizar los tiempos de atención y proporcionar una administración más organizada y segura.


🎯 Objetivo General

Desarrollar un sistema de gestión para un bar y cervecería que permita administrar de manera eficiente los procesos de ventas, compras, inventario, clientes, empleados, proveedores, mesas y pagos, utilizando una arquitectura Modelo-Vista-Controlador (MVC), una base de datos MySQL y una interfaz gráfica intuitiva.


🎯 Objetivos Específicos

✏️Diseñar una base de datos relacional que garantice la integridad de la información.

✏️Implementar un sistema de autenticación para el acceso de los usuarios.

✏️Administrar la información de clientes, empleados y proveedores.

✏️Gestionar el catálogo de productos y sus categorías.

✏️Controlar las existencias del inventario.

✏️Registrar compras realizadas a proveedores.

✏️Registrar ventas efectuadas a los clientes.

✏️Gestionar la ocupación de las mesas.

✏️Registrar los pagos asociados a las ventas y compras.

✏️Generar reportes para apoyar la toma de decisiones.

✏️Desarrollar una interfaz gráfica intuitiva y fácil de utilizar.


📝Alcance

El sistema permitirá administrar las operaciones principales del establecimiento mediante los siguientes módulos:

✅Inicio de sesión.

✅Gestión de usuarios.

✅Gestión de empleados.

✅Gestión de clientes.

✅Gestión de proveedores.

✅Gestión de categorías.

✅Gestión de productos.

✅Gestión de inventario.

✅Gestión de compras.

✅Gestión de ventas.

✅Gestión de mesas.

✅Gestión de pagos.

✅Generación de recibos.

✅Reportes.

El sistema será desarrollado como una aplicación de escritorio en Java utilizando el patrón Modelo-Vista-Controlador (MVC) y una base de datos MySQL.

No se contempla para esta primera versión:

❌Facturación electrónica.

❌Pedidos en línea.

❌Aplicación móvil.

❌Integración con plataformas bancarias.

❌Administración de múltiples sucursales.

Actores del Sistema


🧑‍💼Administrador

Es el responsable de supervisar el funcionamiento general de El Compadre.

Funciones:

-Administrar usuarios.

-Gestionar empleados.

-Consultar reportes.

-Supervisar ventas y compras.

-Controlar el inventario.

👨‍🍳Mesero

Es el encargado de brindar atención a los clientes.

Funciones:

-Asignar mesas.

-Registrar pedidos.

-Registrar ventas.

-Registrar pagos.

-Liberar mesas.


📦Encargado de Inventario

Es responsable del abastecimiento de productos.

Funciones:

-Registrar proveedores.

-Registrar compras.

-Actualizar inventario.

-Consultar existencias.

-Administrar productos.

👨‍💻Requerimientos Funcionales

El sistema deberá permitir:

✔️Autenticar usuarios mediante inicio de sesión.

✔️Administrar usuarios del sistema.

✔️Registrar, consultar, actualizar y eliminar empleados.

✔️Registrar, consultar, actualizar y eliminar clientes.

✔️Registrar, consultar, actualizar y eliminar proveedores.

✔️Registrar, consultar, actualizar y eliminar categorías.

✔️Registrar, consultar, actualizar y eliminar productos.

✔️Actualizar automáticamente el inventario.

✔️Registrar compras.

✔️Registrar ventas.

✔️Asociar productos a una venta.

✔️Calcular automáticamente subtotales, IVA y total.

✔️Registrar pagos.

✔️Generar recibos.

✔️Consultar reportes.

❎Requerimientos No Funcionales
❌El sistema deberá desarrollarse en Java.

❌Utilizará Programación Orientada a Objetos.

❌Implementará la arquitectura Modelo-Vista-Controlador (MVC).

❌Utilizará MySQL como gestor de base de datos.

❌La conexión con la base de datos se realizará mediante JDBC.

❌La interfaz gráfica será intuitiva y fácil de utilizar.

❌El acceso estará protegido mediante autenticación de usuarios.

❌La información deberá mantenerse íntegra y consistente.

❌El sistema será compatible con sistemas operativos Windows.

🖥️Tecnologías a Utilizar

Componente	Tecnología

-Lenguaje	Java

-Arquitectura	MVC

-Base de Datos	MySQL

-Conectividad	JDBC

-IDE	IntelliJ IDEA

-Control de Versiones	Git

-Repositorio	GitHub

⚙️Arquitectura General del Sistema

El sistema será desarrollado siguiendo el patrón Modelo-Vista-Controlador (MVC), el cual divide la aplicación en tres componentes principales:

Modelo (Model): Gestiona la lógica del negocio y el acceso a la base de datos.

Vista (View): Contiene las interfaces gráficas con las que interactúan los usuarios.

Controlador (Controller): Coordina la comunicación entre la vista y el modelo, procesando las acciones del usuario.

Esta arquitectura facilita el mantenimiento, la escalabilidad y la reutilización del código.
