---
title: "BarCodeResult.GetCodeText"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "BarCodeResult método. Obtiene el texto del código con codificación"
type: docs
weight: 130
url: /es/net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

Obtiene el texto del código con codificación.

```csharp
public string GetCodeText(Encoding encoding)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codificación | Codificación | La codificación para el texto del código. |

### Valor de retorno

Una cadena que contiene el texto del código reconocido.

## Ejemplos

Este ejemplo muestra cómo usar `GetCodeText`:

```csharp
[C#]
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Ver también

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


