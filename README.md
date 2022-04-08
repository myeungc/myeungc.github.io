

# C++ 20 New Features

https://github.com/AnthonyCalandra/modern-cpp-features/blob/master/CPP20.md#coroutines

https://changkun.de/modern-cpp/zh-cn/10-cpp20/

https://codeantenna.com/a/6KEVt7pz5X

https://www.jianshu.com/p/8c4952e9edec

https://www.1024sou.com/article/345226.html

https://blog.51cto.com/u_12444109/3031295

https://blog.csdn.net/qq_38289815/article/details/107402557

https://zhuanlan.zhihu.com/p/137646370

https://segmentfault.com/a/1190000040479687

 

### 语言特性（language features）


1、协程（coroutines）
2、概念与约束（concepts & constraints）
3、指定初始化（designated initializers）
4、lambdas 模板语法（template syntax for lambdas）
5、范围（Range）：基于范围的 For 循环初始化（range-based for loop with initializer）、基于范围的访问器、基于范围的原语、基于范围的 concept
6、Attributes（属性）：likely and unlikely 属性（likely and unlikely attributes）、nodiscard、no_unique_address
7、弃用 this 的隐式捕获（deprecate implicit capture of this）
8、非类型模板参数中的类类型（class types in non-type template parameters）
9、constexpr 虚函数（constexpr virtual functions）
10、explicit(bool)
11、立即函数（immediate functions）
12、using enum
13、lambda 捕获中的可变参数（lambda capture of parameter pack）
14、char8_t

 

### 库特性（library features）


1、概念库（concepts library）：核心语言（same_as、derived_from 、convertible_to 、common_with 、integral 、default_constructible ）、比较（boolean 、equality_comparable ）、对象（movable 、copyable、semiregular、regular ）、可调用（invocable 、predicate ）
2、同步缓冲输出流（synchronized buffered outputstream）
3、跨度容器视图（std::span）
4、位操作（bit operations）
5、数学常数（math constants）
6、谓词函数（std::is_constant_evaluated）
7、std::make_shared 支持数组（std::make_shared supports arrays）
8、字符串的 starts_with 和 ends_with 成员函数（starts_with and ends_with on strings）
9、检查关联容器是否有元素（check if associative container has element）
10、std::bit_cast 类型安全转换
11、std::midpoint 安全计算两个 int 数值的中间点
12、std::to_array 数组转换
