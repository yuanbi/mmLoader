## mmLoader 

mmLoader is a library used for loading DLL modules from memory directly. Also, it will bypass the Windows PE loader with processing the import/export table correctly.

[![Build status](https://dev.azure.com/virtable/GitHub-CI/_apis/build/status/mmLoader/build-mmLoader-x86-x64-debug-release)](https://dev.azure.com/virtable/GitHub-CI/_build/latest?definitionId=11)

[DOC](http://tishion.github.io/mmLoader/) | [CI&CD](https://dev.azure.com/virtable/GitHub-CI)

The CI & CD system has been moved to Azure DevOps and mmLoader will not publish more nugget packages.

## How to use

1. Use mmLoader source code:
   - Just include the source files in your projects.

2. Use mmLoader static library
    - Build the projects and collect the static library file, then add reference to it in your projects.

4. Use mmLoader shell code
   - Build project mmLoader-shellcode-generator then run it, collect the generated header file. 
   - Include the header file in your project

## FAQ
Q: Why no dynamic version? 

A: Compiling mmLoader as separated dynamic module is not recommended for some obvious reasons.
