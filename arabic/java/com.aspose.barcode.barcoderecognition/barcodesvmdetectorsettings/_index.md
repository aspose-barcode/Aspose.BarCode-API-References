---
title: "BarcodeSvmDetectorSettings"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "إعدادات كاشف الباركود."
type: docs
weight: 21
url: /ar/java/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeSvmDetectorSettings
```

إعدادات كاشف الباركود.
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | إعداد كشف عالي الأداء. |
| [getHighQuality()](#getHighQuality--) | إعداد كشف عالي الجودة. |
| [getMaxQuality()](#getMaxQuality--) | إعداد كشف بأقصى جودة. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | حجم النافذة لتنعيم المتوسط. |
| [getNormalQuality()](#getNormalQuality--) | إعداد كشف بجودة عادية. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | يضبط العتبة للمناطق المكتشفة التي قد تحتوي على باركود. |
| [getScanWindowSizes()](#getScanWindowSizes--) | أحجام نافذة الفحص بالبكسل. |
| [getSimilarityCoef()](#getSimilarityCoef--) | معامل التشابه يعتمد على مدى تجانس الباركودات. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | يسمح للكاشف بتخطي البحث عن الباركودات القطرية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | حجم النافذة لتنعيم المتوسط. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | يضبط العتبة للمناطق المكتشفة التي قد تحتوي على باركود. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | أحجام نافذة الفحص بالبكسل. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | معامل التشابه يعتمد على مدى تجانس الباركودات. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | يسمح للكاشف بتخطي البحث عن الباركودات القطرية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
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
### getHighPerformance() {#getHighPerformance--}
```
public static BarcodeSvmDetectorSettings getHighPerformance()
```


إعداد كشف عالي الأداء.

القيمة الافتراضية لـ QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


إعداد كشف عالي الجودة.

القيمة الافتراضية لـ QualitySettings.PresetType.HighQualityDetection و QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


إعداد كشف بأقصى جودة.

القيمة الافتراضية لـ QualitySettings.PresetType.MaxQualityDetection و QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


حجم النافذة لتنعيم المتوسط.

القيم النموذجية هي 3 أو 4. 0 يعني عدم وجود تنعيم متوسط. القيمة الافتراضية هي 0. يجب أن يكون حجم نافذة مرشح المتوسط بين [0, 10]

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


إعداد كشف بجودة عادية.

القيمة الافتراضية لـ QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


يضبط العتبة للمناطق المكتشفة التي قد تحتوي على باركود.

القيمة 0.7 تعني أن 70% السفلية من المناطق الممكنة يتم تصفيتها ولا تُعالج لاحقًا. يجب أن يكون عتبة احتمال المنطقة بين [0.05, 0.9]. استخدم قيمًا عالية للصور الواضحة التي تحتوي على عدد قليل من الباركودات. استخدم قيمًا منخفضة للصور التي تحتوي على العديد من الباركودات أو للصور الضوضائية. قد تؤدي القيمة المنخفضة إلى وقت تعرّف أطول.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


أحجام نافذة الفحص بالبكسل.

الأحجام المسموح بها هي 10، 15، 20، 25، 30. المسح باستخدام حجم نافذة صغير يستغرق وقتًا أطول ويوفر دقة أعلى لكنه قد يفشل في اكتشاف الباركودات الكبيرة جدًا. الجمع بين عدة أحجام نافذة يمكن أن يحسن جودة الكشف.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


معامل التشابه يعتمد على مدى تجانس الباركودات.

استخدم قيمة عالية للباركودات الواضحة. استخدم قيم منخفضة لاكتشاف الباركودات التي تكون متضررة جزئيًا أو غير مضاءة بالتساوي. يجب أن يكون معامل التشابه بين [0.5, 0.9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


يسمح للكاشف بتخطي البحث عن الباركودات القطرية.

ضبطه على false سيزيد من وقت الكشف لكنه يسمح بالعثور على الباركودات القطرية التي قد تُفوت otherwise. تمكين البحث القطري يؤدي إلى وقت كشف أكبر.

**Returns:**
boolean
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




### setMedianFilterWindowSize(int value) {#setMedianFilterWindowSize-int-}
```
public void setMedianFilterWindowSize(int value)
```


حجم النافذة لتنعيم المتوسط.

القيم النموذجية هي 3 أو 4. 0 يعني عدم وجود تنعيم متوسط. القيمة الافتراضية هي 0. يجب أن يكون حجم نافذة مرشح المتوسط بين [0, 10]

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


يضبط العتبة للمناطق المكتشفة التي قد تحتوي على باركود.

القيمة 0.7 تعني أن 70% السفلية من المناطق الممكنة يتم تصفيتها ولا تُعالج لاحقًا. يجب أن يكون عتبة احتمال المنطقة بين [0.05, 0.9]. استخدم قيمًا عالية للصور الواضحة التي تحتوي على عدد قليل من الباركودات. استخدم قيمًا منخفضة للصور التي تحتوي على العديد من الباركودات أو للصور الضوضائية. قد تؤدي القيمة المنخفضة إلى وقت تعرّف أطول.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


أحجام نافذة الفحص بالبكسل.

الأحجام المسموح بها هي 10، 15، 20، 25، 30. المسح باستخدام حجم نافذة صغير يستغرق وقتًا أطول ويوفر دقة أعلى لكنه قد يفشل في اكتشاف الباركودات الكبيرة جدًا. الجمع بين عدة أحجام نافذة يمكن أن يحسن جودة الكشف.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


معامل التشابه يعتمد على مدى تجانس الباركودات.

استخدم قيمة عالية للباركودات الواضحة. استخدم قيم منخفضة لاكتشاف الباركودات التي تكون متضررة جزئيًا أو غير مضاءة بالتساوي. يجب أن يكون معامل التشابه بين [0.5, 0.9]

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


يسمح للكاشف بتخطي البحث عن الباركودات القطرية.

ضبطه على false سيزيد من وقت الكشف لكنه يسمح بالعثور على الباركودات القطرية التي قد تُفوت otherwise. تمكين البحث القطري يؤدي إلى وقت كشف أكبر.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

