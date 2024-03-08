# Adyen


```text
simpleicons-8/A/Adyen
```

```text
include('simpleicons-8/A/Adyen')
```



| Illustration | Adyen |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Adyen.png) | ![illustration for Adyen](../../simpleicons-8/A/Adyen.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AdyenXs>`
- `<$AdyenSm>`
- `<$AdyenMd>`
- `<$AdyenLg>`





## Adyen

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Adyen
include('simpleicons-8/A/Adyen')

' renders the element
Adyen('Adyen', 'Adyen', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Adyen
include('simpleicons-8/A/Adyen')

' renders the element
Adyen('Adyen', 'Adyen', 'an optional tech label', 'an optional description')
@enduml
```

