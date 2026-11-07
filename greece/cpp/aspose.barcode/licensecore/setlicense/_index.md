---
title: "μέθοδος"
linktitle: "SetLicense"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδο. Αναζητά την άδεια, τη φορτώνει και προσπαθεί να την εφαρμόσει. Το αποτέλεσμα της εφαρμογής ορίζεται στο errorCode σε C++."
type: docs
weight: 300
url: /el/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Αναζητά την άδεια, τη φορτώνει και προσπαθεί να την υλοποιήσει. Το αποτέλεσμα της υλοποίησης ορίζεται στο errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseName | System::String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | assembly που καλείται για να βρει τη διαδρομή αναζήτησης |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | κωδικός σφάλματος που αποθηκεύει την κατάσταση της άδειας και πρόσθετες πληροφορίες για πιθανό μήνυμα σφάλματος |

## Δείτε επίσης

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Προσπαθεί να υλοποιήσει την άδεια. Το αποτέλεσμα της υλοποίησης ορίζεται στο errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | System::SharedPtr\<System::IO::Stream\> | ροή με αποθηκευμένη άδεια |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | κωδικός σφάλματος που αποθηκεύει την κατάσταση της άδειας και πρόσθετες πληροφορίες για πιθανό μήνυμα σφάλματος |

## Δείτε επίσης

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
