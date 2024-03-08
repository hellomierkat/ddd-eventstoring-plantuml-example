# Nfc


```text
material-4/Device/Nfc
```

```text
include('material-4/Device/Nfc')
```



| Illustration | Nfc |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Device/Nfc.png) | ![illustration for Nfc](../../material-4/Device/Nfc.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$NfcXs>`
- `<$NfcSm>`
- `<$NfcMd>`
- `<$NfcLg>`





## Nfc

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Nfc
include('material-4/Device/Nfc')

' renders the element
Nfc('Nfc', 'Nfc', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Nfc
include('material-4/Device/Nfc')

' renders the element
Nfc('Nfc', 'Nfc', 'an optional tech label', 'an optional description')
@enduml
```

