---
title: "QrParametersUI"
second_title: "Aspose.BarCode for Java API Reference"
description: "Обёртка UI для класса com.aspose.barcode.generation.QrParameters."
type: docs
weight: 17
url: /ru/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

Обёртка UI для класса com.aspose.barcode.generation.QrParameters.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Отношение высоты к ширине модуля 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | Получает или задаёт значение, указывающее, должны ли специальные символы GS1 кодироваться в байтовом режиме для штрих‑кодов QR и RectMicroQR. |
| [getEncodeMode()](#getEncodeMode--) | Тип символьного набора QR для режима кодирования BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Уровень коррекции ошибок Рида‑Соломона для штрих‑кодов QR, MicroQR и RectMicroQR. |
| [getMicroQrVersion()](#getMicroQrVersion--) | Версия MicroQR Code. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Версия RectMicroQR Code. |
| [getVersion()](#getVersion--) | Версия QR Code. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Отношение высоты к ширине модуля 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | Получает или задаёт значение, указывающее, должны ли специальные символы GS1 кодироваться в байтовом режиме для штрих‑кодов QR и RectMicroQR. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Тип символьного набора QR для режима кодирования BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Уровень коррекции ошибок Рида‑Соломона для штрих‑кодов QR, MicroQR и RectMicroQR. |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | Версия MicroQR Code. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Версия RectMicroQR Code. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Версия QR Code. |
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


Отношение высоты к ширине модуля 2D BarCode.

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
public int getECIEncoding()
```


Идентификаторы расширенной интерпретации каналов (ECI). Они используются для передачи сканеру штрих‑кода сведений о используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки набора символов. Не поддерживается MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


Получает или задаёт значение, указывающее, должны ли специальные символы GS1 кодироваться в байтовом режиме для штрих‑кодов QR и RectMicroQR.

Если false, разделители GS1 могут быть закодированы как '%' в алфавитно-цифровом режиме в соответствии со спецификацией QR.

Если true, групповые разделители GS1 кодируются в байтовом режиме как символ 0x1D, а символы '%' также кодируются в байтовом режиме для сохранения их как данных.

Эта опция может улучшить совместимость с декодерами, ожидающими байтовые групповые разделители GS1, и предотвращает интерпретацию символов данных '%' как разделителей GS1.

**Returns:**
boolean
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Тип символьного набора QR для режима кодирования BarCode. Значение по умолчанию: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Уровень коррекции ошибок Рида-Соломона для штрихкодов QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. см. QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
```


Версия MicroQR Code. От версии M1 до версии M4. Значение по умолчанию — MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Версия RectMicroQR Code. От версии R7x59 до версии R17x139. Значение по умолчанию — RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Версия QR Code. От Version1 до Version40 для QR‑кода и от M1 до M4 для MicroQr. Значение по умолчанию — QRVersion.Auto.

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


Отношение высоты к ширине модуля 2D BarCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Идентификаторы расширенной интерпретации каналов (ECI). Они используются для передачи сканеру штрих‑кода сведений о используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки набора символов. Не поддерживается MicroQR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


Получает или задаёт значение, указывающее, должны ли специальные символы GS1 кодироваться в байтовом режиме для штрих‑кодов QR и RectMicroQR.

Если false, разделители GS1 могут быть закодированы как '%' в алфавитно-цифровом режиме в соответствии со спецификацией QR.

Если true, групповые разделители GS1 кодируются в байтовом режиме как символ 0x1D, а символы '%' также кодируются в байтовом режиме для сохранения их как данных.

Эта опция может улучшить совместимость с декодерами, ожидающими байтовые групповые разделители GS1, и предотвращает интерпретацию символов данных '%' как разделителей GS1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Тип символьного набора QR для режима кодирования BarCode. Значение по умолчанию: QREncodeMode.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Уровень коррекции ошибок Рида-Соломона для штрихкодов QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. см. QRErrorLevel.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
```


Версия MicroQR Code. От версии M1 до версии M4. Значение по умолчанию — MicroQRVersion.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Версия RectMicroQR Code. От версии R7x59 до версии R17x139. Значение по умолчанию — RectMicroQRVersion.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Версия QR Code. От Version1 до Version40 для QR‑кода и от M1 до M4 для MicroQr. Значение по умолчанию — QRVersion.Auto.

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
public final native void wait(long arg0)
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

