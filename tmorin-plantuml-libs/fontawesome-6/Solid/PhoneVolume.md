# PhoneVolume


```text
fontawesome-6/Solid/PhoneVolume
```

```text
include('fontawesome-6/Solid/PhoneVolume')
```



| Illustration | PhoneVolume |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/PhoneVolume.png) | ![illustration for PhoneVolume](../../fontawesome-6/Solid/PhoneVolume.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PhoneVolumeXs>`
- `<$PhoneVolumeSm>`
- `<$PhoneVolumeMd>`
- `<$PhoneVolumeLg>`





## PhoneVolume

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element PhoneVolume
include('fontawesome-6/Solid/PhoneVolume')

' renders the element
PhoneVolume('PhoneVolume', 'Phone Volume', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PhoneVolume
include('fontawesome-6/Solid/PhoneVolume')

' renders the element
PhoneVolume('PhoneVolume', 'Phone Volume', 'an optional tech label', 'an optional description')
@enduml
```

