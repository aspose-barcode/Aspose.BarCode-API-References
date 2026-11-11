---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad BarcodeSettings. Devuelve solo los tipos de código de barras especificados explícitamente para el reconocimiento. Cuando está habilitado, los códigos de barras reconocidos de otros tipos compatibles o equivalentes se filtran. El valor predeterminado es false"
type: docs
weight: 50
url: /es/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Devuelve solo los tipos de códigos de barras especificados explícitamente para el reconocimiento. Cuando está habilitado, los códigos de barras reconocidos de otros tipos compatibles o equivalentes se filtran. Valor predeterminado es false.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Devuelve solo los tipos de código de barras especificados explícitamente para el reconocimiento. El valor predeterminado es false.

## Ejemplos

Este ejemplo muestra cómo restringir los resultados del reconocimiento solo a los tipos de código de barras solicitados

```csharp
[C#]
//generar código de barras EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//reconocer solo códigos de barras UPCA (sin resultados, porque la fuente es EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//reconocer tipos compatibles: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 se devolverá como equivalente UPCA)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### Ver también

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


