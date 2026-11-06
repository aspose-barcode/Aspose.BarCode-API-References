---
title: "BarCodeRegionParameters"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "पहचाने गए बारकोड क्षेत्रों और बारकोड कोण को दर्शाता है"
type: docs
weight: 16
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

पहचाने गए बारकोड का क्षेत्र और बारकोड कोण दर्शाता है।

--------------------

> ```
> This sample shows how to get barcode Angle and bounding quadrangle values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>     System.out.println("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
>  }
> ```
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट  BarCodeRegionParameters  मान के बराबर है या नहीं। |
| [getAngle()](#getAngle--) | बारकोड का कोण (0-360) प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | बारकोड क्षेत्र को सीमित करने वाले Point s एरे को प्राप्त करता है |
| [getQuadrangle()](#getQuadrangle--) | बारकोड क्षेत्र को सीमित करने वाला Aspose.BarCode.BarCodeRecognition.Quadrangle प्राप्त करता है |
| [getRectangle()](#getRectangle--) | बारकोड क्षेत्र को सीमित करने वाला System.Drawing.Rectangle प्राप्त करता है |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | इस  BarCodeRegionParameters  का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट  BarCodeRegionParameters  मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण से तुलना करने के लिए एक System.Object मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


बारकोड का कोण (0-360) प्राप्त करता है।

मान: बारकोड के लिए कोण (0-360)।

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


बारकोड क्षेत्र को सीमित करने वाले Point s एरे को प्राप्त करता है

मान: बारकोड क्षेत्र को सीमित करने वाले Point s एरे को लौटाता है

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


बारकोड क्षेत्र को सीमित करने वाला Aspose.BarCode.BarCodeRecognition.Quadrangle प्राप्त करता है

मान: Aspose.BarCode.BarCodeRecognition.Quadrangle को बारकोड क्षेत्र को सीमित करने वाला लौटाता है

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


बारकोड क्षेत्र को सीमित करने वाला System.Drawing.Rectangle प्राप्त करता है

मान: System.Drawing.Rectangle को बारकोड क्षेत्र को सीमित करने वाला लौटाता है

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
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


इस  BarCodeRegionParameters  का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस  BarCodeRegionParameters  को दर्शाती है।
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

