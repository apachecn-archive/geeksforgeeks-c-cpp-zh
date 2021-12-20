# STD::uniform _ real _ distribution max()方法在 C++中的使用示例

> 原文:[https://www . geesforgeks . org/stduniform _ real _ distribution-max-method-in-c-with-examples/](https://www.geeksforgeeks.org/stduniform_real_distribution-max-method-in-c-with-examples/)

C++中**均匀实分布类**的 **max()** 方法用来得到这个均匀实分布可以产生的最大可能值。

**语法:**

```
result_type max() const;

```

**参数:**该方法不接受任何参数。

**返回值:**这个方法返回这个均匀实分布中可能产生的最大值。

**例:**

```
// C++ code to demonstrate
// the working of max() function

#include <iostream>

// for uniform_real_distribution function
#include <random>

using namespace std;

int main()
{
    double a = 10, b = 20.5;

    // Initializing of uniform_real_distribution class
    uniform_real_distribution<double> distribution(a, b);

    // Using max()
    cout << "Max value that can be generated"
         << " by this uniform_real_distribution: "
         << distribution.max() << endl;

    return 0;
}
```

**输出:**

```
Max value that can be generated by this uniform_real_distribution: 20.5

```

**参考:**T2【http://www . cplusplus . com/Reference/random/uniform _ real _ distribution/max/