set(SOURCES
  setcurrentdirectorya.cpp
)

add_executable(paltest_setcurrentdirectorya_test2
  ${SOURCES}
)

add_dependencies(paltest_setcurrentdirectorya_test2 coreclrpal)

target_link_libraries(paltest_setcurrentdirectorya_test2
  ${COMMON_TEST_LIBRARIES}
)
