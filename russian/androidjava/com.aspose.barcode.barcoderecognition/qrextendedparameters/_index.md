---
title: "QRExtendedParameters"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: "Сохраняет информацию о QR Structured Append распознанного штрихкода"
type: docs
weight: 40
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Сохраняет информацию о QR Structured Append распознанного штрихкода

Этот пример показывает, как получить данные QR Structured Append

```
{
```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) value. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Уровень коррекции ошибок Reed-Solomon распознанного штрихкода. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Версия распознанного MicroQR Code. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Версия распознанного RectMicroQR Code. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Получает индекс штрихкода в режиме QR structured append. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Получает количество штрихкодов в режиме QR structured append. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Получает данные четности режима QR structured append. |
| [getVersion()](#getVersion--) | Версия распознанного QR Code. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isEmpty()](#isEmpty--) | Проверяет, имеют ли все параметры только значения по умолчанию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) value.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение System.Object для сравнения с этим экземпляром. |

**Returns:**
boolean -  **true**  если obj имеет то же значение, что и этот экземпляр; иначе,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Уровень коррекции ошибок Reed-Solomon распознанного штрихкода. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Версия распознанного MicroQR Code. От M1 до M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Версия распознанного RectMicroQR Code. От R7x43 до R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Получает индекс штрихкода в режиме QR structured append. Индекс начинается с 0. Значение по умолчанию — -1.

Значение: количество штрихкодов в режиме QR structured append.

**Returns:**
int - индекс штрихкода в режиме QR structured append.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Получает количество штрихкодов в режиме QR structured append. Значение по умолчанию — -1.

Значение: количество штрихкодов в режиме QR structured append.

**Returns:**
int - количество штрихкодов в режиме QR structured append.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Получает данные четности режима QR structured append. Значение по умолчанию — -1.

Значение: индекс штрихкода в режиме QR structured append.

**Returns:**
int - данные четности режима QR structured append.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Версия распознанного QR‑кода. От Version1 до Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - 32-битный знаковый целочисленный хеш-код.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Проверяет, имеют ли все параметры только значения по умолчанию.

Значение: Возвращает  **true**  если все параметры имеют только значения по умолчанию; иначе,  **false** .

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


Возвращает человекочитаемое строковое представление этого [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String — строка, представляющая этот [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
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

