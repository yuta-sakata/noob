# 菜鸡编程语言 (Noob)

菜鸡是一款功能完整的解释型编程语言，**基于灵雀编程语言（Sparrow）的分支项目**。菜鸡最大的特点是采用**纯拼音关键字编程**，让中文开发者能够使用熟悉的威妥玛式拼音来编写代码。语言支持静态类型系统、丰富的控制流、数组操作、函数式编程等现代编程语言特性，专为学习和实验而设计。

## 🌟 核心亮点

**拼音编程范式** - 菜鸡语言的所有关键字都使用威妥玛式拼音，如：
- `pien-liang` (变量) 代替传统的 `var`
- `han-shu` (函数) 代替传统的 `function`
- `ju` (如) 代替传统的 `if`
- `tang` (当) 代替传统的 `while`
- `fan-hui` (返回) 代替传统的 `return`

这种设计让中文母语者能够更自然地理解和编写代码，同时保持了编程语言的严谨性和表达力。

## 语言特性

菜鸡语言（Noob）是一种静态类型的解释型语言，继承自灵雀语言（Sparrow）的核心架构，具有以下特性：

- 🇨🇳 **纯拼音关键字**：所有语言关键字使用威妥玛式拼音，降低中文开发者的学习曲线
- 🎯 **静态类型系统**：支持完整的类型注解和类型检查（`cheng`、`fu`、`chuang`、`pu` 等）
- 🔧 **模块化架构**：采用模块化设计，易于扩展和维护
- 📊 **丰富的数据类型**：支持基本类型、数组、枚举等数据结构
- 🎛️ **完整的控制流**：`ju`/`fou-tse`、`tang`、`tso-tang`、`wei`、`kai-kuan` 等拼音控制语句
- 🚀 **函数式特性**：函数是一等公民，支持递归调用（使用 `han-shu` 定义）
- 🔒 **静态存储**：支持静态变量和常量（`ching pien-liang`、`ching heng`）
- 🛠️ **内置函数库**：提供丰富的拼音命名内置函数（如 `ta-yin-hang`、`chang-tu` 等）
- 🎨 **类型转换**：支持显式类型转换

## 完整功能列表

### ✅ 核心语言特性
- **词法分析器**：完整的词法分析，支持所有语言特性
- **语法分析器**：模块化解析器，支持复杂语法结构
- **抽象语法树**：完整的AST表示，支持所有语言结构
- **解释器引擎**：模块化解释器，高效执行代码
- **环境管理**：完整的作用域和变量管理
- **内存管理**：自动内存管理和垃圾回收

### ✅ 数据类型系统（拼音类型名）
- **基本类型**：`cheng`(整)、`fu`(浮)、`chuang`(串)、`pu`(布)、`kung`(空)、`wu`(无)
- **复合类型**：数组类型（如 `cheng[]`）
- **枚举类型**：支持有值和无值枚举（使用 `mei-chu` 定义）
- **类型转换**：显式类型转换（如 `(fu)cheng-chih`）
- **类型检查**：运行时类型验证（使用 `lei-hsing()` 函数）

### ✅ 变量和常量系统
- **变量声明**：单变量和多变量声明
- **常量声明**：单常量和多常量声明
- **静态存储**：静态变量和静态常量
- **作用域管理**：块级作用域和函数作用域

### ✅ 运算符系统
- **算术运算**：`+`、`-`、`*`、`/`、`%`
- **比较运算**：`<`、`<=`、`>`、`>=`、`==`、`!=`
- **逻辑运算**：`&&`、`||`、`!`
- **赋值运算**：`=`、数组元素赋值
- **一元运算**：`-`（负号）、`!`（逻辑非）
- **前缀运算**：`++var`、`--var`
- **后缀运算**：`var++`、`var--`

### ✅ 控制流结构
- **条件语句**：`ju`(如)、`fou-tse ju`(否则如)、`fou-tse`(否则)
- **循环语句**：`tang`(当)、`tso-tang`(做-当)、`wei`(为)
- **跳转语句**：`po`(破)、`fan-hui`(返回)
- **选择语句**：`kai-kuan`(开关)、`an-li`(案例)、`mo-jen`(默认)（支持fallthrough）

### ✅ 函数系统
- **函数定义**：支持参数和返回值类型
- **函数调用**：支持递归调用
- **静态函数**：静态函数声明和调用
- **参数传递**：值传递参数系统
- **返回值**：支持各种类型的返回值

