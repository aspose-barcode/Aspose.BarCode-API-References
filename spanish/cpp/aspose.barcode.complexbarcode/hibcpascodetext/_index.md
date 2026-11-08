---
title: "Clase Aspose::BarCode::ComplexBarcode::HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::ComplexBarcode::HIBCPASCodetext. Clase para codificar y decodificar el texto incrustado en el código HIBC PAS en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


Clase para codificar y decodificar el texto incrustado en el código HIBC PAS.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Agrega un nuevo registro |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Agrega un nuevo registro |
| [Clear](./clear/)() | Borra la lista de registros |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve un valor que indica si esta instancia es igual a un valor [HIBCPASCodetext](./) especificado. |
| [get_BarcodeType](./get_barcodetype/)() const | Obtiene el tipo de código de barras. El codetext HIBC PAS puede codificarse usando los tipos de codificación HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS y HIBCQRPAS. Valor predeterminado: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Identifica la ubicación de los datos. |
| [GetBarcodeType](./getbarcodetype/)() override | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construye el codetext |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [GetRecords](./getrecords/)() | Obtiene la lista de registros |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Inicializa la instancia a partir del codetext construido. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Establece el tipo de código de barras. El codetext HIBC PAS puede codificarse usando los tipos de codificación HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS y HIBCQRPAS. Valor predeterminado: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Identifica la ubicación de los datos. |
## Observaciones


Este ejemplo muestra cómo codificar y decodificar HIBC PAS usando [HIBCPASCodetext](./).
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
            HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## Ver también

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
