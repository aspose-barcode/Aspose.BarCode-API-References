---
title: "GS1DigitalLink.TryParse"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método GS1DigitalLink. Intenta analizar una URI de GS1 Digital Link sin comprimir y devuelve errores de validación estructurados"
type: docs
weight: 190
url: /es/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

Intenta analizar un URI de GS1 Digital Link sin comprimir y devuelve errores de validación estructurados.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | Cadena | URI de GS1 Digital Link a analizar. |
| resultado | GS1DigitalLink& | Cuando este método devuelve true, contiene el GS1 Digital Link analizado; de lo contrario, null. |
| validationResult | GS1ValidationResult& | Contiene el resultado de validación, o null cuando *value* es null. |

### Valor de retorno

True cuando el análisis tiene éxito; de lo contrario false.

### Ver también

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


