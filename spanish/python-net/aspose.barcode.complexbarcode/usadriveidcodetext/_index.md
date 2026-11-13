---
title: "USADriveIdCodetext"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Clase para codificar y decodificar el texto incrustado en el código PDF417 de la Licencia de Conducir de EE. UU.

El tipo USADriveIdCodetext expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| USADriveIdCodetext() | Inicializa una nueva instancia de la clase USADriveIdCodetext |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| issuer_identification_number | Este número identifica de forma única <br/>            la jurisdicción emisora y puede obtenerse contactando a la ISO<br/>            Autoridad emisora (AAMVA).  El IIN completo de 6 dígitos debe codificarse. |
| aamva_version_number | Número de versión AAMVA 00-99 |
| jurisdiction_version_number | Número de versión de la jurisdicción 00-99 |
| number_of_entries | Número 00-99 de subarchivos |
| subfile_designator | Contiene información sobre los siguientes subarchivos, tipos, desplazamientos y longitudes. <br/>            Importante: si solo se establece el tipo, el desplazamiento y la longitud se establecerán automáticamente. |
| mandatory_elements | Elementos obligatorios (campos) de la tarjeta |
| optional_elements | Elementos opcionales (campos) de la tarjeta |
| jurisdiction_specific_subfile | Campos específicos de la jurisdicción |
## Métodos
| Nombre | Descripción |
| :- | :- |
| get_constructed_codetext() | Construir codetext a partir de los datos de USA DL |
| init_from_string(constructed_codetext) | Inicializar el objeto USA DL a partir del codetext |
| get_barcode_type() | Devuelve el tipo de código de barras de USA DL (Pdf417) |
| save_to_xml(stream) | Guarda en XML |

### Ver también

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

