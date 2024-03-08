# VolumeXmark


```text
fontawesome-6/Solid/VolumeXmark
```

```text
include('fontawesome-6/Solid/VolumeXmark')
```



| Illustration | VolumeXmark |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/VolumeXmark.png) | ![illustration for VolumeXmark](../../fontawesome-6/Solid/VolumeXmark.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VolumeXmarkXs>`
- `<$VolumeXmarkSm>`
- `<$VolumeXmarkMd>`
- `<$VolumeXmarkLg>`





## VolumeXmark

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element VolumeXmark
include('fontawesome-6/Solid/VolumeXmark')

' renders the element
VolumeXmark('VolumeXmark', 'Volume Xmark', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element VolumeXmark
include('fontawesome-6/Solid/VolumeXmark')

' renders the element
VolumeXmark('VolumeXmark', 'Volume Xmark', 'an optional tech label', 'an optional description')
@enduml
```

