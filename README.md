# Lab 8 - Shadow Mapping

## Build Instructions

### Command Line

1. Download and Install CMake
2. Open a terminal
3. Run cmake:

```
cd <source_folder>
cmake -S . -B <build_folder>
cmake --build <build_folder> --target install
```

To generate an Xcode project from the command line use:

```
cd <source_folder>
cmake -S . -B <build_folder> -G Xcode
cmake --build <build_folder> --target install
```

**NOTE:** In the case of cmake the `<source_folder>` is the topmost folder with
a CMakeLists.txt file.

**NOTE:** The `<build_folder>` can be anything but is usually just named `build`.

**NOTE:** The `-G` flag sets the generator of the project to use. On **Linux**
and **macOS** this defaults to **Unix Makefiles**. On **Windows** the default
is **Visual Studio**.

**NOTE:** It's usually a good idea to delete the `<build_folder>` if you switch
generators.

### CMake GUI

You can use the CMake GUI to configure and generate the Visual Studio Project.

1. Download and Install CMake
2. Open the CMake GUI
3. Set the `Where is the source code:` field to the source folder
4. Set the `Where to build the binaries:` field to different location (e.g.: source_folder/build)
5. Click Configure
6. Select the project generator (this will be the project file that compiles program)
7. Click Generate

#### Windows

Once the project is created you can build the **ALL_BUILD** project followed by
building the **INSTALL** project.

#### Xcode

Once the project is created you can build the **ALL_BUILD** target followed by
the **INSTALL** target. 

#### Unix Make File

In the terminal:

```
cd <build_folder>
make install
```

## Running

Once built and installed, all the relevant files will be in the **dist** folder
at the top level of the source folder, along with the program assets, such as
textures, shaders and geometry. The assets generally need to be in the same
path as the program.

### Linux/macOS

In the terminal type:

```
./lab08
```

### Windows

Click on the **lab08.exe** from the File Explorer.

## References

Good place to learn OpenGL
https://www.learnopengl.com

Official OpenGL 4 Reference Documentation
https://www.khronos.org/registry/OpenGL-Refpages/gl4/

Official OpenGL Wiki
https://www.khronos.org/opengl/wiki/

Easy to Navigate OpenGL Function Documentation
http://docs.gl/

GLM Documentation
https://glm.g-truc.net/0.9.9/index.html

GLFW Documentation
https://www.glfw.org/

Good place for advanced graphics theory
https://www.scratchapixel.com/

#  COMP 371  Computer Graphics Shadow Mapping代写
# 加微信 powcoder

# [代做各类CS相关课程和程序语言](https://powcoder.com/)

# Programming Help Add Wechat powcoder

# Email: powcoder@163.com

[成功案例](https://powcoder.com/tag/成功案例/)

[java代写](https://powcoder.com/tag/java/) [c/c++代写](https://powcoder.com/tag/c/) [python代写](https://powcoder.com/tag/python/) [drracket代写](https://powcoder.com/tag/drracket/) [MIPS汇编代写](https://powcoder.com/tag/MIPS/) [matlab代写](https://powcoder.com/tag/matlab/) [R语言代写](https://powcoder.com/tag/r/) [javascript代写](https://powcoder.com/tag/javascript/)

[prolog代写](https://powcoder.com/tag/prolog/) [haskell代写](https://powcoder.com/tag/haskell/) [processing代写](https://powcoder.com/tag/processing/) [ruby代写](https://powcoder.com/tag/ruby/) [scheme代写](https://powcoder.com/tag/drracket/) [ocaml代写](https://powcoder.com/tag/ocaml/) [lisp代写](https://powcoder.com/tag/lisp/)

- [数据结构算法 data structure algorithm 代写](https://powcoder.com/category/data-structure-algorithm/)
- [计算机网络 套接字编程 computer network socket programming 代写](https://powcoder.com/category/network-socket/)
- [数据库 DB Database SQL 代写](https://powcoder.com/category/database-db-sql/)
- [机器学习 machine learning 代写](https://powcoder.com/category/machine-learning/)
- [编译器原理 Compiler 代写](https://powcoder.com/category/compiler/)
- [操作系统OS(Operating System) 代写](https://powcoder.com/category/操作系统osoperating-system/)
- [计算机图形学 Computer Graphics opengl webgl 代写](https://powcoder.com/category/computer-graphics-opengl-webgl/)
- [人工智能 AI Artificial Intelligence 代写](https://powcoder.com/category/人工智能-ai-artificial-intelligence/)
- [大数据 Hadoop Map Reduce Spark HBase 代写](https://powcoder.com/category/hadoop-map-reduce-spark-hbase/)
- [系统编程 System programming 代写](https://powcoder.com/category/sys-programming/)
- [网页应用 Web Application 代写](https://powcoder.com/category/web/)
- [自然语言处理 NLP natural language processing 代写](https://powcoder.com/category/nlp/)
- [计算机体系结构 Computer Architecture 代写](https://powcoder.com/category/computer-architecture/)
- [计算机安全密码学computer security cryptography 代写](https://powcoder.com/category/computer-security/)
- [计算机理论 Computation Theory 代写](https://powcoder.com/category/computation-theory/)
- [计算机视觉(Compute Vision) 代写](https://powcoder.com/category/计算机视觉compute-vision/)

