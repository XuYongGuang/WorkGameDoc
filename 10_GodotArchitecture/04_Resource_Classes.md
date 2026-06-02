# 04 Resource Classes

# TraitResource

extends Resource

字段：
TraitID
Name
Rarity
Tags
Effects

---

# EventResource

字段：
EventID
Weight
Conditions
Results

---

# ProjectResource

字段：
ProjectID
Type
Reward
Risk
Duration

---

# EmployeeTemplateResource

字段：
Attributes
Traits
Salary

---

# 原则

配置资源只存数据。

逻辑全部位于System层。