# Component Diagram
```plantuml
@startuml
package "Vision systeem"{
[Camera Lens] - [Vision Camera]
[Licht setup] -- [Vision Camera]
}
[Vision Camera] -- [PLC]
[PLC] -- [Pneumatische cilinder]
[Vision Camera] -- [Scada-systeem]
[PLC] -- [Scada-systeem]
[Pneumatische cilinder] -- [Cilinder sensor] 
[Conveyer] -- [PLC]
[Sensor conveyer] - [Conveyer]
@enduml
```
---