# Learning How to Program

## Languages
Learning a programming language can be dividied into two tasks;

1. Learning Language and it constructs.
2. Learning Library (Core + Core Extended)
   
This repository will serve as resource to learn similary concepts in various programming langaugaes.
- C/C++
- Rust
- Go
- Java
- JavaScript
  
## Tools
Each language or its ecosystem provides some almost defacto standard for building and deplying code, for example Rust adopted Cargo as a tool to manage depedencies and build codebases; following is the list of tools we will be using across thsi series.

- C/C++
  - https://gcc.gnu.org/
  - https://www.gnu.org/software/make/
- Rust  
  - https://www.rust-lang.org/tools/install
  - https://doc.rust-lang.org/cargo/index.html
  - https://github.com/rust-lang/rust-clippy
- GO
  - https://go.dev/dl/
- Java
  - https://jdk.java.net/
  - https://maven.apache.org/install.html
  - https://www.jenv.be/
- Javascript
  - https://github.com/nvm-sh/nvm           (NVM can manage installation of nodejs)
  - https://nodejs.org/en/download/current  (Please sue NVM to install lateset nodejs version)
### Compilation
    
    1. Preprocessor
        - Source code
    2. Compiler
        - Include Headers
        - Expand acro
    3. Assembler
        - Assembly Code

    4. Linker
       - Linking extenral libraries
       - Executable 
       - 

### Build Toolchain
    Defined set of tools used in conjunction to build, deploy and test a complex software development task. 

A toolchain, often referred to as a development toolchain or software toolchain, is a set of software tools and components that are used in a specific sequence to facilitate the development, building, and deployment of software applications. Toolchains are commonly associated with software development, but they can also be used in various other fields, including hardware development and manufacturing.

The primary purpose of a toolchain is to streamline and automate the various tasks involved in the development and production of software or other products. 

Tool chain is an arragement of numerwous tools in a cascade fashion, allowing each consecutive step to nurture from the output of previous step and enhance it for its leading step, to ultimately produce the actual binary code that runs on a machine.

As a programmer everyone must have used compiler/linker, to analyze, transforma nd transcode one language to another which is understandable by the runtime machine wheter it be a virtual or real. Tool chains are magical incantations to automate the process of comilation and linking.  Build tool chains consists of;
  <details><summary>Preprocessor</summary>
    <ul>
      <li>it gets rid of all the comments in the source file(s)</li>
      <li>it includes the code of the header file(s), which is a file with extension .h which contains C function declarations and macro definitions</li>
      <li>it replaces all of the macros (fragments of code which have been given a name) by their values</li>
    </ul>
  </details>
  <details><summary>Compiler</summary>
    <ul>
      <li>compiler will take the preprocessed file and generate IR code (Intermediate Representation)/Assembly</li>
      <li>IR code is an assemly code for virtual machine</li>
    </ul>  
  </details>
  <details><summary>Assembler</summary>
    <ul>
      <li>assembler takes the IR code and transforms it into object code, that is code in machine language (i.e. binary).</li>
      <li>This will produce a file ending in “.o”.</li>
    </ul>
  </details>
  <details><summary>Linker</summary>
    <ul>
      <li>Linker creates the final executable, in binary, and can play two roles</li>
      <li>
      linking all the source files together, i.e all other object files in the project. 
      For example, after compiling main.c with another file called library.c and make them into one single program, 
      this is the step where the object code (library.o) will be linked to object code (main.o).
      </li>
    </ul>
  </details>

#### Make
[![Make tutorial](http://img.youtube.com/vi/_r7i5X0rXJk/0.jpg)](https://www.youtube.com/watch?v=_r7i5X0rXJk)