### ✅ 数组操作
- **数组字面量**：`[1, 2, 3, 4, 5]`
- **数组访问**：`shu-tsu[so-yin]`
- **数组赋值**：`shu-tsu[so-yin] = chih`
- **数组方法**：`chang-tu()`、`tui()`、`tan()`、`chieh-pien()`

### ✅ 内置函数库
- **输入输出**：`ta-yin()`、`ta-yin-hang()`、`shu-ju()`
- **系统函数**：`shih-chung()`、`lei-hsing()`
- **数组函数**：`chang-tu()`、`tui()`、`tan()`、`tan-shu-tsu()`、`chieh-pien()`


## 快速开始

### 系统要求

- **编译器**：GCC (支持 C99 标准)
- **构建工具**：GNU Make
- **系统库**：数学库 (libm)
- **操作系统**：Linux、macOS、Windows (WSL)

### 安装与构建

```bash
# 克隆仓库
git clone https://github.com/yuta-sakata/noob.git
cd noob

# 编译项目
make

# 运行完整测试套件
make test
# 或者
./output/noob test.noob

# 清理构建文件
make clean
```

### Hello World

创建你的第一个菜鸡程序：

```noob
// hello.noob
han-shu main():kung {
    ta-yin-hang("Hello, Noob!");
    ta-yin-hang("欢迎使用菜鸡编程语言！");
}
```

运行程序：

```bash
./output/noob hello.noob
```

## 语法详解

### 数据类型

菜鸡支持以下数据类型：

```noob
// 基本数据类型
pien-liang cheng-chih:cheng = 42;
pien-liang fu-tien-chih:fu = 3.14159;
pien-liang tzu-chuan-chih:chuang = "Hello, Noob!";
pien-liang pu-erh-chih:pu = chen;

// 数组类型
pien-liang shu-tzu:cheng[] = [1, 2, 3, 4, 5];
pien-liang ming-tzu:chuang[] = ["Alice", "Bob", "Charlie"];

// 类型检查
ta-yin-hang("cheng-chih的类型:", lei-hsing(cheng-chih));
```

### 变量和常量声明

```noob
// 单个变量声明
pien-liang tan-i-pien-liang:cheng = 10;

// 多变量声明（共享类型和初始值）
pien-liang x, y, z:cheng = 5;

// 常量声明
heng HENG-TING-CHIH:cheng = 99;

// 多常量声明
heng A, B, C:chuang = "test";

// 静态变量和常量
ching pien-liang chuan-chu-chi-shu-chi:cheng = 0;
ching heng YUAN-CHOU-LU:fu = 3.14159;
ching heng TSU-TA-CHANG-TU, TSU-HSIAO-CHANG-TU:cheng = 100;
```

### 枚举类型

```noob
// 有值枚举
mei-chu Color {
    RED = 1,
    GREEN = 2,
    BLUE = 3
}

// 无值枚举（自动赋值）
mei-chu Status {
    INACTIVE,    // 0
    ACTIVE,      // 1
    PENDING      // 2
}

// 使用枚举
pien-liang tang-chien-yen-se = Color.RED;
pien-liang tang-chien-chuang-tai = Status.ACTIVE;

ju (tang-chien-yen-se == Color.RED) {
    ta-yin-hang("颜色是红色");
}
```

### 运算符

```noob
han-shu tse-shih-yun-suan-fu():kung {
    pien-liang a:cheng = 20, b:cheng = 6;
    
    // 算术运算
    ta-yin-hang("加法:", a + b);      // 26
    ta-yin-hang("减法:", a - b);      // 14
    ta-yin-hang("乘法:", a * b);      // 120
    ta-yin-hang("除法:", a / b);      // 3.333...
    ta-yin-hang("取模:", a % b);      // 2
    
    // 前缀和后缀运算
    pien-liang c:cheng = 5;
    ta-yin-hang("前缀递增:", ++c);    // 6
    ta-yin-hang("后缀递增:", c++);    // 6 (然后 c 变为 7)
    
    // 比较运算
    ta-yin-hang("大于:", a > b);      // true
    ta-yin-hang("等于:", a == b);     // false
    
    // 逻辑运算
    pien-liang chi-chih1:pu = chen, chi-chih2:pu = chia;
    ta-yin-hang("逻辑与:", chi-chih1 && chi-chih2);  // false
    ta-yin-hang("逻辑或:", chi-chih1 || chi-chih2);  // true
    ta-yin-hang("逻辑非:", !chi-chih1);          // false
}
```

### 控制流

