cmake_minimum_required(VERSION 3.15)
project(ex4)

set(CMAKE_CXX_STANDARD 14)

SET(CMAKE_CXX_FLAGS -pthread)

add_executable(ex4 main.cpp CacheManager.h ClientHandler.h FileCacheManager.h MySerialServer.h
        MySerialServer.cpp MyTestClientHandler.h MyTestClientHandler.cpp Server.h Solver.h StringReverser.cpp
        StringReverser.h Searchable.h State.h Matrix.h Point.cpp Point.h BestFirstSearch.h
        AStar.h Searcher.h BreadthFirstSearch.h DepthFirstSearch.h MyMatrixClientHandler.h
        MyMatrixClientHandler.cpp MatrixSolver.cpp MatrixSolver.h MyParallelServer.cpp MyParallelServer.h)