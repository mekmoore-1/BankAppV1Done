cmake_minimum_required(VERSION 4.3)
project(BankAppV1)

set(CMAKE_CXX_STANDARD 20)

add_executable(BankAppV1 main.cpp
        BankAccount.cpp
        BankAccount.h
        CheckingAccount.h)
