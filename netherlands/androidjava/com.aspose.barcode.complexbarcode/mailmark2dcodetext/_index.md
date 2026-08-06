---
title: Mailmark2DCodetext
second_title: Aspose.BarCode for Android via Java API-referentie
description: Klasse voor het coderen en decoderen van de tekst die is ingebed in de Royal Mail 2D Mailmark-code.
type: docs
weight: 23
url: /nl/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Klasse voor het coderen en decoderen van de tekst die is ingebed in de Royal Mail 2D Mailmark-code.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Haalt barcode‑type op. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Bevat de Return to Sender-postcode maar geen DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Identificeert de unieke groep klanten die bij de verzending betrokken zijn. |
| [getUPUCountryID()](#getUPUCountryID--) | Identificeert de UPU Country ID. Maximale lengte: 4 tekens. |
| [getVersionID()](#getVersionID--) | Identificeert de barcodeversie die relevant is voor elke Information Type ID. |
| [getclass()](#getclass--) | Identificeert de klasse van het item. |
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
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Bevat de Return to Sender-postcode maar geen DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identificeert de unieke groep klanten die bij de verzending betrokken zijn. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identificeert de UPU Country ID. Maximale lengte: 4 tekens. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Identificeert de barcodeversie die relevant is voor elke Information Type ID. |
| [setclass(String value)](#setclass-java.lang.String-) | Identificeert de klasse van het item. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Haalt barcode‑type op.

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
java.lang.String - Gemaakt codetext
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Optionele ruimte voor gebruik door de klant. Maximale lengte per type: Type 7: 6 tekens Type 9: 45 tekens Type 29: 25 tekens

**Returns:**
java.lang.String - Klantinformatie
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Coderingsmodus van Datamatrix-barcode. Standaardwaarde: DataMatrixEncodeMode.C40.

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


Bevat de postcode van het afleveradres met DPS. Als het binnenland betreft, bevat de postcode/DP het volgende aantal tekens. Gebied (1 of 2 tekens) District (1 of 2 tekens) Sector (1 teken) Eenheid (2 tekens) DPS (2 tekens). De postcode en DPS moeten voldoen aan een geldig PAF®-formaat.

**Returns:**
java.lang.String - de postcode van het afleveradres met DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Identificeert de Royal Mail Mailmark-barcodepayload voor elk producttype. Geldige waarden: '0' - Binnenlands gesorteerd & ongesorteerd 'A' - Online postzegel 'B' - Frankering 'C' - Consolidatie

**Returns:**
java.lang.String - Information type ID
### getItemID() {#getItemID--}
```
public int getItemID()
```


Identificeert het unieke item binnen de Supply Chain ID. Elke Mailmark-barcode moet een ID dragen zodat het gedurende ten minste 90 dagen uniek geïdentificeerd kan worden. Maximale waarde: 99999999.

**Returns:**
int - item binnen de Supply Chain ID
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd.

**Returns:**
java.lang.String - RTS-vlag
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Bevat de Return to Sender-postcode maar geen DPS. De PC (zonder DPS) moet voldoen aan een PAF®-formaat.

**Returns:**
java.lang.String - Return to Sender-postcode maar geen DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Identificeert de unieke groep klanten die bij de verzending betrokken zijn. Maximale waarde: 9999999.

**Returns:**
int - Supply chain ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Identificeert de UPU Country ID. Maximale lengte: 4 tekens.

**Returns:**
java.lang.String - Country ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Identificeert de barcodeversie die relevant is voor elke Information Type ID. Geldige waarden: momenteel '1'. '0' & '2' tot '9' en 'A' tot 'Z' gereserveerd voor mogelijk toekomstig gebruik.

**Returns:**
java.lang.String - Version ID
### getclass() {#getclass--}
```
public String getclass()
```


Identificeert de klasse van het item. Geldige waarden: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deferred (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Returns:**
java.lang.String - klasse van het item
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Gemaakt codetext. |

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


Optionele ruimte voor gebruik door de klant. Maximale lengte per type: Type 7: 6 tekens Type 9: 45 tekens Type 29: 25 tekens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.C40.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Bevat de postcode van het afleveradres met DPS. Als het binnenland betreft, bevat de postcode/DP het volgende aantal tekens. Gebied (1 of 2 tekens) District (1 of 2 tekens) Sector (1 teken) Eenheid (2 tekens) DPS (2 tekens). De postcode en DPS moeten voldoen aan een geldig PAF®-formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Identificeert de Royal Mail Mailmark-barcodepayload voor elk producttype. Geldige waarden: '0' - Binnenlands gesorteerd & ongesorteerd 'A' - Online postzegel 'B' - Frankering 'C' - Consolidatie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Identificeert het unieke item binnen de Supply Chain ID. Elke Mailmark-barcode moet een ID dragen zodat het gedurende ten minste 90 dagen uniek geïdentificeerd kan worden. Maximale waarde: 99999999.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Bevat de Return to Sender-postcode maar geen DPS. De PC (zonder DPS) moet voldoen aan een PAF®-formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Identificeert de unieke groep klanten die bij de verzending betrokken zijn. Maximale waarde: 9999999.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Identificeert de UPU Country ID. Maximale lengte: 4 tekens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Identificeert de barcodeversie die relevant is voor elke Information Type ID. Geldige waarden: momenteel '1'. '0' & '2' tot '9' en 'A' tot 'Z' gereserveerd voor mogelijk toekomstig gebruik.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Identificeert de klasse van het item. Geldige waarden: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deferred (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | class of the item |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

