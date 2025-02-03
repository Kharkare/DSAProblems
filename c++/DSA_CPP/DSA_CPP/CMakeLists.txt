# CMakeList.txt : CMake project for DSA_CPP, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (DSA_CPP "DSA_CPP.cpp" "DSA_CPP.h" "test/Medium/Sliding_Window/LongestSubstringNoRepeatTest.cpp"  "test/Medium/Sliding_Window/LongestSubstringNoRepeat.cpp")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET DSA_CPP PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
