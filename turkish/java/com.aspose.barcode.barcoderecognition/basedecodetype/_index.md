---
title: "BaseDecodeType"
second_title: "Aspose.BarCode for Java API Referansı"
description: "MultiDecodeType ve SingleDecodeType için temel sınıf."
type: docs
weight: 22
url: /tr/java/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

MultiDecodeType ve SingleDecodeType için temel sınıf.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Verilen çözümleme tiplerinden herhangi birinin dahil edilip edilmediğini belirler |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Bu örneğin belirtilen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Bu örneğin belirtilen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [equals(Object other)](#equals-java.lang.Object-) | Bu örneğin belirtilen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | BaseDecodeType'ın dize temsilini somut tür belirlenerek örneğine dönüştürür. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType'ın dize temsilini örneğine dönüştürür. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType'ın dize temsilini örneğine dönüştürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Verilen çözümleme tiplerinden herhangi birinin dahil edilip edilmediğini belirler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Doğrulanacak tipler. |

**Returns:**
boolean - Herhangi bir tip dahil edilmişse değer true olur.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Bu örneğin belirtilen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | Bu örnek ile karşılaştırılacak bir java.lang.Object değeri. |

**Returns:**
boolean - obj bu örnek ile aynı değere sahipse true; aksi takdirde false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Bu örneğin belirtilen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Bu örnek ile karşılaştırılacak bir java.lang.Object değeri. |

**Returns:**
boolean - obj bu örnek ile aynı değere sahipse true; aksi takdirde false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bu örneğin belirtilen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | java.lang.Object | Bu örnek ile karşılaştırılacak bir java.lang.Object değeri. |

**Returns:**
boolean - obj bu örnek ile aynı değere sahipse true; aksi takdirde false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
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




**Returns:**
java.lang.String
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


BaseDecodeType'ın dize temsilini somut tipini belirleyerek örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Dönüştürülecek bir MultiDecodeType temsilini içeren bir dize. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

aksi takdirde belirsiz tip döndürür. veya MultiDecodeType (\"None\").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


MultiDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Dönüştürülecek bir MultiDecodeType temsilini içeren bir dize. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

aksi takdirde belirsiz tip döndürür. veya MultiDecodeType (\"None\").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Dönüştürülecek \"EAN8\" veya \"EAN13\" veya \"CodaBar\"... biçimindeki bir SingleDecodeType içeren bir dize. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

aksi takdirde belirsiz tip döndürür. veya SingleDecodeType (-1, \"None\").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

