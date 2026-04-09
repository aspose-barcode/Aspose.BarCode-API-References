---
title: MaxiCodeCodetextMode3
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 用于对嵌入 MaxiCode 代码中模式 3 的文本进行编码和解码的类。
type: docs
weight: 27
url: /zh/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext), [com.aspose.barcode.complexbarcode.MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)
```
public class MaxiCodeCodetextMode3 extends MaxiCodeStructuredCodetext
```

用于对 MaxiCode 代码中嵌入的文本进行编码和解码的类（适用于模式 3）。此示例展示了如何对模式 3 的 MaxiCode 文本进行编码和解码。

```
//Mode 3 with standart second message
  MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
  maxiCodeCodetext.setPostalCode("B1050");
  maxiCodeCodetext.setCountryCode(056);
  maxiCodeCodetext.setServiceCategory(999);
  MaxiCodeStandartSecondMessage maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
  maxiCodeStandartSecondMessage.setMessage("Test message");
  maxiCodeCodetext.setSecondMessage(maxiCodeStandartSecondMessage);
  ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
  complexGenerator.generateBarCodeImage();

  //Mode 3 with structured second message
  MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
  maxiCodeCodetext.setPostalCode("B1050");
  maxiCodeCodetext.setCountryCode(056);
  maxiCodeCodetext.setServiceCategory(999);
  MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
  maxiCodeStructuredSecondMessage.add("634 ALPHA DRIVE");
  maxiCodeStructuredSecondMessage.add("PITTSBURGH");
  maxiCodeStructuredSecondMessage.add("PA");
  maxiCodeStructuredSecondMessage.setYear(99);
  maxiCodeCodetext.setSecondMessage(maxiCodeStructuredSecondMessage);
  ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
  complexGenerator.generateBarCodeImage();

  //Decoding raw codetext with standart second message
  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for(BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceOf MaxiCodeCodetextMode3)
      {
          MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
          if (maxiCodeStructuredCodetext.getSecondMessage() instanceOf MaxiCodeStandartSecondMessage)
          {
              MaxiCodeStandartSecondMessage secondMessage = (MaxiCodeStandartSecondMessage)maxiCodeStructuredCodetext.getSecondMessage();
              System.out.println("Message: " + secondMessage.getMessage());
          }
      }
  }
  //Decoding raw codetext with structured second message
  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for(BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceOf MaxiCodeCodetextMode3)
      {
          MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
          if (maxiCodeStructuredCodetext.getSecondMessage() instanceOf MaxiCodeStructuredSecondMessage)
          {
              MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.getSecondMessage();
              System.out.println("Message:");
              for(String identifier : secondMessage.getIdentifiers())
              {
                  System.out.println(identifier);
              }
          }
      }
  }
```
## Constructors

| Constructor | 描述 |
| --- | --- |
| [MaxiCodeCodetextMode3()](#MaxiCodeCodetextMode3--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 MaxiCodeStructuredCodetext 值。 |
| [getBarcodeType()](#getBarcodeType--) | 获取条形码类型。 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | 构造 codetext |
| [getCountryCode()](#getCountryCode--) | 识别 3 位国家代码。 |
| [getECIEncoding()](#getECIEncoding--) | 获取 ECI 编码。 |
| [getEncodeMode()](#getEncodeMode--) | 获取 MaxiCode 编码模式。 |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | 获取 MaxiCode 编码模式。 |
| [getMode()](#getMode--) | 获取 MaxiCode 模式。 |
| [getPostalCode()](#getPostalCode--) | 识别邮政编码。 |
| [getSecondMessage()](#getSecondMessage--) | 识别条形码的第二条信息。 |
| [getServiceCategory()](#getServiceCategory--) | 识别 3 位服务类别。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 从构造的 codetext 初始化实例。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | 识别 3 位国家代码。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 设置 ECI 编码。 |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | 设置 MaxiCode 编码模式。 |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | 设置 MaxiCode 编码模式。 |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | 识别邮政编码。 |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | 识别条形码的第二条信息。 |
| [setServiceCategory(int value)](#setServiceCategory-int-) | 识别 3 位服务类别。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeCodetextMode3() {#MaxiCodeCodetextMode3--}
```
public MaxiCodeCodetextMode3()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 MaxiCodeStructuredCodetext 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 MaxiCodeStructuredCodetext 值。 |

**Returns:**
布尔型 - **true** 表示 obj 与此实例具有相同的值；否则为 **false**。
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


获取条形码类型。

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


构造 codetext

**Returns:**
java.lang.String - 已构建的编码文本
### getCountryCode() {#getCountryCode--}
```
public int getCountryCode()
```


识别 3 位国家代码。

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


获取 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Returns:**
int - ECI 编码。
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


获取 MaxiCode 编码模式。默认值：Auto。

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


获取 MaxiCode 编码模式。默认值：Auto。

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public int getMode()
```


获取 MaxiCode 模式。

**Returns:**
int - MaxiCode 模式
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


标识邮政编码。模式 2 时必须为 9 位数字，模式 3 时必须为 6 个字母数字符号。

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public MaxiCodeSecondMessage getSecondMessage()
```


识别条形码的第二条信息。

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public int getServiceCategory()
```


识别 3 位服务类别。

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


从构造的 codetext 初始化实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 已构建的编码文本。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCountryCode(int value) {#setCountryCode-int-}
```
public void setCountryCode(int value)
```


识别 3 位国家代码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


设置 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | ECI 编码。 |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


设置 MaxiCode 编码模式。默认值：Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | 一个 MaxiCode 编码模式。 |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


设置 MaxiCode 编码模式。默认值：Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | 一个 MaxiCode 编码模式。 |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


标识邮政编码。模式 2 时必须为 9 位数字，模式 3 时必须为 6 个字母数字符号。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public void setSecondMessage(MaxiCodeSecondMessage value)
```


识别条形码的第二条信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public void setServiceCategory(int value)
```


识别 3 位服务类别。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

