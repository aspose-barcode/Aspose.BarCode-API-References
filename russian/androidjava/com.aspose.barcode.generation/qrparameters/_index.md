---
title: QrParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Параметры QR.
type: docs
weight: 64
url: /ru/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

Параметры QR.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Соотношение высоты к ширине модуля 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getEncodeMode()](#getEncodeMode--) | Тип символьной системы QR для режима кодирования BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Уровень коррекции ошибок Рида-Соломона для штрихкодов QR, MicroQR и RectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Версия MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getQrEncodeMode()](#getQrEncodeMode--) | Тип символьной системы QR для режима кодирования BarCode. |
| [getQrEncodeType()](#getQrEncodeType--) | Режим выбора QR / MicroQR. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Уровень коррекции ошибок Рида-Соломона для штрихкодов QR, MicroQR и RectMicroQR. |
| [getQrVersion()](#getQrVersion--) | Версия QR‑кода. От Version1 до Version40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Версия RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | Параметры структурного добавления QR. |
| [getVersion()](#getVersion--) | Версия QR‑кода. От Version1 до Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Соотношение высоты к ширине модуля 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Тип символьной системы QR для режима кодирования BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Уровень коррекции ошибок Рида-Соломона для штрихкодов QR, MicroQR и RectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Версия MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | Режим выбора QR / MicroQR. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Версия RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | Параметры структурного добавления QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Версия QR‑кода. От Version1 до Version40. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Соотношение высоты к ширине модуля 2D BarCode.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Идентификаторы расширенной интерпретации канала. Используется, чтобы сообщить считывателю штрихкода детали о используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки набора символов. Не поддерживается MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Тип символьной системы QR для режима кодирования BarCode. Значение по умолчанию: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Уровень коррекции ошибок Рида‑Соломона для штрих‑кода QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. См. QERrrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Версия MicroQR‑кода. От версии M1 до версии M4. Значение по умолчанию — MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Идентификаторы расширенной интерпретации канала. Используется, чтобы сообщить считывателю штрихкода детали о используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки набора символов. Не поддерживается MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


Тип символьной системы QR для режима кодирования BarCode. Значение по умолчанию: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


Режим выбора QR / MicroQR. Выберите ForceQR для стандартных QR‑символов, Auto для MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Уровень коррекции ошибок Рида‑Соломона для штрих‑кода QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. См. QERrrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Версия QR‑кода. От Version1 до Version40. Значение по умолчанию — QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Версия RectMicroQR‑кода. От версии R7x59 до версии R17x139. Значение по умолчанию — RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


Параметры структурного добавления QR. Режим структурного добавления не поддерживается штрих‑кодами MicroQR и RectMicroQR.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Версия QR‑кода. От Version1 до Version40. Значение по умолчанию — QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Соотношение высоты к ширине модуля 2D BarCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Идентификаторы расширенной интерпретации канала. Используется, чтобы сообщить считывателю штрихкода детали о используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки набора символов. Не поддерживается MicroQR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Тип символьной системы QR для режима кодирования BarCode. Значение по умолчанию: QREncodeMode.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Уровень коррекции ошибок Рида‑Соломона для штрих‑кода QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. См. QERrrorLevel.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Версия MicroQR‑кода. От версии M1 до версии M4. Значение по умолчанию — MicroQRVersion.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


Режим выбора QR / MicroQR. Выберите ForceQR для стандартных QR‑символов, Auto для MicroQR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Версия RectMicroQR‑кода. От версии R7x59 до версии R17x139. Значение по умолчанию — RectMicroQRVersion.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


Параметры структурного добавления QR. Режим структурного добавления не поддерживается штрих‑кодами MicroQR и RectMicroQR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Версия QR‑кода. От Version1 до Version40. Значение по умолчанию — QRVersion.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String — строка, представляющая этот [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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

