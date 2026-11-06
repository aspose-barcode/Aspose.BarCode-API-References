---
title: "BarcodeSettings"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "主要なBarCodeデコードパラメータです。"
type: docs
weight: 19
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/barcodesettings/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeSettings
```

メインの BarCode デコードパラメータです。認識されたデータに影響を与えるパラメータを含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustraliaPost()](#getAustraliaPost--) | AustraliaPost のデコードパラメータを取得します |
| [getChecksumValidation()](#getChecksumValidation--) | 1D および郵便バーコードの認識時にチェックサム検証を有効にします。 |
| [getClass()](#getClass--) |  |
| [getDetectEncoding()](#getDetectEncoding--) | Unicode コードセットの文字テキストエンコーディングをエンジンが検出するよう強制するフラグ。 |
| [getStripFNC()](#getStripFNC--) | コードテキストから FNC1、FNC2、FNC3 文字を除去します。 |
| [hashCode()](#hashCode--) |  |
| [isOnlyRequestedTypes()](#isOnlyRequestedTypes--) | 認識対象として明示的に指定されたバーコードタイプのみを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChecksumValidation(ChecksumValidation value)](#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-) | 1D および郵便バーコードの認識時にチェックサム検証を有効にします。 |
| [setDetectEncoding(boolean value)](#setDetectEncoding-boolean-) | Unicode コードセットの文字テキストエンコーディングをエンジンが検出するよう強制するフラグ。 |
| [setOnlyRequestedTypes(boolean value)](#setOnlyRequestedTypes-boolean-) | 認識対象として明示的に指定されたバーコードタイプのみを返します。 |
| [setStripFNC(boolean value)](#setStripFNC-boolean-) | コードテキストから FNC1、FNC2、FNC3 文字を除去します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustraliaPost() {#getAustraliaPost--}
```
public AustraliaPostSettings getAustraliaPost()
```


AustraliaPost のデコードパラメータを取得します

**Returns:**
[AustraliaPostSettings](../../com.aspose.barcode.barcoderecognition/australiapostsettings) - The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology
### getChecksumValidation() {#getChecksumValidation--}
```
public ChecksumValidation getChecksumValidation()
```


1D および郵便バーコードの認識時にチェックサム検証を有効にします。デフォルトでは、チェックサムが必須のシンボロジーは「はい」とみなされ、チェックサムが任意のものは「いいえ」とみなされます。チェックサムが使用されないシンボロジー: Codabar, PatchCode, Pharmacode, DataLogic2of5 チェックサムが可能なシンボロジー: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN チェックサムが常に使用されるシンボロジー: その他のシンボロジー Example BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Returns:**
[ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) - Enable checksum validation during recognition for 1D and Postal barcodes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDetectEncoding() {#getDetectEncoding--}
```
public boolean getDetectEncoding()
```


Unicode コードセットの文字テキストエンコーディングをエンジンが検出するよう強制するフラグ。デフォルト値は true です。

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

値: Unicode コードセットの文字テキストエンコーディングをエンジンが検出するよう強制するフラグ

**Returns:**
boolean
### getStripFNC() {#getStripFNC--}
```
public boolean getStripFNC()
```


コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。例: BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOnlyRequestedTypes() {#isOnlyRequestedTypes--}
```
public boolean isOnlyRequestedTypes()
```


認識のために明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換または同等のタイプとして認識されたバーコードは除外されます。デフォルト値は false です。

例:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Returns:**
boolean - 明示的に要求されたバーコードタイプのみが返される場合は true、そうでない場合は false
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChecksumValidation(ChecksumValidation value) {#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-}
```
public void setChecksumValidation(ChecksumValidation value)
```


1D および郵便バーコードの認識時にチェックサム検証を有効にします。デフォルトでは、チェックサムが必須のシンボロジーは「はい」とみなされ、チェックサムが任意のものは「いいえ」とみなされます。チェックサムが使用されないシンボロジー: Codabar, PatchCode, Pharmacode, DataLogic2of5 チェックサムが可能なシンボロジー: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN チェックサムが常に使用されるシンボロジー: その他のシンボロジー Example BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) | 1D および郵便バーコードの認識時にチェックサム検証を有効にします。 |

### setDetectEncoding(boolean value) {#setDetectEncoding-boolean-}
```
public void setDetectEncoding(boolean value)
```


Unicode コードセットの文字テキストエンコーディングをエンジンが検出するよう強制するフラグ。デフォルト値は true です。

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

値: Unicode コードセットの文字テキストエンコーディングをエンジンが検出するよう強制するフラグ

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setOnlyRequestedTypes(boolean value) {#setOnlyRequestedTypes-boolean-}
```
public void setOnlyRequestedTypes(boolean value)
```


認識のために明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換または同等のタイプとして認識されたバーコードは除外されます。デフォルト値は false です。

例:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes())
 {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setStripFNC(boolean value) {#setStripFNC-boolean-}
```
public void setStripFNC(boolean value)
```


コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。例: BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

