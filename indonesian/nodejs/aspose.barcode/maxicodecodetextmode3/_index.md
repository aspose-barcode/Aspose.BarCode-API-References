---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk mengenkode dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode 3."
type: docs
weight: 620
url: /id/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

Kelas untuk mengkodekan dan mendekode teks yang disematkan dalam kode MaxiCode untuk mode 3. Contoh ini menunjukkan cara mengkodekan dan mendekode teks kode MaxiCode untuk mode 3.

```js
new MaxiCodeCodetextMode3()
```

**Example:**

```js
//Mode 3 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode3();
 maxiCodeCodetext.setPostalCode("B1050");
 maxiCodeCodetext.setCountryCode(056);
 maxiCodeCodetext.setServiceCategory(999);
 let MaxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
 MaxiCodeStandardSecondMessage.setMessage("Test message");
 maxiCodeCodetext.setSecondMessage(MaxiCodeStandardSecondMessage);
 let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
 complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getMode()](#getmode) | Mendapatkan mode MaxiCode. |

### getMode() {#getmode}

Mendapatkan mode MaxiCode.

**Returns:** MaxiCode mode
