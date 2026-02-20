# Recuperar una lista de proveedores

## OData

P4W utiliza OData cuando consulta la base de datos a través de llamadas API. El siguiente ejemplo recupera los 20 primeros proveedores, incluidos los clientes asignados, si procede.



<mark style="color:blue;">`GET`</mark> `https://{tenant_name}.p4warehouse.com/odata/Vendor`

### Parámetros de consulta

| Nombre     | Tipo    | Descripción                   |
| ---------- | ------- | ----------------------------- |
| $expand\*  | String  | Base de clientes              |
| $orderby\* | String  | Código de proveedor           |
| $top\*     | Integer | Number of vendors to retrieve |

Utilice la sintaxis OData (https://www.odata.org/documentation/) para personalizar las consultas a través de llamadas a la API.



### Ejemplo de consulta OData

```json
https://{tenant_name}.p4warehouse.com/odata/Vendor
?$expand=Client($select=Id,Name)&$orderby=VendorCode&$top=20&$count=true
```
