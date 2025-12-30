---
title: Mailmark2DCodetext
second_title: Aspose.BarCode for Android via Java API Reference
description: Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code.
type: docs
weight: 23
url: /androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code.
## Constructors

| Constructor | Description |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Gets barcode type. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | Flag which indicates what level of Return to Sender service is being requested. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Contains the Return to Sender Post Code but no DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifies the unique group of customers involved in the mailing. |
| [getUPUCountryID()](#getUPUCountryID--) | Identifies the UPU Country ID.Max length: 4 characters. |
| [getVersionID()](#getVersionID--) | Identifies the barcode version as relevant to each Information Type ID. |
| [getclass()](#getclass--) | Identifies the class of the item. |
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
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Flag which indicates what level of Return to Sender service is being requested. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Contains the Return to Sender Post Code but no DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifies the unique group of customers involved in the mailing. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifies the UPU Country ID.Max length: 4 characters. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Identifies the barcode version as relevant to each Information Type ID. |
| [setclass(String value)](#setclass-java.lang.String-) | Identifies the class of the item. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Gets barcode type.

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
java.lang.String - Constructed codetext
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters

**Returns:**
java.lang.String - Customer content
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40.

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


Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format.

**Returns:**
java.lang.String - the Postcode of the Delivery Address with DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: '0' - Domestic Sorted & Unsorted 'A' - Online Postage 'B' - Franking 'C' - Consolidation

**Returns:**
java.lang.String - Information type ID
### getItemID() {#getItemID--}
```
public int getItemID()
```


Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999.

**Returns:**
int - item within the Supply Chain ID
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Flag which indicates what level of Return to Sender service is being requested.

**Returns:**
java.lang.String - RTS Flag
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format.

**Returns:**
java.lang.String - Return to Sender Post Code but no DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Identifies the unique group of customers involved in the mailing. Max value: 9999999.

**Returns:**
int - Supply chain ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Identifies the UPU Country ID.Max length: 4 characters.

**Returns:**
java.lang.String - Country ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently '1'. '0' & '2' to '9' and 'A' to 'Z' spare reserved for potential future use.

**Returns:**
java.lang.String - Version ID
### getclass() {#getclass--}
```
public String getclass()
```


Identifies the class of the item. Valid Values: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Returns:**
java.lang.String - class of the item
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
| Parameter | Type | Description |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Constructed codetext. |

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


Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: '0' - Domestic Sorted & Unsorted 'A' - Online Postage 'B' - Franking 'C' - Consolidation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Flag which indicates what level of Return to Sender service is being requested.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Identifies the unique group of customers involved in the mailing. Max value: 9999999.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Identifies the UPU Country ID.Max length: 4 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently '1'. '0' & '2' to '9' and 'A' to 'Z' spare reserved for potential future use.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Identifies the class of the item. Valid Values: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | class of the item |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

