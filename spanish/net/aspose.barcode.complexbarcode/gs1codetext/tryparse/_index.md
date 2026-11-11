---
title: "GS1Codetext.TryParse"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método GS1Codetext. Intenta analizar una cadena de elemento GS1 entre corchetes en la forma AIvalueAIvalue y devuelve errores de validación estructurados. Un literal  dentro de un valor debe escribirse como  no se admite ninguna otra secuencia de escape y  no requiere escape."
type: docs
weight: 140
url: /es/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Intenta analizar una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor y devuelve errores de validación estructurados. Un '(' literal dentro de un valor debe escribirse como \\(; no se admite ninguna otra secuencia de escape, y ')' no requiere escape.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | Cadena | Cadena de elemento GS1 entre corchetes para analizar. |
| resultado | GS1Codetext& | Cuando este método devuelve true, contiene el codetexto GS1 analizado; de lo contrario, null. |
| validationResult | GS1ValidationResult& | Contiene el resultado de validación, o null cuando *value* es null. |

### Valor de retorno

True cuando el análisis tiene éxito; de lo contrario false.

### Ver también

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


