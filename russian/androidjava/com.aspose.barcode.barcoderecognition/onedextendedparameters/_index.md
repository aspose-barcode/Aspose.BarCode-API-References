---
title: OneDExtendedParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Сохраняет специальные данные 1D распознанного штрихкода, такие как отдельный кодтекст и контрольную сумму
type: docs
weight: 39
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/onedextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class OneDExtendedParameters extends BaseExtendedParameters
```

Сохраняет специальные данные 1D распознанного штрихкода, такие как отдельный кодтекст и контрольную сумму

--------------------

> ```
> This sample shows how to get 1D barcode value and checksum
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.EAN_13);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue());
>     System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
>  }
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению OneDExtendedParameters. |
| [getCheckSum()](#getCheckSum--) | Получает контрольную сумму для 1D штрихкодов. |
| [getClass()](#getClass--) |  |
| [getValue()](#getValue--) | Получает текст кода 1D штрихкодов без контрольной суммы. |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [isEmpty()](#isEmpty--) | Проверяет, имеют ли все параметры только значения по умолчанию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого OneDExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению OneDExtendedParameters.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение System.Object для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


Получает контрольную сумму для 1D штрихкодов.

Значение: Контрольная сумма для 1D штрихкода.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getValue() {#getValue--}
```
public String getValue()
```


Получает текст кода 1D штрихкодов без контрольной суммы.

Значение: Текст кода 1D штрихкодов без контрольной суммы.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого экземпляра.

**Returns:**
int — 32‑битный знаковый целочисленный хеш‑код.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Проверяет, имеют ли все параметры только значения по умолчанию.

Значение: Возвращает  **true**  если все параметры имеют только значения по умолчанию; в противном случае  **false** .

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


Возвращает человекочитаемое строковое представление этого OneDExtendedParameters.

**Returns:**
java.lang.String — строка, представляющая этот OneDExtendedParameters.
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

