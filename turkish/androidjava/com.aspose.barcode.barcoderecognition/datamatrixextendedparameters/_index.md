---
title: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Tanımlanan DataMatrix barkodunun özel verilerini depolar"
type: docs
weight: 29
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

Tanımlanan DataMatrix barkodunun özel verilerini depolar

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming));
>  }
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen DataMatrixExtendedParameters değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | DataMatrix yapılandırılmış ekleme modu barkodunun kimliğini alır. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | DataMatrix yapılandırılmış ekleme modu barkodlarının sayısını alır. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | DataMatrix yapılandırılmış ekleme modu barkodunun kimliğini alır. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |
| [isReaderProgramming()](#isReaderProgramming--) | Kodun, barkod okuyucusunu başlatma veya yeniden programlama talimatları olarak aşağıdaki verileri yorumlaması için okuyucuya talimat vermek amacıyla kullanılıp kullanılmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu DataMatrixExtendedParameters için insan tarafından okunabilir bir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen DataMatrixExtendedParameters değerine eşit olup olmadığını gösteren bir değer döndürür.

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
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


DataMatrix yapılandırılmış ekleme modu barkodunun kimliğini alır. Kimlik 1'den başlar ve barkod sayısına eşit ya da daha küçük olmalıdır. Varsayılan değer -1'dir.

Değer: DataMatrix yapılandırılmış ekleme modu barkodunun kimliği.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


DataMatrix yapılandırılmış ekleme modu barkodlarının sayısını alır. Varsayılan değer -1'dir. Sayı 1 ile 35 arasında olmalıdır.

Değer: DataMatrix yapılandırılmış ekleme modu barkodunun sayısı.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


DataMatrix yapılandırılmış ekleme modu barkodunun kimliğini alır. Kimlik 1'den başlar ve barkod sayısına eşit ya da daha küçük olmalıdır. Varsayılan değer -1'dir.

Değer: DataMatrix yapılandırılmış ekleme modu barkodunun kimliği.

**Returns:**
int
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
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


Kodun, barkod okuyucusunu başlatma veya yeniden programlama talimatları olarak aşağıdaki verileri yorumlaması için okuyucuya talimat vermek amacıyla kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur.

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


Bu DataMatrixExtendedParameters için insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu DataMatrixExtendedParameters'ı temsil eden bir dize.
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

