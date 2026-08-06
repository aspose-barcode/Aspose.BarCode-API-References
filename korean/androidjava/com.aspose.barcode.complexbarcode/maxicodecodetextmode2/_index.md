---
title: MaxiCodeCodetextMode2
second_title: Aspose.BarCode for Android via Java API Reference
description: 모드 2용 MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.
type: docs
weight: 26
url: /ko/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext), [com.aspose.barcode.complexbarcode.MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)
```
public class MaxiCodeCodetextMode2 extends MaxiCodeStructuredCodetext
```

모드 2용 MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스입니다. 이 샘플은 모드 2용 MaxiCode 코드텍스트를 인코딩하고 디코딩하는 방법을 보여줍니다.

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
## Constructors

| Constructor | 설명 |
| --- | --- |
| [MaxiCodeCodetextMode2()](#MaxiCodeCodetextMode2--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 MaxiCodeStructuredCodetext 값과 동일한지 여부를 나타내는 값을 반환합니다. |
| [getBarcodeType()](#getBarcodeType--) | 바코드 유형을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | 코드텍스트를 구성합니다. |
| [getCountryCode()](#getCountryCode--) | 3자리 국가 코드를 식별합니다. |
| [getECIEncoding()](#getECIEncoding--) | ECI 인코딩을 가져옵니다. |
| [getEncodeMode()](#getEncodeMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getMode()](#getMode--) | MaxiCode 모드를 가져옵니다. |
| [getPostalCode()](#getPostalCode--) | 우편 번호를 식별합니다. |
| [getSecondMessage()](#getSecondMessage--) | 바코드의 두 번째 메시지를 식별합니다. |
| [getServiceCategory()](#getServiceCategory--) | 3자리 서비스 카테고리를 식별합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | 3자리 국가 코드를 식별합니다. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI 인코딩을 설정합니다. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode 인코드 모드를 설정합니다. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode 인코드 모드를 설정합니다. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | 우편 번호를 식별합니다. |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | 바코드의 두 번째 메시지를 식별합니다. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | 3자리 서비스 카테고리를 식별합니다. |
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


이 인스턴스가 지정된 MaxiCodeStructuredCodetext 값과 동일한지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 MaxiCodeStructuredCodetext 값 |

**Returns:**
boolean - 객체가 이 인스턴스와 동일한 값을 가지고 있으면 **true**, 그렇지 않으면 **false**
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


바코드 유형을 가져옵니다.

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


코드텍스트를 구성합니다.

**Returns:**
java.lang.String - 구성된 코드텍스트
### getCountryCode() {#getCountryCode--}
```
public int getCountryCode()
```


3자리 국가 코드를 식별합니다.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI 인코딩을 가져옵니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1

**Returns:**
int - ECI 인코딩.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public int getMode()
```


MaxiCode 모드를 가져옵니다.

**Returns:**
int - MaxiCode 모드
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


우편 번호를 식별합니다. 모드 2에서는 9자리 숫자여야 하고, 모드 3에서는 6개의 영숫자 기호여야 합니다.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public MaxiCodeSecondMessage getSecondMessage()
```


바코드의 두 번째 메시지를 식별합니다.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public int getServiceCategory()
```


3자리 서비스 카테고리를 식별합니다.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드입니다.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


구성된 코드텍스트에서 인스턴스를 초기화합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 구성된 코드텍스트. |

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
public void setCountryCode(int value)
```


3자리 국가 코드를 식별합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI 인코딩을 설정합니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | ECI 인코딩. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode 인코드 모드를 설정합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode 인코드 모드. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode 인코드 모드를 설정합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode 인코드 모드. |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


우편 번호를 식별합니다. 모드 2에서는 9자리 숫자여야 하고, 모드 3에서는 6개의 영숫자 기호여야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public void setSecondMessage(MaxiCodeSecondMessage value)
```


바코드의 두 번째 메시지를 식별합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public void setServiceCategory(int value)
```


3자리 서비스 카테고리를 식별합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

