# Joomla


```text
simpleicons-8/J/Joomla
```

```text
include('simpleicons-8/J/Joomla')
```



| Illustration | Joomla |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/J/Joomla.png) | ![illustration for Joomla](../../simpleicons-8/J/Joomla.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$JoomlaXs>`
- `<$JoomlaSm>`
- `<$JoomlaMd>`
- `<$JoomlaLg>`





## Joomla

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Joomla
include('simpleicons-8/J/Joomla')

' renders the element
Joomla('Joomla', 'Joomla', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Joomla
include('simpleicons-8/J/Joomla')

' renders the element
Joomla('Joomla', 'Joomla', 'an optional tech label', 'an optional description')
@enduml
```

