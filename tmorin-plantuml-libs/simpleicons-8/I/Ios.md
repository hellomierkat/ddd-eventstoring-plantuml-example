# Ios


```text
simpleicons-8/I/Ios
```

```text
include('simpleicons-8/I/Ios')
```



| Illustration | Ios |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/I/Ios.png) | ![illustration for Ios](../../simpleicons-8/I/Ios.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$IosXs>`
- `<$IosSm>`
- `<$IosMd>`
- `<$IosLg>`





## Ios

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Ios
include('simpleicons-8/I/Ios')

' renders the element
Ios('Ios', 'Ios', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ios
include('simpleicons-8/I/Ios')

' renders the element
Ios('Ios', 'Ios', 'an optional tech label', 'an optional description')
@enduml
```

