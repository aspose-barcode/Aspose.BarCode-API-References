---
title: "CodetextParameters"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Kodmetni parametreleri.

CodetextParameters türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| two_d_display_text | Kodmetni yerine 2D barkodlarda gösterilecek metin.<br/>            Kullanım: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | FontMode'u belirtin. FontMode Auto olarak ayarlanırsa, yazı tipi boyutu xDimension değerine göre otomatik olarak hesaplanır.<br/>            Özellikle AutoSizeMode.Nearest veya AutoSizeMode.Interpolation içinde FontMode.Auto kullanmanız önerilir.<br/>            Varsayılan değer: FontMode.Auto. |
| font | Görüntülenen CodeText'in yazı tipini belirtin.<br/>            Varsayılan değer: Arial 5pt normal.<br/>            FontMode FontMode.Auto olarak ayarlanmışsa yok sayılır. |
| space | CodeText ile BarCode arasındaki boşluk [Unit](/barcode/python-net/aspose.barcode.generation/unit/) değerinde.<br/>            Varsayılan değer: 2pt.<br/>            EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon için yok sayılır. |
| hizalama | Kod metninin hizalamasını alır veya ayarlar.<br/>            Varsayılan değer: StringAlignment.Center. |
| renk | Görüntülenen CodeText'in Rengini belirtin.<br/>            Varsayılan değer: Color.Black. |
| konum | Görüntülenen CodeText Konumunu belirtin, CodeText'i gizlemek için CodeLocation.None olarak ayarlayın.<br/>            Varsayılan değer: 1D barkodlar için CodeLocation.Below ve 2D barkodlar için CodeLocation.None. |
| no_wrap | Metin içinde kelime kaydırmalarını (satır sonlarını) belirtin.<br/>            Varsayılan değer: false. |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

