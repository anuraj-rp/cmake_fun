cmake_minimum_required(VERSION 3.16)
project(cmakeGetHostInfo)

cmake_host_system_information(RESULT BUILD_HOST QUERY HOSTNAME)

message("BUILD_HOST: " ${BUILD_HOST})