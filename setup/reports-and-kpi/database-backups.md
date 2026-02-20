---
description: P4 Warehouse
---

# Copias de seguridad de la base de datos

El Almacén P4 dispone de copias de seguridad de la base de datos cada 12 horas. Las copias de seguridad están en formato de archivo Microsoft bacpac. Bacpac es fácil de importar a cualquier Microsoft SQL versión 2008 y superiores.

{% hint style="info" %}
[Instrucciones de Microsoft bacpac](https://docs.microsoft.com/en-us/sql/relational-databases/data-tier-applications/import-a-bacpac-file-to-create-a-new-user-database?view=sql-server-ver15) (clic)
{% endhint %}

El primer paso es descargar los datos de P4 Warehouse.&#x20;

Paso 2: En SQL Manager (SSMS), haga clic con el botón derecho en Bases de datos y seleccione Importar aplicación de nivel de datos.&#x20;

Paso 3 seleccione el archivo bacpac que ha descargado, a continuación, dar a su base de datos un nombre.&#x20;

Paso 4 haga clic en Finalizar, (El proceso normalmente tardará de 1 a 3 minutos en completarse.)&#x20;

![P4 Warehouse Importación de bases de datos en Microsoft SQL Server](<../../.gitbook/assets/image (109).png>)

![P4 Warehouse Tablas de la base de datos](<../../.gitbook/assets/image (170).png>)



### Con esta base de datos puede conectarse a PowerBI, ejecutar consultas, generar informes y otras opciones.

Encontrará las copias de seguridad de la base de datos en Configuración/Sistema/Copias de seguridad de la base de datos

![P4 Warehouse Copias de seguridad de la base de datos](<../../.gitbook/assets/image (91).png>)

Al hacer clic en el botón de descarga, guardará la copia de seguridad en su ordenador local.



