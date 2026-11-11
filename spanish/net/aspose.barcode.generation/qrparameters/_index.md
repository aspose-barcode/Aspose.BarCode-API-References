---
title: "Clase QrParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.QrParameters. Parámetros QR"
type: docs
weight: 1650
url: /es/net/aspose.barcode.generation/qrparameters/
---
## QrParameters class

Parámetros de QR.

```csharp
public class QrParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/qrparameters/aspectratio/) { get; set; } | Relación altura/ancho del módulo de código de barras 2D. |
| [ECIEncoding](../../aspose.barcode.generation/qrparameters/eciencoding/) { get; set; } | Identificadores de Interpretación de Canal Extendida. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. No compatible con MicroQR. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/) { get; set; } | Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para códigos QR y RectMicroQR. |
| [EncodeMode](../../aspose.barcode.generation/qrparameters/encodemode/) { get; set; } | Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.generation/qrparameters/errorlevel/) { get; set; } | Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. Ver QERrrorLevel. |
| [MicroQRVersion](../../aspose.barcode.generation/qrparameters/microqrversion/) { get; set; } | Versión del código MicroQR. Desde la versión M1 hasta la versión M4. Valor predeterminado es MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.generation/qrparameters/rectmicroqrversion/) { get; set; } | Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. Valor predeterminado es RectMicroQRVersion.Auto. |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | Parámetros de anexado estructurado QR. El modo de anexado estructurado no es compatible con los códigos de barras MicroQR y RectMicroQR. |
| [Version](../../aspose.barcode.generation/qrparameters/version/) { get; set; } | Versión del código QR. Desde Version1 hasta Version40. El valor predeterminado es QRVersion.Auto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | Devuelve una representación de cadena legible por humanos de este `QrParameters`. |

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


