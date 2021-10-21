cmake_minimum_required(VERSION 3.17)
project(try2)

set(CMAKE_CXX_STANDARD 11)

add_executable(try2 MainTrain.cpp anomaly_detection_util.h anomaly_detection_util.cpp)