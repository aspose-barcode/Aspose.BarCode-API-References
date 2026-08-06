---
title: Mailmark2DCodetext
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 用于对嵌入 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类。
type: docs
weight: 23
url: /zh/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

用于对嵌入 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类。
## Constructors

| Constructor | 描述 |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | 获取条形码类型。 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | 标志，指示请求的退回寄件服务级别。 |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | 包含退回寄件邮编，但不含DPS。 |
| [getSupplyChainID()](#getSupplyChainID--) | 标识参与邮件投递的唯一客户组。 |
| [getUPUCountryID()](#getUPUCountryID--) | 标识UPU国家ID。最大长度：4个字符。 |
| [getVersionID()](#getVersionID--) | 标识与每个信息类型ID相关的条码版本。 |
| [getclass()](#getclass--) | 标识项目的类别。 |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Mailmark data from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optional space for use by customer. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [setItemID(int value)](#setItemID-int-) | Identifies the unique item within the Supply Chain ID. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | 标志，指示请求的退回寄件服务级别。 |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | 包含退回寄件邮编，但不含DPS。 |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | 标识参与邮件投递的唯一客户组。 |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | 标识UPU国家ID。最大长度：4个字符。 |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | 标识与每个信息类型ID相关的条码版本。 |
| [setclass(String value)](#setclass-java.lang.String-) | 标识项目的类别。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Create default instance of Mailmark2DCodetext class.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
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


Construct codetext from Mailmark data.

**Returns:**
java.lang.String - 已构建的编码文本
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


供客户使用的可选空间。各类型的最大长度：类型7：6个字符，类型9：45个字符，类型29：25个字符。

**Returns:**
java.lang.String - 客户内容
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Datamatrix条码的编码模式。默认值：DataMatrixEncodeMode.C40。

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark Type defines size of Data Matrix barcode.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


包含带DPS的收件地址邮编。如果是内陆，邮编/DP包含以下字符数：地区（1或2个字符） 区（1或2个字符） 扇区（1个字符） 单元（2个字符） DPS（2个字符）。邮编和DPS必须符合有效的PAF®格式。

**Returns:**
java.lang.String - 带DPS的收件地址邮编
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


标识每种产品类型的Royal Mail Mailmark条码负载。有效值：'0' - 国内已分拣和未分拣，'A' - 在线邮资，'B' - 贴票，'C' - 合并。

**Returns:**
java.lang.String - 信息类型ID
### getItemID() {#getItemID--}
```
public int getItemID()
```


标识供应链ID内的唯一项目。每个Mailmark条码必须携带一个ID，以便在至少90天内唯一识别。最大值：99999999。

**Returns:**
int - 供应链ID内的项目
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


标志，指示请求的退回寄件服务级别。

**Returns:**
java.lang.String - RTS标志
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


包含退回寄件邮编，但不含DPS。该邮编（不含DPS）必须符合PAF®格式。

**Returns:**
java.lang.String - 退回寄件邮编（不含DPS）
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


标识参与邮件投递的唯一客户组。最大值：9999999。

**Returns:**
int - 供应链ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


标识UPU国家ID。最大长度：4个字符。

**Returns:**
java.lang.String - 国家ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


标识与每个信息类型ID相关的条码版本。有效值：当前为'1'。'0'以及'2'到'9'和'A'到'Z'保留供未来潜在使用。

**Returns:**
java.lang.String - 版本ID
### getclass() {#getclass--}
```
public String getclass()
```


标识项目的类别。有效值：'1' - 1C（零售），'2' - 2C（零售），'3' - 经济型（零售），'5' - 延期（零售），'8' - 高级（网络访问），'9' - 标准（网络访问）。

**Returns:**
java.lang.String - 项目的类别
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initializes Mailmark data from constructed codetext.

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




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


供客户使用的可选空间。各类型的最大长度：类型7：6个字符，类型9：45个字符，类型29：25个字符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.C40.

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


包含带DPS的收件地址邮编。如果是内陆，邮编/DP包含以下字符数：地区（1或2个字符） 区（1或2个字符） 扇区（1个字符） 单元（2个字符） DPS（2个字符）。邮编和DPS必须符合有效的PAF®格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


标识每种产品类型的Royal Mail Mailmark条码负载。有效值：'0' - 国内已分拣和未分拣，'A' - 在线邮资，'B' - 贴票，'C' - 合并。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


标识供应链ID内的唯一项目。每个Mailmark条码必须携带一个ID，以便在至少90天内唯一识别。最大值：99999999。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


标志，指示请求的退回寄件服务级别。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


包含退回寄件邮编，但不含DPS。该邮编（不含DPS）必须符合PAF®格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


标识参与邮件投递的唯一客户组。最大值：9999999。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


标识UPU国家ID。最大长度：4个字符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


标识与每个信息类型ID相关的条码版本。有效值：当前为'1'。'0'以及'2'到'9'和'A'到'Z'保留供未来潜在使用。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


标识项目的类别。有效值：'1' - 1C（零售），'2' - 2C（零售），'3' - 经济型（零售），'5' - 延期（零售），'8' - 高级（网络访问），'9' - 标准（网络访问）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | class of the item |

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

