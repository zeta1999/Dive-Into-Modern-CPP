## Dive Into Modern CPlusPlus

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
* 02 lambda expression [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/02_lambda.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/02_lambda.cpp)
* 03 typdef, typename and using [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/03_typedef_using.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/03_typedef_using.cpp)
* 04 enum [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/04_enum.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/04_enum.cpp)
* 05 auto, decltype and deducing types [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/05_auto_decltype.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/05_auto_decltype.cpp)
* 06 std::initializer_list and uniform initialization (一致初始化) [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/06_initializer_list.md) [Code](06_initializer_list.cpp)
* 07 variadic templates and recursive programming [Document]() [Code]()
* 08 const and constexpr [Document]() [Code]()
* 09 smart pointer [Document]() [Code]()
* 10 universal reference, rvalue reference, move-aware class, move semantics, and perfect forwading [Document]() [Code]()
* 11 inline [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/11_inline.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/11_inline.cpp) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/test_inline_1.cpp) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/test_inline_2.cpp)
* 12 nullptr, 0, and NULL [Document](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/12_nullptr.md) [Code](https://github.com/jpzhu-edu/Dive-Into-Modern-CPP/blob/main/12_nullptr.cpp)
* 13 Covariant Return Types [Document]() [Code]()
* 14 noexcept [Document]() [Code]()


#### Standard Library
* SL1 type trait [Document]() [Code]()
* SL2 std::bind and std::thread pass by reference [Document]() [Code]()
### Contribute

If you want to add new features, please open the pull requests.