# <p align="center"> inject
<p align="center"> Simple CLI Linux/Unix Utility, Written In C++ 
<p align="center"> Originally Compiled With G++ (GNU/GCC) 

### Setup  
Run `g++ -o inject inject.cpp`

Note (GCC): -O3 Optimizations Tested As Working. 
Note: injectCX (inject-CustomX) Is A Custom Version Of inject That Uses Memory For Holding All Data Instead Of Disk. This Means That While It Is Faster And More Efficient, It’s Incapable Of Handling Files That Are Larger Than The Amount Of Available System RAM. As Such, Large Files Should Be Handled With Regular inject. 

### Usage  
`inject <File> <Line Number> <Content,...>`
