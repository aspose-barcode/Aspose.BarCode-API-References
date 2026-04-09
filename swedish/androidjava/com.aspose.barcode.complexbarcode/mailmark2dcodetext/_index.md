---
title: Mailmark2DCodetext
second_title: Aspose.BarCode for Android via Java API-referens
description: Klass för kodning och avkodning av text som är inbäddad i Royal Mail 2D Mailmark‑koden.
type: docs
weight: 23
url: /sv/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Klass för kodning och avkodning av text som är inbäddad i Royal Mail 2D Mailmark‑koden.
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Hämtar streckkodstyp. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | Flagga som indikerar vilken nivå av Return to Sender-tjänsten som begärs. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Innehåller Return to Sender-postkoden men ingen DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifierar den unika gruppen av kunder som är involverade i utskicket. |
| [getUPUCountryID()](#getUPUCountryID--) | Identifierar UPU-land-ID. Maxlängd: 4 tecken. |
| [getVersionID()](#getVersionID--) | Identifierar streckkodsversionen som är relevant för varje informations-typ-ID. |
| [getclass()](#getclass--) | Identifierar objektets klass. |
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
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Flagga som indikerar vilken nivå av Return to Sender-tjänsten som begärs. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Innehåller Return to Sender-postkoden men ingen DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifierar den unika gruppen av kunder som är involverade i utskicket. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifierar UPU-land-ID. Maxlängd: 4 tecken. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Identifierar streckkodsversionen som är relevant för varje informations-typ-ID. |
| [setclass(String value)](#setclass-java.lang.String-) | Identifierar objektets klass. |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Hämtar streckkodstyp.

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
java.lang.String - Konstruerad kodtext
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Valfritt utrymme för kundens bruk. Maxlängd per typ: Typ 7: 6 tecken Typ 9: 45 tecken Typ 29: 25 tecken

**Returns:**
java.lang.String - Kundinnehåll
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Kodningsläge för Datamatrix-streckkod. Standardvärde: DataMatrixEncodeMode.C40.

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


Innehåller postnumret för leveransadressen med DPS. Om inlandet innehåller postnumret/DP följande antal tecken: Område (1 eller 2 tecken) Distrikt (1 eller 2 tecken) Sektor (1 tecken) Enhet (2 tecken) DPS (2 tecken). Postnumret och DPS måste följa ett giltigt PAF®-format.

**Returns:**
java.lang.String - postnumret för leveransadressen med DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Identifierar Royal Mail Mailmark-streckkodens nyttolast för varje produkttyp. Giltiga värden: '0' - Inrikes sorterad & osorterad 'A' - Onlinepostering 'B' - Franking 'C' - Konsolidering

**Returns:**
java.lang.String - informations-typ-ID
### getItemID() {#getItemID--}
```
public int getItemID()
```


Identifierar det unika objektet inom Supply Chain-ID. Varje Mailmark-streckkod måste bära ett ID så att det kan identifieras unikt i minst 90 dagar. Maxvärde: 99999999.

**Returns:**
int - objekt inom Supply Chain-ID
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Flagga som indikerar vilken nivå av Return to Sender-tjänsten som begärs.

**Returns:**
java.lang.String - RTS-flagga
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Innehåller Return to Sender-postkoden men ingen DPS. PC:n (utan DPS) måste följa ett PAF®-format.

**Returns:**
java.lang.String - Return to Sender-postkod men ingen DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Identifierar den unika gruppen av kunder som är involverade i utskicket. Maxvärde: 9999999.

**Returns:**
int - Supply chain-ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Identifierar UPU-land-ID. Maxlängd: 4 tecken.

**Returns:**
java.lang.String - land-ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Identifierar streckkodsversionen som är relevant för varje informations-typ-ID. Giltiga värden: För närvarande '1'. '0' samt '2' till '9' och 'A' till 'Z' är reserverade för potentiell framtida användning.

**Returns:**
java.lang.String - versions-ID
### getclass() {#getclass--}
```
public String getclass()
```


Identifierar objektets klass. Giltiga värden: '1' - 1C (Detaljhandel) '2' - 2C (Detaljhandel) '3' - Ekonomi (Detaljhandel) '5' - Uppskjuten (Detaljhandel) '8' - Premium (Nätverksåtkomst) '9' - Standard (Nätverksåtkomst)

**Returns:**
java.lang.String - klass av objektet
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruerad kodtext. |

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


Valfritt utrymme för kundens bruk. Maxlängd per typ: Typ 7: 6 tecken Typ 9: 45 tecken Typ 29: 25 tecken

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.C40.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Innehåller postnumret för leveransadressen med DPS. Om inlandet innehåller postnumret/DP följande antal tecken: Område (1 eller 2 tecken) Distrikt (1 eller 2 tecken) Sektor (1 tecken) Enhet (2 tecken) DPS (2 tecken). Postnumret och DPS måste följa ett giltigt PAF®-format.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Identifierar Royal Mail Mailmark-streckkodens nyttolast för varje produkttyp. Giltiga värden: '0' - Inrikes sorterad & osorterad 'A' - Onlinepostering 'B' - Franking 'C' - Konsolidering

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Identifierar det unika objektet inom Supply Chain-ID. Varje Mailmark-streckkod måste bära ett ID så att det kan identifieras unikt i minst 90 dagar. Maxvärde: 99999999.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Flagga som indikerar vilken nivå av Return to Sender-tjänsten som begärs.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Innehåller Return to Sender-postkoden men ingen DPS. PC:n (utan DPS) måste följa ett PAF®-format.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Identifierar den unika gruppen av kunder som är involverade i utskicket. Maxvärde: 9999999.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Identifierar UPU-land-ID. Maxlängd: 4 tecken.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Identifierar streckkodsversionen som är relevant för varje informations-typ-ID. Giltiga värden: För närvarande '1'. '0' samt '2' till '9' och 'A' till 'Z' är reserverade för potentiell framtida användning.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Identifierar objektets klass. Giltiga värden: '1' - 1C (Detaljhandel) '2' - 2C (Detaljhandel) '3' - Ekonomi (Detaljhandel) '5' - Uppskjuten (Detaljhandel) '8' - Premium (Nätverksåtkomst) '9' - Standard (Nätverksåtkomst)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | class of the item |

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

