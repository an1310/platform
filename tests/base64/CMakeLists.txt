INCLUDE_DIRECTORIES(AFTER ${gtest_SOURCE_DIR}/include)
ADD_EXECUTABLE(platform-base64-test base64_test.cc)
TARGET_LINK_LIBRARIES(platform-base64-test platform gtest gtest_main)
ADD_TEST(platform-base64-test platform-base64-test)
