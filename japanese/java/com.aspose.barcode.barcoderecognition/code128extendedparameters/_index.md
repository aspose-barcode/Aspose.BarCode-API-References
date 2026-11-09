---
title: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "認識された Code128 バーコードの特別なデータを格納します"
type: docs
weight: 27
url: /ja/java/com.aspose.barcode.barcoderecognition/code128extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Code128ExtendedParameters extends BaseExtendedParameters
```

認識された Code128 バーコードの特別なデータを格納します

認識されたバーコードの領域とバーコード角度を表します

--------------------

> ```
> This sample shows how to get code128 raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("Code128 Data Portions: " + result.getExtended().getCode128());
>  }
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された  Code128ExtendedParameters  の値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getCode128DataPortions()](#getCode128DataPortions--) | 認識された Code128 バーコードの  Code128DataPortion  配列を取得します |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | すべてのパラメーターがデフォルト値のみであるかテストします |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この  Code128ExtendedParameters  の人間が読める文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された  Code128ExtendedParameters  の値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための System.Object 値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCode128DataPortions() {#getCode128DataPortions--}
```
public Code128DataPortion[] getCode128DataPortions()
```


認識された Code128 バーコードの  Code128DataPortion  配列を取得します

値:  Code128DataPortion  の配列。

**Returns:**
com.aspose.barcode.barcoderecognition.Code128DataPortion[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32ビット符号付き整数のハッシュコード。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


すべてのパラメーターがデフォルト値のみであるかテストします

値: すべてのパラメーターがデフォルト値のみの場合 **true** を返し、そうでない場合は **false** を返します。

**Returns:**
boolean
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


この  Code128ExtendedParameters  の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この  Code128ExtendedParameters  を表す文字列です。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

