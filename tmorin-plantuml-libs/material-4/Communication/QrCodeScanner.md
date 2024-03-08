# QrCodeScanner


```text
material-4/Communication/QrCodeScanner
```

```text
include('material-4/Communication/QrCodeScanner')
```



| Illustration | QrCodeScanner |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/QrCodeScanner.png) | ![illustration for QrCodeScanner](../../material-4/Communication/QrCodeScanner.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$QrCodeScannerXs>`
- `<$QrCodeScannerSm>`
- `<$QrCodeScannerMd>`
- `<$QrCodeScannerLg>`





## QrCodeScanner

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element QrCodeScanner
include('material-4/Communication/QrCodeScanner')

' renders the element
QrCodeScanner('QrCodeScanner', 'Qr Code Scanner', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element QrCodeScanner
include('material-4/Communication/QrCodeScanner')

' renders the element
QrCodeScanner('QrCodeScanner', 'Qr Code Scanner', 'an optional tech label', 'an optional description')
@enduml
```

