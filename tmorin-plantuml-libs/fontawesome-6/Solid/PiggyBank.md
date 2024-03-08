# PiggyBank


```text
fontawesome-6/Solid/PiggyBank
```

```text
include('fontawesome-6/Solid/PiggyBank')
```



| Illustration | PiggyBank |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/PiggyBank.png) | ![illustration for PiggyBank](../../fontawesome-6/Solid/PiggyBank.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PiggyBankXs>`
- `<$PiggyBankSm>`
- `<$PiggyBankMd>`
- `<$PiggyBankLg>`





## PiggyBank

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PiggyBank
include('fontawesome-6/Solid/PiggyBank')

' renders the element
PiggyBank('PiggyBank', 'Piggy Bank', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PiggyBank
include('fontawesome-6/Solid/PiggyBank')

' renders the element
PiggyBank('PiggyBank', 'Piggy Bank', 'an optional tech label', 'an optional description')
@enduml
```

