# AwsNetworkFirewall


```text
aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall
```

```text
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall')
```



| Illustration | AwsNetworkFirewall | AwsNetworkFirewallCard | AwsNetworkFirewallGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall.png) | ![illustration for AwsNetworkFirewall](../../../aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall.Local.png) | ![illustration for AwsNetworkFirewallCard](../../../aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewallCard.Local.png) | ![illustration for AwsNetworkFirewallGroup](../../../aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewallGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsNetworkFirewallXs>`
- `<$AwsNetworkFirewallSm>`
- `<$AwsNetworkFirewallMd>`
- `<$AwsNetworkFirewallLg>`





## AwsNetworkFirewall

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsNetworkFirewall
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall')

' renders the element
AwsNetworkFirewall('AwsNetworkFirewall', 'Aws Network Firewall', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsNetworkFirewall
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall')

' renders the element
AwsNetworkFirewall('AwsNetworkFirewall', 'Aws Network Firewall', 'an optional tech label', 'an optional description')
@enduml
```

## AwsNetworkFirewallCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsNetworkFirewallCard
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall')

' renders the element
AwsNetworkFirewallCard('AwsNetworkFirewallCard', 'Aws Network Firewall Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsNetworkFirewallCard
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall')

' renders the element
AwsNetworkFirewallCard('AwsNetworkFirewallCard', 'Aws Network Firewall Card', 'an optional description')
@enduml
```

## AwsNetworkFirewallGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsNetworkFirewallGroup
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall')

' renders the element
AwsNetworkFirewallGroup('AwsNetworkFirewallGroup', 'Aws Network Firewall Group', 'an optional tech label') {
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
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2023/bootstrap')

' loads the Item which embeds the element AwsNetworkFirewallGroup
include('aws-q2-2023/Architecture/SecurityIdentityCompliance/AwsNetworkFirewall')

' renders the element
AwsNetworkFirewallGroup('AwsNetworkFirewallGroup', 'Aws Network Firewall Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

