# Ngrok


```text
simpleicons-8/N/Ngrok
```

```text
include('simpleicons-8/N/Ngrok')
```



| Illustration | Ngrok |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/N/Ngrok.png) | ![illustration for Ngrok](../../simpleicons-8/N/Ngrok.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$NgrokXs>`
- `<$NgrokSm>`
- `<$NgrokMd>`
- `<$NgrokLg>`





## Ngrok

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Ngrok
include('simpleicons-8/N/Ngrok')

' renders the element
Ngrok('Ngrok', 'Ngrok', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ngrok
include('simpleicons-8/N/Ngrok')

' renders the element
Ngrok('Ngrok', 'Ngrok', 'an optional tech label', 'an optional description')
@enduml
```

