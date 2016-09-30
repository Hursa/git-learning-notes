# Variables

## 变量定义
* 定义单个变量 `var variable_name type`
* 定义多个变量 `var name1, name2, name3 type`
* 定义并初始化 `var name1, name2, name3 type = a, b, c `
* 函数内定义并初始化变量  `name1, name2 := a, b`

NOTE: 变量声明了但没使用，就会编译报错。 全局变量必须用var

## 常量

常量定义： const name type = value

NOTE: 如果value能推导出type，可以不写type

## 内置基本类型

* int型： int8, int16, int32, int 64
* uint型: uint8 (byte), uint16, uint32, uint64

NOTE: 不同类型之间不能相互操作或赋值



