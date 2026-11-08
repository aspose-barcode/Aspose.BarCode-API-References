---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder class"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar la clase Aspose::BarCode::Generation::QrExtCodetextBuilder en C++."
type: docs
weight: 4300
url: /es/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | Agrega texto de código con el modo de compactación QR especificado a los elementos de texto de código extendidos. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Agrega texto de código con Identificador de Canal Extendido |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | Establece FNC1 en la primera posición. Si se había establecido otro modo FNC1 antes, se reemplaza. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Agrega el Separador de Grupo (GS - '\\u001D') a los elementos de texto de código extendido |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | Establece FNC1 en la segunda posición. Si se había establecido otro modo FNC1 antes, se reemplaza. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Agrega texto de código simple a los elementos de texto de código extendido |
| [Clear](./clear/)() override | Borra los elementos de texto de código extendido |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genera texto de código extendido a partir de la lista de texto de código extendido. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## Observaciones


Generador de texto de código extendido para códigos QR 2D en el modo ExtendedCodetext de EncodeMode

Use la propiedad TwoDDisplayText de [BarcodeGenerator](../barcodegenerator/) para establecer el texto visible al eliminar caracteres de gestión.

Esta muestra muestra cómo usar la primera posición FNC1 en Modo Extendido.
```cpp
[C#]
//crear texto de código
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//generar texto de código
string codetext = TextBuilder.GetExtendedCodetext();

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Esta muestra muestra cómo usar la segunda posición FNC1 en Modo Extendido.
```cpp
[C#]
//crear texto de código
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//generar texto de código
string codetext = TextBuilder.GetExtendedCodetext();

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Esta muestra muestra cómo usar el modo multi ECI en Modo Extendido.
```cpp
[C#]
//crear texto de código
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//generar texto de código
string codetext = TextBuilder.GetExtendedCodetext();

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Ver también

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
