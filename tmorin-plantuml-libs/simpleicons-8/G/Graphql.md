# Graphql


```text
simpleicons-8/G/Graphql
```

```text
include('simpleicons-8/G/Graphql')
```



| Illustration | Graphql |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Graphql.png) | ![illustration for Graphql](../../simpleicons-8/G/Graphql.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GraphqlXs>`
- `<$GraphqlSm>`
- `<$GraphqlMd>`
- `<$GraphqlLg>`





## Graphql

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Graphql
include('simpleicons-8/G/Graphql')

' renders the element
Graphql('Graphql', 'Graphql', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Graphql
include('simpleicons-8/G/Graphql')

' renders the element
Graphql('Graphql', 'Graphql', 'an optional tech label', 'an optional description')
@enduml
```

