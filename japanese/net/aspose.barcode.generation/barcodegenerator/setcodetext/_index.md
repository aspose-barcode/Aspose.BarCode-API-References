---
title: "BarcodeGenerator.SetCodeText"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "BarcodeGenerator メソッド。codetext をバイト列として設定します。"
type: docs
weight: 100
url: /ja/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

codetext をバイト列として設定します。

```csharp
public void SetCodeText(byte[] codeBytes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| codeBytes | Byte[] | codetext のバイト |

### 関連項目

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

指定された **encoding** を使用して、Unicode の **codeText** をバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。エンコーディングがサポートしている場合、関数は自動的に [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) を挿入します。

この関数は 2D バーコード（例: Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR など）のみでの使用を想定しています。国内または特殊なエンコーディングを使用して Unicode テキストを手動でエンコードできるようにしますが、現代のアプリケーションではこの方法は時代遅れと見なされています。最新のユースケースでは、Unicode データに対して [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) エンコーディングの使用が推奨されます。

この関数を 1D バーコード、GS1 準拠のバーコード（2D を含む）または HIBC バーコード（2D を含む）で使用すると、該当するバーコード規格でサポートされておらず、予測不能な結果になる可能性があります。

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| codeText | 文字列 | CodeText 文字列 |
| エンコーディング | エンコーディング | 適用されたエンコーディング |

## 例

この例は、異なるエンコーディングを使用して 2D バーコード用の Unicode エンコードテキストを設定する方法として `SetCodeText` の使用例を示します。

```csharp
[C#]
//UTF-8（BOM 付き）で QR コードテキストをエンコードする
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Shift-JIS（日本語エンコーディング）で DataMatrix テキストをエンコードする
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### 関連項目

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

指定された **encoding** を使用して、Unicode の **codeText** をバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。エンコーディングがサポートし、**insertBOM** が `true` に設定されている場合、関数は [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) を含めます。

この関数は 2D バーコード（例: Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR など）のみでの使用を想定しています。国内または特殊なエンコーディングを使用して Unicode テキストを手動でエンコードできるようにしますが、現代のアプリケーションではこの方法は時代遅れと見なされています。最新のユースケースでは、Unicode データに対して [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) エンコーディングの使用が推奨されます。

この関数を 1D バーコード、GS1 準拠のバーコード（2D を含む）または HIBC バーコード（2D を含む）で使用すると、該当するバーコード規格でサポートされておらず、予測不能な結果になる可能性があります。

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| codeText | 文字列 | CodeText 文字列 |
| エンコーディング | エンコーディング | 適用されたエンコーディング |
| insertBOM | Boolean | 指定されたエンコーディングがサポートしている場合にバイト順マーク（BOM）を挿入するかどうかを示します（例: UTF-8、UTF-16、UTF-32）。`true` に設定すると BOM が追加され、`false` に設定すると、エンコーディングが通常 BOM を使用していても省略されます。 |

## 例

この例は、2D バーコードで BOM の有無にかかわらず `SetCodeText` を使用する方法を示しています。

```csharp
[C#]
//UTF-8（BOM 付き）で codetext をエンコードする
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//UTF-8（BOM なし）で codetext をエンコードする
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### 関連項目

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


