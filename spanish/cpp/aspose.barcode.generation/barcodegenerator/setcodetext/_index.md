---
title: "método"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Establece el codetext como una secuencia de bytes en C++."
type: docs
weight: 700
url: /es/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


Establece el texto del código como una secuencia de bytes.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | Bytes del codetext |

## Ver también

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codeText | System::String | Cadena CodeText |
| codificación | System::SharedPtr\<System::Text::Encoding\> | Codificación aplicada |
## Observaciones


Codifica el **codeText** Unicode en una secuencia de bytes usando la **encoding** especificada. UTF-8 es la codificación más utilizada. Si la codificación lo soporta, la función inserta automáticamente una [marca de orden de bytes (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Esta función está destinada solo para su uso con códigos de barras 2D (p. ej., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Permite la codificación manual de texto Unicode usando codificaciones nacionales o especiales; sin embargo, este método se considera obsoleto en aplicaciones modernas. Para casos de uso actuales, se recomienda la codificación [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) para datos Unicode.

El uso de esta función con códigos de barras 1D, códigos de barras compatibles con GS1 (incluidos los 2D) o códigos de barras HIBC (incluidos los 2D) no está soportado por las normas de códigos de barras correspondientes y puede producir resultados impredecibles.


Este ejemplo muestra cómo usar **SetCodeText** para establecer texto codificado en Unicode para códigos de barras 2D usando diferentes codificaciones:


```cpp
[C#]
//Codificar texto QR usando UTF-8 con BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Codificar texto DataMatrix usando Shift-JIS (codificación japonesa)
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Ver también

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codeText | System::String | Cadena CodeText |
| codificación | System::SharedPtr\<System::Text::Encoding\> | Codificación aplicada |
| insertBOM | bool | Indica si se debe insertar una marca de orden de bytes (BOM) cuando la codificación especificada lo soporta (p. ej., UTF-8, UTF-16, UTF-32). Si se establece en **true**, se agrega el BOM; si se establece en **false**, el BOM se omite incluso si la codificación normalmente lo utiliza. |
## Observaciones


Codifica el **codeText** Unicode en una secuencia de bytes usando la **encoding** especificada. UTF-8 es la codificación más utilizada. Si la codificación lo soporta y **insertBOM** está establecido en **true**, la función incluye una [marca de orden de bytes (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Esta función está destinada solo para su uso con códigos de barras 2D (p. ej., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Permite la codificación manual de texto Unicode usando codificaciones nacionales o especiales; sin embargo, este método se considera obsoleto en aplicaciones modernas. Para casos de uso actuales, se recomienda la codificación [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) para datos Unicode.

El uso de esta función con códigos de barras 1D, códigos de barras compatibles con GS1 (incluidos los 2D) o códigos de barras HIBC (incluidos los 2D) no está soportado por las normas de códigos de barras correspondientes y puede producir resultados impredecibles.


Este ejemplo muestra cómo usar **SetCodeText** con o sin un BOM para códigos de barras 2D.


```cpp
[C#]
    //Codificar texto de código usando UTF-8 con BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Codificar texto de código usando UTF-8 sin BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## Ver también

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
