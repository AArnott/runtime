set(SOURCES
  SearchPathA.cpp
)

add_executable(paltest_searchpatha_test1
  ${SOURCES}
)

add_dependencies(paltest_searchpatha_test1 coreclrpal)

target_link_libraries(paltest_searchpatha_test1
  ${COMMON_TEST_LIBRARIES}
)
