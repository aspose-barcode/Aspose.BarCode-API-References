---
title: "RecognitionAbortedException"
linktitle: "RecognitionAbortedException"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يمثل استثناء إلغاء التعرف الذي يُرمى عند تجاوز مهلة الوقت أثناء التعرف باستخدام BarCodeReader."
type: docs
weight: 870
url: /ar/nodejs/aspose.barcode/recognitionabortedexception/
---

## RecognitionAbortedException class

يمثل استثناء إلغاء التعرف الذي يُرمى عند تجاوز مهلة الوقت أثناء التعرف باستخدام BarCodeReader.

```js
new RecognitionAbortedException(message, executionTime)
```

ينشئ مثيلة جديدة من الفئة مع رسالة إلغاء التعرف المحددة.

| معامل | الوصف |
| --- | --- |
| رسالة | رسالة الخطأ في الاستثناء. |
| executionTime | وقت تنفيذ جلسة التعرف الحالية. |

## طرق

| اسم | الوصف |
| --- | --- |
| [getExecutionTime()](#getexecutiontime) | يحصل على وقت تنفيذ جلسة التعرف الحالية |
| [setExecutionTime(value)](#setexecutiontime) | يضبط وقت تنفيذ جلسة التعرف الحالية |

### getExecutionTime() {#getexecutiontime}

يحصل على وقت تنفيذ جلسة التعرف الحالية

**Returns:** The execution time of current recognition session

### setExecutionTime(value) {#setexecutiontime}

يضبط وقت تنفيذ جلسة التعرف الحالية

| معامل | الوصف |
| --- | --- |
| القيمة | وقت تنفيذ جلسة التعرف الحالية |
