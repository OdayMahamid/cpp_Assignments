cmake_minimum_required(VERSION 3.16)
project(Assignments)

set(CMAKE_CXX_STANDARD 20)

add_executable(Assignment_1 Ex1/PhoneticFinder.cpp Ex1/PhoneticFinder.hpp Ex1/Test_ofek.cpp Ex1/Test_snir.cpp Ex1/TestRunner.cpp Ex1/doctest.h)
add_executable(Assignment_2  Ex2/FamilyTree.hpp Ex2/FamilyTree.cpp  Ex2/doctest.h  Ex2/Test.cpp Ex2/Test_ariel.cpp Ex2/Test_hila.cpp Ex2/TestRunner.cpp)
add_executable(Assignment_3 Ex3/solver.hpp Ex3/solver.cpp Ex3/doctest.h Ex3/TestRunner.cpp Ex3/Test_iris.cpp Ex3/Test_shahar.cpp )
add_executable(Assignment_4 Ex4/DemoGame.cpp  Ex4/DemoGame.hpp  Ex4/Soldier.cpp Ex4/Soldier.hpp Ex4/FootSoldier.cpp Ex4/FootSoldier.hpp Ex4/FootCommander.cpp Ex4/FootCommander.hpp Ex4/Sniper.cpp Ex4/Sniper.hpp Ex4/SniperCommander.cpp Ex4/SniperCommander.hpp Ex4/Paramedic.cpp Ex4/Paramedic.hpp Ex4/ParamedicCommander.cpp Ex4/ParamedicCommander.hpp Ex4/Attacker.cpp Ex4/Attacker.hpp Ex4/Board.original.cpp Ex4/Board.original.hpp Ex4/TestRunner.cpp  Ex4/Test_oriane_yirat.cpp Ex4/Test_amichai.cpp   Ex4/doctest.h)
add_executable(Assignment_5 Ex5/accumulate.hpp Ex5/range.hpp Ex5/filterfalse.hpp Ex5/compress.hpp Ex5/doctest.h Ex5/Test_snir.cpp Ex5/TestRunner.cpp)