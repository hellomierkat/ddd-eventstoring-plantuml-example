# CcPaypal


```text
fontawesome-6/Brands/CcPaypal
```

```text
include('fontawesome-6/Brands/CcPaypal')
```



| Illustration | CcPaypal |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/CcPaypal.png) | ![illustration for CcPaypal](../../fontawesome-6/Brands/CcPaypal.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CcPaypalXs>`
- `<$CcPaypalSm>`
- `<$CcPaypalMd>`
- `<$CcPaypalLg>`





## CcPaypal

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CcPaypal
include('fontawesome-6/Brands/CcPaypal')

' renders the element
CcPaypal('CcPaypal', 'Cc Paypal', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element CcPaypal
include('fontawesome-6/Brands/CcPaypal')

' renders the element
CcPaypal('CcPaypal', 'Cc Paypal', 'an optional tech label', 'an optional description')
@enduml
```

