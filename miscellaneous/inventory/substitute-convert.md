# Sustituto Convertir

P4 Almacén Sustituir Convertir<br>

Sustituto Convertir es una función única en P4 Warehouse. Esta función está diseñada para permitir la conversión limpia de un SKU a otro SKU diferente.<br>

Para este proceso utilizaremos el ejemplo de los Pavos. Muchas tiendas compran y luego venden pavos por peso, ya sea libras o kilos. Sin embargo, otras tiendas como Costo compran y luego venden pavos como unidades. En el Almacén P4 crearía dos SKU's uno para decimales (peso) y otro para unidades, en ambos SKU's introduciría la palabra pavo en el grupo sustituto. Luego con un PDT (dispositivo android) introducirías el proceso llamado Conversión de Sustituto.

![](<../../.gitbook/assets/image (272).png>)

Aquí escaneará una etiqueta para procesar la solicitud de sustitución.&#x20;

Ejemplo: Se solicita al usuario que convierta 500 pavos a libras, esto creará aproximadamente treinta y ocho pavos. Una vez completada la conversión, los pavos individuales estarán disponibles para la venta.

{% hint style="info" %}
En el Sistema de Almacén P4 esto se reflejará como una conversión de producto, dependiendo de su ERP lo más probable es que se refleje como un ajuste negativo / positivo.
{% endhint %}
