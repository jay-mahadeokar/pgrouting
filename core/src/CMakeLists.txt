
SET(LIBRARY_OUTPUT_PATH ../../lib/)
ADD_LIBRARY(routing SHARED dijkstra.c apsp.c boost_wrapper.cpp apsp_boost_wrapper.cpp)
INSTALL(TARGETS routing DESTINATION ${LIBRARY_INSTALL_PATH})


