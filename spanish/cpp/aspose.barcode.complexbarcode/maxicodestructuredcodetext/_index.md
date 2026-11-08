---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext clase"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext clase. Clase base para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2 y 3 en C++."
type: docs
weight: 2200
url: /es/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Clase base para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2 y 3.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [MaxiCodeStructuredCodetext](./). |
| [get_CountryCode](./get_countrycode/)() const | Identifica el código de país de 3 dígitos. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Obtiene la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Obtiene un modo de codificación MaxiCode. Valor predeterminado: Auto. |
| [get_PostalCode](./get_postalcode/)() const | Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o de 6 símbolos alfanuméricos en el modo 3. |
| [get_SecondMessage](./get_secondmessage/)() const | Identifica el segundo mensaje del código de barras. |
| [get_ServiceCategory](./get_servicecategory/)() const | Identifica la categoría de servicio de 3 dígitos. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construye el codetext |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | Obtiene el modo MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | Inicializa la instancia a partir del codetext construido. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | Identifica el código de país de 3 dígitos. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Establece un modo de codificación MaxiCode. Valor predeterminado: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o de 6 símbolos alfanuméricos en el modo 3. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identifica el segundo mensaje del código de barras. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | Identifica la categoría de servicio de 3 dígitos. |
## Observaciones


Este ejemplo muestra cómo decodificar texto sin formato MaxiCode a una instancia de [MaxiCodeStructuredCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

## Ver también

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
