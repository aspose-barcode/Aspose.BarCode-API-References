---
title: "método"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Devuelve solo los tipos de códigos de barras especificados explícitamente para el reconocimiento. Cuando está habilitado, los códigos de barras reconocidos de otros tipos compatibles o equivalentes se filtran. El valor predeterminado es falso en C++."
type: docs
weight: 500
url: /es/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


Devuelve solo los tipos de código de barras especificados explícitamente para el reconocimiento. Cuando está habilitado, los códigos de barras reconocidos de otros tipos compatibles o equivalentes se filtran. El valor predeterminado es false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## Observaciones


Este ejemplo muestra cómo restringir los resultados del reconocimiento solo a los tipos de códigos de barras solicitados
```cpp
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


Devuelve solo los tipos de códigos de barras especificados explícitamente para el reconocimiento. El valor predeterminado es falso.
## Ver también

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
