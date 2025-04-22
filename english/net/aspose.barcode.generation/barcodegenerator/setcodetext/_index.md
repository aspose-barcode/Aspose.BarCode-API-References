---
title: BarcodeGenerator.SetCodeText
second_title: Aspose.BarCode for .NET API Reference
description: BarcodeGenerator method. Set codetext as sequence of bytes
type: docs
weight: 100
url: /net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Set codetext as sequence of bytes.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| codeBytes | Byte[] | Bytes of codetext |

### See Also

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Encodes codetext with byte order mark (BOM), using specified encoding: like UTF8, UTF16, UTF32, e.t.c.. 1D barcodes should use Encoding.ASCII or ISO/IEC 8859-1 - Encoding.GetEncoding(28591). 2D barcodes should use Encoding.UTF8.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Parameter | Type | Description |
| --- | --- | --- |
| codeText | String | CodeText string |
| encoding | Encoding | Applied encoding |

## Examples

This sample shows how to use SetCodeText with 1D and 2D barcodes

```csharp
[C#]
//Encode codetext of 1D barcodes with 7-bit ASCII encoding, byte order mark (BOM) is absent
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.Code128))
{
    gen.SetCodeText("123ABCD", Encoding.ASCII);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
//Encode codetext of 1D barcodes with 8-bit ISO/IEC 8859-1 encoding, byte order mark (BOM) is absent
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.Code128))
{
    gen.SetCodeText("123ABCD", Encoding.GetEncoding(28591));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
//Encode codetext of 2D barcodes with UTF8 encoding with byte order mark (BOM)
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.Code128))
{
    gen.SetCodeText("123ABCD", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
```

### See Also

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Encodes codetext with optional byte order mark (BOM) insertion, using specified encoding: like UTF8, UTF16, UTF32, e.t.c.. 1D barcodes should use Encoding.ASCII or ISO/IEC 8859-1 - Encoding.GetEncoding(28591). 2D barcodes should use Encoding.UTF8.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Parameter | Type | Description |
| --- | --- | --- |
| codeText | String | CodeText string |
| encoding | Encoding | Applied encoding |
| insertBOM | Boolean | flag indicates insertion of the Encoding byte order mark (BOM). In case, the Encoding requires byte order mark (BOM) insertion: like UTF8, UTF16, UTF32, e.t.c. and flag is set to true, the BOM is added, in case of setting flag to false, the BOM insertion is ignored. |

## Examples

This sample shows how to use SetCodeText with 1D and 2D barcodes

```csharp
[C#]
//Encode codetext of 1D barcodes with 7-bit ASCII encoding, byte order mark (BOM) is absent
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.Code128))
{
    gen.SetCodeText("123ABCD", Encoding.ASCII, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
//Encode codetext of 1D barcodes with 8-bit ISO/IEC 8859-1 encoding, byte order mark (BOM) is absent
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.Code128))
{
    gen.SetCodeText("123ABCD", Encoding.GetEncoding(28591), true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
//Encode codetext of 2D barcodes with UTF8 encoding with byte order mark (BOM)
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.Code128))
{
    gen.SetCodeText("123ABCD", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
//Encode codetext of 2D barcodes with UTF8 encoding without byte order mark (BOM)
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.Code128))
{
    gen.SetCodeText("123ABCD", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
```

### See Also

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


