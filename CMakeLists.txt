cmake_minimum_required(VERSION 3.10)
project(MyProject)

# Добавляем исполняемый файл
add_executable(MyExecutable main.cpp)

# Здесь вы можете добавить другие файлы и библиотеки к вашему проекту

# Пример добавления библиотеки
# find_package(SomeLibrary REQUIRED)
# target_link_libraries(MyExecutable SomeLibrary::SomeLibrary)
