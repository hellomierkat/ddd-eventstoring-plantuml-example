# Github


```text
simpleicons-8/G/Github
```

```text
include('simpleicons-8/G/Github')
```



| Illustration | Github |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Github.png) | ![illustration for Github](../../simpleicons-8/G/Github.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GithubXs>`
- `<$GithubSm>`
- `<$GithubMd>`
- `<$GithubLg>`





## Github

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Github
include('simpleicons-8/G/Github')

' renders the element
Github('Github', 'Github', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Github
include('simpleicons-8/G/Github')

' renders the element
Github('Github', 'Github', 'an optional tech label', 'an optional description')
@enduml
```

