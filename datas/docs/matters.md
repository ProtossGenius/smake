# matters

1. #include "a/a.hpp" && g++ find file.
use s-link
2. product Makefile. compile/link (CMake)
3. how to config.
- find sub-project list.(config sub-projects in root-dir)
- find #include "*" (if * in sub-projects then create s-link else error endif)

4. result

   1.   analysis .smake get sub-projects; if root-dir, add sub-dirs to sub-projects;
root-dir: find .git/.root/.project ... 
   2.   deep-list c/cpp file, analysis #include
   3.   create s-link or throw error.
   4.   -o binarys's output. main.o ==> main.mo
