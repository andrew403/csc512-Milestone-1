# Course Project Milestone-1

## Members
- Yung Hsuan Teng
- Jo Hao Huang

### Project Start
To initiate our project, we began by thoroughly reading the LLVM documentation and attempted to run the built-in clang on our computer. We successfully used a test file from a previous homework assignment, which generated a `.ll` file, transforming the original C language into assembly language.

### LLVM Repository Setup
We then proceeded to clone the LLVM GitHub repository onto our computer and attempted to build it. However, we encountered some difficulties in the process.

1. After cloning the code from GitHub, we used the `cmake` command to configure the build (setting the generator as Ninja and build type as debug) by executing `cmake --build build --config Debug`. Unfortunately, there was an issue in the result. We are currently investigating the part that failed to compile, unsure if this affects the overall build. Our assumption is that there might be missing steps or configurations that need attention. We have verified that our versions of `cmake` and `ninja` are up to date.

2. Despite the issues with the configuration, we decided to try building the code directly. The build seemed fine; however, when we attempted the `make` command, it failed to generate a makefile. This indicates that there might be an issue with the `cmake` configuration, preventing the generation of necessary build files.

### Next Steps
Our immediate focus is on successfully building and running the LLVM code. Once this milestone is achieved, we plan to delve into understanding the structure of LLVM and thoroughly explore the codebase.

---
Please see the [google doc](https://docs.google.com/document/d/1iE_LOlKSIuWxxjMnYPfdsQLz-UYNeKn1QI3e5aGW6bU/edit?usp=sharing) for the full content. 
