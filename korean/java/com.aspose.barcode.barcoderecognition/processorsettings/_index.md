---
title: "ProcessorSettings"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "ProcessorSettings는 멀티스레드 성능 향상을 통해 바코드를 인식하도록 허용합니다"
type: docs
weight: 37
url: /ko/java/com.aspose.barcode.barcoderecognition/processorsettings/
---
**Inheritance:**
java.lang.Object
```
public class ProcessorSettings
```

ProcessorSettings는 멀티스레드 성능 향상을 통해 바코드를 인식하도록 허용합니다

--------------------

> ```
> This sample shows how to use ProcessorSettings to add maximum multi-threaded performnce
>  
>  BarCodeReader.getProcessorSettings().setMaxAdditionalAllowedThreads(Environment.getProcessorCount()* 2);
>  //this allows to use all cores for single BarCodeReader call
>  BarCodeReader.getProcessorSettings().setUseAllCores(true);
>  //this allows to use current count of cores
>  BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxAdditionalAllowedThreads()](#getMaxAdditionalAllowedThreads--) | 코드를 병렬로 실행하기 위한 추가 스레드의 최대 수를 지정합니다. |
| [getUseAllCores()](#getUseAllCores--) | 전체 코어를 사용하려면 필요합니다. |
| [getUseOnlyThisCoresCount()](#getUseOnlyThisCoresCount--) | 사용할 코어 수를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxAdditionalAllowedThreads(int value)](#setMaxAdditionalAllowedThreads-int-) | 코드를 병렬로 실행하기 위한 추가 스레드의 최대 수를 지정합니다. |
| [setUseAllCores(boolean value)](#setUseAllCores-boolean-) | 전체 코어를 사용하려면 필요합니다. |
| [setUseOnlyThisCoresCount(int value)](#setUseOnlyThisCoresCount-int-) | 사용할 코어 수를 지정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMaxAdditionalAllowedThreads() {#getMaxAdditionalAllowedThreads--}
```
public int getMaxAdditionalAllowedThreads()
```


코드를 병렬로 실행하기 위한 추가 스레드의 최대 수를 지정합니다.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setMaxAdditionalAllowedThreads(Environment.getProcessorCount() * 2);
> ```

**Returns:**
int
### getUseAllCores() {#getUseAllCores--}
```
public boolean getUseAllCores()
```


전체 코어를 사용하려면 필요합니다.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(true);
> ```

**Returns:**
boolean
### getUseOnlyThisCoresCount() {#getUseOnlyThisCoresCount--}
```
public int getUseOnlyThisCoresCount()
```


사용할 코어 수를 지정합니다. 속성 \"UseAllCores\"를 \"false\"로 변경해야 합니다.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```

**Returns:**
int
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




### setMaxAdditionalAllowedThreads(int value) {#setMaxAdditionalAllowedThreads-int-}
```
public void setMaxAdditionalAllowedThreads(int value)
```


코드를 병렬로 실행하기 위한 추가 스레드의 최대 수를 지정합니다.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setMaxAdditionalAllowedThreads(Environment.getProcessorCount() * 2);
> ```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setUseAllCores(boolean value) {#setUseAllCores-boolean-}
```
public void setUseAllCores(boolean value)
```


전체 코어를 사용하려면 필요합니다.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(true);
> ```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setUseOnlyThisCoresCount(int value) {#setUseOnlyThisCoresCount-int-}
```
public void setUseOnlyThisCoresCount(int value)
```


사용할 코어 수를 지정합니다. 속성 \"UseAllCores\"를 \"false\"로 변경해야 합니다.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```

**Parameters:**
| 매개변수 | 유형 | 설명 |
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
public final native void wait(long arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

