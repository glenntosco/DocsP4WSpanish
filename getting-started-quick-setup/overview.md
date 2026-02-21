---
description: P4 Warehouse Resumen
---

# Resumen

**Tipos de Usuarios**

En P4 Warehouse hay dos estilos de usuarios completamente únicos.

**Despachador Web:** El despachador web utiliza una computadora y un navegador web moderno para gestionar el flujo de entrada y salida del almacén. El despachador web también controla el flujo de trabajo de los usuarios PDT. Piensa en los despachadores web como la torre de control en un aeropuerto.

**Usuario PDT:** El usuario PDT son las personas en el almacén ejecutando las instrucciones establecidas por el Despachador Web. Estas son las personas que físicamente reciben Órdenes de Compra y RMA's, recogen y envían pedidos salientes, y realizan el Conteo Cíclico del inventario. Estos usuarios trabajan desde un dispositivo móvil, generalmente con un escáner de códigos de barras.

Necesitarás una buena cantidad de experiencia en almacenes/WMS para usar este documento. Contacta a tu socio de ventas de P4 Warehouse si te encuentras con temas que no comprendas completamente.

Aquí puedes encontrar la información de contacto de soporte para tu país.

**Android**

Android Nuget y versiones superiores funcionarán con el Sistema P4 Warehouse. P4W Handheld se puede descargar a un dispositivo Android desde [Google Play Store](https://play.google.com/store/apps/details?id=com.pro4soft.p4w\&hl=en_US\&gl=US).

Se recomienda que el dispositivo Android tenga un escáner de códigos de barras incorporado. El hardware de Zebra Technologies funciona mejor ya que el WMS de P4 Warehouse está validado por Zebra para funcionar correctamente en sus Computadoras Móviles Android.

**Definiciones**

Hay palabras específicas relacionadas con la industria logística que a veces no se entienden claramente. A continuación, se presentan algunas de las definiciones de palabras que encontrarás en esta documentación:

**Despachador Web** — Usuario que trabaja desde una computadora usando un navegador web para gestionar las operaciones del almacén, crear órdenes, configurar el sistema y monitorear las actividades del piso del almacén.

**Usuario PDT** — Usuario de Terminal Portátil de Datos; trabajadores del piso del almacén que usan dispositivos móviles Android con escáneres de códigos de barras para ejecutar tareas de almacén (recepción, picking, envío, conteo cíclico).

**SKU** — Unidad de Mantenimiento de Stock (Stock Keeping Unit); un identificador único de producto utilizado para rastrear el inventario.

**LPN** — Número de Placa de Licencia (License Plate Number); un identificador único para una paleta, cartón o contenedor que agrupa múltiples productos para seguimiento y movimiento.

**Ticket de Picking** — Documento de orden que instruye a los trabajadores del almacén qué productos recoger, cantidades y ubicaciones.

**Onda** — Grupo de tickets de picking liberados juntos para picking, típicamente organizados por zona, transportista o fecha de envío.

**Asignación** — Proceso de reservar inventario para órdenes específicas antes de que comience el picking.

**Cartonización** — Proceso automatizado de determinar tamaños óptimos de cartón y configuraciones de empaque para pedidos salientes.

**Putaway** — Mover inventario recibido desde el muelle a su ubicación de almacenamiento designada.

**Conteo Cíclico** — Proceso regular de conteo de inventario que verifica que el stock físico coincida con los registros del sistema sin requerir un cierre completo del almacén.

**Control de Lote** — Rastreo de inventario por lote de producción o número de lote, típicamente para trazabilidad y control de calidad.

**Control por Serie** — Rastreo de inventario a nivel de unidad individual usando números de serie únicos.

**Control de Vencimiento** — Gestión de productos con fechas de vencimiento para asegurar la rotación FIFO/FEFO y prevenir el envío de productos vencidos.

**Packsize** — Jerarquía de unidad de medida de 5 niveles de P4 Warehouse (Cada Uno, Paquete Interno, Caja, Paleta, Contenedor) que puede incluir cantidades decimales para productos basados en peso.

**3PL** — Logística de Terceros (Third-Party Logistics); operador de almacén que almacena y cumple órdenes para múltiples empresas cliente.

**BOM** — Lista de Materiales (Bill of Materials); lista de componentes requeridos para fabricar un producto terminado (usado en producción, no en cumplimiento).

**Paquete de Producto** — Un solo SKU que representa múltiples productos componentes para propósitos de cumplimiento (el ticket de picking muestra los componentes, no el SKU del paquete).

**ASN** — Aviso Anticipado de Envío (Advanced Shipping Notice); notificación electrónica enviada antes de que llegue un envío, conteniendo detalles de productos y cantidades.

**BOL** — Conocimiento de Embarque (Bill of Lading); documento legal entre el remitente y el transportista detallando el contenido del envío.

**Cross-Dock** — Recibir inventario e inmediatamente enviarlo sin putaway a almacenamiento, minimizando el tiempo de manejo.

**FIFO** — Primero en Entrar, Primero en Salir (First In, First Out); método de rotación de inventario donde el stock más antiguo se recoge primero.

**FEFO** — Primero en Vencer, Primero en Salir (First Expired, First Out); método de rotación de inventario donde los productos con las fechas de vencimiento más tempranas se recogen primero.

**Código de Razón** — Código definido por el sistema usado para documentar por qué ocurrió un ajuste, devolución o cambio de inventario.

**Tote** — Contenedor usado para consolidar artículos recogidos para una orden durante el proceso de picking y staging.

**Puerta de Muelle** — Área designada de carga/descarga donde se asignan camiones para recepción o envío.

**Zona** — Subdivisión lógica del espacio del almacén utilizada para organizar el inventario y optimizar los flujos de trabajo.

**Bin** — Ubicación de almacenamiento específica dentro de una zona donde se almacena el inventario (estante, posición de rack, ubicación de piso).

Para un glosario completo de términos de la cadena de suministro, consulte [Glosario de la Cadena de Suministro](supply-chain-glossary.md).

