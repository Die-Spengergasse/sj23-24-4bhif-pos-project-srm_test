# Project

Beschreibung vom Projekt

## Zweck

x

## Team

* A
* B

## Technologie

x

## Libraries

x

## Domain Model

x

``` plantuml

@startuml

class Person {
    - FirstName: string
    - LastName: string
    Create(Person item)
    Update(Guid Id, Person item)
    Delete(Guid Id)
    ChangePassword(string OldPasswrod, string NewPassword)
    PasswordForgotten(Guid Id)
}

@enduml

```

