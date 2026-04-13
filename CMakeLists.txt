cmake_minimum_required(VERSION 4.2)
project(Leetcode_Solutions)

set(CMAKE_CXX_STANDARD 14)

include_directories("Easy Problems")

add_executable(Leetcode_Solutions
        "Easy Problems/0001-Two Sum/Two Sum Cpp/Solution.cpp"
        "Easy Problems/0009-Palindrome/Palindrome Cpp/Solution.cpp"
        "Easy Problems/0121-Best Time to Buy and Sell Stock/BTB and SS Cpp/Solution.cpp")
