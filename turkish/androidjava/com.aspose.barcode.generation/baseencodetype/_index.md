---
title: "BaseEncodeType"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "SymbologyEncodeType için temel sınıf."
type: docs
weight: 16
url: /tr/androidjava/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

SymbologyEncodeType için temel sınıf.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Bu örneğin belirtilen BaseEncodeType değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Bu sembolün sınıflandırmasını alır. |
| [getString()](#getString--) | BaseEncodeType örneğini eşdeğer dize temsiline dönüştürür. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | BaseEncodeType örneğini eşdeğer dize temsiline dönüştürür. |
| [getTypeIndex()](#getTypeIndex--) | Kodlama türünün bir dizinini alır |
| [getTypeName()](#getTypeName--) | Kodlama türünün adını alır |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | BaseEncodeType adının dize temsiliğini örneğine dönüştürür. |
| [toString()](#toString--) | Verilen BaseEncodeType'ın adını dize olarak döndürür. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | BaseEncodeType'ın dize temsiliğini örneğine dönüştürür. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | BaseEncodeType'ın dize temsiliğini örneğine dönüştürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bu örneğin belirtilen BaseEncodeType değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | java.lang.Object | Bu örnekle karşılaştırmak için bir BaseEncodeType değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


Bu sembolün sınıflandırmasını alır.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


BaseEncodeType örneğini eşdeğer dize temsiline dönüştürür. Dize biçimi: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - Kodlama türünün tam değerini temsil eden bir dize
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


BaseEncodeType örneğini eşdeğer dize temsiline dönüştürür. Dize biçimi: "Index:-1; Name:None".

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Dönüştürülecek BaseEncodeType örneği |

**Returns:**
java.lang.String - Verilen kodlama türünün tam değerini temsil eden bir dize
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Kodlama türünün bir dizinini alır

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Kodlama türünün adını alır

**Returns:**
java.lang.String
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




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


BaseEncodeType adının dize temsiliğini örneğine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stringEncodeType | java.lang.String | Dönüştürülecek bir BaseEncodeType'ın adını içeren bir dize. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Verilen BaseEncodeType'ın adını dize olarak döndürür.

**Returns:**
java.lang.String - Kodlama türünün adını temsil eden bir dize
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


BaseEncodeType'ın dize temsiliğini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | "Index:-1; Name:None" biçiminde bir dize, dönüştürmek için. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Dönüşüm başarıyla tamamlandığında gerçek bir SingleEncodeType döner; |

aksi takdirde null döner. |

**Returns:**
boolean -  **true**  eğer s başarıyla dönüştürüldüyse; aksi takdirde,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


BaseEncodeType'ın dize temsiliğini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | "Index:-1; Name:None" biçiminde bir dize, dönüştürmek için. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Dönüşüm başarıyla tamamlandığında gerçek bir SingleEncodeType döner; |

aksi takdirde null döner. |

**Returns:**
boolean -  **true**  eğer s başarıyla dönüştürüldüyse; aksi takdirde,  **false** .
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

