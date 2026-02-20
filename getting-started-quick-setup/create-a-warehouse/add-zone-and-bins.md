---
description: P4 Warehouse Añadir zona
---

# Añadir zona

### Añadir zona

En la pantalla de edición del almacén, haga clic en el botón nuevo de la sección Zonas de la pantalla.

{% hint style="info" %}
Para una información más detallada de las [Zonas](add-zone-and-bins.md#add-zone).
{% endhint %}

![](<../../.gitbook/assets/add zone.gif>)

Después de hacer clic en nuevo obtendrá la pantalla en la imagen de abajo, complete el código de zona, la máscara, la descripción y el tipo de manejo del producto y luego haga clic en enviar.

{% hint style="info" %}
Los tipos de manipulación de productos son Por producto o Por LPN. Si no utiliza LPN, no seleccione LPN como tipo de manipulación.
{% endhint %}

Nueva pantalla de zona

![](<../../.gitbook/assets/new zone.gif>)

Ahora verá su nueva zona en la lista de zonas debajo de la pantalla de configuración del almacén.

![](<../../.gitbook/assets/edit zone 2.gif>)

Abra su nueva Zona haciendo clic en el enlace de la columna Código. Aquí configurará los detalles de la Zona.

![P4 Warehouse Zone Configuration](<../../.gitbook/assets/image (86).png>)

En la pantalla de ajustes de zona, encontrará varios ajustes detallados para el comportamiento de la zona.

{% hint style="info" %}
Si pone una zona en cuarentena, no podrá asignar el inventario de esta zona.
{% endhint %}

La máscara de zona es una función especialmente importante, que gestiona mejor el equipo de implantación. La máscara de zona le ayudará a crear cientos o miles de ubicaciones de contenedores. Estructura de la Máscara: Los segmentos de la máscara están dentro de { } cada segmento está numerado. A continuación se muestran un par de ejemplos con los resultados.

* 01-A-{0:00}-(1:0} = 01-A-12-A&#x20;
  * Este formato es pasillo, zona, contenedor, nivel
* A-{0:00}-{1:0} = A-03-A
  * Este formato es Zona, Contenedor, Nivel

El enmascaramiento de zonas depende de la distribución física de su almacén, utilice esta función con cuidado ya que puede crear accidentalmente cientos de miles de ubicaciones de ubicaciones.

> No es obligatorio incluir la Zona en el formato de la etiqueta, la zona puede incluirse como un campo separado en la etiqueta del contenedor.

La configuración de la Zona para ubicaciones de producto dedicadas es para casos de uso excepcionales y no se recomienda para la mayoría de almacenes o centros de distribución. La configuración de la Zona para un contenedor por producto es para casos de uso excepcionales y no se recomienda para la mayoría de almacenes o centros de distribución.

{% hint style="success" %}
Es importante configurar la impresora de tickets de picking en cada zona, esto es vital si planea utilizar el picking por Zonas. Las dimensiones de las Zonas/Cubos son vitales para varios propósitos.
{% endhint %}

Cuando diseñe sus zonas, tenga en cuenta las zonas de preparación, las zonas de muelles transversales, las zonas de recepción, las zonas refrigeradas, las zonas de congelados, las zonas de materiales peligrosos, etc.
