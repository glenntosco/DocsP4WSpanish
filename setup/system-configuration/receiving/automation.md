---
description: P4 Warehouse Automatización de la recepción
---

# Automatización

#### En esta pantalla configurará los valores por defecto para el comportamiento del proceso de Recepción.<br>

Auto Cerrar Pedidos Recibidos (POs): esto cerrará automáticamente y enviará por correo electrónico el comprobante de recepción de los Pedidos de Compra que se reciban al 100%.&#x20;

{% hint style="warning" %}
Las órdenes de compra recibidas en exceso o en defecto no se cerrarán automáticamente y deberán ser cerradas manualmente por el despachador web.&#x20;

La sobre recepción está permitida en productos de tipo decimal como libras, kilogramos, metros, pies, litros y galones. Esto se debe al hecho de que este tipo de producto a menudo varía en peso y/o volumen.
{% endhint %}

Generar pedidos pendientes al cierre, en el caso de que la orden de compra no se haya recibido en su totalidad y exista un saldo en la orden, entonces al cierre se generará automáticamente el pedido pendiente por el saldo del producto. Esto se puede repetir varias veces hasta que el pedido se reciba en su totalidad. Esta funcionalidad se utiliza a menudo para órdenes de compra globales en las que una empresa encarga 12.000 unidades, pero sólo recibe 1.000 al mes. Si está conectado a través de una interfaz API al ERP de la empresa, cada recepción se cargará y reducirá del importe total pendiente.

Liberación automática de pedido pendiente mueve el pedido pendiente del estado Borrador al estado No recibido.

![](<../../../.gitbook/assets/image (46).png>)
