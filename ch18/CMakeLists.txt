# fig_18_03-alternative.cpp
add_executable(fig_18_03-alternative  fig_18_03-alternative.cpp)
target_link_libraries(fig_18_03-alternative  PRIVATE TBB::tbb)

# fig_18_04.cpp
add_executable(fig_18_04  fig_18_04.cpp)
target_link_libraries(fig_18_04  PRIVATE TBB::tbb)

# fig_18_11.cpp
add_executable(fig_18_11  fig_18_11.cpp)
target_link_libraries(fig_18_11  PRIVATE TBB::tbb)

# fig_18_03.cpp
add_executable(fig_18_03  fig_18_03.cpp)
target_link_libraries(fig_18_03  PRIVATE TBB::tbb)

# fig_18_11-svmCLheader.cpp
add_executable(fig_18_11-svmCLheader  fig_18_11-svmCLheader.cpp)
target_link_libraries(fig_18_11-svmCLheader  PRIVATE TBB::tbb)

# fig_18_11-svm.cpp
add_executable(fig_18_11-svm  fig_18_11-svm.cpp)
target_link_libraries(fig_18_11-svm  PRIVATE TBB::tbb)

# fig_18_11-CLheader.cpp
add_executable(fig_18_11-CLheader  fig_18_11-CLheader.cpp)
target_link_libraries(fig_18_11-CLheader  PRIVATE TBB::tbb)

