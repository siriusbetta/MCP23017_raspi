cmake_minimum_required(VERSION 3.15)
project (mcp23017)
set(SRC "src/MCP23017.cpp")
add_library(${PROJECT_NAME} ${SRC})
