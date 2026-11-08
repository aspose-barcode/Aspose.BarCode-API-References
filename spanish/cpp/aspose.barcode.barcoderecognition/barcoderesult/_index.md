---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult clase"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult clase. Almacena datos de código de barras reconocidos como tipo SingleDecodeType, **System::String** codetext, región BarCodeRegionParameters y otros parámetros en C++."
type: docs
weight: 700
url: /es/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Almacena datos de código de barras reconocidos como tipo [SingleDecodeType](../singledecodetype/), **System::String** codetext, región [BarCodeRegionParameters](../barcoderegionparameters/) y otros parámetros

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Crea una copia de la clase [BarCodeResult](./). |
| [Clone](./clone/)() override | Crea una copia de la clase [BarCodeResult](./). |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Devuelve un valor que indica si esta instancia es igual a un valor [BarCodeResult](./) especificado. |
| [get_CodeBytes](./get_codebytes/)() const | Obtiene los bytes del código codificado |
| [get_CodeText](./get_codetext/)() const | Obtiene el texto del código |
| [get_CodeType](./get_codetype/)() const | Obtiene el tipo de código de barras |
| [get_CodeTypeName](./get_codetypename/)() | Obtiene el nombre del tipo de código de barras |
| [get_Confidence](./get_confidence/)() const | Obtiene el nivel de confianza del reconocimiento del código de barras reconocido |
| [get_Extended](./get_extended/)() const | Obtiene los parámetros extendidos del código de barras reconocido |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | Obtiene los resultados de la evaluación de calidad de símbolos ISO/IEC para el código de barras reconocido. |
| [get_ReadingQuality](./get_readingquality/)() const | Obtiene la calidad de lectura. Funciona para códigos de barras 1D y postales. |
| [get_Region](./get_region/)() const | Obtiene la región del código de barras |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Obtiene el texto del código con codificación. |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [BarCodeResult](./). |
## Observaciones


Este ejemplo muestra cómo obtener [BarCodeResult](./).
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
