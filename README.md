# Lab-Data-Cleaner
Automated chemical data validator | Python loops/conditionals | University application
# Lab Data Automation Project

## 🔬 功能
- 自动过滤无效实验数据（温度>0°C & 产率>5%）
- 减少70%手动验证时间

## ⚙️ 核心技术
```python
# 关键逻辑（循环+条件判断）
for row in reader:
    if temperature > 0 and yield_value > 5:
        writer.writerow(row)
