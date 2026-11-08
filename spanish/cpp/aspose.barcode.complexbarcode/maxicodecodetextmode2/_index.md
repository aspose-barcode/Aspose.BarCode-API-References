---
title: "Clase Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2. Clase para codificar y decodificar el texto incrustado en el código MaxiCode para el modo 2 en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
## MaxiCodeCodetextMode2 class


Clase para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2.

```cpp
class MaxiCodeCodetextMode2 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/). |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | Identifica el código de país de 3 dígitos. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Obtiene la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Obtiene un modo de codificación MaxiCode. Valor predeterminado: Auto. |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o de 6 símbolos alfanuméricos en el modo 3. |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | Identifica el segundo mensaje del código de barras. |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | Identifica la categoría de servicio de 3 dígitos. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | Construye el codetext |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [GetMode](./getmode/)() const override | Obtiene el modo MaxiCode. |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | Inicializa la instancia a partir del codetext construido. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | Identifica el código de país de 3 dígitos. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Establece un modo de codificación MaxiCode. Valor predeterminado: Auto. |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o de 6 símbolos alfanuméricos en el modo 3. |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identifica el segundo mensaje del código de barras. |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | Identifica la categoría de servicio de 3 dígitos. |
## Observaciones


Este ejemplo muestra cómo codificar y decodificar el codetexto MaxiCode para el modo 2.
```cpp
[C#]
//Modo 2 con mensaje secundario estándar
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Modo 2 con mensaje secundario estructurado
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Decodificando texto sin formato con mensaje secundario estándar
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStandardSecondMessage){
                MaxiCodeStandardSecondMessage secondMessage = (MaxiCodeStandardSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message: " + secondMessage.Message);
            }
        }
    }
}
//Decodificando texto sin formato con mensaje secundario estructurado
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStructuredSecondMessage){
                MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message:");
                foreach (var identifier in secondMessage.Identifiers){
                    Console.WriteLine(identifier);
                }
            }
        }
    }
}
```

## Ver también

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
