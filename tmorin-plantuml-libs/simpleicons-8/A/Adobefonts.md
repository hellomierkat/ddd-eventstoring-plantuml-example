# Adobefonts


```text
simpleicons-8/A/Adobefonts
```

```text
include('simpleicons-8/A/Adobefonts')
```



| Illustration | Adobefonts |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Adobefonts.png) | ![illustration for Adobefonts](../../simpleicons-8/A/Adobefonts.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AdobefontsXs>`
- `<$AdobefontsSm>`
- `<$AdobefontsMd>`
- `<$AdobefontsLg>`





## Adobefonts

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Adobefonts
include('simpleicons-8/A/Adobefonts')

' renders the element
Adobefonts('Adobefonts', 'Adobefonts', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Adobefonts
include('simpleicons-8/A/Adobefonts')

' renders the element
Adobefonts('Adobefonts', 'Adobefonts', 'an optional tech label', 'an optional description')
@enduml
```

