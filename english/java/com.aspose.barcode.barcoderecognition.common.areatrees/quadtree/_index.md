---
title: QuadTree
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.common.areatrees/quadtree/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.barcoderecognition.common.areatrees.Point2DTree
```
public class QuadTree<T> extends Point2DTree<T>
```
## Constructors

| Constructor | Description |
| --- | --- |
| [QuadTree(int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)](#QuadTree-int-int-int-boolean-int-) |  |
| [QuadTree(System.Drawing.Rectangle AreaRect, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)](#QuadTree-com.aspose.ms.System.Drawing.Rectangle-int-int-int-boolean-int-) |  |
| [QuadTree(List<T> ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)](#QuadTree-java.util.List-T--int-int-int-boolean-int-) |  |
| [QuadTree(T[] ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)](#QuadTree-T---int-int-int-boolean-int-) |  |
| [QuadTree(List<T> ElementList)](#QuadTree-java.util.List-T--) |  |
| [QuadTree(T[] ElementList)](#QuadTree-T---) |  |
| [QuadTree(System.Drawing.Rectangle AreaRect)](#QuadTree-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [QuadTree()](#QuadTree--) |  |
## Methods

| Method | Description |
| --- | --- |
| [add(T Element)](#add-T-) |  |
| [addRange(T[] ElementList)](#addRange-T---) |  |
| [addRange(List<T> ElementList)](#addRange-java.util.List-T--) |  |
| [balanceTree()](#balanceTree--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findElementsByElement(T aElement, double aDistance)](#findElementsByElement-T-double-) |  |
| [findElementsByPoint(System.Drawing.Point aPoint, double aDistance)](#findElementsByPoint-com.aspose.ms.System.Drawing.Point-double-) |  |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) |  |
| [hashCode()](#hashCode--) |  |
| [isElementExist(T aElement)](#isElementExist-T-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(T Element)](#remove-T-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QuadTree(int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize) {#QuadTree-int-int-int-boolean-int-}
```
public QuadTree(int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aMaxDataInNode | int |  |
| aMinNodeArea | int |  |
| aMinNodeSide | int |  |
| isBalance | boolean |  |
| InflateSize | int |  |

### QuadTree(System.Drawing.Rectangle AreaRect, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize) {#QuadTree-com.aspose.ms.System.Drawing.Rectangle-int-int-int-boolean-int-}
```
public QuadTree(System.Drawing.Rectangle AreaRect, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| AreaRect | com.aspose.ms.System.Drawing.Rectangle |  |
| aMaxDataInNode | int |  |
| aMinNodeArea | int |  |
| aMinNodeSide | int |  |
| isBalance | boolean |  |
| InflateSize | int |  |

### QuadTree(List<T> ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize) {#QuadTree-java.util.List-T--int-int-int-boolean-int-}
```
public QuadTree(List<T> ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | java.util.List<T> |  |
| aMaxDataInNode | int |  |
| aMinNodeArea | int |  |
| aMinNodeSide | int |  |
| isBalance | boolean |  |
| InflateSize | int |  |

### QuadTree(T[] ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize) {#QuadTree-T---int-int-int-boolean-int-}
```
public QuadTree(T[] ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | T[] |  |
| aMaxDataInNode | int |  |
| aMinNodeArea | int |  |
| aMinNodeSide | int |  |
| isBalance | boolean |  |
| InflateSize | int |  |

### QuadTree(List<T> ElementList) {#QuadTree-java.util.List-T--}
```
public QuadTree(List<T> ElementList)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | java.util.List<T> |  |

### QuadTree(T[] ElementList) {#QuadTree-T---}
```
public QuadTree(T[] ElementList)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | T[] |  |

### QuadTree(System.Drawing.Rectangle AreaRect) {#QuadTree-com.aspose.ms.System.Drawing.Rectangle-}
```
public QuadTree(System.Drawing.Rectangle AreaRect)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| AreaRect | com.aspose.ms.System.Drawing.Rectangle |  |

### QuadTree() {#QuadTree--}
```
public QuadTree()
```


### add(T Element) {#add-T-}
```
public void add(T Element)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Element | T |  |

### addRange(T[] ElementList) {#addRange-T---}
```
public void addRange(T[] ElementList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | T[] |  |

### addRange(List<T> ElementList) {#addRange-java.util.List-T--}
```
public void addRange(List<T> ElementList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | java.util.List<T> |  |

### balanceTree() {#balanceTree--}
```
public void balanceTree()
```




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
### findElementsByElement(T aElement, double aDistance) {#findElementsByElement-T-double-}
```
public List<T> findElementsByElement(T aElement, double aDistance)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aElement | T |  |
| aDistance | double |  |

**Returns:**
[List](../../java.util/list)
### findElementsByPoint(System.Drawing.Point aPoint, double aDistance) {#findElementsByPoint-com.aspose.ms.System.Drawing.Point-double-}
```
public List<T> findElementsByPoint(System.Drawing.Point aPoint, double aDistance)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.Point |  |
| aDistance | double |  |

**Returns:**
[List](../../java.util/list)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public List<T> getElements()
```




**Returns:**
[List](../../java.util/list)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isElementExist(T aElement) {#isElementExist-T-}
```
public boolean isElementExist(T aElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aElement | T |  |

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




### remove(T Element) {#remove-T-}
```
public void remove(T Element)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Element | T |  |

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

