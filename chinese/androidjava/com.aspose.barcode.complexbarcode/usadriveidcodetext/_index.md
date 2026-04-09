---
title: USADriveIdCodetext
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 用于对嵌入 USA Driving License PDF417 代码中的文本进行编码和解码的类。
type: docs
weight: 38
url: /zh/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

用于对嵌入 USA Driving License PDF417 代码中的文本进行编码和解码的类。
## Constructors

| Constructor | 描述 |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | 默认构造函数 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | AAMVA 版本号 00-99 |
| [getBarcodeType()](#getBarcodeType--) | 返回 USA 驾驶执照（Pdf417）的条码类型 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | 从 USA 驾驶执照数据构建编码文本 |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | 此号码唯一标识发行司法辖区，可通过联系 ISO 发行机构（AAMVA）获取。 |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | 司法辖区特定字段 |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | 司法辖区版本号 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | 卡片的必填元素（字段） |
| [getNumberOfEntries()](#getNumberOfEntries--) | 子文件的数量 00-99 |
| [getOptionalElements()](#getOptionalElements--) | 卡片的可选元素（字段） |
| [getSubfileDesignator()](#getSubfileDesignator--) | 包含以下子文件、类型、偏移量和长度的信息。 |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 从编码文本初始化 USA 驾驶执照对象 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | 保存为 XML |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | AAMVA 版本号 00-99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | 此号码唯一标识发行司法辖区，可通过联系 ISO 发行机构（AAMVA）获取。 |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | 司法辖区特定字段 |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | 司法辖区版本号 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | 卡片的必填元素（字段） |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | 子文件的数量 00-99 |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | 卡片的可选元素（字段） |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | 包含以下子文件、类型、偏移量和长度的信息。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


默认构造函数

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


AAMVA 版本号 00-99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


返回 USA 驾驶执照（Pdf417）的条码类型

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


从 USA 驾驶执照数据构建编码文本

**Returns:**
java.lang.String - 已构建的编码文本
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


此号码唯一标识发行司法辖区，可通过联系 ISO 发行机构（AAMVA）获取。应对完整的6位 IIN 进行编码。

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


司法辖区特定字段

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


司法辖区版本号 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


卡片的必填元素（字段）

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


子文件的数量 00-99

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


卡片的可选元素（字段）

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


包含以下子文件、类型、偏移量和长度的信息。重要提示：仅设置类型，偏移量和长度将自动设置。

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


从编码文本初始化 USA 驾驶执照对象

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 构建的代码文本 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


保存为 XML

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 保存的流 |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


AAMVA 版本号 00-99

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


此号码唯一标识发行司法辖区，可通过联系 ISO 发行机构（AAMVA）获取。应对完整的6位 IIN 进行编码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


司法辖区特定字段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


司法辖区版本号 00-99

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


卡片的必填元素（字段）

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


子文件的数量 00-99

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


卡片的可选元素（字段）

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


包含以下子文件、类型、偏移量和长度的信息。重要提示：仅设置类型，偏移量和长度将自动设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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

