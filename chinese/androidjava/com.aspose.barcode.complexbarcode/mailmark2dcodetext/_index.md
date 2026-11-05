---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "用于对嵌入 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类。"
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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | 创建 Mailmark2DCodetext 类的默认实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | 获取条形码类型。 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | 从 Mailmark 数据构造代码文本。 |
| [getCustomerContent()](#getCustomerContent--) | 供客户使用的可选空间。 |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Datamatrix 条形码的编码模式。 |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark 类型定义 Data Matrix 条形码的大小。 |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | 包含带有 DPS 的收货地址邮编；如果是内陆地区，邮编/DP 包含以下字符数。 |
| [getInformationTypeID()](#getInformationTypeID--) | 标识每种产品类型的皇家邮政 Mailmark 条形码负载。 |
| [getItemID()](#getItemID--) | 标识供应链 ID 中的唯一项目。 |
| [getRTSFlag()](#getRTSFlag--) | 指示请求的退回寄件人服务级别的标志。 |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | 包含退回寄件人邮编，但不含 DPS。 |
| [getSupplyChainID()](#getSupplyChainID--) | 标识参与邮件发送的唯一客户组。 |
| [getUPUCountryID()](#getUPUCountryID--) | 标识 UPU 国家 ID。最大长度：4 个字符。 |
| [getVersionID()](#getVersionID--) | 标识与每个信息类型 ID 相关的条形码版本。 |
| [getclass()](#getclass--) | 标识项目的类别。 |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 从构造的代码文本初始化 Mailmark 数据。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | 供客户使用的可选空间。 |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix 条形码的编码模式。 |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark 类型定义 Data Matrix 条形码的大小。 |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | 包含带有 DPS 的收货地址邮编；如果是内陆地区，邮编/DP 包含以下字符数。 |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | 标识每种产品类型的皇家邮政 Mailmark 条形码负载。 |
| [setItemID(int value)](#setItemID-int-) | 标识供应链 ID 中的唯一项目。 |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | 指示请求的退回寄件人服务级别的标志。 |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | 包含退回寄件人邮编，但不含 DPS。 |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | 标识参与邮件发送的唯一客户组。 |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | 标识 UPU 国家 ID。最大长度：4 个字符。 |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | 标识与每个信息类型 ID 相关的条形码版本。 |
| [setclass(String value)](#setclass-java.lang.String-) | 标识项目的类别。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


创建 Mailmark2DCodetext 类的默认实例。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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


从 Mailmark 数据构造代码文本。

**Returns:**
java.lang.String - 已构建的 codetext
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


供客户使用的可选空间。按类型的最大长度：类型 7：6 个字符，类型 9：45 个字符，类型 29：25 个字符

**Returns:**
java.lang.String - 客户内容
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Datamatrix 条形码的编码模式。默认值：DataMatrixEncodeMode.C40。

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark 类型定义 Data Matrix 条形码的大小。

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


包含带 DPS 的送货地址邮编。如果是内陆，邮编/DP 包含以下字符数：地区（1 或 2 个字符） 区（1 或 2 个字符） 部分（1 个字符） 单元（2 个字符） DPS（2 个字符）。邮编和 DPS 必须符合有效的 PAF® 格式。

**Returns:**
java.lang.String - 带 DPS 的送货地址邮编
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


标识每种产品类型的皇家邮政 Mailmark 条形码负载。有效值：'0' - 国内已分拣和未分拣，'A' - 在线邮资，'B' - 贴票，'C' - 合并

**Returns:**
java.lang.String - 信息类型 ID
### getItemID() {#getItemID--}
```
public int getItemID()
```


标识供应链 ID 中的唯一项目。每个 Mailmark 条形码必须携带一个 ID，以便在至少 90 天内唯一识别。最大值：99999999。

**Returns:**
int - 供应链 ID 中的项目
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


指示请求的退回寄件人服务级别的标志。

**Returns:**
java.lang.String - RTS 标志
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


包含退回寄件人邮编，但不含 DPS。该邮编（不含 DPS）必须符合 PAF® 格式。

**Returns:**
java.lang.String - 退回寄件人邮编（不含 DPS）
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


标识参与邮件发送的唯一客户组。最大值：9999999。

**Returns:**
int - 供应链 ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


标识 UPU 国家 ID。最大长度：4 个字符。

**Returns:**
java.lang.String - 国家 ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


标识与每个信息类型 ID 相关的条形码版本。有效值：当前为 '1'。'0' 和 '2' 到 '9' 以及 'A' 到 'Z' 预留供未来潜在使用。

**Returns:**
java.lang.String - 版本 ID
### getclass() {#getclass--}
```
public String getclass()
```


标识项目的类别。有效值：'1' - 1C（零售），'2' - 2C（零售），'3' - 经济型（零售），'5' - 延迟（零售），'8' - 高级（网络访问），'9' - 标准（网络访问）

**Returns:**
java.lang.String - 项目的类别
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
整数
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


从构造的代码文本初始化 Mailmark 数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 已构建的 codetext。 |

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


供客户使用的可选空间。按类型的最大长度：类型 7：6 个字符，类型 9：45 个字符，类型 29：25 个字符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 客户内容 |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix 条形码的编码模式。默认值：EncodeMode.C40。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Datamatrix 条形码的编码模式。 |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark 类型定义 Data Matrix 条形码的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Data Matrix 条形码的尺寸 |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


包含带 DPS 的送货地址邮编。如果是内陆，邮编/DP 包含以下字符数：地区（1 或 2 个字符） 区（1 或 2 个字符） 部分（1 个字符） 单元（2 个字符） DPS（2 个字符）。邮编和 DPS 必须符合有效的 PAF® 格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 带 DPS 的送货地址邮编 |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


标识每种产品类型的皇家邮政 Mailmark 条形码负载。有效值：'0' - 国内已分拣和未分拣，'A' - 在线邮资，'B' - 贴票，'C' - 合并

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 信息类型 ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


标识供应链 ID 中的唯一项目。每个 Mailmark 条形码必须携带一个 ID，以便在至少 90 天内唯一识别。最大值：99999999。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 | 供应链 ID 中的项目 |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


指示请求的退回寄件人服务级别的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


包含退回寄件人邮编，但不含 DPS。该邮编（不含 DPS）必须符合 PAF® 格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 返回发件人邮编，但无 DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


标识参与邮件发送的唯一客户组。最大值：9999999。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 | 供应链 ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


标识 UPU 国家 ID。最大长度：4 个字符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 国家 ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


标识与每个信息类型 ID 相关的条形码版本。有效值：当前为 '1'。'0' 和 '2' 到 '9' 以及 'A' 到 'Z' 预留供未来潜在使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 版本 ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


标识项目的类别。有效值：'1' - 1C（零售），'2' - 2C（零售），'3' - 经济型（零售），'5' - 延迟（零售），'8' - 高级（网络访问），'9' - 标准（网络访问）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 项目的类 |

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

