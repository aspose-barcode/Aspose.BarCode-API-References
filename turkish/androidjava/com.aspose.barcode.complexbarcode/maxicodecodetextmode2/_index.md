---
title: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Mod 2 için MaxiCode koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 26
url: /tr/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext), [com.aspose.barcode.complexbarcode.MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)
```
public class MaxiCodeCodetextMode2 extends MaxiCodeStructuredCodetext
```

Mod 2 için MaxiCode koduna gömülü metni kodlamak ve kodunu çözmek için sınıf.  Bu örnek, mod 2 için MaxiCode kod metninin nasıl kodlanacağını ve çözüleceğini gösterir.

```
//Mode 2 with standart second message
  MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
  maxiCodeCodetext.setPostalCode("524032140");
  maxiCodeCodetext.setCountryCode(056);
  maxiCodeCodetext.setServiceCategory(999);
  MaxiCodeStandartSecondMessage maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
  maxiCodeStandartSecondMessage.setMessage("Test message");
  maxiCodeCodetext.setSecondMessage(maxiCodeStandartSecondMessage);
  ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
  complexGenerator.generateBarCodeImage();

  //Mode 2 with structured second message
  MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
  maxiCodeCodetext.setPostalCode("524032140");
  maxiCodeCodetext.setCountryCode(056);
  maxiCodeCodetext.setServiceCategory(999);
  MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
  maxiCodeStructuredSecondMessage.add("634 ALPHA DRIVE");
  maxiCodeStructuredSecondMessage.add("PITTSBURGH");
  maxiCodeStructuredSecondMessage.add("PA");
  maxiCodeStructuredSecondMessage.setYear(99);
  maxiCodeCodetext.setSecondMessage(maxiCodeStructuredSecondMessage);
  ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
  complexGenerator.generateBarCodeImage();

  //Decoding raw codetext with standart second message
  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  {
       for (BarCodeResult result : reader.readBarCodes())
      {
          MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
          if (resultMaxiCodeCodetext instanceof MaxiCodeCodetextMode2)
          {
              MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
              System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
              System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
              System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
              if (maxiCodeStructuredCodetext.getSecondMessage() instanceof MaxiCodeStandartSecondMessage){
                  MaxiCodeStandartSecondMessage secondMessage = (MaxiCodeStandartSecondMessage)maxiCodeStructuredCodetext.getSecondMessage();
                  System.out.println("Message: " + secondMessage.getMessage());
              }
          }
      }
  }
  //Decoding raw codetext with structured second message
  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  {
       for(BarCodeResult result : reader.readBarCodes())
      {
          MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
          if (resultMaxiCodeCodetext instanceof MaxiCodeCodetextMode2){
              MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
              System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
              System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
              System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
              if (maxiCodeStructuredCodetext.getSecondMessage() instanceof MaxiCodeStructuredSecondMessage){
                  MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.getSecondMessage();
                  System.out.println("Message:");
                  for (String identifier : secondMessage.getIdentifiers()){
                      System.out.println(identifier);
                  }
              }
          }
      }
  }
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MaxiCodeCodetextMode2()](#MaxiCodeCodetextMode2--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getBarcodeType()](#getBarcodeType--) | Barkod tipini alır. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Kod metnini oluşturur |
| [getCountryCode()](#getCountryCode--) | 3 haneli ülke kodunu tanımlar. |
| [getECIEncoding()](#getECIEncoding--) | ECI kodlamasını alır. |
| [getEncodeMode()](#getEncodeMode--) | Bir MaxiCode kodlama modunu alır. |
| [getMode()](#getMode--) | MaxiCode modunu alır. |
| [getPostalCode()](#getPostalCode--) | Posta kodunu tanımlar. |
| [getSecondMessage()](#getSecondMessage--) | Barkodun ikinci mesajını tanımlar. |
| [getServiceCategory()](#getServiceCategory--) | 3 haneli hizmet kategorisini tanımlar. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Oluşturulmuş kod metninden örneği başlatır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | 3 haneli ülke kodunu tanımlar. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI kodlamasını ayarlar. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Bir MaxiCode kodlama modunu ayarlar. |
| [setPostalCode(String postalCode)](#setPostalCode-java.lang.String-) |  |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Barkodun ikinci mesajını tanımlar. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | 3 haneli hizmet kategorisini tanımlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeCodetextMode2() {#MaxiCodeCodetextMode2--}
```
public MaxiCodeCodetextMode2()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext) değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırmak için bir [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext) değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
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


Kod metnini oluşturur

**Returns:**
java.lang.String - Oluşturulmuş kod metni
### getCountryCode() {#getCountryCode--}
```
public final int getCountryCode()
```


3 haneli ülke kodunu tanımlar.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI kodlamasını alır. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Returns:**
int - ECI kodlaması.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Bir MaxiCode kodlama modunu alır. Varsayılan değer: Otomatik.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public MaxiCodeMode getMode()
```


MaxiCode modunu alır.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Posta kodunu tanımlar. Mod 2'de 9 hane, mod 3'te 6 alfanümerik sembol olmalıdır.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public final MaxiCodeSecondMessage getSecondMessage()
```


Barkodun ikinci mesajını tanımlar.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public final int getServiceCategory()
```


3 haneli hizmet kategorisini tanımlar.

**Returns:**
int
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


Oluşturulmuş kod metninden örneği başlatır.

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




### setCountryCode(int value) {#setCountryCode-int-}
```
public final void setCountryCode(int value)
```


3 haneli ülke kodunu tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI kodlamasını ayarlar. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | ECI kodlaması. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Bir MaxiCode kodlama modunu ayarlar. Varsayılan değer: Otomatik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | bir MaxiCode kodlama modu. |

### setPostalCode(String postalCode) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String postalCode)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| postalCode | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public final void setSecondMessage(MaxiCodeSecondMessage value)
```


Barkodun ikinci mesajını tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public final void setServiceCategory(int value)
```


3 haneli hizmet kategorisini tanımlar.

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

