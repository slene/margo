### About this repo

Fork from [GoSublime](https://github.com/DisposaBoy/GoSublime)

Add [liteide](https://github.com/visualfc/liteide) goapi tools instead GoSublime margo Goto Definition

### Usage

build margo

    GOPATH=/project/works/margo:$GOPATH go build -o main src/*.go

copy execute file `main` to Sublime Text Packages directory

in my case i use mac osx:

> just copy `main` to `Packages/User/GoSublime/osx-x64/bin` and rename it to gosublime.margo_xxx.exe. replace xxx to your margo file name

now restart Sublime Text and test Goto Definition

use hotkey [`command + .`,`command + g`] or `command + shift + g`
