# 声明要求的 cmake 最低版本
cmake_minimum_required(VERSION 2.8)

# 声明一个 cmake 工程
project(hello-world)

# 添加一个可执行程序
add_executable(hello-world main.c)