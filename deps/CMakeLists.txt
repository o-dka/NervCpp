include(FetchContent)

FetchContent_Declare(
  eigen
  GIT_REPOSITORY https://github.com/PX4/eigen.git 
  GIT_TAG dde02fceedfc1ba09d4d4f71a2b5dafcfcb85491
)
FetchContent_MakeAvailable(eigen)

