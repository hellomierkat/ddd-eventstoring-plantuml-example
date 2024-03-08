# CreditCard


```text
fontawesome-6/Solid/CreditCard
```

```text
include('fontawesome-6/Solid/CreditCard')
```



| Illustration | CreditCard |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/CreditCard.png) | ![illustration for CreditCard](../../fontawesome-6/Solid/CreditCard.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CreditCardXs>`
- `<$CreditCardSm>`
- `<$CreditCardMd>`
- `<$CreditCardLg>`





## CreditCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CreditCard
include('fontawesome-6/Solid/CreditCard')

' renders the element
CreditCard('CreditCard', 'Credit Card', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element CreditCard
include('fontawesome-6/Solid/CreditCard')

' renders the element
CreditCard('CreditCard', 'Credit Card', 'an optional tech label', 'an optional description')
@enduml
```

