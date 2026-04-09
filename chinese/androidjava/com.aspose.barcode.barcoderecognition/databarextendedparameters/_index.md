---
title: DataBarExtendedParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 存储已识别条码的 DataBar 附加信息 BarCodeReader reader  new BarCodeReadertest.png DecodeType.DATABAR_OMNI_DIRECTIONAL forBarCodeResult result  reader.readBarCodes    System.out.printlnBarCode Type   result.getCodeTypeName    System.out.printlnBarCode CodeText   result.getCodeText    System.out.printlnQR Structured Append Quantity   result.getExtended.getQR.getQRStructuredAppendModeBarCodesQuantity
type: docs
weight: 30
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/databarextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public class DataBarExtendedParameters extends BaseExtendedParameters
```

存储已识别的条形码的 DataBar 附加信息 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的值。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [is2DCompositeComponent()](#is2DCompositeComponent--) | 获取 DataBar 2D 复合组件标志。 |
| [isEmpty()](#isEmpty--) | 测试所有参数是否仅具有默认值 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此对象的可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 一个 System.Object 值，用于与此实例进行比较。 |

**Returns:**
boolean - **true** 如果对象的值与此实例相同；否则，**false**。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
### is2DCompositeComponent() {#is2DCompositeComponent--}
```
public boolean is2DCompositeComponent()
```


获取 DataBar 2D 复合组件标志。默认值为 false。

**Returns:**
boolean - DataBar 2D 复合组件标志。
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


返回此对象的可读字符串表示。

**Returns:**
java.lang.String - 表示此对象的字符串。
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

