include(FetchContent)

FetchContent_Declare(
  eigen
  GIT_REPOSITORY https://gitlab.com/libeigen/eigen
  GIT_TAG 3147391d946bb4b6c68edd901f2add6ac1f31f8c
)
FetchContent_MakeAvailable(eigen)

