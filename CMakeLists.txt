MESSAGE("Start to process y mode")
INCLUDE_DIRECTORIES(includes)
SET(SRCS 
${CMAKE_CURRENT_SOURCE_DIR}/srcs/log.cc
)
ADD_LIBRARY(y STATIC ${SRCS})