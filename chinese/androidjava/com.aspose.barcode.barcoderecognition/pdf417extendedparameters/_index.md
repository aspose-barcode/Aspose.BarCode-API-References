---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 存储已识别的条形码的 MacroPdf417 元数据
type: docs
weight: 40
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

存储已识别的条形码的 MacroPdf417 元数据

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 Pdf417ExtendedParameters 值。 |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417 收件人名称（可选）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417 校验和（可选）。 |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | 获取条形码的文件 ID，仅在 MacroPdf417 中可用。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417 文件名（可选）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417 文件大小（可选）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | 获取条形码的段 ID，仅在 MacroPdf417 中可用。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | 获取 macro pdf417 条形码段计数。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417 发件人名称（可选）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | 指示该段是否为 Macro PDF417 文件的最后一段。 |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417 时间戳（可选）。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isCode128Emulation()](#isCode128Emulation--) | 标志，指示 MicroPdf417 条形码使用 908、909、910 或 911 Code 128 仿真代码字进行编码。 |
| [isEmpty()](#isEmpty--) | 测试所有参数是否仅具有默认值 |
| [isLinked()](#isLinked--) | 标志，指示该条形码必须链接到 1D 条形码。 |
| [isReaderInitialization()](#isReaderInitialization--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此 Pdf417ExtendedParameters 的可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 Pdf417ExtendedParameters 值。

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
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Macro PDF417 收件人名称（可选）。

**Returns:**
java.lang.String - 收件人名称。
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417 校验和（可选）。

**Returns:**
int - 校验和。
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


获取条形码的文件 ID，仅在 MacroPdf417 中可用。

值：MacroPdf417 的文件 ID

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417 文件名（可选）。

**Returns:**
java.lang.String - 文件名。
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417 文件大小（可选）。

**Returns:**
int - 文件大小。
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


获取条形码的段 ID，仅在 MacroPdf417 中可用。

值：条形码的段 ID。

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


获取 macro pdf417 条形码段计数。默认值为 -1。

值：段计数。

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Macro PDF417 发件人名称（可选）。

**Returns:**
java.lang.String - 发件人名称
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


指示该段是否为 Macro PDF417 文件的最后一段。

**Returns:**
boolean - 终止符。
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417 时间戳（可选）。

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


标志，指示 MicroPdf417 条形码使用 908、909、910 或 911 Code 128 仿真代码字进行编码。

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


测试所有参数是否仅具有默认值

值：如果所有参数仅具有默认值，则返回 **true**；否则返回 **false**。

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


标志，指示该条形码必须链接到 1D 条形码。

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

Value: Reader initialization flag

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


返回此 Pdf417ExtendedParameters 的可读字符串表示。

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
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

