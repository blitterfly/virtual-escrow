add_library(CLIENTLIB client-process.cpp client-ui.cpp)
target_compile_options(CLIENTLIB PUBLIC "-std=c++11")
