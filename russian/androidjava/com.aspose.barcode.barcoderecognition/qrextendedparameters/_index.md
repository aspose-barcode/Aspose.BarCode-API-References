---
title: QRExtendedParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Сохраняет информацию QR Structured Append распознанного штрихкода
type: docs
weight: 42
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Сохраняет информацию QR Structured Append распознанного штрихкода

Этот пример показывает, как получить данные QR Structured Append

```
{
```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Уровень коррекции ошибок Reed‑Solomon распознанного штрих‑кода. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Версия распознанного MicroQR Code. |
| [getQRErrorLevel()](#getQRErrorLevel--) | Уровень коррекции ошибок Reed‑Solomon распознанного штрих‑кода. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Получает индекс штрих‑кода в режиме QR structured append. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Получает количество штрих‑кодов в режиме QR structured append. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Получает данные четности режима структурного добавления QR. |
| [getQRVersion()](#getQRVersion--) | Версия распознанного QR-кода. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Версия распознанного RectMicroQR-кода. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Получает индекс штрих‑кода в режиме QR structured append. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Получает количество штрих‑кодов в режиме QR structured append. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Получает данные четности режима структурного добавления QR. |
| [getVersion()](#getVersion--) | Версия распознанного QR-кода. |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [isEmpty()](#isEmpty--) | Проверяет, имеют ли все параметры только значения по умолчанию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Возвращает значение, указывающее, равна ли первая величина [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) второй. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Возвращает значение, указывающее, отличается ли первая величина [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) от второй. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли данный экземпляр указанному значению [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение System.Object для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
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


Уровень коррекции ошибок Рида-Соломона распознанного штрихкода. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Версия распознанного MicroQR-кода. От M1 до M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


Уровень коррекции ошибок Рида-Соломона распознанного штрихкода. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


Получает индекс штрихкода режима структурного добавления QR. Индекс начинается с 0. Значение по умолчанию — -1.

Значение: количество штрихкодов режима структурного добавления QR.

**Returns:**
int — индекс штрихкода режима структурного добавления QR.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


Получает количество штрихкодов режима структурного добавления QR. Значение по умолчанию — -1.

Значение: количество штрихкодов режима структурного добавления QR.

**Returns:**
int — количество штрихкодов режима структурного добавления QR.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


Получает данные четности режима структурного добавления QR. Значение по умолчанию — -1.

Значение: индекс штрихкода режима структурного добавления QR.

**Returns:**
int — данные четности режима структурного добавления QR.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


Версия распознанного QR-кода. От Version1 до Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Версия распознанного RectMicroQR-кода. От R7x43 до R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Получает индекс штрихкода режима структурного добавления QR. Индекс начинается с 0. Значение по умолчанию — -1.

Значение: количество штрихкодов режима структурного добавления QR.

**Returns:**
int — индекс штрихкода режима структурного добавления QR.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Получает количество штрихкодов режима структурного добавления QR. Значение по умолчанию — -1.

Значение: количество штрихкодов режима структурного добавления QR.

**Returns:**
int — количество штрихкодов режима структурного добавления QR.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Получает данные четности режима структурного добавления QR. Значение по умолчанию — -1.

Значение: индекс штрихкода режима структурного добавления QR.

**Returns:**
int — данные четности режима структурного добавления QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Версия распознанного QR-кода. От Version1 до Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


Возвращает значение, указывающее, равна ли первая величина [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) второй.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Первое сравниваемое значение |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Второе сравниваемое значение |

**Returns:**
boolean —  **true**  если первое имеет то же значение, что и второе; в противном случае  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


Возвращает значение, указывающее, отличается ли первая величина [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) от второй.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Первое сравниваемое значение |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Второе сравниваемое значение |

**Returns:**
boolean —  **true**  если первое имеет отличное значение от второго; в противном случае  **false** .
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

