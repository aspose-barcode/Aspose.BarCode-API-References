---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk warna CMYK."
type: docs
weight: 180
url: /id/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

Kelas untuk warna CMYK. Instance null berarti CMYK tidak digunakan, dan warna RGB default sedang digunakan.

```js
new CMYKColor(c, m, y, k)
```

Menginisialisasi instance baru dari kelas CMYKColor menggunakan nilai CMYK. Nilai CMYK diharapkan dalam rentang 0–100.

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | angka | – Nilai Cyan [0, 100] |
| m | angka | – Nilai Magenta [0, 100] |
| y | angka | – Nilai Yellow [0, 100] |
| k | angka | – Nilai Black [0, 100] |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | Mengurai string CMYK dengan format "C_M_Y_K" menjadi instance CMYKColor. |
| [formatCMYK()](#formatcmyk) | Format CMYKColor ini menjadi string "C_M_Y_K", dengan mengalikan setiap komponen internal (0–1) dengan 100 dan membulatkan. |
| [toString()](#tostring) | Opsional: representasi yang dapat dibaca manusia. |

### parseCMYK(str) (static) {#parsecmyk}

Mengurai string CMYK dengan format "C_M_Y_K" menjadi instance CMYKColor.

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | string | – sebuah string seperti "30_100_0_30" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

Format CMYKColor ini menjadi string "C_M_Y_K", dengan mengalikan setiap komponen internal (0–1) dengan 100 dan membulatkan.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

Opsional: representasi yang dapat dibaca manusia.
