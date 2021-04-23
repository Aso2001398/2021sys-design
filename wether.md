```uml
@startuml
start

:wether;
if(wether=0) then (true)
:快晴です;
else if(wether=1) then (true)
:曇りです;
else if(wether=2) then (true)
:雨です;
else
:不明です;
endif

stop
@enduml
```
