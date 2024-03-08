# Adobepremierepro


```text
simpleicons-8/A/Adobepremierepro
```

```text
include('simpleicons-8/A/Adobepremierepro')
```



| Illustration | Adobepremierepro |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/A/Adobepremierepro.png) | ![illustration for Adobepremierepro](../../simpleicons-8/A/Adobepremierepro.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AdobepremiereproXs>`
- `<$AdobepremiereproSm>`
- `<$AdobepremiereproMd>`
- `<$AdobepremiereproLg>`





## Adobepremierepro

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Adobepremierepro
include('simpleicons-8/A/Adobepremierepro')

' renders the element
Adobepremierepro('Adobepremierepro', 'Adobepremierepro', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Adobepremierepro
include('simpleicons-8/A/Adobepremierepro')

' renders the element
Adobepremierepro('Adobepremierepro', 'Adobepremierepro', 'an optional tech label', 'an optional description')
@enduml
```

