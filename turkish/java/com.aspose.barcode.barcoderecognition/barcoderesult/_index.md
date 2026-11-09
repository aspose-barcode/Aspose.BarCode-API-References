---
title: "BarCodeResult"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Tanımlanan barkod verilerini, SingleDecodeType türü, string codetext, BarCodeRegionParameters bölgesi ve diğer parametreler gibi depolar"
type: docs
weight: 17
url: /tr/java/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Tanımlanan barkod verilerini, örneğin SingleDecodeType türü, string codetext, BarCodeRegionParameters bölgesi ve diğer parametreleri saklar

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | BarCodeResult sınıfının bir kopyasını oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [deepClone()](#deepClone--) | BarCodeResult sınıfının bir kopyasını oluşturur. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen BarCodeResult değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Kodun kodlanmış baytlarını alır |
| [getCodeText()](#getCodeText--) | Kod metnini alır |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | Kod metnini kodlamayla birlikte alır. |
| [getCodeType()](#getCodeType--) | Barkod tipini alır |
| [getCodeTypeName()](#getCodeTypeName--) | Barkod tipinin adını alır |
| [getConfidence()](#getConfidence--) | Tanımlanan barkodun tanıma güven düzeyini alır |
| [getExtended()](#getExtended--) | Tanımlanan barkodun genişletilmiş parametrelerini alır |
| [getReadingQuality()](#getReadingQuality--) | Okuma kalitesini alır. |
| [getRegion()](#getRegion--) | Barkod bölgesini alır |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu BarCodeResult nesnesinin insan tarafından okunabilir bir dize temsilini döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


BarCodeResult sınıfının bir kopyasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Bir BarCodeResult kopyası örneği. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


BarCodeResult sınıfının bir kopyasını oluşturur.

**Returns:**
java.lang.Object - BarCodeResult sınıfının bir kopyasını döndürür.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen BarCodeResult değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırmak için bir BarCodeResult değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnek ile aynı değere sahipse; aksi takdirde,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Kodun kodlanmış baytlarını alır

Değer: Barkodun kod baytları

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Kod metnini alır

Değer: Barkodun kod metni

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


Kod metnini kodlamayla birlikte alır.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| charset | java.nio.charset.Charset | Codetext için kodlama. |

**Returns:**
java.lang.String - Tanınan kod metnini içeren bir dize.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Barkod tipini alır

Value: Tanınan barkodun tip bilgisi

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Barkod tipinin adını alır

Value: Tanınan barkodun tip adı

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


Tanımlanan barkodun tanıma güven düzeyini alır

Value:  BarCodeConfidence.Strong  sahte veya yanlış tanıma içermez,  BarCodeConfidence.Moderate  bazen sahte veya hatalı kod metni içerebilir çünkü bu güven seviyesi zayıf kontrol toplamına sahip barkodlar için veya hiç kontrol toplamı olmayanlar için geçerlidir,  BarCodeConfidence.None  her zaman hatalı kod metni içerir ve sahte tanımalara yol açabilir

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Tanımlanan barkodun genişletilmiş parametrelerini alır

Value: Tanınan barkodun genişletilmiş parametreleri

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Okuma kalitesini alır. 1D ve posta barkodları için çalışır.

Value: Okuma kalitesi yüzdesi

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Barkod bölgesini alır

Value: Tanınan barkodun bölgesi

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
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


Bu BarCodeResult nesnesinin insan tarafından okunabilir bir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu  BarCodeResult  nesnesini temsil eden bir dize.
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

