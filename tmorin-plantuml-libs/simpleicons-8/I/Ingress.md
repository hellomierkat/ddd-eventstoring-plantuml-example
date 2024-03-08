# Ingress


```text
simpleicons-8/I/Ingress
```

```text
include('simpleicons-8/I/Ingress')
```



| Illustration | Ingress |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/I/Ingress.png) | ![illustration for Ingress](../../simpleicons-8/I/Ingress.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$IngressXs>`
- `<$IngressSm>`
- `<$IngressMd>`
- `<$IngressLg>`





## Ingress

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Ingress
include('simpleicons-8/I/Ingress')

' renders the element
Ingress('Ingress', 'Ingress', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ingress
include('simpleicons-8/I/Ingress')

' renders the element
Ingress('Ingress', 'Ingress', 'an optional tech label', 'an optional description')
@enduml
```

