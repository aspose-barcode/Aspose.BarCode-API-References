---
title: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Tanımlanan DotCode barkodunun özel verilerini depolar"
type: docs
weight: 31
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Tanımlanan DotCode barkodunun özel verilerini depolar

Bu örnek, DotCode ham değerlerini nasıl alacağınızı gösterir

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");

 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | DotCode yapılandırılmış ekleme modundaki barkodun kimliğini alır. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | DotCode yapılandırılmış ekleme modu barkod sayısını alır. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |
| [isReaderInitialization()](#isReaderInitialization--) | Kodun, barkod okuyucusunu başlatma veya yeniden programlama talimatları olarak aşağıdaki verileri yorumlaması için okuyucuya talimat vermek amacıyla kullanılıp kullanılmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) nesnesinin insan tarafından okunabilir bir dize temsilini döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) değerine eşit olup olmadığını gösteren bir değer döndürür.

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
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode yapılandırılmış ekleme modu barkodunun kimliğini (ID) alır. ID 1'den başlar ve barkod sayısına eşit ya da daha az olmalıdır. Varsayılan değer -1'dir.

Değer: DotCode yapılandırılmış ekleme modu barkodunun kimliği (ID).

**Returns:**
int - DotCode yapılandırılmış ekleme modu barkodunun kimliği (ID).
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode yapılandırılmış ekleme modu barkod sayısını alır. Varsayılan değer -1'dir. Sayı 1 ile 35 arasında bir değer olmalıdır.

Değer: DotCode yapılandırılmış ekleme modu barkod sayısı.

**Returns:**
int - DotCode yapılandırılmış ekleme modu barkod sayısı.
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
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
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


Bu [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) nesnesinin insan tarafından okunabilir bir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) nesnesini temsil eden bir dize.
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

