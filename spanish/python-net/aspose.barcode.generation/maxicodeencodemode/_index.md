---
title: "MaxiCodeEncodeMode"
second_title: "Referencia de API de Aspose.Sildes para Python vía .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/maxicodeencodemode/
---

## MaxiCodeEncodeMode enumeration

Modo de codificación para códigos de barras MaxiCode.

## Members
| Nombre del miembro | Descripción |
| :- | :- |
| AUTO | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. <br/> Los caracteres Unicode se re‑codifican en la codificación especificada por ECIEncoding con la inserción de un identificador ECI.<br/> Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. |
| EXTENDED |  |
| BINARY | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. <br/> Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | En modo ECI, todo el mensaje se re‑codifica en la codificación especificada por ECIEncoding con la inserción de un identificador ECI.<br/> Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción.<br/> Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no ser compatibles con este modo. |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

