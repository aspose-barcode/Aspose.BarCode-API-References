---
title: CollectionHelpers
second_title: Aspose.BarCode for Java API Reference
description: Functions for working with Collections
type: docs
weight: 10
url: /java/com.aspose.barcode.common.helpers/collectionhelpers/
---
**Inheritance:**
java.lang.Object
```
public class CollectionHelpers
```

Functions for working with Collections
## Constructors

| Constructor | Description |
| --- | --- |
| [CollectionHelpers()](#CollectionHelpers--) |  |
## Methods

| Method | Description |
| --- | --- |
| [<TKey>incKeyValue(System.Collections.Generic.Dictionary<TKey,Integer> dictionary, TKey key)](#-TKey-incKeyValue-com.aspose.ms.System.Collections.Generic.Dictionary-TKey-java.lang.Integer--TKey-) | Increment by "1" value of the key |
| [<TKey>updateMaxValue(System.Collections.Generic.Dictionary<TKey,Integer> dictionary, TKey key, int value)](#-TKey-updateMaxValue-com.aspose.ms.System.Collections.Generic.Dictionary-TKey-java.lang.Integer--TKey-int-) | Try update max value of the key |
| [<TValueItem>addKeyValue(System.Collections.Generic.Dictionary<Integer,ArrayList<TValueItem>> dictionary, int key, TValueItem value)](#-TValueItem-addKeyValue-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.util.ArrayList-TValueItem---int-TValueItem-) | Use if value contains list of all values with a key |
| [containsSubsequence(byte[] sequence, int index, byte[] subsequence)](#containsSubsequence-byte---int-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findKeysOfMax(System.Collections.Generic.Dictionary<Integer,Integer> dictionary)](#findKeysOfMax-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--) | Finds all keys of max value. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intListToString(System.Collections.Generic.IGenericList<Integer> intList)](#intListToString-com.aspose.ms.System.Collections.Generic.IGenericList-java.lang.Integer--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CollectionHelpers() {#CollectionHelpers--}
```
public CollectionHelpers()
```


### <TKey>incKeyValue(System.Collections.Generic.Dictionary<TKey,Integer> dictionary, TKey key) {#-TKey-incKeyValue-com.aspose.ms.System.Collections.Generic.Dictionary-TKey-java.lang.Integer--TKey-}
```
public static void <TKey>incKeyValue(System.Collections.Generic.Dictionary<TKey,Integer> dictionary, TKey key)
```


Increment by "1" value of the key

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dictionary | com.aspose.ms.System.Collections.Generic.Dictionary<TKey,java.lang.Integer> | the dictionary |
| key | TKey | the specified key

 TKey : Type of class for the dictionary |

### <TKey>updateMaxValue(System.Collections.Generic.Dictionary<TKey,Integer> dictionary, TKey key, int value) {#-TKey-updateMaxValue-com.aspose.ms.System.Collections.Generic.Dictionary-TKey-java.lang.Integer--TKey-int-}
```
public static void <TKey>updateMaxValue(System.Collections.Generic.Dictionary<TKey,Integer> dictionary, TKey key, int value)
```


Try update max value of the key

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dictionary | com.aspose.ms.System.Collections.Generic.Dictionary<TKey,java.lang.Integer> | the dictionary |
| key | TKey | the specified key |
| value | int | the specified value

 TKey : Type of class for the dictionary |

### <TValueItem>addKeyValue(System.Collections.Generic.Dictionary<Integer,ArrayList<TValueItem>> dictionary, int key, TValueItem value) {#-TValueItem-addKeyValue-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.util.ArrayList-TValueItem---int-TValueItem-}
```
public static void <TValueItem>addKeyValue(System.Collections.Generic.Dictionary<Integer,ArrayList<TValueItem>> dictionary, int key, TValueItem value)
```


Use if value contains list of all values with a key

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dictionary | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.util.ArrayList<TValueItem>> |  |
| key | int |  |
| value | TValueItem |  |

### containsSubsequence(byte[] sequence, int index, byte[] subsequence) {#containsSubsequence-byte---int-byte---}
```
public static boolean containsSubsequence(byte[] sequence, int index, byte[] subsequence)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequence | byte[] |  |
| index | int |  |
| subsequence | byte[] |  |

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
### findKeysOfMax(System.Collections.Generic.Dictionary<Integer,Integer> dictionary) {#findKeysOfMax-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--}
```
public static List<Integer> findKeysOfMax(System.Collections.Generic.Dictionary<Integer,Integer> dictionary)
```


Finds all keys of max value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dictionary | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.Integer> | Input dictionary |

**Returns:**
[List](../../java.util/list) - Keys of max value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intListToString(System.Collections.Generic.IGenericList<Integer> intList) {#intListToString-com.aspose.ms.System.Collections.Generic.IGenericList-java.lang.Integer--}
```
public static String intListToString(System.Collections.Generic.IGenericList<Integer> intList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| intList | com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> |  |

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

