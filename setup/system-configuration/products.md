---
description: P4 Warehouse Productos
---

# Productos

Esta página de configuración presenta el Formato de Expiración (por defecto es yyyyMMdd para Año-Mes-Día), Permitir Producto Expirado (Sí/No, por defecto: No), Imprimir Etiquetas de Tamaño de Paquete al Consolidar (Sí/No, por defecto: Sí), Unidad de Medida Decimal (unidad de medida para productos controlados decimalmente; por defecto es kilogramos Kg), Margen de Error Decimal (margen de error aceptable para productos controlados decimalmente por defecto; 1.5). Tras modificar cualquier entrada, seleccione el botón "Guardar" situado en la parte inferior derecha.

![P4 Warehouse Configuración general del producto](<../../.gitbook/assets/image (21).png>)

{% hint style="danger" %}
Establecer Permitir Producto Expirado a Verdadero permitirá al sistema enviar productos expirados. Utilice esta configuración con precaución.
{% endhint %}

Activando la opción "Permitir mover stock asignado" permitirá el movimiento directo de productos. Los pedidos de venta con estos productos se reasignarán automáticamente a la nueva ubicación del producto.

Activar la opción "Permitir cambio de atributos" permitirá reconfigurar el producto, esto SÓLO funcionará cuando un producto específico tenga inventario cero. Utilice esta opción con precaución.

{% hint style="danger" %}
Es fundamental que sus productos estén configurados correctamente desde el principio, una configuración precisa del producto es vital para tener un buen historial y una funcionalidad fluida en los procesos.
{% endhint %}

Dimensional Data

![P4 Warehouse Dimensional data setup](<../../.gitbook/assets/image (32).png>)

En la imagen de arriba, esto establece los valores predeterminados de cómo se capturan y muestran los datos dimensionales. En la imagen anterior, el peso se expresa en libras y la longitud en pies cúbicos.

Capturar Peso y Capturar Longitud son las unidades utilizadas por el usuario PDT para capturar el tamaño y peso total de la paleta, en la imagen de arriba el usuario PDT utilizará pulgadas para las dimensiones de la paleta y libras para el peso de la paleta.
