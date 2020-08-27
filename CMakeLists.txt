
cmake_minimum_required(VERSION 3.17)
project(VulkanMemoryAllocator C CXX)

add_library(VulkanMemoryAllocator INTERFACE include/VulkanMemoryAllocator/vk_mem_alloc.h)
target_include_directories(VulkanMemoryAllocator INTERFACE include/VulkanMemoryAllocator)

