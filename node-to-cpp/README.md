## Prerequisite* for node-gyp
<sub>*checked in macOS Ventura 13.2.1 (22D68)</sub>  

**node-gyp** requires *python* binary the execute the build.  
**python** requires *xcode-select* and *xcode* to work with *clang/clang++<sup>Apple</sup>* compiler.  

- Install **xcode** from Apple Store.
- Install **xcode-select** using terminal: `xcode-select --install`<sup>*For every os update repeat this step.</sup>
- Install **pyenv**  using *homebrew*: `arch -x86_64 brew install pyenv`  
- Install **python** using *pyenv*: `arch -x86_64 pyenv install <version>` 
