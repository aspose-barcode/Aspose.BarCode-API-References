---
title: "Clase QrExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.QrExtCodetextBuilder. Generador de texto extendido para códigos QR 2D para el modo ExtendedCodetext de EncodeMode"
type: docs
weight: 1630
url: /es/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

Generador de codetexto extendido para códigos de barras 2D QR para ExtendedCodetext Mode de EncodeMode

Utilice la propiedad TwoDDisplayText de BarcodeGenerator para establecer el texto visible eliminando los caracteres de gestión.

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddCodetextWithCompactionMode](../../aspose.barcode.generation/qrextcodetextbuilder/addcodetextwithcompactionmode/)(QrExtCompactionMode, string) | Agrega codetext con el modo de compactación QR especificado a los elementos de codetext extendido. |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Agrega codetexto con Identificador de Canal Extendido |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | Establece FNC1 en la primera posición. Si se había establecido otro modo FNC1 antes, se reemplaza. |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | Agrega Separador de Grupo (GS - '\\u001D') a los elementos de codetext extendido |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | Establece FNC1 en la segunda posición. Si se había establecido otro modo FNC1 antes, se reemplaza. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Agrega codetexto simple a los elementos de codetexto extendido |
| override [Clear](../../aspose.barcode.generation/qrextcodetextbuilder/clear/)() | Borra los elementos de codetexto extendido |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | Genera codetexto extendido a partir de la lista de codetexto extendido. |

## Ejemplos

Este ejemplo muestra cómo usar la primera posición FNC1 en Modo Extendido.

```csharp
[C#]
//crear codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//generar codetext
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

Este ejemplo muestra cómo usar la segunda posición FNC1 en Modo Extendido.

```csharp
[C#]
//crear codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//generar codetext
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

Este ejemplo muestra cómo usar el modo multi ECI en Modo Extendido.

```csharp
[C#]
//crear codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//generar codetext
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

### Ver también

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


