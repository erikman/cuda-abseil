cmake_minimum_required(VERSION 3.10)

project(cuda_abseil CXX CUDA)

add_subdirectory(abseil)

add_executable(cuda_abseil example.cu)
target_link_libraries(cuda_abseil absl::container)
