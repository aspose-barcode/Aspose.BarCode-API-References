---
title: "Enumeración Pdf417EncodeMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Enumeración Aspose.BarCode.Generation.Pdf417EncodeMode. Modo de codificación del código de barras Pdf417"
type: docs
weight: 1540
url: /es/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Modo de codificación de código de barras Pdf417

```csharp
public enum Pdf417EncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se re‑codifican en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. |
| Binary | `1` | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | `2` | En modo ECI, todo el mensaje se re‑codifica en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no soportar este modo. |
| Extended | `3` | Modo extendido que admite varios modos ECI. |

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


