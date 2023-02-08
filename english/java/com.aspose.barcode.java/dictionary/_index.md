---
title: Dictionary
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.java/dictionary/
---
**Inheritance:**
java.lang.Object
```
public class Dictionary<T,V>
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Dictionary()](#Dictionary--) |  |
| [Dictionary(Tup<T,V>[] pairs)](#Dictionary-com.aspose.barcode.common.generic.types.Tup-T-V-...-) |  |
| [Dictionary(Dictionary<T,V> typeSet)](#Dictionary-com.aspose.barcode.java.Dictionary-T-V--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addItem(T key, V value)](#addItem-T-V-) |  |
| [clear()](#clear--) |  |
| [containsKey(T key)](#containsKey-T-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) |  |
| [getValues()](#getValues--) |  |
| [get_Item(T key)](#get-Item-T-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeItemByKey(T key)](#removeItemByKey-T-) |  |
| [set_Item(T key, V value)](#set-Item-T-V-) |  |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [tryGetValue(T key, V[] outValue)](#tryGetValue-T-V---) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Dictionary() {#Dictionary--}
```
public Dictionary()
```


### Dictionary(Tup<T,V>[] pairs) {#Dictionary-com.aspose.barcode.common.generic.types.Tup-T-V-...-}
```
public Dictionary(Tup<T,V>[] pairs)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pairs | com.aspose.barcode.common.generic.types.Tup<T,V>[] |  |

### Dictionary(Dictionary<T,V> typeSet) {#Dictionary-com.aspose.barcode.java.Dictionary-T-V--}
```
public Dictionary(Dictionary<T,V> typeSet)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeSet | [Dictionary](../../com.aspose.barcode.java/dictionary) |  |

### addItem(T key, V value) {#addItem-T-V-}
```
public void addItem(T key, V value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | T |  |
| value | V |  |

### clear() {#clear--}
```
public void clear()
```




### containsKey(T key) {#containsKey-T-}
```
public boolean containsKey(T key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | T |  |

**Returns:**
boolean
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
### getKeys() {#getKeys--}
```
public Set<T> getKeys()
```




**Returns:**
java.util.Set<T>
### getValues() {#getValues--}
```
public Collection<V> getValues()
```




**Returns:**
java.util.Collection<V>
### get_Item(T key) {#get-Item-T-}
```
public V get_Item(T key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | T |  |

**Returns:**
V
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




### removeItemByKey(T key) {#removeItemByKey-T-}
```
public void removeItemByKey(T key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | T |  |

### set_Item(T key, V value) {#set-Item-T-V-}
```
public void set_Item(T key, V value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | T |  |
| value | V |  |

### size() {#size--}
```
public int size()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetValue(T key, V[] outValue) {#tryGetValue-T-V---}
```
public boolean tryGetValue(T key, V[] outValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | T |  |
| outValue | V[] |  |

**Returns:**
boolean
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

