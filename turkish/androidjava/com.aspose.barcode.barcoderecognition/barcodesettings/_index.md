---
title: "BarcodeSettings"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Ana BarCode kod çözme parametreleri."
type: docs
weight: 19
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/barcodesettings/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeSettings
```

Ana BarCode kod çözme parametreleri. Tanınan veriler üzerinde etkisi olan parametreleri içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustraliaPost()](#getAustraliaPost--) | AustraliaPost çözümleme parametrelerini alır |
| [getChecksumValidation()](#getChecksumValidation--) | 1D ve Posta barkodları için tanıma sırasında sağlama toplamı doğrulamasını etkinleştirin. |
| [getClass()](#getClass--) |  |
| [getDetectEncoding()](#getDetectEncoding--) | Unicode kod kümeleri için kod metni kodlamasını algılamasını zorlayan bayrak. |
| [getStripFNC()](#getStripFNC--) | Kod metninden FNC1, FNC2, FNC3 karakterlerini kaldır. |
| [hashCode()](#hashCode--) |  |
| [isOnlyRequestedTypes()](#isOnlyRequestedTypes--) | Yalnızca tanıma için açıkça belirtilen barkod türlerini döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChecksumValidation(ChecksumValidation value)](#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-) | 1D ve Posta barkodları için tanıma sırasında sağlama toplamı doğrulamasını etkinleştirin. |
| [setDetectEncoding(boolean value)](#setDetectEncoding-boolean-) | Unicode kod kümeleri için kod metni kodlamasını algılamasını zorlayan bayrak. |
| [setOnlyRequestedTypes(boolean value)](#setOnlyRequestedTypes-boolean-) | Yalnızca tanıma için açıkça belirtilen barkod türlerini döndürür. |
| [setStripFNC(boolean value)](#setStripFNC-boolean-) | Kod metninden FNC1, FNC2, FNC3 karakterlerini kaldır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustraliaPost() {#getAustraliaPost--}
```
public AustraliaPostSettings getAustraliaPost()
```


AustraliaPost çözümleme parametrelerini alır

**Returns:**
[AustraliaPostSettings](../../com.aspose.barcode.barcoderecognition/australiapostsettings) - The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology
### getChecksumValidation() {#getChecksumValidation--}
```
public ChecksumValidation getChecksumValidation()
```


1D ve Posta barkodları için tanıma sırasında kontrol toplamı doğrulamasını etkinleştir. Varsayılan, kontrol toplamı içermesi gereken sembolojiler için Evet, sadece mümkün olduğu durumlarda Hayır olarak değerlendirilir. Kontrol toplamı hiç kullanılmaz: Codabar, PatchCode, Pharmacode, DataLogic2of5 Kontrol toplamı mümkündür: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Kontrol toplamı her zaman kullanılır: Diğer sembolojeler Örnek BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Returns:**
[ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) - Enable checksum validation during recognition for 1D and Postal barcodes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDetectEncoding() {#getDetectEncoding--}
```
public boolean getDetectEncoding()
```


Unicode kod kümeleri için kod metni kodlamasını algılamasını zorlayan bayrak. Varsayılan değer doğrudur.

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Değer: Unicode kod kümeleri için kod metni kodlamasını algılamasını zorlayan bayrak

**Returns:**
boolean
### getStripFNC() {#getStripFNC--}
```
public boolean getStripFNC()
```


Kod metninden FNC1, FNC2, FNC3 karakterlerini kaldır. Varsayılan değer yanlıştır. Örnek BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - Kod metninden FNC1, FNC2, FNC3 karakterlerini kaldır. Varsayılan değer false.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOnlyRequestedTypes() {#isOnlyRequestedTypes--}
```
public boolean isOnlyRequestedTypes()
```


Yalnızca tanıma için açıkça belirtilen barkod türlerini döndürür. Etkinleştirildiğinde, diğer uyumlu veya eşdeğer türlerin tanınan barkodları filtrelenir. Varsayılan değer false.

Örnek:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Returns:**
boolean - yalnızca açıkça istenen barkod türleri döndürülürse true; aksi takdirde false
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChecksumValidation(ChecksumValidation value) {#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-}
```
public void setChecksumValidation(ChecksumValidation value)
```


1D ve Posta barkodları için tanıma sırasında kontrol toplamı doğrulamasını etkinleştir. Varsayılan, kontrol toplamı içermesi gereken sembolojiler için Evet, sadece mümkün olduğu durumlarda Hayır olarak değerlendirilir. Kontrol toplamı hiç kullanılmaz: Codabar, PatchCode, Pharmacode, DataLogic2of5 Kontrol toplamı mümkündür: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Kontrol toplamı her zaman kullanılır: Diğer sembolojeler Örnek BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) | 1D ve Posta barkodları için tanıma sırasında sağlama toplamı doğrulamasını etkinleştirin. |

### setDetectEncoding(boolean value) {#setDetectEncoding-boolean-}
```
public void setDetectEncoding(boolean value)
```


Unicode kod kümeleri için kod metni kodlamasını algılamasını zorlayan bayrak. Varsayılan değer doğrudur.

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Değer: Unicode kod kümeleri için kod metni kodlamasını algılamasını zorlayan bayrak

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setOnlyRequestedTypes(boolean value) {#setOnlyRequestedTypes-boolean-}
```
public void setOnlyRequestedTypes(boolean value)
```


Yalnızca tanıma için açıkça belirtilen barkod türlerini döndürür. Etkinleştirildiğinde, diğer uyumlu veya eşdeğer türlerin tanınan barkodları filtrelenir. Varsayılan değer false.

Örnek:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes())
 {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setStripFNC(boolean value) {#setStripFNC-boolean-}
```
public void setStripFNC(boolean value)
```


Kod metninden FNC1, FNC2, FNC3 karakterlerini kaldır. Varsayılan değer yanlıştır. Örnek BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Kod metninden FNC1, FNC2, FNC3 karakterlerini kaldır. Varsayılan değer false. |

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

