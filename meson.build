project('asyncplusplus', ['cpp'])


asyncpp_lib = static_library('asyncpp',
[
'src/scheduler.cpp',
'src/threadpool_scheduler.cpp'
], 
include_directories: ['include'],
cpp_args : ['-DLIBASYNC_STATIC'])

asyncpp_dep = declare_dependency(link_with: asyncpp_lib, include_directories: ['include'], compile_args : ['-DLIBASYNC_STATIC']))