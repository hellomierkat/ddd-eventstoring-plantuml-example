# SurroundSound


```text
material-4/Av/SurroundSound
```

```text
include('material-4/Av/SurroundSound')
```



| Illustration | SurroundSound |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/SurroundSound.png) | ![illustration for SurroundSound](../../material-4/Av/SurroundSound.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SurroundSoundXs>`
- `<$SurroundSoundSm>`
- `<$SurroundSoundMd>`
- `<$SurroundSoundLg>`





## SurroundSound

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element SurroundSound
include('material-4/Av/SurroundSound')

' renders the element
SurroundSound('SurroundSound', 'Surround Sound', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element SurroundSound
include('material-4/Av/SurroundSound')

' renders the element
SurroundSound('SurroundSound', 'Surround Sound', 'an optional tech label', 'an optional description')
@enduml
```

