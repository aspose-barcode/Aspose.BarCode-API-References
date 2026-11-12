---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "الوضع الذي يتيح الطرق للتعرف على عناصر الباركود بالجودة المحددة."
type: docs
weight: 80
url: /ar/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المحددة. العنصر ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف. يوضح هذا المثال كيفية استخدام وضع BarcodeQuality let reader = new BarCodeReader(\"test.png\", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText()); }

## القيم

| اسم | الوصف |
| --- | --- |
| SOLID | يحدد خطًا صلبًا. |
| DASH | يحدد خطًا مكوّنًا من شرطات. |
| DOT | يحدد خطًا مكوّنًا من نقاط. |
| DASH_DOT | يحدد خطًا مكوّنًا من نمط متكرر من شرطة-نقطة. |
| DASH_DOT_DOT | يحدد خطًا مكوّنًا من نمط متكرر من شرطة-نقطة-نقطة. |
