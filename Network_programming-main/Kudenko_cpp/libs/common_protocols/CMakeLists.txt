project(common_protocols)

file(GLOB SRC src/*.cpp src/*.cxx)

add_library(${PROJECT_NAME} ${SRC})

target_include_directories(
        ${PROJECT_NAME}
        PUBLIC
        ${PROJECT_SOURCE_DIR}/include
)