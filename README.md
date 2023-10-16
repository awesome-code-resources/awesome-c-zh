# Awesome C #
C好东西的精选清单。此列表包含*仅*[开源][13] 代码 (由链接的开源定义定义)，以及对物理资源不邪恶的卖家。
这是在Creative Commons-Attribution-ShareAlike许可证版本4 (SPDX代码 “CC-BY-SA-4.0”) 下发布的。您可以在许可证文件中找到其文本。

**一个重要的注意事项:**这个项目做*不*索引任何与C相关的东西; 只考虑纯C的东西。

**贡献者注意事项:**如果您想提出拉取请求，请先阅读贡献.md。

## Contents ##

* [AI](#ai) 人工智能
* [Benchmarking](#benchmarking) 基准测试
* [Build Systems](#build-systems) 构建系统
* [Compilers](#compilers) 编译器
* [Compression](#compression) 压缩
* [Concurrency and Parallelism](#concurrency-and-parallelism) 并发性和并行性
* [Crypto](#crypto) 加密
* [Database](#database) 数据库
* [Data Structures](#data-structures) 数据结构
* [Debugging](#debugging) 调试
* [Documentation Generation](#documentation-generation) 文档生成
* [Editors](#editors) 编辑者
* [Embeddable Scripting Engines](#embeddable-scripting-engines) 嵌入式脚本引擎
* [Frameworks](#frameworks) 框架
* [Game Programming](#game-programming) 游戏编程
* [Graphics](#graphics) 图形
* [Graphical User Interface](#graphical-user-interface) 图形用户界面
* [Hashing](#hashing) 散列
* [Learning, Reference and Tutorials](#learning-reference-and-tutorials) 学习、参考和教程
  * [Reference resources online](#reference-resources-online) 在线参考资源
  * [Beginner resources online](#beginner-resources-online) 初学者在线资源
  * [Intermediate resources online](#intermediate-resources-online) 在线中间资源
  * [Advanced resources online](#advanced-resources-online) 在线高级资源
  * [Reference books](#reference-books) 参考书
  * [Beginner books](#beginner-books) 初学者书籍
  * [Intermediate books](#intermediate-books) 中级书籍
  * [Advanced books](#advanced-books) 高级书籍
* [Lexing and Parsing](#lexing-and-parsing) 词法与句法分析
* [Memory Management](#memory-management) 内存管理
* [Multimedia](#multimedia) 多媒体
* [Networking and Internet](#networking-and-internet) 网络和互联网
* [Numerical](#numerical) 数值
* [Profiling](#profiling) 剖析
* [Regex](#regex) 正则表达式
* [Serialization](#serialization) 序列化
* [Source Code Collections](#source-code-collections) 源代码集合
* [Standard Libraries](#standard-libraries) 标准库
  * [Template Libraries](#template-libraries) 模板库
* [String Manipulation](#string-manipulation) 字符串操作
* [Structured File Processing](#structured-file-processing) 结构化文件处理
	* [CSV](#csv) CSV
	* [JSON](#json) JSON
	* [INI](#ini) INI
	* [Others](#others) 其他
	* [XML](#xml) XML
	* [YAML](#yaml) YAML
* [Testing](#testing) 测试
* [Text Editor Extensions](#text-editor-extensions) 文本编辑器扩展
* [Tools](#tools) 工具
* [Utilities](#utilities) 公用事业
* [Web Frameworks](#web-frameworks) Web框架
* [Windows Environments](#windows-environments) Windows环境

## AI ##
计算机视觉、神经网络、机器学习和其他类似的东西。基本上，如果你的大学称之为AI，它就住在这里。

* [ccv][195] - 基于C/缓存/核心计算机视觉库; 现代计算机视觉。[``BSD-3-Clause``][BSD-3-Clause]
* [Cranium][525] - C99中的便携式，仅标题ANN库。[``MIT``][MIT]
* [FANN][325] - 快速人工神经网络库; 神经网络的实现。[``GPL-2.0-only``][GPL-2.0-only]
* [Genann][412] - C89中的简单ANN，没有额外的依赖关系。[``Zlib``][Zlib]
* [KANN][327] - 两个文件的ANN库。[``MIT``][MIT]
* [LibDEEP][477] - 深度学习库。[``BSD-3-Clause``][BSD-3-Clause]
* [m2cgen][610] - 一个CLI工具，用于将经过训练的经典ML模型转换为具有零依赖关系的本机C代码。[``MIT``][MIT]
* [sod][611] -  嵌入式计算机视觉和机器学习库[``GPL-3``][GPL-3]

## Benchmarking ##
比较跨不同芯片/系统架构的各种子系统的性能。

* [b63][553] - 适用于C的轻量级微型基准测试工具。[``Apache-2.0``][Apache-2.0]

## Build Systems ##
在C中自动构建和测试项目的工具。

* [Autotools][583] - 也称为GNU构建系统 (automake，autoconf，libtool...) 是最广泛使用的构建系统之一 (configure & & mke)。[GPL-1.0-or-later][335]
* [Autotools project skeleton][584] - 一个简单的autotools骨架 (模板) 来快速引导新项目。[``BSD-2-Clause``][BSD-2-Clause]
* [CMake][329] - 用于构建、打包和测试软件的跨平台工具系列。[``BSD-3-Clause``][BSD-3-Clause]
* [GNU Make][324] - 控制程序的可执行文件和其他非源文件的生成的工具。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Meson][368] - 非常快速，用户友好的构建系统。基于忍者。[``Apache-2.0``][Apache-2.0]
* [Premake][435] - 命令行实用工具，它读取软件项目的脚本定义，并使用它为Visual Studio和GNU制作生成项目文件。其他目标也正在努力。[``BSD-3-Clause``][BSD-3-Clause]
* [SCons][521] - 使用Python的软件构建工具。[``MIT``][MIT]
* [xmake][271] - 跨平台构建实用程序。[``Apache-2.0``][Apache-2.0]
* [zproject][420] - 项目生成器和生成系统支持工具。[``MPL-2.0``][MPL-2.0]

## Compilers ##
编译器，以及编译器和编译相关的工具。

* [ccache][466] - 编译器缓存旨在加快重新编译。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Clang][38] - LLVM的编译器。支持c11。[``NCSA``][NCSA]
* [cproc][574] - 使用QBE作为后端的C11编译器。[``ISC``][ISC]
* [distcc][452] - 允许在几台机器之间分发构建的程序。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [Firm][361] - 库，提供适合在编译器中使用的基于图的中间表示，优化和汇编代码生成。带有相同许可证下的示例C前端。[``LGPL-2.1-only``][LGPL-2.1-only]
* [GCC][40] - 提供C编译器作为其编译器集的一部分。支持c11。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [PCC][74] - 古老的编译器。支持c99。[各种许可证][75]，全部开源。

## Compression ##

* [blosc][445] - 非常快速，多线程，元压缩器库。各种许可证，都是开源的。
* [Brotli][24] - 通用无损压缩算法库。具有与DEFLATE相当的速度，但压缩比要高得多。[''MIT''][麻省理工学院]。
* [clzip][432] - C版高质量数据压缩器[Lzip][433] (LZMA   implementation). [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [CRoaring][481] - C实现[Roaring bitmaps][482]. [``Apache-2.0``][Apache-2.0]
* [FiniteStateEntropy][2] - 为现代cpu优化的两个高效压缩编解码器。[``BSD-2-Clause``][BSD-2-Clause]
* [DENSITY][506] - 超快速压缩库。[``BSD-3-Clause``][BSD-3-Clause]
* [heatshrink][514] - 用于嵌入式和实时系统的数据压缩/解压缩库。[``ISC``][ISC]
* [fast\_zlib][533] - 改进的zlib，运行速度快2到10倍。[``BSD-3-Clause``][BSD-3-Clause]
* [fastLZ][586] - Lightning-fast无损压缩库 (LZ77型)。可植入小目标，如手臂皮质-M家族。源代码直接可在您的项目 (一对h/c文件)，没有动态内存分配。[``MIT``][MIT]
* [huffandpuff][214] - 最小霍夫曼编码器和解码器。公共领域。
* [libzip][587] - 用于读取，创建和修改zip存档的C库。[``BSD-3-Clause``][BSD-3-Clause]
* [libbzip2][427] - 无专利的高质量数据压缩库。[``BSD-4-Clause``][BSD-4-Clause]
* [Lizard][489] - 以前是LZ5; 快速减压的高效压缩机。以1000MB/s和更快的解压缩速度实现与zip和zlib相当的压缩比。[``BSD-2-Clause``][BSD-2-Clause]
* [lz4][508] - 库的一个非常快速的压缩算法。[``BSD-2-Clause``][BSD-2-Clause]
* [lzo][338] - 快速数据压缩库。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [pixz][49] - 并行，索引xz压缩机。[``BSD-2-Clause``][BSD-2-Clause]
* [shoco][363] - 小型文本字符串的压缩器。[``MIT``][MIT]
* [SIMDComp][519] - 使用二进制打包压缩整数列表的简单库。在x86上使用SIMD指令。[``BSD-3-Clause``][BSD-3-Clause]
* [smaz][364] - 高效的字符串压缩库。[``BSD-3-Clause``][BSD-3-Clause]
* [squash][393] - 压缩抽象库，完成一些实用程序。[``MIT``][MIT]
* [TurboPFor][471] - 最快的整数压缩。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [TurboRLE][484] - 最有效的运行长度编码。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [zip][520] - 真的真的很小的zip存档处理库。[``Unlicense``][Unlicense]
* [Zlib][230] - 大规模的spiffy但微妙的不显眼的压缩库。[``BSD-3-Clause``][BSD-3-Clause]
* [libarchive][548] - libarchive是一个可移植的，高效的C库，可以读取和写入各种格式的流档案。[``BSD-3-Clause``][BSD-3-Clause]
* [zlib-ng][1] - Zlib替换为 “下一代” 系统的优化。[``BSD-3-Clause``][BSD-3-Clause]
* [Zstandard][510] - 快速、无损的压缩算法，针对zlib级别或更高压缩比的实时压缩场景。[``BSD-3-Clause``][BSD-3-Clause]

## Concurrency and Parallelism ##

* [cchan][243] - 用于线程间通信的通道构造的小型库。公共领域。
* [checkedthreads][465] - 一个简单的并行性库，内置检查竞争条件。[``BSD-2-Clause``][BSD-2-Clause]
* [ck][242] - 并发原语，安全的内存回收机制和非阻塞数据结构。[``BSD-2-Clause``][BSD-2-Clause]
* [FCFS RWLock][540] - 先到先得的读者/作家锁定POSIX线程。[``CC0-1.0``][CC0-1.0]
* [Libaco][599] - 一个快速和轻量级的C非对称协联库。[``Apache-2.0``][Apache-2.0]
* [libconcurrent][390] - 并发编程库，使用协程，用于c11。[``BSD-3-Clause``][BSD-3-Clause]
* [libcsp][572] - 受CSP模型影响的高性能并发C库。[``MIT``][MIT]
* [libdill][442] - 库，使结构化并发编程变得容易。[``MIT``][MIT]
* [libhl][478] - 实现线程安全API的库来管理一系列数据结构。还为并发和无锁编程提供了一些支持功能和结构。[``LGPL-3.0-only``][LGPL-3.0-only]
* [liburcu][474] - 数据同步库，随核数线性扩展。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [mill][352] - Go风格的并发性。[``MIT``][MIT]
* [oclkit][311] - 双文件OpenCL包装器。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [OCL-MLA][312] - OpenCL中级抽象。[``BSD-3-Clause``][BSD-3-Clause]
* [OpenMP][37] - 为便于代码并行化而设计的杂注集。标准 (许可不适用)。
* [Open MPI][284] - 消息传递接口实现。[``BSD-3-Clause``][BSD-3-Clause]
* [pal][459] - 针对数学、并行处理和数据移动的优化库。[``Apache-2.0``][Apache-2.0]
* [pth][180] - 用于多个执行线程的非抢占式基于优先级的调度的便携式实现。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [pthreads][146] - POSIX线程库。标准 (不适用许可证)。
* [TinyCThread][115] - C11线程API的可移植的小型实现。[``Zlib``][Zlib]

## Crypto ##
主要是众所周知的加密算法或协议的库实现。

* [GNU SASL][160] - 实现了简单的身份验证和安全层以及一些常见的SASL机制。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [GnuTLS][112] - 安全通信库，实现SSL，TLS和DTLS。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libgcrypt][142] - 通用加密库，具有一系列可用的密码。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [OpenSSL][110] - SSL和TLS协议的实现。还包括密码库。[OpenSSL许可证和SSLeay许可证双重许可][111]。
* [liboqs][493] - 抗量子密码算法库。[``MIT``][MIT]
* [libsodium][198] - 现代和易于使用的加密库。[``MIT``][MIT]
* [libtomcrypt][299] - 相当全面，模块化和便携式加密工具包。公共领域。
* [mbed TLS][291] - 另一个加密实现。[``Apache-2.0``][Apache-2.0]
* [MIRACL][480] - 多精度整数和有理算术加密库; 用于椭圆曲线加密的SDK。[``AGPL-3.0-or-later``][AGPL-3.0-or-later]
* [retter][507] - 收集与密码学和安全性相关的哈希函数，密码，工具，库和资料。公共领域。
* [s2n][359] - C99实现了TLS/SSL协议，旨在简单，快速且以安全性为优先。[``Apache-2.0``][Apache-2.0]
* [sphlib][526] - 各种哈希函数的一组实现，包括几个加密函数。[``MIT``][MIT]
* [trezor-crypto][485] - 针对嵌入式设备进行了大量优化的加密算法。[``MIT``][MIT]
* [bfish][598] - 一个包括C99 Blowfish ECB加密库。公共领域。

## Database ##
使用C api的数据库和数据存储。

* [BerkeleyDB][380] - 用于键值数据的高性能嵌入式数据库的库。[``AGPL-3.0-only``][AGPL-3.0-only]
* [EJDB2][568] - 可嵌入的JSON数据库引擎。[``MIT``][MIT]
* [Groonga][524] - 带全文搜索的列式存储。[``LGPL-2.1-only``][LGPL-2.1-only]
* [Hiredis][201] - Redis的简约客户端库。[``BSD-3-Clause``][BSD-3-Clause]
* [libmongoc][233] - 高性能客户端库[MongoDB][234]. [``Apache-2.0``][Apache-2.0]
* [LMDB][105] - 超快速、超紧凑的键值嵌入式数据存储。[``OLDAP-2.8``][OLDAP-2.8]
* [MySQL][551] - 世界上最流行的开源数据库。[``GPL-2.0-only``][GPL-2.0-only]
* [PostgreSQL][121] - 强大的对象关系数据库系统。[``PostgreSQL``][PostgreSQL]
* [Redis][51] - 高级键值存储。[``BSD-3-Clause``][BSD-3-Clause]
* [sophia][244] - 现代的、可嵌入的键值数据库。[``BSD-2-Clause``][BSD-2-Clause]
* [sparkey][509] - 简单的常量键/值存储库。设计用于读取不常见的重载，大容量插入。[``Apache-2.0``][Apache-2.0]
* [SQLite][22] - 自包含、无服务器、零配置、事务性SQL数据库引擎。公共领域。
* [UnQLite][23] - 自包含、无服务器、零配置、事务性NoSQL引擎。[``BSD-2-Clause``][BSD-2-Clause]
* [WhiteDB][512] - 轻量级数据库库，完全在主内存中运行。[``GPL-3.0-or-later``][GPL-3.0-or-later]

## Data Structures ##

* [C-Macro-Collections][550] - 使用宏生成简单和通用的数据结构。[``MIT``][MIT]
* [CLIST][371] - 简单和轻量级[dynamic array][25] implementation.   [``BSD-2-Clause``][BSD-2-Clause]
* [Collections-C][406] - 通用数据结构库。[``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [ds][541] - 常见的数据结构和算法。[``MIT``][MIT]
* [igraph][544] - 图形处理库。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [kdtree][337] - 使用KD树的简单库。[``BSD-3-Clause``][BSD-3-Clause]
* [libavl][156] - 包含一系列自平衡二叉树的库。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libcdada][585] - C (C后端) 中用于基本数据结构 (列表，集合，映射，队列...) 的小型，可移植，无宏库。[``BSD-2-Clause``][BSD-2-Clause]
* [liblfds][411] - 可移植的无锁数据结构库。公共领域 (更确切地说，任何你想要的许可证)。
* [libsrt][305] - 软、硬实时数据结构[''BSD-3-Clause''][BSD-3-Clause]。
* [list.h][538] - 单链和双链表函数的实现。[``GPL-3.0-only``][GPL-3.0-only]
* [M\*LIB][350] - 库为泛型，但类型安全的C容器。实现为仅标头。[``BSD-2-Clause``][BSD-2-Clause]
* [offbrand][498] - 泛型、引用计数的数据结构的集合。[``MIT``][MIT]
* [PackedArray][241] - 任何所需宽度的紧密打包的无符号整数的随机访问数组。有一个SIMD优化的实现。[``WTFPL``][WTFPL]
* [rb3ptr][561] - 红黑树。公开了几乎所有的实现原语，因此可以用于增强、多个兼容的排序函数等场景。[``MIT``][MIT]
* [uthash][273] - 单文件哈希表实现。[``BSD-1-Clause``][BSD-1-Clause]
* [vector.h][154] - 类型化列表的头库。[``MIT``][MIT]

## Debugging ##
因为我们有时都必须这样做。使调试更容易或更好的各种工具，以及允许更好的调试工作的库或代码。

* [C-Reduce][403] - 工具，它采用具有感兴趣属性的大型C文件，并自动生成具有相同属性的小得多的C文件。旨在帮助在复杂代码中创建最小的bug演示案例。[``BSD-3-Clause``][BSD-3-Clause]
* [CBMC][309] - C有界模型检查器; 用于验证数组边界，指针安全性和用户指定断言的工具。[``BSD-4-Clause``][BSD-4-Clause]
* [cflow][404] - 分析源文件的集合，并在程序中打印图表控制流。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Complexity][307] - 用于测量源代码复杂性的工具。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [CScout][410] - C程序的源代码分析器和重构浏览器。[``GPL-3.0-only``][GPL-3.0-only]
* [DDD][320] - 一系列命令行调试器的图形前端。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [debug][467] - 一个头库更容易的 “printf调试”。[``MIT``][MIT]
* [ESBMC][567] - 高效的基于SMT的有界模型检查器; 用于验证单线程和多线程程序，用户断言，溢出和指针/内存安全的工具。[``Apache-2.0``][Apache-2.0]
* [GDB][87] - GNU项目调试器。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [lldb][468] - LLVM调试器。[``NCSA``][NCSA]
* [rr][95] - 记录非确定性执行以允许确定性调试的调试器。[``BSD-2-Clause``][BSD-2-Clause]
* [Valgrind][85] - 一系列动态分析工具，包括泄漏检查器。[``GPL-2.0-only``][GPL-2.0-only]

## Documentation Generation ##

* [Cxref][317] - 生成LaTeX，HTML，RTF或SGML文档。[``GPL-2.0-only``][GPL-2.0-only]
* [DocOnce][322] - 适当标记的标记语言，可用于生成一系列格式。[``BSD-3-Clause``][BSD-3-Clause]
* [Doxygen][318] - 用于从注释源生成文档的事实上的标准工具。可以生成大范围的格式。[``GPL-2.0-only``][GPL-2.0-only]

## Editors ##
Fancier，IDE类型的编辑器。如果你想要一个程序员的文本编辑器，看看其他地方。此外，无论你使用最有可能支持C反正。

* [Anjuta DevStudio][42] - GNOME IDE。[``GPL-2.0-only``][GPL-2.0-only]
* [Code::Blocks][249] - 可扩展的，可配置的IDE支持C.[``GPL-3.0-only``][GPL-3.0-only]
* [CodeLite][45] - 跨平台IDE。[``GPL-2.0-only``][GPL-2.0-only]
* [Geany][43] - 小而快速的IDE。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [KDevelop][44] - KDE IDE。[``GPL-2.0-only``][GPL-2.0-only]
* [zinjaI][578] - 简单，轻量级和功能丰富的IDE。[``GPL-3.0-only``][GPL-3.0-only]

# # 可嵌入的脚本引擎
当C不是正确的解决方案，或者当你需要一个更动态的配置引擎:

* [Duktape][591] - 嵌入式Javascript引擎，专注于可移植性和紧凑的足迹 [''MIT''][MIT]。
* [MetaCall][607] - 跨平台多语言运行时，支持NodeJS，JavaScript，TypeScript，Python，Ruby，C #，Wasm，Java，Cobol等。[``Apache-2.0``][Apache-2.0]

## Frameworks ##
提供数据结构和其他你期望的 “现代” 标准库的大型库。

* [APR][78] - Apache可移植运行时; 另一个跨平台实用程序函数库。[``Apache-2.0``][Apache-2.0]
* [C Algorithms][88] - 常用算法和数据结构的集合。[``ISC``][ISC]
* [CPL][308] - 通用管道库; 一组库，旨在成为一个全面，高效和强大的软件工具包。[``GPL-2.0-only``][GPL-2.0-only]
* [EFL][119] - 有用的数据结构和函数的大集合。各种许可证，都是开源的。
* [GLib][701] - 库的实用功能和结构，旨在是便携式的，高效的和强大的。[``LGPL-2.1-only``][LGPL-2.1-only]
* [klib][76] - 通用算法和数据结构的小型和轻量级实现。[``MIT``][MIT]
* [libcork][476] - 为资源受限系统设计的实用功能和结构。可以嵌入。[``BSD-3-Clause``][BSD-3-Clause]
* [libnih][93] - 轻量级的函数和结构库。[``GPL-2.0-only``][GPL-2.0-only]
* [libU][28] - 基本实用程序的小型库，包括内存分配，字符串操作和日志记录。[``BSD-3-Clause``][BSD-3-Clause]
* [PBL][346] - 大型实用程序库，其中包括数据结构。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [plibsys][588] - 跨平台系统C库。零第三方依赖项，仅使用本机系统调用。[``MIT``][MIT]
* [qlibc][277] - 简单而强大的库，旨在替代GLib，同时专注于小巧轻便。[``BSD-2-Clause``][BSD-2-Clause]
* [sc][595] - C的通用库和数据结构。[``MIT``][MIT]
* [TBOX][398] - 具有大量功能的多平台库。[``Apache-2.0``][Apache-2.0]
* [pspsdk][620] - 用于PSP自制程序开发的开源SDK。[各种许可证][621]。

## Game Programming ##
引擎、库和其他专门用于制作游戏的有用的东西。

* [Allegro][48] - 跨平台，视频游戏开发和多媒体库。[``Zlib``][Zlib]
* [AssetKit][571] 🎨基于COLLADA/glTF规格的3D资产进口商/出口商/实用库[``MIT``][MIT]
* [astera][594] - C99跨平台2D游戏库[``MIT``][MIT]
* [cglm][542] - 优化的OpenGL/图形数学 (glm) 为C。[``MIT``][MIT]
* [Chipmunk2D][303] - 快速和轻量级的2D游戏物理库。[``MIT``][MIT]
* [cmt][570] - C绑定/包装苹果的金属图形框架。[``MIT``][MIT]
* [Corange][101] - 纯C中的游戏引擎。[``BSD-2-Clause``][BSD-2-Clause]
* [CSFML][90] - 绑定为[SFML][91]. [``Zlib``][Zlib]
* [Darkplaces][369] - Quake2引擎的修改版本。[``GPL-2.0-only``][GPL-2.0-only]
* [Epoxy][414] - 用于处理OpenGL函数指针管理的库。[``MIT``][MIT]
* [exengine][618] - C99中的3D游戏引擎，带有起始模板。[``MIT``][MIT]
* [Flecs][557] - 为C89和C99编写的多线程实体组件系统[``MIT``][MIT]
* [Freecell Solver][539] - 一组库和命令行程序，用于自动解决纸牌接龙和一些类似的变体。[``MIT``][MIT]
* [FreeGLUT][99] - OpenGL实用工具工具包的替代。允许使用OpenGL上下文创建和管理窗口。[``X11``][X11]
* [GLFW][98] - 用于使用OpenGL上下文创建窗口的多平台库。[``Zlib``][Zlib]
* [ioquake3][107] - Quake3引擎，终于释放了。[``GPL-2.0-only``][GPL-2.0-only]
* [kazmath][446] - 数学图书馆的游戏。[``BSD-2-Clause``][BSD-2-Clause]
* [libao][376] - 具有各种输出的跨平台音频库。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [librg][558] - 纯C99游戏网络库，用于构建简单优雅的跨平台多人客户端-服务器解决方案。[``Apache-2.0``][Apache-2.0]
* [MATHC][534] - 用于2D和3D编程的数学库。[``ZLib``][Zlib]
* [Orx][370] - 便携式，轻量级，基于插件，数据驱动，面向2d的游戏引擎。[``Zlib``][Zlib]
* [Quake][225] - 地震发动机。[``GPL-2.0-only``][GPL-2.0-only]
* [Quake2][221] - Quake2发动机。[``GPL-2.0-only``][GPL-2.0-only]
* [raylib][516] - 简单易用的库来学习视频游戏编程。[``Zlib``][Zlib]
* [RetroArch][231] - 参考前端[libretro][232]. [``GPL-3.0-only``][GPL-3.0-only]
* [SDL2][50] - 跨平台库，旨在通过OpenGL提供对音频，键盘，鼠标，操纵杆和图形硬件的低级访问。[``Zlib``][Zlib]
* [sdl-gpu][457] - 高性能的现代2D图形库。基于SDL。[``MIT``][MIT]
* [SIGIL][429] - 声音，输入和图形集成库; 一个简单的替代其他库做所有这些事情。各种许可证，都是开源的。
* [uastar][535] - 最小A \*实施。[``ZLib``][Zlib]

## Graphics ##
C中图形的编程操作; 如果要制作GUI，则图形用户界面部分具有所需的内容。

* [AssetKit][571] 🎨基于COLLADA/glTF规格的3D资产进口商/出口商/实用库[``MIT``][MIT]
* [Cairo][384] - 2D图形库。[''LGPL-2.1-only''][LGPL-2.1-only] 或 [''MPL-1.1''][385]。
* [cmt][570] - C绑定/包装苹果的金属图形框架。[``MIT``][MIT]
* [giflib][401] - 用于读取和写入gif图像的库。[``MIT``][MIT]
* [graphene][515] - 图形数据类型的薄层。[``MIT``][MIT]
* [heman][365] - 处理高度地图，法线贴图，距离场等的图像实用程序的微型库。[``MIT``][MIT]
* [libcaca][366] - 用于基于终端的接口的ASCII渲染器。[``WTFPL``][WTFPL]
* [libgd][402] - 由程序员动态创建图像的库。[``MIT``][MIT]
* [libimagequant][300] - 小型便携式库，用于将RGBA图像高质量转换为8位索引彩色图像。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libjpeg-turbo][193] - 用于读取和写入JPEG文件的更快的库。[各种许可证][194]。
* [libpng][382] - 巴布亚新几内亚官方参考图书馆。[``Libpng``][Libpng]
* [libRSVG][417] - 库使用Cairo渲染SVG文件。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libsixel][17] - 库实现SIXEL协议，允许在您的终端漂亮的图形。[``MIT``][MIT]
* [libspng][68] - 一个更简单的读写PNG文件的界面。[``BSD-2-Clause``][BSD-2-Clause]
* [libvips][511] - 图像处理库。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libxmi][174] - 用于栅格化2D矢量图形的函数库。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [lightmapper][444] - 用于光照贴图烘焙的单文件库，使用现有的OpenGL渲染器。公共领域。
* [little CMS][600] - 色彩管理系统。它提供了ICC配置文件之间的快速转换。[``MIT``][MIT]
* [mozjpeg][200] - 改进的JPEG编码器。[``BSD-3-Clause``][BSD-3-Clause]
* [nanovg][505] - 在OpenGL之上的反锯齿2D矢量绘图库，用于UI和可视化。[``Zlib``][Zlib]
* [OpenGL][147] - 高性能图形的行业标准，具有本机C绑定。[各种许可证][148]。
* [PlutoVG][590] - C中的独立2D矢量图形库[``MIT``][MIT]
* [SAIL][601] - ⛵人类缺少的小型快速图像解码库 (不适用于机器)[``MIT``][MIT]

## Graphical User Interface ##
Widget工具包，或以类似方式使用它们的东西。

* [GTK+][14] - 跨平台小部件工具包。[``LGPL-2.1-only``][LGPL-2.1-only]
* [IUP][16] - 另一个跨平台小部件工具包。[``MIT``][MIT]
* [microui][616] - 用便携式ANSI C编写的微型即时模式UI库。[```MIT```][MIT]
* [nuklear][408] - 小，C89，单标题小部件工具包。公共领域。
* [tinyfiledialogs][426] - 用于简单对话框的单文件库。与许多其他工具包和操作系统兼容。[``Zlib``][Zlib]
* [Tk][19] - 基本小部件工具包。Tcl/Tk的一部分。[``TCL``][TCL]
* [XForms Toolkit][21] - 为XWindow系统设计的小部件工具包。[``LGPL-2.1-only``][LGPL-2.1-only]
* [LVGL][575] - 嵌入式GUI具有易于使用的图形元素，美丽的视觉效果和低内存占用。[``MIT``][MIT]
* [luigi][614] - Win32，X11和Essence的准系统单标题GUI库。[``MIT``][MIT]

## Hashing ##
的哈希函数实现*非*-加密目的。加密哈希可以在Crypto部分找到。

* [CLHash][495] - 库实现可笑的快速CLHash哈希函数。仅适用于Intel Haswell或更新版本。[``Apache-2.0``][Apache-2.0]
* [HighwayHash][527] - 快速，强大，SIMD-使用哈希函数。还包含SipHash的实现 (尽管速度较慢)。[``Apache-2.0``][Apache-2.0]
* [SpookyHash][326] - 非常快速的哈希函数。[``BSD-3-Clause``][BSD-3-Clause]
* [t1ha][530] - 快速正散列-一种可移植的快速散列函数。[``BSD-3-Clause``][BSD-3-Clause]
* [xxHash][522] - 非常快速的哈希算法。有32位和64位的品种。[``BSD-2-Clause``][BSD-2-Clause]

## Learning, Reference and Tutorials ##
一般学习C编程的资源，或与C编程相关的有用资源。

### Reference resources online ###

* [Benchmarks of the Lockless Memory Allocator][450]
* [C FAQ - comp.lang.c Frequently Asked Questions][262]
* [Comparison of C/POSIX standard library implementations for Linux][362]
* [Draft C89 standard][6]
* [Draft C99 standard][258]
* [Draft C11 standard][247]
* [Finding the best 64-bit simulation PRNG][529]
* [SEI CERT C Coding Standard][266]
* [tinyc.game][559] - Tiny C游戏，您可以立即编译和运行http:// tinyc.games[``MIT``][MIT]

### Beginner resources online ###

* [A tutorial on pointers][213]
* [A tutorial on portable Makefiles][528]
* [Building C Projects][208]
* [C Programming Wikibook][248]
* [Introduction to \`fun' C][279]
* [Learning C with GDB][349]
* [memcpy vs memmove][205]
* [POSIX Threads Programming tutorial][263] (有点过时，但大部分仍然有效和有用)
* [The GNU C Programming Tutorial][212] (在线PDF)
* [Templating in C][267]
* [What a C programmer should know about memory][227]
* [CodeforWin: Learn C Programming, Data Structures Tutorials and Exercises online][605]
* [Learn C: Free and Open-Source Interactive C Tutorial][606]
* [How to program a text adventure in C][615]

### Intermediate resources online ###

* [8 gdb tricks you should know][206]
* [10 C99 tricks][257]
* [A comprehensive MPI tutorial resource][454]
* [Build Your Own Text Editor][700]
* [Diving into concurrency: trying out mutexes and atomics][202]
* [Generic C reference counting][443]
* [How to write portable C without complicating your build][490]
* [Introduction to OpenMP][207] (视频)
* [OpenMP tutorial][264] (适用于OpenMP3标准)
* [MPI tutorial][265]
* [Scalable C - Writing Large-Scale Distributed C][391]
* [Some unknown features or tricks in C language][374]
* [What every C programmer should know about undefined behaviour][275]

### Advanced resources online ###

* [Advanced metaprogramming in C][357]
* [A quick tutorial on implementing and debugging malloc, free, calloc, and realloc][204]
* [Bit twiddling hacks][73]
* [Implementing smart pointers for the C programming language][240]
* [Inline functions in C][245]
* [Metaprogramming custom control structures in C][343]
* [Solving the temporary storage problem of C macros][358]
* [Some dark corners of C][210]
* [Writing efficient C and C code optimization][33]
* [Compiling Algebraic Data Types in Pure C99][608]

### Reference books ###

* [C: A Reference Manual 5E][181] - C99的完整参考书。
* [C in a Nutshell 2E][418] - C11简明参考书。
* [C Pocket Reference][182] - C99简明参考书。
* [The C Programming Language 2E][7] - 原书C，由其创作者。

### Beginner books ###

* [C Primer Plus 6E][184] - 完整的c11编程教程。
* [C Programming: A Modern Approach][64] - 学习C的基础知识的好书。
* [Head First C][102] - 学习C的 “Head-first” 样式书。

### Intermediate books ###

* [21st Century C][35] - 好_第二_C编程的书。
* [Understanding and Using C Pointers][36] - C中的指针上的深入资源。
* [ZeroMQ][183] - 使用ZeroMQ与C的书。

### Advanced books ###

* [Expert C Programming: Deep C Secrets][55] - 有趣，深入和有趣的看看C的内部。

## Lexing and Parsing ##
专门用于词法分析 (或词法) 和句法分析 (或解析) 的库。

* [flex][491] - 快速词法分析器生成器。[``BSD-2-Clause``][BSD-2-Clause]
* [GNU Bison][492] - 通用解析器生成器，将带注释的上下文无关语法转换为一系列解析器。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [hammer][356] - 二进制格式的解析器组合器。[``GPL-2.0-only``][GPL-2.0-only]
* [mpc][238] - 解析器组合程序库。[``BSD-2-Clause``][BSD-2-Clause]
* [owl][576] - 用于可视下推语言的解析器生成器。[``MIT``][MIT]
* [re2c][34] - Lexer生成器，生产快速Lexer，可以访问其内部。公共领域。

## Memory Management ##
无论是不同的，更快的malloc还是直接的垃圾收集，任何与管理C内存有关的事情都在这里。

* [Boehm GC][125] - C的垃圾收集。各种许可证，都是开源的。
* [jemalloc][293] - Malloc实现，强调避免碎片和可扩展的并发支持。[``BSD-2-Clause``][BSD-2-Clause]
* [Lockless Memory Allocator][451] - 高效的内存分配器。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libcsptr][66] - C的智能指针。[``MIT``][MIT]
* [rpmalloc][126] - 线程缓存，快速内存分配器，在32字节边界上自然对齐。公共领域。
* [talloc][353] - 具有析构函数的分层引用计数内存池系统。[``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [tlsf][531] - 两级隔离Fit分配器; 一种通用的动态内存分配器，旨在满足实时要求。[Up-to-date   implementation][532]. [``BSD-3-Clause``][BSD-3-Clause]

## Multimedia ##

* [aubio][523] - 音频和音乐分析库。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [FFMPEG][63] - 完整的跨平台解决方案，用于记录，转换和流式传输音频和视频。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [GStreamer][123] - 视听媒体框架。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libmpv][348] - 音乐播放库。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [libsndfile][458] - 用于读取和写入声音文件的库。支持多种格式。[``LGPL-2.1-only``][LGPL-2.1-only] or   [``LGPL-3.0-only``][LGPL-3.0-only]
* [libsoundio][372] - 用于跨平台、实时音频输入和输出的库。有一系列的后端。[``MIT``][MIT]
* [libVLC][556] - 完整的多媒体库，用于音频和视频编码，解码，播放和流式传输。[``GPL-2.0-only``][GPL-2.0-only]
* [lodepng][69] - 简单的PNG图像解码器和编码器，不需要其他依赖项。[``BSD-3-Clause``][BSD-3-Clause]
* [minimp3][536] - 轻量级MP3解码器单头库。[``CC0-1.0``][CC0-1.0]
* [Soundpipe][513] - 轻量级的音乐DSP库。[``MIT``][MIT]

## Networking and Internet ##
低级网络和互联网相关的东西。如果你想要更全面和更高层次的东西，你可能需要Web框架部分。

* [asnlc][138] - 将ASN.1规范编译成C源代码。[``BSD-2-Clause``][BSD-2-Clause]
* [CHL][422] - C超文本库-用于在C中编写web应用程序的库。[``GPL-3.0-only``][GPL-3.0-only]
* [czmq][226] - ZeroMQ的高级绑定。[``MPL-2.0``][MPL-2.0]
* [Dyad.c][554] - 轻量级，简单，异步网络库。[``MIT``][MIT]
* [GNU adns][155] - 高级，易于使用，异步功能的DNS客户端库和实用程序。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [gumbo-parser][196] - C99中的HTML5解析库。[``Apache-2.0``][Apache-2.0]
* [H20][127] - 新一代HTTP服务器。[``MIT``][MIT]
* [llhttp][197] - HTTP请求/响应解析器。[``MIT``][MIT]
* [ldns][339] - 库来简化DNS编程。[``BSD-3-Clause``][BSD-3-Clause]
* [libcurl][65] - 客户端URL传输库，支持多种格式。[``curl``][curl]
* [LibEtPan][222] - 邮件库为IMAP，SMTP，POP和NNTP提供了高效的网络。[``BSD-3-Clause``][BSD-3-Clause]
* [libev][144] - 又一个事件循环。[``BSD-2-Clause``][BSD-2-Clause]
* [libevent][124] - 网络服务器的事件循环替换。[``BSD-3-Clause``][BSD-3-Clause]
* [libhttpd][166] - 库向应用程序或嵌入式设备添加基本的web服务器功能。[``GPL-2.0-only``][GPL-2.0-only]
* [libhv][564] - 跨平台事件循环库。[``BSD-3-Clause``][BSD-3-Clause]
* [libidn][164] - 实现Stringprep、Punycode和IDNA规范。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libmicrohttpd][165] - 小型库，可以轻松地将HTTP服务器作为另一个应用程序的一部分运行。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libnl][582] - “Libnl” 是为Netlink协议提供api的库集合 (替代ioctl)。它的主要用途是与linux内核通信，修改网络状态 (接口，路由等)。[``LGPL-2.1-only``][LGPL-2.1-only]
* [libonion][170] - HTTP服务器库，旨在易于使用。[``Apache-2.0``][Apache-2.0]
* [libpcap][566] - API提供给各种内核数据包捕获机制。[``BSD-3-Clause``][BSD-3-Clause]
* [libquickmail][399] - 库旨在为开发人员提供一种从其应用程序发送电子邮件的方法。支持多个收件人/抄送/密件抄送收件人和附件，无大小限制。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libsagui][172] - 跨平台HTTP服务器库。[``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [libuhttpd][577] - 一个非常灵活，轻量级和完全异步的HTTP服务器库，基于libev和http解析器，用于嵌入式Linux。[``MIT``][MIT]
* [LibVNCServer][464] - 跨平台库来实现VNC服务器和/或客户端功能。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [libwebsock][261] - 易于使用和强大的web套接字库。[``LGPL-3.0-only``][LGPL-3.0-only]
* [libzmq][581] - 核心ZeroMQ库，一个高性能异步消息库，旨在用于分布式或并发应用程序。C API (后端C) [''GPL-3.0-or-later''][GPL-3.0-or-later] 有静态链接异常
* [lwan][199] - 实验性、可扩展、高性能的HTTP服务器。[``GPL-2.0-only``][GPL-2.0-only]
* [mongoose][171] - 嵌入式web服务器。[``GPL-2.0-only``][GPL-2.0-only]
* [MQTT-C][549] - 适用于嵌入式系统和pc的便携式MQTT C客户端。[``MIT``][MIT]
* [nanomsg][139] - ZeroMQ的基于C的实现[``MIT``][MIT]
* [NNG][106] - nanomsg-下一代-轻量级无代理消息传递。[``MIT``][MIT]
* [oSip][179] - SIP实现没有额外的依赖关系。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [silgy][579] - C/C项目的异步HTTP(S) 引擎。[``MIT``][MIT]
* [socket99][203] - BSD套接字API的C99包装。[``ISC``][ISC]
* [twitc][237] - 与Twitter OAuth API交互的迷你库。[``MIT``][MIT]
* [uriparser][100] - 严格符合RFC 3986的URI解析和处理库。[``BSD-3-Clause``][BSD-3-Clause]
* [Wslay][460] - WebSocket库。实现WebSocket协议的版本13，如RFC 6455中所述。[``MIT``][MIT]
* [zyre][419] - 基于邻近的对等应用程序的框架。[``MPL-2.0``][MPL-2.0]

## Numerical ##

* [apophenia][188] - 统计和科学计算图书馆。[``GPL-2.0-only``][GPL-2.0-only]
* [Arb][497] - 用于任意精度区间算术的库。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [ATLAS][137] - 自动调谐线性代数软件。[``BSD-3-Clause``][BSD-3-Clause]
* [clBLAS][439] - 用OpenCL编写的b拉斯函数。[``Apache-2.0``][Apache-2.0]
* [cmathl][546] - 数学库与各种各样的数学函数与cmaby构建支持。寻求接近C89/C90兼容的便携性。[``MIT``][MIT]
* [Cuba][316] - 多维数值积分库。[``LGPL-3.0-only``][LGPL-3.0-only]
* [fft-c][537] - 来自netlib的fftpack的高性能傅立叶变换; 以用户友好的格式包装[``MIT``][ MIT]
* [FFTW][70] - 西方最快的傅立叶变换; 高度优化的快速傅立叶变换例程。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [FLINT][255] - 数论的快速库; 支持数字，多项式，幂级数和矩阵等算术的库。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [GLPK][159] - GNU线性编程工具包; 用于解决大规模线性规划，混合整数规划和其他相关问题的软件包。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [GMP][79] - GNU多精度算术库; 用于任意精度算术的库。[``GPL-2.0-only``][GPL-2.0-only] or [``LGPL-3.0-only``][LGPL-3.0-only]
* [GNU MPC][175] - 复数算术库。[``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [GNU MPFR][176] - 任意精度浮点算术库。[``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [GNU MPRIA][177] - 多精度有理区间算法的便携式数学库。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [GSL][47] - GNU科学图书馆; 一个复杂的数字图书馆。[''GPL-3.0-only''][GPL-3.0-only]。
* [KISS FFT][71] - 简单的快速傅立叶变换库。[``BSD-3-Clause``][BSD-3-Clause]
* [LAPACKE][133] - 接口到[LAPACK][134]. [``BSD-3-Clause``][BSD-3-Clause]
* [LibTomMath][461] - 便携式，数论，多精度整数库。支持代数，数字操作，模块约简和各种数论例程。公共领域。
* [LibTomPoly][463] - 多项式相关的数学库。公共领域。
* [PARI/GP][256] - 数论的计算机代数系统; 包括C的编译器。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [PETSc][282] - 一套数据结构和例程，用于通过偏微分方程建模的科学应用程序的可扩展并行解决方案。[``BSD-2-Clause``][BSD-2-Clause]
* [SCS][483] - 分裂圆锥求解器; 求解大规模凸锥问题的数值优化包。[``MIT``][MIT]
* [SLEPc][283] - 用于在并行计算机上解决大型稀疏特征值问题的库。[``LGPL-3.0-only``][LGPL-3.0-only]
* [TomsFastMath][462] - 一组优化的数学运算 (在汇编中)，适合加密使用。公共领域。
* [Yeppp!][72] - 快速、SIMD优化的数学库[``BSD-3-Clause``][BSD-3-Clause]

## Profiling ##

* [gperftools][295] - 用于测量和改进性能的实用程序的集合。[``BSD-3-Clause``][BSD-3-Clause]
* [gprof][86] - 性能分析工具。GNU binutils的一部分。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [OProfile][475] - Linux的统计分析器。可以分析任何代码 (包括内核!)，开销低，无需重新编译。[``GPL-2.0-only``][GPL-2.0-only]
* [perf][375] - 基于linux内核的分析器，具有很多功能。[``GPL-2.0-only``][GPL-2.0-only]

## PDF ##

* [pdfio][612] - PDFio是一个简单的C库，用于读取和写入pdf文件。[``Apache-2.0``][Apache-2.0]

## Regex ##

* [Onigmo][518] - Oniguruma的叉子，支持更高级的regexps。[``BSD-2-Clause``][BSD-2-Clause]
* [Oniguruma][517] - 正则表达式库支持广泛的编码，并包含许多面向安全的修补程序。[``BSD-2-Clause``][BSD-2-Clause]
* [PCRE][83] - 实现与Perl 5相同的正则表达式。[``BSD-3-Clause``][BSD-3-Clause]
* [SLRE][80] - 超轻正则表达式库; Perl正则表达式语法子集的一个小实现。[``GPL-2.0-only``][GPL-2.0-only]
* [TRE][82] - POSIX兼容，功能完整的正则表达式库。[``BSD-2-Clause``][BSD-2-Clause]

## Serialization ##

* [binn][400] - 二进制序列化格式，意味着紧凑，快速和易于使用。[``Apache-2.0``][Apache-2.0]
* [c-capnproto][130] - Cap'n Proto序列化协议的实现。[``MIT``][MIT]
* [cmp][377] - 实施[MessagePack][379] serialization   protocol. [``MIT``][MIT]
* [flatcc][187] - [FlatBuffers][145] compiler and library.   [``Apache-2.0``][Apache-2.0]
* [libavro][140] - Avro数据序列化系统的实现[``Apache-2.0``][Apache-2.0]
* [mpack][378] - 的另一个实现[MessagePack][379] serialization   protocol. [``MIT``][MIT]
* [OPIC][397] - C中的对象持久性; 革命性的序列化框架，具有匹配的磁盘和内存表示形式。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [protobuf-c][129] - Google协议缓冲区的实现。[``BSD-2-Clause``][BSD-2-Clause]
* [tpl][473] - 小型二进制序列化库。[``MIT``][MIT]
* [xdr][131] - 外部数据表示; 数据序列化的标准。标准 (无许可证适用)。
* [pbtools][555] - Google Protocol Buffers C源代码生成器.[``MIT``][MIT]

## Source Code Collections ##
小源代码的集合。如果你想要一些大的和集成的东西，检查框架部分。

* [CCAN][103] - 仿照Perl的CPAN，这是一个很大的代码集合，做东西。完整列表是 [here][104]。各种许可证，都是开源的。
* [clib][26] - 包管理器的东西。附带一个[bunch of libraries of its own][27]. [``MIT``][MIT]
* [gnulib][46] - 通用GNU代码的集合。各种许可证，都是开源的。
* [libdjb][292] - 图书馆做各种事情的集合。(显然) 公共领域。
* [mmx][448] - 单头库的集合。各种许可证，都是开源的。
* [par][456] - 一堆单文件库。[``MIT``][MIT]
* [Snippets][220] - 有用的代码段和仅标题库。公共领域。
* [stb][114] - 单文件库的范围。公共领域。
* [tinyheaders][108] - 仅标题库的集合，主要面向游戏开发。[``Zlib``][Zlib]
* [zpl][602] - C99跨平台的标题只有库与许多好东西。[``BSD-3-Clause``, ``Unlicense``][BSD-3-Clause, Unlicense]

## Standard Libraries ##
(标准强制) C标准库的实现。

* [Bionic][4] - Google的标准库，为Android开发。[``BSD-3-Clause``][BSD-3-Clause]
* [cloudlibc][486] - 基于概念的标准库[capability-based security][487]. [``BSD-2-Clause``][BSD-2-Clause]
* [dietlibc][9] - 为尽可能小的二进制文件设计的标准库。[``GPL-2.0-only``][GPL-2.0-only]
* [glibc][57] - GNU C库; 标准库的实现。[''LGPL-2.1-only''][LGPL-2.1-only]。
* [musl][10] - 标准库，兼容POSIX 2008和c11。专为静态链接而设计。[``MIT``][MIT]
* [PDCLib][447] - 公共领域C库。实现了C99的大部分和c11的一些。[``CC0-1.0``][CC0-1.0]
* [uClibc-ng][12] - 用于开发嵌入式系统的小型C库。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]

### 模板库

* [CTL][613] - C容器模板库 (CTL)[``MIT``][MIT]

## String Manipulation ##

* [bstring][116] - 更好的字符串库。[``BSD-3-Clause``][BSD-3-Clause]
* [ICU][67] - Unicode的国际组件; 支持Unicode的库。[``ICU``][ICU]
* [levenstein.c][360] - [Levenstein距离][334] 算法实现.[''MIT''][麻省理工学院]。
* [libunistring][173] - 用于操作Unicode字符串的库。[``LGPL-3.0-only``][LGPL-3.0-only]
* [libgiconv][163] - 文本转换库。[``LGPL-2.1-only``][LGPL-2.1-only]
* [librope][479] - UTF-8绳子 (“沉重” 字符串) 库。[``MIT``][MIT]
* [SDS][29] - 简单的动态字符串; 一个以更简单的方式处理字符串的库，但与普通的C字符串函数兼容。可通过[clib][26]. [``BSD-2-Clause``][BSD-2-Clause]
* [stmr.c][383] - [Porter Stemmer][367] algorithm implementation. [``MIT``][MIT]
* [str][587] - 又一个c语言的字符串库。[``BSD-3-Clause``][BSD-3-Clause]
* [utf8.h][472] - 单头UTF-8库，旨在模仿C风格的字符串函数。公共领域。
* [utf8proc][469] - 用于处理UTF-8数据的库。[``MIT``][MIT]

## Structured File Processing ##
这包括XML、JSON、CSV和其他类似格式的库。

### CSV ###

* [libcsv][387] - 简单的流式CSV解析器。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]

### JSON ###

* [Jansson][53] - 用于编码，解码和操作JSON的库。[``MIT``][MIT]
* [jfes][488] - 用于嵌入式系统的JSON; 简单的JSON引擎，没有任何依赖关系。[``MIT``][MIT]
* [jsmn][120] - 简约的JSON解析器。[``MIT``][MIT]
* [json][39] - 简单，低内存使用JSON解析器。[``MIT``][MIT]
* [json-c][8] - 在C中轻松使用JSON。带有一个引用计数的对象模型，并旨在与[RFC 7159][11]. [``MIT``][MIT]
* [json.h][431] - 单文件非流式JSON解析器。[``Unlicense``][Unlicense]
* [parson][32] - 两个文件，C89-compatible JSON解析器。[``MIT``][MIT]
* [WJElement][77] - 高级JSON操作库，支持JSON架构。[``LGPL-2.0-or-later``][LGPL-2.0-or-later] or   [``LGPL-2.1-or-later``][LGPL-2.1-or-later] or [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [YAJL][60] - 快速流式JSON解析器库。[``ISC``][ISC]

### INI ###

* [inih][547] - 小而简单的ini文件解析器，适合嵌入式系统。[``BSD-3-Clause``][BSD-3-Clause]
* [iniparser][336] - 的解析器。ini文件。[``MIT``][MIT]
* [libconfini][122] - 还有一个INI解析器。[``GPL-3.0-only``][GPL-3.0-only]
* [minIni][109] - 小巧便携的INI解析器。[``Apache-2.0``][Apache-2.0]

### Others ###

* [libbson][235] - BSON实用程序库。[``Apache-2.0``][Apache-2.0]
* [libcbor][573]: C和其他人的CBOR协议实现。[``MIT``][MIT]
* [libconfuse][135] - 小型配置文件解析器库。[``ISC``][ISC]
* [libelf][310] - 解析ELF文件的简单库。[``MIT``][MIT]
* [libucl][239] - 通用配置库解析器。[``BSD-2-Clause``][BSD-2-Clause]
* [libxo][407] - 允许应用程序使用一组通用的函数调用生成纯文本、XML、JSON和HTML输出。应用程序在运行时决定应该产生什么输出样式。[``BSD-2-Clause``][BSD-2-Clause]

### XML ###

* [Expat][89] - 面向流的XML解析器。[MIT][MIT]
* [libxml2][62] - 符合标准的可移植XML解析器。[MIT][MIT]
* [xml][569] - 简单、低内存使用的XML解析器/标记器。[``MIT``][MIT]

### YAML ###

* [libYAML][341] - YAML 1.1解析器和发射器。[``MIT``][MIT]

## Signal Processing ##

* [libsigrok][601] -  支持各种设备类型 (如逻辑分析仪、示波器、万用表等) 的信号分析软件套件。[``GPL``][GPL]

## Testing ##

* [CHEAT][84] - 简单的单元测试框架。[``BSD-2-Clause``][BSD-2-Clause]
* [Check][59] - 单元测试框架。[``LGPL-2.1-only``][LGPL-2.1-only]
* [ciut][5] - 一个现代的最小麻烦单元测试框架。[``MIT``][MIT]
* [clar][470] - 清晰和简单的单元测试框架。[``MIT``][MIT]
* [CMock][297] - 模拟/存根生成器。[``MIT``][MIT]
* [cmocka][141] - 支持模拟对象的单元测试框架。[``Apache-2.0``][Apache-2.0]
* [Criterion][246] - KISS，非侵入式测试框架[``MIT``][MIT]
* [ctest][503] - 另一个单元测试框架。[``Apache-2.0``][Apache-2.0]
* [CUnit][94] - 另一个单元测试框架。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [greatest][58] - 单元测试库在一个文件中，没有内存分配。[``ISC``][ISC]
* [minctest][394] - 单元测试微库。[``BSD-3-Clause``][BSD-3-Clause]
* [munit][392] - 小型单元测试框架。[``MIT``][MIT]
* [Nala][560] - C项目的测试框架。[``MIT``][MIT]
* [Rexo][563] - C89/C框架，具有自动注册测试和完善的API。[``Unlicense``][Unlicense]
* [Tau][609] -  C/C的微型单元测试框架 (〜1k代码行)。包括一组丰富的断言宏，支持自动测试注册，并可以输出多种格式，如TAP格式或JUnit XML。支持Linux、macOS、FreeBSD和Windows。[``MIT``][MIT]
* [theft][302] - 基于属性的测试 (类似于[Quickcheck][301]). [``MIT``][MIT]
* [Unity][296] - 简单的单元测试框架。[``MIT``][MIT]
* [utest][386] - 单头单元测试库。[``Unlicense``][Unlicense]

## Text Editor Extensions ##
虽然几乎任何体面的程序员的文本编辑器都支持C，但有一些扩展使它更愉快。这些是由编辑标记的。

* [CCompletion][92] - 记事本自动完成插件。适用于Ctags识别的所有标识符。这是一个下载链接。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [CEDET][250] - Emacs开发环境工具的集合; 旨在为Emacs提供类似IDE的功能。内置。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Flycheck][149] - Emacs的现代语法检查。对于C，它可以使用GCC或Clang作为后端。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Neomake][441] - 异步: Neovim/Vim的制作和linting框架。[``MIT``][MIT]
* [Syntastic][186] - Vim的语法检查和衬里。[``WTFPL``][WTFPL]
* [YASnippet][150] - Emacs代码模板系统，带有C模板的常用代码片段。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [YouCompleteMe][151] - Vim的代码完成引擎。[``GPL-3.0-only``][GPL-3.0-only]

## Tools ##
有用的程序来帮助你编写和调试C代码*不*编辑器、库或编译器。

* [Artistic Style][314] - 支持C的快速小型自动源代码格式化程序。[``LGPL-3.0-only``][LGPL-3.0-only]
* [address-sanitizer][288] - 快速内存错误检测器。[``Apache-2.0``][Apache-2.0]
* [bcc][619] - 一个字节数组生成器，以xxd的精神从C直接导入二进制文件。[``ISC``][ISC]
* [c][276] - 在命令行上一次编译并执行C “脚本”。也有shebang的支持。[``MIT``][MIT]
* [c99sh][113] - 使用hash-bang运行C文件。[``BSD-2-Clause``][BSD-2-Clause]
* [cdecl][347] - 在线服务将C声明翻译成英文，反之亦然。公共领域。
* [cinclude2dot][280] - 图包括使用Graphviz的项目中的依赖关系。[GPL-1.0-or-later][335] or [``GPL-2.0-or-later``][GPL-2.0-or-later] or   [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [ClangCheck][502] - 静态分析工具，旨在与Clang一起使用。[``NCSA``][NCSA]
* [conan.io][304] - C的包管理器的东西。[''MIT''][麻省理工学院]。
* [Cppcheck][501] - 静态分析工具。尽管有这个名字，但与C配合得很好。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Glade][328] - RAD工具，可以快速开发GTK gui。[``GPL-2.0-only``][GPL-2.0-only]
* [GMSL][331] - GNU制作标准库; GNU制作的附加功能集合。[``BSD-3-Clause``][BSD-3-Clause]
* [GNU Global][330] - 源代码标记工具。[``GPL-3.0-only``][GPL-3.0-only]
* [GPP][269] - 通用预处理器。比C预处理器更通用，但比m4更灵活。[``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [Highlight][333] - 将源代码转换为带有突出显示的格式化文本。[``GPL-3.0-only``][GPL-3.0-only]
* [include-what-you-use][289] - 帮助找到不必要的内含物，并提出修复它们的建议。基于LLVM/Clang (并且仅适用于它)。[``NCSA``][NCSA]
* [incbin][592] - 轻松地在C/C应用程序中包含二进制文件[``Unlicense``][Unlicense]
* [indent][315] - 自动格式化C源代码，使其更易于阅读。也从一种样式的源转换为另一种样式。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [SMACK][500] - 模块化软件验证工具链和独立的软件验证程序。目前仅适用于使用Clang编译的程序。[``MIT``][MIT]
* [unifdef][290] - 删除 # ifdef和 # if指令及其分隔文本，而不触及文件的任何其他部分。[``BSD-3-Clause``][BSD-3-Clause] or   [``BSD-2-Clause``][BSD-2-Clause]

## Utilities ##
任何不适合其他地方的东西的 “全能” 类别。

* [ApeTagLibs][345] - 用于处理APEv2标记的库。[``MIT``][MIT]
* [argparse][413] - 命令行参数解析库，灵感来自Python的argparse模块。[``MIT``][MIT]
* [attr][425] - 用于操作文件系统扩展属性的命令。[``GPL-2.0-or-later``][GPL-2.0-or-later]
* [bfd][157] - 用于操作二进制对象文件的库。GNU binutils的一部分。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Caffeine][496] - 用于为Linux和FreeBSD系统构建守护程序和服务的库。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [CException][298] - 例外的实现。[``MIT``][MIT]
* [CommonMark][223] - CommonMark规范的实现。
* [cosmopolitan][597] - 快速可移植的静态原生textmode容器 (一次性构建Linux \ Mac \ Windows的C程序) [各种许可证，全部开源][224]。
* [cpu\_features][319] - 在运行时获取CPU功能。[''阿帕奇-2.0''][阿帕奇-2.0]。
* [CRIU][440] - 用户空间中的检查点/恢复; 一个软件工具 (带有C API)，用于将正在运行的应用程序 “冻结” 到磁盘，然后恢复它。[``GPL-2.0-only``][GPL-2.0-only] or [``LGPL-2.1-only``][LGPL-2.1-only]
* [D-Bus][430] - 简单的方式为应用程序互相交谈。[``AFL-2.1``][AFL-2.1] or [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [Discount][438] - Markdown解析器的简单实现。[``BSD-3-Clause``][BSD-3-Clause]
* [dlx][388] - 实施[Knuth's Algorithm X][389], with example   solvers. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [docopt.c][270] - 命令行选项解析器的实现。[``MIT``][MIT]
* [dyncall][281] - 另一个外部函数接口库。[``MIT``][MIT]
* [GNU FreeIPMI][158] - 带内和带外IPMI实现。[``GPL-3.0-only``][GPL-3.0-only]
* [GNU gperf][351] - 完美的哈希函数生成器，给定一个字符串列表。输出C代码。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [GNU Libffcall][162] - 用于构建外函数接口的库的集合[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Hoedown][405] - 完全符合标准，支持扩展，UTF-8感知，快速降价解析器。[``MIT``][MIT]
* [Kitsune][355] - 用于动态软件更新的高效通用框架。[``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [libCello][96] - 向C引入高级编程的库。[``BSD-3-Clause``][BSD-3-Clause]
* [libcmark][436] - 用于解析Markdown的CommonMark方言的库。[``BSD-2-Clause``][BSD-2-Clause]
* [libcoap][136] - 实施[Constrained Application Protocol][117].   [``GPL-2.0-or-later``][GPL-2.0-or-later] or [``BSD-2-Clause``][BSD-2-Clause]
* [libcox][373] - 允许跨不同操作系统的跨平台系统调用和标准实用程序的库。[``BSD-2-Clause``][BSD-2-Clause]
* [libffi][128] - 可移植的外函数接口库。[``MIT``][MIT]
* [libgeohash][499] - Geohash算法的纯C实现。[``BSD-3-Clause``][BSD-3-Clause]
* [libgit2][61] - Git核心方法的可移植实现，作为可重入可链接库提供。[自定义许可证][41]。
* [libgss][161] - 通用安全服务。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libimobiledevice][354] - 跨平台协议库，用于与iThings通信。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libnfc][332] - 独立于平台的近场通信库。[``LGPL-3.0-only``][LGPL-3.0-only]
* [libpostal][434] - 用于解析和规范化世界各地街道地址的库。由统计NLP和开放地理数据提供支持。[``MIT``][MIT]
* [libtrading][455] - 实现与交易所，暗池和其他交易场所进行通信的网络协议。支持FIX，FIX/FAST和许多专有协议。[``BSD-2-Clause``][BSD-2-Clause]
* [libusb][306] - 提供对USB设备的通用访问。[``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libuv][56] - 跨平台异步I/O。[``MIT``][MIT]
* [libvldmail][3] - 您友好的电子邮件验证库。没有外部依赖关系 (甚至不是regexp)。[``WTFPL``][WTFPL]
* [linenoise][504] - 小，独立的替代readline和libedit。[``BSD-2-Clause``][BSD-2-Clause]
* [libXDGdirs][589] - XDG基目录规范的实现[``MIT``][MIT]
* [MegaMimes][31] - 库，用于获取[MIME][30] types of a file.   [``MIT``][MIT]
* [ncurses][178] - 彩色终端UI库。[``MIT``][MIT]
* [netbsd-curses][494] - ncurses的简化和小版本，具有相同的界面。[``BSD-3-Clause``][BSD-3-Clause]
* [nope.c][209] - 适用于可扩展服务器端和网络应用程序的超轻软件平台 (请考虑适用于C程序员的node.js)。[``GPL-2.0-only``][GPL-2.0-only]
* [obj.h][580] - 单标头在纯C中支持OOP。[``MIT``][MIT]
* [parg][274] - 具有更好默认值的 “getopt” 的单文件重新实现。[``CC0-1.0``][CC0-1.0]
* [pbc][236] - 协议缓冲区库。[``MIT``][MIT]
* [progressbar][453] - 易于使用的库，用于显示文本进度条。[``BSD-3-Clause``][BSD-3-Clause]
* [rabbitmq-c][228] - 的客户端库[RabbitMQ][229]. [``MIT``][MIT]
* [Ragel][54] - 编译为C的状态机的DSL。[``GPL-2.0-only``][GPL-2.0-only]
* [rmw][622] - 用于命令行的safe-remove实用程序，可以在x天后从废物目录中清除项目。[``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Rogueutil][565] - 用于创建基于文本的用户界面 (TUI) 的跨平台库[``Apache-2.0``][Apache-2.0]
* [sort][190] - 排序例程的集合，该例程在编译时使用用户定义的类型进行类型专门化。[``MIT``][MIT]
* [termbox][396] - 用于编写基于文本的接口的库。[``MIT``][MIT]
* [tinyexpr][395] - 微型递归下降解析器，编译器和评估引擎，用于简单的数学表达式。[``BSD-3-Clause``][BSD-3-Clause]
* [tm][543] - ⏱C的计时器和时间线使用情况。[``MIT``][MIT]
* [Tulip Indicators][449] - 用于对财务数据进行技术分析的函数库。[``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [whereami][167] - 一个文件库，用于在文件系统上查找当前可执行文件。[``WTFPL``][WTFPL]
* [XLSX I/O][344] - 用于阅读和写作的跨平台库。xlsx文件。[``MIT``][MIT]
* [xlsx_drone][596] - 快速的Microsoft Excel*。xlsx读取器。[''MIT''][MIT]
* [zlog][437] - 可靠，纯C日志库。[``LGPL-2.1-only``][LGPL-2.1-only]
* [zproto][421] - ZeroMQ的协议框架。[``MIT``][MIT]
* [Metalang99][603] - 全面的预处理器元编程。[``MIT``][MIT]
* [Datatype99][604] - C99的代数数据类型。[``MIT``][MIT]

## Web Frameworks ##
全面和集成的解决方案，用于在C中构建下一个出色的web应用程序。

* [Concord][617] - 一个用C ++ 编写的Discord API包装库。[``MIT``][MIT]
* [facil.io][118] - web应用程序的微型框架。包括快速的HTTP和Websocket服务器，还支持自定义协议。[``MIT``][MIT]
* [kcgi][562] - 用于C ['isc''][ISC] 的CGI和FastCGI库。
* [KLone][423] - 功能齐全的多平台web应用程序开发框架，特别针对嵌入式系统和设备。[``BSD-3-Clause``][BSD-3-Clause]
* [Kore][415] - 易于使用的web应用程序框架，用于在C中编写可扩展的web api。[``ISC``][ISC]

## Windows Environments ##
旨在使Windows在支持C方面投入21世纪的技术。

* [Cygwin][253] - 旨在广泛模拟Windows下的POSIX兼容环境。[各种许可证，全部开源][254]。
* [MinGW-w64][287] - 在Windows上支持64位C开发的简约环境。[各种许可证，全部开源][252]。
* [MSYS2][428] - 最小系统2; 旨在为Windows上的POSIX环境提供支持，并带有基于Arch Linux的pacman的软件包管理器。包有单独的许可证，否则，如MinGW和Cygwin。


[AFL-2.1]: https://spdx.org/licenses/AFL-2.1.html
[AGPL-3.0-only]: https://spdx.org/licenses/AGPL-3.0-only.html
[AGPL-3.0-or-later]: https://spdx.org/licenses/AGPL-3.0-or-later.html
[Apache-2.0]: https://spdx.org/licenses/Apache-2.0.html
[BSD-1-Clause]: https://spdx.org/licenses/BSD-1-Clause.html
[BSD-2-Clause]: https://spdx.org/licenses/BSD-2-Clause.html
[BSD-3-Clause]: https://spdx.org/licenses/BSD-3-Clause.html
[BSD-4-Clause]: https://spdx.org/licenses/BSD-4-Clause.html
[CC0-1.0]: https://spdx.org/licenses/CC0-1.0.html
[curl]: https://spdx.org/licenses/curl.html
[GPL-2.0-only]: https://spdx.org/licenses/GPL-2.0-only.html
[GPL-2.0-or-later]: https://spdx.org/licenses/GPL-2.0-or-later.html
[GPL-3.0-only]: https://spdx.org/licenses/GPL-3.0-only.html
[GPL-3.0-or-later]: https://spdx.org/licenses/GPL-3.0-or-later.html
[ICU]: https://spdx.org/licenses/ICU.html
[ISC]: https://spdx.org/licenses/ISC.html
[LGPL-2.0-or-later]: https://spdx.org/licenses/LGPL-2.0-or-later.html
[LGPL-2.1-only]: https://spdx.org/licenses/LGPL-2.1-only.html
[LGPL-2.1-or-later]: https://spdx.org/licenses/LGPL-2.1-or-later.html
[LGPL-3.0-only]: https://spdx.org/licenses/LGPL-3.0-only.html
[LGPL-3.0-or-later]: https://spdx.org/licenses/LGPL-3.0-or-later.html
[Libpng]: https://spdx.org/licenses/Libpng.html
[麻省理工]: https://spdx.org/licenses/MIT.html
[MPL-2.0]: https://spdx.org/licenses/MPL-2.0.html
[NCSA]: https://spdx.org/licenses/NCSA.html
[OLDAP-2.8]: https://spdx.org/licenses/OLDAP-2.8.html
[PostgreSQL]: https://spdx.org/licenses/PostgreSQL.html
[TCL]: https://spdx.org/licenses/TCL.html
[取消许可]: https://spdx.org/licenses/Unlicense.html
[WTFPL]: https://spdx.org/licenses/WTFPL.html
[X11]: https://spdx.org/licenses/X11.html
[Zlib]: https://spdx.org/licenses/Zlib.html* [AI2](https://github.com/zeromq/libzmq)[AI2](https://github.com/zeromq/libzmq)

[1]: https://github.com/Dead2/zlib-ng
[2]: https://github.com/Cyan4973/FiniteStateEntropy
[3]: https://github.com/dertuxmalwieder/libvldmail
[4]: https://github.com/aosp-mirror/platform_bionic
[5]: https://github.com/yhfudev/cpp-ci-unit-test.git
[6]: https://port70.net/~nsz/c/c89/c89-draft.html
[7]: https://en.wikipedia.org/wiki/The_C_Programming_Language
[8]: https://github.com/json-c/json-c
[9]: https://www.fefe.de/dietlibc/
[10]: https://musl.libc.org/
[11]: https://tools.ietf.org/html/rfc7159
[12]: https://uclibc-ng.org/
[13]: https://opensource.org/osd
[14]: https://www.gtk.org/

[16]: http://webserver2.tecgraf.puc-rio.br/iup/
[17]: https://github.com/saitoha/libsixel
[18]: https://www.enlightenment.org?p=about%252Flibs
[19]: http://www.tcl.tk/

[21]: http://xforms-toolkit.org/
[22]: https://www.sqlite.org/
[23]: https://unqlite.org/
[24]: https://github.com/google/brotli
[25]: https://en.wikipedia.org/wiki/Dynamic_array
[26]: https://github.com/clibs/clib
[27]: https://github.com/clibs/clib/wiki/Packages
[28]: http://www.koanlogic.com/libu/
[29]: https://github.com/antirez/sds
[30]: https://en.wikipedia.org/wiki/MIME
[31]: https://trumpowen.github.io/MegaMimes
[32]: https://github.com/kgabis/parson
[33]: https://www.codeproject.com/Articles/6154/Writing-Efficient-C-and-C-Code-Optimization
[34]: http://re2c.org/index.html
[35]: http://shop.oreilly.com/product/0636920033677.do
[36]: http://shop.oreilly.com/product/0636920028000.do
[37]: https://www.openmp.org/
[38]: https://clang.llvm.org/
[39]: https://github.com/recp/json
[40]: https://gcc.gnu.org/
[41]: https://github.com/libgit2/libgit2/blob/master/COPYING
[42]: http://anjuta.org/
[43]: https://www.geany.org/
[44]: https://www.kdevelop.org/
[45]: https://www.codelite.org/
[46]: https://www.gnu.org/software/gnulib/
[47]: https://www.gnu.org/software/gsl/
[48]: https://liballeg.org
[49]: https://github.com/vasi/pixz
[50]: https://www.libsdl.org/
[51]: https://redis.io/
[52]: http://zeromq.org/
[53]: http://www.digip.org/jansson/
[54]: http://www.colm.net/open-source/ragel/
[55]: https://dl.acm.org/citation.cfm?id=179241
[56]: http://libuv.org
[57]: https://www.gnu.org/software/libc/
[58]: https://github.com/silentbicycle/greatest
[59]: https://libcheck.github.io/check
[60]: https://lloyd.github.io/yajl/
[61]: https://libgit2.org/
[62]: http://xmlsoft.org/
[63]: https://www.ffmpeg.org/
[64]: http://knking.com/books/c2/index.html
[65]: https://curl.haxx.se/libcurl/
[66]: https://github.com/Snaipe/libcsptr
[67]: http://site.icu-project.org/
[68]: https://libspng.org/
[69]: https://lodev.org/lodepng/
[70]: http://www.fftw.org/
[71]: https://sourceforge.net/projects/kissfft/
[72]: https://bitbucket.org/MDukhan/yeppp
[73]: https://graphics.stanford.edu/~seander/bithacks.html
[74]: http://pcc.ludd.ltu.se/
[75]: http://pcc.ludd.ltu.se/licenses/
[76]: http://attractivechaos.github.io/klib/#About
[77]: https://github.com/netmail-open/wjelement/
[78]: http://apr.apache.org/
[79]: https://gmplib.org/
[80]: https://github.com/cesanta/slre
[81]: http://tiny-rex.sourceforge.net/
[82]: https://github.com/laurikari/tre/
[83]: http://www.pcre.org/
[84]: https://github.com/Tuplanolla/cheat
[85]: http://www.valgrind.org/
[86]: https://www.gnu.org/software/binutils/
[87]: https://www.gnu.org/software/gdb/
[88]: https://fragglet.github.io/c-algorithms
[89]: http://expat.sourceforge.net/
[90]: https://www.sfml-dev.org/download/csfml/
[91]: https://www.sfml-dev.org/index.php
[92]: http://freeweb.siol.net/rmihor/NppCCompletionPlugin.zip
[93]: https://github.com/keybuk/libnih
[94]: http://cunit.sourceforge.net/
[95]: https://rr-project.org/
[96]: http://libcello.org/
[97]: http://nethack4.org/projects/aimake/
[98]: https://www.glfw.org/
[99]: http://freeglut.sourceforge.net
[100]: https://uriparser.github.io
[101]: https://github.com/orangeduck/Corange
[102]: http://shop.oreilly.com/product/0636920015482.do
[103]: http://ccodearchive.net/
[104]: http://ccodearchive.net/list.html
[105]: https://symas.com/lightning-memory-mapped-database/
[106]: https://nanomsg.github.io/nng/
[107]: https://ioquake3.org
[108]: https://github.com/RandyGaul/tinyheaders
[109]: https://github.com/compuphase/minIni
[110]: https://www.openssl.org/
[111]: https://www.openssl.org/source/license.html
[112]: http://www.gnutls.org/
[113]: https://github.com/RhysU/c99sh
[114]: https://github.com/nothings/stb
[115]: https://tinycthread.github.io/
[116]: http://mike.steinert.ca/bstring/
[117]: http://coap.technology/
[118]: http://facil.io/
[119]: https://www.enlightenment.org
[120]: https://zserge.com/jsmn.html
[121]: https://www.postgresql.org/
[122]: https://madmurphy.github.io/libconfini/html/index.html
[123]: https://gstreamer.freedesktop.org/
[124]: http://libevent.org/
[125]: https://www.hboehm.info/gc/
[126]: https://github.com/rampantpixels/rpmalloc
[127]: https://h2o.examp1e.net/
[128]: https://github.com/atgreen/libffi
[129]: https://github.com/protobuf-c/protobuf-c
[130]: https://github.com/jmckaskill/c-capnproto
[131]: https://en.wikipedia.org/wiki/External_Data_Representation
[132]: https://bitbucket.org/martijnj/msgpackalt
[133]: http://www.netlib.org/lapack/lapacke.html
[134]: http://www.netlib.org/lapack/
[135]: https://github.com/martinh/libconfuse
[136]: https://github.com/obgm/libcoap
[137]: http://math-atlas.sourceforge.net/
[138]: http://lionet.info/asn1c/compiler.html
[139]: https://github.com/nanomsg/nanomsg
[140]: http://avro.apache.org/docs/current/api/c/index.html#_introduction_to_avro_c
[141]: https://cmocka.org/
[142]: https://gnupg.org/related_software/libgcrypt
[143]: https://github.com/libressl-portable/
[144]: http://software.schmorp.de/pkg/libev.html
[145]: https://google.github.io/flatbuffers/
[146]: https://en.wikipedia.org/wiki/POSIX_Threads
[147]: https://www.opengl.org/
[148]: http://www.sgi.com/tech/opengl/?/license.html
[149]: https://github.com/flycheck/flycheck
[150]: http://joaotavora.github.io/yasnippet/
[151]: https://github.com/ycm-core/YouCompleteMe
[152]: https://sites.google.com/site/lccretargetablecompiler/
[153]: https://github.com/drh/lcc/blob/master/CPYRIGHT
[154]: https://github.com/swenson/vector.h
[155]: https://www.gnu.org/software/adns/
[156]: http://adtinfo.org/libavl.html/index.html
[157]: http://sourceware.org/binutils/docs/bfd/
[158]: https://gnu.org/software/freeipmi/index.html
[159]: https://gnu.org/software/glpk/
[160]: https://gnu.org/software/gsasl/
[161]: https://gnu.org/software/gss/
[162]: https://gnu.org/software/libffcall/
[163]: https://gnu.org/software/libiconv/
[164]: https://gnu.org/software/libidn/
[165]: https://gnu.org/software/libmicrohttpd/
[166]: https://www.hughes.com.au/products/libhttpd/
[167]: https://github.com/gpakosz/whereami
[168]: http://www.webdav.org/neon/
[169]: http://mihl.sourceforge.net/
[170]: https://www.coralbits.com/libonion/
[171]: https://cesanta.com
[172]: https://risoflora.github.io/libsagui/
[173]: https://gnu.org/software/libunistring/
[174]: https://gnu.org/software/libxmi/
[175]: http://www.multiprecision.org/mpc/
[176]: http://mpfr.loria.fr/index.html
[177]: https://gnu.org/software/mpria/
[178]: https://gnu.org/software/ncurses/
[179]: https://gnu.org/software/osip/
[180]: https://gnu.org/software/pth/
[181]: https://savedparadigms.files.wordpress.com/2014/09/harbison-s-p-steele-g-l-c-a-reference-manual-5th-ed.pdf
[182]: http://shop.oreilly.com/product/9780596004361.do
[183]: http://shop.oreilly.com/product/0636920026136.do
[184]: https://www.pearson.com/us/higher-education/program/Prata-C-Primer-Plus-6th-Edition/PGM4399.html
[185]: http://www.planetpdf.com/codecuts/pdfs/ooc.pdf
[186]: https://github.com/vim-syntastic/syntastic
[187]: https://github.com/dvidelabs/flatcc
[188]: http://apophenia.info
[189]: https://github.com/b-k/apophenia/blob/master/install/COPYING
[190]: https://github.com/swenson/sort
[191]: http://steve-yegge.blogspot.co.nz/2008/10/universal-design-pattern.html
[192]: http://libjpeg.sourceforge.net/
[193]: https://libjpeg-turbo.virtualgl.org/
[194]: https://www.libjpeg-turbo.org/About/License
[195]: http://libccv.org/
[196]: https://github.com/google/gumbo-parser
[197]: https://llhttp.org
[198]: https://download.libsodium.org/doc
[199]: https://lwan.ws
[200]: https://github.com/mozilla/mozjpeg
[201]: https://github.com/redis/hiredis
[202]: https://jvns.ca/blog/2014/12/14/fun-with-threads/
[203]: https://github.com/silentbicycle/socket99
[204]: http://danluu.com/malloc-tutorial/
[205]: https://web.archive.org/web/20170620131430/https://www.tedunangst.com/flak/post/memcpy-vs-memmove
[206]: https://blogs.oracle.com/linux/8-gdb-tricks-you-should-know-v2
[207]: https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG
[208]: http://nethack4.org/blog/building-c.html
[209]: https://github.com/riolet/WAFer
[210]: https://docs.google.com/presentation/d/1h49gY3TSiayLMXYmRMaAEMl05FaJ-Z6jDOWOz3EsqqQ/edit?pli=1#slide=id.gaf50702c_0153
[212]: http://www.crasseux.com/books/ctut.pdf
[213]: https://pdos.csail.mit.edu/6.828/2017/readings/pointers.pdf
[214]: https://github.com/adamierymenko/huffandpuff
[215]: https://sourceforge.net/projects/vtd-xml/
[216]: https://michaelrsweet.github.io?Z3
[217]: http://svn.msweet.org/mxml/trunk/COPYING
[218]: http://ezxml.sourceforge.net/
[219]: https://github.com/blunderer/libroxml
[220]: https://github.com/DanielGibson/Snippets/
[221]: https://github.com/id-Software/Quake-2
[222]: http://www.etpan.org
[223]: https://github.com/commonmark/commonmark-spec
[224]: https://github.com/commonmark/commonmark-spec/blob/master/LICENSE
[225]: https://github.com/id-Software/Quake
[226]: http://czmq.zeromq.org
[227]: https://marek.vavrusa.com/memory/
[228]: https://github.com/alanxz/rabbitmq-c
[229]: http://www.rabbitmq.com/
[230]: http://zlib.net
[231]: https://github.com/libretro/RetroArch
[232]: https://www.libretro.com/
[233]: http://mongoc.org/
[234]: https://www.mongodb.org/
[235]: https://github.com/mongodb/libbson
[236]: https://github.com/cloudwu/pbc
[237]: https://github.com/sinemetu1/twitc
[238]: https://github.com/orangeduck/mpc
[239]: https://github.com/vstakhov/libucl
[240]: http://snaipe.me/c/c-smart-pointers/
[241]: https://github.com/gpakosz/PackedArray
[242]: http://concurrencykit.org
[243]: http://repo.hu/projects/cchan/
[244]: http://sophia.systems
[245]: http://www.greenend.org.uk/rjk/tech/inline.html
[246]: https://criterion.readthedocs.io/en/master
[247]: https://port70.net/~nsz/c/c11/n1570.html
[248]: https://en.wikibooks.org/wiki/C_Programming
[249]: http://www.codeblocks.org/
[250]: http://cedet.sourceforge.net/
[251]: http://mingw.org/
[252]: http://mingw.org/license
[253]: https://cygwin.com/
[254]: https://cygwin.com/licensing.html
[255]: http://flintlib.org/
[256]: http://pari.math.u-bordeaux.fr/
[257]: http://blog.noctua-software.com/c-tricks.html
[258]: https://port70.net/~nsz/c/c99/n1256.html
[259]: https://spdx.org/licenses/EPL-1.0.html
[260]: https://netbeans.org/
[261]: https://github.com/JonnyWhatshisface/libwebsock
[262]: http://c-faq.com/
[263]: https://computing.llnl.gov/tutorials/pthreads/
[264]: https://computing.llnl.gov/tutorials/openMP/
[265]: https://computing.llnl.gov/tutorials/mpi/
[266]: https://wiki.sei.cmu.edu/confluence/display/c/SEI+CERT+C+Coding+Standard
[267]: http://blog.pkh.me/p/20-templating-in-c.html
[268]: http://lipforge.ens-lyon.fr/www/crlibm/index.html
[269]: https://logological.org/gpp
[270]: https://github.com/docopt/docopt.c
[271]: https://xmake.io/
[273]: http://troydhanson.github.io/uthash/
[274]: https://github.com/jibsen/parg
[275]: http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html
[276]: https://github.com/ryanmjacobs/c
[277]: http://wolkykim.github.io/qlibc
[278]: https://github.com/wolkykim/qlibc/blob/master/LICENSE
[279]: https://gist.github.com/eatonphil/21b3d6569f24ad164365
[280]: https://www.flourish.org/cinclude2dot/
[281]: http://www.dyncall.org/
[282]: http://www.mcs.anl.gov/petsc/
[283]: http://slepc.upv.es/
[284]: https://github.com/open-mpi/ompi
[285]: http://www.mpich.org/
[286]: http://git.mpich.org/mpich.git/blob_plain/6aab201f58d71fc97f2c044d250389ba86ac1e3c:/COPYRIGHT
[287]: http://mingw-w64.yaxm.org/doku.php/start
[288]: https://github.com/google/sanitizers
[289]: https://github.com/include-what-you-use/include-what-you-use
[290]: http://dotat.at/prog/unifdef/
[291]: https://tls.mbed.org/
[292]: http://www.fefe.de/djb/
[293]: http://jemalloc.net
[295]: https://github.com/gperftools/gperftools
[296]: http://www.throwtheswitch.org/unity
[297]: http://www.throwtheswitch.org/cmock
[298]: http://www.throwtheswitch.org/cexception
[299]: https://www.libtom.net
[300]: https://pngquant.org/lib/
[301]: https://wiki.haskell.org/Introduction_to_QuickCheck2
[302]: https://github.com/silentbicycle/theft
[303]: http://chipmunk-physics.net
[304]: https://conan.io/
[305]: https://faragon.github.io/libsrt.html
[306]: https://libusb.info/
[307]: https://www.gnu.org/software/complexity/
[308]: http://www.eso.org/sci/software/cpl/
[309]: https://www.cprover.org/cbmc/
[310]: https://github.com/0intro/libelf
[311]: https://github.com/matze/oclkit
[312]: http://tuxfan.github.io/ocl-mla/
[313]: http://c2html.sourceforge.net/whatisc2html.html
[314]: http://astyle.sourceforge.net/
[315]: https://www.gnu.org/software/indent/
[316]: http://www.feynarts.de/cuba/
[317]: http://www.gedanken.org.uk/software/cxref/
[318]: http://www.doxygen.nl/
[319]: https://github.com/google/cpu_features
[320]: https://www.gnu.org/software/ddd/ddd.html
[321]: http://docutils.sourceforge.net/
[322]: https://hplgit.github.io/doconce/doc/web/index.html
[323]: http://fabutil.org/
[324]: https://www.gnu.org/software/make/
[325]: https://github.com/libfann/fann
[326]: https://github.com/centaurean/spookyhash
[327]: https://github.com/attractivechaos/kann
[328]: https://glade.gnome.org/
[329]: https://cmake.org/
[330]: https://www.gnu.org/software/global/
[331]: https://gmsl.sourceforge.net/
[332]: https://github.com/nfc-tools/libnfc
[333]: http://www.andre-simon.de/index.php
[334]: https://en.wikipedia.org/wiki/Levenshtein_distance
[335]: https://spdx.org/licenses/GPL-1.0.html
[336]: https://github.com/ndevilla/iniparser
[337]: https://github.com/jtsiomb/kdtree
[338]: http://www.oberhumer.com/opensource/lzo/
[339]: http://www.nlnetlabs.nl/projects/ldns/index.html
[340]: https://wiki.gnome.org/Projects/LibRsvg
[341]: https://www.pyyaml.org/wiki/LibYAML
[342]: https://www.xiph.org/ao/
[343]: https://www.chiark.greenend.org.uk/~sgtatham/mp/
[344]: https://brechtsanders.github.io/xlsxio/
[345]: https://github.com/jeremyevans/ape_tag_libs/tree/master/c
[346]: http://www.mission-base.com/peter/source/
[347]: https://cdecl.org/
[348]: https://mpv.io
[349]: https://www.recurse.com/blog/5-learning-c-with-gdb
[350]: https://github.com/P-p-H-d/mlib
[351]: https://www.gnu.org/software/gperf/
[352]: http://libmill.org/
[353]: https://talloc.samba.org/talloc/doc/html/index.html
[354]: https://github.com/libimobiledevice/libimobiledevice
[355]: http://kitsune-dsu.com/
[356]: https://github.com/abiggerhammer/hammer
[357]: http://250bpm.com/blog:56
[358]: https://web.archive.org/web/20170429175803/http://www.samnip.ps/thought/macro-storage-for-inverse-comma
[359]: https://github.com/awslabs/s2n
[360]: https://github.com/wooorm/levenshtein.c
[361]: https://pp.ipd.kit.edu/firm/
[362]: http://www.etalabs.net/compare_libcs.html
[363]: http://ed-von-schleck.github.io/shoco
[364]: https://github.com/antirez/smaz
[365]: https://github.com/prideout/heman
[366]: https://github.com/cacalabs/libcaca
[367]: http://tartarus.org/martin/PorterStemmer/
[368]: https://mesonbuild.com/
[369]: https://icculus.org/twilight/darkplaces/
[370]: http://orx-project.org
[371]: https://github.com/AlexanderAgd/CLIST
[372]: http://libsound.io
[373]: http://libcox.symisc.net/
[374]: https://proprogramming.org/some-unknown-features-or-tricks-in-c-language/
[375]: https://perf.wiki.kernel.org/index.php/Main_Page
[376]: https://xiph.org/ao/
[377]: https://github.com/camgunz/cmp
[378]: https://github.com/ludocode/mpack
[379]: https://msgpack.org/
[380]: http://www.oracle.com/us/products/database/berkeley-db
[381]: https://spdx.org/licenses/AGPL-1.0.html
[382]: http://www.libpng.org/
[383]: https://github.com/wooorm/stmr.c
[384]: http://cairographics.org/
[385]: https://spdx.org/licenses/MPL-1.1.html
[386]: https://github.com/evolutional/utest
[387]: https://github.com/rgamble/libcsv
[388]: https://github.com/blynn/dlx
[389]: https://en.wikipedia.org/wiki/Knuth's_Algorithm_X
[390]: https://github.com/sharow/libconcurrent
[391]: https://hintjens.gitbooks.io/scalable-c/content/index.html
[392]: https://nemequ.github.io/munit
[393]: https://github.com/quixdb/squash
[394]: https://github.com/codeplea/minctest
[395]: https://github.com/codeplea/tinyexpr
[396]: https://github.com/nsf/termbox
[397]: http://opic.rocks/
[398]: https://github.com/waruqi/tbox
[399]: http://sourceforge.net/projects/libquickmail/
[400]: https://github.com/liteserver/binn
[401]: https://sourceforge.net/projects/giflib/
[402]: https://github.com/libgd/libgd
[403]: https://embed.cs.utah.edu/creduce/
[404]: http://www.gnu.org/software/cflow/
[405]: https://github.com/hoedown/hoedown
[406]: https://github.com/srdja/Collections-C
[407]: https://github.com/Juniper/libxo
[408]: https://github.com/Immediate-Mode-UI/Nuklear
[409]: https://github.com/blunderer/libroxml
[410]: https://www.spinellis.gr/cscout/
[411]: https://liblfds.org/
[412]: https://codeplea.com/genann
[413]: https://github.com/cofyc/argparse
[414]: https://github.com/anholt/libepoxy
[415]: https://kore.io/
[416]: http://zeromq.org/
[417]: https://wiki.gnome.org/action/show/Projects/LibRsvg?action=show&redirect=LibRsvg
[418]: http://shop.oreilly.com/product/0636920033844.do
[419]: https://github.com/zeromq/zyre
[420]: https://github.com/zeromq/zproject
[421]: https://github.com/zeromq/zproto
[422]: https://github.com/it4e/CHL
[423]: http://www.koanlogic.com/klone/
[425]: http://savannah.nongnu.org/projects/attr/
[426]: https://sourceforge.net/projects/tinyfiledialogs/
[427]: http://www.bzip.org/
[428]: http://msys2.github.io/
[429]: http://www.libsigil.com/
[430]: https://www.freedesktop.org/wiki/Software/dbus/
[431]: https://github.com/sheredom/json.h
[432]: http://lzip.nongnu.org/clzip.html
[433]: http://lzip.nongnu.org/lzip.html
[434]: https://github.com/openvenues/libpostal
[435]: https://premake.github.io/
[436]: https://github.com/jgm/cmark
[437]: http://hardysimpson.github.io/zlog/
[438]: http://www.pell.portland.or.us/~orc/Code/discount/
[439]: https://github.com/clMathLibraries/clBLAS
[440]: https://criu.org/Main_Page
[441]: https://github.com/neomake/neomake
[442]: http://libdill.org/
[443]: https://nullprogram.com/blog/2015/02/17
[444]: https://github.com/ands/lightmapper
[445]: http://blosc.org/pages/blosc-in-depth
[446]: https://github.com/Kazade/kazmath
[447]: http://pdclib.e43.eu/
[448]: https://github.com/vurtun/mmx
[449]: https://tulipindicators.org/
[450]: https://locklessinc.com/benchmarks_allocator.shtml
[451]: https://locklessinc.com/
[452]: https://github.com/distcc/distcc
[453]: https://github.com/doches/progressbar
[454]: http://mpitutorial.com/
[455]: http://libtrading.org/
[456]: https://github.com/prideout/par
[457]: https://github.com/grimfang4/sdl-gpu
[458]: http://www.mega-nerd.com/libsndfile/
[459]: https://github.com/parallella/pal
[460]: https://tatsuhiro-t.github.io/wslay/
[461]: http://www.libtom.net/LibTomMath/
[462]: http://www.libtom.net/TomsFastMath/
[463]: http://www.libtom.net/LibTomPoly/
[464]: https://github.com/LibVNC/libvncserver
[465]: https://github.com/yosefk/checkedthreads
[466]: https://ccache.dev/
[467]: https://github.com/esneider/debug
[468]: https://lldb.llvm.org/
[469]: https://github.com/JuliaLang/utf8proc
[470]: https://github.com/vmg/clar
[471]: https://github.com/powturbo/TurboPFor
[472]: https://github.com/sheredom/utf8.h
[473]: https://github.com/troydhanson/tpl
[474]: http://liburcu.org/
[475]: http://oprofile.sourceforge.net/news/
[476]: http://libcork.readthedocs.io/en/0.14.0/
[477]: https://github.com/jppbsi/LibDEEP
[478]: https://github.com/xant/libhl
[479]: https://github.com/josephg/librope
[480]: https://github.com/miracl/MIRACL
[481]: https://github.com/RoaringBitmap/CRoaring
[482]: http://roaringbitmap.org/
[483]: https://github.com/cvxgrp/scs
[484]: https://github.com/powturbo/TurboRLE
[485]: https://github.com/trezor/trezor-crypto
[486]: https://github.com/NuxiNL/cloudlibc
[487]: https://en.wikipedia.org/wiki/Capability-based_security
[488]: https://github.com/NeonMercury/jfes
[489]: https://github.com/inikep/lizard
[490]: https://nullprogram.com/blog/2017/03/30
[491]: https://github.com/westes/flex
[492]: https://www.gnu.org/software/bison/
[493]: https://openquantumsafe.org/
[494]: https://github.com/sabotage-linux/netbsd-curses
[495]: https://github.com/lemire/clhash
[496]: https://github.com/dmw/caffeine
[497]: https://github.com/fredrik-johansson/arb
[498]: https://github.com/theck01/offbrand_lib
[499]: https://github.com/simplegeo/libgeohash
[500]: https://github.com/smackers/smack
[501]: http://cppcheck.sourceforge.net/
[502]: https://clang.llvm.org/docs/ClangCheck.html
[503]: https://github.com/bvdberg/ctest
[504]: https://github.com/antirez/linenoise
[505]: https://github.com/memononen/nanovg
[506]: https://github.com/centaurean/density
[507]: https://maciejczyzewski.github.io/retter
[508]: http://lz4.github.io/lz4/
[509]: https://github.com/spotify/sparkey
[510]: http://facebook.github.io/zstd/
[511]: https://libvips.github.io/libvips/
[512]: http://whitedb.org/
[513]: http://paulbatchelor.github.io/proj/soundpipe.html
[514]: https://github.com/atomicobject/heatshrink
[515]: http://ebassi.github.io/graphene/
[516]: https://www.raylib.com
[517]: https://github.com/kkos/oniguruma
[518]: https://github.com/k-takata/Onigmo
[519]: https://github.com/lemire/simdcomp
[520]: https://github.com/kuba--/zip
[521]: https://www.scons.org/
[522]: http://cyan4973.github.io/xxHash
[523]: https://github.com/aubio/aubio
[524]: https://github.com/groonga/groonga
[525]: https://100.github.io/Cranium/
[526]: http://www.saphir2.com/sphlib/
[527]: https://github.com/google/highwayhash
[528]: http://nullprogram.com/blog/2017/08/20/
[529]: http://nullprogram.com/blog/2017/09/21/
[530]: https://github.com/leo-yuriev/t1ha
[531]: http://www.gii.upv.es/tlsf/
[532]: https://github.com/minad/tlsf
[533]: https://github.com/gildor2/fast_zlib
[534]: https://github.com/ferreiradaselva/mathc
[535]: https://github.com/ferreiradaselva/uastar
[536]: https://github.com/lieff/minimp3
[537]: https://github.com/adis300/fft-c
[538]: https://github.com/nbulischeck/list.h
[539]: https://github.com/shlomif/fc-solve
[540]: http://www.shlomifish.org/rwlock/
[541]: https://github.com/recp/ds
[542]: https://github.com/recp/cglm
[543]: https://github.com/recp/tm
[544]: https://igraph.org/
[546]: https://scientificc.github.io/cmathl/
[547]: https://github.com/benhoyt/inih
[548]: https://github.com/libarchive/libarchive
[549]: https://github.com/LiamBindle/MQTT-C
[550]: https://github.com/LeoVen/C-Macro-Collections
[551]: https://github.com/mysql/mysql-server
[553]: https://github.com/okuvshynov/b63
[554]: https://github.com/rxi/dyad
[555]: https://github.com/eerimoq/pbtools
[556]: https://wiki.videolan.org/LibVLC
[557]: https://github.com/SanderMertens/flecs
[558]: https://github.com/librg/librg
[559]: https://github.com/superjer/tinyc.games
[560]: https://github.com/eerimoq/nala
[561]: http://jstimpfle.de/projects/rb3ptr/rb3ptr.html
[562]: https://kristaps.bsd.lv/kcgi
[563]: https://github.com/christophercrouzet/rexo
[564]: https://github.com/ithewei/libhv
[565]: https://github.com/sakhmatd/rogueutil
[566]: https://github.com/the-tcpdump-group/libpcap
[567]: http://esbmc.org/
[568]: https://ejdb.org/
[569]: https://github.com/recp/xml
[570]: https://github.com/recp/cmt
[571]: https://github.com/recp/AssetKit
[572]: https://github.com/shiyanhui/libcsp
[573]: https://github.com/PJK/libcbor
[574]: https://git.sr.ht/~mcf/cproc
[575]: https://lvgl.io/
[576]: https://github.com/ianh/owl
[577]: https://github.com/zhaojh329/libuhttpd
[578]: http://zinjai.sourceforge.net/
[579]: https://github.com/silgy/silgy
[580]: https://github.com/small-c/obj.h
[581]: https://github.com/zeromq/libzmq
[582]: https://www.infradead.org/~tgr/libnl/
[583]: https://www.gnu.org/software/automake/manual/html_node/GNU-Build-System.html
[584]: https://github.com/msune/autotools-skeleton
[585]: https://msune.github.io/libcdada/
[586]: https://github.com/ariya/fastlz
[587]: https://github.com/maxim2266/str
[588]: https://github.com/saprykin/plibsys
[589]: https://github.com/Jorengarenar/libXDGdirs
[590]: https://github.com/sammycage/plutovg
[591]: https://duktape.org/
[592]: https://github.com/graphitemaster/incbin
[593]: https://libzip.org
[594]: https://github.com/tek256/astera
[595]: https://github.com/tezc/sc
[596]: https://github.com/damian-m-g/xlsx_drone
[597]: https://github.com/jart/cosmopolitan
[598]: https://github.com/cjwagenius/bfish
[599]: https://github.com/hnes/libaco
[600]: www.littlecms.com
[601]: https://github.com/smoked-herring/sail
[601]: https://sigrok.org/wiki/Libsigrok
[602]: https://github.com/zpl-c/zpl
[603]: https://github.com/Hirrolot/metalang99
[604]: https://github.com/Hirrolot/datatype99
[605]: https://codeforwin.org/2015/09/singly-linked-list-data-structure-in-c.html
[606]: https://www.learn-c.org
[607]: https://github.com/metacall/core
[608]: https://hirrolot.github.io/posts/compiling-algebraic-data-types-in-pure-c99.html
[609]: https://github.com/jasmcaus/tau
[610]: https://github.com/BayesWitnesses/m2cgen
[611]: https://sod.pixlab.io/
[612]: https://github.com/michaelrsweet/pdfio
[613]: https://github.com/rurban/ctl
[614]: https://github.com/nakst/luigi
[615]: https://github.com/helderman/htpataic
[616]: https://github.com/rxi/microui
[617]: https://github.com/Cogmasters/concord
[618]: https://github.com/solenum/exengine
[619]: https://projects.malikania.fr/bcc
[620]: https://github.com/pspdev/pspsdk
[621]: https://github.com/pspdev/pspsdk/blob/master/LICENSE
[622]: https://remove-to-waste.info
[700]: https://viewsourcecode.org/snaptoken/kilo/
[701]: https://wiki.gnome.org/Projects/GLib

