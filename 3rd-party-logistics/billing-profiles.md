---
description: Perfil de facturación de P4 Warehouse 3PL
---

# Perfiles de facturación 3PL

La creación de perfiles de facturación 3PL es una tarea extremadamente ardua en la mayoría de los sistemas de gestión de almacenes, sin embargo, en P4 Warehouse está basado en un asistente para simplificar el proceso.

Mediante la creación de diferentes perfiles de facturación, puede facturar al cliente 3PL correctamente la primera vez. Puede haber varios perfiles para la misma tarea, en el caso de que facture a los clientes 3PL de forma diferente en función del volumen o del tipo de productos.&#x20;

{% hint style="warning" %}
Todas las tarifas de almacenamiento se calculan por hora, hemos encontrado a través de nuestra experiencia e investigación que esto funciona mejor para el proveedor 3PL, así como para el cliente 3PL.
{% endhint %}

![Perfiles de facturación del almacén P4](<../.gitbook/assets/image (216).png>)

En la pantalla de arriba verá la lista de perfiles, también puede crear nuevos perfiles.&#x20;

Haga clic en el botón Nuevo para seguir con el ejemplo de abajo, para este ejemplo crearemos un perfil para picking. Cada unidad recolectada le costará al cliente 3PL .002 centavos, en la factura esto mostrará un total para el periodo de facturación.

![Perfil de facturación del almacén P4 Paso nº 1](<../.gitbook/assets/image (182).png>)

En la pantalla anterior, seleccione Cumplimiento

![Perfil de facturación del almacén P4 Paso nº 2](<../.gitbook/assets/image (191).png>)

En la pantalla anterior introduzca un nombre para el perfil, este será el SKU o a veces llamado código de facturación, a continuación introduzca la descripción, esta es la descripción que se mostrará en la factura, a continuación establezca la precedencia a 1 (en el caso de que tenga varios perfiles para la misma función de almacén asignada al mismo cliente puede cambiar la precedencia para dejar que el sistema decida cómo facturar por esta tarea), establezca el tipo de cargo en este caso establézcalo en Picking.

![Perfil de facturación del almacén P4 Paso nº 3](<../.gitbook/assets/image (123).png>)

En la pantalla de arriba elija cada, esto facturará al cliente 3PL .002 centavos por cada unidad recogida. Como muestra la imagen de arriba, hay varias opciones para elegir dependiendo del acuerdo que tenga con su cliente.

{% hint style="danger" %}
Si eligió peso o cubo como método de cálculo de facturación, es fundamental que configure las dimensiones correctamente en la pantalla de productos.
{% endhint %}

![P4 Perfil de facturación del almacén Paso nº 4](<../.gitbook/assets/image (127).png>)

En la pantalla anterior introduzca .002 para la tarifa, en el campo de cargos adicionales esto es para descuentos, impuestos o cargos varios.

![P4 Perfil de facturación del almacén Paso nº 5](<../.gitbook/assets/image (242).png>)

En la pantalla de arriba seleccione Acumulativo esto consolidará todo el picking a través de varias órdenes en una línea en la factura. Este código aparecerá ahora en la pantalla de configuración del cliente 3PL y le permitirá asignar el perfil al cliente.

{% hint style="info" %}
Hay un libro de Excel detallado que se envía por correo electrónico con la factura en PDF, este libro de Excel contiene información detallada para cada cargo de línea, no importa su selección en el paso # 5.&#x20;

Paso # 5 es para no tener miles de líneas en la factura real.
{% endhint %}

