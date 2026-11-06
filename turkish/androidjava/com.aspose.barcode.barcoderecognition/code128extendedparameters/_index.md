---
title: "Code128ExtendedParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Code128 tanınan barkodun özel verilerini depolar"
type: docs
weight: 27
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/code128extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Code128ExtendedParameters extends BaseExtendedParameters
```

Code128 tanınan barkodun özel verilerini depolar

Tanınan barkodun bölgesini ve barkod açısını temsil eder

--------------------

> ```
> This sample shows how to get code128 raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("Code128 Data Portions: " + result.getExtended().getCode128());
>  }
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen  Code128ExtendedParameters  değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getCode128DataPortions()](#getCode128DataPortions--) | Tanımlanan Code128 barkodunun  Code128DataPortion  dizisini alır |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu  Code128ExtendedParameters  nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen  Code128ExtendedParameters  değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak bir System.Object değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCode128DataPortions() {#getCode128DataPortions--}
```
public Code128DataPortion[] getCode128DataPortions()
```


Tanımlanan Code128 barkodunun  Code128DataPortion  dizisini alır

Değer:  Code128DataPortion  dizisi.

**Returns:**
com.aspose.barcode.barcoderecognition.Code128DataPortion[]
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


Bu  Code128ExtendedParameters  nesnesinin insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu  Code128ExtendedParameters  nesnesini temsil eden bir dize.
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

