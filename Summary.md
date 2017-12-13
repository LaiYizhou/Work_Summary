####1. 一个关于位运算的题目

现在有两个变量A和B，A的取值范围是[1, 9]，B的取值范围也是[1, 9]

需要保存该两个变量的值，完全可以用两个int即可，两个int，一共 32x2 位

如果是，为了节约空间而节约空间，为了位运算而位运算，完全可以使用 **8位** 就保存两个变量的值

总之：**使用一个Byte类型的变量就可以完成**

（注：在C#中，有一个值类型是byte，[官方文档](https://docs.microsoft.com/zh-cn/dotnet/csharp/language-reference/keywords/byte)）
