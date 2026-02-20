---
description: P4 Warehouse Órdenes de compra pendientes
---

# Órdenes de compra pendientes

La página de Pedidos Pendientes (Pedidos de Compra) presenta un listado de todos los pedidos de compra pendientes en el software del Sistema de Gestión de Almacenes. Hay columnas para Casilla de Selección, Estado, Número de OC, Proveedor, Cliente, Almacén, Designación, Muelle, Número de Citación, Fecha de Citación (Número y Fecha de Citación; se utiliza cuando el producto debe entregarse en una fecha específica, normalmente el conductor de entrega coordinará con el despachador del almacén) y creado. También hay cuatro botones en la parte superior derecha. El primer botón es «Entrada de Datos» con dos opciones: Nuevo (crear un nuevo pedido) y A borrador (asignar un pedido seleccionado al estado de borrador). El segundo botón es «Recepción» con tres opciones: Liberar a planta (saca un pedido del estado de borrador y lo convierte en una tarea activa que debe realizarse), Asignar operador (asigna un pedido a un operador concreto) y Asignar puerta de muelle (asigna un pedido a una puerta de muelle concreta). El tercer botón es «Otros» con dos opciones: Correo electrónico (para enviar una notificación por correo electrónico a un tercero) y Eliminar (eliminar un pedido seleccionado de la lista). El último botón es «Actualizar» (para actualizar la lista una vez realizados los cambios). El botón «Exportar todos los datos» se encuentra justo debajo de los cuatro botones descritos anteriormente, y aparece como una carpeta negra rodeando una X blanca. Tanto las columnas de Fecha de la cita como las de Creado tienen un botón de Calendario en la parte derecha. Al seleccionar este botón, aparecerá un menú desplegable en el que podrá seleccionar una fecha del calendario.

![P4 Warehouse Lista de pedidos
](<../.gitbook/assets/image (92).png>)

Para crear una nueva orden de compra, seleccione el botón «Entrada de Datos» y elija la opción Nuevo. Aparecerá la ventana emergente Nuevo pedido con opciones para Proveedor, Almacén y Número de pedido. Seleccione el Proveedor y el Almacén en los menús desplegables. Introduzca un número de pedido manualmente o deje el campo vacío (lo que generará automáticamente un nuevo número de pedido). Seleccione el botón «Enviar» y el sistema de Almacén P4 abrirá la página de Orden de Compra.

![P4 Warehouse añadir nueva orden](<../.gitbook/assets/image (20).png>)

Alternativamente, edite un pedido de compra existente seleccionando el número de pedido de compra en la lista bajo la columna Número de pedido. El sistema P4 Warehouse abrirá la página de perfil de ese pedido en particular. En la parte superior derecha, junto al número de pedido, se encuentra la opción de selección de texto «Auditoría...» que proporciona un registro de seguimiento completo (rastro cronológico de eventos y detalles) sobre este pedido de compra. Debajo está la sección Cabecera para editar Proveedor, Almacén, Referencia y Comentarios. A la derecha se encuentra la sección Cita, donde el pedido puede aplicarse a un transportista, con un número de transportista, una opción Programada para elegir una fecha con un menú desplegable de calendario, una opción Puerta de muelle y la opción de selección de texto «Asignar».



![](<../.gitbook/assets/image (323).png>)

\
Seleccione la opción de selección de texto «Asignar» y aparecerá una ventana emergente para asignar este pedido a un usuario. En la ventana emergente aparecerá una lista de usuarios existentes con un botón «Elegir» a la izquierda de cada nombre de usuario. Una vez asignado un usuario, la ventana emergente desaparecerá y, de vuelta a la página de perfil del pedido de compra, el campo «Asignado a» mostrará el usuario seleccionado. Ahora también habrá un botón de opción a la derecha para «Eliminar» el usuario asignado.

![Asignar usuario para el pedido](<../.gitbook/assets/image (326).png>)

\
Cerca de la parte inferior de la página de la orden de compra se encuentra la sección Líneas que detalla todos los artículos que actualmente forman parte de esta orden de compra. La lista incluye columnas para una imagen en miniatura, Producto, Descripción, Tamaño del paquete, Paquetes, Cantidad (con una opción de menú para aumentar/disminuir) y Acción. En la esquina superior derecha de la página del pedido aparecen tres botones. El botón «Actualizar» revisará el perfil del pedido de compra con los cambios realizados. El botón «Liberar al piso» coloca la orden de compra en el siguiente estado activo, típicamente No Recibido. Todos los pedidos de compra se encuentran en estado Borrador hasta que se selecciona el botón «Liberar a planta». Una vez liberada una orden de compra, seleccione el botón «A Borrador» para revertir la orden de compra al estado Borrador. Seleccione el botón «Actualizar» para visualizar los cambios.



