---
title: "AztecExtendedParameters"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Aztec tanınan barkodun özel verilerini saklar"
type: docs
weight: 12
url: /tr/java/com.aspose.barcode.barcoderecognition/aztecextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class AztecExtendedParameters extends BaseExtendedParameters
```

Aztec tanınan barkodun özel verilerini saklar

--------------------

> ```
> This sample shows how to get Aztec raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345");
>  generator.save("test.png");
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.AZTEC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText());
>      System.out.println("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
>      System.out.println("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
>      System.out.println("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
>      System.out.println("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
>  }
> ```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen  AztecExtendedParameters  değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec yapılandırılmış ekleme modu barkodunun kimliğini alır |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec yapılandırılmış ekleme modundaki barkod sayısını alır. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec yapılandırılmış ekleme modunun Dosya kimliğini alır. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder. |
| [isReaderInitialization()](#isReaderInitialization--) | Kodun, okuyucuya aşağıdaki verileri barkod okuyucusunun başlatılması veya yeniden programlanması için talimat olarak yorumlamasını söylemek amacıyla kullanılıp kullanılmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu AztecExtendedParameters nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen  AztecExtendedParameters  değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak bir System.Object değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnek ile aynı değere sahipse; aksi takdirde,  **false** .
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


Aztec yapılandırılmış ekleme modundaki barkodun kimliğini alır. Kimlik 1'den başlar ve barkod sayısına eşit veya daha az olmalıdır. Varsayılan değer 0'dır.

Değer: Aztec yapılandırılmış ekleme modunun barkod kimliği.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Aztec yapılandırılmış ekleme modundaki barkod sayısını alır. Varsayılan değer 0'dır. Sayı 1 ile 26 arasında olmalıdır.

Değer: Aztec yapılandırılmış ekleme modundaki barkod sayısı.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


Aztec yapılandırılmış ekleme modunun Dosya kimliğini alır. Varsayılan değer boş dizedir.

Değer: Aztec yapılandırılmış ekleme modunun Dosya kimliği.

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


Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder.

Değer: Tüm parametreler yalnızca varsayılan değerlere sahipse **true** döndürür; aksi takdirde **false**.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Kodun, okuyucuya aşağıdaki verileri barkod okuyucusunun başlatılması veya yeniden programlanması için talimat olarak yorumlamasını söylemek için kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur.

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


Bu AztecExtendedParameters nesnesinin insan tarafından okunabilir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu AztecExtendedParameters nesnesini temsil eden bir dize.
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

