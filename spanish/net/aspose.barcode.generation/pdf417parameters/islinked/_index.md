---
title: "Pdf417Parameters.IsLinked"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad Pdf417Parameters. Define los modos enlazados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica 906 907 912 913 914 915 modos UCC/EAN128 enlazados. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado, distinto de un EAN.UCC."
type: docs
weight: 70
url: /es/net/aspose.barcode.generation/pdf417parameters/islinked/
---
## Pdf417Parameters.IsLinked property

Define modos vinculados con códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC.

```csharp
public bool IsLinked { get; set; }
```

## Ejemplos

Estos ejemplos muestran cómo codificar los modos "Linked" UCC/EAN-128 en GS1MicroPdf417 y la bandera de enlace (918) en los códigos de barras MicroPdf417 y Pdf417.

```csharp
[C#]
//Codifica el modo enlazado GS1 912 con el campo de fecha AI 11 (fecha de producción) y AI 10 (número de lote).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica el modo enlazado GS1 912 con el campo de fecha AI 13 (fecha de empaquetado) y AI 21 (número de serie).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica el modo enlazado GS1 912 con el campo de fecha AI 15 (fecha de caducidad) y AI 10 (número de lote).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica el modo enlazado GS1 912 con el campo de fecha AI 17 (fecha de caducidad) y AI 21 (número de serie)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica el modo enlazado GS1 914 con AI 10 (número de lote)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica el modo enlazado GS1 915 con AI 21 (número de serie)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica los modos enlazados GS1 906, 907 con cualquier AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica MicroPdf417 NO EAN.UCC Modo enlazado 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica Pdf417 NO EAN.UCC Modo enlazado 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

### Ver también

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


