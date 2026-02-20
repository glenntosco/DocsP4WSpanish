# Crear un nuevo proveedor

## Punto final

El punto final de la API «CreateOrUpdate» se utiliza para crear un nuevo proveedor.

<mark style="color:green;">`POST`</mark> `https://{tenant_name}.p4warehouse.com/api/VendorApi/CreateOrUpdate`

#### Encabezados

| Nombre                                   | Tipo   | Descripción           |
| ---------------------------------------- | ------ | --------------------- |
| ApiKey<mark style="color:red;">\*</mark> | String | Llave API del sistema |

#### Cuerpo de la solicitud

| Nombre                                         | Tipo   | Descripción                                 |
| ---------------------------------------------- | ------ | ------------------------------------------- |
| "VendorCode"<mark style="color:red;">\*</mark> | String | Número de proveedor asignado por el usuario |

{% tabs %}
{% tab title="200: OK Vendor is created" %}
```json
{
    "$id": "1",
    "VendorCode": "123456",
    "PurchaseOrders": [],
    "ClientId": null,
    "Client": null,
    "CompanyName": "Test",
    "ProductExpiryAllowance": null,
    "Description": "Demo",
    "Logo": null,
    "ReceivingSlipDisclaimer": null,
    "IsGeneratePoBackOrder": null,
    "ContactPerson": null,
    "Email": null,
    "Phone": null,
    "Info1": null,
    "Info2": null,
    "Info3": null,
    "Info4": null,
    "Info5": null,
    "Info6": null,
    "Info7": null,
    "Info8": null,
    "Info9": null,
    "Info10": null,
    "IsEmailReceivingSlips": false,
    "Address1": null,
    "Address2": null,
    "City": null,
    "StateProvince": null,
    "ZipPostalCode": null,
    "Country": null,
    "AddressHash": "",
    "Id": "f7476132-b8e2-4ccf-88fc-3c1e82f52414",
    "DateCreated": "2023-08-15T20:37:08.7079073+00:00",
    "TypeName": "Pro4Soft.TenantData.Entities.Business.Purchasing.Vendor",
    "TypeNameShort": "Vendor"
}
```
{% endtab %}

{% tab title="406: Not Acceptable Missing field" %}
```
[VendorCode]: The VendorCode field is required.
```
{% endtab %}

{% tab title="401: Unauthorized Incorrect API key" %}

{% endtab %}

{% tab title="404: Not Found Incorrect URL" %}

{% endtab %}
{% endtabs %}

A los vendedores recién creados se les asigna un número de «Id». Utilice este número para actualizar/editar los vendedores seleccionados.

## Ejemplo de JSON

A continuación se muestra un ejemplo de carga útil JSON para crear un nuevo proveedor con número de proveedor, descripción, nombre de la empresa, dirección e información adicional.

```postman_json
{
   "VendorCode":"1234",
   "Description":"API Demo",
   "CompanyName":"A&B",
   "Address1": "4310 N Whipple",
    "Address2": "5",
    "City": "Chicago",
    "StateProvince": "IL",
    "ZipPostalCode": "60618",
    "Country":"USA",
    "Info1":"Info1",
    "Info2":"Info2"
}
```
