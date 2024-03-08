# Dolby


```text
simpleicons-8/D/Dolby
```

```text
include('simpleicons-8/D/Dolby')
```



| Illustration | Dolby |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/D/Dolby.png) | ![illustration for Dolby](../../simpleicons-8/D/Dolby.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DolbyXs>`
- `<$DolbySm>`
- `<$DolbyMd>`
- `<$DolbyLg>`





## Dolby

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Dolby
include('simpleicons-8/D/Dolby')

' renders the element
Dolby('Dolby', 'Dolby', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Dolby
include('simpleicons-8/D/Dolby')

' renders the element
Dolby('Dolby', 'Dolby', 'an optional tech label', 'an optional description')
@enduml
```

