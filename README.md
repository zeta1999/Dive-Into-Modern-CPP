![Github stars](https://img.shields.io/github/stars/jpzhu-edu/Dive-Into-Modern-CPP.svg)
![github language](https://img.shields.io/badge/language-C++-green.svg)
![](https://img.shields.io/github/license/jpzhu-edu/Dive-Into-Modern-CPP.svg)
![](https://img.shields.io/github/forks/jpzhu-edu/Dive-Into-Modern-CPP.svg)

## Dive Into Modern CPlusPlus

The project is aim to dive into c++ new features for languages and standard library.
It is important to understand the nature of the new features. The C++ language
is getting better and better. These features are what I usually use more often.
But I prefer rust now 😅.

### C++ Standard

C++ 11, C++ 14, C++ 17, and C++ 20 are used usually.

### How to run the project

In macos,I use the vscode to `mkbuild`, `cmake`, `compile`, and `run` the project.
I write the `tasks.json` and `launch.json` files to use easily the project.

```shell
command + shift + B # select "compile" or "run" or "cmake" or "mkbuild"  tasks.json
```

Then select the following options:

1. mkbuild. It will build directory for the compile and run.
2. cmake. It will issue the Makefile.
3. compile. It will build the project.
4. run. It will run the some executable file in tasks.json.

```shell
F5  # debug launch.json
```

If you may add the different cpp files, you should add executable file in `CMakeLists.txt`.

### Outline of New Features

#### Languages
* 01 final and override [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/01_final_override.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/01_final_override.cpp)
* 02 lambda and functor [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/02_lambda.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/02_lambda.cpp)
* 03 `typdef`, `typename` and `using` [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/03_typedef_using.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/03_typedef_using.cpp)
* 04 enum [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/04_enum.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/04_enum.cpp)
* 05 auto, decltype and deducing types [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/05_auto_decltype.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/05_auto_decltype.cpp)
* 06 std::initializer_list and uniform initialization (一致初始化) [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/06_initializer_list.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/06_initializer_list.cpp)
* 07 Covariant Return Types [Document](https://quuxplusone.github.io/blog/2019/01/20/covariance-and-contravariance/)
* 08 noexcept [Document]() [Code]()
* 09 smart pointer [Document]() [Code]()
* 10 universal reference, rvalue reference, move-aware class, move semantics, and perfect forwading [Document]() [Code]()
* 11 inline [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/11_inline.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/11_inline.cpp) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/test_inline_1.cpp) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/test_inline_2.cpp)
* 12 nullptr, 0, and NULL [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/12_nullptr.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/12_nullptr.cpp)
* 13 variadic templates and recursive programming [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/13_variadic_template.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/13_variadic_template.cpp)
* 14 Default Initializers for Member Variables and POD [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/14_default_initializer.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/14_default_initializer.cpp)
#### Standard Library

* SL1 type trait and C++ template [Document]() [Code]()
* SL2 std::bind and std::thread [Document]() [Code]()

#### Template Techniques


#### Concurrency
### Contribute

If you want to add new features, please open the pull requests.

### References

1. https://arne-mertz.de/category/cpp/modern-cpp/
2. Effective Modern C++, by Scott Meyers
3. C++ Crash Course: A Fast-Paced Introduction, by Josh Lospinoso
4. C++ Template: The Completion Guide (2nd), by David Vandevoorde
5. C++ Concurrency in Action (2nd). by ANTHONY WILLIAMS