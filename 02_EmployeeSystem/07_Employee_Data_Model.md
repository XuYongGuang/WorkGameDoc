# 07 Employee Data Model

# Godot数据结构

```gdscript
class_name EmployeeData

var id:int
var name:String
var age:int

var execution:int
var creativity:int
var social:int
var resilience:int

var happiness:float
var stress:float
var belonging:float
var anxiety:float

var traits:Array
var relationships:Dictionary

var department_id:int
var level:int
var experience:int
```

---

# 设计原则

员工数据与表现分离。

EmployeeData负责存储。

EmployeeNode负责表现。

---

# 存档要求

支持JSON序列化。

支持版本升级。