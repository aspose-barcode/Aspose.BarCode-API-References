---
title: MaxiCodeCodetextMode2
second_title: Справочник API Aspose.BarCode для Android через Java
description: Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режима 2.
type: docs
weight: 26
url: /ru/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext), [com.aspose.barcode.complexbarcode.MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)
```
public class MaxiCodeCodetextMode2 extends MaxiCodeStructuredCodetext
```

Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 2. Этот пример показывает, как кодировать и декодировать кодовый текст MaxiCode для режима 2.

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MaxiCodeCodetextMode2()](#MaxiCodeCodetextMode2--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению MaxiCodeStructuredCodetext. |
| [getBarcodeType()](#getBarcodeType--) | Получает тип штрих‑кода. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Создаёт codetext |
| [getCountryCode()](#getCountryCode--) | Определяет трехзначный код страны. |
| [getECIEncoding()](#getECIEncoding--) | Получает кодировку ECI. |
| [getEncodeMode()](#getEncodeMode--) | Получает режим кодирования MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Получает режим кодирования MaxiCode. |
| [getMode()](#getMode--) | Получает режим MaxiCode. |
| [getPostalCode()](#getPostalCode--) | Определяет почтовый индекс. |
| [getSecondMessage()](#getSecondMessage--) | Определяет второе сообщение штрихкода. |
| [getServiceCategory()](#getServiceCategory--) | Определяет трехзначную категорию услуги. |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Инициализирует экземпляр из построенного codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | Определяет трехзначный код страны. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Устанавливает кодировку ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Устанавливает режим кодирования MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Устанавливает режим кодирования MaxiCode. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Определяет почтовый индекс. |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Определяет второе сообщение штрихкода. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | Определяет трехзначную категорию услуги. |
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


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению MaxiCodeStructuredCodetext.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение MaxiCodeStructuredCodetext для сравнения с этим экземпляром |

**Returns:**
boolean — **true**, если obj имеет то же значение, что и этот экземпляр; иначе, **false**
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Получает тип штрих‑кода.

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


Создаёт codetext

**Returns:**
java.lang.String - Сконструированный codetext
### getCountryCode() {#getCountryCode--}
```
public int getCountryCode()
```


Определяет трехзначный код страны.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

**Returns:**
int — кодировка ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Получает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Получает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public int getMode()
```


Получает режим MaxiCode.

**Returns:**
int — режим MaxiCode
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Определяет почтовый индекс. Должен содержать 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public MaxiCodeSecondMessage getSecondMessage()
```


Определяет второе сообщение штрихкода.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public int getServiceCategory()
```


Определяет трехзначную категорию услуги.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого экземпляра.

**Returns:**
int — 32‑битный знаковый целочисленный хеш‑код.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Инициализирует экземпляр из построенного codetext.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Сконструированный codetext. |

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


Определяет трехзначный код страны.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Кодировка ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | режим кодирования MaxiCode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | режим кодирования MaxiCode. |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Определяет почтовый индекс. Должен содержать 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public void setSecondMessage(MaxiCodeSecondMessage value)
```


Определяет второе сообщение штрихкода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public void setServiceCategory(int value)
```


Определяет трехзначную категорию услуги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

