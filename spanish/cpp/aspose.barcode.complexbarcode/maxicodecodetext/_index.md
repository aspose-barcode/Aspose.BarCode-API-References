---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext clase"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext class. Clase base para codificar y decodificar el texto incrustado en el código MaxiCode en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


Clase base para codificar y decodificar el texto incrustado en el código MaxiCode.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Obtiene la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Obtiene un modo de codificación MaxiCode. Valor predeterminado: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | Obtiene el tipo de código de barras. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Construye el codetext |
| virtual [GetMode](./getmode/)() const | Obtiene el modo MaxiCode. |
| virtual [InitFromString](./initfromstring/)(System::String) | Inicializa la instancia a partir del codetext construido. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | Establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | Establece un modo de codificación MaxiCode. Valor predeterminado: Auto. |
## Observaciones


Este ejemplo muestra cómo decodificar el codetext bruto de MaxiCode a una instancia de [MaxiCodeCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## Ver también

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
