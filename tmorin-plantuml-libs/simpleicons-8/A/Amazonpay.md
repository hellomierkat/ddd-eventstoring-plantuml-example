# Amazonpay


```text
simpleicons-8/A/Amazonpay
```

```text
include('simpleicons-8/A/Amazonpay')
```



| Illustration | Amazonpay |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Amazonpay.png) | ![illustration for Amazonpay](../../simpleicons-8/A/Amazonpay.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonpayXs>`
- `<$AmazonpaySm>`
- `<$AmazonpayMd>`
- `<$AmazonpayLg>`





## Amazonpay

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Amazonpay
include('simpleicons-8/A/Amazonpay')

' renders the element
Amazonpay('Amazonpay', 'Amazonpay', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Amazonpay
include('simpleicons-8/A/Amazonpay')

' renders the element
Amazonpay('Amazonpay', 'Amazonpay', 'an optional tech label', 'an optional description')
@enduml
```

