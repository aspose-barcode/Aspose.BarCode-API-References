---
title: "BarCodeExtendedParameters"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "存储已识别条码的扩展参数"
type: docs
weight: 13
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/barcodeextendedparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeExtendedParameters
```

存储已识别条码的扩展参数
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 BarCodeExtendedParameters 值。 |
| [getAztec()](#getAztec--) | 获取已识别条码的 Aztec 附加信息 AztecExtendedParameters。 |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | 获取已识别条码的 Codabar 附加信息 CodabarExtendedParameters。 |
| [getCode128()](#getCode128--) | 获取 Code128 已识别条码的特殊数据 Code128ExtendedParameters。 |
| [getDataBar()](#getDataBar--) | 获取已识别条码的 DataBar 附加信息 DataBarExtendedParameters。 |
| [getDataMatrix()](#getDataMatrix--) | 获取已识别条码的 DataMatrix 附加信息 DataMatrixExtendedParameters。 |
| [getDotCode()](#getDotCode--) | 获取已识别条码的 DataMatrix 附加信息 DotCodeExtendedParameters。 |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | 获取已识别条码的 GS1CompositeBar 附加信息 GS1CompositeBarExtendedParameters。 |
| [getMaxiCode()](#getMaxiCode--) | 获取已识别条码的 MaxiCode 附加信息 MaxiCodeExtendedParameters。 |
| [getOneD()](#getOneD--) | 获取 1D 已识别条码的特殊数据 OneDExtendedParameters。 |
| [getPdf417()](#getPdf417--) | 获取已识别条码的 MacroPdf417 元数据信息 Pdf417ExtendedParameters。 |
| [getQR()](#getQR--) | 获取已识别条码的 QR 结构化追加信息 QRExtendedParameters。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此 BarCodeExtendedParameters 的可读字符串表示形式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 BarCodeExtendedParameters 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 System.Object 值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则，  **false** 。
### getAztec() {#getAztec--}
```
public AztecExtendedParameters getAztec()
```


获取已识别条码的 Aztec 附加信息 AztecExtendedParameters。

值：已识别条码的 Aztec 附加信息 AztecExtendedParameters。

**Returns:**
com.aspose.barcode.barcoderecognition.AztecExtendedParameters
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodabar() {#getCodabar--}
```
public CodabarExtendedParameters getCodabar()
```


获取已识别条码的 Codabar 附加信息 CodabarExtendedParameters。

**Returns:**
[CodabarExtendedParameters](../../com.aspose.barcode.barcoderecognition/codabarextendedparameters) - A Codabar additional information CodabarExtendedParameters  of recognized barcode
### getCode128() {#getCode128--}
```
public Code128ExtendedParameters getCode128()
```


获取 Code128 已识别条码的特殊数据 Code128ExtendedParameters。

值：Code128 已识别条码的特殊数据 Code128ExtendedParameters。

**Returns:**
[Code128ExtendedParameters](../../com.aspose.barcode.barcoderecognition/code128extendedparameters)
### getDataBar() {#getDataBar--}
```
public DataBarExtendedParameters getDataBar()
```


获取已识别条码的 DataBar 附加信息 DataBarExtendedParameters。

**Returns:**
[DataBarExtendedParameters](../../com.aspose.barcode.barcoderecognition/databarextendedparameters) - A DataBar additional informationDataBarExtendedParameters of recognized barcode
### getDataMatrix() {#getDataMatrix--}
```
public DataMatrixExtendedParameters getDataMatrix()
```


获取已识别条码的 DataMatrix 附加信息 DataMatrixExtendedParameters。

值：已识别条码的 DataMatrix 附加信息 DataMatrixExtendedParameters。

**Returns:**
[DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters)
### getDotCode() {#getDotCode--}
```
public DotCodeExtendedParameters getDotCode()
```


获取已识别条码的 DataMatrix 附加信息 DotCodeExtendedParameters。

值：已识别条码的 DotCode 附加信息 DotCodeExtendedParameters。

**Returns:**
[DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public GS1CompositeBarExtendedParameters getGS1CompositeBar()
```


获取已识别条码的 GS1CompositeBar 附加信息 GS1CompositeBarExtendedParameters。

值：已识别条码的 GS1CompositeBar 附加信息 GS1CompositeBarExtendedParameters。

**Returns:**
com.aspose.barcode.barcoderecognition.GS1CompositeBarExtendedParameters
### getMaxiCode() {#getMaxiCode--}
```
public MaxiCodeExtendedParameters getMaxiCode()
```


获取已识别条码的 MaxiCode 附加信息 MaxiCodeExtendedParameters。

**Returns:**
[MaxiCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) - A MaxiCode additional information MaxiCodeExtendedParameters of recognized barcode
### getOneD() {#getOneD--}
```
public OneDExtendedParameters getOneD()
```


获取 1D 已识别条码的特殊数据 OneDExtendedParameters。

值：1D 已识别条码的特殊数据 OneDExtendedParameters。

**Returns:**
[OneDExtendedParameters](../../com.aspose.barcode.barcoderecognition/onedextendedparameters)
### getPdf417() {#getPdf417--}
```
public Pdf417ExtendedParameters getPdf417()
```


获取已识别条码的 MacroPdf417 元数据信息 Pdf417ExtendedParameters。

值：已识别条码的 MacroPdf417 元数据信息 Pdf417ExtendedParameters。

**Returns:**
[Pdf417ExtendedParameters](../../com.aspose.barcode.barcoderecognition/pdf417extendedparameters)
### getQR() {#getQR--}
```
public QRExtendedParameters getQR()
```


获取已识别条码的 QR 结构化追加信息 QRExtendedParameters。

值：已识别条形码的 QR 结构化追加信息 QRExtendedParameters

**Returns:**
[QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)
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


返回此 BarCodeExtendedParameters 的可读字符串表示形式。

**Returns:**
java.lang.String - 表示此 BarCodeExtendedParameters 的字符串。
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

