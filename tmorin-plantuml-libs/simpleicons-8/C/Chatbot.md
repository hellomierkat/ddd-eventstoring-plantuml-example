# Chatbot


```text
simpleicons-8/C/Chatbot
```

```text
include('simpleicons-8/C/Chatbot')
```



| Illustration | Chatbot |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/C/Chatbot.png) | ![illustration for Chatbot](../../simpleicons-8/C/Chatbot.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ChatbotXs>`
- `<$ChatbotSm>`
- `<$ChatbotMd>`
- `<$ChatbotLg>`





## Chatbot

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Chatbot
include('simpleicons-8/C/Chatbot')

' renders the element
Chatbot('Chatbot', 'Chatbot', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Chatbot
include('simpleicons-8/C/Chatbot')

' renders the element
Chatbot('Chatbot', 'Chatbot', 'an optional tech label', 'an optional description')
@enduml
```

