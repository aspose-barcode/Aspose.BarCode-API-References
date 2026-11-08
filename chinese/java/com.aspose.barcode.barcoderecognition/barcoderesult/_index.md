---
title: "BarCodeResult"
second_title: "Aspose.BarCode for Java API Reference"
description: "存储已识别的条形码数据，如 SingleDecodeType 类型、字符串 codetext、BarCodeRegionParameters 区域以及其他参数"
type: docs
weight: 17
url: /zh/java/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

存储已识别条形码数据，如 SingleDecodeType 类型、string codetext、BarCodeRegionParameters 区域以及其他参数

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | 创建 BarCodeResult 类的副本。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建 BarCodeResult 类的副本。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 BarCodeResult 值。 |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | 获取已编码的代码字节 |
| [getCodeText()](#getCodeText--) | 获取代码文本 |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | 获取带有编码的代码文本。 |
| [getCodeType()](#getCodeType--) | 获取条形码类型 |
| [getCodeTypeName()](#getCodeTypeName--) | 获取条形码类型的名称 |
| [getConfidence()](#getConfidence--) | 获取已识别条形码的识别置信度水平 |
| [getExtended()](#getExtended--) | 获取已识别条形码的扩展参数 |
| [getReadingQuality()](#getReadingQuality--) | 获取读取质量。 |
| [getRegion()](#getRegion--) | 获取条形码区域 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此 BarCodeResult 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


创建 BarCodeResult 类的副本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | 一个 BarCodeResult 副本实例。 |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建 BarCodeResult 类的副本。

**Returns:**
java.lang.Object - 返回 BarCodeResult 类的副本。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 BarCodeResult 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 一个用于与此实例比较的 BarCodeResult 值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则，  **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


获取已编码的代码字节

值：条形码的代码字节

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


获取代码文本

值：条形码的代码文本

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


获取带有编码的代码文本。

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| charset | java.nio.charset.Charset | codetext 的编码。 |

**Returns:**
java.lang.String - 包含已识别代码文本的字符串。
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


获取条形码类型

Value: 已识别条形码的类型信息

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


获取条形码类型的名称

Value: 已识别条形码的类型名称

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


获取已识别条形码的识别置信度水平

Value:  BarCodeConfidence.Strong  不会出现伪造或误识别，  BarCodeConfidence.Moderate  可能有时会出现伪造或不正确的代码文本，因为此置信度水平适用于校验和弱或甚至没有校验和的条形码，  BarCodeConfidence.None  总是产生不正确的代码文本，可能是伪识别。

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


获取已识别条形码的扩展参数

Value: 已识别条形码的扩展参数

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


获取读取质量。适用于 1D 和邮政条形码。

Value: 读取质量百分比

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


获取条形码区域

Value: 已识别条形码的区域

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
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


返回此 BarCodeResult 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此  BarCodeResult  的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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
| arg1 | int |  |

