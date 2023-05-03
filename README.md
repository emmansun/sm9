# sm9

[![ci](https://github.com/emmansun/sm9/actions/workflows/ci.yml/badge.svg)](https://github.com/emmansun/sm9/actions/workflows/ci.yml)
[![arm64-qemu](https://github.com/emmansun/sm9/actions/workflows/arm64-qemu.yml/badge.svg)](https://github.com/emmansun/sm9/actions/workflows/arm64-qemu.yml)
![GitHub go.mod Go version (branch)](https://img.shields.io/github/go-mod/go-version/emmansun/sm9)
[![Release](https://img.shields.io/github/release/emmansun/sm9/all.svg)](https://github.com/emmansun/sm9/releases)

 SM9 bn256 1-2-6-12 towering extensions complete reference implementation. GT's Marshal/Unmarshal functions have been converted to 1-2-4-12 format. (当你用本项目实现SM9规范的签名/验签等的时候，就可以忽略1-2-6-12塔式扩域带来的不同)