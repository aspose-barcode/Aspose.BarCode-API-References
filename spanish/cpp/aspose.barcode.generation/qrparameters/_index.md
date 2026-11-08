---
title: "Clase Aspose::BarCode::Generation::QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::Generation::QrParameters. Parámetros QR en C++."
type: docs
weight: 4400
url: /es/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


Parámetros QR.

```cpp
class QrParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjuntos de caracteres conocidas. No compatible con MicroQR. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | Tipo de simbología QR del modo de codificación de [BarCode](../../aspose.barcode/). Valor predeterminado: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | Nivel de corrección de errores Reed‑Solomon para los códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. Ver QRErrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Versión del código MicroQR. Desde la versión M1 hasta la versión M4. El valor predeterminado es [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. El valor predeterminado es [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | Parámetros de anexado estructurado QR. El modo de anexado estructurado no es compatible con los códigos de barras MicroQR y RectMicroQR. |
| [get_Version](./get_version/)() const | Versión del código QR. Desde Version1 hasta Version40. El valor predeterminado es [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjuntos de caracteres conocidas. No compatible con MicroQR. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | Tipo de simbología QR del modo de codificación de [BarCode](../../aspose.barcode/). Valor predeterminado: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | Nivel de corrección de errores Reed‑Solomon para los códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. Ver QRErrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | Versión del código MicroQR. Desde la versión M1 hasta la versión M4. El valor predeterminado es [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. El valor predeterminado es [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | Parámetros de anexado estructurado QR. El modo de anexado estructurado no es compatible con los códigos de barras MicroQR y RectMicroQR. |
| [set_Version](./set_version/)(QRVersion) | Versión del código QR. Desde Version1 hasta Version40. El valor predeterminado es [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [QrParameters](./). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
