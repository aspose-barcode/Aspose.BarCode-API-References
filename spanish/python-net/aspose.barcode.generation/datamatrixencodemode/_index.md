---
title: "DataMatrixEncodeMode"
second_title: "Referencia de API de Aspose.Sildes para Python vía .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

Modo de codificación del codificador DataMatrix, por defecto Auto

## Members
| Nombre del miembro | Descripción |
| :- | :- |
| AUTO | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. <br/> Los caracteres Unicode se re‑codifican en la codificación especificada por ECIEncoding con la inserción de un identificador ECI.<br/> Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. |
| ASCII | Codifica un carácter alfanumérico o dos caracteres numéricos por byte |
| C40 | Utiliza la codificación C40. Codifica alfanuméricos en mayúsculas, minúsculas y caracteres especiales |
| TEXT | Utiliza la codificación Text. Codifica alfanuméricos en minúsculas, mayúsculas y caracteres especiales |
| EDIFACT | Utiliza la codificación EDIFACT. Usa seis bits por carácter, codifica dígitos, letras mayúsculas y muchos signos de puntuación, pero no admite letras minúsculas. |
| ANSIX12 | Utiliza la codificación ANSI X12. |
| EXTENDED |  |
| BASE256 | Codifica valores de 8 bits |
| BINARY | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. <br/> Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | En modo ECI, todo el mensaje se re‑codifica en la codificación especificada por ECIEncoding con la inserción de un identificador ECI.<br/> Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción.<br/> Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no ser compatibles con este modo. |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

