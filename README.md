# android-ndk-missing
Android NDK missing functions

## Reference

https://android.googlesource.com/platform/bionic/+/HEAD/docs/status.md

## unistd.h int getdtablesize()

reference: https://www.man7.org/linux/man-pages/man2/getdtablesize.2.html
source: https://android.googlesource.com/platform/bionic/+/72dc1c22dc6a92dea925398c9e3880364ab29c1c/libc/bionic/getdtablesize.c

## spawn.h int posix_spawnp(pid_t* _Nullable __pid, const char* _Nonnull __file, const posix_spawn_file_actions_t _Nullable * _Nullable __actions, const posix_spawnattr_t _Nullable * _Nullable __attr, char* const _Nonnull __argv[_Nonnull], char* const _Nullable __env[_Nullable]) __INTRODUCED_IN(28)

reference: https://pubs.opengroup.org/onlinepubs/9799919799/functions/posix_spawn.html
source:
    - https://android.googlesource.com/platform/bionic/+/master/libc/include/spawn.h
    - https://android.googlesource.com/platform/bionic/+/master/libc/bionic/spawn.cpp
