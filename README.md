# ParMiBench
An Open-Source Benchmark for Embedded Multiprocessor Systems

Published on IEEE

It is a new and open-source benchmark for multiprocessor based embedded system. It comprises a set of parallel implementations for seven classical algorithms that cover different computing features of general-purpose processor. The performance data including tables and figures is provided for guiding the potential users to evaluate the design of multiprocessor based embedded system.

The parallel implementations for seven applications that cover four categories are shown according to the category:

Automation and Industry Control
Bitcount
SUSAN
BASICMATH
Network
Patricia
Dijkstra
Office
Stringsearch
Security
SHA
Among them, Bitcount and Dijkstra involve more than one parallel application implemented for different functions or using different strategies. Bitcount consists three parallel applications, parallel Bitcnt_1, parallel Bitstring and parallel Bitcnts, that implemented bit counting with different strategy. Three parallel applications implemented for Dijkstra. One is for all-pairs shortest paths problem. Another two are for solving single-source shortest paths problem using single queue strategy and multiple queue strategy respectively. Stringsearch consists of Pratt-Boyer-Moore, Case-sensitive Boyer-Moore-Horspool, Case-Insensitive Boyer-Moore-Horspool, and Boyer-Moore-Horspool (Case-insensitive with accented character translation) implementations.

Source code of sequential versions of these applications download from Mibench as well as the standard output based on x86-linux. For OpenMPBench, all parallel applications have been implemented in ANCI C language using POSIX threads. All libraries related to implementations are based on GNU standard library. Development environment is in UBUNTU 9.04 with 2.6.28-generic Linux kernel, GCC 4.2.4 compiler, and Emacs 22.1 editor.

On the basis of current hardware condition, a workstation with 8 processors, shipped with UBUNTU 4.2.4, is selected for experiment environment. UBUNTU is a free GNU Linux version that offers all GNU standard library and GCC has been installed by default. In conclusion, we consider this experiment environment is available to simulate the multiprocessor based on embedded systems.

Copyright: Blekinge Inst. of Technol., Karlskrona, Sweden
http://ieeexplore.ieee.org/xpl/articleDetails.jsp?tp=&arnumber=5550920&url=http%3A%2F%2Fieeexplore.ieee.org%2Fxpls%2Fabs_all.jsp%3Farnumber%3D5550920