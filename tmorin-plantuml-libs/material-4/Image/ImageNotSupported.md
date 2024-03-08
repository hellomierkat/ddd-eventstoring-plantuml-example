# ImageNotSupported


```text
material-4/Image/ImageNotSupported
```

```text
include('material-4/Image/ImageNotSupported')
```



| Illustration | ImageNotSupported |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/ImageNotSupported.png) | ![illustration for ImageNotSupported](../../material-4/Image/ImageNotSupported.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ImageNotSupportedXs>`
- `<$ImageNotSupportedSm>`
- `<$ImageNotSupportedMd>`
- `<$ImageNotSupportedLg>`





## ImageNotSupported

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ImageNotSupported
include('material-4/Image/ImageNotSupported')

' renders the element
ImageNotSupported('ImageNotSupported', 'Image Not Supported', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ImageNotSupported
include('material-4/Image/ImageNotSupported')

' renders the element
ImageNotSupported('ImageNotSupported', 'Image Not Supported', 'an optional tech label', 'an optional description')
@enduml
```

