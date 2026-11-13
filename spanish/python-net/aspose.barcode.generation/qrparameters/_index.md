---
title: "QrParameters"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

Parámetros de QR.

El tipo QrParameters expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| eci_encoding | Identificadores de Interpretación de Canal Extendido. Se utiliza para proporcionar al lector de códigos de barras detalles<br/>            sobre las referencias usadas para codificar los datos en el símbolo.<br/>            La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas.<br/>            No compatible con MicroQR. |
| encode_mode | Tipo de simbología QR del modo de codificación de BarCode.<br/>            Valor predeterminado: QREncodeMode.Auto. |
| error_level | Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR.<br/>             De bajo a alto: LevelL, LevelM, LevelQ, LevelH. Ver QRErrorLevel. |
| version | Versión del código QR. De Version1 a Version40.<br/>            El valor predeterminado es QRVersion.Auto. |
| micro_qr_version | Versión del código MicroQR. De la versión M1 a la versión M4.<br/>            El valor predeterminado es MicroQRVersion.Auto. |
| rect_micro_qr_version | Versión del código RectMicroQR. De la versión R7x59 a la versión R17x139.<br/>            El valor predeterminado es RectMicroQRVersion.Auto. |
| aspect_ratio | Relación altura/ancho del módulo de código de barras 2D. |
| structured_append | Parámetros de anexado estructurado QR.<br/>            El modo de anexado estructurado no es compatible con los códigos de barras MicroQR y RectMicroQR. |
| encode_gs1_separator_in_byte_mode |  |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

