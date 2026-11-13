---
title: "HanXinEncodeMode"
second_title: "Referencia de API de Aspose.Sildes para Python vía .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Modo de codificación Han Xin Code. Se recomienda usar Auto con caracteres ASCII / chinos o Unicode para caracteres Unicode.

## Members
| Nombre del miembro | Descripción |
| :- | :- |
| AUTO | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. <br/>            Los caracteres Unicode se codifican usando la codificación GB18030 según la especificación del código de barras HanXin. |
| BINARY | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. <br/> Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | En modo ECI, todo el mensaje se re‑codifica en la codificación especificada por ECIEncoding con la inserción de un identificador ECI.<br/> Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción.<br/> Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no ser compatibles con este modo. |
| UNICODE | El modo Unicode define una forma de representar cualquier dato de texto haciendo referencia a la codificación/charset UTF8 en el código Han Xin. |
| URI | El modo URI indica que los datos representados en el código Han Xin son un Identificador Uniforme de Recursos (URI)<br/>            referencia a la RFC 3986. |
| EXTENDED | El modo Extended permite combinaciones de modos internos: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            El codetext puede construirse manualmente con prefijos y barras invertidas dobles, p.ej.: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" o usando el HanXinExtCodetextBuilder.<br/>            Si el codetext contiene un fragmento ECI, entonces solo los siguientes modos pueden estar en ese codetext después del fragmento ECI:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

