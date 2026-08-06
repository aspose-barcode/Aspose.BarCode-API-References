---
title: AztecExtendedParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 存储 Aztec 识别条码的特殊数据
type: docs
weight: 12
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/aztecextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class AztecExtendedParameters extends BaseExtendedParameters
```

存储 Aztec 识别条码的特殊数据

--------------------

> ```
> This sample shows how to get Aztec raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.AZTEC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText());
>      System.out.println("Aztec barcode ID: " + result.getExtended.getAztec.getStructuredAppendBarcodeId());
>      System.out.println("Aztec barcodes count: " + result.getExtended.getAztec.getStructuredAppendBarcodesCount());
>      System.out.println("Aztec file ID: " + result.getExtended.getAztec.getStructuredAppendFileId());
>      System.out.println("Aztec is reader initialization: " + result.getExtended.getAztec.isReaderInitialization());
>  }
> ```
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 AztecExtendedParameters 值。 |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | 获取 Aztec 结构化追加模式条形码的 ID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | 获取 Aztec 结构化追加模式条形码的计数。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | 获取 Aztec 结构化追加模式的文件 ID。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEmpty()](#isEmpty--) | 测试所有参数是否仅具有默认值 |
| [isReaderInitialization()](#isReaderInitialization--) | 指示代码是否用于指示读取器将以下数据解释为初始化或重新编程条形码读取器的指令。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此 AztecExtendedParameters 的可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 AztecExtendedParameters 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 一个 System.Object 值，用于与此实例进行比较。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则， **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


获取 Aztec 结构化追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码计数。默认值为 0。

值：Aztec 结构化追加模式的条形码 ID。

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


获取 Aztec 结构化追加模式条形码的计数。默认值为 0。计数必须在 1 到 26 之间。

值：Aztec 结构化追加模式的条形码计数。

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


获取 Aztec 结构化追加模式的文件 ID。默认值为空字符串

值：Aztec 结构化追加模式的文件 ID。

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
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


指示代码是否用于指示读取器将以下数据解释为初始化或重新编程条形码读取器的指令。默认值为 false。

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


返回此 AztecExtendedParameters 的可读字符串表示。

**Returns:**
java.lang.String - 表示此 AztecExtendedParameters 的字符串。
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

