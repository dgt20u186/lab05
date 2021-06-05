cmake_minimum_required(VERSION 3.4)
project(banking)
add_library(Account STATIC Account.h Account.cpp)
add_library(Transaction STATIC Transaction.h Transaction.cpp)
