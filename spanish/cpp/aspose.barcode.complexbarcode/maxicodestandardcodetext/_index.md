---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext clase"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext clase. Clase para codificar y decodificar el codetext de MaxiCode para los modos 4, 5 y 6 en C++."
type: docs
weight: 2000
url: /es/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


Clase para codificar y decodificar el texto de código MaxiCode para los modos 4, 5 y 6.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [MaxiCodeStandardCodetext](./). |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Obtiene la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Obtiene un modo de codificación MaxiCode. Valor predeterminado: Auto. |
| [get_Message](./get_message/)() const | Obtiene el mensaje. |
| [get_Mode](./get_mode/)() | Obtiene el modo MaxiCode. El codetext estándar solo puede usarse con los modos 4, 5 y 6. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construye el codetext |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [GetMode](./getmode/)() const override | Obtiene el modo MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | Inicializa la instancia a partir del codetext construido. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Establece un modo de codificación MaxiCode. Valor predeterminado: Auto. |
| [set_Message](./set_message/)(System::String) | Establece el mensaje. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | Establece el modo MaxiCode. El codetext estándar solo puede usarse con los modos 4, 5 y 6. |
## Observaciones


//Modo 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Modo 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Modo 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## Ver también

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
