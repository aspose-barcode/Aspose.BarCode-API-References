---
title: "HIBCPASCodetext"
second_title: "Aspose.BarCode for Java API Referansı"
description: "HIBC PAS koduna gömülü metni kodlamak ve kodunu çözmek için sınıf."
type: docs
weight: 18
url: /tr/java/com.aspose.barcode.complexbarcode/hibcpascodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class HIBCPASCodetext implements IComplexCodetext
```

HIBC PAS koduna gömülü metni kodlamak ve kodunu çözmek için sınıf.

--------------------

> ```
> This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.
>   
> 
>   HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
>   complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
>   complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
>   complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
>   complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
>   ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>   BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.HIBC_DATA_MATRIX_PAS);
>   reader.readBarCodes();
>   String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  	HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
>   System.out.println("Data location: {0}", readCodetext.getDataLocation());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[0].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[0].getData());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[1].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[1].getData());
>       }
>   }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HIBCPASCodetext()](#HIBCPASCodetext--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addRecord(HIBCPASRecord record)](#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-) | Yeni kayıt ekler |
| [addRecord(int dataType, String data)](#addRecord-int-java.lang.String-) | Yeni kayıt ekler |
| [clear()](#clear--) | Kayıt listesini temizler |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen HIBCPASCodetext değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getBarcodeType()](#getBarcodeType--) | Barkod tipini alır. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Kod metnini oluşturur. |
| [getDataLocation()](#getDataLocation--) | Veri konumunu belirler. |
| [getRecords()](#getRecords--) | Kayıt listesini alır |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Oluşturulan kod metninden örneği başlatır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Barkod tipini alır veya ayarlar. |
| [setDataLocation(int value)](#setDataLocation-int-) | Veri konumunu belirler. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCPASCodetext() {#HIBCPASCodetext--}
```
public HIBCPASCodetext()
```


### addRecord(HIBCPASRecord record) {#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-}
```
public void addRecord(HIBCPASRecord record)
```


Yeni kayıt ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| record | [HIBCPASRecord](../../com.aspose.barcode.complexbarcode/hibcpasrecord) | Eklenecek kayıt |

### addRecord(int dataType, String data) {#addRecord-int-java.lang.String-}
```
public void addRecord(int dataType, String data)
```


Yeni kayıt ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataType | int | Veri türü |
| veri | java.lang.String | Veri dizesi |

### clear() {#clear--}
```
public void clear()
```


Kayıt listesini temizler

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen HIBCPASCodetext değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak bir HIBCPASCodetext değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnek ile aynı değere sahipse; aksi takdirde,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Barkod tipini alır.

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


Kod metnini oluşturur.

**Returns:**
java.lang.String - Oluşturulmuş kod metni
### getDataLocation() {#getDataLocation--}
```
public int getDataLocation()
```


Veri konumunu belirler.

**Returns:**
int
### getRecords() {#getRecords--}
```
public System.Collections.Generic.List<HIBCPASRecord> getRecords()
```


Kayıt listesini alır

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.complexbarcode.HIBCPASRecord> - Kayıtların listesi
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Oluşturulan kod metninden örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Oluşturulmuş kod metni. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Barkod tipini alır veya ayarlar. HIBC PAS kod metni, HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS ve HIBCQRPAS kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39PAS.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setDataLocation(int value) {#setDataLocation-int-}
```
public void setDataLocation(int value)
```


Veri konumunu belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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

