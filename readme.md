# go plus

不好用。

## 编译器 gop

可以转译成 golang 后利用 go 编译生成
也可以生成 igop 的字节码

```bash
# 居然用这种方式安装，也是挺怪的。不知道为什么不和 igop 一样用 go install 安装。
git clone git@github.com:goplus/gop.git
cd gop
all.bat
```

## 解释器 igop

```bash
# 安装
go install github.com/goplus/igop/cmd/igop@latest

# igop 命令信息
igop help [run|build|test|verson|export]
```