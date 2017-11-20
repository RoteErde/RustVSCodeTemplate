# Visual Studio Code template for Rust (Windows)

This assumes you have just the vanilla install of Visual Studio Code

Installing Rust

As of 11/20/2017 What works for me is:
1) Rust Nightly
    `rustup install nightly`
    append Path variable in the user profile (yay bug finally fixed for Windows 10)
    PATH: `%USERPROFILE%\.cargo\bin`
2) Visual Studio C++ Build Tools (http://landinghub.visualstudio.com/visual-cpp-build-tools), select the default C++ option
3) Once that has been installed VSCode plugin:
    `Rust (rls)` https://marketplace.visualstudio.com/items?itemName=rust-lang.rust

    `C/C++` https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools

    `Native-Debug` https://marketplace.visualstudio.com/items?itemName=webfreak.debug

4) Clone this repo
Ctrl-Shift+B to build (Rust: Cargo build)
F5 to debug

