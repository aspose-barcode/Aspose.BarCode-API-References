---
title: CameraMode
second_title: Aspose.BarCode for Android via Java API Reference
description: 카메라에서 이미지를 얻기 위한 모드를 포함합니다
type: docs
weight: 32
url: /ko/androidjava/com.aspose.barcode.component.barcodescanner/cameramode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum CameraMode extends Enum<CameraMode>
```

카메라에서 이미지를 얻기 위한 모드를 포함합니다
## 필드

| 필드 | 설명 |
| --- | --- |
| [PHOTO](#PHOTO) | 이 모드는 더 높은 품질의 이미지를 촬영할 수 있지만, 사진을 얻고 처리하는 데 많은 리소스를 사용합니다. |
| [SNAPSHOT](#SNAPSHOT) | 이 모드는 스냅샷으로 이미지를 촬영할 수 있지만, 이미지 품질이 낮습니다. |
## Methods

| Method | 설명 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PHOTO {#PHOTO}
```
public static final CameraMode PHOTO
```


이 모드는 더 높은 품질의 이미지를 촬영할 수 있지만, 사진을 얻고 처리하는 데 많은 리소스를 사용합니다.

### SNAPSHOT {#SNAPSHOT}
```
public static final CameraMode SNAPSHOT
```


이 모드는 스냅샷으로 이미지를 촬영할 수 있지만, 이미지 품질이 낮습니다. 이 모드가 더 권장됩니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static CameraMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode)
### values() {#values--}
```
public static CameraMode[] values()
```




**Returns:**
com.aspose.barcode.component.barcodescanner.CameraMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

