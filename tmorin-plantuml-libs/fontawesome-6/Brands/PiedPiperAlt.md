# PiedPiperAlt


```text
fontawesome-6/Brands/PiedPiperAlt
```

```text
include('fontawesome-6/Brands/PiedPiperAlt')
```



| Illustration | PiedPiperAlt |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/PiedPiperAlt.png) | ![illustration for PiedPiperAlt](../../fontawesome-6/Brands/PiedPiperAlt.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PiedPiperAltXs>`
- `<$PiedPiperAltSm>`
- `<$PiedPiperAltMd>`
- `<$PiedPiperAltLg>`





## PiedPiperAlt

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PiedPiperAlt
include('fontawesome-6/Brands/PiedPiperAlt')

' renders the element
PiedPiperAlt('PiedPiperAlt', 'Pied Piper Alt', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PiedPiperAlt
include('fontawesome-6/Brands/PiedPiperAlt')

' renders the element
PiedPiperAlt('PiedPiperAlt', 'Pied Piper Alt', 'an optional tech label', 'an optional description')
@enduml
```

