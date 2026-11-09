---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "Параметры DataMatrix."
type: docs
weight: 32
url: /ru/java/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

Параметры DataMatrix.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Отношение высоты к ширине модуля 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Получает кодировку ECI. |
| [getEccType()](#getEccType--) | Получает тип ECC Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Режим кодирования штрих‑кода Datamatrix. |
| [getMacroCharacters()](#getMacroCharacters--) | Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Идентификатор штрихкода для режима структурного добавления Datamatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Количество штрихкодов для режима Structured Append штрихкода Datamatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Идентификатор файла для режима Structured Append штрихкода Datamatrix. |
| [getVersion()](#getVersion--) | Получает размер символа Datamatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Отношение высоты к ширине модуля 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Устанавливает кодировку ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Устанавливает тип ECC Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Режим кодирования штрих‑кода Datamatrix. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Идентификатор штрихкода для режима структурного добавления Datamatrix. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Количество штрихкодов для режима Structured Append штрихкода Datamatrix. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Идентификатор файла для режима Structured Append штрихкода Datamatrix. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Устанавливает размер символа Datamatrix. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
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
public final int getECIEncoding()
```


Получает кодировку ECI. Используется, когда EncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

**Returns:**
int - кодировка ECI.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Получает тип ECC Datamatrix. Значение по умолчанию: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Режим кодирования штрих‑кода Datamatrix. Значение по умолчанию: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с DataMatrixEccType.Ecc200 или DataMatrixEccType.EccAuto. Не может использоваться с EncodeTypes.GS1DataMatrix. Значение по умолчанию: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Идентификатор штрихкода для режима Structured Append штрихкода Datamatrix. Значение по умолчанию: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Количество штрихкодов для режима Structured Append штрихкода Datamatrix. Значение по умолчанию: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Идентификатор файла для режима Structured Append штрихкода Datamatrix. Значение по умолчанию: 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Получает размер символа Datamatrix. Значение по умолчанию: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. Значение по умолчанию: false

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
public final void setECIEncoding(int value)
```


Устанавливает кодировку ECI. Используется, когда EncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Кодировка ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Устанавливает тип ECC Datamatrix. Значение по умолчанию: DataMatrixEccType.Ecc200.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | тип ECC Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Режим кодирования штрих‑кода Datamatrix. Значение по умолчанию: EncodeMode.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с DataMatrixEccType.Ecc200 или DataMatrixEccType.EccAuto. Не может использоваться с EncodeTypes.GS1DataMatrix. Значение по умолчанию: MacroCharacters.None.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. Значение по умолчанию: false

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Идентификатор штрихкода для режима Structured Append штрихкода Datamatrix. Значение по умолчанию: 0

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Количество штрихкодов для режима Structured Append штрихкода Datamatrix. Значение по умолчанию: 0

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Идентификатор файла для режима Structured Append штрихкода Datamatrix. Значение по умолчанию: 0

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Устанавливает размер символа Datamatrix. Значение по умолчанию: Version.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | размер символа Datamatrix. |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - Строка, представляющая этот [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
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

