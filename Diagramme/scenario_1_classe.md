``` mermaid
@startuml
class Car {
  +startEngine()
}

class Driver {
  -car : Car
  +drive()
}
Driver -right-> Car : drives >
@enduml

