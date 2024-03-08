# Signature


```text
fontawesome-6/Solid/Signature
```

```text
include('fontawesome-6/Solid/Signature')
```



| Illustration | Signature |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Signature.png) | ![illustration for Signature](../../fontawesome-6/Solid/Signature.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SignatureXs>`
- `<$SignatureSm>`
- `<$SignatureMd>`
- `<$SignatureLg>`





## Signature

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Signature
include('fontawesome-6/Solid/Signature')

' renders the element
Signature('Signature', 'Signature', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Signature
include('fontawesome-6/Solid/Signature')

' renders the element
Signature('Signature', 'Signature', 'an optional tech label', 'an optional description')
@enduml
```