```noob
han-shu tse-shih-kung-chih-liu():kung {
    // ju-fou-tse 语句
    pien-liang fen-shu:cheng = 85;
    ju (fen-shu >= 90) {
        ta-yin-hang("等级: A");
    } fou-tse ju (fen-shu >= 80) {
        ta-yin-hang("等级: B");
    } fou-tse {
        ta-yin-hang("等级: C");
    }
    
    // tang 循环
    pien-liang i:cheng = 1;
    tang (i <= 3) {
        ta-yin-hang("tang循环:", i);
        i++;
    }
    
    // tso-tang 循环
    pien-liang j:cheng = 1;
    tso {
        ta-yin-hang("tso-tang循环:", j);
        j++;
    } tang (j <= 2);
    
    // wei 循环
    wei (pien-liang k:cheng = 0; k < 3; k++) {
        ta-yin-hang("wei循环:", k);
    }
}
```

### Switch 语句

```noob
han-shu tse-shih-kai-kuan():kung {
    pien-liang jih:cheng = 3;
    
    kai-kuan (jih) {
        an-li 1:
            ta-yin-hang("星期一");
            po;
        an-li 2:
            ta-yin-hang("星期二");
            po;
        an-li 3:
            ta-yin-hang("星期三");
            po;
        mo-jen:
            ta-yin-hang("其他日期");
            po;
    }
    
    // 支持 fallthrough
    pien-liang teng-chi:chuang = "B";
    kai-kuan (teng-chi) {
        an-li "A":
        an-li "B":
        an-li "C":
            ta-yin-hang("及格");
            po;
        mo-jen:
            ta-yin-hang("不及格");
            po;
    }
}
```

### 函数定义与调用

```noob
// 带参数和返回值的函数
han-shu chia(pien-liang a:cheng, pien-liang b:cheng):cheng {
    fan-hui a + b;
}

// 递归函数
han-shu chieh-cheng(pien-liang n:cheng):cheng {
    ju (n <= 1) {
        fan-hui 1;
    }
    fan-hui n * chieh-cheng(n - 1);
}

// 静态函数
ching han-shu huo-chu-hsin-hsi():chuang {
    fan-hui "这是静态函数";
}

// 主函数
han-shu main():kung {
    pien-liang ho:cheng = chia(5, 3);
    pien-liang chieh-kuo:cheng = chieh-cheng(5);
    ta-yin-hang("5 + 3 =", ho);
    ta-yin-hang("5! =", chieh-kuo);
    ta-yin-hang(huo-chu-hsin-hsi());
}
```

### 数组操作

```noob
han-shu tse-shih-shu-tsu():kung {
    // 创建和初始化数组
    pien-liang shu-tzu:cheng[] = [1, 2, 3, 4, 5];
    ta-yin-hang("原始数组:", shu-tzu);
    ta-yin-hang("数组长度:", chang-tu(shu-tzu));
    
    // 访问和修改元素
    ta-yin-hang("第一个元素:", shu-tzu[0]);
    shu-tzu[2] = 99;
    ta-yin-hang("修改后:", shu-tzu);
    
    // 数组方法
    pien-liang hsin-shu-tsu:cheng[] = tui(shu-tzu, 6);
    ta-yin-hang("push后:", hsin-shu-tsu);
    
    pien-liang tsui-hou-yuan-su = tan(hsin-shu-tsu);
    pien-liang tan-chu-hou = tan-shu-tsu(hsin-shu-tsu);
    ta-yin-hang("弹出的元素:", tsui-hou-yuan-su);
    ta-yin-hang("pop后数组:", tan-chu-hou);
    
    // 数组切片
    pien-liang chieh-pien-shu-tsu = chieh-pien(shu-tzu, 1, 4);
    ta-yin-hang("切片 [1:4]:", chieh-pien-shu-tsu);
}
```

### 类型转换

```noob
han-shu tse-shih-lei-hsing-chuan-huan():kung {
    pien-liang cheng-chih:cheng = 42;
    pien-liang fu-tien-chih:fu = 3.14;
    
    // 显式类型转换
    ta-yin-hang("整数转浮点:", (fu)cheng-chih);    // 42.0
    ta-yin-hang("浮点转整数:", (cheng)fu-tien-chih);    // 3
}
```

## 内置函数参考

### 输入输出函数

```noob
// 打印函数（不换行）
ta-yin("Hello", "World", 123);

// 打印函数（换行）
ta-yin-hang("这会自动换行");
ta-yin-hang("支持多个参数:", 42, chen, 3.14);

// 用户输入
pien-liang ming-tzu:chuang = shu-ju("请输入你的名字: ");
ta-yin-hang("你好,", ming-tzu);
```

### 系统函数

