---
description: P4 Warehouse Creación de KPI
---

# Creación de KPI

El primer paso en la creación de KPI es decidir qué datos va a reportar, a continuación, crear la consulta SQL para extraer los datos de la base de datos.

![P4 Warehouse Lista de widgets](<../../.gitbook/assets/image (260).png>)

En esta pantalla puede editar un informe existente o crear uno nuevo.

{% hint style="info" %}
Para crear informes necesitará conocer TSQL, la mejor opción es descargar la copia de seguridad de la base de datos para crear su sentencia SQL.
{% endhint %}

Haciendo clic en el nombre de un Widget existente, podrá editar la sentencia SQL de los informes.

![P4 Warehouse Informes SQL Querry](<../../.gitbook/assets/image (162).png>)

Una vez que tenga su Consulta SQL funcionando, necesitará añadir un Gráfico.

![](<../../.gitbook/assets/image (214).png>)

* En la configuración del gráfico, establezca el nombre que desee.
* Para Tipo de Gráfico seleccione el tipo de gráfico que necesita, Área, Barra, Columna, Línea o Circular.
* Ponga el nombre exacto de su columna en el Campo Argumento y en el Campo Valor.
* Ponga el nombre de su Columna de Series.

{% hint style="danger" %}
Los KPI son un tema en profundidad; le recomendamos que hable con su socio del almacén P4 para obtener más detalles.
{% endhint %}

![](<../../.gitbook/assets/image (61).png>)



