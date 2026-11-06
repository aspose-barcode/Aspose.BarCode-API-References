---
title: "MultiDecodeType"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Bileşik çözümleme tipi."
type: docs
weight: 35
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

Bileşik çözümleme tipi.

Bu örnek, SingleDecodeType ve MultiDecode türlerini birleştiren birleşik MultiDecode türlerini nasıl oluşturacağınızı gösterir.

```

```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Yeni bir [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) sınıfının örneğini başlatır. |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Yeni bir [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | MultiDecodeType'a bir başka [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) ekler. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Barkod türlerinden tüm türleri içerip içermediğini kontrol edin. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Herhangi bir tür içeriyor mu |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Bu örneğin belirtilen bir [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Bu kod çözme türleri koleksiyonunun yalnızca belirtilen bir [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) değerini içerip içermediğini gösteren bir değer döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen bir [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) öğesini MultiDecodeType'tan çıkarır ve yeni bir MultiDecodeType örneği döndürür. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Tek tiplerin bir listesini temsil eder. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Tek tiplerin sayısını döndürür. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | MultiDecodeType'ı bir dize olarak temsil eden geçersiz kılınmış yöntem. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | BaseDecodeType'ın dize temsili, somut tip belirlenerek örneğine dönüştürülür. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType'ın dize temsili örneğine dönüştürülür. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType'ın dize temsili örneğine dönüştürülür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


Yeni bir [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Tek kod çözme türlerinin dizisi |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


Yeni bir [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Çoklu ve tek kod çözme türlerinin dizisi |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


MultiDecodeType'a bir başka [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Listeye eklenecek bir Single DecodeType |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Barkod türlerinden tüm türleri içerip içermediğini kontrol edin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tek veya çoklu barkod türlerini girin |

**Returns:**
boolean - Tüm türler dahil edildiğinde değer true olur
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Herhangi bir tür içeriyor mu

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türleri |

**Returns:**
boolean - Herhangi bir tip dahil edildiğinde değer true'dur
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Bu örneğin belirtilen bir [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | Bu örnekle karşılaştırılacak bir [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Bu kod çözme türleri koleksiyonunun yalnızca belirtilen bir [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) değerini içerip içermediğini gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Bu kod çözme türleri koleksiyonuyla karşılaştırılacak bir [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) değeri. |

**Returns:**
boolean -  **true**  bu koleksiyon yalnızca belirtilen kod çözme türünü içeriyorsa; aksi takdirde,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen bir [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak bir System.Object değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) öğesini MultiDecodeType'tan çıkarır ve yeni bir MultiDecodeType örneği döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Hariç tutulacak bir Single DecodeType. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - New MultiDecodeType instance with excluded SingleDecodeType.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


Tek tiplerin bir listesini temsil eder.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Tek tiplerin listesi
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Tek tiplerin sayısını döndürür.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu.
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


MultiDecodeType'ı bir dize olarak temsil eden geçersiz kılınmış yöntem.

**Returns:**
java.lang.String - MultiDecodeType örneğini "singleDecodeType1, singleDecodeType2, ..." olarak temsil eden bir dize

 **"AllSupportedTypes"**  returns when all types are included.
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


BaseDecodeType'ın dize temsilini, somut tip belirlenerek örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Dönüştürülecek bir MultiDecodeType temsilini içeren bir dize. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

Aksi takdirde belirsiz tip döndürür. ya da MultiDecodeType ("None").
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

Aksi takdirde belirsiz tip döndürür. ya da MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Dönüştürülecek "EAN8" veya "EAN13" veya "CodaBar"... biçiminde bir SingleDecodeType içeren bir dize. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

Aksi takdirde belirsiz tip döndürür. ya da SingleDecodeType (-1, "None").
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

