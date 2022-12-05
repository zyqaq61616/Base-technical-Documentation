# CmakeList常用语法  
[Cmake官方文档](https://cmake.org/cmake/help/v3.16/index.html)
## Cmake基本语法  
### 1.set()语法  
用于显式的定义变量  
***
[Cmake set用法](https://blog.csdn.net/Calvin_zhou/article/details/104060927)  
### 2.include_directories()  
将指定目录添加到编译器的头文件搜索路径之下，指定的目录被解释成当前源码路径的**相对路径**。  
***
[include_directories用法](https://www.jianshu.com/p/e7de3de1b0fa)  
### 3.target_include_directories()  
指定目标包含的头文件路径。一般引用库路径使用这个命令，作为外部依赖项引入进来，target是自己项目生成的lib。  
***
[target_include_directories用法](https://zhuanlan.zhihu.com/p/82244559)  
## Ros Catkin特有语法  
### 1.find_package() 
find_package()是 cmake 中常见的宏，用于加载 catkin 宏和指定对其他 ROS 功能包的依赖关系。大概就是这个功能包需要依赖哪些其他的Cmake功能包。至少要包含一个catkin组件   
***
[find_package用法](https://blog.csdn.net/lcc816/article/details/82949880)
### 2.catkin_package()  
catkin_package()是catkin提供的CMake宏，用于为catkin提供构建、生成pkg-config和CMake文件所需要的信息。
***
[Catkin_package语法](https://zhuanlan.zhihu.com/p/299148013)

