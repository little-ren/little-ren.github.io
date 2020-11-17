---
layout: post
title:  "检查编译器是否支持C++11"
date: 2015-02-10 15:14:54 
categories: c++
tags: c++
excerpt: c++还是我的白月光啊。
mathjax: true
---

```c++
#include <iostream>

using namespace std;


int main()
{
    cout << __cplusplus << endl;
  
    return 0;
}
```