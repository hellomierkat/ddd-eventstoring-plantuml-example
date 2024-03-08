# LibraryBooks


```text
material-4/Av/LibraryBooks
```

```text
include('material-4/Av/LibraryBooks')
```



| Illustration | LibraryBooks |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/LibraryBooks.png) | ![illustration for LibraryBooks](../../material-4/Av/LibraryBooks.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LibraryBooksXs>`
- `<$LibraryBooksSm>`
- `<$LibraryBooksMd>`
- `<$LibraryBooksLg>`





## LibraryBooks

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element LibraryBooks
include('material-4/Av/LibraryBooks')

' renders the element
LibraryBooks('LibraryBooks', 'Library Books', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element LibraryBooks
include('material-4/Av/LibraryBooks')

' renders the element
LibraryBooks('LibraryBooks', 'Library Books', 'an optional tech label', 'an optional description')
@enduml
```

