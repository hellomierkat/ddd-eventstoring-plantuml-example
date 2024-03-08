# Paypal


```text
fontawesome-6/Brands/Paypal
```

```text
include('fontawesome-6/Brands/Paypal')
```



| Illustration | Paypal |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/Paypal.png) | ![illustration for Paypal](../../fontawesome-6/Brands/Paypal.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PaypalXs>`
- `<$PaypalSm>`
- `<$PaypalMd>`
- `<$PaypalLg>`





## Paypal

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Paypal
include('fontawesome-6/Brands/Paypal')

' renders the element
Paypal('Paypal', 'Paypal', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Paypal
include('fontawesome-6/Brands/Paypal')

' renders the element
Paypal('Paypal', 'Paypal', 'an optional tech label', 'an optional description')
@enduml
```

