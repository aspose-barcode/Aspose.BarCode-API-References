---
title: "GS1DigitalLink.TryParse"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Метод GS1DigitalLink. Пытается разобрать несжатый URI GS1 Digital Link и возвращает структурированные ошибки проверки."
type: docs
weight: 190
url: /ru/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

Пытается разобрать несжатый GS1 Digital Link URI и возвращает структурированные ошибки проверки.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | String | URI GS1 Digital Link для разбора. |
| result | GS1DigitalLink& | Когда этот метод возвращает true, содержит разобранный GS1 Digital Link; в противном случае null. |
| validationResult | GS1ValidationResult& | Содержит результат проверки, или null, когда *value* равно null. |

### Возвращаемое значение

True, когда разбор успешен; иначе false.

### См. также

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


