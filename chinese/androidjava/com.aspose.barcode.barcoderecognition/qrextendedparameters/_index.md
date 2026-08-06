---
title: QRExtendedParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 存储已识别的条形码的 QR Structured Append 信息
type: docs
weight: 42
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

存储已识别的条形码的 QR Structured Append 信息

此示例展示如何获取 QR Structured Append 数据

```
{
```
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 值。 |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | 已识别条码的 Reed-Solomon 错误校正级别。 |
| [getMicroQRVersion()](#getMicroQRVersion--) | 已识别 MicroQR Code 的版本。 |
| [getQRErrorLevel()](#getQRErrorLevel--) | 已识别条码的 Reed-Solomon 错误校正级别。 |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | 获取 QR 结构化追加模式条码的索引。 |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | 获取 QR 结构化追加模式条码的数量。 |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | 获取 QR 结构追加模式奇偶校验数据。 |
| [getQRVersion()](#getQRVersion--) | 识别的 QR Code 的版本。 |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | 识别的 RectMicroQR Code 的版本。 |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | 获取 QR 结构化追加模式条码的索引。 |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | 获取 QR 结构化追加模式条码的数量。 |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | 获取 QR 结构追加模式奇偶校验数据。 |
| [getVersion()](#getVersion--) | 识别的 QR Code 的版本。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEmpty()](#isEmpty--) | 测试所有参数是否仅具有默认值 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | 返回一个值，指示第一个 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 值是否等于第二个。 |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | 返回一个值，指示第一个 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 值是否不同于第二个。 |
| [toString()](#toString--) | 返回此 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 值。

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
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


识别的条形码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


识别的 MicroQR Code 的版本。从 M1 到 M4。

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


识别的条形码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


获取 QR 结构追加模式条形码的索引。索引从 0 开始。默认值为 -1。

值：QR 结构追加模式条形码的数量。

**Returns:**
int - QR 结构追加模式条形码的索引。
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


获取 QR 结构追加模式条形码的数量。默认值为 -1。

值：QR 结构追加模式条形码的数量。

**Returns:**
int - QR 结构追加模式条形码的数量。
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


获取 QR 结构追加模式奇偶校验数据。默认值为 -1。

值：QR 结构追加模式条形码的索引。

**Returns:**
int - QR 结构追加模式奇偶校验数据。
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


识别的 QR Code 的版本。从 Version1 到 Version40。

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


识别的 RectMicroQR Code 的版本。从 R7x43 到 R17x139。

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


获取 QR 结构追加模式条形码的索引。索引从 0 开始。默认值为 -1。

值：QR 结构追加模式条形码的数量。

**Returns:**
int - QR 结构追加模式条形码的索引。
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


获取 QR 结构追加模式条形码的数量。默认值为 -1。

值：QR 结构追加模式条形码的数量。

**Returns:**
int - QR 结构追加模式条形码的数量。
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


获取 QR 结构追加模式奇偶校验数据。默认值为 -1。

值：QR 结构追加模式条形码的索引。

**Returns:**
int - QR 结构追加模式奇偶校验数据。
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


识别的 QR Code 的版本。从 Version1 到 Version40。

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


返回一个值，指示第一个 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 值是否等于第二个。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 第一个比较值 |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 第二个比较值 |

**Returns:**
boolean -  **true**  如果第一个与第二个具有相同的值；否则， **false**。
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


返回一个值，指示第一个 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 值是否不同于第二个。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 第一个比较值 |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 第二个比较值 |

**Returns:**
boolean -  **true**  如果第一个与第二个的值不同；否则， **false**。
### toString() {#toString--}
```
public String toString()
```


返回此 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 的字符串。
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

