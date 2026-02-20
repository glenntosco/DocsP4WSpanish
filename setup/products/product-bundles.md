---
description: P4 Warehouse Paquetes de productos
---

# Paquetes de productos

P4 Warehouse permite crear paquetes de productos. Un ejemplo de paquete de productos sería una promoción de ventas de «compre una impresora térmica y llévese 5 rollos de cintas incluidos». En el proceso de pedido, el vendedor simplemente introduce el SKU de la promoción en el sistema de pedidos. En este punto, el SGA entiende que necesita seleccionar varios productos y cantidades para completar el pedido. Esto reduce la posibilidad de que el vendedor cometa un error de tecleo.

{% hint style="info" %}
Los subcomponentes deben crearse antes de crear el paquete de productos.
{% endhint %}

En la imagen anterior, P4 Warehouse enviará un recolector a recoger 1 impresora y cinco (5) rollos de cinta de cera para completar el pedido. Las dos (2) líneas podrían introducirse manualmente en el pedido de venta, pero la función de paquete de productos reduce la posibilidad de error. Si utiliza SAP B1, esto se denomina kit de ventas.

{% hint style="success" %}
Recuerde que un paquete de productos y la producción son dos (2) procesos diferentes.

La producción es cuando convierte uno (1) o más productos en una SKU completamente nueva.
{% endhint %}

