# Morrisons


```text
simpleicons-8/M/Morrisons
```

```text
include('simpleicons-8/M/Morrisons')
```



| Illustration | Morrisons |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/M/Morrisons.png) | ![illustration for Morrisons](../../simpleicons-8/M/Morrisons.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MorrisonsXs>`
- `<$MorrisonsSm>`
- `<$MorrisonsMd>`
- `<$MorrisonsLg>`





## Morrisons

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Morrisons
include('simpleicons-8/M/Morrisons')

' renders the element
Morrisons('Morrisons', 'Morrisons', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Morrisons
include('simpleicons-8/M/Morrisons')

' renders the element
Morrisons('Morrisons', 'Morrisons', 'an optional tech label', 'an optional description')
@enduml
```

