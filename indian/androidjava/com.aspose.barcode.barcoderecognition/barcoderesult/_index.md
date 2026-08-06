---
title: BarCodeResult
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: पहचाने गए बारकोड डेटा को संग्रहीत करता है जैसे SingleDecodeType प्रकार, स्ट्रिंग codetext, BarCodeRegionParameters region और अन्य पैरामीटर।
type: docs
weight: 18
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

पहचाने गए बारकोड डेटा संग्रहीत करता है जैसे SingleDecodeType प्रकार, string codetext, BarCodeRegionParameters क्षेत्र और अन्य पैरामीटर

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | BarCodeResult क्लास की एक प्रति बनाता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | BarCodeResult क्लास की एक प्रति बनाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट BarCodeResult मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | एन्कोडेड कोड बाइट्स प्राप्त करता है |
| [getCodeText()](#getCodeText--) | कोड टेक्स्ट प्राप्त करता है |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | एन्कोडिंग के साथ कोड टेक्स्ट प्राप्त करता है। |
| [getCodeType()](#getCodeType--) | बारकोड प्रकार प्राप्त करता है |
| [getCodeTypeName()](#getCodeTypeName--) | बारकोड प्रकार का नाम प्राप्त करता है |
| [getConfidence()](#getConfidence--) | पहचाने गए बारकोड की पहचान विश्वास स्तर प्राप्त करता है |
| [getExtended()](#getExtended--) | पहचाने गए बारकोड के विस्तारित पैरामीटर प्राप्त करता है |
| [getReadingQuality()](#getReadingQuality--) | पढ़ने की गुणवत्ता प्राप्त करता है। |
| [getRegion()](#getRegion--) | बारकोड क्षेत्र प्राप्त करता है |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | इस BarCodeResult की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


BarCodeResult क्लास की एक प्रति बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | BarCodeResult की एक प्रति इंस्टेंस। |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


BarCodeResult क्लास की एक प्रति बनाता है।

**Returns:**
java.lang.Object - BarCodeResult क्लास की प्रति लौटाता है।
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट BarCodeResult मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए BarCodeResult मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


एन्कोडेड कोड बाइट्स प्राप्त करता है

मान: बारकोड के कोड बाइट्स

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


कोड टेक्स्ट प्राप्त करता है

मान: बारकोड का कोड टेक्स्ट

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
```


एन्कोडिंग के साथ कोड टेक्स्ट प्राप्त करता है।

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| एन्कोडिंग | java.nio.charset.Charset | कोडटेक्स्ट के लिए एन्कोडिंग। |

**Returns:**
java.lang.String - पहचाने गए कोड टेक्स्ट को शामिल करने वाली स्ट्रिंग।
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


बारकोड प्रकार प्राप्त करता है

मान: पहचाने गए बारकोड की प्रकार जानकारी

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


बारकोड प्रकार का नाम प्राप्त करता है

मान: पहचाने गए बारकोड का प्रकार नाम

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


पहचाने गए बारकोड की पहचान विश्वास स्तर प्राप्त करता है

मान:  BarCodeConfidence.Strong  में कोई नकली या गलत पहचान नहीं होती,  BarCodeConfidence.Moderate  कभी-कभी नकली या गलत कोडटेक्स्ट रख सकता है क्योंकि यह भरोसे का स्तर कमजोर चेकसम वाले या बिना चेकसम वाले बारकोड्स के लिए है,  BarCodeConfidence.None  हमेशा गलत कोडटेक्स्ट रखता है और नकली पहचान हो सकती है।

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


पहचाने गए बारकोड के विस्तारित पैरामीटर प्राप्त करता है

मान: पहचाने गए बारकोड के विस्तारित पैरामीटर

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


पढ़ने की गुणवत्ता प्राप्त करता है। 1D और डाक बारकोड्स के लिए काम करता है।

मान: पढ़ने की गुणवत्ता प्रतिशत

**Returns:**
डबल
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


बारकोड क्षेत्र प्राप्त करता है

मान: पहचाने गए बारकोड का क्षेत्र

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - एक 32-बिट साइन्ड इंटेजर हैश कोड।
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


इस BarCodeResult की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - यह  BarCodeResult  को दर्शाने वाली स्ट्रिंग।
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
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

