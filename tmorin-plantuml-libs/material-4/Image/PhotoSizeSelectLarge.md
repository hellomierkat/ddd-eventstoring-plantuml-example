# PhotoSizeSelectLarge


```text
material-4/Image/PhotoSizeSelectLarge
```

```text
include('material-4/Image/PhotoSizeSelectLarge')
```



| Illustration | PhotoSizeSelectLarge |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/PhotoSizeSelectLarge.png) | ![illustration for PhotoSizeSelectLarge](../../material-4/Image/PhotoSizeSelectLarge.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PhotoSizeSelectLargeXs>`
- `<$PhotoSizeSelectLargeSm>`
- `<$PhotoSizeSelectLargeMd>`
- `<$PhotoSizeSelectLargeLg>`





## PhotoSizeSelectLarge

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PhotoSizeSelectLarge
include('material-4/Image/PhotoSizeSelectLarge')

' renders the element
PhotoSizeSelectLarge('PhotoSizeSelectLarge', 'Photo Size Select Large', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PhotoSizeSelectLarge
include('material-4/Image/PhotoSizeSelectLarge')

' renders the element
PhotoSizeSelectLarge('PhotoSizeSelectLarge', 'Photo Size Select Large', 'an optional tech label', 'an optional description')
@enduml
```

