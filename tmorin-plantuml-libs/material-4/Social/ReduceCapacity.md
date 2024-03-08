# ReduceCapacity


```text
material-4/Social/ReduceCapacity
```

```text
include('material-4/Social/ReduceCapacity')
```



| Illustration | ReduceCapacity |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/ReduceCapacity.png) | ![illustration for ReduceCapacity](../../material-4/Social/ReduceCapacity.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ReduceCapacityXs>`
- `<$ReduceCapacitySm>`
- `<$ReduceCapacityMd>`
- `<$ReduceCapacityLg>`





## ReduceCapacity

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ReduceCapacity
include('material-4/Social/ReduceCapacity')

' renders the element
ReduceCapacity('ReduceCapacity', 'Reduce Capacity', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ReduceCapacity
include('material-4/Social/ReduceCapacity')

' renders the element
ReduceCapacity('ReduceCapacity', 'Reduce Capacity', 'an optional tech label', 'an optional description')
@enduml
```

