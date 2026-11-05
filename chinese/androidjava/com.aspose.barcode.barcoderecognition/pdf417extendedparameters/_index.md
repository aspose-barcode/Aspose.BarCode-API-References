---
title: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "存储已识别条码的 MacroPdf417 元数据信息"
type: docs
weight: 38
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object，[com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

存储已识别条码的 MacroPdf417 元数据信息

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
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 Pdf417ExtendedParameters 值。 |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | 宏 PDF417 收件人名称（可选）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | 宏 PDF417 校验和（可选）。 |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | 获取条码的文件 ID，仅在 MacroPdf417 中可用。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | 宏 PDF417 文件名（可选）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | 宏 PDF417 文件大小（可选）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | 获取条码的段 ID，仅在 MacroPdf417 中可用。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | 获取宏 pdf417 条码段的计数。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | 宏 PDF417 发件人名称（可选）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | 指示该段是否为宏 PDF417 文件的最后一段。 |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | 宏 PDF417 时间戳（可选）。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isCode128Emulation()](#isCode128Emulation--) | 标志，指示 MicroPdf417 条码使用 908、909、910 或 911 Code 128 仿真码字进行编码。 |
| [isEmpty()](#isEmpty--) | 测试所有参数是否仅具有默认值 |
| [isLinked()](#isLinked--) | 标志，指示该条码必须链接到 1D 条码。 |
| [isReaderInitialization()](#isReaderInitialization--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程指令。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此 Pdf417ExtendedParameters 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 Pdf417ExtendedParameters 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 System.Object 值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则，  **false** 。
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


宏 PDF417 收件人名称（可选）。

**Returns:**
java.lang.String - 收件人名称。
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


宏 PDF417 校验和（可选）。

**Returns:**
int - 校验和。
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


获取条码的文件 ID，仅在 MacroPdf417 中可用。

值：MacroPdf417 的文件 ID

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


宏 PDF417 文件名（可选）。

**Returns:**
java.lang.String - 文件名。
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


宏 PDF417 文件大小（可选）。

**Returns:**
int - 文件大小。
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


获取条码的段 ID，仅在 MacroPdf417 中可用。

值：条形码的段 ID。

**Returns:**
整数
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


获取宏 pdf417 条形码段计数。默认值为 -1。

值：段计数。

**Returns:**
整数
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


宏 PDF417 发件人名称（可选）。

**Returns:**
java.lang.String - 发件人名称
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


指示该段是否为宏 PDF417 文件的最后一段。

**Returns:**
boolean - 终止符。
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


宏 PDF417 时间戳（可选）。

**Returns:**
java.time.LocalDateTime - 时间戳。
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


标志，指示 MicroPdf417 条码使用 908、909、910 或 911 Code 128 仿真码字进行编码。

**Returns:**
boolean - Code 128 仿真标志
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


测试所有参数是否仅具有默认值

值：如果所有参数仅具有默认值则返回  **true** ；否则返回  **false** 。

**Returns:**
布尔
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


标志，指示该条码必须链接到 1D 条码。

值：链接标志

**Returns:**
布尔
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程指令。

值：读取器初始化标志

**Returns:**
布尔
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


返回此 Pdf417ExtendedParameters 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 Pdf417ExtendedParameters 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | 整数 |  |

