---
title: BarCodeResult
second_title: Aspose.BarCode for Android via Java API Reference
description: 認識されたバーコードデータを、SingleDecodeType 型、文字列 codetext、BarCodeRegionParameters region などのパラメータと共に保存します。
type: docs
weight: 18
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

SingleDecodeType 型、string codetext、BarCodeRegionParameters region などの認識バーコードデータを保存します

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | BarCodeResult クラスのコピーを作成します。 |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | BarCodeResult クラスのコピーを作成します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された BarCodeResult の値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | エンコードされたコードバイトを取得します |
| [getCodeText()](#getCodeText--) | コードテキストを取得します |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | エンコードされたコードテキストを取得します。 |
| [getCodeType()](#getCodeType--) | バーコードのタイプを取得します |
| [getCodeTypeName()](#getCodeTypeName--) | バーコードタイプの名前を取得します |
| [getConfidence()](#getConfidence--) | 認識されたバーコードの信頼度レベルを取得します |
| [getExtended()](#getExtended--) | 認識されたバーコードの拡張パラメータを取得します |
| [getReadingQuality()](#getReadingQuality--) | 読み取り品質を取得します。 |
| [getRegion()](#getRegion--) | バーコード領域を取得します |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この BarCodeResult の人間が読める文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


BarCodeResult クラスのコピーを作成します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | BarCodeResult のコピーインスタンスです。 |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


BarCodeResult クラスのコピーを作成します。

**Returns:**
java.lang.Object - BarCodeResult クラスのコピーを返します。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された BarCodeResult の値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較する BarCodeResult の値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


エンコードされたコードバイトを取得します

値: バーコードのコードバイト

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


コードテキストを取得します

Value: バーコードのコードテキスト

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
```


エンコードされたコードテキストを取得します。

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| エンコーディング | java.nio.charset.Charset | コードテキストのエンコーディングです。 |

**Returns:**
java.lang.String - 認識されたコードテキストを含む文字列です。
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


バーコードのタイプを取得します

Value: 認識されたバーコードの型情報

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


バーコードタイプの名前を取得します

Value: 認識されたバーコードの型名

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


認識されたバーコードの信頼度レベルを取得します

Value:  BarCodeConfidence.Strong は偽や誤認識がなく、 BarCodeConfidence.Moderate は弱いチェックサムまたはチェックサムなしのバーコードに対してこの信頼レベルのため、時々偽や誤ったコードテキストがある可能性があります、 BarCodeConfidence.None は常に誤ったコードテキストで、偽の認識である可能性があります

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


認識されたバーコードの拡張パラメータを取得します

Value: 認識されたバーコードの拡張パラメータ

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


読み取り品質を取得します。1D および郵便バーコードで機能します。

Value: 読み取り品質のパーセンテージ

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


バーコード領域を取得します

Value: 認識されたバーコードの領域

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


この BarCodeResult の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この BarCodeResult を表す文字列です。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

