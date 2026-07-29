# 课程总结

## Day 1（2026-07-29）— 完成

**主题：**
- Part A：什么是 AI Agent（已讲）
- Part B：Python 入门
  - Topic 1：`print()` 与运行第一个程序（完成）
  - Topic 2：变量与 f-string（完成）
  - Topic 3：用户输入 `input()` 与类型转换（完成）
  - Topic 4：条件判断 `if/elif/else`（完成）
  - Topic 5：简易 Agent 模拟器（完成）

**学到的代码能力：**
- `print()`、变量、字符串、f-string
- `input()` + `int()`/`float()` 类型转换
- `:03d` / `:04.2f` 数字格式化
- `if/elif/else` + 比较运算符（`==`, `!=`, `<`, `>`, `<=`, `>=`）
- `in` 和 `or` 运算符
- 字符串方法 `.lower()`

**养成的工程习惯：**
- 文件头注释、PEP 8 命名
- VS Code + 终端运行 `.py`
- 亲手撞错自己修通：SyntaxError（句号外置）、f-string 缺 `f`、`else` 带条件、`or` 优先级
- 多次测试覆盖不同输入

**建立的概念：**
- Agent 与普通 LLM 的三大差异（推理 / 工具 / 记忆）
- API = 两个软件之间的对话约定
- 字符串 vs 数字的边界（`input()` 永远返回字符串）
- 健壮性：处理「意料之外的输入」（用 `.lower()` 兼容大小写）

**完成的练习：**
- 练习 1：`exercises/day1_topic1_hello.py` —— 3 行 print，成功运行。
- 练习 2：`exercises/day1_topic2_variables.py` —— 3 变量 / 3 print / 数字类型 / `:03d` 补零。
- 练习 3：`exercises/day1_topic3-input.py` —— 3 input + int 转换 + 除法 + `:04.2f` 格式化。
- 练习 4：`exercises/day1_topic4_conditionals.py` —— if/elif/else 命令检测器。
- 练习 5：`exercises/day1_topic5_agent.py` —— 迷你 Agent，支持大小写兼容、退出与未知分离。

**下一步：Day 2**
- Topic 1：while 循环 + break → Agent 支持多轮对话
- Topic 2：列表（list）→ Agent 记住用户的所有问题
- Topic 3：函数（function）→ 把 Agent 拆成模块
- Topic 4：字典（dict）→ 保存 Agent 状态
- Topic 5：综合升级 → 把 Day 1 的 Agent 重写为可读可扩展版本
