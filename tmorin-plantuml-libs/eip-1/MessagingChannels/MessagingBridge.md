# MessagingBridge


```text
eip-1/MessagingChannels/MessagingBridge
```

```text
include('eip-1/MessagingChannels/MessagingBridge')
```



| Illustration | MessagingBridge | MessagingBridgeGroup |
| :---: | :---: | :---: |
| ![illustration for Illustration](../../eip-1/MessagingChannels/MessagingBridge.png) | ![illustration for MessagingBridge](../../eip-1/MessagingChannels/MessagingBridge.Local.png) | ![illustration for MessagingBridgeGroup](../../eip-1/MessagingChannels/MessagingBridgeGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MessagingBridgeXs>`
- `<$MessagingBridgeSm>`
- `<$MessagingBridgeMd>`
- `<$MessagingBridgeLg>`





## MessagingBridge

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('eip-1/bootstrap')

' loads the Item which embeds the element MessagingBridge
include('eip-1/MessagingChannels/MessagingBridge')

' renders the element
MessagingBridge('MessagingBridge', 'Messaging Bridge', 'an optional tech label', 'an optional description')
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
include('eip-1/bootstrap')

' loads the Item which embeds the element MessagingBridge
include('eip-1/MessagingChannels/MessagingBridge')

' renders the element
MessagingBridge('MessagingBridge', 'Messaging Bridge', 'an optional tech label', 'an optional description')
@enduml
```

## MessagingBridgeGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('eip-1/bootstrap')

' loads the Item which embeds the element MessagingBridgeGroup
include('eip-1/MessagingChannels/MessagingBridge')

' renders the element
MessagingBridgeGroup('MessagingBridgeGroup', 'Messaging Bridge Group', 'an optional tech label') {
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
include('eip-1/bootstrap')

' loads the Item which embeds the element MessagingBridgeGroup
include('eip-1/MessagingChannels/MessagingBridge')

' renders the element
MessagingBridgeGroup('MessagingBridgeGroup', 'Messaging Bridge Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

