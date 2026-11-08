---
title: "método"
linktitle: "set_IsLinked"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Define modos vinculados con códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC en C++."
type: docs
weight: 4200
url: /es/cpp/aspose.barcode.generation/pdf417parameters/set_islinked/
---
## Pdf417Parameters::set_IsLinked method


Define modos vinculados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos UCC/EAN-128 “Linked” 906, 907, 912, 913, 914, 915. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado, distinto de un EAN.UCC.

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsLinked(bool value)
```

## Observaciones


Estos ejemplos muestran cómo codificar los modos "Linked" UCC/EAN-128 en GS1MicroPdf417 y la bandera de enlace (918) en códigos de barras MicroPdf417 y Pdf417.
```cpp
[C#]
//Codifica el modo GS1 Linked 912 con el campo de fecha AI 11 (fecha de producción) y AI 10 (número de lote).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica el modo GS1 Linked 912 con el campo de fecha AI 13 (fecha de empaquetado) y AI 21 (número de serie).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica el modo GS1 Linked 912 con el campo de fecha AI 15 (fecha de venta) y AI 10 (número de lote).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica el modo GS1 Linked 912 con el campo de fecha AI 17 (fecha de caducidad) y AI 21 (número de serie).
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

//Codifica el modo enlazado MicroPdf417 NON EAN.UCC 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codifica el modo enlazado Pdf417 NON EAN.UCC 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

## Ver también

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
