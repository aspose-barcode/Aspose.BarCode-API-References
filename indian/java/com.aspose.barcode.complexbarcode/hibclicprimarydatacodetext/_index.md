---
title: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "प्राथमिक डेटा संग्रहीत करने वाले HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 16
url: /hi/java/com.aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICPrimaryDataCodetext extends HIBCLICComplexCodetext
```

प्राथमिक डेटा संग्रहीत करने वाले HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

--------------------

> ```
> This sample shows how to encode and decode HIBC LIC using HIBCLICPrimaryDataCodetext.
>  
>  HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
>  complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
>  complexCodetext.setData(new PrimaryData());
>  complexCodetext.getData().setProductOrCatalogNumber("12345");
>  complexCodetext.getData().setLabelerIdentificationCode("A999");
>  complexCodetext.getData().setUnitOfMeasureID(1);
>  ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>  {
>      BufferedImage image = generator.generateBarCodeImage();
>      BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC);
>      {
>          reader.readBarCodes();
>          HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
>          HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.tryDecodeHIBCLIC(codetext);
>          System.out.println("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
>          System.out.println("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
>          System.out.println("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
>      }
>  }
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [HIBCLICPrimaryDataCodetext()](#HIBCLICPrimaryDataCodetext--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट  HIBCLICPrimaryDataCodetext  मान के बराबर है या नहीं। |
| [getBarcodeType()](#getBarcodeType--) | बारकोड प्रकार को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | कोडटेक्स्ट बनाता है। |
| [getData()](#getData--) | प्राथमिक डेटा की पहचान करता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | निर्मित कोडटेक्स्ट से इंस्टेंस को प्रारंभ करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | बारकोड प्रकार को प्राप्त करता है या सेट करता है। |
| [setData(PrimaryData value)](#setData-com.aspose.barcode.complexbarcode.PrimaryData-) | प्राथमिक डेटा की पहचान करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICPrimaryDataCodetext() {#HIBCLICPrimaryDataCodetext--}
```
public HIBCLICPrimaryDataCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट  HIBCLICPrimaryDataCodetext  मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | एक  HIBCLICPrimaryDataCodetext  मान जिसे इस उदाहरण से तुलना की जा सकती है। |

**Returns:**
boolean -  **true**  यदि obj का मान इस इंस्टेंस के समान है; अन्यथा,  **false** ।
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


बारकोड प्रकार को प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC।

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


कोडटेक्स्ट बनाता है।

**Returns:**
java.lang.String - निर्मित कोडटेक्स्ट
### getData() {#getData--}
```
public PrimaryData getData()
```


प्राथमिक डेटा की पहचान करता है।

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


निर्मित कोडटेक्स्ट से इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| constructedCodetext | java.lang.String | निर्मित कोडटेक्स्ट। |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


बारकोड प्रकार को प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setData(PrimaryData value) {#setData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setData(PrimaryData value)
```


प्राथमिक डेटा की पहचान करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata) |  |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

