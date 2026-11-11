---
title: "QrParametersUI.EncodeGS1SeparatorInByteMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad QrParametersUI. Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para códigos de barras QR y RectMicroQR"
type: docs
weight: 30
url: /es/net/aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/
---
## QrParametersUI.EncodeGS1SeparatorInByteMode property

Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para códigos QR y RectMicroQR.

Si es falso, los separadores GS1 pueden codificarse como '%' en modo Alfanumérico según la especificación QR.

Si es verdadero, los separadores de grupo GS1 se codifican en modo Byte como el carácter 0x1D, y los caracteres '%' también se codifican en modo Byte para preservarlos como datos.

Esta opción puede mejorar la compatibilidad con decodificadores que esperan separadores de grupo GS1 a nivel de byte y evita que los caracteres de datos '%' se interpreten como separadores GS1.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Ver también

* class [QrParametersUI](../)
* namespace [Aspose.BarCode.Windows.Forms](../../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../../)


