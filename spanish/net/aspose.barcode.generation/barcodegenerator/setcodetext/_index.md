---
title: "BarcodeGenerator.SetCodeText"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método BarcodeGenerator. Establece codetext como una secuencia de bytes"
type: docs
weight: 100
url: /es/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Establece codetext como una secuencia de bytes.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codeBytes | Byte[] | Bytes de codetext |

### Ver también

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Codifica el Unicode **codeText** en una secuencia de bytes usando la **encoding** especificada. UTF-8 es la codificación más utilizada. Si la codificación lo admite, la función inserta automáticamente una [marca de orden de bytes (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Esta función está destinada únicamente al uso con códigos de barras 2D (p.ej., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Permite la codificación manual de texto Unicode usando codificaciones nacionales o especiales; sin embargo, este método se considera obsoleto en aplicaciones modernas. Para casos de uso modernos, se recomienda la codificación [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) para datos Unicode.

El uso de esta función con códigos de barras 1D, códigos de barras compatibles con GS1 (incluidos los 2D), o códigos de barras HIBC (incluidos los 2D) no está soportado por las normas de códigos de barras correspondientes y puede producir resultados impredecibles.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codeText | Cadena | Cadena CodeText |
| codificación | Codificación | Codificación aplicada |

## Ejemplos

Este ejemplo muestra cómo usar `SetCodeText` para establecer texto codificado en Unicode para códigos de barras 2D usando diferentes codificaciones:

```csharp
[C#]
//Codificar texto QR Code usando UTF-8 con BOM
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

### Ver también

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Codifica el Unicode **codeText** en una secuencia de bytes usando la **encoding** especificada. UTF-8 es la codificación más utilizada. Si la codificación lo admite y **insertBOM** está configurado a `true`, la función incluye una [marca de orden de bytes (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Esta función está destinada únicamente al uso con códigos de barras 2D (p.ej., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Permite la codificación manual de texto Unicode usando codificaciones nacionales o especiales; sin embargo, este método se considera obsoleto en aplicaciones modernas. Para casos de uso modernos, se recomienda la codificación [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) para datos Unicode.

El uso de esta función con códigos de barras 1D, códigos de barras compatibles con GS1 (incluidos los 2D), o códigos de barras HIBC (incluidos los 2D) no está soportado por las normas de códigos de barras correspondientes y puede producir resultados impredecibles.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codeText | Cadena | Cadena CodeText |
| codificación | Codificación | Codificación aplicada |
| insertBOM | Boolean | Indica si se debe insertar una marca de orden de bytes (BOM) cuando la codificación especificada la soporta (p.ej., UTF-8, UTF-16, UTF-32). Si se establece en `true`, se agrega el BOM; si se establece en `false`, se omite el BOM incluso si la codificación normalmente lo usa. |

## Ejemplos

Este ejemplo muestra cómo usar `SetCodeText` con o sin un BOM para códigos de barras 2D.

```csharp
[C#]
//Codificar codetext usando UTF-8 con BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Codificar codetext usando UTF-8 sin BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### Ver también

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


