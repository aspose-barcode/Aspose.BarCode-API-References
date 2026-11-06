---
title: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Tanımlanan barkodun MacroPdf417 meta veri bilgilerini depolar"
type: docs
weight: 38
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Tanımlanan barkodun MacroPdf417 meta veri bilgilerini depolar

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen  Pdf417ExtendedParameters  değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417 alıcı adı (isteğe bağlı). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417 sağlama toplamı (isteğe bağlı). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Barkodun dosya kimliğini alır, yalnızca MacroPdf417 ile kullanılabilir. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417 dosya adı (isteğe bağlı). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417 dosya boyutu (isteğe bağlı). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Barkodun segment kimliğini alır, yalnızca MacroPdf417 ile kullanılabilir. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Macro pdf417 barkod segment sayısını alır. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417 gönderici adı (isteğe bağlı). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Segmentin bir Macro PDF417 dosyasının son segmenti olup olmadığını gösterir. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417 zaman damgası (isteğe bağlı). |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isCode128Emulation()](#isCode128Emulation--) | 908, 909, 910 veya 911 Code 128 taklit kod kelimeleriyle kodlanmış MicroPdf417 barkodunu gösteren işaret. |
| [isEmpty()](#isEmpty--) | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |
| [isLinked()](#isLinked--) | Barkodun 1D barkoda bağlanması gerektiğini gösteren işaret. |
| [isReaderInitialization()](#isReaderInitialization--) | Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu  Pdf417ExtendedParameters nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen  Pdf417ExtendedParameters  değerine eşit olup olmadığını gösteren bir değer döndürür.

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
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Macro PDF417 alıcı adı (isteğe bağlı).

**Returns:**
java.lang.String - Alıcı adı.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417 sağlama toplamı (isteğe bağlı).

**Returns:**
int - Kontrol toplamı.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Barkodun dosya kimliğini alır, yalnızca MacroPdf417 ile kullanılabilir.

Değer: MacroPdf417 için dosya kimliği

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417 dosya adı (isteğe bağlı).

**Returns:**
java.lang.String - Dosya adı.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417 dosya boyutu (isteğe bağlı).

**Returns:**
int - Dosya boyutu.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Barkodun segment kimliğini alır, yalnızca MacroPdf417 ile kullanılabilir.

Değer: Barkodun segment kimliği.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Macro pdf417 barkod segment sayısını alır. Varsayılan değer -1'dir.

Değer: Segment sayısı.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Macro PDF417 gönderici adı (isteğe bağlı).

**Returns:**
java.lang.String - Gönderen adı
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Segmentin bir Macro PDF417 dosyasının son segmenti olup olmadığını gösterir.

**Returns:**
boolean - Sonlandırıcı.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417 zaman damgası (isteğe bağlı).

**Returns:**
java.time.LocalDateTime - Zaman damgası.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


908, 909, 910 veya 911 Code 128 taklit kod kelimeleriyle kodlanmış MicroPdf417 barkodunu gösteren işaret.

**Returns:**
boolean - Code 128 emülasyon bayrağı
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder

Değer: Tüm parametrelerin yalnızca varsayılan değerlere sahip olması durumunda  **true**  döndürür; aksi takdirde  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Barkodun 1D barkoda bağlanması gerektiğini gösteren işaret.

Değer: Bağlantı bayrağı

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.

Değer: Okuyucu başlatma bayrağı

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


Bu  Pdf417ExtendedParameters nesnesinin insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu  Pdf417ExtendedParameters nesnesini temsil eden bir dize.
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