```noob
// 获取当前时间戳
pien-liang tang-chien-shih-chien = shih-chung();
ta-yin-hang("当前时间戳:", tang-chien-shih-chien);

// 获取值的类型
pien-liang chih:cheng = 42;
ta-yin-hang("值的类型:", lei-hsing(chih));  // 输出: cheng
```

### 数组函数

```noob
pien-liang shu-tsu:cheng[] = [1, 2, 3];

// 获取数组长度
pien-liang chang-tu-chih:cheng = chang-tu(shu-tsu);
ta-yin-hang("数组长度:", chang-tu-chih);

// 添加元素（返回新数组）
pien-liang hsin-shu-tsu:cheng[] = tui(shu-tsu, 4);
ta-yin-hang("添加元素后:", hsin-shu-tsu);

// 弹出最后一个元素
pien-liang tsui-hou-yuan-su = tan(shu-tsu);        // 获取最后一个元素
pien-liang tan-chu-hou-shu-tsu:cheng[] = tan-shu-tsu(shu-tsu); // 获取移除最后元素后的数组
ta-yin-hang("弹出的元素:", tsui-hou-yuan-su);
ta-yin-hang("剩余数组:", tan-chu-hou-shu-tsu);

// 数组切片
pien-liang chieh-pien-shu-tsu:cheng[] = chieh-pien(shu-tsu, 0, 2);     // 从索引0到2（不包含2）
pien-liang tai-pu-chang:cheng[] = chieh-pien(shu-tsu, 1); // 从索引1到末尾
```

## 完整示例程序

以下是一个展示菜鸡语言主要特性的完整程序：

```noob
// 静态变量和常量
ching pien-liang chuan-chu-chi-shu-chi:cheng = 0;
ching heng YUAN-CHOU-LU:fu = 3.14159;

// 枚举定义
mei-chu Color {
    RED = 1,
    GREEN = 2,
    BLUE = 3
}

// 递归函数示例
han-shu fei-po-na-chi(pien-liang n:cheng):cheng {
    ju (n <= 1) {
        fan-hui n;
    }
    fan-hui fei-po-na-chi(n - 1) + fei-po-na-chi(n - 2);
}

// 数组处理函数
han-shu chu-li-shu-tsu(pien-liang shu-tsu:cheng[]):kung {
    ta-yin-hang("处理数组:", shu-tsu);
    ta-yin-hang("数组长度:", chang-tu(shu-tsu));
    
    // 计算数组元素和
    pien-liang ho:cheng = 0;
    wei (pien-liang i:cheng = 0; i < chang-tu(shu-tsu); i++) {
        ho = ho + shu-tsu[i];
    }
    ta-yin-hang("数组元素和:", ho);
}

// 主函数
han-shu main():kung {
    ta-yin-hang("=== 菜鸡语言演示程序 ===");
    
    // 基本数据类型
    pien-liang ming-cheng:chuang = "Noob";
    pien-liang pan-pen:fu = 1.0;
    pien-liang shih-fou-wen-ting:pu = chen;
    
    ta-yin-hang("语言名称:", ming-cheng);
    ta-yin-hang("版本:", pan-pen);
    ta-yin-hang("稳定版本:", shih-fou-wen-ting);
    
    // 控制流演示
    ju (shih-fou-wen-ting) {
        ta-yin-hang("当前版本稳定");
    } fou-tse {
        ta-yin-hang("当前版本为测试版");
    }
    
    // 循环和数组
    pien-liang shu-tzu:cheng[] = [1, 2, 3, 4, 5];
    chu-li-shu-tsu(shu-tzu);
    
    // 递归函数调用
    ta-yin-hang("斐波那契数列前10项:");
    wei (pien-liang i:cheng = 0; i < 10; i++) {
        ta-yin(fei-po-na-chi(i), " ");
    }
    ta-yin-hang();
    
    // 枚举使用
    pien-liang tang-chien-yen-se = Color.RED;
    kai-kuan (tang-chien-yen-se) {
        an-li Color.RED:
            ta-yin-hang("当前颜色: 红色");
            po;
        an-li Color.GREEN:
            ta-yin-hang("当前颜色: 绿色");
            po;
        an-li Color.BLUE:
            ta-yin-hang("当前颜色: 蓝色");
            po;
    }
    
    // 静态变量操作
    chuan-chu-chi-shu-chi = chuan-chu-chi-shu-chi + 1;
    ta-yin-hang("全局计数器:", chuan-chu-chi-shu-chi);
    ta-yin-hang("圆周率常量:", YUAN-CHOU-LU);
    
    ta-yin-hang("程序执行完成!");
}
```
