# Fence


```text
material-4/Places/Fence
```

```text
include('material-4/Places/Fence')
```



| Illustration | Fence |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Places/Fence.png) | ![illustration for Fence](../../material-4/Places/Fence.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FenceXs>`
- `<$FenceSm>`
- `<$FenceMd>`
- `<$FenceLg>`





## Fence

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Fence
include('material-4/Places/Fence')

' renders the element
Fence('Fence', 'Fence', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Fence
include('material-4/Places/Fence')

' renders the element
Fence('Fence', 'Fence', 'an optional tech label', 'an optional description')
@enduml
```

