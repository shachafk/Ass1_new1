cmake_minimum_required(VERSION 3.15)
project(Ass1)

set(CMAKE_CXX_STANDARD 11)
set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra")


add_executable(Ass1 src/main.cpp src/Movie.cpp src/Episode.cpp src/Watchable.cpp src/LengthRecommenderUser src/Session.cpp src/User.cpp include/Session.h include/Watchable.h include/Action.h include/User.h src/BaseAction.cpp src/CreateUser.cpp src/ChangeActiveUser.cpp src/DeleteUser.cpp src/DuplicateUser.cpp src/PrintContentList.cpp src/PrintWatchHistory.cpp src/Watch.cpp src/PrintActionsLog.cpp src/Exit.cpp src/RerunRecommenderUser.cpp src/GenreRecommenderUser.cpp)