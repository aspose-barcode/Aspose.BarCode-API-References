---
title: TreeNode
second_title: Aspose.BarCode for Java API Reference
description: A node of a graph
type: docs
weight: 12
url: /java/com.aspose.barcode.common.generic.collections/treenode/
---
**Inheritance:**
java.lang.Object
```
public class TreeNode<T>
```

A node of a graph

 T : a type of Data in the node
## Constructors

| Constructor | Description |
| --- | --- |
| [TreeNode()](#TreeNode--) | Initializes a new instance of  TreeNode\{T\}  class. |
| [TreeNode(T data)](#TreeNode-T-) | Initializes a new instance of  TreeNode\{T\}  class, initializes Data by parameter data |
## Methods

| Method | Description |
| --- | --- |
| [add(T value)](#add-T-) | Adds a child to the node |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildren()](#getChildren--) | Gets children of a node |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Gets data of a node |
| [getParent()](#getParent--) | A parent of the node |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(T value)](#setData-T-) | Sets data of a node |
| [toString()](#toString--) | Returns a data of node in the string format |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TreeNode() {#TreeNode--}
```
public TreeNode()
```


Initializes a new instance of  TreeNode\{T\}  class.

### TreeNode(T data) {#TreeNode-T-}
```
public TreeNode(T data)
```


Initializes a new instance of  TreeNode\{T\}  class, initializes Data by parameter data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | T | iniializes Data |

### add(T value) {#add-T-}
```
public TreeNode<T> add(T value)
```


Adds a child to the node

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | T | Data of a child |

**Returns:**
[TreeNode](../../com.aspose.barcode.common.generic.collections/treenode) - child node
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
### getChildren() {#getChildren--}
```
public System.Collections.Generic.IGenericList<TreeNode<T>> getChildren()
```


Gets children of a node

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.barcode.common.generic.collections.TreeNode<T>>
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public T getData()
```


Gets data of a node

**Returns:**
T
### getParent() {#getParent--}
```
public TreeNode<T> getParent()
```


A parent of the node

**Returns:**
[TreeNode](../../com.aspose.barcode.common.generic.collections/treenode)
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




### setData(T value) {#setData-T-}
```
public void setData(T value)
```


Sets data of a node

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | T |  |

### toString() {#toString--}
```
public String toString()
```


Returns a data of node in the string format

**Returns:**
java.lang.String - a data of node in the string format
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

