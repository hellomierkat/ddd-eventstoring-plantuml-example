# Microphone


```text
fontawesome-6/Solid/Microphone
```

```text
include('fontawesome-6/Solid/Microphone')
```



| Illustration | Microphone |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Microphone.png) | ![illustration for Microphone](../../fontawesome-6/Solid/Microphone.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MicrophoneXs>`
- `<$MicrophoneSm>`
- `<$MicrophoneMd>`
- `<$MicrophoneLg>`





## Microphone

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Microphone
include('fontawesome-6/Solid/Microphone')

' renders the element
Microphone('Microphone', 'Microphone', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Microphone
include('fontawesome-6/Solid/Microphone')

' renders the element
Microphone('Microphone', 'Microphone', 'an optional tech label', 'an optional description')
@enduml
```

