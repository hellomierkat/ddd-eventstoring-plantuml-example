# Smartphone


```text
homecloud-2/Hardware/Smartphone
```

```text
include('homecloud-2/Hardware/Smartphone')
```



| Illustration | Smartphone | SmartphoneCard | SmartphoneGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../homecloud-2/Hardware/Smartphone.png) | ![illustration for Smartphone](../../homecloud-2/Hardware/Smartphone.Local.png) | ![illustration for SmartphoneCard](../../homecloud-2/Hardware/SmartphoneCard.Local.png) | ![illustration for SmartphoneGroup](../../homecloud-2/Hardware/SmartphoneGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SmartphoneXs>`
- `<$SmartphoneSm>`
- `<$SmartphoneMd>`
- `<$SmartphoneLg>`





## Smartphone

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('homecloud-2/bootstrap')

' loads the Item which embeds the element Smartphone
include('homecloud-2/Hardware/Smartphone')

' renders the element
Smartphone('Smartphone', 'Smartphone', 'an optional tech label', 'an optional description')
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
include('homecloud-2/bootstrap')

' loads the Item which embeds the element Smartphone
include('homecloud-2/Hardware/Smartphone')

' renders the element
Smartphone('Smartphone', 'Smartphone', 'an optional tech label', 'an optional description')
@enduml
```

## SmartphoneCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('homecloud-2/bootstrap')

' loads the Item which embeds the element SmartphoneCard
include('homecloud-2/Hardware/Smartphone')

' renders the element
SmartphoneCard('SmartphoneCard', 'Smartphone Card', 'an optional description')
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
include('homecloud-2/bootstrap')

' loads the Item which embeds the element SmartphoneCard
include('homecloud-2/Hardware/Smartphone')

' renders the element
SmartphoneCard('SmartphoneCard', 'Smartphone Card', 'an optional description')
@enduml
```

## SmartphoneGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('homecloud-2/bootstrap')

' loads the Item which embeds the element SmartphoneGroup
include('homecloud-2/Hardware/Smartphone')

' renders the element
SmartphoneGroup('SmartphoneGroup', 'Smartphone Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
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
include('homecloud-2/bootstrap')

' loads the Item which embeds the element SmartphoneGroup
include('homecloud-2/Hardware/Smartphone')

' renders the element
SmartphoneGroup('SmartphoneGroup', 'Smartphone Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

