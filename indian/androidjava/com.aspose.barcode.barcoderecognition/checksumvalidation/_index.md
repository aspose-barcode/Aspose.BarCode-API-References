---
title: ChecksumValidation
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 
type: docs
weight: 52
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/checksumvalidation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChecksumValidation extends Enum<ChecksumValidation>
```

1D और पोस्टल बारकोड्स की पहचान के दौरान चेकसम वैधता सक्षम करें।

डिफ़ॉल्ट रूप से उन सिम्बोलॉजीज़ के लिए Yes माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ No माना जाता है।

चेकसम कभी उपयोग नहीं किया जाता: Codabar, PatchCode, Pharmacode, DataLogic2of5

चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

चेकसम हमेशा उपयोग किया जाता है: शेष सिम्बोलॉजीज़

--------------------

> ```
> This sample shows influence of ChecksumValidation on recognition quality and results
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
>  {
>      generator.save("test.png");
>  }
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.EAN_13))
>  {
>      //checksum disabled
>      reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue());
>          System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
>      }
>  }
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.EAN_13);
>  //checksum enabled
>  reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue());
>     System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
>  }
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DEFAULT](#DEFAULT) | यदि विनिर्देश द्वारा चेकसम आवश्यक है - इसे मान्य किया जाएगा। |
| [OFF](#OFF) | चेकसम को मान्य न करें। |
| [ON](#ON) | यदि संभव हो तो हमेशा चेकसम को मान्य करें। |
## Methods

| Method | विवरण |
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
### DEFAULT {#DEFAULT}
```
public static final ChecksumValidation DEFAULT
```


यदि विनिर्देश द्वारा चेकसम आवश्यक है - इसे मान्य किया जाएगा।

### OFF {#OFF}
```
public static final ChecksumValidation OFF
```


चेकसम को मान्य न करें।

### ON {#ON}
```
public static final ChecksumValidation ON
```


यदि संभव हो तो हमेशा चेकसम को मान्य करें।

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
public static ChecksumValidation valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation)
### values() {#values--}
```
public static ChecksumValidation[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.ChecksumValidation[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

