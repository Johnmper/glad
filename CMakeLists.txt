cmake_minimum_required(VERSION 3.5.1)

execute_process(COMMAND python ${CMAKE_CURRENT_SOURCE_DIR}/generator/glad/main.py --profile=core --generator=c --spec=gl --out-path=${CMAKE_CURRENT_SOURCE_DIR}
    WORKING_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/generator/glad/)
