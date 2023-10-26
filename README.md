如果您觉得这个项目对您有帮助，就请点右上角的**Star**按钮为它加星星✨✨ 其他TIOBE Top 20编程语言的中文翻译请看[awesome-code-resources](https://github.com/awesome-code-resources/awesome-code-resources)。
# Awesome C
C好东西的精选清单。此列表包含* 仅* [open source](https://opensource.org/osd)代码 (由链接的开源定义定义) 和卖家对物质资源来说并不邪恶。
这是在创作共用属性共享许可下发布的，版本4 (SPDX代码)。您可以在许可证文件中找到其文本。
** 一个重要的注意事项:** 这个项目做* 不* 索引任何与C相关的; 仅纯C的东西被认为是。
** 贡献者注意事项:** 如果您想提出拉取请求，请阅读[this](CONTRIBUTING.md)首先。
## 内容
* [人工智能](#人工智能)
* [基准测试](#基准测试)
* [构建系统](#构建系统)
* [编译器](#编译器)
* [压缩](#压缩)
* [并发性和并行性](#并发性和并行性)
* [加密](#加密)
* [数据库](#数据库)
* [数据结构](#数据结构)
* [调试](#调试)
* [文档生成](#文档生成)
* [编辑者](#编辑者)
* [嵌入式脚本引擎](#嵌入式脚本引擎)
* [框架](#框架)
* [游戏编程](#游戏编程)
* [图形](#图形)
* [图形用户界面](#图形用户界面)
* [散列](#散列)
* [学习、参考和教程](#学习、参考和教程)
  * [在线参考资源](#在线参考资源)
  * [初学者在线资源](#初学者在线资源)
  * [在线中间资源](#在线中间资源)
  * [在线高级资源](#在线高级资源)
  * [参考书](#参考书)
  * [初学者书籍](#初学者书籍)
  * [中级书籍](#中级书籍)
  * [高级书籍](#高级书籍)
* [词法与句法分析](#词法与句法分析)
* [内存管理](#内存管理)
* [多媒体](#多媒体)
* [网络和互联网](#网络和互联网)
* [数值](#数值)
* [剖析](#剖析)
* [正则表达式](#正则表达式)
* [序列化](#序列化)
* [源代码集合](#源代码集合)
* [标准库](#标准库)
  * [模板库](#模板库)
* [字符串操作](#字符串操作)
* [结构化文件处理](#结构化文件处理)
  * [CSV](#CSV)
  * [JSON](#JSON)
  * [INI](#INI)
  * [其他](#其他)
  * [XML](#XML)
  * [YAML](#YAML)
* [测试](#测试)
* [文本编辑器扩展](#文本编辑器扩展)
* [工具](#工具)
* [公用事业](#公用事业)
* [Web框架](#Web框架)
* [Windows环境](#Windows环境)
## 人工智能
计算机视觉、神经网络、机器学习和其他类似的东西。基本上，如果你的大学称之为AI，它就住在这里。
* [ccv](http://libccv.org/)-基于C/缓存/核心计算机视觉库; 现代计算机愿景。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [Cranium](https://100.github.io/Cranium/)-C99中的便携式，仅标题ANN库。[](https://spdx.org/licenses/MIT.html)
* [FANN](https://github.com/libfann/fann)-快速人工神经网络库的实现神经网络。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [Genann](https://codeplea.com/genann)-C89中的简单ANN，没有额外的依赖关系。[](https://spdx.org/licenses/Zlib.html)
* [KANN](https://github.com/attractivechaos/kann)-两个文件的ANN库。[](https://spdx.org/licenses/MIT.html)
* [LibDEEP](https://github.com/jppbsi/LibDEEP)-深度学习库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [m2cgen](https://github.com/BayesWitnesses/m2cgen)-CLI工具，用于将经过训练的经典ML模型转换为具有零依赖关系的本机C代码。[](https://spdx.org/licenses/MIT.html)
* [sod](https://sod.pixlab.io/)-嵌入式计算机视觉和机器学习库 [][GPL-3]
## 基准测试
比较跨不同芯片/系统架构的各种子系统的性能。
* [b63](https://github.com/okuvshynov/b63)-用于C的轻量级微型基准测试工具。[](https://spdx.org/licenses/Apache-2.0.html)
## 构建系统
在C中自动构建和测试项目的工具。
* [Autotools](https://www.gnu.org/software/automake/manual/html_node/GNU-Build-System.html)-也称为GNU构建系统 (automake，autoconf，libtool...)是最广泛使用的构建系统之一 (configure & & mdp)。[GPL-1.0-or-later](https://spdx.org/licenses/GPL-1.0.html)
* [Autotools project skeleton](https://github.com/msune/autotools-skeleton)-一个简单的autotools骨架 (模板) 快速引导新项目。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [CMake](https://cmake.org/)-设计用于构建，打包和测试的跨平台工具系列软件。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [GNU Make](https://www.gnu.org/software/make/)-控制可执行文件和其他文件生成的工具程序的非源文件。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [Meson](https://mesonbuild.com/)-非常快速，用户友好的构建系统。基于忍者。[](https://spdx.org/licenses/Apache-2.0.html)
* [Premake](https://premake.github.io/)-命令行实用程序，它读取脚本定义的软件项目，并使用它为Visual Studio和GNU制造。其他目标也正在努力。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [SCons](https://www.scons.org/)-使用Python的软件构建工具。[](https://spdx.org/licenses/MIT.html)
* [xmake](https://xmake.io/)-跨平台构建实用程序。[](https://spdx.org/licenses/Apache-2.0.html)
* [zproject](https://github.com/zeromq/zproject)-项目生成器和构建系统支持工具。[](https://spdx.org/licenses/MPL-2.0.html)
## 编译器
编译器，以及编译器和编译相关的工具。
* [ccache](https://ccache.dev/)-编译器缓存旨在加快重新编译。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [Clang](https://clang.llvm.org/)-LLVM的编译器。支持c11。[](https://spdx.org/licenses/NCSA.html)
* [cproc](https://git.sr.ht/~mcf/cproc)-使用QBE作为后端的C11编译器。[](https://spdx.org/licenses/ISC.html)
* [distcc](https://github.com/distcc/distcc)-允许构建在几个之间分发的程序机器。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [Firm](https://pp.ipd.kit.edu/firm/)-提供基于图形的中间库表示、优化和汇编代码生成适用于编译器。带有一个示例C前端在相同的执照。[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [GCC](https://gcc.gnu.org/)-提供C编译器作为其编译器集的一部分。支架C11。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [PCC](http://pcc.ludd.ltu.se/)-古老的编译器.支持c99。[Various licenses](http://pcc.ludd.ltu.se/licenses/),所有开源。
## 压缩
* [blosc](http://blosc.org/pages/blosc-in-depth)-非常快速，多线程，元压缩器库。各种许可证，都是开源的。
* [Brotli](https://github.com/google/brotli)通用无损压缩算法库。有速度与放气相当，但压缩比要高得多。[](https://spdx.org/licenses/MIT.html)。
* [clzip](http://lzip.nongnu.org/clzip.html)-C版本的高质量数据压缩器[Lzip](http://lzip.nongnu.org/lzip.html)(LZMA实施)。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [CRoaring](https://github.com/RoaringBitmap/CRoaring)-C的实现[Roaring bitmaps](http://roaringbitmap.org/)。[](https://spdx.org/licenses/Apache-2.0.html)
* [FiniteStateEntropy](https://github.com/Cyan4973/FiniteStateEntropy)-两个高效的压缩编解码器优化对于现代cpu。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [DENSITY](https://github.com/centaurean/density)-超快速压缩库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [heatshrink](https://github.com/atomicobject/heatshrink)-嵌入式和数据压缩/解压缩库实时系统。[](https://spdx.org/licenses/ISC.html)
* [fast_zlib](https://github.com/gildor2/fast_zlib)-改进的zlib，运行速度快2到10倍。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [fastLZ](https://github.com/ariya/fastlz)-快如闪电的无损压缩库 (LZ77型)。可植入小目标，如手臂皮质-M家族。源代码直接可在您的项目 (一对h/c文件)，没有动态内存分配。[](https://spdx.org/licenses/MIT.html)
* [huffandpuff](https://github.com/adamierymenko/huffandpuff)-最小的霍夫曼编码器和解码器。公共领域。
* [libzip](https://github.com/maxim2266/str)-用于读取，创建和修改zip存档的C库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libbzip2](http://www.bzip.org/)-无专利，高质量的数据压缩库。[](https://spdx.org/licenses/BSD-4-Clause.html)
* [Lizard](https://github.com/inikep/lizard)-以前的LZ5; 快速的高效压缩机减压。实现了与zip和zlib相当的压缩比解压速度达到1000MB/s，速度更快。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [lz4](http://lz4.github.io/lz4/)-一个非常快速的压缩算法库。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [lzo](http://www.oberhumer.com/opensource/lzo/)-快速数据压缩库。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [pixz](https://github.com/vasi/pixz)-并行，索引xz压缩机。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [shoco](http://ed-von-schleck.github.io/shoco)-小文本字符串的压缩器。[](https://spdx.org/licenses/MIT.html)
* [SIMDComp](https://github.com/lemire/simdcomp)-使用压缩整数列表的简单库二元包装。在x86上使用SIMD指令。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [smaz](https://github.com/antirez/smaz)高效的字符串压缩库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [squash](https://github.com/quixdb/squash)-压缩抽象库，完成一些公用事业。[](https://spdx.org/licenses/MIT.html)
* [TurboPFor](https://github.com/powturbo/TurboPFor)-最快的整数压缩。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [TurboRLE](https://github.com/powturbo/TurboRLE)-最有效的运行长度编码。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [zip](https://github.com/kuba--/zip)-真的真的很小的zip存档处理库。[](https://spdx.org/licenses/Unlicense.html)
* [Zlib](http://zlib.net)-大规模的spiffy但微妙的不显眼的压缩库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libarchive](https://github.com/libarchive/libarchive)-libarchive是一个可移植的，高效的C库，可以读取和写入各种格式的流档案。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [zlib-ng](https://github.com/Dead2/zlib-ng)-Zlib替换与优化 '下一代'系统。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [Zstandard](http://facebook.github.io/zstd/)-快速、无损的压缩算法，目标实时zlib级别或更高压缩率的压缩方案。[](https://spdx.org/licenses/BSD-3-Clause.html)
## 并发性和并行性
* [cchan](http://repo.hu/projects/cchan/)-用于线程间通道构造的小型库沟通。公共领域。
* [checkedthreads](https://github.com/yosefk/checkedthreads)-一个简单的库并行性，内置检查竞争条件。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [ck](http://concurrencykit.org)-并发原语，安全的内存回收机制和非阻塞数据结构。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [FCFS RWLock](http://www.shlomifish.org/rwlock/)-先到先得的读者/作家锁定POSIX线程。[](https://spdx.org/licenses/CC0-1.0.html)
* [Libaco](https://github.com/hnes/libaco)-一个快速和轻量级的C非对称协联库。[](https://spdx.org/licenses/Apache-2.0.html)
* [libconcurrent](https://github.com/sharow/libconcurrent)-并发编程库，使用协程，用于C11。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libcsp](https://github.com/shiyanhui/libcsp)受CSP模型影响的高性能并发C库。[](https://spdx.org/licenses/MIT.html)
* [libdill](http://libdill.org/)-使结构化并发编程的库别紧张.[](https://spdx.org/licenses/MIT.html)
* [libhl](https://github.com/xant/libhl)-实现线程安全API来管理一系列数据的库结构。还提供了一些支持功能和结构并发和无锁编程。[](https://spdx.org/licenses/LGPL-3.0-only.html)
* [liburcu](http://liburcu.org/)-数据同步库，随核心数量。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [mill](http://libmill.org/)-Go风格的并发。[](https://spdx.org/licenses/MIT.html)
* [oclkit](https://github.com/matze/oclkit)-双文件OpenCL包装器[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [OCL-MLA](http://tuxfan.github.io/ocl-mla/)-OpenCL中级抽象。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [OpenMP](https://www.openmp.org/)-一套实用程序，旨在允许轻松并行化代码。标准 (许可不适用)。
* [Open MPI](https://github.com/open-mpi/ompi)-消息传递接口实现。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [pal](https://github.com/parallella/pal)-数学，并行处理和数据的优化库动。[](https://spdx.org/licenses/Apache-2.0.html)
* [pth](https://gnu.org/software/pth/)-基于非抢占式优先级的便携式实现多个执行线程的调度。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [pthreads](https://en.wikipedia.org/wiki/POSIX_Threads)-POSIX线程库。标准 (无许可证适用)。
* [TinyCThread](https://tinycthread.github.io/)-可移植，C11线程的小型实现API。[](https://spdx.org/licenses/Zlib.html)
## 加密
主要是众所周知的加密算法的库实现或协议。
* [GNU SASL](https://gnu.org/software/gsasl/)-实现简单的身份验证和安全性层和几种常见的SASL机制。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [GnuTLS](http://www.gnutls.org/)-安全通信库，实现SSL，TLS和DTLS。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [libgcrypt](https://gnupg.org/related_software/libgcrypt)-通用加密库，具有一系列可用的密码。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [OpenSSL](https://www.openssl.org/)-SSL和TLS协议的实现。还包括一个密码学库。[Dual Licensed under the OpenSSL License and the SSLeay License](https://www.openssl.org/source/license.html)。
* [liboqs](https://openquantumsafe.org/)-抗量子密码算法库。[](https://spdx.org/licenses/MIT.html)
* [libsodium](https://download.libsodium.org/doc)-现代和易于使用的加密库。[](https://spdx.org/licenses/MIT.html)
* [libtomcrypt](https://www.libtom.net)-相当全面，模块化和便携式加密工具包。公共领域。
* [mbed TLS](https://tls.mbed.org/)-另一个加密实现。[](https://spdx.org/licenses/Apache-2.0.html)
* [MIRACL](https://github.com/miracl/MIRACL)-多精度整数和有理算术密码库; 用于椭圆曲线加密的SDK。[](https://spdx.org/licenses/AGPL-3.0-or-later.html)
* [retter](https://maciejczyzewski.github.io/retter)-哈希函数，密码，工具，库和与密码学和安全相关的材料。公共领域。
* [s2n](https://github.com/awslabs/s2n)-C99实现的TLS/SSL协议，旨在简单，快速和安全作为优先事项。[](https://spdx.org/licenses/Apache-2.0.html)
* [sphlib](http://www.saphir2.com/sphlib/)-各种哈希函数的实现集，包括几个加密的。[](https://spdx.org/licenses/MIT.html)
* [trezor-crypto](https://github.com/trezor/trezor-crypto)-针对嵌入式的高度优化的加密算法设备。[](https://spdx.org/licenses/MIT.html)
* [bfish](https://github.com/cjwagenius/bfish)-一个包括C99 Blowfish ECB加密库。公共域。
## 数据库
具有C api的数据库和数据存储。
* [BerkeleyDB](http://www.oracle.com/us/products/database/berkeley-db)-用于高性能嵌入式数据库的库键值数据。[](https://spdx.org/licenses/AGPL-3.0-only.html)
* [EJDB2](https://ejdb.org/)-可嵌入的JSON数据库引擎。[](https://spdx.org/licenses/MIT.html)
* [Groonga](https://github.com/groonga/groonga)-带全文搜索的柱状存储。[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [Hiredis](https://github.com/redis/hiredis)-Redis的简约客户端库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libmongoc](http://mongoc.org/)-高性能客户端库[MongoDB](https://www.mongodb.org/)。[](https://spdx.org/licenses/Apache-2.0.html)
* [LMDB](https://symas.com/lightning-memory-mapped-database/)-超快速，超紧凑的键值嵌入式数据存储。[](https://spdx.org/licenses/OLDAP-2.8.html)
* [MySQL](https://github.com/mysql/mysql-server)-世界上最流行的开源数据库。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [PostgreSQL](https://www.postgresql.org/)-强大的对象关系数据库系统。[](https://spdx.org/licenses/PostgreSQL.html)
* [Redis](https://redis.io/)-高级键值存储。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [sophia](http://sophia.systems)-现代的，可嵌入的键值数据库。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [sparkey](https://github.com/spotify/sparkey)-简单的常量键/值存储库。设计用于read-具有不常见的大体积插入物的重负载。[](https://spdx.org/licenses/Apache-2.0.html)
* [SQLite](https://www.sqlite.org/)-自包含、无服务器、零配置、事务性SQL数据库引擎。公共领域。
* [UnQLite](https://unqlite.org/)-自包含、无服务器、零配置、事务性NoSQL引擎。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [WhiteDB](http://whitedb.org/)-轻量级数据库库，完全在main中运行记忆。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
## 数据结构
* [C-Macro-Collections](https://github.com/LeoVen/C-Macro-Collections)-使用宏生成简单和通用的数据结构。[](https://spdx.org/licenses/MIT.html)
* [CLIST](https://github.com/AlexanderAgd/CLIST)-简单和轻量级[dynamic array](https://en.wikipedia.org/wiki/Dynamic_array)实施。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [Collections-C](https://github.com/srdja/Collections-C)-通用数据结构库。[](https://spdx.org/licenses/LGPL-3.0-or-later.html)
* [ds](https://github.com/recp/ds)-常见的数据结构和算法。[](https://spdx.org/licenses/MIT.html)
* [igraph](https://igraph.org/)-一个图形处理库。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [kdtree](https://github.com/jtsiomb/kdtree)-使用KD树的简单库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libavl](http://adtinfo.org/libavl.html/index.html)-包含一系列自平衡二进制库树。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [libcdada](https://msune.github.io/libcdada/)-用于基本数据结构的小型，可移植，无宏的库(列表，设置，映射，队列...) 在C (C后端)。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [liblfds](https://liblfds.org/)便携式无锁数据结构库。公共领域(更确切地说，任何你想要的许可证)。
* [libsrt](https://faragon.github.io/libsrt.html)-软硬实时数据结构。[](https://spdx.org/licenses/BSD-3-Clause.html)。
* [list.h](https://github.com/nbulischeck/list.h)-单链和双链表函数的实现。[](https://spdx.org/licenses/GPL-3.0-only.html)
* [M*LIB](https://github.com/P-p-H-d/mlib)-用于通用但类型安全的C容器的库。实施为仅标题。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [offbrand](https://github.com/theck01/offbrand_lib)-通用的、引用计数的数据结构的集合。[](https://spdx.org/licenses/MIT.html)
* [PackedArray](https://github.com/gpakosz/PackedArray)-随机访问数组的紧密包装的无符号整数任何所需的宽度。有一个SIMD优化的实现。[](https://spdx.org/licenses/WTFPL.html)
* [rb3ptr](http://jstimpfle.de/projects/rb3ptr/rb3ptr.html)-红黑树.公开几乎所有的实现原语，因此可以用于场景，如增强，多个兼容的排序功能，等等。[](https://spdx.org/licenses/MIT.html)
* [uthash](http://troydhanson.github.io/uthash/)-单文件哈希表实现。[](https://spdx.org/licenses/BSD-1-Clause.html)
* [vector.h](https://github.com/swenson/vector.h)-类型化列表的头库。[](https://spdx.org/licenses/MIT.html)
## 调试
因为我们有时都必须这样做。用于调试的各种工具更容易或更好，以及允许更好调试的库或代码工作。
* [C-Reduce](https://embed.cs.utah.edu/creduce/)-工具，需要一个大的C文件与感兴趣的属性并自动生成一个小得多的C文件，该文件具有相同的属性。旨在帮助在复杂的情况下创建最小的bug演示代码。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [CBMC](https://www.cprover.org/cbmc/)-C有界模型检查器; 用于验证数组的工具边界、指针安全和用户指定的断言。[](https://spdx.org/licenses/BSD-4-Clause.html)
* [cflow](http://www.gnu.org/software/cflow/)-分析源文件的集合并打印图形在程序中绘制控制流图。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [Complexity](https://www.gnu.org/software/complexity/)-用于测量源的复杂性的工具代码。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [CScout](https://www.spinellis.gr/cscout/)-C的源代码分析器和重构浏览器程序。[](https://spdx.org/licenses/GPL-3.0-only.html)
* [DDD](https://www.gnu.org/software/ddd/ddd.html)-一系列命令行的图形前端调试器。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [debug](https://github.com/esneider/debug)-一个头库更容易的 “printf调试”。[](https://spdx.org/licenses/MIT.html)
* [ESBMC](http://esbmc.org/)-高效的基于SMT的有界模型检查器; 用于验证的工具单线程和多线程程序、用户断言、溢出和指针/内存安全。[](https://spdx.org/licenses/Apache-2.0.html)
* [GDB](https://www.gnu.org/software/gdb/)-GNU项目调试器。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [lldb](https://lldb.llvm.org/)-LLVM调试器。[](https://spdx.org/licenses/NCSA.html)
* [rr](https://rr-project.org/)-记录非确定性执行以允许的调试器确定性调试。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [Valgrind](http://www.valgrind.org/)-动态分析工具的范围，包括泄漏检查员。[](https://spdx.org/licenses/GPL-2.0-only.html)
## 文档生成
* [Cxref](http://www.gedanken.org.uk/software/cxref/)-在LaTeX，HTML，RTF或生成文档SGML。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [DocOnce](https://hplgit.github.io/doconce/doc/web/index.html)-适度标记的标记语言，可用于生成一系列格式。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [Doxygen](http://www.doxygen.nl/)-用于从以下位置生成文档的事实上的标准工具注释的源。可以生成大范围的格式。[](https://spdx.org/licenses/GPL-2.0-only.html)
## 编辑者
Fancier，IDE类型的编辑器。如果你想要一个程序员的文本编辑器，看其他地方。此外，无论你使用最有可能支持C反正。
* [Anjuta DevStudio](http://anjuta.org/)-GNOME IDE。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [Code::Blocks](http://www.codeblocks.org/)-可扩展，可配置的IDE支持C.[](https://spdx.org/licenses/GPL-3.0-only.html)
* [CodeLite](https://www.codelite.org/)-跨平台IDE。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [Geany](https://www.geany.org/)-小而快速的IDE。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [KDevelop](https://www.kdevelop.org/)-KDE IDE。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [zinjaI](http://zinjai.sourceforge.net/)-简单，轻量级和功能丰富的IDE。[](https://spdx.org/licenses/GPL-3.0-only.html)
## 嵌入式脚本引擎
当C不是正确的解决方案时，或者当您需要更动态的配置引擎时:
* [Duktape](https://duktape.org/)-可嵌入的Javascript引擎，专注于可移植性和紧凑的足迹[](https://spdx.org/licenses/MIT.html)。
* [MetaCall](https://github.com/metacall/core)-跨平台的Polyglot运行时，支持NodeJS，JavaScript，TypeScript，Python，Ruby，C #，Wasm，Java，Cobol等。[](https://spdx.org/licenses/Apache-2.0.html)
## 框架
提供数据结构和您期望的其他内容的大型库“现代” 标准库。
* [APR](http://apr.apache.org/)-Apache便携式运行时; 另一个跨平台实用程序库功能。[](https://spdx.org/licenses/Apache-2.0.html)
* [C Algorithms](https://fragglet.github.io/c-algorithms)-常用算法和数据结构的集合。[](https://spdx.org/licenses/ISC.html)
* [CPL](http://www.eso.org/sci/software/cpl/)-通用管道库; 一组设计为全面、高效和强大的软件工具包。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [EFL](https://www.enlightenment.org)-大量有用的数据结构和功能。各种许可证，都是开源的。
* [GLib](https://wiki.gnome.org/Projects/GLib)-实用功能和结构库，旨在便携，高效，功能强大。[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [klib](http://attractivechaos.github.io/klib/#About)-通用算法的小型和轻量级实现数据结构。[](https://spdx.org/licenses/MIT.html)
* [libcork](http://libcork.readthedocs.io/en/0.14.0/)-实用功能和结构，设计用于资源受限的系统。可以嵌入。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libnih](https://github.com/keybuk/libnih)-轻量级的函数库和结构。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [libU](http://www.koanlogic.com/libu/)基本实用程序的小库，包括内存分配，字符串操作和日志记录。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [PBL](http://www.mission-base.com/peter/source/)-大型实用程序库，具有数据结构，其中其他事情。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [plibsys](https://github.com/saprykin/plibsys)跨平台系统C库。零第三方依赖项，仅使用本机系统调用。[](https://spdx.org/licenses/MIT.html)
* [qlibc](http://wolkykim.github.io/qlibc)-简单而强大的库，旨在取代GLib，同时专注于小巧轻便。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [sc](https://github.com/tezc/sc)-C的通用库和数据结构。[](https://spdx.org/licenses/MIT.html)
* [TBOX](https://github.com/waruqi/tbox)-具有大量多平台库能力。[](https://spdx.org/licenses/Apache-2.0.html)
* [pspsdk](https://github.com/pspdev/pspsdk)-用于PSP自制开发的开源SDK。[Various licences](https://github.com/pspdev/pspsdk/blob/master/LICENSE)。
## 游戏编程
引擎、库和其他专门用于制作游戏的有用的东西。
* [Allegro](https://liballeg.org)-跨平台，视频游戏开发和多媒体库。[](https://spdx.org/licenses/Zlib.html)
* [AssetKit](https://github.com/recp/AssetKit)基于COLLADA/glTF规范的3D资产导入器/导出器/util库[](https://spdx.org/licenses/MIT.html)
* [astera](https://github.com/tek256/astera)-C99跨平台2D游戏库[](https://spdx.org/licenses/MIT.html)
* [cglm](https://github.com/recp/cglm)-优化的OpenGL/图形数学 (glm) 为C。[](https://spdx.org/licenses/MIT.html)
* [Chipmunk2D](http://chipmunk-physics.net)-快速和轻量级的2D游戏物理库。[](https://spdx.org/licenses/MIT.html)
* [cmt](https://github.com/recp/cmt)-C绑定/包装苹果的金属图形框架。[](https://spdx.org/licenses/MIT.html)
* [Corange](https://github.com/orangeduck/Corange)-纯C游戏引擎。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [CSFML](https://www.sfml-dev.org/download/csfml/)-绑定为[SFML](https://www.sfml-dev.org/index.php)。[](https://spdx.org/licenses/Zlib.html)
* [Darkplaces](https://icculus.org/twilight/darkplaces/)-Quake2引擎的修改版本。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [Epoxy](https://github.com/anholt/libepoxy)用于处理OpenGL函数指针管理的库。[](https://spdx.org/licenses/MIT.html)
* [exengine](https://github.com/solenum/exengine)-C99中的3D游戏引擎，带有起始模板。[](https://spdx.org/licenses/MIT.html)
* [Flecs](https://github.com/SanderMertens/flecs)-为C89和C99编写的多线程实体组件系统[](https://spdx.org/licenses/MIT.html)
* [Freecell Solver](https://github.com/shlomif/fc-solve)-一组库和命令行程序自动解决纸牌接龙和一些类似的变种。[](https://spdx.org/licenses/MIT.html)
* [FreeGLUT](http://freeglut.sourceforge.net)-替代OpenGL实用工具工具包。允许使用OpenGL上下文创建和管理窗口。[](https://spdx.org/licenses/X11.html)
* [GLFW](https://www.glfw.org/)-用于使用OpenGL创建窗口的多平台库上下文。[](https://spdx.org/licenses/Zlib.html)
* [ioquake3](https://ioquake3.org)-Quake3引擎，终于释放了。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [kazmath](https://github.com/Kazade/kazmath)-数学库的游戏。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [libao](https://xiph.org/ao/)-跨平台的音频库与各种各样的输出。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [librg](https://github.com/librg/librg)-纯C99游戏网络库，用于构建简单而优雅的跨平台多人客户端-服务器解决方案。[](https://spdx.org/licenses/Apache-2.0.html)
* [MATHC](https://github.com/ferreiradaselva/mathc)-用于2D和3D编程的数学库。[](https://spdx.org/licenses/Zlib.html)
* [Orx](http://orx-project.org)-便携式，轻量级，基于插件，数据驱动，面向2d游戏引擎。[](https://spdx.org/licenses/Zlib.html)
* [Quake](https://github.com/id-Software/Quake)-地震引擎.[](https://spdx.org/licenses/GPL-2.0-only.html)
* [Quake2](https://github.com/id-Software/Quake-2)-Quake2引擎。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [raylib](https://www.raylib.com)-简单和易于使用的库来学习视频游戏编程。[](https://spdx.org/licenses/Zlib.html)
* [RetroArch](https://github.com/libretro/RetroArch)-参考前端[libretro](https://www.libretro.com/)。[](https://spdx.org/licenses/GPL-3.0-only.html)
* [SDL2](https://www.libsdl.org/)-跨平台库，旨在提供对音频，键盘，鼠标，操纵杆和图形硬件通过OpenGL。[](https://spdx.org/licenses/Zlib.html)
* [sdl-gpu](https://github.com/grimfang4/sdl-gpu)-高性能的现代2D图形库。基于SDL。[](https://spdx.org/licenses/MIT.html)
* [SIGIL](http://www.libsigil.com/)-声音，输入和图形集成库; 一个简单的替代其他库做所有这些事情。各种许可证，全部开源。
* [uastar](https://github.com/ferreiradaselva/uastar)-最小A * 实现。[](https://spdx.org/licenses/Zlib.html)
## 图形
C中的图形的编程操作; 如果你想制作一个GUI，图形用户界面部分有你需要的。
* [AssetKit](https://github.com/recp/AssetKit)基于COLLADA/glTF规范的3D资产导入器/导出器/util库[](https://spdx.org/licenses/MIT.html)
* [Cairo](http://cairographics.org/)-2D图形库。[](https://spdx.org/licenses/LGPL-2.1-only.html)或[](https://spdx.org/licenses/MPL-1.1.html)。
* [cmt](https://github.com/recp/cmt)-C绑定/包装苹果的金属图形框架。[](https://spdx.org/licenses/MIT.html)
* [giflib](https://sourceforge.net/projects/giflib/)-用于读取和写入gif图像的库。[](https://spdx.org/licenses/MIT.html)
* [graphene](http://ebassi.github.io/graphene/)-图形数据类型的薄层。[](https://spdx.org/licenses/MIT.html)
* [heman](https://github.com/prideout/heman)-处理高度图的图像实用程序的微型库，法线贴图，距离场等。[](https://spdx.org/licenses/MIT.html)
* [libcaca](https://github.com/cacalabs/libcaca)-用于基于终端的接口的ASCII渲染器。[](https://spdx.org/licenses/WTFPL.html)
* [libgd](https://github.com/libgd/libgd)-由程序员动态创建图像的库。[](https://spdx.org/licenses/MIT.html)
* [libimagequant](https://pngquant.org/lib/)-用于高质量转换的小型便携式库RGBA图像到8位索引彩色图像。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [libjpeg-turbo](https://libjpeg-turbo.virtualgl.org/)-更快的库读取和写入JPEG文件。[Various licences](https://www.libjpeg-turbo.org/About/License)。
* [libpng](http://www.libpng.org/)-官方PNG参考库。[](https://spdx.org/licenses/Libpng.html)
* [libRSVG](https://wiki.gnome.org/action/show/Projects/LibRsvg?action=show&redirect=LibRsvg)-库使用开罗渲染SVG文件。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [libsixel](https://github.com/saitoha/libsixel)实现SIXEL协议的库，允许漂亮的终端中的图形。[](https://spdx.org/licenses/MIT.html)
* [libspng](https://libspng.org/)-用于读取和写入PNG文件的更简单的界面。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [libvips](https://libvips.github.io/libvips/)图像处理库。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [libxmi](https://gnu.org/software/libxmi/)-用于栅格化2D向量的函数库图形。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [lightmapper](https://github.com/ands/lightmapper)-用于光照贴图烘焙的单文件库，使用现有的OpenGL渲染器。公共领域。
* [little CMS](www.littlecms.com)-色彩管理系统。它提供了ICC配置文件之间的快速转换。[](https://spdx.org/licenses/MIT.html)
* [mozjpeg](https://github.com/mozilla/mozjpeg)-改进的JPEG编码器。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [nanovg](https://github.com/memononen/nanovg)-在OpenGL之上的反锯齿2D矢量绘图库，用于UI和可视化。[](https://spdx.org/licenses/Zlib.html)
* [OpenGL](https://www.opengl.org/)-高性能显卡的行业标准，具有本机C绑定。[Various licenses](http://www.sgi.com/tech/opengl/?/license.html)。
* [PlutoVG](https://github.com/sammycage/plutovg)-一个独立的二维矢量图形库在C[](https://spdx.org/licenses/MIT.html)
* [SAIL](https://github.com/smoked-herring/sail)-⛵人类缺少的小而快速的图像解码库 (不适用于机器)[](https://spdx.org/licenses/MIT.html)
## 图形用户界面
Widget工具包，或以类似方式使用它们的东西。
* [GTK+](https://www.gtk.org/)-跨平台的小部件工具包。[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)-另一个跨平台的小部件工具包。[](https://spdx.org/licenses/MIT.html)
* [microui](https://github.com/rxi/microui)-用便携式ANSI C编写的微型即时模式UI库。[](https://spdx.org/licenses/MIT.html)
* [nuklear](https://github.com/Immediate-Mode-UI/Nuklear)-小，C89，单标题小部件工具包。公共领域。
* [tinyfiledialogs](https://sourceforge.net/projects/tinyfiledialogs/)-用于简单对话框的单文件库。兼容与许多其他工具包和操作系统。[](https://spdx.org/licenses/Zlib.html)
* [Tk](http://www.tcl.tk/)-基本的小部件工具包。Tcl/Tk的一部分。[](https://spdx.org/licenses/TCL.html)
* [XForms Toolkit](http://xforms-toolkit.org/)-为XWindow设计的小部件工具包系统。[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [LVGL](https://lvgl.io/)-嵌入式GUI与易于使用的图形元素，美丽的视觉效果和低内存占用。[](https://spdx.org/licenses/MIT.html)
* [luigi](https://github.com/nakst/luigi)-用于Win32，X11和Essence的准系统单标题GUI库。[](https://spdx.org/licenses/MIT.html)
## 散列
的哈希函数实现* 非* -加密目的。加密哈希可以在Crypto部分中找到。
* [CLHash](https://github.com/lemire/clhash)-库实现可笑的快速CLHash哈希功能。仅适用于Intel Haswell或更新版本。[](https://spdx.org/licenses/Apache-2.0.html)
* [HighwayHash](https://github.com/google/highwayhash)-快速，强大，SIMD-使用哈希函数。还包含SipHash的实现 (尽管速度较慢)。[](https://spdx.org/licenses/Apache-2.0.html)
* [SpookyHash](https://github.com/centaurean/spookyhash)-非常快速的哈希函数。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [t1ha](https://github.com/leo-yuriev/t1ha)-快速正哈希-一个便携式，快速的哈希函数。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [xxHash](http://cyan4973.github.io/xxHash)-非常快速的哈希算法。有32位和64位品种。[](https://spdx.org/licenses/BSD-2-Clause.html)
## 学习、参考和教程
学习C编程的一般资源，或一些有用的相关资源到C编程。
### 在线参考资源
* [Benchmarks of the Lockless Memory Allocator](https://locklessinc.com/benchmarks_allocator.shtml)
* [C FAQ - comp.lang.c Frequently Asked Questions](http://c-faq.com/)
* [Comparison of C/POSIX standard library implementations for Linux](http://www.etalabs.net/compare_libcs.html)
* [Draft C89 standard](https://port70.net/~nsz/c/c89/c89-draft.html)
* [Draft C99 standard](https://port70.net/~nsz/c/c99/n1256.html)
* [Draft C11 standard](https://port70.net/~nsz/c/c11/n1570.html)
* [Finding the best 64-bit simulation PRNG](http://nullprogram.com/blog/2017/09/21/)
* [SEI CERT C Coding Standard](https://wiki.sei.cmu.edu/confluence/display/c/SEI+CERT+C+Coding+Standard)
* [tinyc.game](https://github.com/superjer/tinyc.games)-微小的C游戏，你可以编译和运行现在http:// tinyc.games[](https://spdx.org/licenses/MIT.html)
### 初学者在线资源
* [A tutorial on pointers](https://pdos.csail.mit.edu/6.828/2017/readings/pointers.pdf)
* [A tutorial on portable Makefiles](http://nullprogram.com/blog/2017/08/20/)
* [Building C Projects](http://nethack4.org/blog/building-c.html)
* [C Programming Wikibook](https://en.wikibooks.org/wiki/C_Programming)
* [Introduction to `fun' C](https://gist.github.com/eatonphil/21b3d6569f24ad164365)
* [Learning C with GDB](https://www.recurse.com/blog/5-learning-c-with-gdb)
* [memcpy vs memmove](https://web.archive.org/web/20170620131430/https://www.tedunangst.com/flak/post/memcpy-vs-memmove)
* [POSIX Threads Programming tutorial](https://computing.llnl.gov/tutorials/pthreads/)(有点过时，但大部分是仍然有效和有用)
* [The GNU C Programming Tutorial](http://www.crasseux.com/books/ctut.pdf)(在线PDF)
* [Templating in C](http://blog.pkh.me/p/20-templating-in-c.html)
* [What a C programmer should know about memory](https://marek.vavrusa.com/memory/)
* [CodeforWin: Learn C Programming, Data Structures Tutorials and Exercises online](https://codeforwin.org/2015/09/singly-linked-list-data-structure-in-c.html)
* [Learn C: Free and Open-Source Interactive C Tutorial](https://www.learn-c.org)
* [How to program a text adventure in C](https://github.com/helderman/htpataic)
### 在线中间资源
* [8 gdb tricks you should know](https://blogs.oracle.com/linux/8-gdb-tricks-you-should-know-v2)
* [10 C99 tricks](http://blog.noctua-software.com/c-tricks.html)
* [A comprehensive MPI tutorial resource](http://mpitutorial.com/)
* [Build Your Own Text Editor](https://viewsourcecode.org/snaptoken/kilo/)
* [Diving into concurrency: trying out mutexes and atomics](https://jvns.ca/blog/2014/12/14/fun-with-threads/)
* [Generic C reference counting](https://nullprogram.com/blog/2015/02/17)
* [How to write portable C without complicating your build](https://nullprogram.com/blog/2017/03/30)
* [Introduction to OpenMP](https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG)(视频)
* [OpenMP tutorial](https://computing.llnl.gov/tutorials/openMP/)(适用于OpenMP3标准)
* [MPI tutorial](https://computing.llnl.gov/tutorials/mpi/)
* [Scalable C - Writing Large-Scale Distributed C](https://hintjens.gitbooks.io/scalable-c/content/index.html)
* [Some unknown features or tricks in C language](https://proprogramming.org/some-unknown-features-or-tricks-in-c-language/)
* [What every C programmer should know about undefined behaviour](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html)
### 在线高级资源
* [Advanced metaprogramming in C](http://250bpm.com/blog:56)
* [A quick tutorial on implementing and debugging malloc, free, calloc, and realloc](http://danluu.com/malloc-tutorial/)
* [Bit twiddling hacks](https://graphics.stanford.edu/~seander/bithacks.html)
* [Implementing smart pointers for the C programming language](http://snaipe.me/c/c-smart-pointers/)
* [Inline functions in C](http://www.greenend.org.uk/rjk/tech/inline.html)
* [Metaprogramming custom control structures in C](https://www.chiark.greenend.org.uk/~sgtatham/mp/)
* [Solving the temporary storage problem of C macros](https://web.archive.org/web/20170429175803/http://www.samnip.ps/thought/macro-storage-for-inverse-comma)
* [Some dark corners of C](https://docs.google.com/presentation/d/1h49gY3TSiayLMXYmRMaAEMl05FaJ-Z6jDOWOz3EsqqQ/edit?pli=1#slide=id.gaf50702c_0153)
* [Writing efficient C and C code optimization](https://www.codeproject.com/Articles/6154/Writing-Efficient-C-and-C-Code-Optimization)
* [Compiling Algebraic Data Types in Pure C99](https://hirrolot.github.io/posts/compiling-algebraic-data-types-in-pure-c99.html)
### 参考书
* [C: A Reference Manual 5E](https://savedparadigms.files.wordpress.com/2014/09/harbison-s-p-steele-g-l-c-a-reference-manual-5th-ed.pdf)-C99的完整参考书。
* [C in a Nutshell 2E](http://shop.oreilly.com/product/0636920033844.do)-C11的简明参考书。
* [C Pocket Reference](http://shop.oreilly.com/product/9780596004361.do)-C99简明参考书。
* [The C Programming Language 2E](https://en.wikipedia.org/wiki/The_C_Programming_Language)-原著在C，由其创作者。
### 初学者书籍
* [C Primer Plus 6E](https://www.pearson.com/us/higher-education/program/Prata-C-Primer-Plus-6th-Edition/PGM4399.html)-完整的c11编程教程。
* [C Programming: A Modern Approach](http://knking.com/books/c2/index.html)-学习基础知识的优秀书籍的C。
* [Head First C](http://shop.oreilly.com/product/0636920015482.do)-学习C的 “Head-first” 样式书。
### 中级书籍
* [21st Century C](http://shop.oreilly.com/product/0636920033677.do)-不错_ 第二_ 关于C的编程书。
* [Understanding and Using C Pointers](http://shop.oreilly.com/product/0636920028000.do)-中的指针上的深入资源C.
* [ZeroMQ](http://shop.oreilly.com/product/0636920026136.do)-使用ZeroMQ与C的书。
### 高级书籍
* [Expert C Programming: Deep C Secrets](https://dl.acm.org/citation.cfm?id=179241)-有趣，深入和有趣的是看看C的内部。
## 词法与句法分析
专门用于词法分析 (或词法分析) 和句法分析的库(或解析)。
* [flex](https://github.com/westes/flex)-快速词法分析器生成器。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [GNU Bison](https://www.gnu.org/software/bison/)-通用解析器生成器，用于转换将带注释的上下文无关语法转换为一系列解析器。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [hammer](https://github.com/abiggerhammer/hammer)-二进制格式的解析器组合器。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [mpc](https://github.com/orangeduck/mpc)-解析器组合程序库。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [owl](https://github.com/ianh/owl)-用于可见下推语言的解析器生成器。[](https://spdx.org/licenses/MIT.html)
* [re2c](http://re2c.org/index.html)-词法生成器，生产快速词法分析器，可以访问其内部构件。公共领域。
## 内存管理
无论是不同的，更快的malloc或彻底的垃圾收集，任何管理C内存住在这里。
* [Boehm GC](https://www.hboehm.info/gc/)-C的垃圾收集。各种许可证，都是开源的。
* [jemalloc](http://jemalloc.net)-Malloc实现，强调避免碎片和可扩展的并发支持。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [Lockless Memory Allocator](https://locklessinc.com/)-高效的内存分配器。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [libcsptr](https://github.com/Snaipe/libcsptr)-C的智能指针。[](https://spdx.org/licenses/MIT.html)
* [rpmalloc](https://github.com/rampantpixels/rpmalloc)-线程缓存，快速内存分配器，自然对齐32字节的边界。公共领域。
* [talloc](https://talloc.samba.org/talloc/doc/html/index.html)-分层，参考计数的内存池系统析构函数。[](https://spdx.org/licenses/LGPL-3.0-or-later.html)
* [tlsf](http://www.gii.upv.es/tlsf/)-两级隔离的Fit分配器; 一个通用的、动态的内存分配器旨在满足实时要求。[Up-to-dateimplementation](https://github.com/minad/tlsf)。[](https://spdx.org/licenses/BSD-3-Clause.html)
## 多媒体
* [aubio](https://github.com/aubio/aubio)-音频和音乐分析库。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [FFMPEG](https://www.ffmpeg.org/)-完整的跨平台解决方案来记录，转换和流音频和视频。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [GStreamer](https://gstreamer.freedesktop.org/)-音频和视觉媒体的框架。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [libmpv](https://mpv.io)-音乐播放库。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [libsndfile](http://www.mega-nerd.com/libsndfile/)-用于读取和写入声音文件的库。支架许多格式。[](https://spdx.org/licenses/LGPL-2.1-only.html)或[](https://spdx.org/licenses/LGPL-3.0-only.html)
* [libsoundio](http://libsound.io)-跨平台库，实时音频输入和输出。有一系列的后端。[](https://spdx.org/licenses/MIT.html)
* [libVLC](https://wiki.videolan.org/LibVLC)-完整的音频和视频多媒体库编码，解码，播放和流媒体。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [lodepng](https://lodev.org/lodepng/)-简单的PNG图像解码器和编码器，不需要其他依赖关系。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [minimp3](https://github.com/lieff/minimp3)-轻量级MP3解码器单头库。[](https://spdx.org/licenses/CC0-1.0.html)
* [Soundpipe](http://paulbatchelor.github.io/proj/soundpipe.html)-轻量级的音乐DSP库。[](https://spdx.org/licenses/MIT.html)
## 网络和互联网
低级网络和互联网相关的东西。如果你想要更多的东西全面和高级，您可能需要Web框架部分。
* [asnlc](http://lionet.info/asn1c/compiler.html)将ASN.1规范编译成C源代码。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [CHL](https://github.com/it4e/CHL)-C超文本库-用于在中编写web应用程序的库C.[](https://spdx.org/licenses/GPL-3.0-only.html)
* [czmq](http://czmq.zeromq.org)-ZeroMQ的高级绑定。[](https://spdx.org/licenses/MPL-2.0.html)
* [Dyad.c](https://github.com/rxi/dyad)-轻量级，简单，异步网络库。[](https://spdx.org/licenses/MIT.html)
* [GNU adns](https://www.gnu.org/software/adns/)-先进的，易于使用的，异步功能的DNS客户端库和公用事业。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [gumbo-parser](https://github.com/google/gumbo-parser)C99中的HTML5解析库。[](https://spdx.org/licenses/Apache-2.0.html)
* [H20](https://h2o.examp1e.net/)-新一代HTTP服务器。[](https://spdx.org/licenses/MIT.html)
* [llhttp](https://llhttp.org)-HTTP请求/响应解析器。[](https://spdx.org/licenses/MIT.html)
* [ldns](http://www.nlnetlabs.nl/projects/ldns/index.html)-库，以简化DNS编程。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libcurl](https://curl.haxx.se/libcurl/)-客户端URL传输库，支持广泛的格式。[](https://spdx.org/licenses/curl.html)
* [LibEtPan](http://www.etpan.org)-为IMAP提供高效网络的邮件库，SMTP、POP和NNTP。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libev](http://software.schmorp.de/pkg/libev.html)-又一个事件循环。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [libevent](http://libevent.org/)-网络服务器的事件循环替换。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libhttpd](https://www.hughes.com.au/products/libhttpd/)-库将基本的web服务器功能添加到应用程序或嵌入式设备。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [libhv](https://github.com/ithewei/libhv)跨平台事件循环库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libidn](https://gnu.org/software/libidn/)-实现Stringprep，Punycode和IDNA规格。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [libmicrohttpd](https://gnu.org/software/libmicrohttpd/)-小型库，可以很容易地运行HTTP服务器作为另一个应用程序的一部分。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [libnl](https://www.infradead.org/~tgr/libnl/)-是一个库集合，用于将api提供给Netlink协议 (替代ioctl)。它的主要用途是沟通使用linux内核，修改网络状态 (接口，路由等)。[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [libonion](https://www.coralbits.com/libonion/)-HTTP服务器库，旨在易于使用。[](https://spdx.org/licenses/Apache-2.0.html)
* [libpcap](https://github.com/the-tcpdump-group/libpcap)-API提供给各种内核数据包捕获机制。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libquickmail](http://sourceforge.net/projects/libquickmail/)-旨在为开发人员提供一种发送方式的库电子邮件从他们的应用程序。支持多个收件人/抄送/密件抄送收件人和无大小限制的附件。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [libsagui](https://risoflora.github.io/libsagui/)-跨平台HTTP服务器库。[](https://spdx.org/licenses/LGPL-3.0-or-later.html)
* [libuhttpd](https://github.com/zhaojh329/libuhttpd)-一个非常灵活，轻量级和完全异步的HTTP服务器基于libev和http解析器的嵌入式Linux库。[](https://spdx.org/licenses/MIT.html)
* [LibVNCServer](https://github.com/LibVNC/libvncserver)-跨平台库来实现VNC服务器和/或客户端功能。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [libwebsock](https://github.com/JonnyWhatshisface/libwebsock)-易于使用和强大的web套接字库。[](https://spdx.org/licenses/LGPL-3.0-only.html)
* [libzmq](https://github.com/zeromq/libzmq)-核心ZeroMQ库，高性能异步消息库，旨在在分布式或并发应用程序中使用。C API (后端C)[](https://spdx.org/licenses/GPL-3.0-or-later.html)带静态链接异常
* [lwan](https://lwan.ws)-实验性、可扩展、高性能HTTP服务器。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [mongoose](https://cesanta.com)-嵌入式web服务器。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [MQTT-C](https://github.com/LiamBindle/MQTT-C)-适用于嵌入式系统和pc的便携式MQTT C客户端。[](https://spdx.org/licenses/MIT.html)
* [nanomsg](https://github.com/nanomsg/nanomsg)-基于C实现的ZeroMQ。[](https://spdx.org/licenses/MIT.html)
* [NNG](https://nanomsg.github.io/nng/)-nanomsg-下一代-轻量级无代理消息传递。[](https://spdx.org/licenses/MIT.html)
* [oSip](https://gnu.org/software/osip/)-没有额外的SIP实施依赖关系。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [silgy](https://github.com/silgy/silgy)-用于C/C项目的异步HTTP(S) 引擎。[](https://spdx.org/licenses/MIT.html)
* [socket99](https://github.com/silentbicycle/socket99)-BSD套接字API的C99包装。[](https://spdx.org/licenses/ISC.html)
* [twitc](https://github.com/sinemetu1/twitc)-用于与Twitter OAuth API交互的迷你库。[](https://spdx.org/licenses/MIT.html)
* [uriparser](https://uriparser.github.io)-严格符合RFC 3986的URI解析和处理库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [Wslay](https://tatsuhiro-t.github.io/wslay/)-WebSocket库。实现WebSocket的版本13协议，如RFC 6455中所述。[](https://spdx.org/licenses/MIT.html)
* [zyre](https://github.com/zeromq/zyre)-基于邻近的对等应用的框架。[](https://spdx.org/licenses/MPL-2.0.html)
## 数值
* [apophenia](http://apophenia.info)-统计和科学计算库。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [Arb](https://github.com/fredrik-johansson/arb)-用于任意精度区间算术的库。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [ATLAS](http://math-atlas.sourceforge.net/)-自动调整线性代数软件。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [clBLAS](https://github.com/clMathLibraries/clBLAS)-用OpenCL编写的bla函数。[](https://spdx.org/licenses/Apache-2.0.html)
* [cmathl](https://scientificc.github.io/cmathl/)-数学库与各种各样的数学函数与cmke构建支持。寻求接近C89/C90兼容的便携性。[](https://spdx.org/licenses/MIT.html)
* [Cuba](http://www.feynarts.de/cuba/)-多维数值积分库。[](https://spdx.org/licenses/LGPL-3.0-only.html)
* [fft-c](https://github.com/adis300/fft-c)-来自netlib的fftpack的高性能傅立叶变换; 以用户友好的格式包装[](https://spdx.org/licenses/MIT.html)
* [FFTW](http://www.fftw.org/)-西方最快的傅立叶变换; 高度优化的快速傅立叶变换例程。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [FLINT](http://flintlib.org/)-数论的快速库; 支持算术的库有数字、多项式、幂级数和矩阵，其中其他人。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [GLPK](https://gnu.org/software/glpk/)-GNU线性编程工具包; 用于解决大规模线性规划、混合整数规划等相关问题。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [GMP](https://gmplib.org/)-GNU多精度算术库; 用于任意精度算术。[](https://spdx.org/licenses/GPL-2.0-only.html)或[](https://spdx.org/licenses/LGPL-3.0-only.html)
* [GNU MPC](http://www.multiprecision.org/mpc/)·复数算术库[](https://spdx.org/licenses/LGPL-3.0-or-later.html)
* [GNU MPFR](http://mpfr.loria.fr/index.html)-任意精度浮点库算术。[](https://spdx.org/licenses/LGPL-3.0-or-later.html)
* [GNU MPRIA](https://gnu.org/software/mpria/)-用于多精度有理的便携式数学库区间算术。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [GSL](https://www.gnu.org/software/gsl/)-GNU科学库; 一个复杂的数字库。[](https://spdx.org/licenses/GPL-3.0-only.html)。
* [KISS FFT](https://sourceforge.net/projects/kissfft/)简单的快速傅立叶变换库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [LAPACKE](http://www.netlib.org/lapack/lapacke.html)-接口到[LAPACK](http://www.netlib.org/lapack/)。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [LibTomMath](http://www.libtom.net/LibTomMath/)-便携式，数论，多精度整数库。支持代数、数字操作、模块化归约和各种数论例程。公共领域。
* [LibTomPoly](http://www.libtom.net/LibTomPoly/)-多项式相关的数学库。公共领域。
* [PARI/GP](http://pari.math.u-bordeaux.fr/)-数论的计算机代数系统; 包括一个编译器到C。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [PETSc](http://www.mcs.anl.gov/petsc/)-一套可扩展并行的数据结构和例程用偏微分建模的科学应用的解决方案方程式。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [SCS](https://github.com/cvxgrp/scs)-分裂圆锥求解器; 一个数值优化包求解大规模凸锥问题。[](https://spdx.org/licenses/MIT.html)
* [SLEPc](http://slepc.upv.es/)-用于解决大型稀疏特征值的库并行计算机上的问题。[](https://spdx.org/licenses/LGPL-3.0-only.html)
* [TomsFastMath](http://www.libtom.net/TomsFastMath/)-一套优化的数学运算 (汇编)，适合加密使用。公共领域。
* [Yeppp!](https://bitbucket.org/MDukhan/yeppp)-快速，SIMD优化的数学库。[](https://spdx.org/licenses/BSD-3-Clause.html)
## 剖析
* [gperftools](https://github.com/gperftools/gperftools)-收集用于测量和改进的实用程序性能。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [gprof](https://www.gnu.org/software/binutils/)-性能分析工具。GNU binutils的一部分。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [OProfile](http://oprofile.sourceforge.net/news/)-Linux的统计分析器。可以分析任何代码(包括内核!) 低开销，无需重新编译。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [perf](https://perf.wiki.kernel.org/index.php/Main_Page)-基于linux内核的分析器，具有很多功能。[](https://spdx.org/licenses/GPL-2.0-only.html)
## PDF
* [pdfio](https://github.com/michaelrsweet/pdfio)-PDFio是一个简单的C库，用于读写pdf文件。[](https://spdx.org/licenses/Apache-2.0.html)
## 正则表达式
* [Onigmo](https://github.com/k-takata/Onigmo)-Oniguruma的叉子，支持更高级的regexps。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [Oniguruma](https://github.com/kkos/oniguruma)-支持广泛编码的正则表达式库，以及整合了许多面向安全的修补程序。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [PCRE](http://www.pcre.org/)-实现与Perl 5。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [SLRE](https://github.com/cesanta/slre)-超轻正则表达式库; 一个小Perl正则表达式语法子集的实现。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [TRE](https://github.com/laurikari/tre/)-符合POSIX，功能完整的正则表达式库。[](https://spdx.org/licenses/BSD-2-Clause.html)
## 序列化
* [binn](https://github.com/liteserver/binn)-二进制序列化格式，意味着紧凑，快速和易于使用。[](https://spdx.org/licenses/Apache-2.0.html)
* [c-capnproto](https://github.com/jmckaskill/c-capnproto)-Cap'n Proto序列化的实现协议。[](https://spdx.org/licenses/MIT.html)
* [cmp](https://github.com/camgunz/cmp)-实施[MessagePack](https://msgpack.org/)序列化协议。[](https://spdx.org/licenses/MIT.html)
* [flatcc](https://github.com/dvidelabs/flatcc)-[FlatBuffers](https://google.github.io/flatbuffers/)编译器和库。[](https://spdx.org/licenses/Apache-2.0.html)
* [libavro](http://avro.apache.org/docs/current/api/c/index.html#_introduction_to_avro_c)Avro数据序列化系统的实现。[](https://spdx.org/licenses/Apache-2.0.html)
* [mpack](https://github.com/ludocode/mpack)-另一个实现[MessagePack](https://msgpack.org/)序列化协议。[](https://spdx.org/licenses/MIT.html)
* [OPIC](http://opic.rocks/)-C中的对象持久性; 革命性的序列化框架，具有匹配的磁盘上和内存中的表示形式。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [protobuf-c](https://github.com/protobuf-c/protobuf-c)Google协议缓冲区的实现。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [tpl](https://github.com/troydhanson/tpl)-小型二进制序列化库。[](https://spdx.org/licenses/MIT.html)
* [xdr](https://en.wikipedia.org/wiki/External_Data_Representation)-外部数据表示; 数据的标准序列化。标准 (无许可证适用)。
* [pbtools](https://github.com/eerimoq/pbtools)Google协议缓冲区C源代码生成器。[](https://spdx.org/licenses/MIT.html)
## 源代码集合
小源代码的集合。如果你想要一些大的和集成的东西，检查框架部分。
* [CCAN](http://ccodearchive.net/)-以Perl的CPAN为模型，这是一个大的代码集合做的东西。完整列表是[here](http://ccodearchive.net/list.html)。各种许可证，所有开源。
* [clib](https://github.com/clibs/clib)-一个包管理器的东西。附带a[bunch of libraries of its own](https://github.com/clibs/clib/wiki/Packages)。[](https://spdx.org/licenses/MIT.html)
* [gnulib](https://www.gnu.org/software/gnulib/)-通用GNU代码的集合。各种许可证，所有开源。
* [libdjb](http://www.fefe.de/djb/)-收集库做各种事情。(显然)公共领域。
* [mmx](https://github.com/vurtun/mmx)-单头库的集合。各种许可证，所有开源。
* [par](https://github.com/prideout/par)-一堆单文件库。[](https://spdx.org/licenses/MIT.html)
* [Snippets](https://github.com/DanielGibson/Snippets/)-有用的代码片段和仅标题库。公共领域。
* [stb](https://github.com/nothings/stb)-单文件库的范围。公共领域。
* [tinyheaders](https://github.com/RandyGaul/tinyheaders)-仅标题库的集合，主要面向走向游戏开发。[](https://spdx.org/licenses/Zlib.html)
* [zpl](https://github.com/zpl-c/zpl)-C99跨平台的标题只有库与许多好东西。[,][BSD-3-Clause，取消许可]
## 标准库
(标准强制) C标准库的实现。
* [Bionic](https://github.com/aosp-mirror/platform_bionic)-为Android开发的Google标准库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [cloudlibc](https://github.com/NuxiNL/cloudlibc)-基于概念的标准库[capability-based security](https://en.wikipedia.org/wiki/Capability-based_security)。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [dietlibc](https://www.fefe.de/dietlibc/)-为尽可能小的设计标准库二进制文件。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [glibc](https://www.gnu.org/software/libc/)-GNU C库; 标准的实现库。[](https://spdx.org/licenses/LGPL-2.1-only.html)。
* [musl](https://musl.libc.org/)-标准库，与POSIX 2008和c11兼容。设计用于静态链接。[](https://spdx.org/licenses/MIT.html)
* [PDCLib](http://pdclib.e43.eu/)-公共领域C库。实现了大部分的C99和一些C11。[](https://spdx.org/licenses/CC0-1.0.html)
* [uClibc-ng](https://uclibc-ng.org/)-用于开发嵌入式系统的小型C库。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
### 模板库
* [CTL](https://github.com/rurban/ctl)-C容器模板库 (CTL)[](https://spdx.org/licenses/MIT.html)
## 字符串操作
* [bstring](http://mike.steinert.ca/bstring/)-更好的字符串库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [ICU](http://site.icu-project.org/)-Unicode的国际组件; Unicode库支持。[](https://spdx.org/licenses/ICU.html)
* [levenstein.c](https://github.com/wooorm/levenshtein.c)-[Levenstein distance](https://en.wikipedia.org/wiki/Levenshtein_distance)算法实现。[](https://spdx.org/licenses/MIT.html)。
* [libunistring](https://gnu.org/software/libunistring/)-用于操作Unicode的库字符串。[](https://spdx.org/licenses/LGPL-3.0-only.html)
* [libgiconv](https://gnu.org/software/libiconv/)-文本转换库。[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [librope](https://github.com/josephg/librope)-UTF-8绳子 ('沉重' 字符串) 库。[](https://spdx.org/licenses/MIT.html)
* [SDS](https://github.com/antirez/sds)-简单的动态字符串; 用于处理字符串的库更简单的方法，但一个与正常的C字符串兼容功能。可通过[clib](https://github.com/clibs/clib)。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [stmr.c](https://github.com/wooorm/stmr.c)-[Porter Stemmer](http://tartarus.org/martin/PorterStemmer/)算法实现。[](https://spdx.org/licenses/MIT.html)
* [str](https://github.com/maxim2266/str)-另一个用于c语言的字符串库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [utf8.h](https://github.com/sheredom/utf8.h)-单头UTF-8库，旨在模仿C风格的字符串功能。公共领域。
* [utf8proc](https://github.com/JuliaLang/utf8proc)-用于处理UTF-8数据的库。[](https://spdx.org/licenses/MIT.html)
## 结构化文件处理
这包括XML、JSON、CSV和其他类似格式的库。
### CSV
* [libcsv](https://github.com/rgamble/libcsv)-简单，流式CSV解析器。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
### JSON
* [Jansson](http://www.digip.org/jansson/)-用于编码，解码和操作JSON的库。[](https://spdx.org/licenses/MIT.html)
* [jfes](https://github.com/NeonMercury/jfes)-嵌入式系统的JSON; 简单的JSON引擎，没有任何依赖关系。[](https://spdx.org/licenses/MIT.html)
* [jsmn](https://zserge.com/jsmn.html)-简约的JSON解析器[](https://spdx.org/licenses/MIT.html)
* [json](https://github.com/recp/json)-简单，低内存-使用JSON解析器。[](https://spdx.org/licenses/MIT.html)
* [json-c](https://github.com/json-c/json-c)-在C中轻松使用JSON。附带一个引用计数的对象模型，并以符合[RFC 7159](https://tools.ietf.org/html/rfc7159)。[](https://spdx.org/licenses/MIT.html)
* [json.h](https://github.com/sheredom/json.h)-单文件非流式JSON解析器。[](https://spdx.org/licenses/Unlicense.html)
* [parson](https://github.com/kgabis/parson)-两个文件，C89-compatible JSON解析器。[](https://spdx.org/licenses/MIT.html)
* [WJElement](https://github.com/netmail-open/wjelement/)-高级JSON操作库，支持JSON架构。[](https://spdx.org/licenses/LGPL-2.0-or-later.html)或[](https://spdx.org/licenses/LGPL-2.1-or-later.html)或[](https://spdx.org/licenses/LGPL-3.0-or-later.html)
* [YAJL](https://lloyd.github.io/yajl/)-快速流JSON解析器库。[](https://spdx.org/licenses/ISC.html)
### INI
* [inih](https://github.com/benhoyt/inih)小而简单的ini文件解析器，适合嵌入式系统。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [iniparser](https://github.com/ndevilla/iniparser)-用于的解析器。ini文件。[](https://spdx.org/licenses/MIT.html)
* [libconfini](https://madmurphy.github.io/libconfini/html/index.html)-另一个INI解析器。[](https://spdx.org/licenses/GPL-3.0-only.html)
* [minIni](https://github.com/compuphase/minIni)-小而便携的INI解析器。[](https://spdx.org/licenses/Apache-2.0.html)
### 其他
* [libbson](https://github.com/mongodb/libbson)-BSON实用程序库。[](https://spdx.org/licenses/Apache-2.0.html)
* [libcbor](https://github.com/PJK/libcbor): C和其他人的CBOR协议实现。[](https://spdx.org/licenses/MIT.html)
* [libconfuse](https://github.com/martinh/libconfuse)小型配置文件解析器库。[](https://spdx.org/licenses/ISC.html)
* [libelf](https://github.com/0intro/libelf)-用于解析ELF文件的简单库。[](https://spdx.org/licenses/MIT.html)
* [libucl](https://github.com/vstakhov/libucl)通用配置库解析器。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [libxo](https://github.com/Juniper/libxo)-允许应用程序生成纯文本，XML，JSON和使用一组通用函数调用的HTML输出。应用程序在运行时决定应该产生什么输出样式。[](https://spdx.org/licenses/BSD-2-Clause.html)
### XML
* [Expat](http://expat.sourceforge.net/)-面向流的XML解析器。[MIT](https://spdx.org/licenses/MIT.html)
* [libxml2](http://xmlsoft.org/)-符合标准，可移植的XML解析器。[MIT](https://spdx.org/licenses/MIT.html)
* [xml](https://github.com/recp/xml)-简单，低内存-使用XML解析器/tokenizer[](https://spdx.org/licenses/MIT.html)
### YAML
* [libYAML](https://www.pyyaml.org/wiki/LibYAML)-YAML 1.1解析器和发射器。[](https://spdx.org/licenses/MIT.html)
## 信号处理
* [libsigrok](https://github.com/smoked-herring/sail)-信号分析软件套件，支持各种设备类型 (如逻辑分析仪、示波器、万用表等)。[][GPL]
## 测试
* [CHEAT](https://github.com/Tuplanolla/cheat)简单的单元测试框架。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [Check](https://libcheck.github.io/check)-单元测试框架。[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [ciut](https://github.com/yhfudev/cpp-ci-unit-test.git)-一个现代的最小麻烦单元测试框架。[](https://spdx.org/licenses/MIT.html)
* [clar](https://github.com/vmg/clar)-清晰和简单的单元测试框架。[](https://spdx.org/licenses/MIT.html)
* [CMock](http://www.throwtheswitch.org/cmock)-模拟/存根生成器。[](https://spdx.org/licenses/MIT.html)
* [cmocka](https://cmocka.org/)-支持模拟对象的单元测试框架。[](https://spdx.org/licenses/Apache-2.0.html)
* [Criterion](https://criterion.readthedocs.io/en/master)-KISS，非侵入式测试框架。[](https://spdx.org/licenses/MIT.html)
* [ctest](https://github.com/bvdberg/ctest)-另一个单元测试框架。[](https://spdx.org/licenses/Apache-2.0.html)
* [CUnit](http://cunit.sourceforge.net/)-另一个单元测试框架。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [greatest](https://github.com/silentbicycle/greatest)-单元测试库在一个文件中，没有内存分配。[](https://spdx.org/licenses/ISC.html)
* [minctest](https://github.com/codeplea/minctest)-单元测试微库。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [munit](https://nemequ.github.io/munit)小型单元测试框架。[](https://spdx.org/licenses/MIT.html)
* [Nala](https://github.com/eerimoq/nala)-C项目的测试框架。[](https://spdx.org/licenses/MIT.html)
* [Rexo](https://github.com/christophercrouzet/rexo)-C89/C框架，具有自动注册测试和完善的API。[](https://spdx.org/licenses/Unlicense.html)
* [Tau](https://github.com/jasmcaus/tau)-C/C的微型单元测试框架 (〜1k代码行)。包括一组丰富的断言宏，支持自动测试注册，并且可以输出为多种格式，如TAP格式或JUnit XML。支持Linux、macOS、FreeBSD和Windows。[](https://spdx.org/licenses/MIT.html)
* [theft](https://github.com/silentbicycle/theft)-基于属性的测试 (类似于[Quickcheck](https://wiki.haskell.org/Introduction_to_QuickCheck2))。[](https://spdx.org/licenses/MIT.html)
* [Unity](http://www.throwtheswitch.org/unity)简单的单元测试框架。[](https://spdx.org/licenses/MIT.html)
* [utest](https://github.com/evolutional/utest)-单头单元测试库。[](https://spdx.org/licenses/Unlicense.html)
## 文本编辑器扩展
虽然几乎任何体面的程序员的文本编辑器都支持C，但有一些扩展，使它更愉快。这些是由编辑标记的。
* [CCompletion](http://freeweb.siol.net/rmihor/NppCCompletionPlugin.zip)-记事本自动完成插件。与所有作品Ctags识别的标识符。这是一个下载链接。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [CEDET](http://cedet.sourceforge.net/)-Emacs开发环境工具的集合; 旨在为Emacs提供类似IDE的功能。内置。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [Flycheck](https://github.com/flycheck/flycheck)-Emacs的现代语法检查。对于C，它可以使用GCC或Clang作为后端。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [Neomake](https://github.com/neomake/neomake)-异步: Neovim/Vim的制作和linting框架。[](https://spdx.org/licenses/MIT.html)
* [Syntastic](https://github.com/vim-syntastic/syntastic)-Vim的语法检查和linting。[](https://spdx.org/licenses/WTFPL.html)
* [YASnippet](http://joaotavora.github.io/yasnippet/)Emacs代码模板系统，以C模板为通用片段。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [YouCompleteMe](https://github.com/ycm-core/YouCompleteMe)-Vim的代码完成引擎。[](https://spdx.org/licenses/GPL-3.0-only.html)
## 工具
有用的程序来帮助你编写和调试C代码* 不* 编辑，库或编译器。
* [Artistic Style](http://astyle.sourceforge.net/)-快速和小型自动源代码格式化程序支持C.[](https://spdx.org/licenses/LGPL-3.0-only.html)
* [address-sanitizer](https://github.com/google/sanitizers)-快速内存错误检测器。[](https://spdx.org/licenses/Apache-2.0.html)
* [bcc](https://projects.malikania.fr/bcc)-一个字节数组生成器，用于从C中直接导入二进制文件xxd的精神。[](https://spdx.org/licenses/ISC.html)
* [c](https://github.com/ryanmjacobs/c)-在命令行上一次编译并执行C “脚本”。也有shebang的支持。[](https://spdx.org/licenses/MIT.html)
* [c99sh](https://github.com/RhysU/c99sh)-使用hash-bang运行C文件。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [cdecl](https://cdecl.org/)-在线服务，将C声明翻译成英文和反之亦然。公共领域。
* [cinclude2dot](https://www.flourish.org/cinclude2dot/)-图形包括使用项目中的依赖关系Graphviz。[GPL-1.0-or-later](https://spdx.org/licenses/GPL-1.0.html)或[](https://spdx.org/licenses/GPL-2.0-or-later.html)或[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [ClangCheck](https://clang.llvm.org/docs/ClangCheck.html)-静态分析工具，旨在与Clang一起工作。[](https://spdx.org/licenses/NCSA.html)
* [conan.io](https://conan.io/)-C的包管理器的东西。[](https://spdx.org/licenses/MIT.html)。
* [Cppcheck](http://cppcheck.sourceforge.net/)-静态分析工具。尽管名称，但与C配合良好。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [Glade](https://glade.gnome.org/)-RAD工具，使GTK的快速开发GUIs。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [GMSL](https://gmsl.sourceforge.net/)-GNU制作标准库; 额外的集合GNU的功能。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [GNU Global](https://www.gnu.org/software/global/)-源代码标记工具。[](https://spdx.org/licenses/GPL-3.0-only.html)
* [GPP](https://logological.org/gpp)-通用预处理器。比C更通用预处理器，但比m4更灵活。[](https://spdx.org/licenses/LGPL-3.0-or-later.html)
* [Highlight](http://www.andre-simon.de/index.php)-将源代码转换为格式化文本与nice突出显示。[](https://spdx.org/licenses/GPL-3.0-only.html)
* [include-what-you-use](https://github.com/include-what-you-use/include-what-you-use)-帮助找到不必要的夹杂物，使建议修复它们。基于LLVM/Clang (并且仅适用于它)。[](https://spdx.org/licenses/NCSA.html)
* [incbin](https://github.com/graphitemaster/incbin)-轻松地在C/C应用程序中包含二进制文件[](https://spdx.org/licenses/Unlicense.html)
* [indent](https://www.gnu.org/software/indent/)-自动格式化C源代码，使其更容易阅读。也从一种样式的源转换为另一种样式。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [SMACK](https://github.com/smackers/smack)-模块化软件验证工具链和独立的软件验证器。目前仅适用于使用Clang编译的程序。[](https://spdx.org/licenses/MIT.html)
* [unifdef](http://dotat.at/prog/unifdef/)-删除 # ifdef和 # if指令及其分隔文本不接触文件的任何其他部分。[](https://spdx.org/licenses/BSD-3-Clause.html)或[](https://spdx.org/licenses/BSD-2-Clause.html)
## 公用事业
任何不适合其他地方的东西的 “全能” 类别。
* [ApeTagLibs](https://github.com/jeremyevans/ape_tag_libs/tree/master/c)-用于处理APEv2标签的库。[](https://spdx.org/licenses/MIT.html)
* [argparse](https://github.com/cofyc/argparse)-命令行参数解析库，灵感来自Python的argparse模块。[](https://spdx.org/licenses/MIT.html)
* [attr](http://savannah.nongnu.org/projects/attr/)-操作文件系统的命令扩展属性。[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [bfd](http://sourceware.org/binutils/docs/bfd/)-用于操作二进制对象文件的库。GNU的一部分binutils。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [Caffeine](https://github.com/dmw/caffeine)-用于为Linux和Linux构建守护进程和服务的库FreeBSD系统。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [CException](http://www.throwtheswitch.org/cexception)-例外的实施。[](https://spdx.org/licenses/MIT.html)
* [CommonMark](https://github.com/commonmark/commonmark-spec)-CommonMark规范的实现。
* [cosmopolitan](https://github.com/jart/cosmopolitan)-快速可移植的静态本机textmode容器 (为Linux \ Mac \ Windows一次性构建C程序)[Variety of licenses, all open source](https://github.com/commonmark/commonmark-spec/blob/master/LICENSE)。
* [cpu_features](https://github.com/google/cpu_features)-在运行时获取CPU功能。[](https://spdx.org/licenses/Apache-2.0.html)。
* [CRIU](https://criu.org/Main_Page)-用户空间中的检查点/恢复; 软件工具 (带有C API)用于将正在运行的应用程序 “冻结” 到磁盘，然后恢复它。[](https://spdx.org/licenses/GPL-2.0-only.html)或[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [D-Bus](https://www.freedesktop.org/wiki/Software/dbus/)-应用程序与一个简单的方法另一个。[](https://spdx.org/licenses/AFL-2.1.html)或[](https://spdx.org/licenses/GPL-2.0-or-later.html)
* [Discount](http://www.pell.portland.or.us/~orc/Code/discount/)-Markdown解析器的简单实现。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [dlx](https://github.com/blynn/dlx)-实施[Knuth's Algorithm X](https://en.wikipedia.org/wiki/Knuth's_Algorithm_X),有例子解决者。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [docopt.c](https://github.com/docopt/docopt.c)-命令行选项解析器的实现。[](https://spdx.org/licenses/MIT.html)
* [dyncall](http://www.dyncall.org/)-另一个外部函数接口库。[](https://spdx.org/licenses/MIT.html)
* [GNU FreeIPMI](https://gnu.org/software/freeipmi/index.html)-带内和带外IPMI实施。[](https://spdx.org/licenses/GPL-3.0-only.html)
* [GNU gperf](https://www.gnu.org/software/gperf/)-完美的哈希函数生成器，给定的列表字符串。输出C代码。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [GNU Libffcall](https://gnu.org/software/libffcall/)-收集用于建立外国功能的库接口。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [Hoedown](https://github.com/hoedown/hoedown)-完全符合标准，支持扩展，UTF-8意识，快速降价解析器。[](https://spdx.org/licenses/MIT.html)
* [Kitsune](http://kitsune-dsu.com/)-高效，通用的动态软件框架正在更新。[](https://spdx.org/licenses/LGPL-3.0-or-later.html)
* [libCello](http://libcello.org/)-引入更高级别的编程的库C.[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libcmark](https://github.com/jgm/cmark)-用于解析CommonMark方言的库降价。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [libcoap](https://github.com/obgm/libcoap)-实施[Constrained Application Protocol](http://coap.technology/)。[](https://spdx.org/licenses/GPL-2.0-or-later.html)或[](https://spdx.org/licenses/BSD-2-Clause.html)
* [libcox](http://libcox.symisc.net/)-允许跨平台系统调用和跨不同操作系统的标准实用程序。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [libffi](https://github.com/atgreen/libffi)可移植的外函数接口库。[](https://spdx.org/licenses/MIT.html)
* [libgeohash](https://github.com/simplegeo/libgeohash)纯C实现的Geohash算法。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [libgit2](https://libgit2.org/)-Git核心方法的可移植实现，作为可重入可链接库。[Custom license](https://github.com/libgit2/libgit2/blob/master/COPYING)。
* [libgss](https://gnu.org/software/gss/)-通用安全服务。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice)-跨平台协议库进行通信用iThings。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [libnfc](https://github.com/nfc-tools/libnfc)-独立于平台的近场通信库。[](https://spdx.org/licenses/LGPL-3.0-only.html)
* [libpostal](https://github.com/openvenues/libpostal)-用于解析和规范化街道地址的库在世界各地。由统计NLP和开放地理数据提供支持。[](https://spdx.org/licenses/MIT.html)
* [libtrading](http://libtrading.org/)-实现用于通信的网络协议与交易所、暗池等交易场所。支持FIX，FIX/FAST和许多专有协议。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [libusb](https://libusb.info/)-提供对USB设备的通用访问。[](https://spdx.org/licenses/LGPL-2.1-or-later.html)
* [libuv](http://libuv.org)-跨平台异步I/O。[](https://spdx.org/licenses/MIT.html)
* [libvldmail](https://github.com/dertuxmalwieder/libvldmail)-您友好的电子邮件验证库。没有外部依赖项 (甚至不是regexps)。[](https://spdx.org/licenses/WTFPL.html)
* [linenoise](https://github.com/antirez/linenoise)-小，独立的替代readline和libedit。[](https://spdx.org/licenses/BSD-2-Clause.html)
* [libXDGdirs](https://github.com/Jorengarenar/libXDGdirs)-XDG基目录规范的实现[](https://spdx.org/licenses/MIT.html)
* [MegaMimes](https://trumpowen.github.io/MegaMimes)-用于获取的库[MIME](https://en.wikipedia.org/wiki/MIME)文件的类型。[](https://spdx.org/licenses/MIT.html)
* [ncurses](https://gnu.org/software/ncurses/)-彩色终端UI库。[](https://spdx.org/licenses/MIT.html)
* [netbsd-curses](https://github.com/sabotage-linux/netbsd-curses)-ncurses的简化和小版本，具有相同的接口。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [nope.c](https://github.com/riolet/WAFer)-用于可扩展服务器端和网络应用程序 (想想C程序员的node.js)。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [obj.h](https://github.com/small-c/obj.h)-单标头支持纯C中的OOP。[](https://spdx.org/licenses/MIT.html)
* [parg](https://github.com/jibsen/parg)-单文件重新实现更好的默认值。[](https://spdx.org/licenses/CC0-1.0.html)
* [pbc](https://github.com/cloudwu/pbc)-协议缓冲区库。[](https://spdx.org/licenses/MIT.html)
* [progressbar](https://github.com/doches/progressbar)-易于使用的库，用于显示文本进度条。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [rabbitmq-c](https://github.com/alanxz/rabbitmq-c)-客户端库[RabbitMQ](http://www.rabbitmq.com/)。[](https://spdx.org/licenses/MIT.html)
* [Ragel](http://www.colm.net/open-source/ragel/)-编译为C的状态机的DSL。[](https://spdx.org/licenses/GPL-2.0-only.html)
* [rmw](https://remove-to-waste.info)-安全-删除命令行的实用程序，可以在x天之后从废物目录中清除项目。[](https://spdx.org/licenses/GPL-3.0-or-later.html)
* [Rogueutil](https://github.com/sakhmatd/rogueutil)-用于创建基于文本的用户的跨平台库接口 (TUI)[](https://spdx.org/licenses/Apache-2.0.html)
* [sort](https://github.com/swenson/sort)-排序例程的集合，其类型专门化于用户定义类型的编译时。[](https://spdx.org/licenses/MIT.html)
* [termbox](https://github.com/nsf/termbox)-用于编写基于文本的接口的库。[](https://spdx.org/licenses/MIT.html)
* [tinyexpr](https://github.com/codeplea/tinyexpr)-微小的递归下降解析器，编译器和评估用于简单数学表达式的引擎。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [tm](https://github.com/recp/tm)-⏱C的计时器和时间线使用情况。[](https://spdx.org/licenses/MIT.html)
* [Tulip Indicators](https://tulipindicators.org/)-用于技术分析的函数库财务数据。[](https://spdx.org/licenses/LGPL-3.0-or-later.html)
* [whereami](https://github.com/gpakosz/whereami)-一个文件库，用于在文件系统。[](https://spdx.org/licenses/WTFPL.html)
* [XLSX I/O](https://brechtsanders.github.io/xlsxio/)-阅读和写作的跨平台库。xlsx文件。[](https://spdx.org/licenses/MIT.html)
* [xlsx_drone](https://github.com/damian-m-g/xlsx_drone)-快速Microsoft Excel的 *.xlsx阅读器。[](https://spdx.org/licenses/MIT.html)
* [zlog](http://hardysimpson.github.io/zlog/)-可靠的，纯C日志库。[](https://spdx.org/licenses/LGPL-2.1-only.html)
* [zproto](https://github.com/zeromq/zproto)-ZeroMQ的协议框架。[](https://spdx.org/licenses/MIT.html)
* [Metalang99](https://github.com/Hirrolot/metalang99)-全面的预处理器元编程。[](https://spdx.org/licenses/MIT.html)
* [Datatype99](https://github.com/Hirrolot/datatype99)-C99的代数数据类型。[](https://spdx.org/licenses/MIT.html)
## Web框架
全面和集成的解决方案，用于构建下一个辉煌的web在C中的应用。
* [Concord](https://github.com/Cogmasters/concord)-用C编写的Discord API包装库。[](https://spdx.org/licenses/MIT.html)
* [facil.io](http://facil.io/)-用于web应用程序的迷你框架。包括一个快速的HTTP和Websocket服务器，还支持自定义协议。[](https://spdx.org/licenses/MIT.html)
* [kcgi](https://kristaps.bsd.lv/kcgi)-C的CGI和FastCGI库[](https://spdx.org/licenses/ISC.html)。
* [KLone](http://www.koanlogic.com/klone/)-功能齐全，多平台，web应用程序开发框架，特别针对嵌入式系统和电器。[](https://spdx.org/licenses/BSD-3-Clause.html)
* [Kore](https://kore.io/)-易于使用的web应用程序框架，用于编写可扩展的C中的web api。[](https://spdx.org/licenses/ISC.html)
## Windows环境
旨在使Windows在以下方面投入21世纪的技术支持C。
* [Cygwin](https://cygwin.com/)-旨在广泛模拟POSIX兼容的环境在Windows下。[Various licenses, all open source](https://cygwin.com/licensing.html)。
* [MinGW-w64](http://mingw-w64.yaxm.org/doku.php/start)-在Windows上进行C开发的简约环境64位支持。[Various licenses, all open source](http://mingw.org/license)。
* [MSYS2](http://msys2.github.io/)-最小系统2; 旨在为POSIX提供支持Windows上的环境，带有基于Arch Linux的包管理器pacman.包有单独的许可证，否则，如MinGW和Cygwin。
