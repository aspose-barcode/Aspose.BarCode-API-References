---
title: "Clase QrParametersUI"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Windows.Forms.QrParametersUI. Contenedor UI para la clase QrParameters"
type: docs
weight: 1870
url: /es/net/aspose.barcode.windows.forms/qrparametersui/
---
## QrParametersUI class

Contenedor UI para la clase [`QrParameters`](../../aspose.barcode.generation/qrparameters/).

```csharp
public class QrParametersUI
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/qrparametersui/aspectratio/) { get; set; } | Relación altura/ancho del módulo de código de barras 2D. |
| [ECIEncoding](../../aspose.barcode.windows.forms/qrparametersui/eciencoding/) { get; set; } | Identificadores de Interpretación de Canal Extendida. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. No compatible con MicroQR. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/) { get; set; } | Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para códigos QR y RectMicroQR. |
| [EncodeMode](../../aspose.barcode.windows.forms/qrparametersui/encodemode/) { get; set; } | Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/qrparametersui/errorlevel/) { get; set; } | Nivel de corrección de errores Reed-Solomon para códigos QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. ver QRErrorLevel. |
| [MicroQrVersion](../../aspose.barcode.windows.forms/qrparametersui/microqrversion/) { get; set; } | Versión del código MicroQR. Desde la versión M1 hasta la versión M4. Valor predeterminado es MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.windows.forms/qrparametersui/rectmicroqrversion/) { get; set; } | Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. Valor predeterminado es RectMicroQRVersion.Auto. |
| [Version](../../aspose.barcode.windows.forms/qrparametersui/version/) { get; set; } | Versión del código QR. Desde Version1 hasta Version40 para códigos QR y desde M1 hasta M4 para MicroQr. Valor predeterminado es QRVersion.Auto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/qrparametersui/tostring/)() | Devuelve una representación en cadena legible por humanos de este [`QrParameters`](../../aspose.barcode.generation/qrparameters/). |

### Ver también

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


