---
title: DataBarExtendedParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Сохраняет дополнительную информацию DataBar распознанного штрих‑кода BarCodeReader reader  new BarCodeReadertest.png DecodeType.DATABAR_OMNI_DIRECTIONAL forBarCodeResult result  reader.readBarCodes    System.out.printlnBarCode Type   result.getCodeTypeName    System.out.printlnBarCode CodeText   result.getCodeText    System.out.printlnQR Structured Append Quantity   result.getExtended.getQR.getQRStructuredAppendModeBarCodesQuantity
type: docs
weight: 30
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/databarextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public class DataBarExtendedParameters extends BaseExtendedParameters
```

Сохраняет дополнительную информацию DataBar распознанного штрихкода BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [is2DCompositeComponent()](#is2DCompositeComponent--) | Получает флаг составного компонента DataBar 2D. |
| [isEmpty()](#isEmpty--) | Проверяет, имеют ли все параметры только значения по умолчанию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого объекта. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли данный экземпляр указанному значению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение System.Object для сравнения с этим экземпляром. |

**Returns:**
boolean - **true** если obj имеет то же значение, что и этот экземпляр; в противном случае, **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого экземпляра.

**Returns:**
int — 32‑битный знаковый целочисленный хеш‑код.
### is2DCompositeComponent() {#is2DCompositeComponent--}
```
public boolean is2DCompositeComponent()
```


Получает флаг составного компонента DataBar 2D. Значение по умолчанию — false.

**Returns:**
boolean - Флаг составного компонента DataBar 2D.
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


Возвращает человекочитаемое строковое представление этого объекта.

**Returns:**
java.lang.String - Строка, представляющая этот объект.
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

