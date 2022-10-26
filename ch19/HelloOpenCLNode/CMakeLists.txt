# TwoGPUs.cpp
add_executable(TwoGPUs  TwoGPUs.cpp)
target_link_libraries(TwoGPUs  PRIVATE TBB::tbb)

# ordering-ok.cpp
add_executable(ordering-ok  ordering-ok.cpp)
target_link_libraries(ordering-ok  PRIVATE TBB::tbb)

# devices.cpp
add_executable(devices  devices.cpp)
target_link_libraries(devices  PRIVATE TBB::tbb)

# Hello_ranges2.cpp
add_executable(Hello_ranges2  Hello_ranges2.cpp)
target_link_libraries(Hello_ranges2  PRIVATE TBB::tbb)

# ordering-wrong.cpp
add_executable(ordering-wrong  ordering-wrong.cpp)
target_link_libraries(ordering-wrong  PRIVATE TBB::tbb)

# Hello_ranges-b.cpp
add_executable(Hello_ranges-b  Hello_ranges-b.cpp)
target_link_libraries(Hello_ranges-b  PRIVATE TBB::tbb)

# Hello_OCLNode-gpu.cpp
add_executable(Hello_OCLNode-gpu  Hello_OCLNode-gpu.cpp)
target_link_libraries(Hello_OCLNode-gpu  PRIVATE TBB::tbb)

# Hello_ranges.cpp
add_executable(Hello_ranges  Hello_ranges.cpp)
target_link_libraries(Hello_ranges  PRIVATE TBB::tbb)

# Hello_OCLNode.cpp
add_executable(Hello_OCLNode  Hello_OCLNode.cpp)
target_link_libraries(Hello_OCLNode  PRIVATE TBB::tbb)

