---
title: "OneDExtendedParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Tanımlanan 1D barkodunun ayrı kod metni ve kontrol toplamı gibi özel verilerini depolar"
type: docs
weight: 37
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/onedextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class OneDExtendedParameters extends BaseExtendedParameters
```

Tanımlanan 1D barkodunun ayrı kod metni ve kontrol toplamı gibi özel verilerini depolar

--------------------

> ```
> This sample shows how to get 1D barcode value and checksum
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.EAN_13);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue());
>     System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
>  }
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen  OneDExtendedParameters  değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getCheckSum()](#getCheckSum--) | 1D barkodlar için sağlama toplamını alır. |
| [getClass()](#getClass--) |  |
| [getValue()](#getValue--) | Sağlama toplamı olmadan 1D barkodların kod metnini alır. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu  OneDExtendedParameters  nesnesinin insan tarafından okunabilir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen  OneDExtendedParameters  değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak bir System.Object değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


1D barkodlar için sağlama toplamını alır.

Değer: 1D barkod için sağlama toplamı.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getValue() {#getValue--}
```
public String getValue()
```


Sağlama toplamı olmadan 1D barkodların kod metnini alır.

Değer: Sağlama toplamı olmadan 1D barkodların kod metni.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder

Değer: Tüm parametrelerin yalnızca varsayılan değerlere sahip olması durumunda  **true**  döndürür; aksi takdirde  **false** .

**Returns:**
boolean
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


Bu  OneDExtendedParameters  nesnesinin insan tarafından okunabilir dize temsili döndürür.

**Returns:**
java.lang.String - Bu  OneDExtendedParameters  nesnesini temsil eden bir dize.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

