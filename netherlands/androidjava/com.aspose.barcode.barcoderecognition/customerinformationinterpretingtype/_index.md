---
title: CustomerInformationInterpretingType
second_title: Aspose.BarCode for Android via Java API-referentie
description: Definieert het interpreteertype C_TABLE of N_TABLE van klantinformatie voor AustralianPost BarCode.
type: docs
weight: 54
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum CustomerInformationInterpretingType extends Enum<CustomerInformationInterpretingType>
```

Definieert het interpretatietype (C\_TABLE of N\_TABLE) van klantinformatie voor AustralianPost‑barcode.

Deze voorbeeld toont hoe een Australia Post-barcode te genereren en te herkennen met CTable Interpreting Type.

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde");
>   generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
>   Bitmap image = generator.generateBarCodeImage();
>   BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST);
>   reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
>   for(BarCodeResult result : reader.readBarCodes())
>   {
>       System.out.println("BarCode Type: " + result.getCodeType());
>       System.out.println("BarCode CodeText: " + result.getCodeText());
>   }
> ```

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456781234567"))
>   generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.N_TABLE);
>   Bitmap image = generator.generateBarCodeImage();
>   BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST))
>   reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.N_TABLE);
>   for(BarCodeResult result : reader.readBarCodes())
>   {
>       System.out.println("BarCode Type: " + result.getCodeType());
>       System.out.println("BarCode CodeText: " + result.getCodeText());
>   }
> ```

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "59123456780123012301230123");
>   generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.OTHER);
>   Bitmap image = generator.generateBarCodeImage();
>   BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST);
>   reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.OTHER);
>   for(BarCodeResult result : reader.readBarCodes())
>   {
>       System.out.println("BarCode Type: " + result.getCodeType());
>       System.out.println("BarCode CodeText: " + result.getCodeText());
>   }
> ```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [C_TABLE](#C-TABLE) | Gebruik C\_TABLE om de klantinformatie te interpreteren. |
| [N_TABLE](#N-TABLE) | Gebruik N\_TABLE om de klantinformatie te interpreteren. |
| [OTHER](#OTHER) | Interpreteer de klantinformatie niet. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### C_TABLE {#C-TABLE}
```
public static final CustomerInformationInterpretingType C_TABLE
```


Gebruik C\_TABLE om de klantinformatie te interpreteren. Staat A..Z, a..z, 1..9, spatie en \# teken toe.

### N_TABLE {#N-TABLE}
```
public static final CustomerInformationInterpretingType N_TABLE
```


Gebruik N\_TABLE om de klantinformatie te interpreteren. Staat cijfers toe.

### OTHER {#OTHER}
```
public static final CustomerInformationInterpretingType OTHER
```


Interpreteer de klantinformatie niet. Staat alleen het symbool 0, 1, 2 of 3 toe.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static CustomerInformationInterpretingType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype)
### values() {#values--}
```
public static CustomerInformationInterpretingType[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType[]
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

