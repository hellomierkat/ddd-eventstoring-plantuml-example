# Xampp


```text
simpleicons-8/X/Xampp
```

```text
include('simpleicons-8/X/Xampp')
```



| Illustration | Xampp |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/X/Xampp.png) | ![illustration for Xampp](../../simpleicons-8/X/Xampp.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$XamppXs>`
- `<$XamppSm>`
- `<$XamppMd>`
- `<$XamppLg>`





## Xampp

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Xampp
include('simpleicons-8/X/Xampp')

' renders the element
Xampp('Xampp', 'Xampp', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Xampp
include('simpleicons-8/X/Xampp')

' renders the element
Xampp('Xampp', 'Xampp', 'an optional tech label', 'an optional description')
@enduml
```

