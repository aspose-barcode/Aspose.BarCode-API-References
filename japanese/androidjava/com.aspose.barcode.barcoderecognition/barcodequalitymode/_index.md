---
title: "BarcodeQualityMode"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: 
type: docs
weight: 49
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/barcodequalitymode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BarcodeQualityMode extends Enum<BarcodeQualityMode>
```

選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低い要素は、より高度なメソッドが必要となり、認識速度が低下します。

--------------------

> ```
> This sample shows how to use BarcodeQuality mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## フィールド

| フィールド | 説明 |
| --- | --- |
| [HIGH](#HIGH) | 高品質バーコードの認識メソッドを有効にします。 |
| [LOW](#LOW) | 低品質バーコードの認識メソッドを有効にします。 |
| [NORMAL](#NORMAL) | 一般（標準）品質バーコードの認識メソッドを有効にします。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIGH {#HIGH}
```
public static final BarcodeQualityMode HIGH
```


高品質バーコードの認識メソッドを有効にします。

### LOW {#LOW}
```
public static final BarcodeQualityMode LOW
```


低品質バーコードの認識メソッドを有効にします。

### NORMAL {#NORMAL}
```
public static final BarcodeQualityMode NORMAL
```


一般（標準）品質バーコードの認識メソッドを有効にします。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static BarcodeQualityMode fromValue(int value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static BarcodeQualityMode valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### values() {#values--}
```
public static BarcodeQualityMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeQualityMode[]
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

