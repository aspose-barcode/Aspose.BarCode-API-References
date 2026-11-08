---
title: "método"
linktitle: "set_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar el método set_EncodeGS1SeparatorInByteMode de la clase Aspose::BarCode::Generation::QrParameters en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.barcode.generation/qrparameters/set_encodegs1separatorinbytemode/
---
## QrParameters::set_EncodeGS1SeparatorInByteMode method




```cpp
void Aspose::BarCode::Generation::QrParameters::set_EncodeGS1SeparatorInByteMode(bool value)
```

## Observaciones


Establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para los códigos de barras QR y RectMicroQR.

Si es false, los separadores GS1 pueden codificarse como '' en modo Alfanumérico según la especificación QR.

Si es true, los separadores de grupo GS1 se codifican en modo Byte como el carácter 0x1D, y los caracteres '' también se codifican en modo Byte para preservarlos como datos.

Esta opción puede mejorar la compatibilidad con decodificadores que esperan separadores de grupo GS1 a nivel de byte y evita que los caracteres de datos '' se interpreten como separadores GS1.
## Ver también

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
