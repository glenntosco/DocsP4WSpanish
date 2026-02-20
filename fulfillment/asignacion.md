---
description: P4 Warehouse
---

# Asignación

Si el ticket se encuentra en estado borrador, deberá ser liberado a piso para iniciar los procesos.

{% hint style="info" %}
Si se publica, la Orden pasa de borrador (editable) a documento activo.
{% endhint %}

{% hint style="warning" %}
En el caso de que su instancia de P4 Almacén esté conectada mediante integración con su ERP, los pedidos no mostrarán el estado borrador y no podrán editarse desde el SGA, las ediciones deberán realizarse desde el ERP.
{% endhint %}

![P4 Warehouse Pantalla de pedido de cliente](<../.gitbook/assets/Pick ticket screen-01.png>)

La liberación a planta puede realizarse por pedido individual o en grupos.

{% hint style="info" %}
Se puede activar o desactivar el procesamiento automático de las distintas fases de cumplimiento en Configuración->Sistema->Configuración->Empresa->Cumplimiento->Automatización.
{% endhint %}

![](<../.gitbook/assets/image (192).png>)

El estado del ticket de picking es ahora no asignado y los nuevos procesos están disponibles:

![](<../.gitbook/assets/image (51).png>)

La sección Pick ticket Line también se actualiza con más información para su revisión:

![](<../.gitbook/assets/image (160).png>)

Si toda la información es correcta, el usuario está listo para asignar utilizando las reglas del sistema y las selecciones del usuario pulsando el botón Asignar. Como se puede ver en las dos imágenes siguientes esta pantalla (la mayoría de las pantallas en P4 Warehouse) es dinámica, lo que significa que la pantalla sólo muestra las opciones que están disponibles para este pedido o grupo de pedidos. La primera foto de abajo no tiene artículos con Números de Lote o Caducidad por lo tanto la pantalla no muestra las opciones que se ven en la segunda foto de abajo.

{% hint style="success" %}
P4 Warehouse tiene el algoritmo más potente del sector. El proceso de asignación consiste en que el sistema escanea y decide lo que debe recogerse basándose en las reglas del sistema y los ajustes de la pantalla de asignación.
{% endhint %}

![P4 Warehouse Pantalla de asignación de productos por paquetes](<../.gitbook/assets/image (244).png>)

![P4 Warehouse Pantalla de asignación de productos con caducidad y lote controlado](<../.gitbook/assets/image (264).png>)

El Ticket de Recogida muestra ahora el estado «Listo para Recoger» y el porcentaje de Asignación junto con más procesos disponibles.

Los siguientes botones de Proceso están habilitados:

* Desasignar -
* Imprimir códigos de barras de productos -
* Ondular -
* Encartonar -
* Suspender -
* Factura proforma -

![](<../.gitbook/assets/image (220).png>)

La sección Líneas de la orden de venta muestra ahora información sobre la asignación:

![P4 Warehouse Pantalla de pedidos asignados](<../.gitbook/assets/image (156).png>)

{% hint style="info" %}
Con P4 Warehouse puede desasignar 1 línea en el pedido y o puede reducir la cantidad en mitad del picking.
{% endhint %}

Imprimir códigos de barras de productos:

{% tabs %}
{% tab title="1) seleccionar elementos para imprimir" %}
![](<../.gitbook/assets/image (287).png>)
{% endtab %}

{% tab title="2) seleccione impresora y cantidad" %}
![](<../.gitbook/assets/image (131).png>)
{% endtab %}
{% endtabs %}

Cartonizado de Pedidos basado en reglas preestablecidas del sistema o anulación manual:

![](<../.gitbook/assets/image (263).png>)

Suspender: pone los pedidos en espera. Una vez confirmado, el estado del billete de recogida cambia a Suspendido y será necesario desbloquearlo para continuar.

![](<../.gitbook/assets/image (140).png>)

La factura proforma se abre en una nueva pestaña del navegador y permite descargarla.

{% file src="../.gitbook/assets/Proforma Invoice sample.pdf" %}
Ejemplo de factura proforma
{% endfile %}

Onda:

![](<../.gitbook/assets/image (172).png>)

El ticket de picking está ahora en estado Ondulado y la sección Totes es ahora visible:

![](<../.gitbook/assets/image (181).png>)

![](<../.gitbook/assets/image (204).png>)

Se puede acceder a la información de los contenedores haciendo clic en el hipervínculo SSCC-18. A medida que se procesan los pedidos, se rellena la sección de contenido y se pueden imprimir las etiquetas de contenido.

* Las etiquetas Tote pueden reimprimirse con el botón Etiqueta Tote
* Las etiquetas de contenido pueden imprimirse con el botón de etiquetas de contenido

![](<../.gitbook/assets/image (142).png>)



