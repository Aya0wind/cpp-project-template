# cpp-project-template  
A c++ project template, use cmake as buildsystem and use vcpkg to manage dependencies.

+ Auto Package Manager
  Just add your vcpkg dependencies to ```vcpkg.json```,and use find_package in CMakeLists.txt
+ Default GTest integrate
  Use GTest to do your own unit tests.
+ Github Actions integrate
  Auto build your project in Github Action when push to branch.
+ Default clang-format
  Format code for your automatically


## Usage
```bash
git clone https://github.com/Aya0wind/cpp-project-template.git
cmake -Bbuild . -DVCPKG_ROOT=your/local/vcpkg/root #..other args
cmake --build build
./build/main(.exe)
```
    