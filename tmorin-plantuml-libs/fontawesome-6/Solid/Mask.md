# Mask


```text
fontawesome-6/Solid/Mask
```

```text
include('fontawesome-6/Solid/Mask')
```



| Illustration | Mask |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Mask.png) | ![illustration for Mask](../../fontawesome-6/Solid/Mask.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MaskXs>`
- `<$MaskSm>`
- `<$MaskMd>`
- `<$MaskLg>`





## Mask

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Mask
include('fontawesome-6/Solid/Mask')

' renders the element
Mask('Mask', 'Mask', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mask
include('fontawesome-6/Solid/Mask')

' renders the element
Mask('Mask', 'Mask', 'an optional tech label', 'an optional description')
@enduml
```

