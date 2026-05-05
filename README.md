更多学习资料：https://github.com/Tuning-Luna/HFUT_XC_Study_Things

# 栈数据结构实现项目

本项目包含两种栈的实现方式

## 文件说明

- `stack_array.cpp`: 基于数组的栈实现
- `stack_link.cpp`: 基于链表的栈实现

## 功能特性

- **push(int elem)**: 向栈中添加元素
- **pop()**: 弹出栈顶元素
- **top()**: 获取栈顶元素值
- **size()**: 获取栈中元素数量
- **empty()**: 检查栈是否为空
- **clear()**: 清空栈中所有元素

## 使用限制

- 最大容量：100个元素（由MAX_SIZE常量定义）
- 当栈满时尝试push会输出"满栈！"
- 当栈空时尝试pop或top会输出"空栈！"

## 注意事项

- 实现使用了链表结构存储数据
- 第一个节点的\_val成员存储栈中元素的数量
- this->\_next指针指向栈顶元素

## 编译运行

```bash
g++ stack_link.cpp -o stack_program
./stack_program
```
