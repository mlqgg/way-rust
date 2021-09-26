# way-rust

> rust 是一种<strong>预编译静态类型</strong>语言

## 安装

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## 基础

1. 编译命令: `rustc`
2. `Cargo` 是 Rust 的构建系统和包管理器。(安装 Rust 时会自动被自动安装)
3. Rust 源文件总是以 .rs 拓展名结尾。如果文件名包含多个单词，使用下划线分隔他们。
4. cargo build 命令：构建项目，会将编译产物放到 target/debug 文件夹中
   cargo build --release 能够优化编译项目
   cargo run 可以一步构建并执行项目
   cargo check 能够在不生成二进制文件的情况下检查错误
