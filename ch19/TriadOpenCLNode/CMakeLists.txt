# triad_oclNode-subbuff.cpp
add_executable(triad_oclNode-subbuff  triad_oclNode-subbuff.cpp)
target_link_libraries(triad_oclNode-subbuff  PRIVATE TBB::tbb)

# triad_oclPrecomp.cpp
add_executable(triad_oclPrecomp  triad_oclPrecomp.cpp)
target_link_libraries(triad_oclPrecomp  PRIVATE TBB::tbb)

# triad_oclNode.cpp
add_executable(triad_oclNode  triad_oclNode.cpp)
target_link_libraries(triad_oclNode  PRIVATE TBB::tbb)

