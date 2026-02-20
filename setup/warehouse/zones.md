---
description: P4 Warehouse Configuración de zona
---

# Zonas

### Añadir zona

Las zonas son una característica clave en P4 Warehouse, las zonas permiten un nivel de control que no se incluye comúnmente en los sistemas de gestión de almacenes. Como la configuración mostrará, hay opciones muy potentes en las pantallas de configuración de zona.

En la pantalla de edición del almacén, haga clic en  :new:  en la sección Zonas de la pantalla.

{% hint style="info" %}
Discuta la configuración de zonas con su socio del almacén P4, siempre es mejor tener un plan y no crear zonas al azar.
{% endhint %}

![](<../../.gitbook/assets/add zone.gif>)

Después de hacer clic en nuevo, aparecerá la siguiente pantalla: complete el código de zona, la máscara, la descripción y el tipo de manipulación del producto y, a continuación, haga clic en enviar.

{% hint style="info" %}
Los tipos de manejo de productos son Por producto o Por LPN. Si no utiliza LPN, no seleccione LPN como tipo de manipulación.
{% endhint %}

### Nueva pantalla de zona

![P4 warehouse Nueva pantalla de zona](<../../.gitbook/assets/new zone.gif>)

{% hint style="info" %}
Las zonas se pueden elegir; usted elige, sin embargo no se pueden duplicar. Si está configurando varios almacenes tenga en cuenta que no puede duplicar las zonas.
{% endhint %}

Ahora verá su nueva zona en la lista de zonas debajo de la pantalla de configuración del almacén.

![](<../../.gitbook/assets/edit zone 2.gif>)

Abra su nueva Zona haciendo clic en el enlace de la columna Código. Aquí configurará los detalles de la Zona.

![P4 Warehouse Configuración de zona](<../../.gitbook/assets/image (136).png>)

Configure las dimensiones de sus ubicaciones, esto permitirá que el sistema P4 Warehouse le diga dónde encajará el producto. Sin esta información, P4 Warehouse no sabrá qué producto encaja en qué tamaño de ubicación de contenedor.

En la pantalla de ajustes de zona, encontrará varios ajustes detallados para el comportamiento de la zona.

{% hint style="info" %}
Configurar una zona en cuarentena le impedirá asignar el inventario en esta zona así como este inventario no se mostrará en el informe de disponibilidad de inventario.
{% endhint %}

La máscara de zona es una característica especialmente importante, esto es mejor gestionado por el equipo de implementación. En resumen, la máscara de zona le ayudará a crear cientos o miles de ubicaciones de contenedores.

Estructura de la máscara: Los segmentos de la máscara están dentro de { } cada segmento está numerado. A continuación se muestran un par de ejemplos con los resultados.

* 01-A-{0:00}-(1:0} = 01-A-12-A&#x20;
  * Este formato es pasillo, zona, contenedor, nivel
* A-{0:00}-{1:0} = A-03-A
  * Este formato es Zona, Contenedor, Nivel

El enmascaramiento de zonas depende de la distribución física de su almacén, utilice esta función con cuidado ya que puede crear accidentalmente cientos de miles de ubicaciones de ubicaciones.

{% hint style="info" %}
> No es obligatorio incluir la Zona en el formato de la etiqueta, la zona puede incluirse como un campo separado en la etiqueta del contenedor.
{% endhint %}

{% hint style="info" %}
La configuración de la Zona para ubicaciones de producto dedicadas es para casos de uso excepcionales y no se recomienda para la mayoría de almacenes o centros de distribución.
{% endhint %}

{% hint style="info" %}
Ajustar la Zona a un contenedor por producto es para casos de uso excepcional y no se recomienda para la mayoría de almacenes o centros de distribución.
{% endhint %}

Cuando diseñe sus zonas, tenga en cuenta las zonas de preparación, las zonas de muelles transversales, las zonas de recepción, las zonas refrigeradas, las zonas de congelados, las zonas de materiales peligrosos, etc.

### Zonas

Existen cuatro tipos de Zonas: Zona de Producto, Zona LPN, Zona de Cuarentena y Zona de Producción.

La Zona de Producto es para el almacenamiento y movimiento de unidades y cajas, normalmente se denomina zona de picking.

La zona LPN es para productos en cantidad de palets, a menudo denominada zona Overstock.

La Zona de Cuarentena es para productos rotos, dañados o caducados, este inventario no aparece como disponible para recoger para pedidos de venta.

Zona de Producción es para la fabricación de productos, una zona de producción típicamente es una serie de Líneas de Producción. Las materias primas se entregan en la zona de producción, los productos acabados se retiran de la zona de producción.

### Permitir varios productos por ubicación

Este ajuste suele estar desactivado para la mayoría de las ubicaciones, ya que colocar varios productos en una misma ubicación puede ralentizar los procesos del almacén.

