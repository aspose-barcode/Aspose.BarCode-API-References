---
title: GS1HanXinEncoder
second_title: Справочник API Aspose.BarCode для Android через Java
description: Содержит функции для кодирования GS1HanXin
type: docs
weight: 47
url: /ru/androidjava/com.aspose.barcode.generation/gs1hanxinencoder/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder, com.aspose.barcode.generation.HanXinEncoder
```
public class GS1HanXinEncoder extends HanXinEncoder
```

Содержит функции для кодирования GS1HanXin
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GS1HanXinEncoder(HanXinEncoderParameters parameters)](#GS1HanXinEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters-) | Входные данные должны содержать скобки () только в качестве разделителей режимов, например: (01)12345678901231(21)ASPOSE(30)9876. Согласно спецификациям GS1, все строки данных GS1 фиксированной длины должны предшествовать всем строкам данных GS1 переменной длины. |
## Методы

| Метод | Описание |
| --- | --- |
| [encode(String str)](#encode-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlwaysShowChecksum()](#getAlwaysShowChecksum--) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getEncodeType()](#getEncodeType--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getParameters()](#getParameters--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GS1HanXinEncoder(HanXinEncoderParameters parameters) {#GS1HanXinEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters-}
```
public GS1HanXinEncoder(HanXinEncoderParameters parameters)
```


Входные данные должны содержать скобки () только в качестве разделителей режимов, например: (01)12345678901231(21)ASPOSE(30)9876. Согласно спецификациям GS1, все строки данных GS1 фиксированной длины должны предшествовать всем строкам данных GS1 переменной длины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| параметры | com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters |  |

### encode(String str) {#encode-java.lang.String-}
```
public String encode(String str)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
java.lang.String
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
### getAlwaysShowChecksum() {#getAlwaysShowChecksum--}
```
public boolean getAlwaysShowChecksum()
```




**Returns:**
boolean
### getChecksum() {#getChecksum--}
```
public String getChecksum()
```




**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableChecksum() {#getEnableChecksum--}
```
public EnableChecksum getEnableChecksum()
```




**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### getEncodeType() {#getEncodeType--}
```
public BaseEncodeType getEncodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getHumanReadableCodeText() {#getHumanReadableCodeText--}
```
public String getHumanReadableCodeText()
```




**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public EncoderParameters getParameters()
```




**Returns:**
com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.EncoderParameters
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

