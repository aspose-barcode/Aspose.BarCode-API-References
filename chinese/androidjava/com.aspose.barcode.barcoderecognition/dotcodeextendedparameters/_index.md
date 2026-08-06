---
title: DotCodeExtendedParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 存储已识别的 DotCode 条形码的特殊数据
type: docs
weight: 33
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

存储已识别的 DotCode 条形码的特殊数据

此示例展示如何获取 DotCode 原始值

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");

 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 值。 |
| [getClass()](#getClass--) |  |
| [getDotCodeIsReaderInitialization()](#getDotCodeIsReaderInitialization--) | 指示代码是否用于指示读取器将以下数据解释为初始化或重新编程条形码读取器的指令。 |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | 获取 DotCode 结构化追加模式条形码的 ID。 |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | 获取 DotCode 结构化追加模式条形码的数量。 |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | 获取 DotCode 结构化追加模式条形码的 ID。 |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | 获取 DotCode 结构化追加模式条形码的数量。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEmpty()](#isEmpty--) | 测试所有参数是否仅具有默认值 |
| [isReaderInitialization()](#isReaderInitialization--) | 指示代码是否用于指示读取器将以下数据解释为初始化或重新编程条形码读取器的指令。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | 返回一个值，指示第一个 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 值是否等于第二个。 |
| [op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | 返回一个值，指示第一个 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 值是否与第二个不同。 |
| [toString()](#toString--) | 返回此 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 值。

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
### getDotCodeIsReaderInitialization() {#getDotCodeIsReaderInitialization--}
```
public final boolean getDotCodeIsReaderInitialization()
```


指示代码是否用于指示读取器将以下数据解释为初始化或重新编程条形码读取器的指令。默认值为 false。

**Returns:**
boolean
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


获取 DotCode 结构化追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码计数。默认值为 -1。

值：DotCode 结构化追加模式条形码的 ID。

**Returns:**
int - DotCode 结构化追加模式条形码的 ID。
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


获取 DotCode 结构化追加模式条形码的计数。默认值为 -1。计数必须在 1 到 35 之间。

值：DotCode 结构化追加模式条形码的计数。

**Returns:**
int - DotCode 结构化追加模式条形码的计数。
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


获取 DotCode 结构化追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码计数。默认值为 -1。

值：DotCode 结构化追加模式条形码的 ID。

**Returns:**
int - DotCode 结构化追加模式条形码的 ID。
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


获取 DotCode 结构化追加模式条形码的计数。默认值为 -1。计数必须在 1 到 35 之间。

值：DotCode 结构化追加模式条形码的计数。

**Returns:**
int - DotCode 结构化追加模式条形码的计数。
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
public final boolean isReaderInitialization()
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




### op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


返回一个值，指示第一个 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 值是否等于第二个。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 第一个比较值 |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 第二个比较值 |

**Returns:**
boolean -  **true**  如果第一个与第二个具有相同的值；否则， **false**。
### op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


返回一个值，指示第一个 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 值是否与第二个不同。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 第一个比较值 |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 第二个比较值 |

**Returns:**
boolean -  **true**  如果第一个与第二个的值不同；否则， **false**。
### toString() {#toString--}
```
public String toString()
```


返回此 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 的字符串。
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

