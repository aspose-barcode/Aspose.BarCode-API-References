---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext clase"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext clase. Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios en C++."
type: docs
weight: 900
url: /es/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios.

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [HIBCLICPrimaryDataCodetext](./). |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Obtiene el tipo de código de barras. El codetext HIBC LIC puede codificarse usando los tipos de codificación HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC y HIBCQRLIC. Valor predeterminado: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | Identifica los datos primarios. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construye el codetext |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Inicializa la instancia a partir del codetext construido. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Establece el tipo de código de barras. El codetext HIBC LIC puede codificarse usando los tipos de codificación HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC y HIBCQRLIC. Valor predeterminado: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | Identifica los datos primarios. |
## Observaciones


Este ejemplo muestra cómo codificar y decodificar HIBC LIC usando [HIBCLICPrimaryDataCodetext](./).
```cpp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

## Ver también

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
