---
title: OneDExtendedParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 存储已识别的 1D 条形码的特殊数据，例如分离的代码文本和校验和
type: docs
weight: 39
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/onedextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class OneDExtendedParameters extends BaseExtendedParameters
```

存储已识别的 1D 条形码的特殊数据，例如分离的代码文本和校验和

--------------------

> ```
> This sample shows how to get 1D barcode value and checksum
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.EAN_13);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue());
>     System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
>  }
> ```
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的  OneDExtendedParameters  值。 |
| [getCheckSum()](#getCheckSum--) | 获取 1D 条形码的校验和。 |
| [getClass()](#getClass--) |  |
| [getValue()](#getValue--) | 获取 1D 条形码的代码文本（不含校验和）。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEmpty()](#isEmpty--) | 测试所有参数是否仅具有默认值 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此  OneDExtendedParameters 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的  OneDExtendedParameters  值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 一个 System.Object 值，用于与此实例进行比较。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则， **false** 。
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


获取 1D 条形码的校验和。

值：1D 条形码的校验和。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getValue() {#getValue--}
```
public String getValue()
```


获取 1D 条形码的代码文本（不含校验和）。

值：1D 条形码的代码文本（不含校验和）。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


测试所有参数是否仅具有默认值

值：如果所有参数仅具有默认值，则返回 **true**；否则返回 **false**。

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


返回此  OneDExtendedParameters 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此  OneDExtendedParameters 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

