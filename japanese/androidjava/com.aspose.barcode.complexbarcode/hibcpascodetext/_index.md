---
title: "HIBCPASCodetext"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "HIBC PASコードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 18
url: /ja/androidjava/com.aspose.barcode.complexbarcode/hibcpascodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class HIBCPASCodetext implements IComplexCodetext
```

HIBC PASコードに埋め込まれたテキストをエンコードおよびデコードするクラス。

--------------------

> ```
> This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.
>   
> 
>   HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
>   complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
>   complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
>   complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
>   complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
>   ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>   BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.HIBC_DATA_MATRIX_PAS);
>   reader.readBarCodes();
>   String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  	HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
>   System.out.println("Data location: {0}", readCodetext.getDataLocation());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[0].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[0].getData());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[1].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[1].getData());
>       }
>   }
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HIBCPASCodetext()](#HIBCPASCodetext--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addRecord(HIBCPASRecord record)](#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-) | 新しいレコードを追加します |
| [addRecord(int dataType, String data)](#addRecord-int-java.lang.String-) | 新しいレコードを追加します |
| [clear()](#clear--) | レコードリストをクリアします |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された HIBCPASCodetext 値と等しいかどうかを示す値を返します。 |
| [getBarcodeType()](#getBarcodeType--) | バーコードの種類を取得します。 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | コードテキストを構築します |
| [getDataLocation()](#getDataLocation--) | データの場所を特定します。 |
| [getRecords()](#getRecords--) | レコードリストを取得します |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 構築されたコードテキストからインスタンスを初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | バーコードのタイプを取得または設定します。 |
| [setDataLocation(int value)](#setDataLocation-int-) | データの場所を特定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCPASCodetext() {#HIBCPASCodetext--}
```
public HIBCPASCodetext()
```


### addRecord(HIBCPASRecord record) {#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-}
```
public void addRecord(HIBCPASRecord record)
```


新しいレコードを追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| record | [HIBCPASRecord](../../com.aspose.barcode.complexbarcode/hibcpasrecord) | 追加されるレコード |

### addRecord(int dataType, String data) {#addRecord-int-java.lang.String-}
```
public void addRecord(int dataType, String data)
```


新しいレコードを追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dataType | int | データのタイプ |
| データ | java.lang.String | データ文字列 |

### clear() {#clear--}
```
public void clear()
```


レコードリストをクリアします

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された HIBCPASCodetext 値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための HIBCPASCodetext 値。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は、  **false** 。
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


バーコードの種類を取得します。

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


コードテキストを構築します

**Returns:**
java.lang.String - 構築されたコードテキスト
### getDataLocation() {#getDataLocation--}
```
public int getDataLocation()
```


データの場所を特定します。

**Returns:**
int
### getRecords() {#getRecords--}
```
public System.Collections.Generic.List<HIBCPASRecord> getRecords()
```


レコードリストを取得します

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.complexbarcode.HIBCPASRecord> - レコードのリスト
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


構築されたコードテキストからインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 構築されたコードテキスト。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


バーコードの種類を取得または設定します。HIBC PAS コードテキストは HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCDataMatrixPAS、HIBCQRPAS エンコードタイプを使用してエンコードできます。デフォルト値: HIBCCode39PAS。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setDataLocation(int value) {#setDataLocation-int-}
```
public void setDataLocation(int value)
```


データの場所を特定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

