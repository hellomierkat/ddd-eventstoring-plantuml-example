# Voicemail


```text
material-4/Communication/Voicemail
```

```text
include('material-4/Communication/Voicemail')
```



| Illustration | Voicemail |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/Voicemail.png) | ![illustration for Voicemail](../../material-4/Communication/Voicemail.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VoicemailXs>`
- `<$VoicemailSm>`
- `<$VoicemailMd>`
- `<$VoicemailLg>`





## Voicemail

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Voicemail
include('material-4/Communication/Voicemail')

' renders the element
Voicemail('Voicemail', 'Voicemail', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element Voicemail
include('material-4/Communication/Voicemail')

' renders the element
Voicemail('Voicemail', 'Voicemail', 'an optional tech label', 'an optional description')
@enduml
```

