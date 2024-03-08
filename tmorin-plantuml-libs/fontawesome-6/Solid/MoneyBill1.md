# MoneyBill1


```text
fontawesome-6/Solid/MoneyBill1
```

```text
include('fontawesome-6/Solid/MoneyBill1')
```



| Illustration | MoneyBill1 |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/MoneyBill1.png) | ![illustration for MoneyBill1](../../fontawesome-6/Solid/MoneyBill1.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MoneyBill1Xs>`
- `<$MoneyBill1Sm>`
- `<$MoneyBill1Md>`
- `<$MoneyBill1Lg>`





## MoneyBill1

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element MoneyBill1
include('fontawesome-6/Solid/MoneyBill1')

' renders the element
MoneyBill1('MoneyBill1', 'Money Bill1', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element MoneyBill1
include('fontawesome-6/Solid/MoneyBill1')

' renders the element
MoneyBill1('MoneyBill1', 'Money Bill1', 'an optional tech label', 'an optional description')
@enduml
```

